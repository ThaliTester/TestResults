#### Test 83627337315fde5_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
09-08 14:31:21.718   292   292 E SMD     : DCD OFF
,09-08 14:31:22.638  6636  6636 D AndroidRuntime: 
09-08 14:31:22.638  6636  6636 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-08 14:31:22.648  6636  6636 D AndroidRuntime: CheckJNI is OFF
09-08 14:31:22.648  6636  6636 D AndroidRuntime: readGMSProperty: start
09-08 14:31:22.648  6636  6636 D AndroidRuntime: readGMSProperty: already setted!!
09-08 14:31:22.648  6636  6636 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-08 14:31:22.648  6636  6636 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-08 14:31:22.648  6636  6636 D AndroidRuntime: readGMSProperty: end
09-08 14:31:22.648  6636  6636 D AndroidRuntime: addProductProperty: start
09-08 14:31:22.808  6636  6636 E AffinityControl: AffinityControl: registerfunction enter
09-08 14:31:22.838  6636  6636 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-08 14:31:22.848  1015  1319 E PersonaManagerService: inState():  stateMachine is null !!
09-08 14:31:22.858  1015  1319 I PersonaManagerService: PersonaId don't exist
09-08 14:31:22.858  1015  1319 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-08 14:31:22.858  1015  1319 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
09-08 14:31:22.888  1015  1319 W ActivityManager: mDVFSHelper.acquire()
09-08 14:31:22.888   259   259 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-08 14:31:22.898   259   259 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
09-08 14:31:22.898  1015  1319 D FocusedStackFrame: Set to : 0
09-08 14:31:22.908  1015  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:22.908  1015  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:22.908  1015  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:22.908  1015  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:22.908  1015  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-08 14:31:22.908  1015  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-08 14:31:22.918  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-08 14:31:22.918  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-08 14:31:22.928  6647  6647 E Zygote  : MountEmulatedStorage()
09-08 14:31:22.928  6647  6647 E Zygote  : v2
09-08 14:31:22.928  6647  6647 I libpersona: KNOX_SDCARD checking this for 10171
09-08 14:31:22.928  6647  6647 I libpersona: KNOX_SDCARD not a persona
09-08 14:31:22.928  6647  6647 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 14:31:22.928   259   259 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
09-08 14:31:22.928  1015  1319 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-08 14:31:22.928  1015  1319 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6647 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-08 14:31:22.928  1015  1319 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-08 14:31:22.928  1015  1319 D InputDispatcher: Focused application set to: xxxx
09-08 14:31:22.928  1015  1319 D InputDispatcher: Focus left window: 1481
09-08 14:31:22.938  6647  6647 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 14:31:22.938  6636  6636 D AndroidRuntime: Shutting down VM
09-08 14:31:22.938  6647  6647 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-08 14:31:22.938  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-08 14:31:22.938  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
09-08 14:31:22.948  6647  6647 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 14:31:22.948  6647  6647 D ActivityThread: Added TimaKeyStore provider
09-08 14:31:22.958  1015  1028 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-08 14:31:22.968  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-08 14:31:22.968  1015  1015 V ActivityManager: Display changed displayId=0
09-08 14:31:22.978  1015  1028 D PersonaManager: isKioskContainerExistOnDevice
09-08 14:31:22.988  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-08 14:31:22.998  1015  1330 E Watchdog: !@Sync 3
09-08 14:31:23.018   259  1037 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
09-08 14:31:23.028   259   447 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
09-08 14:31:23.028  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{b0e82b1 token=android.os.BinderProxy@2dd31f20 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-08 14:31:23.028  1481  1481 D Launcher: onTrimMemory. Level: 20
09-08 14:31:23.128  6647  6647 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-08 14:31:23.138  6636  6636 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-08 14:31:23.178  6647  6647 I cr.library_loader: Time to load native libraries: 12 ms (timestamps 8245-8257)
,09-08 14:31:23.178  6647  6647 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-08 14:31:23.208  6647  6647 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bebf9ae}
,09-08 14:31:23.208  6647  6647 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-08 14:31:23.218  6647  6647 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 14:31:23.258  6647  6647 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-08 14:31:23.258  6647  6647 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 14:31:23.268  6647  6647 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 14:31:23.308  6647  6647 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-08 14:31:23.308  6647  6647 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-08 14:31:23.308  6647  6647 I Adreno-EGL: Build Date: 04/06/15 Mon
09-08 14:31:23.308  6647  6647 I Adreno-EGL: Local Branch: 
09-08 14:31:23.308  6647  6647 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-08 14:31:23.308  6647  6647 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-08 14:31:23.308  6647  6647 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-08 14:31:23.388  6647  6647 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 14:31:23.398  6647  6647 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-08 14:31:23.398  6647  6647 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-08 14:31:23.408  6647  6647 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-08 14:31:23.408  6647  6647 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-08 14:31:23.488  1015  1041 W ActivityManager: Activity pause timeout for ActivityRecord{1f1dae37 u0 com.test.thalitest/.MainActivity t2}
,09-08 14:31:23.528  6647  6647 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 14:31:23.538  6647  6647 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-08 14:31:23.548  6647  6647 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-08 14:31:23.548  6647  6647 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-08 14:31:23.558  6647  6647 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-08 14:31:23.568  6647  6647 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 14:31:23.568  6647  6647 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 14:31:23.608  6647  6686 D OpenGLRenderer: Render dirty regions requested: true
,09-08 14:31:23.608  1015  1028 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-08 14:31:23.608  1015  1028 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-08 14:31:23.608  1015  1028 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-08 14:31:23.608  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-08 14:31:23.608  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,09-08 14:31:23.618  6647  6675 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-08 14:31:23.618  6647  6647 V ActivityThread: updateVisibility : ActivityRecord{2cd9e70e token=android.os.BinderProxy@1d7e1ed3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-08 14:31:23.618  6647  6647 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-08 14:31:23.628  6647  6647 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-08 14:31:23.638   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-08 14:31:23.648  1015  1463 D InputDispatcher: Focus entered window: 6647
,09-08 14:31:23.658  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-08 14:31:23.658  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-08 14:31:23.658  6647  6647 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-08 14:31:23.658  6647  6686 I OpenGLRenderer: Initialized EGL, version 1.4
,09-08 14:31:23.658  6647  6686 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-08 14:31:23.658  6647  6686 D OpenGLRenderer: Enabling debug mode 0
,09-08 14:31:23.688  1015  1027 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-08 14:31:23.688  1173  1173 I StatusBar: Icon Only
09-08 14:31:23.688  1173  1173 D PanelView: There is/are notification(s) 
,09-08 14:31:23.698  1015  6692 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-08 14:31:23.708  1015  1046 I ActivityManager: Displayed Component not be shown by security: +721ms (total +799ms)
,09-08 14:31:23.708  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1f1dae37 u0 com.test.thalitest/.MainActivity t2} time:108782
09-08 14:31:23.708  1015  1046 W ActivityManager: mDVFSHelper.release()
,09-08 14:31:23.708  6647  6647 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-08 14:31:23.708   259   451 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-08 14:31:23.708   259   447 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
09-08 14:31:23.708  6647  6647 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1d7e1ed3 time:108786
,09-08 14:31:23.738  1873  1873 I SamsungIME: getCurrentCandidateView
,09-08 14:31:23.758   335   335 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-08 14:31:23.758   335   335 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-08 14:31:23.858  6647  6647 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6647
,09-08 14:31:23.888  1873  1873 D SamsungIME: Dismiss ExpandCandiate
,09-08 14:31:24.028  1873  1873 I SamsungIME: getDebugLevel  : 0x4f4c
,09-08 14:31:24.078  1873  1873 I SamsungIME: getDebugLevel  : 0x4f4c
,09-08 14:31:24.098  1873  1873 I SamsungIME: KeybaordView init() : load resources,
,09-08 14:31:24.138  1873  1873 I SamsungIME: getCurrentKeyboard
,09-08 14:31:24.138  1873  1873 I SamsungIME: getTextKeyboard
,09-08 14:31:24.158  1873  1873 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-08 14:31:24.208  6647  6647 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 14:31:24.278  6647  6694 D jxcore_app_log: JniHelper::setJavaVM(0xb7f322b0), pthread_self() = -1202980368
,09-08 14:31:24.288  6647  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 14:31:24.288  6647  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 14:31:24.288  6647  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 14:31:24.288  6647  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 14:31:24.288  6647  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-08 14:31:24.288  6647  6694 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bd641d4 added. We now have 1 listener(s)
,09-08 14:31:24.288  6647  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,09-08 14:31:24.288  6647  6694 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
09-08 14:31:24.288  6647  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:24.288  6647  6694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 14:31:24.298  6647  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 14:31:24.298  6647  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 14:31:24.298  6647  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 14:31:24.298  6647  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
09-08 14:31:24.298  6647  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 14:31:24.298  6647  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 14:31:24.298  6647  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 14:31:24.298  6647  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 14:31:24.298  6647  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 14:31:24.298  6647  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 14:31:24.298  6647  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 14:31:24.298  6647  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 14:31:24.298  6647  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 14:31:24.298  6647  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-08 14:31:24.298  6647  6694 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@325c62c3 added. We now have 1 listener(s)
09-08 14:31:24.298  6647  6694 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:31:24.298  6647  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:31:24.298  6647  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-08 14:31:24.298  6647  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 14:31:24.298  6647  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 14:31:24.298  6647  6694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-08 14:31:24.308  6647  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:31:24.308  6647  6694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,09-08 14:31:24.318  6647  6694 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-08 14:31:24.318  6647  6694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:24.318  6647  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:24.318  6647  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:24.318  6647  6694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:24.318  6647  6694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:24.318  6647  6694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:24.318  6647  6694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:24.318  6647  6694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:31:24.318  6647  6694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 14:31:24.318  6647  6694 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:31:24.318  6647  6694 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 14:31:24.318  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:24.318  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:24.348  6647  6647 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 14:31:24.718   292   292 E SMD     : DCD OFF
,09-08 14:31:24.898  6647  6702 W jxcore-log: Initializing JXcore engine
09-08 14:31:24.898  6647  6702 W jxcore-log: JXcore engine is ready
,09-08 14:31:24.948  1995  1995 E audit   : type=1400 msg=audit(1473337884.948:205): avc:  denied  { ioctl } for  pid=6702 comm="Thread-1226" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-08 14:31:24.948  1995  1995 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:31:24.948  1995  1995 E audit   : type=1300 msg=audit(1473337884.948:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9e9fb8f8 items=0 ppid=323 ppcomm=main pid=6702 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1226" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-08 14:31:24.948  1995  1995 E audit   : type=1320 msg=audit(1473337884.948:205): 
,09-08 14:31:24.968  6647  6702 W jxcore-log: Starting JXcore engine,
,09-08 14:31:25.068  6647  6702 W jxcore-log: Platform android
09-08 14:31:25.068  6647  6702 W jxcore-log: 
09-08 14:31:25.068  6647  6702 W jxcore-log: Process ARCH arm
09-08 14:31:25.068  6647  6702 W jxcore-log: 
,09-08 14:31:25.278  6647  6702 I jxcore-log: JXcore Cordova bridge is ready!,
09-08 14:31:25.278  6647  6702 I jxcore-log: 
09-08 14:31:25.278  6647  6702 W jxcore-log: JXcore engine is started
,09-08 14:31:25.278  6647  6694 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-08 14:31:25.278  6647  6647 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-08 14:31:27.718   292   292 E SMD     : DCD OFF
,09-08 14:31:27.758  1015  1048 I PowerManagerService: [PWL] Off : 50s ago
,09-08 14:31:27.928  1015  3328 D SSRM:n  : SIOP:: AP = 330,
,09-08 14:31:28.768   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 14:31:29.208  5565  5565 D FactoryTest: Not factory mode
,09-08 14:31:29.208  5565  5565 D FactoryTest: Not factory mode. isFactoryMode() returend false
09-08 14:31:29.208  5565  5565 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
09-08 14:31:29.208  5565  5565 D MTPRx   : still no open session command from host, so toast
,09-08 14:31:29.218  5565  5565 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-08 14:31:29.218  5565  5565 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-08 14:31:29.218  5565  5565 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114296
,09-08 14:31:29.218  1015  1463 E PersonaManagerService: inState():  stateMachine is null !!
,09-08 14:31:29.218  1015  1463 I PersonaManagerService: PersonaId don't exist
09-08 14:31:29.218  1015  1463 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-08 14:31:29.228  1015  1463 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-08 14:31:29.228  1015  1463 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:29.228  1015  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:29.228  1015  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-08 14:31:29.228  1015  1463 W ActivityManager: mDVFSHelper.acquire()
,09-08 14:31:29.248  1015  1463 D PersonaManager: isKioskContainerExistOnDevice
,09-08 14:31:29.258  1015  1463 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-08 14:31:29.258  1015  1463 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-08 14:31:29.258  1015  1463 D InputDispatcher: Focused application set to: xxxx
09-08 14:31:29.258  1015  1463 D InputDispatcher: Focus left window: 6647
,09-08 14:31:29.258  5565  5565 E MTPRx   : started activity for popup
,09-08 14:31:29.268  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-08 14:31:29.268  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-08 14:31:29.288  5565  5565 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-08 14:31:29.288  5565  5565 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-08 14:31:29.288  5565  5565 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-08 14:31:29.288  5565  5565 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 14:31:29.288  5565  5565 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-08 14:31:29.288  5565  5565 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-08 14:31:29.318  5565  5565 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-08 14:31:29.318  1015  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-08 14:31:29.318  1015  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-08 14:31:29.318  1015  1028 D InputDispatcher: Focused application set to: xxxx
,09-08 14:31:29.318  1015  1028 D InputDispatcher: Focus entered window: 6647
,09-08 14:31:29.328  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-08 14:31:29.328  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-08 14:31:29.328  1015  1495 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-08 14:31:29.328  1015  1495 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3b5beb46 attribute=null, token = android.os.BinderProxy@39983096
,09-08 14:31:29.368  5565  5565 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-08 14:31:29.378  5565  5565 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-08 14:31:29.378  5565  5565 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-08 14:31:29.398  6647  6647 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-08 14:31:29.398  6647  6647 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-08 14:31:29.398  6647  6647 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-08 14:31:29.398  6647  6647 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-08 14:31:29.398  1015  1490 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-08 14:31:29.398  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
09-08 14:31:29.398  1015  1490 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-08 14:31:29.398  1015  1490 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-08 14:31:29.398  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-08 14:31:29.418  6647  6647 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 14:31:29.418  6647  6647 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-08 14:31:29.428  6647  6647 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4cede3f Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@39bb4d74, 16908290=android.view.AbsSavedState$1@39bb4d74}, android:focusedViewId=100}]}]
,09-08 14:31:29.428  6647  6647 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-08 14:31:29.428  6647  6647 V ActivityThread: updateVisibility : ActivityRecord{2cd9e70e token=android.os.BinderProxy@1d7e1ed3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-08 14:31:29.428  6647  6647 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-08 14:31:29.428  6647  6647 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-08 14:31:29.428  6647  6647 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1d7e1ed3 time:114506
,09-08 14:31:29.428  1015  1464 D PersonaManager: isKioskContainerExistOnDevice
,09-08 14:31:29.768   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 14:31:30.718   292   292 E SMD     : DCD OFF
,09-08 14:31:30.768   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 14:31:31.128  1015  1463 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-08 14:31:31.128  1015  1463 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-08 14:31:31.128  1015  1463 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-08 14:31:31.128  1015  1463 D BatteryService: stay LED for fully charged
,09-08 14:31:31.128  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-08 14:31:31.128  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-08 14:31:31.128  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-08 14:31:31.138  1015  1015 I MotionRecognitionService: Plugged
09-08 14:31:31.138  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-08 14:31:31.138  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-08 14:31:31.138  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-08 14:31:31.148  3149  3149 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-08 14:31:31.148  3149  3252 D HeadsetStateMachine: Disconnected process message: 10
,09-08 14:31:31.158  1173  1173 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-08 14:31:31.158  1173  1173 D SViewCoverView: level :100 plugged : 2
,09-08 14:31:31.158  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-08 14:31:31.158  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-08 14:31:31.158  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-08 14:31:31.768   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 14:31:32.228  1015  1041 W ActivityManager: mDVFSHelper.release()
,09-08 14:31:32.768   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 14:31:32.958  1015  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,09-08 14:31:33.718   292   292 E SMD     : DCD OFF
,09-08 14:31:33.768   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-08 14:31:34.928  1015  1094 V AlarmManager: waitForAlarm result :4
,09-08 14:31:34.938  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-08 14:31:34.958  1997  1997 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-08 14:31:34.988  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 14:31:34.998  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-08 14:31:34.998  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:34.998  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:34.998  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:35.078  4659  4659 D ConnectivityManager: CallingUid : 10011, CallingPid : 4659
,09-08 14:31:35.078  1015  1319 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-08 14:31:35.078  1015  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-08 14:31:35.078  1015  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
09-08 14:31:35.078  1015  1127 D ConnectivityService: apparently satisfied.  currentScore=60
,09-08 14:31:35.088  4659  6711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-08 14:31:35.138  4659  6712 W DriveInitializer: Background init thread started
,09-08 14:31:35.168   258   548 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-08 14:31:35.168   258   548 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 14:31:35.168  4659  6712 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-08 14:31:35.278  4659  6712 W DriveInitializer: Background init thread ended
,09-08 14:31:35.298  1997  1997 I art     : Explicit concurrent mark sweep GC freed 57934(3MB) AllocSpace objects, 15(240KB) LOS objects, 40% free, 10MB/17MB, paused 1.200ms total 68.305ms
,09-08 14:31:35.318  1015  1327 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 14:31:35.318  1015  1327 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-08 14:31:35.318  1015  1327 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:35.318  1015  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 14:31:35.318  1015  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:35.348  1015  1490 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-08 14:31:35.348  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-08 14:31:35.368  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 14:31:35.368  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-08 14:31:35.368  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:35.368  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:35.368  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:35.418  1997  1997 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-08 14:31:35.438  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:35.438  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:35.438  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:35.518  1015  1495 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 14:31:35.518  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-08 14:31:35.518  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:35.518  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:35.518  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:35.548  1015  1135 I art     : Explicit concurrent mark sweep GC freed 37804(2039KB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 24MB/36MB, paused 2.564ms total 164.535ms
,09-08 14:31:35.568  4659  6720 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
09-08 14:31:35.568  4659  6720 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-08 14:31:35.588  1015  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:35.588  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:35.588  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:35.588  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:35.648  1015  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:35.648  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:35.648  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:35.648  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:35.658  1015  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:35.658  1015  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:35.658  1015  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:35.658  1015  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:35.668  6723  6723 E Zygote  : MountEmulatedStorage(),
09-08 14:31:35.668  6723  6723 E Zygote  : v2
09-08 14:31:35.668  6723  6723 I libpersona: KNOX_SDCARD checking this for 10011
09-08 14:31:35.668  6723  6723 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:35.668  1015  1319 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6723 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-08 14:31:35.678  6723  6723 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-08 14:31:35.678  6723  6723 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-08 14:31:35.678  6723  6723 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-08 14:31:35.698  6723  6723 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:35.698  6723  6723 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:35.708  6723  6723 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-08 14:31:35.708  6723  6723 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-08 14:31:35.748  6723  6723 I MultiDex: VM with version 2.1.0 has multidex support,
09-08 14:31:35.748  6723  6723 I MultiDex: install
09-08 14:31:35.748  6723  6723 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-08 14:31:35.778  6723  6723 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-08 14:31:35.838  6723  6723 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-08 14:31:35.838  6723  6723 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31df89ca: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-08 14:31:35.838  6723  6723 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-08 14:31:35.858  6723  6723 D ChimeraCfgMgr: Reading stored module config
,09-08 14:31:35.898  6723  6737 W art     : Suspending all threads took: 7.549ms
,09-08 14:31:35.918  6723  6737 I art     : Background sticky concurrent mark sweep GC freed 26476(1248KB) AllocSpace objects, 3(133KB) LOS objects, 3% free, 7MB/7MB, paused 12.041ms total 43.116ms
,09-08 14:31:35.948  6723  6723 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-08 14:31:35.948  6723  6723 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-08 14:31:35.958  6723  6740 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-08 14:31:36.058   284   718 D WVCdm   : Instantiating CDM.
,09-08 14:31:36.058   284   284 I WVCdm   : CdmEngine::OpenSession
,09-08 14:31:36.058   284   284 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-08 14:31:36.078   284   284 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-08 14:31:36.098   284   284 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,09-08 14:31:36.138  6723  6733 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,09-08 14:31:36.138  6723  6733 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-08 14:31:36.138  6723  6733 I System.out: (HTTPLog)-Static: isShipBuild true
,09-08 14:31:36.138  6723  6733 I System.out: (HTTPLog)-Thread-1202-489789199: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-08 14:31:36.138  6723  6733 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 14:31:36.148   279   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 14:31:36.148   279   963 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-08 14:31:36.158   284   284 I WVCdm   : CdmEngine::QueryKeyControlInfo,
,09-08 14:31:36.158   284   691 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4),
09-08 14:31:36.158   284   691 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-08 14:31:36.158   284   691 I WVCdm   : CdmEngine::GenerateKeyRequest
09-08 14:31:36.158   284   691 D WVCdm   : PrepareKeyRequest: nonce=1604559545
,09-08 14:31:36.218  6723  6733 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,09-08 14:31:36.218  6723  6733 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6723, getuid(): 10011
,09-08 14:31:36.358  1015  3349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-08 14:31:36.578  6723  6733 I qtaguid : Untagging socket 30
,09-08 14:31:36.718   292   292 E SMD     : DCD OFF,
,09-08 14:31:36.928  6748  6748 I dex2oat : ----------------------------------------------------
09-08 14:31:36.928  6748  6748 I dex2oat : <SS>: S T A R T I N G . . .
09-08 14:31:36.928  6748  6748 I dex2oat : <SS>: Zip is absent. Canceled.
,09-08 14:31:36.928  6748  6748 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-08 14:31:36.978  6748  6748 I dex2oat : dex2oat took 48.674ms (threads: 4)
,09-08 14:31:36.988  6723  6733 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-08 14:31:36.988  6723  6733 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-08 14:31:36.988  6723  6733 I Adreno-EGL: Build Date: 04/06/15 Mon
09-08 14:31:36.988  6723  6733 I Adreno-EGL: Local Branch: 
09-08 14:31:36.988  6723  6733 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-08 14:31:36.988  6723  6733 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-08 14:31:36.988  6723  6733 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-08 14:31:37.308  6723  6733 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-08 14:31:37.308  6723  6733 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-08 14:31:37.308  6723  6733 I Adreno-EGL: Build Date: 04/06/15 Mon
09-08 14:31:37.308  6723  6733 I Adreno-EGL: Local Branch: 
09-08 14:31:37.308  6723  6733 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-08 14:31:37.308  6723  6733 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-08 14:31:37.308  6723  6733 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-08 14:31:37.348  6723  6733 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-08 14:31:37.348  6723  6733 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-08 14:31:37.348  6723  6733 I Adreno-EGL: Build Date: 04/06/15 Mon
09-08 14:31:37.348  6723  6733 I Adreno-EGL: Local Branch: 
09-08 14:31:37.348  6723  6733 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-08 14:31:37.348  6723  6733 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-08 14:31:37.348  6723  6733 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-08 14:31:37.518  1015  1319 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-08 14:31:37.518  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-08 14:31:37.528  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:37.528  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:37.528  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:37.548  1997  6722 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,09-08 14:31:37.548  1997  6722 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-08 14:31:37.548  1997  6722 I System.out: (HTTPLog)-Static: isShipBuild true
09-08 14:31:37.548  1997  6722 I System.out: (HTTPLog)-Thread-267-1051673723: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,09-08 14:31:37.558  1997  6722 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-08 14:31:37.558   279   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 14:31:37.558   279   963 D Netd    : getNetworkForDns: using netid 502 for uid 10011
09-08 14:31:37.558  1997  6722 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-08 14:31:37.558  1997  6722 I qtaguid : Tagging socket 54 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1997, getuid(): 10011
,09-08 14:31:37.598  1997  6722 I qtaguid : Tagging socket 57 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1997, getuid(): 10011
,09-08 14:31:37.698   284   718 I WVCdm   : CdmEngine::CloseSession
,09-08 14:31:37.708   284   718 I WVCdm   : L3 Terminate.
,09-08 14:31:37.748  1015  1135 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 14:31:37.748  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-08 14:31:37.748  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:37.748  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:37.748  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:37.818  1015  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:37.818  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:37.828  1015  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:37.828  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:37.948  1015  3328 D SSRM:n  : SIOP:: AP = 350
,09-08 14:31:37.958  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 14:31:37.958  6647  6702 I jxcore-log: 
,09-08 14:31:37.958  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 14:31:37.958  6647  6702 I jxcore-log: 
,09-08 14:31:37.968  6647  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:37.968  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:37.968  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:37.968  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:37.968  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:37.968  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:37.968  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:37.968  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:31:37.968  6647  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:31:37.978  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 14:31:37.978  6647  6702 I jxcore-log: 
,09-08 14:31:37.978  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 14:31:37.978  6647  6702 I jxcore-log: 
,09-08 14:31:38.168  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-08 14:31:38.178  1015  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:38.178  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:38.178  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:38.178  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:38.188  1015  1463 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:38.188  1015  1463 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:38.188  1015  1463 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:38.188  1015  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:38.228  1997  1997 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=1f32752c-7462-4f61-b638-49cbdec0e261
,09-08 14:31:38.228  1015  1463 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-08 14:31:38.228  1015  1463 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-08 14:31:38.228  1015  1463 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:38.228  1015  1463 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:38.228  1015  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:38.248  1997  1997 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-08 14:31:38.248  1997  1997 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-08 14:31:38.268  1015  1327 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:38.268  1015  1327 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:38.268  1015  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:38.268  1015  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:38.308  4236  4246 I art     : Explicit concurrent mark sweep GC freed 1545(52KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 686us total 22.645ms
,09-08 14:31:38.388  1997  2152 W GCoreFlp: No location to return for getLastLocation()
,09-08 14:31:38.418  1015  1464 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:38.418  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:38.418  1015  1464 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:38.418  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:38.428  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:38.428  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:38.428  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:38.428  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:38.428  4659  6758 D UdcContextInitService: registered all accounts: true
,09-08 14:31:38.428  1015  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:38.428  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:38.428  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:38.428  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:38.458  1997  2156 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-08 14:31:38.478  1997  2175 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-08 14:31:38.538  1015  1495 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 14:31:38.538  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-08 14:31:38.538  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:38.548  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:38.548  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:38.658  1015  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:38.658  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:38.658  1015  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:38.658  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:38.678  1015  1027 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-08 14:31:38.678  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-08 14:31:38.678  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:38.678  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:38.678  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:38.708  1997  2175 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-08 14:31:38.718  1997  2175 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-08 14:31:38.728  1997  6765 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 14:31:38.728   279   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 14:31:38.728   279   963 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-08 14:31:38.728  1997  6765 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-08 14:31:38.728  1997  6765 I qtaguid : Tagging socket 71 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1997, getuid(): 10011
,09-08 14:31:38.768  6647  6702 I jxcore-log: Unit Test app is loaded
09-08 14:31:38.768  6647  6702 I jxcore-log: 
,09-08 14:31:38.768   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 14:31:38.768  1997  6763 I art     : Explicit concurrent mark sweep GC freed 55376(3MB) AllocSpace objects, 10(301KB) LOS objects, 40% free, 11MB/18MB, paused 6.232ms total 103.952ms
09-08 14:31:38.768  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-08 14:31:38.778  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:31:38.778  6647  6702 I jxcore-log: 
,09-08 14:31:38.778  6647  6647 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-08 14:31:38.788  6647  6702 D executeNativeTests: Running unit tests
,09-08 14:31:38.788  6647  6702 D BluetoothAdapter: enable()
,09-08 14:31:38.788  6647  6702 D BluetoothAdapter: enable(): BT is already enabled..!
,09-08 14:31:38.808  1015  1480 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-08 14:31:38.808  1015  1480 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-08 14:31:38.808  1015  1480 D SecContentProvider2: mCursor = null
,09-08 14:31:38.808  1015  1480 D WifiService: setWifiEnabled: true pid=6647, uid=10171
,09-08 14:31:38.808  1015  1480 W ActivityManager: Permission Denial: getCurrentUser() from pid=6647, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-08 14:31:38.808  1015  1762 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:38.808  1015  1762 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:38.808  1015  1762 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:38.808  1997  6765 I qtaguid : Tagging socket 73 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1997, getuid(): 10011
09-08 14:31:38.808  1015  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:38.818  1015  1480 W WifiService: Failed getting userId using ActivityManagerNative
09-08 14:31:38.818  1015  1480 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6647, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-08 14:31:38.818  1015  1480 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-08 14:31:38.818  1015  1480 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-08 14:31:38.818  1015  1480 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-08 14:31:38.818  1015  1480 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-08 14:31:38.818  1015  1480 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-08 14:31:38.818  1015  1480 D SettingsProvider: name = wifi_on
,09-08 14:31:38.868  1015  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:38.868  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:38.868  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:38.868  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:38.868  1997  6773 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-08 14:31:38.868  1997  6763 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-08 14:31:38.868  1015  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:38.868  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:38.868  1015  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:38.868  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:38.898  1015  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:38.898  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:38.898  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:38.898  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:38.898  1997  6773 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-08 14:31:38.898  1997  6763 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-08 14:31:38.898  1015  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:38.898  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:38.898  1015  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:38.898  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:38.928  1015  1135 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:38.928  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:38.928  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:38.928  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:38.928  1997  6773 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-08 14:31:38.928  1997  6763 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-08 14:31:38.928  1997  6763 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-08 14:31:38.938  1997  6763 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-08 14:31:38.968  1015  1027 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-08 14:31:39.008  1997  6763 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 14:31:39.008   279   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 14:31:39.008   279   963 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-08 14:31:39.008  1997  6763 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-08 14:31:39.008  1997  6763 I qtaguid : Tagging socket 77 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1997, getuid(): 10011
,09-08 14:31:39.048  1997  6763 I qtaguid : Tagging socket 80 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1997, getuid(): 10011
,09-08 14:31:39.168  1997  6765 I qtaguid : Untagging socket 71
,09-08 14:31:39.168  1997  2175 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-08 14:31:39.298  1015  1135 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-08 14:31:39.308  1997  6763 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 14:31:39.308  1997  6763 I qtaguid : Tagging socket 77 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1997, getuid(): 10011
,09-08 14:31:39.448  1015  1463 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-08 14:31:39.458  1997  6763 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 14:31:39.458  1997  6763 I qtaguid : Tagging socket 77 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1997, getuid(): 10011
,09-08 14:31:39.588  1015  1135 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-08 14:31:39.598  1997  6763 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 14:31:39.598  1997  6763 I qtaguid : Tagging socket 77 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1997, getuid(): 10011
,09-08 14:31:39.728   292   292 E SMD     : DCD OFF
,09-08 14:31:39.768   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 14:31:40.768   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 14:31:40.838  1997  6766 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 14:31:40.848  1997  6766 I qtaguid : Tagging socket 71 with tag 1000310200000000{268448002,0} for uid 10011, pid: 1997, getuid(): 10011
,09-08 14:31:40.998  1997  6766 I qtaguid : Untagging socket 71
,09-08 14:31:41.008  1997  2175 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-08 14:31:41.038  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-08 14:31:41.188  1015  1327 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-08 14:31:41.188  1015  1327 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-08 14:31:41.188  1015  1327 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-08 14:31:41.198  1015  1327 D BatteryService: stay LED for fully charged
09-08 14:31:41.198  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-08 14:31:41.198  1015  1015 I MotionRecognitionService: Plugged
,09-08 14:31:41.198  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-08 14:31:41.208  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-08 14:31:41.208  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
09-08 14:31:41.208  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-08 14:31:41.208  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-08 14:31:41.218  3149  3149 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-08 14:31:41.218  3149  3252 D HeadsetStateMachine: Disconnected process message: 10
,09-08 14:31:41.228  1173  1173 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-08 14:31:41.228  1173  1173 D SViewCoverView: level :100 plugged : 2
,09-08 14:31:41.238  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-08 14:31:41.238  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-08 14:31:41.238  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-08 14:31:41.778   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 14:31:41.938  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 14:31:41.938  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d added. We now have 2 listener(s)
,09-08 14:31:41.938  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-08 14:31:41.938  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:41.938  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:31:41.938  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:31:41.938  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 added. We now have 2 listener(s)
09-08 14:31:41.938  6647  6702 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:31:41.938  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:31:41.948  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-08 14:31:41.948  6647  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:41.948  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:41.948  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:41.948  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:41.948  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,09-08 14:31:41.948  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:41.948  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:41.948  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:31:41.948  6647  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:31:41.948  6647  6702 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:31:41.948  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:41.958  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:41.958  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 14:31:41.958  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:31:41.958  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 14:31:41.958  6647  6702 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-08 14:31:41.968  6647  6702 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-08 14:31:41.968  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-08 14:31:41.968  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:31:41.968  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 14:31:41.968  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:31:41.968  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:31:41.968  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:41.968  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 14:31:41.968  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d removed from the list
09-08 14:31:41.968  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:41.968  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 removed from the list
,09-08 14:31:41.968  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:41.968  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:41.968  6647  6702 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-08 14:31:41.978  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:41.978  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:41.978  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:41.978  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:41.978  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:41.978  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:41.978  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:41.978  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 14:31:41.978  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:41.978  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:41.978  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:41.978  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:41.978  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:41.978  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
09-08 14:31:41.978  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:41.978  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:41.978  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:41.978  6647  6702 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-08 14:31:41.978  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:41.988  6647  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:41.988  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:41.988  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:41.988  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:41.988  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:41.988  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:41.988  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:41.988  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:31:41.988  6647  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:41.988  6647  6702 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:41.988  6647  6702 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-08 14:31:41.988  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-08 14:31:41.988  6647  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 14:31:41.988  6647  6702 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-08 14:31:41.988  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 14:31:41.988  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:41.988  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 14:31:41.988  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:41.988  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 14:31:41.988  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 14:31:41.988  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 14:31:41.988  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 14:31:41.988  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:41.988  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:31:41.998  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:41.998  6647  6647 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 14:31:41.998  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 14:31:41.998  6647  6779 D BluetoothSocket: bindListen(): myUserId = 0
09-08 14:31:41.998  6647  6779 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:31:42.008  6647  6779 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
09-08 14:31:42.008  6647  6779 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 14:31:42.008  6647  6779 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 14:31:42.008  6647  6779 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28de9b0e
09-08 14:31:42.008  6647  6779 D BluetoothSocket: channel: 6
09-08 14:31:42.008  6647  6779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-08 14:31:42.008  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 14:31:42.018  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 14:31:42.018  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-08 14:31:42.018  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-08 14:31:42.018  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 08 EC A9 50 76 27
09-08 14:31:42.018  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 14:31:42.018  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 14:31:42.018  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-08 14:31:42.028  3149  3161 D BtGatt.GattService: registerClient() - UUID=3e90b437-897e-4958-add3-71fc1a912daa
,09-08 14:31:42.078  3149  3243 D BtGatt.GattService: onClientRegistered() - UUID=3e90b437-897e-4958-add3-71fc1a912daa, clientIf=6,
,09-08 14:31:42.078  6647  6658 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
09-08 14:31:42.078  3149  3249 D BtGatt.AdvertiseManager: message : 0
09-08 14:31:42.078  3149  3249 D BtGatt.AdvertiseManager: number of adv instance running0
09-08 14:31:42.078  3149  3249 D BtGatt.AdvertiseManager: size of list is =0
09-08 14:31:42.078  3149  3249 D BtGatt.AdvertiseManager: starting advertising
09-08 14:31:42.078  3149  3249 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-08 14:31:42.088  3149  3243 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
09-08 14:31:42.088  3149  3249 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 14:31:42.088  3149  3243 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
09-08 14:31:42.088  3149  3249 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-08 14:31:42.088  3149  3249 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-08 14:31:42.088  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 14:31:42.098  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 14:31:42.098  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 14:31:42.098  6647  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 14:31:42.098  6647  6702 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 14:31:42.098  6647  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-08 14:31:42.108  6647  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-08 14:31:42.108  6647  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-08 14:31:42.108  6647  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-08 14:31:42.108  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 14:31:42.108  6647  6647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 14:31:42.108  6647  6647 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 14:31:42.508  1015  1495 I ActivityManager: Killing 6349:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-08 14:31:42.608  6647  6702 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:31:42.608  6647  6702 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 14:31:42.608  6647  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-08 14:31:42.608  6647  6702 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 14:31:42.608  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 14:31:42.608  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 14:31:42.608  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 14:31:42.608  6647  6702 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3b4c1b3c, channel: 6, state: LISTENING
,09-08 14:31:42.608  6647  6702 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3b4c1b3c, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28de9b0e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3c1c10c5mSocket: android.net.LocalSocket@226d5a1a impl:android.net.LocalSocketImpl@41f794b fd:FileDescriptor[106]
09-08 14:31:42.608  6647  6702 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@226d5a1a impl:android.net.LocalSocketImpl@41f794b fd:FileDescriptor[106],
09-08 14:31:42.608  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 14:31:42.608  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 14:31:42.608  6647  6779 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3b4c1b3c, channel: 6, state: CLOSED
09-08 14:31:42.608  6647  6779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 14:31:42.608  6647  6779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 14:31:42.608  6647  6779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 14:31:42.608  6647  6647 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 14:31:42.608  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 14:31:42.608  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:31:42.608  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:31:42.608  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:31:42.608  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 14:31:42.608  6647  6702 D BluetoothLeScanner: could not find callback wrapper
09-08 14:31:42.608  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 14:31:42.608  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-08 14:31:42.618  3149  3249 D BtGatt.AdvertiseManager: message : 1
09-08 14:31:42.618  3149  3249 D BtGatt.AdvertiseManager: stop advertise for client 6
09-08 14:31:42.618  3149  3249 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
09-08 14:31:42.618  3149  3249 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-08 14:31:42.618  3149  3243 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-08 14:31:42.618  3149  3243 D BtGatt.GattService: Client app is not null!
,09-08 14:31:42.628  3149  3161 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-08 14:31:42.628  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 14:31:42.628  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-08 14:31:42.628  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-08 14:31:42.628  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-08 14:31:42.628  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 14:31:42.638  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:31:42.638  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 14:31:42.638  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 14:31:42.638  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:31:42.638  6647  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 14:31:42.638  6647  6647 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:31:42.638  6647  6647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-08 14:31:42.638  6647  6647 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-08 14:31:42.648  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:31:42.648  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:31:42.648  6647  6647 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:31:42.648  6647  6702 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-08 14:31:42.648  6647  6702 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-08 14:31:42.648  6647  6702 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-08 14:31:42.648  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-08 14:31:42.648  6647  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 14:31:42.648  6647  6702 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-08 14:31:42.648  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 14:31:42.648  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:31:42.648  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-08 14:31:42.648  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-08 14:31:42.648  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 14:31:42.648  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-08 14:31:42.648  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 14:31:42.648  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:42.648  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 14:31:42.658  6647  6647 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-08 14:31:42.658  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 14:31:42.668  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 14:31:42.668  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:31:42.668  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-08 14:31:42.668  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-08 14:31:42.668  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 08 EC A9 50 76 27
,09-08 14:31:42.668  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 14:31:42.668  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-08 14:31:42.668  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-08 14:31:42.668  3149  3244 D BtGatt.GattService: registerClient() - UUID=6cd6514d-fb7b-4392-8e68-fed90c38e809
,09-08 14:31:42.678  6647  6783 D BluetoothSocket: bindListen(): myUserId = 0
09-08 14:31:42.678  6647  6783 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:31:42.678  6647  6783 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
,09-08 14:31:42.678  6647  6783 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 14:31:42.678  6647  6783 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-08 14:31:42.678  6647  6783 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b6a5f27
09-08 14:31:42.678  6647  6783 D BluetoothSocket: channel: 6
,09-08 14:31:42.678  6647  6783 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-08 14:31:42.718  3149  3243 D BtGatt.GattService: onClientRegistered() - UUID=6cd6514d-fb7b-4392-8e68-fed90c38e809, clientIf=6
,09-08 14:31:42.718  6647  6655 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-08 14:31:42.718  3149  3249 D BtGatt.AdvertiseManager: message : 0
,09-08 14:31:42.718  3149  3249 D BtGatt.AdvertiseManager: number of adv instance running0
,09-08 14:31:42.718  3149  3249 D BtGatt.AdvertiseManager: size of list is =0
,09-08 14:31:42.718  3149  3249 D BtGatt.AdvertiseManager: starting advertising
,09-08 14:31:42.718  3149  3249 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-08 14:31:42.728   292   292 E SMD     : DCD OFF
,09-08 14:31:42.728  3149  3243 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-08 14:31:42.738  3149  3249 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 14:31:42.738  3149  3243 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-08 14:31:42.738  3149  3249 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-08 14:31:42.738  3149  3249 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-08 14:31:42.738  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 14:31:42.738  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 14:31:42.748  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 14:31:42.748  6647  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 14:31:42.748  6647  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-08 14:31:42.748  6647  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-08 14:31:42.748  6647  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-08 14:31:42.748  6647  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-08 14:31:42.748  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 14:31:42.758  6647  6702 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 14:31:42.758  6647  6647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 14:31:42.758  6647  6647 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 14:31:42.778   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 14:31:43.258  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:31:43.258  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 14:31:43.258  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 14:31:43.258  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 14:31:43.258  6647  6702 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@47295d4, channel: 6, state: LISTENING
,09-08 14:31:43.258  6647  6702 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@47295d4, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b6a5f27, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@468937dmSocket: android.net.LocalSocket@d251272 impl:android.net.LocalSocketImpl@1a93c6c3 fd:FileDescriptor[105]
09-08 14:31:43.258  6647  6702 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d251272 impl:android.net.LocalSocketImpl@1a93c6c3 fd:FileDescriptor[105]
09-08 14:31:43.258  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:31:43.258  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 14:31:43.258  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
,09-08 14:31:43.258  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:43.258  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:31:43.258  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:31:43.258  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:31:43.258  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 14:31:43.258  6647  6702 D BluetoothLeScanner: could not find callback wrapper
09-08 14:31:43.258  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 14:31:43.258  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-08 14:31:43.258  6647  6647 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-08 14:31:43.258  6647  6647 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-08 14:31:43.258  6647  6783 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@47295d4, channel: 6, state: CLOSED
09-08 14:31:43.258  6647  6783 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 14:31:43.258  6647  6783 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 14:31:43.258  6647  6783 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-08 14:31:43.258  3149  3249 D BtGatt.AdvertiseManager: message : 1
,09-08 14:31:43.258  3149  3249 D BtGatt.AdvertiseManager: stop advertise for client 6,
09-08 14:31:43.258  3149  3249 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
09-08 14:31:43.258  3149  3249 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-08 14:31:43.268  3149  3243 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-08 14:31:43.268  3149  3243 D BtGatt.GattService: Client app is not null!
,09-08 14:31:43.278  3149  3244 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-08 14:31:43.278  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 14:31:43.278  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-08 14:31:43.278  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-08 14:31:43.278  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-08 14:31:43.278  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 14:31:43.278  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:31:43.278  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 14:31:43.278  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 14:31:43.278  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:31:43.288  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 14:31:43.288  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 14:31:43.288  6647  6647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-08 14:31:43.288  6647  6647 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:31:43.288  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
,09-08 14:31:43.288  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:43.288  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:43.288  6647  6702 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-08 14:31:43.298  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:31:43.298  6647  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:43.298  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:43.298  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:43.298  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:43.298  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:43.298  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:43.298  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:43.298  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:31:43.298  6647  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:31:43.298  6647  6702 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:31:43.308  6647  6702 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-08 14:31:43.308  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-08 14:31:43.308  6647  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 14:31:43.308  6647  6702 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-08 14:31:43.308  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 14:31:43.308  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:31:43.308  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 14:31:43.308  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 14:31:43.308  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 14:31:43.308  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 14:31:43.308  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 14:31:43.308  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:43.308  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 14:31:43.308  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:43.308  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 14:31:43.318  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:43.318  6647  6647 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-08 14:31:43.318  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 14:31:43.318  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:31:43.328  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-08 14:31:43.328  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-08 14:31:43.328  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 08 EC A9 50 76 27
,09-08 14:31:43.328  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-08 14:31:43.328  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 14:31:43.328  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-08 14:31:43.328  3149  3163 D BtGatt.GattService: registerClient() - UUID=9730b047-c5a9-480f-a575-2c1e7b56f464
,09-08 14:31:43.328  6647  6786 D BluetoothSocket: bindListen(): myUserId = 0
,09-08 14:31:43.328  6647  6786 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:31:43.338  6647  6786 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
,09-08 14:31:43.338  6647  6786 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 14:31:43.338  6647  6786 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 14:31:43.338  6647  6786 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@346acb6c
09-08 14:31:43.338  6647  6786 D BluetoothSocket: channel: 6
09-08 14:31:43.338  6647  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-08 14:31:43.368  3149  3243 D BtGatt.GattService: onClientRegistered() - UUID=9730b047-c5a9-480f-a575-2c1e7b56f464, clientIf=6
,09-08 14:31:43.378  6647  6658 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-08 14:31:43.378  3149  3249 D BtGatt.AdvertiseManager: message : 0
,09-08 14:31:43.378  3149  3249 D BtGatt.AdvertiseManager: number of adv instance running0
,09-08 14:31:43.378  3149  3249 D BtGatt.AdvertiseManager: size of list is =0
,09-08 14:31:43.378  3149  3249 D BtGatt.AdvertiseManager: starting advertising
,09-08 14:31:43.378  3149  3249 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-08 14:31:43.388  3149  3243 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-08 14:31:43.388  3149  3249 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 14:31:43.388  3149  3243 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-08 14:31:43.398  3149  3249 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-08 14:31:43.398  3149  3249 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-08 14:31:43.398  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 14:31:43.398  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 14:31:43.398  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 14:31:43.398  6647  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 14:31:43.398  6647  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-08 14:31:43.398  6647  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-08 14:31:43.398  6647  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-08 14:31:43.398  6647  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-08 14:31:43.408  6647  6702 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 14:31:43.408  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 14:31:43.408  6647  6647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 14:31:43.408  6647  6647 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 14:31:43.778   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-08 14:31:43.908  6647  6702 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:31:43.908  6647  6702 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 14:31:43.908  6647  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-08 14:31:43.908  6647  6702 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 14:31:43.908  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 14:31:43.908  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 14:31:43.908  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 14:31:43.908  6647  6702 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1cfbb535, channel: 6, state: LISTENING
09-08 14:31:43.908  6647  6702 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1cfbb535, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@346acb6c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@24607dcamSocket: android.net.LocalSocket@37a54b3b impl:android.net.LocalSocketImpl@38ef3258 fd:FileDescriptor[105]
09-08 14:31:43.908  6647  6702 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@37a54b3b impl:android.net.LocalSocketImpl@38ef3258 fd:FileDescriptor[105]
,09-08 14:31:43.908  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:31:43.908  6647  6786 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1cfbb535, channel: 6, state: CLOSED
09-08 14:31:43.908  6647  6786 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 14:31:43.908  6647  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 14:31:43.908  6647  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-08 14:31:43.908  6647  6647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 14:31:43.908  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-08 14:31:43.908  6647  6647 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-08 14:31:43.908  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 14:31:43.908  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 14:31:43.908  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:31:43.908  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 14:31:43.908  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 14:31:43.908  6647  6702 D BluetoothLeScanner: could not find callback wrapper
,09-08 14:31:43.908  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 14:31:43.908  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-08 14:31:43.918  3149  3249 D BtGatt.AdvertiseManager: message : 1
,09-08 14:31:43.918  3149  3249 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-08 14:31:43.918  3149  3249 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-08 14:31:43.918  3149  3249 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-08 14:31:43.928  3149  3243 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-08 14:31:43.928  3149  3243 D BtGatt.GattService: Client app is not null!
,09-08 14:31:43.928  3149  3163 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-08 14:31:43.928  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 14:31:43.928  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-08 14:31:43.928  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-08 14:31:43.928  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-08 14:31:43.928  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 14:31:43.928  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:31:43.928  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 14:31:43.928  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 14:31:43.938  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-08 14:31:43.938  6647  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:31:43.938  6647  6647 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:31:43.938  6647  6647 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-08 14:31:43.938  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:31:43.938  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-08 14:31:43.938  6647  6647 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:31:43.938  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:31:43.948  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.948  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:43.948  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:43.948  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:43.948  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
09-08 14:31:43.948  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:43.948  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:43.948  6647  6702 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-08 14:31:43.948  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:31:43.948  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.948  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:43.948  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:43.948  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:31:43.948  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
09-08 14:31:43.948  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:31:43.948  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.948  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:43.948  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-08 14:31:43.948  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:31:43.948  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.948  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:43.948  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:43.958  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:43.958  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
09-08 14:31:43.958  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:43.958  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.958  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:43.958  6647  6702 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-08 14:31:43.958  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:31:43.958  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.958  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:43.958  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:43.958  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:43.958  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
,09-08 14:31:43.958  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:43.958  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.958  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:43.958  6647  6702 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-08 14:31:43.958  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:43.958  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:31:43.958  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:43.958  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:43.958  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:31:43.958  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
,09-08 14:31:43.958  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:43.958  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.958  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:43.958  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 14:31:43.968  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:31:43.968  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 14:31:43.968  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:31:43.968  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 14:31:43.968  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 14:31:43.968  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:43.968  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.968  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:43.968  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:43.968  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:31:43.968  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:43.968  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.968  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:43.968  6647  6702 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 14:31:43.968  6647  6702 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-08 14:31:43.968  6647  6702 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 14:31:43.968  6647  6702 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310],
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 14:31:43.968  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 14:31:43.968  6647  6702 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-08 14:31:43.968  6647  6702 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-08 14:31:43.968  6647  6702 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 14:31:43.968  6647  6702 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:31:43.968  6647  6702 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 14:31:43.968  6647  6702 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 14:31:43.968  6647  6702 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:31:43.968  6647  6702 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 14:31:43.968  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-08 14:31:43.968  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-08 14:31:43.978  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-08 14:31:43.978  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-08 14:31:43.978  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 14:31:43.978  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-08 14:31:43.978  6647  6702 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-08 14:31:43.978  6647  6702 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
09-08 14:31:43.978  6647  6702 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 14:31:43.978  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:43.978  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.978  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:43.978  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-08 14:31:43.978  6647  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1327)
09-08 14:31:43.978  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:43.978  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:43.978  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
09-08 14:31:43.978  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:43.978  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.978  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-08 14:31:43.978  6647  6702 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-08 14:31:43.978  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:43.978  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.978  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:43.978  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:43.978  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:43.978  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
09-08 14:31:43.978  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:43.978  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.978  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:43.978  6647  6791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1327
,09-08 14:31:43.978  6647  6702 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-08 14:31:43.978  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:43.978  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.978  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:43.978  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:43.978  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:43.978  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
09-08 14:31:43.978  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:43.978  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.978  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:43.978  6647  6702 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 14:31:43.978  6647  6702 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 14:31:43.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 14:31:43.978  6647  6702 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-08 14:31:43.978  6647  6702 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 14:31:43.978  6647  6702 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-08 14:31:43.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-08 14:31:43.978  6647  6702 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 14:31:43.978  6647  6702 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 14:31:43.978  6647  6702 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 14:31:43.978  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 14:31:43.978  6647  6702 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 14:31:43.978  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:43.978  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.978  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:43.978  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:43.978  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:31:43.978  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
09-08 14:31:43.978  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:43.978  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:43.978  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:43.978  6647  6702 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-08 14:31:43.978  6647  6790 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-08 14:31:43.978  6647  6790 D BluetoothSocket: connect(): myUserId = 0
09-08 14:31:43.978  6647  6790 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:31:43.978  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:31:43.988  3149  3161 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:43.988  6647  6790 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,09-08 14:31:43.988  6647  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-08 14:31:43.988  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:43.988  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:43.988  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:43.988  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:43.988  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:43.988  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:43.988  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:31:43.988  6647  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:31:43.988  6647  6702 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:43.998  6647  6702 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-08 14:31:43.998  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-08 14:31:43.998  6647  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 14:31:43.998  6647  6702 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-08 14:31:43.998  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-08 14:31:43.998  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:31:43.998  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 14:31:43.998  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 14:31:43.998  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 14:31:43.998  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 14:31:43.998  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 14:31:43.998  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:31:43.998  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 14:31:43.998  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:43.998  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 14:31:43.998  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:43.998  6647  6647 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-08 14:31:44.008  6647  6792 D BluetoothSocket: bindListen(): myUserId = 0
09-08 14:31:44.008  6647  6792 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:31:44.008  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 14:31:44.008  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:31:44.008  6647  6792 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
09-08 14:31:44.008  6647  6792 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 14:31:44.008  6647  6792 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 14:31:44.008  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-08 14:31:44.008  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-08 14:31:44.008  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 08 EC A9 50 76 27
09-08 14:31:44.008  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 14:31:44.008  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-08 14:31:44.008  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-08 14:31:44.008  6647  6792 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@6511c04
09-08 14:31:44.008  6647  6792 D BluetoothSocket: channel: 6
09-08 14:31:44.008  6647  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-08 14:31:44.008  3149  3244 D BtGatt.GattService: registerClient() - UUID=4786dfaf-35c1-4855-9f92-483873a77d91
,09-08 14:31:44.048  3149  3243 D BtGatt.GattService: onClientRegistered() - UUID=4786dfaf-35c1-4855-9f92-483873a77d91, clientIf=6
09-08 14:31:44.048  6647  6655 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-08 14:31:44.058  3149  3249 D BtGatt.AdvertiseManager: message : 0
,09-08 14:31:44.058  3149  3249 D BtGatt.AdvertiseManager: number of adv instance running0
09-08 14:31:44.058  3149  3249 D BtGatt.AdvertiseManager: size of list is =0
,09-08 14:31:44.058  3149  3249 D BtGatt.AdvertiseManager: starting advertising,
,09-08 14:31:44.058  3149  3249 D BtGatt.AdvertiseManager: isStandardAdvfalse
09-08 14:31:44.058  3149  3243 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
09-08 14:31:44.058  3149  3249 D BtGatt.AdvertiseManager: starting multi advertising
09-08 14:31:44.058  3149  3243 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0,
09-08 14:31:44.058  3149  3249 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
09-08 14:31:44.058  3149  3249 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-08 14:31:44.058  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-08 14:31:44.058  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 14:31:44.058  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
09-08 14:31:44.068  6647  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 14:31:44.068  6647  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-08 14:31:44.068  6647  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-08 14:31:44.068  6647  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-08 14:31:44.068  6647  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-08 14:31:44.068  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-08 14:31:44.068  6647  6702 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 14:31:44.068  6647  6647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-08 14:31:44.068  6647  6647 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 14:31:44.568  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:31:44.568  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 14:31:44.568  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 14:31:44.568  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 14:31:44.568  6647  6702 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3882fc22, channel: 6, state: LISTENING
09-08 14:31:44.568  6647  6702 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3882fc22, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@6511c04, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ce3e6b3mSocket: android.net.LocalSocket@1ec5f470 impl:android.net.LocalSocketImpl@296363e9 fd:FileDescriptor[105]
,09-08 14:31:44.568  6647  6702 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1ec5f470 impl:android.net.LocalSocketImpl@296363e9 fd:FileDescriptor[105]
09-08 14:31:44.568  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:31:44.568  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 14:31:44.568  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:44.568  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:31:44.568  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:31:44.568  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:31:44.568  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:31:44.568  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 14:31:44.568  6647  6792 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3882fc22, channel: 6, state: CLOSED
,09-08 14:31:44.568  6647  6792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 14:31:44.568  6647  6792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 14:31:44.568  6647  6792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 14:31:44.568  6647  6647 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-08 14:31:44.568  6647  6647 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-08 14:31:44.568  6647  6702 D BluetoothLeScanner: could not find callback wrapper
09-08 14:31:44.568  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 14:31:44.568  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-08 14:31:44.568  3149  3249 D BtGatt.AdvertiseManager: message : 1
,09-08 14:31:44.568  3149  3249 D BtGatt.AdvertiseManager: stop advertise for client 6
09-08 14:31:44.568  3149  3249 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-08 14:31:44.578  3149  3249 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-08 14:31:44.578  3149  3243 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-08 14:31:44.578  3149  3243 D BtGatt.GattService: Client app is not null!
,09-08 14:31:44.578  3149  3161 D BtGatt.GattService: unregisterClient() - clientIf=6
09-08 14:31:44.578  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 14:31:44.578  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED,
,09-08 14:31:44.578  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-08 14:31:44.578  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-08 14:31:44.578  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 14:31:44.578  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:31:44.578  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 14:31:44.578  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:31:44.578  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:44.588  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 14:31:44.588  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:31:44.588  6647  6647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 14:31:44.588  6647  6647 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:31:44.588  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
09-08 14:31:44.588  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:31:44.588  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:44.588  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:31:44.588  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:44.588  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:44.588  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:44.588  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:31:44.588  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
09-08 14:31:44.588  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:44.588  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:44.588  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:44.588  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-08 14:31:44.588  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:31:44.588  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 14:31:44.588  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 14:31:44.588  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 14:31:44.588  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 14:31:44.588  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 14:31:44.598  6647  6647 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 14:31:44.598  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:44.598  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 14:31:44.598  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 14:31:44.598  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 14:31:44.598  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:44.598  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 14:31:44.598  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:44.598  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:44.598  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:31:44.598  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:31:44.598  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:31:44.598  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:44.598  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:44.598  6647  6796 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 14:31:44.598  6647  6796 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 14:31:44.598  6647  6647 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-08 14:31:44.598  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:31:44.598  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:31:44.598  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:31:44.598  6647  6647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-08 14:31:44.598  6647  6647 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:31:44.598  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
09-08 14:31:44.598  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:44.598  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:44.598  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:44.598  6647  6702 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-08 14:31:44.598  6647  6702 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 14:31:44.598  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 14:31:44.598  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:31:44.598  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:44.598  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:31:44.598  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:44.598  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:44.598  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:44.598  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
09-08 14:31:44.598  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:44.598  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:44.598  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:44.608  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:31:44.608  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:44.608  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:44.608  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:44.608  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:44.608  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
09-08 14:31:44.608  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:44.608  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:44.608  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:44.608  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:44.608  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:44.608  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:44.608  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fd4d0d not in the list
09-08 14:31:44.608  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:44.608  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b61f4c2 not in the list
09-08 14:31:44.608  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:44.608  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:31:44.608  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:44.608  6647  6702 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-08 14:31:44.608  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-08 14:31:44.608  6647  6702 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 14:31:44.608  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-08 14:31:44.608  6647  6702 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 14:31:44.608  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-08 14:31:44.618  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-08 14:31:44.618  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-08 14:31:44.618  6647  6702 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-08 14:31:44.618  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 14:31:44.618  6647  6702 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-08 14:31:44.618  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 14:31:44.618  6647  6702 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 14:31:44.618  6647  6702 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-08 14:31:44.618  6647  6702 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-08 14:31:44.618  6647  6702 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-08 14:31:44.618  6647  6702 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-08 14:31:44.618  6647  6702 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 14:31:44.618  6647  6702 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 14:31:44.618  6647  6702 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-08 14:31:44.628  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 14:31:44.628  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@232c3b0f added. We now have 2 listener(s)
,09-08 14:31:44.628  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-08 14:31:44.628  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:44.628  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 14:31:44.628  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:31:44.628  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@306de79c added. We now have 2 listener(s)
,09-08 14:31:44.628  6647  6702 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:31:44.628  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:31:44.628  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:31:44.638  6647  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:44.638  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:44.638  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:44.638  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:44.638  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:44.638  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:44.638  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:44.638  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:31:44.638  6647  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-08 14:31:44.638  6647  6702 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:31:44.638  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:44.648  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:44.648  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:44.648  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:44.648  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:31:44.648  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@232c3b0f removed from the list
09-08 14:31:44.648  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:44.648  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@306de79c removed from the list
,09-08 14:31:44.648  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:44.648  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:44.648  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:44.648  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:31:44.648  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16fbed7a added. We now have 2 listener(s)
,09-08 14:31:44.648  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-08 14:31:44.648  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:44.648  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 14:31:44.648  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:31:44.648  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fb792b added. We now have 2 listener(s)
09-08 14:31:44.648  6647  6702 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:31:44.648  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:31:44.658  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:31:44.658  6647  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:44.658  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:44.658  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:44.658  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:44.658  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:44.658  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:44.658  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:44.658  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:31:44.658  6647  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-08 14:31:44.658  6647  6702 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:31:44.658  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:44.658  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:44.658  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:44.658  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 14:31:44.658  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16fbed7a removed from the list
09-08 14:31:44.658  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:44.658  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31fb792b removed from the list
09-08 14:31:44.658  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:44.668  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:31:44.668  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:44.668  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:31:44.668  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e1aa721 added. We now have 2 listener(s)
,09-08 14:31:44.668  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-08 14:31:44.668  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:44.668  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 14:31:44.668  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:31:44.668  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14cb6746 added. We now have 2 listener(s)
,09-08 14:31:44.668  6647  6702 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:31:44.668  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:31:44.678  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:31:44.678  6647  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:44.678  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:44.678  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:44.678  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:44.678  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:44.678  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:44.678  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:44.678  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:31:44.678  6647  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:31:44.678  6647  6702 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:31:44.678  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:44.688  1015  1463 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-08 14:31:44.688  1015  1463 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-08 14:31:44.688  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:44.688  1015  1463 D SecContentProvider2: mCursor = null
,09-08 14:31:44.688  1015  1463 D WifiService: setWifiEnabled: false pid=6647, uid=10171
,09-08 14:31:44.688  1015  1463 D SettingsProvider: name = wifi_on
,09-08 14:31:44.698  1015  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 14:31:44.698  1334  1334 I wpa_supplicant: reset timer : RESET_TIMER 0
09-08 14:31:44.698  1334  1334 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-08 14:31:44.698  1334  1334 I wpa_supplicant: P2P: Current p2p state = IDLE
09-08 14:31:44.698  1334  1334 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-08 14:31:44.708  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:31:44.718  1015  1125 E WifiNative-wlan0: do suspend true,
,09-08 14:31:45.098  6647  6647 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,09-08 14:31:45.268  1015  1124 D WifiP2pService: InactiveState{ what=143375 },
09-08 14:31:45.268  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-08 14:31:45.268  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:31:45.268  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-08 14:31:45.268  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.278  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.278  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.278  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:45.278   279   967 D CommandListener: Clearing all IP addresses on wlan0
09-08 14:31:45.278  1997  3008 V NativeCrypto: Read error: ssl=0xb84299b0: I/O error during system call, Connection timed out
,09-08 14:31:45.288  1997  3008 V NativeCrypto: SSL shutdown failed: ssl=0xb84299b0: I/O error during system call, Broken pipe
,09-08 14:31:45.288  1997  3008 E GCM     : Wifi connection closed with errorCode 20
09-08 14:31:45.288  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:31:45.288  1015  1127 E ConnectivityService: updateNetworkInfo()
09-08 14:31:45.288  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
09-08 14:31:45.288  1015  1135 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,09-08 14:31:45.308  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:45.308  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
09-08 14:31:45.308  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:45.308  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-08 14:31:45.308  1015  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-11ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.308  1015  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-11ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.308  1015  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-08 14:31:45.308  1015  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.308  1015  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-08 14:31:45.308  1015  1748 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-08 14:31:45.308  1015  1748 I qtaguid : Tagging socket 325 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
09-08 14:31:45.308  1015  1748 I qtaguid : Untagging socket 325
09-08 14:31:45.308  1015  1748 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-08 14:31:45.318  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-08 14:31:45.318  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:45.318  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:45.318  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:45.338  6801  6801 E Zygote  : MountEmulatedStorage()
,09-08 14:31:45.338  6801  6801 E Zygote  : v2
09-08 14:31:45.338  6801  6801 I libpersona: KNOX_SDCARD checking this for 10102
09-08 14:31:45.338  6801  6801 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:45.338  6801  6801 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:31:45.338  1015  1041 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6801 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-08 14:31:45.348  6801  6801 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:31:45.348  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-08 14:31:45.348  6801  6801 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-08 14:31:45.358  1015  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 14:31:45.358  1015  1124 D WifiP2pService: InactiveState{ what=131204 }
09-08 14:31:45.358  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:31:45.358  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
09-08 14:31:45.358  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 14:31:45.358  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.358  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.358  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.358  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:45.368  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
09-08 14:31:45.368  1015  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.368  1015  1015 D RttService: SCAN_AVAILABLE : 1
09-08 14:31:45.368  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-08 14:31:45.368  1015  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.368  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:31:45.368  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
09-08 14:31:45.368  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-08 14:31:45.368  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-08 14:31:45.378  1015  1124 D WifiP2pService: P2pDisablingState
,09-08 14:31:45.378  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
09-08 14:31:45.378  1015  1124 D WifiP2pService: p2p socket connection lost
09-08 14:31:45.378  1015  1124 D WifiP2pService: P2pDisabledState
09-08 14:31:45.378  1015  1125 E WifiNative-wlan0: do suspend true
,09-08 14:31:45.378  6801  6801 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:45.378  6801  6801 D ActivityThread: Added TimaKeyStore provider
09-08 14:31:45.378  1015  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-08 14:31:45.378  1015  1124 D WifiP2pService: DefaultState{ what=143375 }
,09-08 14:31:45.388  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-08 14:31:45.388  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-08 14:31:45.388  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.388  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.388  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.388  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:45.388   279   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 14:31:45.388   279   963 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-08 14:31:45.388   279   967 D CommandListener: Clearing all IP addresses on wlan0
,09-08 14:31:45.388  1015  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-08 14:31:45.398  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:45.398  1015  1127 V NetworkStats: updateIfacesLocked()
09-08 14:31:45.398  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
09-08 14:31:45.398  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-08 14:31:45.398  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
09-08 14:31:45.398  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-08 14:31:45.398  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 14:31:45.398  1015  1046 D WifiDisplayController: disconnect
09-08 14:31:45.398  1015  1046 D WifiDisplayController: updateConnection
09-08 14:31:45.398  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 14:31:45.398  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-08 14:31:45.398  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
09-08 14:31:45.398  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-08 14:31:45.398  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
09-08 14:31:45.398  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:31:45.398  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-08 14:31:45.398  1015  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-08 14:31:45.398  1015  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-08 14:31:45.398  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 14:31:45.398  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-08 14:31:45.398  1334  1334 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-08 14:31:45.408  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:31:45.408  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 14:31:45.408  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.408  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.408  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.408  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:45.408  1015  1127 V NetworkStats: performPollLocked() took 14ms
09-08 14:31:45.408  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:45.408  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-08 14:31:45.408  1015  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-08 14:31:45.408  1015  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:45.408  4659  6711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-08 14:31:45.418  1173  1672 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-08 14:31:45.418  1015  1762 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-08 14:31:45.418  1015  1127 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-08 14:31:45.418  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-08 14:31:45.418  1015  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-08 14:31:45.418  1015  1125 D SecContentProvider2: mCursor = null
09-08 14:31:45.418  1015  1127 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-08 14:31:45.418  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-08 14:31:45.418  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-08 14:31:45.418  1455  1455 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:31:45.418  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-08 14:31:45.418  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-08 14:31:45.418  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE,
09-08 14:31:45.428  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:31:45.428  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-08 14:31:45.428  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.428  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.428  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.428  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:45.428  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:31:45.428  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 14:31:45.428  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-08 14:31:45.428  1173  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-08 14:31:45.428  1173  1173 D HotspotTile: onReceive : 0, 0
,09-08 14:31:45.428  1299  1299 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:31:45.428  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:45.428  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:45.438  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-08 14:31:45.438  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-08 14:31:45.438  1015  1130 D Tethering: MasterInitialState.processMessage what=3
,09-08 14:31:45.438  6801  6801 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-08 14:31:45.438  1015  1127 D ConnectivityService: nai.networkMonitor.doQuit()
09-08 14:31:45.438  1015  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-08 14:31:45.438  1015  1122 V NetworkStats: updateIfacesLocked()
09-08 14:31:45.438  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:45.438  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
09-08 14:31:45.438  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:31:45.438  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 14:31:45.438  1015  1127 E ConnectivityService: updateNetworkInfo()
09-08 14:31:45.438  1015  1127 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-08 14:31:45.438  1015  1127 E ConnectivityService: updateNetworkInfo()
09-08 14:31:45.438  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:31:45.438  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-08 14:31:45.438  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-08 14:31:45.438  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-08 14:31:45.438  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-08 14:31:45.438  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-08 14:31:45.438  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-08 14:31:45.438  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-08 14:31:45.438  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:45.438  1015  1122 V NetworkStats: performPollLocked() took 4ms
,09-08 14:31:45.448  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:45.448  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:45.448  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:45.448  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:31:45.448  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:45.448  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:45.448  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:45.448  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:31:45.448  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:45.448  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:45.448  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:45.448  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:45.448  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-08 14:31:45.448  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
09-08 14:31:45.448  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-08 14:31:45.458  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
09-08 14:31:45.458  6647  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:45.458  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-08 14:31:45.458  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal,
09-08 14:31:45.458  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 14:31:45.458  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-08 14:31:45.458  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.458  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.458  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:45.458  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:45.458  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:45.458  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:45.458  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:45.458  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:31:45.458  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:45.458  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:45.458  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:45.458  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:31:45.468  6647  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:31:45.468  1334  1334 I wpa_supplicant: Blacklist: Clear (all) 
,09-08 14:31:45.508  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:31:45.508  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:31:45.518  1334  1334 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-08 14:31:45.518  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 14:31:45.518  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-08 14:31:45.518  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-08 14:31:45.518  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:31:45.518  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:31:45.518  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,09-08 14:31:45.518  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:31:45.518  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:31:45.518  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:31:45.528  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:31:45.528  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:31:45.528  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:31:45.528  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 14:31:45.528  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,09-08 14:31:45.528  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 14:31:45.528  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,09-08 14:31:45.528  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:31:45.528  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:31:45.528  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:31:45.528  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,09-08 14:31:45.538  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:31:45.538  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,09-08 14:31:45.538  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:31:45.538  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:31:45.538  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:31:45.538  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:31:45.538  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:31:45.538  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:31:45.548  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:31:45.548  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:31:45.548  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:31:45.598  1334  1334 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-08 14:31:45.598  1334  1334 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-08 14:31:45.598  1334  1334 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-08 14:31:45.598  1334  1334 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-08 14:31:45.598  1334  1334 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-08 14:31:45.598  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,09-08 14:31:45.598  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-08 14:31:45.598  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-08 14:31:45.598  1015  1130 D Tethering: InitialState.processMessage what=4
,09-08 14:31:45.608  1015  1130 E Tethering: No numeric data
,09-08 14:31:45.608  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 14:31:45.608  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 14:31:45.608  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 14:31:45.608  1015  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 14:31:45.608  1015  1130 D Tethering: clearTetheredNotification()
09-08 14:31:45.608  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
09-08 14:31:45.608  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:45.608  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,09-08 14:31:45.608  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 14:31:45.608  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-08 14:31:45.608  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-08 14:31:45.608  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:31:45.608  1173  1173 D HotspotTile: updateTetherState():false, false
09-08 14:31:45.608  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 14:31:45.608  1015  1122 V NetworkStats: performPollLocked() took 4ms
,09-08 14:31:45.608  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:45.608  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:45.618  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:45.658   274   274 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb83bd7c8
09-08 14:31:45.658   274   274 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,09-08 14:31:45.658   274   274 I rmt_storage: wakelock acquired: 1, error no: 42
09-08 14:31:45.658   274   311 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1204038344)
,09-08 14:31:45.688  6801  6841 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-08 14:31:45.688  6801  6841 I Babel_SMS: MmsConfig.loadMmsSettings
,09-08 14:31:45.688  6801  6841 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-08 14:31:45.688  6801  6841 I Babel_SMS: MmsConfig.loadFromDatabase
,09-08 14:31:45.688   274   311 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
09-08 14:31:45.688   274   311 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-08 14:31:45.688   274   311 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1204038344) wakelock released: 1, error no: 0
09-08 14:31:45.688   274   311 I rmt_storage: 
,09-08 14:31:45.698   274   274 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb83bd7c8
,09-08 14:31:45.708  1015  1028 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-08 14:31:45.708  1015  1028 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-08 14:31:45.708  1015  1028 D SecContentProvider2: mCursor = null
,09-08 14:31:45.708  1015  1028 D WifiService: setWifiEnabled: true pid=6647, uid=10171
09-08 14:31:45.708  1015  1028 W ActivityManager: Permission Denial: getCurrentUser() from pid=6647, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-08 14:31:45.708  1015  1028 W WifiService: Failed getting userId using ActivityManagerNative
09-08 14:31:45.708  1015  1028 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6647, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-08 14:31:45.708  1015  1028 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-08 14:31:45.708  1015  1028 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-08 14:31:45.708  1015  1028 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-08 14:31:45.708  1015  1028 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-08 14:31:45.708  1015  1028 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-08 14:31:45.708  1015  1028 D SettingsProvider: name = wifi_on
,09-08 14:31:45.708  6801  6841 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-08 14:31:45.708  6801  6841 I Babel_SMS: MmsConfig.loadFromResources
,09-08 14:31:45.708  6801  6841 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-08 14:31:45.718  6801  6841 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-08 14:31:45.728   292   292 E SMD     : DCD OFF
,09-08 14:31:45.728  1015  1495 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-08 14:31:45.728  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-08 14:31:45.738  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:45.738  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 14:31:45.738  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-08 14:31:45.748  6801  6801 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:31:45.768  6801  6801 I Babel_Crash: startup - clean
,09-08 14:31:45.828  1334  1334 I wpa_supplicant: Blacklist: Clear (all) 
09-08 14:31:45.828  1015  1327 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 14:31:45.828  1015  1327 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 14:31:45.828  1015  1327 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:45.828  1015  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:45.828  1015  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 14:31:45.828  1603  1603 I Hs20UtilService: Starting #8
,09-08 14:31:45.828  1603  1640 I Hs20UtilService: Message received 5007
,09-08 14:31:45.838  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 14:31:45.838  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 14:31:45.838  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 14:31:45.848  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-08 14:31:45.848  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 14:31:45.848  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 14:31:45.848  1299  2233 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 14:31:45.858  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-08 14:31:45.858  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 14:31:45.858  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 14:31:45.858  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-08 14:31:45.858  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 14:31:45.858  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 14:31:45.858  1299  2233 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 14:31:45.868  1015  1135 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-08 14:31:45.868  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:45.868  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:45.868  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:45.868  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:45.868  6801  6801 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:31:45.868  6801  6801 W AudioCapabilities: Unsupported mime audio/evrc
,09-08 14:31:45.878  6801  6801 W AudioCapabilities: Unsupported mime audio/qcelp
,09-08 14:31:45.878  6801  6801 W AudioCapabilities: Unsupported mime audio/mpeg-L1,
09-08 14:31:45.878  6801  6801 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-08 14:31:45.878  6801  6801 W AudioCapabilities: Unsupported mime audio/x-ms-wma,
09-08 14:31:45.878  6801  6801 W AudioCapabilities: Unsupported mime audio/x-ima
,09-08 14:31:45.878  6801  6801 W AudioCapabilities: Unsupported mime audio/qcelp
,09-08 14:31:45.878  6801  6801 W AudioCapabilities: Unsupported mime audio/evrc
,09-08 14:31:45.888  6846  6846 E Zygote  : MountEmulatedStorage(),
09-08 14:31:45.888  6846  6846 E Zygote  : v2
09-08 14:31:45.888  6846  6846 I libpersona: KNOX_SDCARD checking this for 10064
,09-08 14:31:45.888  6846  6846 I libpersona: KNOX_SDCARD not a persona
09-08 14:31:45.888  1015  1135 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6846 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:31:45.888  6846  6846 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 14:31:45.888  6801  6801 W VideoCapabilities: Unsupported mime video/wvc1
,09-08 14:31:45.888  6801  6801 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-08 14:31:45.898  6846  6846 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-08 14:31:45.898  6846  6846 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 14:31:45.908  6801  6801 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-08 14:31:45.908  1334  1334 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-08 14:31:45.908   323   323 I art     : Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 23.908ms
09-08 14:31:45.908  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 14:31:45.908  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-08 14:31:45.908  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 14:31:45.918  6801  6801 W VideoCapabilities: Unsupported mime video/wvc1
09-08 14:31:45.918  6801  6801 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-08 14:31:45.918  6801  6801 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
09-08 14:31:45.918  6801  6801 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
09-08 14:31:45.928  6801  6801 W VideoCapabilities: Unsupported mime video/mp43,
,09-08 14:31:45.928  6801  6801 W VideoCapabilities: Unsupported mime video/sorenson
,09-08 14:31:45.928   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 17.360ms
,09-08 14:31:45.928  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:45.938  6801  6801 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-08 14:31:45.938  6846  6846 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:45.938  6846  6846 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:45.938  1015  1015 I ApplicationPolicy: updateDataUsageMap
,09-08 14:31:45.948   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 16.379ms
,09-08 14:31:45.948  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:45.958  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:45.958  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:45.958  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:45.958  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:31:45.958  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:45.958  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:45.958  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:45.958  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:31:45.968  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:45.968  6801  6801 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-08 14:31:45.978  6846  6846 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-08 14:31:45.988  6801  6801 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:31:45.998  6801  6801 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:31:45.998  6801  6801 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:31:45.998  6846  6846 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 14:31:45.998  6801  6801 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 14:31:46.008  6846  6846 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-08 14:31:46.008  1015  1464 I ActivityManager: Killing 6245:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-08 14:31:46.008  6801  6801 I vclib   : onServiceConnected
,09-08 14:31:46.018  6801  6801 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:31:46.018  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-08 14:31:46.018  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-08 14:31:46.018  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:31:46.018  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-08 14:31:46.018  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:46.018  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:46.018  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:46.018  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:46.018  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 14:31:46.018  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-08 14:31:46.018  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 14:31:46.018  1173  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-08 14:31:46.028  1997  2162 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:31:46.028  1173  1173 D HotspotTile: onReceive : 1, 0
,09-08 14:31:46.028  1299  1299 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:31:46.028  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:46.028  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:46.038  6846  6846 D FileShare-Client: Outbound.stopDelayTimer - 
,09-08 14:31:46.038  1015  1762 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-08 14:31:46.038  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.038  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.038  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.038  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.048  6861  6861 E Zygote  : MountEmulatedStorage(),
,09-08 14:31:46.048  6861  6861 E Zygote  : v2
09-08 14:31:46.058  6861  6861 I libpersona: KNOX_SDCARD checking this for 10065
,09-08 14:31:46.058  6861  6861 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:46.058  6861  6861 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:31:46.058  6861  6861 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-08 14:31:46.058  1015  1762 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6861 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:31:46.058  6861  6861 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 14:31:46.058  1015  1762 I ActivityManager: Killing 6381:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,09-08 14:31:46.078  6861  6861 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:46.078  6861  6861 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:46.108  6861  6861 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 14:31:46.118  1015  1027 I ActivityManager: Killing 6433:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,09-08 14:31:46.118  1015  1464 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 14:31:46.118  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 14:31:46.118  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:46.118  1015  1464 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:46.118  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 14:31:46.128  1603  1603 I Hs20UtilService: Starting #9
,09-08 14:31:46.128  1603  1640 I Hs20UtilService: Message received 5007
,09-08 14:31:46.128  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 14:31:46.128  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 14:31:46.128  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 14:31:46.128  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-08 14:31:46.128  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 14:31:46.128  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 14:31:46.128  1299  2233 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 14:31:46.138  1015  1490 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 14:31:46.138  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 14:31:46.138  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:46.138  1015  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:46.138  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 14:31:46.138  1603  1603 I Hs20UtilService: Starting #10
,09-08 14:31:46.138  1603  1640 I Hs20UtilService: Message received 5011
,09-08 14:31:46.138  1015  1762 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-08 14:31:46.138  1015  1762 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.receivers.NetworkReceiver}
09-08 14:31:46.138  1015  1762 W BroadcastQueue: android.os.TransactionTooLargeException
09-08 14:31:46.138  1015  1762 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 14:31:46.138  1015  1762 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 14:31:46.138  1015  1762 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-08 14:31:46.138  1015  1762 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-08 14:31:46.138  1015  1762 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-08 14:31:46.138  1015  1762 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-08 14:31:46.138  1015  1762 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-08 14:31:46.138  1015  1762 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-08 14:31:46.138  1015  1762 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-08 14:31:46.138  1015  1762 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-08 14:31:46.148  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.148  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.148  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.148  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.158  1015  1762 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6877 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-08 14:31:46.158  6877  6877 E Zygote  : MountEmulatedStorage()
09-08 14:31:46.158  6877  6877 E Zygote  : v2
09-08 14:31:46.158  6877  6877 I libpersona: KNOX_SDCARD checking this for 1000
09-08 14:31:46.158  6877  6877 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:46.158  6877  6877 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-08 14:31:46.168  6877  6877 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-08 14:31:46.168  6877  6877 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 14:31:46.188  1015  1040 W libprocessgroup: failed to open /acct/uid_1000/pid_6433/cgroup.procs: No such file or directory
,09-08 14:31:46.198  6877  6877 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:46.198  6877  6877 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:46.228  6877  6877 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-08 14:31:46.228  6877  6877 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-08 14:31:46.228  6877  6877 D SecurityLogAgent: StateMachine : Current State = 1
,09-08 14:31:46.228  6877  6877 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 14:31:46.238  1015  1135 I ActivityManager: Killing 6411:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-08 14:31:46.238  1015  1762 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:46.238  1015  1762 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:46.238  1015  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:31:46.388  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:46.388  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:46.388  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:31:46.388  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:46.388  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:46.388  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:31:46.398  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:46.398  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:46.398  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:31:46.398  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:46.398  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:46.398  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:31:46.398  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:46.398  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:46.398  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:31:46.398  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:46.398  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:46.398  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:31:46.408  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:46.408  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:46.408  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:31:46.408  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:46.408  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:46.408  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:31:46.408  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:46.408  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:46.408  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:31:46.418  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:46.418  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 14:31:46.418  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:31:46.418  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:46.418  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 14:31:46.428  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:31:46.428  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:46.428  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 14:31:46.428  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:31:46.428  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:46.438  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 14:31:46.438  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:31:46.438  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:46.438  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 14:31:46.438  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:31:46.448  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-08 14:31:46.448  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.448  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.448  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.448  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.468  6893  6893 E Zygote  : MountEmulatedStorage(),
,09-08 14:31:46.468  6893  6893 E Zygote  : v2
,09-08 14:31:46.468  6893  6893 I libpersona: KNOX_SDCARD checking this for 1000
09-08 14:31:46.468  6893  6893 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:46.468  6893  6893 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:31:46.468  6893  6893 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-08 14:31:46.478  6893  6893 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-08 14:31:46.478  1015  1015 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6893 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-08 14:31:46.498  6893  6893 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:46.498  6893  6893 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:46.528  6893  6893 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-08 14:31:46.528  6893  6893 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-08 14:31:46.528  6893  6893 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-08 14:31:46.548  6893  6893 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-08 14:31:46.548  6893  6893 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-08 14:31:46.548  6893  6893 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-08 14:31:46.548  6893  6893 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE,
,09-08 14:31:46.558  1015  1495 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,09-08 14:31:46.558  1015  1495 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-08 14:31:46.558  6893  6908 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
09-08 14:31:46.558  1015  1495 I ActivityManager: Killing 6459:com.samsung.android.sm/1000 (adj 15): empty #21
,09-08 14:31:46.568  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-08 14:31:46.568  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.568  1797  1797 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-08 14:31:46.578  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.578  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.578  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.588  1015  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6910 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-08 14:31:46.588  6910  6910 E Zygote  : MountEmulatedStorage()
09-08 14:31:46.588  6910  6910 I libpersona: KNOX_SDCARD checking this for 10121
09-08 14:31:46.588  6910  6910 E Zygote  : v2
09-08 14:31:46.588  6910  6910 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:46.588  6910  6910 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:31:46.588  1015  1762 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-08 14:31:46.598  6910  6910 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-08 14:31:46.598  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.598  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.598  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.598  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.598  6910  6910 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 14:31:46.608  6910  6910 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:46.618  6910  6910 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:46.618  6924  6924 E Zygote  : MountEmulatedStorage(),
,09-08 14:31:46.618  6924  6924 E Zygote  : v2,
09-08 14:31:46.628  6924  6924 I libpersona: KNOX_SDCARD checking this for 10031
09-08 14:31:46.628  6924  6924 I libpersona: KNOX_SDCARD not a persona
09-08 14:31:46.628  1015  1762 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6924 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
09-08 14:31:46.628  6924  6924 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:31:46.628  6924  6924 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:31:46.628  6924  6924 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 14:31:46.638  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-08 14:31:46.638  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.638  1836  1849 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
09-08 14:31:46.638  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.638  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.638  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.648  6910  6910 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 14:31:46.648  6910  6910 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-08 14:31:46.648  6910  6910 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-08 14:31:46.658  6936  6936 E Zygote  : MountEmulatedStorage(),
09-08 14:31:46.658  6936  6936 E Zygote  : v2
09-08 14:31:46.658  6936  6936 I libpersona: KNOX_SDCARD checking this for 10001
09-08 14:31:46.658  6936  6936 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:46.658  6936  6936 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 14:31:46.658  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6936 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:31:46.668  1797  1797 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-08 14:31:46.668  1797  1797 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-08 14:31:46.668  1797  1797 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-08 14:31:46.668  1797  1797 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-08 14:31:46.668  6936  6936 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-08 14:31:46.678  6936  6936 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 14:31:46.678  6910  6910 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:46.678  6910  6910 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
09-08 14:31:46.678  1797  1797 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-08 14:31:46.688  6924  6924 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:46.688  1015  1043 D Tethering: interfaceRemoved wlan0
09-08 14:31:46.688  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
09-08 14:31:46.688  6924  6924 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:46.688  1797  1797 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-08 14:31:46.688  1015  1464 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-08 14:31:46.688  6910  6910 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-08 14:31:46.688  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.688  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.688  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.688  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.708  6950  6950 E Zygote  : MountEmulatedStorage()
09-08 14:31:46.708  6950  6950 E Zygote  : v2
,09-08 14:31:46.708  6950  6950 I libpersona: KNOX_SDCARD checking this for 10077
09-08 14:31:46.708  6950  6950 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:46.708  6950  6950 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:31:46.708  6950  6950 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 14:31:46.708  1015  1464 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6950 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:31:46.708  1015  1464 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
09-08 14:31:46.708  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.708  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.708  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.708  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.718  6950  6950 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-08 14:31:46.738  6966  6966 E Zygote  : MountEmulatedStorage()
09-08 14:31:46.738  6966  6966 E Zygote  : v2
09-08 14:31:46.738  6966  6966 I libpersona: KNOX_SDCARD checking this for 10141
09-08 14:31:46.738  6966  6966 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:46.738  6966  6966 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:31:46.738  1015  1464 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6966 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-08 14:31:46.738  6936  6936 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:46.738  6936  6936 D ActivityThread: Added TimaKeyStore provider
09-08 14:31:46.738  6966  6966 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:31:46.738  6966  6966 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 14:31:46.748  1015  1464 I ActivityManager: Killing 6482:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-08 14:31:46.758  6950  6950 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:46.758  6950  6950 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:46.768  1015  1043 D Tethering: interfaceRemoved p2p0
,09-08 14:31:46.768  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-08 14:31:46.778  6966  6966 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:46.778  6966  6966 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:46.808  6966  6966 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-08 14:31:46.808  6966  6966 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 14:31:46.808  6966  6966 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 14:31:46.808  6924  6924 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-08 14:31:46.808  6966  6966 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-08 14:31:46.808  1015  1027 I ActivityManager: Killing 6497:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,09-08 14:31:46.828  1015  1463 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-08 14:31:46.828  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.828  2744  6985 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
09-08 14:31:46.828  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.828  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.828  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.828  2744  6985 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-08 14:31:46.838  2744  6985 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-08 14:31:46.838  2744  6985 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-08 14:31:46.838  2744  6985 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-08 14:31:46.838  6986  6986 E Zygote  : MountEmulatedStorage()
,09-08 14:31:46.838  6986  6986 I libpersona: KNOX_SDCARD checking this for 10032
,09-08 14:31:46.838  6986  6986 E Zygote  : v2
09-08 14:31:46.838  6986  6986 I libpersona: KNOX_SDCARD not a persona
09-08 14:31:46.838  6986  6986 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 14:31:46.848  1015  1463 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6986 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:31:46.848  6986  6986 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-08 14:31:46.848  6986  6986 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-08 14:31:46.878  1015  1490 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 14:31:46.878  6986  6986 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:46.878  6986  6986 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:46.898  1015  1464 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 14:31:46.908  1015  1135 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-08 14:31:46.918  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.918  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.918  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.918  1015  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:46.938  1015  1135 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7008 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-08 14:31:46.938  1015  1135 I ActivityManager: Killing 6513:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
09-08 14:31:46.938  7008  7008 E Zygote  : MountEmulatedStorage()
09-08 14:31:46.938  7008  7008 I libpersona: KNOX_SDCARD checking this for 1000
09-08 14:31:46.938  7008  7008 E Zygote  : v2
09-08 14:31:46.938  7008  7008 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:46.948  7008  7008 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:31:46.948  7008  7008 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:31:46.948  7008  7008 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 14:31:46.978  6986  7023 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-08 14:31:46.978  6986  7023 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version,
,09-08 14:31:46.978  7008  7008 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:46.978  7008  7008 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:46.988  6986  7023 D SPPClientService: PushLog.txt file is not deleted.
09-08 14:31:46.988  6986  7023 D SPPClientService: PushLog.txt file is not deleted.
09-08 14:31:46.988  6986  7023 D SPPClientService: ============PushLog. stop!
,09-08 14:31:46.998  6986  6986 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-08 14:31:46.998  1015  1327 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-08 14:31:46.998  1015  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.998  1015  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.998  1015  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:46.998  1015  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:47.008  1015  1027 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 14:31:47.018  7028  7028 E Zygote  : MountEmulatedStorage()
09-08 14:31:47.018  7028  7028 E Zygote  : v2
09-08 14:31:47.018  7028  7028 I libpersona: KNOX_SDCARD checking this for 10036
09-08 14:31:47.018  7028  7028 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:47.028  7028  7028 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 14:31:47.028  1015  1327 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7028 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:31:47.028  7028  7028 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:31:47.028  7028  7028 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-08 14:31:47.038  1015  1327 I ActivityManager: Killing 6442:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-08 14:31:47.038  1015  1463 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 14:31:47.038  1015  1464 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-08 14:31:47.038  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
09-08 14:31:47.038  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:47.038  1015  1464 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-08 14:31:47.038  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-08 14:31:47.058   323   323 I art     : Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 718us total 28.250ms
,09-08 14:31:47.058  7028  7028 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:47.058  7028  7028 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:47.068  7008  7008 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-08 14:31:47.078   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 17.002ms,
,09-08 14:31:47.098   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 800us total 19.222ms,
,09-08 14:31:47.108  1015  1475 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-08 14:31:47.108  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:47.108  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:47.108  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:47.108  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:47.118  1015  1480 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 14:31:47.128  1015  1463 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 14:31:47.138  1015  1475 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7049 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,09-08 14:31:47.138  7049  7049 E Zygote  : MountEmulatedStorage()
09-08 14:31:47.138  7049  7049 I libpersona: KNOX_SDCARD checking this for 10068
09-08 14:31:47.138  7049  7049 E Zygote  : v2
09-08 14:31:47.138  7049  7049 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:47.148  7049  7049 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:31:47.148  7049  7049 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 14:31:47.148  7049  7049 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-08 14:31:47.168  6986  7041 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-08 14:31:47.168  1015  1495 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-08 14:31:47.168  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-08 14:31:47.168  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:47.168  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:47.168  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-08 14:31:47.168  1015  1495 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-08 14:31:47.178  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:47.178  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:47.178  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:47.178  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:47.178  7028  7028 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@8ba05d6
,09-08 14:31:47.178  7049  7049 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:47.178  7049  7049 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:47.188  1015  1135 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 14:31:47.198  1015  1027 D RCPManagerService: exchangeData() failure , invalid userId,
,09-08 14:31:47.198  7065  7065 E Zygote  : MountEmulatedStorage()
09-08 14:31:47.198  7065  7065 I libpersona: KNOX_SDCARD checking this for 10110
09-08 14:31:47.198  7065  7065 E Zygote  : v2
09-08 14:31:47.198  7065  7065 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:47.198  7065  7065 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-08 14:31:47.208  7065  7065 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 14:31:47.208  1015  1495 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7065 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 14:31:47.208  7028  7028 I SA      : [SSP] onCreated
,09-08 14:31:47.208  7065  7065 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-08 14:31:47.208  1015  1319 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-08 14:31:47.208  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
09-08 14:31:47.208  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:47.208  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:47.208  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-08 14:31:47.218  1015  1464 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-08 14:31:47.218  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:47.218  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:47.218  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:47.218  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:47.228  7077  7077 E Zygote  : MountEmulatedStorage()
09-08 14:31:47.228  7077  7077 I libpersona: KNOX_SDCARD checking this for 10009
09-08 14:31:47.228  7077  7077 E Zygote  : v2
09-08 14:31:47.228  7077  7077 I libpersona: KNOX_SDCARD not a persona
09-08 14:31:47.228  7077  7077 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:31:47.228  1015  1464 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7077 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,09-08 14:31:47.228  1015  1464 I ActivityManager: Killing 6528:com.qualcomm.timeservice/1000 (adj 15): empty #21
,09-08 14:31:47.238  1015  1464 I ActivityManager: Killing 5980:com.android.mms/u0a41 (adj 15): empty #21
,09-08 14:31:47.238  7077  7077 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:31:47.238  7065  7065 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 14:31:47.238  6801  7064 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-08 14:31:47.238  7077  7077 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-08 14:31:47.238  7065  7065 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:47.248  6966  7009 W art     : Verification of void com.android.email.activity.MessageListItemOuterContainer.updateContainerLayout(boolean) took 111.971ms
,09-08 14:31:47.258  1015  1480 I ActivityManager: Killing 6557:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,09-08 14:31:47.268  7077  7077 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:47.268  7077  7077 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:47.268  7049  7049 D BadgeProvider: onCreate
09-08 14:31:47.268  7049  7049 D BadgeProvider: DatabaseHelper
,09-08 14:31:47.268  7028  7028 I SA      : [TPM] There is no property file
,09-08 14:31:47.278  7028  7028 I SA      : [SCU] isHaveSA() - false
,09-08 14:31:47.278  7028  7028 I SA      : [TPM] getModelProperty : null
,09-08 14:31:47.278  7028  7028 I SA      : [TPM] getCSCProperty : null
,09-08 14:31:47.288  7028  7028 I SA      : [DM] FLOATING AMOLED FEATURE: true
,09-08 14:31:47.288  7028  7028 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-08 14:31:47.288  7028  7028 I SA      : [DM] TFT FEATURE: false
,09-08 14:31:47.288  7028  7028 I SA      : [DM] init START
,09-08 14:31:47.288  7008  7008 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-08 14:31:47.298  7028  7028 I SA      : [DM] This device is not a Vodafone
,09-08 14:31:47.298  7008  7008 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-08 14:31:47.308  7008  7008 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:47.308  7008  7008 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-08 14:31:47.308  7008  7008 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-08 14:31:47.308  7008  7008 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-08 14:31:47.378  1015  1464 D CountryDetector: No listener is left
,09-08 14:31:47.378  1015  1028 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-08 14:31:47.428  1015  1762 I art     : Explicit concurrent mark sweep GC freed 54437(3MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 24MB/36MB, paused 2.451ms total 153.292ms
,09-08 14:31:47.438  1015  1327 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-08 14:31:47.438  7028  7028 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-08 14:31:47.438  7028  7028 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
09-08 14:31:47.438  7028  7028 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-08 14:31:47.438  7028  7028 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
09-08 14:31:47.438  7028  7028 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-08 14:31:47.438  7028  7028 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-08 14:31:47.438  7028  7028 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-08 14:31:47.438  7028  7028 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-08 14:31:47.438  7049  7057 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-08 14:31:47.438  7028  7028 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-08 14:31:47.438  7028  7028 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-08 14:31:47.438  7028  7028 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
09-08 14:31:47.438  7028  7028 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
09-08 14:31:47.438  7028  7028 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-08 14:31:47.448  1015  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:47.448  1015  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:47.448  1015  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:47.448  7028  7028 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
09-08 14:31:47.448  1015  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:47.448  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
09-08 14:31:47.448  7028  7028 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,09-08 14:31:47.448  1015  1125 E WifiHW  : ##################### set firmware type 0 #####################
09-08 14:31:47.448  7028  7028 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
09-08 14:31:47.448  7028  7028 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
09-08 14:31:47.448  7028  7028 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,09-08 14:31:47.448  7028  7028 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-08 14:31:47.448  7028  7028 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
09-08 14:31:47.448  7028  7028 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
09-08 14:31:47.448  7028  7028 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-08 14:31:47.448  7028  7028 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-08 14:31:47.448  7028  7028 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75),
,09-08 14:31:47.448  7028  7028 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-08 14:31:47.458  7028  7028 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-08 14:31:47.458  7028  7028 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-08 14:31:47.458  7028  7028 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-08 14:31:47.458  7028  7028 I SA      : [SCU] isHaveSA() - false,
09-08 14:31:47.458  7101  7101 I libpersona: KNOX_SDCARD checking this for 10008
09-08 14:31:47.458  7028  7028 I SA      : support phone number id : false
09-08 14:31:47.458  7101  7101 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:47.458  7028  7028 I SA      : [DM] Supports Ref Jpn : true
09-08 14:31:47.458  7028  7028 I SA      : [DM] init END
,09-08 14:31:47.458  7028  7028 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
09-08 14:31:47.458  7101  7101 E Zygote  : MountEmulatedStorage()
,09-08 14:31:47.458  7101  7101 E Zygote  : v2
09-08 14:31:47.458  7101  7101 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:31:47.468  7101  7101 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:31:47.468  7101  7101 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,09-08 14:31:47.468  1015  1327 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7101 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 14:31:47.478  1015  1327 I ActivityManager: Killing 6574:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,09-08 14:31:47.498  7028  7028 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-08 14:31:47.498  7028  7028 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-08 14:31:47.498  7101  7101 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:47.498  7101  7101 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:47.508  7049  7057 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-08 14:31:47.508  7049  7057 D BadgeProvider: sendNotify, [notify] : null
09-08 14:31:47.508  7049  7057 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-08 14:31:47.508  7049  7057 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-08 14:31:47.508  7049  7057 D BadgeProvider: update, [UpdateCount] : 1
09-08 14:31:47.508  1481  1481 D Launcher.Model: reloadBadges entered.
,09-08 14:31:47.528  7028  7028 I SA      : [SLFUCHKMGR] constructor called,
,09-08 14:31:47.548  7028  7028 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-08 14:31:47.548  7028  7028 I SA      : [OR] == isSIMCardReady false ==
,09-08 14:31:47.568  7028  7028 I SA      : [SCU] == networkStateCheck == false
,09-08 14:31:47.568  7028  7028 I SA      : [OR] onReceive END
,09-08 14:31:47.578  1015  1027 I ActivityManager: Killing 6391:com.android.calendar/u0a131 (adj 15): empty #21
,09-08 14:31:47.598  1015  1028 I ActivityManager: Killing 6590:com.google.android.gms:car/u0a11 (adj 15): empty #21
,09-08 14:31:47.598  1015  1463 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 14:31:47.598  1015  1463 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-08 14:31:47.598  1015  1463 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:47.598  1015  1463 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:47.598  1015  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:47.618  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:47.618  4659  7120 I iu.SyncManager: SYNC; picasa accounts
,09-08 14:31:47.668  4659  4659 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-08 14:31:47.688  2843  2843 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Sep 08 14:31:47 GMT+02:00 2016
,09-08 14:31:47.688  1015  1495 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-08 14:31:47.688  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-08 14:31:47.688  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:47.688  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:47.688  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-08 14:31:47.688  2843  2843 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-08 14:31:47.698  1015  1480 I ActivityManager: Killing 5941:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-08 14:31:47.698  2843  2843 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-08 14:31:47.708   258   548 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-08 14:31:47.708   258   548 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 14:31:47.708  7065  7122 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-08 14:31:47.718  2843  2843 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-08 14:31:47.718  2843  2843 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-08 14:31:47.718  2843  7123 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-08 14:31:47.728  2843  7123 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-08 14:31:47.728   258   548 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-08 14:31:47.728   258   548 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 14:31:47.738  7065  7122 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
09-08 14:31:47.738  7065  7065 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 14:31:47.738  7065  7065 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 14:31:47.738  7065  7065 I GAv4    :   adb logcat -s GAv4
,09-08 14:31:47.738  2843  7123 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-08 14:31:47.738  2843  7123 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-08 14:31:47.738  2843  2843 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-08 14:31:47.748   258   548 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-08 14:31:47.748   258   548 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 14:31:47.748  7065  7128 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-08 14:31:47.748   258   548 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-08 14:31:47.748   258   548 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 14:31:47.748  7065  7128 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-08 14:31:47.758  7065  7065 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 14:31:47.758  1015  1480 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-08 14:31:47.778  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-08 14:31:47.778  1015  1319 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-08 14:31:47.778  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-08 14:31:47.778  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-08 14:31:47.788  7065  7065 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 14:31:47.788  7065  7133 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 14:31:47.888  1015  1043 D Tethering: interfaceAdded wlan0
,09-08 14:31:47.898  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 14:31:47.898  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 14:31:47.898  1015  1130 E Tethering: No numeric data,
,09-08 14:31:47.898  1015  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-08 14:31:47.898  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 14:31:47.898  1015  1130 D Tethering: clearTetheredNotification()
09-08 14:31:47.898  1015  1130 D Tethering: InitialState.processMessage what=4
09-08 14:31:47.898  1015  1130 E Tethering: No numeric data
,09-08 14:31:47.898  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
09-08 14:31:47.898  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:47.908  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-08 14:31:47.908  1173  1173 D HotspotTile: updateTetherState():false, false
,09-08 14:31:47.908  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:31:47.908  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 14:31:47.908  1015  1043 D Tethering: interfaceAdded p2p0
,09-08 14:31:47.908  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-08 14:31:47.908  1015  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-08 14:31:47.908  1015  1122 V NetworkStats: performPollLocked() took 5ms
09-08 14:31:47.908  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:47.908  1015  1130 D Tethering: clearTetheredNotification()
,09-08 14:31:47.908  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-08 14:31:47.908  1173  1173 D HotspotTile: updateTetherState():false, false
,09-08 14:31:47.908  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
09-08 14:31:47.908  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:47.918  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:47.918  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:47.918  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,09-08 14:31:47.918  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
09-08 14:31:47.918  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:31:47.918  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 14:31:47.918   279   967 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-08 14:31:47.918   279   967 D SoftapController: Softap fwReload - Ok
09-08 14:31:47.918  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-08 14:31:47.928   279   967 D CommandListener: Setting iface cfg
09-08 14:31:47.928   279   967 D CommandListener: Trying to bring down wlan0
,09-08 14:31:47.928   279   967 D CommandListener: Clearing all IP addresses on wlan0
,09-08 14:31:47.928  1015  1122 V NetworkStats: performPollLocked() took 14ms
,09-08 14:31:47.928  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:47.928  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:47.928  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:47.928  1015  1125 E WifiHW  : supplicant_name : p2p_supplicant
,09-08 14:31:47.928  1015  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-08 14:31:47.938  1015  1125 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-08 14:31:47.938  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 14:31:47.938  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-08 14:31:47.938  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:47.938  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:47.938  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:47.938  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:47.938  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 14:31:47.938  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-08 14:31:47.948  1173  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-08 14:31:47.948  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:31:47.948  1173  1173 D HotspotTile: onReceive : 2, 0
,09-08 14:31:47.948  1299  1299 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:31:47.948  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:47.948  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-08 14:31:47.958  1015  3328 D SSRM:n  : SIOP:: AP = 340
,09-08 14:31:47.978  7141  7141 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-08 14:31:47.978  7141  7141 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-08 14:31:47.978  7141  7141 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-08 14:31:47.988  7141  7141 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-08 14:31:47.998   405   405 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7141,
09-08 14:31:47.998   405   405 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
09-08 14:31:47.998  7141  7141 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
09-08 14:31:47.998  7141  7141 I wpa_supplicant: ssSupport state is = 1
09-08 14:31:47.998  7141  7141 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
09-08 14:31:47.998  7141  7141 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-08 14:31:47.998   405   405 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7141,
09-08 14:31:47.998   405   405 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-08 14:31:48.048  1015  1762 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:48.058  1015  1762 W ActivityManager: userId = 0, bbcId = -10000,
09-08 14:31:48.058  1015  1762 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:48.058  1015  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-08 14:31:48.088  7065  7065 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-08 14:31:48.108  7065  7065 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 3179-3181)
,09-08 14:31:48.108  7065  7065 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-08 14:31:48.108  7065  7065 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {67a5fe9}
,09-08 14:31:48.108  7065  7065 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-08 14:31:48.108  7065  7065 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 14:31:48.128  7065  7065 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-08 14:31:48.138  7065  7065 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 14:31:48.138  7065  7065 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 14:31:48.158  7065  7065 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-08 14:31:48.158  7065  7065 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-08 14:31:48.158  7065  7065 I Adreno-EGL: Build Date: 04/06/15 Mon
09-08 14:31:48.158  7065  7065 I Adreno-EGL: Local Branch: 
09-08 14:31:48.158  7065  7065 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-08 14:31:48.158  7065  7065 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-08 14:31:48.158  7065  7065 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-08 14:31:48.178   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,09-08 14:31:48.178  7141  7141 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-08 14:31:48.218  7065  7065 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 14:31:48.218  7065  7164 W cr.media: Requires BLUETOOTH permission
,09-08 14:31:48.228  7065  7065 I NSApplication: Starting up...
,09-08 14:31:48.228  1015  1762 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-08 14:31:48.228  7141  7141 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-08 14:31:48.228  7141  7141 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-08 14:31:48.238  1015  1480 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output,
,09-08 14:31:48.238  7141  7141 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-08 14:31:48.238   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7141
09-08 14:31:48.238   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-08 14:31:48.238  7141  7141 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-08 14:31:48.238  7141  7141 I wpa_supplicant: ssSupport state is = 1
,09-08 14:31:48.238  7141  7141 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-08 14:31:48.238  1015  1463 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-08 14:31:48.248  7141  7141 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 14:31:48.248  7141  7141 E wpa_supplicant: SIM READ ERROR
09-08 14:31:48.248  7141  7141 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 14:31:48.248  7141  7141 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 14:31:48.248  7141  7141 E wpa_supplicant: SIM READ ERROR
09-08 14:31:48.248  7141  7141 I wpa_supplicant: Blacklist: Clear (all) 
09-08 14:31:48.248  7141  7141 I wpa_supplicant: wpa_default_ap_write_once
09-08 14:31:48.248  7141  7141 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-08 14:31:48.248  7141  7141 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 14:31:48.248  7141  7141 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-08 14:31:48.248  7141  7141 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 14:31:48.248  7141  7141 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-08 14:31:48.248  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-08 14:31:48.248  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:48.248  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:48.248  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:48.248  7141  7141 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 14:31:48.248  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 14:31:48.248  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 14:31:48.248  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-08 14:31:48.258  7170  7170 E Zygote  : MountEmulatedStorage(),
,09-08 14:31:48.258  7170  7170 E Zygote  : v2,
09-08 14:31:48.258  7170  7170 I libpersona: KNOX_SDCARD checking this for 10117
,09-08 14:31:48.258  7170  7170 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:48.258  7170  7170 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:31:48.268  7170  7170 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 14:31:48.268  1015  1463 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7170 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-08 14:31:48.268  7170  7170 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-08 14:31:48.268  1015  1463 I ActivityManager: Killing 5744:com.android.vending/u0a26 (adj 15): empty #21
,09-08 14:31:48.298  7170  7170 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:48.298  7170  7170 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:48.318  7170  7170 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 14:31:48.368  7141  7141 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-08 14:31:48.558  7141  7141 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-08 14:31:48.558  7141  7141 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-08 14:31:48.578  7141  7141 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-08 14:31:48.578   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7141,
09-08 14:31:48.578   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-08 14:31:48.578  7141  7141 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
,09-08 14:31:48.578  7141  7141 I wpa_supplicant: ssSupport state is = 1
,09-08 14:31:48.598  7141  7141 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-08 14:31:48.598  7141  7141 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-08 14:31:48.608  7141  7141 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-08 14:31:48.608   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7141
09-08 14:31:48.608   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-08 14:31:48.608  7141  7141 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-08 14:31:48.608  7141  7141 I wpa_supplicant: ssSupport state is = 1
09-08 14:31:48.608  7141  7141 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 14:31:48.608  7141  7141 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 14:31:48.608  7141  7141 E wpa_supplicant: SIM READ ERROR
09-08 14:31:48.608  7141  7141 I wpa_supplicant: wpa_default_ap_write_once
09-08 14:31:48.608  7141  7141 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-08 14:31:48.608  7141  7141 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 14:31:48.608  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
09-08 14:31:48.608  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-08 14:31:48.618  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-08 14:31:48.618  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,09-08 14:31:48.618  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-08 14:31:48.618  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-08 14:31:48.668  1015  1495 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-08 14:31:48.668  1015  1495 I ActivityManager: Killing 6723:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,09-08 14:31:48.678  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 14:31:48.678  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 14:31:48.678  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:48.678  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:48.678  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-08 14:31:48.678  1603  1603 I Hs20UtilService: Starting #11
09-08 14:31:48.678  1603  1640 I Hs20UtilService: Message received 5011
,09-08 14:31:48.678  6877  6877 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-08 14:31:48.678  6877  6877 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 14:31:48.678  6877  6877 D SecurityLogAgent: StateMachine : Current State = 1
,09-08 14:31:48.678  6877  6877 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 14:31:48.688  1015  1327 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 14:31:48.688  1015  1327 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 14:31:48.688  1015  1327 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:48.688  1015  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:48.688  1015  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 14:31:48.688  1603  1603 I Hs20UtilService: Starting #12
,09-08 14:31:48.688  1603  1640 I Hs20UtilService: Message received 5011
,09-08 14:31:48.698  6877  6877 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-08 14:31:48.698  6877  6877 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-08 14:31:48.698  6877  6877 D SecurityLogAgent: StateMachine : Current State = 1
,09-08 14:31:48.698  6877  6877 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 14:31:48.708  7141  7141 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-08 14:31:48.708  7141  7141 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-08 14:31:48.728   292   292 E SMD     : DCD OFF
,09-08 14:31:48.768  7141  7141 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-08 14:31:48.768  7141  7141 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-08 14:31:48.768  7141  7141 I wpa_supplicant: Skip scan - bUseNetwork false
,09-08 14:31:48.898  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
09-08 14:31:48.898  1015  1043 D Tethering: interfaceStatusChanged p2p0, false,
09-08 14:31:48.898  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-08 14:31:48.938  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-08 14:31:48.938  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-08 14:31:48.948  7141  7141 I wpa_supplicant: HOTSPOT20_ENABLE called
09-08 14:31:48.948  7141  7141 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 14:31:48.948  7141  7141 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-08 14:31:48.948  7141  7141 E wpa_supplicant: SIM READ ERROR
09-08 14:31:48.948  7141  7141 I wpa_supplicant: Blacklist: Clear (all) ,
,09-08 14:31:48.968  7141  7141 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-08 14:31:48.978  7141  7141 I wpa_supplicant: Skip scan - bUseNetwork false
09-08 14:31:48.978  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:31:48.978  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 14:31:48.978  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:48.978  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:48.978  1015  1125 D WifiConfigStore: Loading config and enabling all networks 
09-08 14:31:48.978  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:48.978  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:48.978  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 14:31:48.978  1173  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-08 14:31:48.978  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-08 14:31:48.978  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 14:31:48.978  1173  1173 D HotspotTile: onReceive : 3, 0
,09-08 14:31:48.988  1299  1299 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:31:48.988  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:48.988  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:48.988  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:48.988  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:48.988  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:48.988  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:48.988  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:48.988  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:31:48.988  6647  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-08 14:31:48.988  1015  1125 E WifiConfigStore: Not a HS20
,09-08 14:31:48.988  1015  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 14:31:48.988  1015  1762 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 14:31:48.998  1015  1762 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 14:31:48.998  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-08 14:31:48.998  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:48.998  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:48.998  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:48.998  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:48.998  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:31:48.998  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:31:48.998  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:31:48.998  1015  1762 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:48.998  1015  1762 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:48.998  1015  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-08 14:31:48.998  1603  1603 I Hs20UtilService: Starting #13
09-08 14:31:48.998  1603  1640 I Hs20UtilService: Message received 5011
09-08 14:31:48.998  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
09-08 14:31:48.998  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-08 14:31:48.998  7141  7141 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-08 14:31:48.998  7141  7141 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-08 14:31:48.998  7141  7141 I wpa_supplicant: reset timer : RESET_TIMER 0
09-08 14:31:48.998  7141  7141 I wpa_supplicant: P2P: Current p2p state = IDLE
09-08 14:31:48.998  7141  7141 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-08 14:31:48.998  7141  7141 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-08 14:31:48.998  7141  7141 I wpa_supplicant: First Scan Start
09-08 14:31:48.998  7141  7141 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-08 14:31:48.998  6877  6877 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-08 14:31:48.998  6877  6877 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 14:31:48.998  6877  6877 D SecurityLogAgent: StateMachine : Current State = 1
09-08 14:31:48.998  6877  6877 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 14:31:49.008  6647  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:31:49.008  1015  1125 D WifiNative-wlan0: Setting external_sim to 1
,09-08 14:31:49.008  6801  6801 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:31:49.008  1015  1125 D WifiStateMachine: Setting OUI to DA-A1-19
,09-08 14:31:49.008  1015  1125 I WifiNative-HAL: startHal
09-08 14:31:49.008  1015  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d4c288c
09-08 14:31:49.008  1015  1125 I WifiNative-HAL: Could not start hal
,09-08 14:31:49.018  1015  1125 E WifiNative-wlan0: do suspend true
,09-08 14:31:49.018  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-08 14:31:49.018  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3,
,09-08 14:31:49.018  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
09-08 14:31:49.018  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:49.018  1015  1149 I WifiNative-HAL: startHal
,09-08 14:31:49.018  1015  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9e87c9bc
09-08 14:31:49.018  1015  1149 I WifiNative-HAL: Could not start hal
09-08 14:31:49.018  1015  1149 E WifiScanningService: could not start HAL
09-08 14:31:49.018  1015  1015 D RttService: SCAN_AVAILABLE : 3
09-08 14:31:49.018  1015  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:49.018   279   967 D CommandListener: Setting iface cfg
09-08 14:31:49.018  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-08 14:31:49.018  1015  1124 D WifiP2pService: P2pEnablingState
09-08 14:31:49.018   279   967 D CommandListener: Trying to bring up p2p0
09-08 14:31:49.018  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-08 14:31:49.018  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
09-08 14:31:49.018  1015  1125 E WifiNative-wlan0: invaild command id : 215
09-08 14:31:49.018  1015  1124 D WifiP2pService: P2p socket connection successful
09-08 14:31:49.018  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 14:31:49.018  1015  1124 D WifiP2pService: P2pEnabledState
09-08 14:31:49.018  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207],
,09-08 14:31:49.018  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-08 14:31:49.018  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-08 14:31:49.028  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-08 14:31:49.018  1015  1125 E WifiNative-wlan0: invaild command id : 215
09-08 14:31:49.028  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 14:31:49.018  1015  1127 E ConnectivityService: updateNetworkInfo()
09-08 14:31:49.028  1015  1046 D WifiDisplayController: disconnect
09-08 14:31:49.028  7141  7141 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-08 14:31:49.028  1015  1046 D WifiDisplayController: updateConnection
09-08 14:31:49.028  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 14:31:49.028  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-08 14:31:49.028  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-08 14:31:49.028  7141  7141 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-08 14:31:49.028  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-08 14:31:49.028  7141  7141 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-08 14:31:49.028  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
09-08 14:31:49.028  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-08 14:31:49.028  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-08 14:31:49.028  1015  1125 E WifiStateMachine: Failed to set frequency band 0
,09-08 14:31:49.028  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 14:31:49.028  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-08 14:31:49.028  1015  1125 D SecContentProvider2: mCursor = null
,09-08 14:31:49.028  1015  1495 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-08 14:31:49.028  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-08 14:31:49.038  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-08 14:31:49.038  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,09-08 14:31:49.038  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
09-08 14:31:49.038  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 14:31:49.038  1015  1125 D SecContentProvider2: mCursor = null
,09-08 14:31:49.038  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-08 14:31:49.038  1015  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-08 14:31:49.038  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
09-08 14:31:49.038  1015  1046 D WifiDisplayController:  secondary type: null
09-08 14:31:49.038  1015  1046 D WifiDisplayController:  wps: 0
09-08 14:31:49.038  1015  1046 D WifiDisplayController:  grpcapab: 0
09-08 14:31:49.038  1015  1046 D WifiDisplayController:  devcapab: 0
09-08 14:31:49.038  1015  1046 D WifiDisplayController:  status: 3
09-08 14:31:49.038  1015  1046 D WifiDisplayController:  wfdInfo: null
09-08 14:31:49.038  1015  1046 D WifiDisplayController:  groupownerAddress: null
09-08 14:31:49.038  1015  1046 D WifiDisplayController:  GOdeviceName: null
09-08 14:31:49.038  1015  1046 D WifiDisplayController:  interfaceAddress: 
09-08 14:31:49.038  1015  1046 D WifiDisplayController:  SConnectInfo : null
,09-08 14:31:49.038  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-08 14:31:49.038  1015  1124 D WifiP2pService: DeviceAddress: 0a:76:28
,09-08 14:31:49.038  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 14:31:49.038  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-08 14:31:49.038  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 14:31:49.038  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 14:31:49.038  1299  2233 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 14:31:49.048  6846  6846 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
09-08 14:31:49.048  6846  6846 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-08 14:31:49.048  6846  6846 D FileShare-Client: Outbound.stopDelayTimer - 
,09-08 14:31:49.048  6861  6861 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 14:31:49.058  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-08 14:31:49.058  1015  1124 D WifiP2pService: InactiveState
,09-08 14:31:49.058  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-08 14:31:49.058  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-08 14:31:49.058  7141  7141 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-08 14:31:49.058  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-08 14:31:49.058  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-08 14:31:49.228  6647  6702 D BluetoothAdapter: enable()
,09-08 14:31:49.228  6647  6702 D BluetoothAdapter: enable(): BT is already enabled..!
,09-08 14:31:50.328  7141  7141 I wpa_supplicant: nl80211: Received scan results (7 BSSes)
09-08 14:31:50.328  7141  7141 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-08 14:31:50.328  7141  7141 I wpa_supplicant: Trying to associate with SSID '4E47373030',
09-08 14:31:50.328  7141  7141 I wpa_supplicant: Trying to associate with  'G700'
,09-08 14:31:50.328  7141  7141 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-08 14:31:50.328  7141  7141 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-08 14:31:50.338  1015  7195 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,09-08 14:31:50.348  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-08 14:31:50.348  1015  1125 D SecContentProvider2: mCursor = null
,09-08 14:31:50.598  7141  7141 E wpa_supplicant: Cmd 35605 not handled
,09-08 14:31:50.598  7141  7141 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-08 14:31:50.598  7141  7141 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
09-08 14:31:50.598  7141  7141 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-08 14:31:50.598  7141  7141 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-08 14:31:50.598  7141  7141 I wpa_supplicant: Associated with F4.99.3E
09-08 14:31:50.598  7141  7141 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-08 14:31:50.598  7141  7141 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-08 14:31:50.598  7141  7141 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-08 14:31:50.598  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 14:31:50.598  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 14:31:50.598  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-08 14:31:50.598  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 14:31:50.598  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 14:31:50.598  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-08 14:31:50.598  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 14:31:50.598  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 14:31:50.598  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 14:31:50.598  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true,
09-08 14:31:50.598  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-08 14:31:50.598  1015  1043 D Tethering: interfaceStatusChanged wlan0, true,
,09-08 14:31:50.598  1015  1130 E Tethering: No numeric data
09-08 14:31:50.608  1015  1122 V NetworkStats: performPollLocked(flags=0x1),
,09-08 14:31:50.598  1015  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-08 14:31:50.608  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-08 14:31:50.598  1015  1130 D Tethering: clearTetheredNotification()
09-08 14:31:50.608  1173  1173 D HotspotTile: updateTetherState():false, false
09-08 14:31:50.608  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 14:31:50.608  1015  1125 D SecContentProvider2: mCursor = null
09-08 14:31:50.608  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:50.608  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:31:50.608  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 14:31:50.608  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 14:31:50.608  1015  1125 D SecContentProvider2: mCursor = null
09-08 14:31:50.608  1015  1122 V NetworkStats: performPollLocked() took 7ms
09-08 14:31:50.608  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:50.618  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:50.618  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:50.698  7141  7141 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-08 14:31:50.698  7141  7141 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-08 14:31:50.698  7141  7141 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-08 14:31:50.698  7141  7141 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030,
09-08 14:31:50.698  7141  7141 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 14:31:50.698  7141  7141 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,09-08 14:31:50.698  7141  7141 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-08 14:31:50.698  7141  7141 I wpa_supplicant: Blacklist: Clear (temp) 
09-08 14:31:50.698  7141  7141 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-08 14:31:50.698  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true,
09-08 14:31:50.698  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-08 14:31:50.698  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,09-08 14:31:50.708  1015  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-08 14:31:50.708  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1,
,09-08 14:31:50.708  1015  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-08 14:31:50.708  1015  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-08 14:31:50.718  1015  1127 E ConnectivityService: updateNetworkInfo()
09-08 14:31:50.718  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-08 14:31:50.718  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 14:31:50.718  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 14:31:50.718  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:50.718  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:50.718  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:50.718  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:50.718  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-08 14:31:50.718  1015  1475 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 14:31:50.728  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 14:31:50.728  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:50.728  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:50.728  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 14:31:50.728  1603  1603 I Hs20UtilService: Starting #14
,09-08 14:31:50.728  1603  1640 I Hs20UtilService: Message received 5007,
,09-08 14:31:50.728  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 14:31:50.728  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 14:31:50.738  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:31:50.738  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,09-08 14:31:50.738  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-08 14:31:50.738  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-08 14:31:50.738  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 14:31:50.748  1299  2233 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 14:31:50.748   279   967 D CommandListener: Setting iface cfg
,09-08 14:31:50.758  1015  1125 E WifiStateMachine: Start Dhcp Watchdog 2
,09-08 14:31:50.758  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-08 14:31:50.758  1015  1125 D SecContentProvider2: mCursor = null
,09-08 14:31:50.768  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 14:31:50.768  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-08 14:31:50.768  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:50.768  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:50.768  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:50.778  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:50.778  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-08 14:31:50.778  1015  1125 D SecContentProvider2: mCursor = null
,09-08 14:31:50.788  1015  1125 E WifiNative-wlan0: do suspend false
,09-08 14:31:50.788  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-08 14:31:50.788  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-08 14:31:51.008  7202  7202 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-08 14:31:51.008  7202  7202 I dhcpcd  : version 5.5.6 starting,
,09-08 14:31:51.018  7202  7202 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-08 14:31:51.068  7202  7202 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-08 14:31:51.068  7202  7202 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-08 14:31:51.068  7202  7202 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
09-08 14:31:51.068  7202  7202 I dhcpcd  : bssid match,
,09-08 14:31:51.068  7202  7202 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,09-08 14:31:51.108  3149  3271 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-08 14:31:51.108  3149  3271 E bt-btif : DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,09-08 14:31:51.108  3149  3329 W bt-btif : invalid rfc slot id: 7
,09-08 14:31:51.108  6647  6790 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1db58e34, channel: -1, state: INIT
,09-08 14:31:51.108  6647  6790 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1db58e34, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27d9945d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1fc6b1d2mSocket: android.net.LocalSocket@2c33e2a3 impl:android.net.LocalSocketImpl@e3759a0 fd:FileDescriptor[106]
,09-08 14:31:51.108  6647  6790 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2c33e2a3 impl:android.net.LocalSocketImpl@e3759a0 fd:FileDescriptor[106]
,09-08 14:31:51.108  6647  6790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1327)
,09-08 14:31:51.138  7202  7202 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,09-08 14:31:51.228  7202  7202 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,09-08 14:31:51.258  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-08 14:31:51.258  1015  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-08 14:31:51.258  1015  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-08 14:31:51.258  1015  1027 D BatteryService: stay LED for fully charged,
09-08 14:31:51.258  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-08 14:31:51.258  1015  1015 I MotionRecognitionService: Plugged
09-08 14:31:51.258  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-08 14:31:51.258  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-08 14:31:51.258  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-08 14:31:51.268  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-08 14:31:51.268  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-08 14:31:51.288  3149  3149 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-08 14:31:51.288  3149  3252 D HeadsetStateMachine: Disconnected process message: 10
,09-08 14:31:51.298  1173  1173 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-08 14:31:51.298  1173  1173 D SViewCoverView: level :100 plugged : 2
,09-08 14:31:51.298  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
09-08 14:31:51.298  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-08 14:31:51.298  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-08 14:31:51.598  1015  1125 E WifiNative-wlan0: do suspend true
,09-08 14:31:51.618  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-08 14:31:51.628  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-08 14:31:51.628  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-08 14:31:51.628  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 14:31:51.628  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.628  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:51.628  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.628  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.628  1015  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-08 14:31:51.628  1015  1125 E WifiStateMachine: VerifyingLinkState enter
,09-08 14:31:51.628  1015  1127 E ConnectivityService: updateNetworkInfo()
,09-08 14:31:51.638  1015  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-08 14:31:51.638  1015  1127 D ConnectivityService: Adding iface wlan0 to network 503
,09-08 14:31:51.648  1015  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-08 14:31:51.648  1015  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-08 14:31:51.648  1015  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-08 14:31:51.648  1015  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-08 14:31:51.648  1015  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-08 14:31:51.658  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 14:31:51.658  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
09-08 14:31:51.668  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.668  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.668  1015  1463 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 14:31:51.668  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.668  1015  1463 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-08 14:31:51.668  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.668  1015  1463 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:51.668  1015  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:51.668  1015  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 14:31:51.668  1015  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-08 14:31:51.678  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-08 14:31:51.678  1603  1603 I Hs20UtilService: Starting #15
09-08 14:31:51.678  1603  1640 I Hs20UtilService: Message received 5007
,09-08 14:31:51.678  1299  1299 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-08 14:31:51.678  1015  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
09-08 14:31:51.678  1015  1127 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
09-08 14:31:51.678  1015  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,09-08 14:31:51.688  1015  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 14:31:51.688  1015  1127 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,09-08 14:31:51.688  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling,
,09-08 14:31:51.688  1015  1127 D ConnectivityService: LTETest block dns file not exists
,09-08 14:31:51.698  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 14:31:51.698  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 14:31:51.698  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.698  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.698  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.698  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:51.698  1015  1475 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 14:31:51.698  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 14:31:51.698  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:51.698  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:51.698  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 14:31:51.698  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 14:31:51.698  1015  1127 V NetworkStats: updateIfacesLocked()
09-08 14:31:51.698  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:51.698  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
09-08 14:31:51.698  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-08 14:31:51.698  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:31:51.698  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 14:31:51.708  1603  1603 I Hs20UtilService: Starting #16
09-08 14:31:51.708  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-08 14:31:51.708  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
09-08 14:31:51.708  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
09-08 14:31:51.708  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:51.708  1015  1127 V NetworkStats: performPollLocked() took 5ms
,09-08 14:31:51.708  1603  1640 I Hs20UtilService: Message received 5007
,09-08 14:31:51.718  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:31:51.718  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-08 14:31:51.718  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.718  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.718  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.718  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:51.718  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
09-08 14:31:51.718  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 14:31:51.718  1015  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-08 14:31:51.718  1015  1127 E ConnectivityService: updateNetworkInfo()
09-08 14:31:51.718  1015  1127 E ConnectivityService: updateNetworkInfo()
09-08 14:31:51.718  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-08 14:31:51.718  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:51.718  1015  1127 V NetworkStats: updateIfacesLocked()
09-08 14:31:51.718  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
,09-08 14:31:51.728  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:31:51.728  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 14:31:51.728  1015  1127 V NetworkStats: performPollLocked() took 4ms
09-08 14:31:51.728  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:51.728  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:51.728  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:51.728  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:51.728  1015  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
09-08 14:31:51.728  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:51.728  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
09-08 14:31:51.728  1015  7200 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:51.728  1015  7200 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-08 14:31:51.728  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-08 14:31:51.728  1015  7200 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:31:51.728  1015  7200 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-08 14:31:51.728  1015  7200 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-08 14:31:51.728  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-08 14:31:51.728  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 14:31:51.728  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-08 14:31:51.728  1299  2233 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-08 14:31:51.728   279   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 14:31:51.728   279   963 D Netd    : getNetworkForDns: using netid 503 for uid 1000
,09-08 14:31:51.728   292   292 E SMD     : DCD OFF
09-08 14:31:51.728  1015  1127 D ConnectivityService:    accepting network in place of null
09-08 14:31:51.728  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-08 14:31:51.728  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-08 14:31:51.728  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-08 14:31:51.728  1455  1455 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-08 14:31:51.738  1015  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-08 14:31:51.738  1015  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
09-08 14:31:51.738  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-08 14:31:51.738  1015  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-08 14:31:51.738  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-08 14:31:51.738  1015  1130 D Tethering: MasterInitialState.processMessage what=3
09-08 14:31:51.738  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
09-08 14:31:51.748  1015  1122 V NetworkStats: updateIfacesLocked()
09-08 14:31:51.748  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:51.748  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
09-08 14:31:51.748  1173  1672 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-08 14:31:51.748  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:31:51.748  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 14:31:51.748  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 14:31:51.748  4659  6711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 14:31:51.748  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 14:31:51.748  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:51.748  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:51.748  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:51.748  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-08 14:31:51.748  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:51.748  1015  1122 V NetworkStats: performPollLocked() took 5ms
09-08 14:31:51.748  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:51.748  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:51.748  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-08 14:31:51.748  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:31:51.748  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-08 14:31:51.748  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-08 14:31:51.748  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-08 14:31:51.748  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-08 14:31:51.748  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-08 14:31:51.748  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-08 14:31:51.748  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:51.748  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:51.748  1603  1603 I Hs20UtilService: Starting #17
,09-08 14:31:51.758  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-08 14:31:51.758  1299  1299 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-08 14:31:51.758  1603  1640 I Hs20UtilService: Message received 5007
,09-08 14:31:51.758  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-08 14:31:51.758  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-08 14:31:51.758  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-08 14:31:51.758  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:31:51.758  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-08 14:31:51.758  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.758  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.758  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.758  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.758  1015  1495 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-08 14:31:51.768  1015  1027 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState,
09-08 14:31:51.768  1015  1027 D SecContentProvider2: mCursor = null
09-08 14:31:51.768  1015  1327 D SecContentProvider2: uri = 15 selection = getToastGravity
09-08 14:31:51.768  1015  1327 D SecContentProvider2: mCursor = null
09-08 14:31:51.768  1015  1135 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-08 14:31:51.768  1015  1135 D SecContentProvider2: mCursor = null
09-08 14:31:51.768  1015  1464 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-08 14:31:51.768  1015  1464 D SecContentProvider2: mCursor = null
,09-08 14:31:51.778  1015  1028 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,09-08 14:31:51.778  1015  1028 D SecContentProvider2: mCursor = null
,09-08 14:31:51.778  1015  1463 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-08 14:31:51.778  1015  1463 D SecContentProvider2: mCursor = null
,09-08 14:31:51.808   259   259 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-08 14:31:51.818  1015  1327 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,09-08 14:31:51.828  1173  1173 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-08 14:31:51.848  1015  7200 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-08 14:31:51.918  1015  7200 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 12:31:51 GMT], X-Android-Received-Millis=[1473337911925], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473337911887]}
,09-08 14:31:51.918  1015  7200 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-08 14:31:51.918  1015  7200 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-08 14:31:51.918  1015  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
09-08 14:31:51.918  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
09-08 14:31:51.918  1015  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
09-08 14:31:51.918  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,09-08 14:31:51.918  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 14:31:51.918  1173  1672 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-08 14:31:51.918  4659  6711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-08 14:31:51.918  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
,09-08 14:31:51.928  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-08 14:31:51.928  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-08 14:31:51.928  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-08 14:31:51.928  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-08 14:31:51.928  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-08 14:31:51.928  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-08 14:31:51.928  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-08 14:31:51.928  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-08 14:31:51.928  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 14:31:51.928  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-08 14:31:51.928  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:51.928  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:51.928  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:31:51.928  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:31:52.248  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:52.258  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:52.268  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:52.268  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:52.268  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:52.268  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:52.268  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:52.268  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:52.268  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:52.268  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:31:52.278  6893  6893 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-08 14:31:52.278  6893  6893 I PCWCLIENTTRACE_PushUtil: sales region : global
09-08 14:31:52.278  6893  6893 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-08 14:31:52.278  6893  6893 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:52.278  6647  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:31:52.288  1015  1028 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
09-08 14:31:52.288  1015  1028 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-08 14:31:52.298  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:52.298  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:52.298  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:52.298  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:52.298  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:31:52.298  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:52.298  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:52.298  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:31:52.298  6647  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:31:52.308  1797  1797 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-08 14:31:52.308  6910  6910 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:52.318  6910  6910 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-08 14:31:52.318  6910  6910 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-08 14:31:52.328  1015  1762 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-08 14:31:52.328  1015  1762 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,09-08 14:31:52.328  1015  1762 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:52.328  1015  1762 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:52.328  1015  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-08 14:31:52.328  1836  2335 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,09-08 14:31:52.338  1015  1490 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-08 14:31:52.338  1015  1490 D SecContentProvider2: mCursor = null
,09-08 14:31:52.338  1797  1797 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-08 14:31:52.338  1797  1797 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-08 14:31:52.338  1797  1797 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-08 14:31:52.338  1797  1797 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-08 14:31:52.338  1015  1490 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 14:31:52.348  7008  7008 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:52.348  7008  7008 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-08 14:31:52.348  7008  7008 I DIAGMON_AGENT: ./extraInfo: "NG700"
,09-08 14:31:52.348  7008  7008 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
09-08 14:31:52.348  1015  1762 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 14:31:52.358  1797  1797 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-08 14:31:52.358  1797  1797 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-08 14:31:52.368  7077  7077 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-08 14:31:52.378  2744  7240 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-08 14:31:52.378  2744  7240 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,09-08 14:31:52.388  6986  6986 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,09-08 14:31:52.388  2744  7240 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-08 14:31:52.388  7028  7028 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-08 14:31:52.388  7028  7028 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
09-08 14:31:52.388  7028  7028 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-08 14:31:52.388  1015  1495 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
09-08 14:31:52.388  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,09-08 14:31:52.398  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:52.398  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:52.398  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,09-08 14:31:52.398  7028  7028 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-08 14:31:52.398  7028  7028 I SA      : [OR] == isSIMCardReady false ==
,09-08 14:31:52.398  7028  7028 I SA      : [SCU] == networkStateCheck == true
,09-08 14:31:52.408  7028  7028 I SA      : [DM] getCountryCodeFromCSC : PL
09-08 14:31:52.408  7028  7028 I SA      : isChinaCountryCode : false
09-08 14:31:52.408  7028  7028 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-08 14:31:52.408  7028  7028 I SA      : [OR] == networkStateCheck true ==
,09-08 14:31:52.408  1015  1475 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-08 14:31:52.408  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-08 14:31:52.408  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:52.408  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:52.408  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-08 14:31:52.428  2744  7240 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,09-08 14:31:52.428  2744  7240 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,09-08 14:31:52.428  7028  7028 I SA      : [OR] GetMyCountryZoneTask
,09-08 14:31:52.428  2744  7240 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,09-08 14:31:52.438  7028  7028 I SA      : [OR] onReceive END
,09-08 14:31:52.438  2744  7240 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,09-08 14:31:52.438  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:31:52.448  2744  7240 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,09-08 14:31:52.448  2744  7240 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,09-08 14:31:52.448  1015  1319 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
09-08 14:31:52.448  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,09-08 14:31:52.448  2744  7240 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
09-08 14:31:52.448  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:52.448  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:52.448  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,09-08 14:31:52.448  6801  7244 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,09-08 14:31:52.448  6801  7244 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-08 14:31:52.448  6801  7244 I System.out: (HTTPLog)-Static: isShipBuild true
09-08 14:31:52.448  6801  7244 I System.out: (HTTPLog)-Thread-1220-1027581760: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-08 14:31:52.458  6801  7244 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 14:31:52.458  2744  7240 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,09-08 14:31:52.458   279   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 14:31:52.458   279   963 D Netd    : getNetworkForDns: using netid 503 for uid 10102
,09-08 14:31:52.468  7028  7246 I SA      : [SRS] prepareGetMyCountryZone
,09-08 14:31:52.468  1015  1028 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
09-08 14:31:52.468  1015  1028 D SecContentProvider2: mCursor = null
,09-08 14:31:52.468  7028  7246 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-08 14:31:52.478  7028  7246 I SA      : [SSP] query invoked
,09-08 14:31:52.478  7028  7246 I SA      : [TPMU] GetMccFromDB : null
,09-08 14:31:52.488  7028  7246 I SA      : [SCU] getMccFromPreferece mcc = 260
09-08 14:31:52.488  7028  7246 I SA      : [LBE] isSupportCheckDomainRegion : false
,09-08 14:31:52.488  7028  7246 I SA      : [TPM] isNoProxy(default) : true
,09-08 14:31:52.498  6801  7244 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-08 14:31:52.508  2744  7240 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,09-08 14:31:52.518  7101  7101 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-08 14:31:52.528  2744  7240 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-08 14:31:52.528  7028  7246 E File    : fail readDirectory() errno=2
,09-08 14:31:52.538  7101  7101 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,09-08 14:31:52.548  7101  7101 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,09-08 14:31:52.548  7101  7101 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,09-08 14:31:52.548  6801  7244 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 14:31:52.548  2843  2843 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Sep 08 14:31:52 GMT+02:00 2016
,09-08 14:31:52.548  1015  1480 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-08 14:31:52.548  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-08 14:31:52.558  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:52.558  1015  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:52.558  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-08 14:31:52.558  2843  2843 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-08 14:31:52.568  2843  2843 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-08 14:31:52.568  2843  2843 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-08 14:31:52.568  2843  2843 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-08 14:31:52.568  2843  7253 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-08 14:31:52.578  2843  7253 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-08 14:31:52.578  2843  7253 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,09-08 14:31:52.578  2843  7253 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,09-08 14:31:52.578  2843  7253 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,09-08 14:31:52.598  2843  7253 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,09-08 14:31:52.598  2843  7253 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-08 14:31:52.598  2843  2843 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-08 14:31:52.678  1015  1463 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,09-08 14:31:52.678  1015  1463 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,09-08 14:31:52.678  1015  1463 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:52.678  1015  1463 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-08 14:31:52.678  1015  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-08 14:31:52.688  1015  1135 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 14:31:52.688  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-08 14:31:52.688  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:52.698  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:52.698  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:52.698  7077  7077 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,09-08 14:31:52.698  7077  7077 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,09-08 14:31:52.708  7077  7077 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,09-08 14:31:52.708  7077  7077 D InitializeManagerStateMachine: exit::IDLE
09-08 14:31:52.708  7077  7077 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,09-08 14:31:52.708   279   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 14:31:52.708   279   963 D Netd    : getNetworkForDns: using netid 503 for uid 10011
,09-08 14:31:52.708  7077  7077 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
09-08 14:31:52.708  7077  7077 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-08 14:31:52.708  7077  7077 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-08 14:31:52.708  7077  7077 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-08 14:31:52.708  7077  7077 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-08 14:31:52.708  7077  7077 D InitializeManagerStateMachine: entry::SUCCESS
09-08 14:31:52.708  7077  7077 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-08 14:31:52.708  4659  4659 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 14:31:52.708  7077  7077 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-08 14:31:52.708  7077  7077 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,09-08 14:31:52.718  7077  7077 D InitializeManagerStateMachine: exit::SUCCESS
09-08 14:31:52.718  7077  7077 D InitializeManagerStateMachine: entry::IDLE
,09-08 14:31:52.718  4659  7120 I iu.UploadsManager: num queued entries: 0
,09-08 14:31:52.718  4659  7120 I iu.UploadsManager: num updated entries: 0
,09-08 14:31:52.728  4659  7120 I iu.SyncManager: NEXT; no task
,09-08 14:31:52.748  1015  1127 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network,
,09-08 14:31:52.758  1015  1048 I PowerManagerService: [PWL] Off : 75s ago
09-08 14:31:52.758  1015  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-08 14:31:52.758  1015  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-08 14:31:52.758  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'GCM_CONN_ALARM' (uid=10011, pid=1997, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=63)
09-08 14:31:52.768  1015  1464 I splitIntent: Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-08 14:31:52.848  1997  7255 I qtaguid : Tagging socket 47 with tag 1000040700000000{268436487,0} for uid -1, pid: 1997, getuid(): 10011
,09-08 14:31:52.948  7028  7246 I SA      : [RC New] Execute method=[GET] start
,09-08 14:31:52.978  7028  7246 I SA      : [RC New] Security=[true]
,09-08 14:31:52.978  7028  7246 I System.out: Thread-1276(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,09-08 14:31:52.978  7028  7246 I System.out: Thread-1276(ApacheHTTPLog):isSBSettingEnabled false
,09-08 14:31:52.978  7028  7246 I System.out: Thread-1276(ApacheHTTPLog):isShipBuild true
09-08 14:31:52.978  7028  7246 I System.out: Thread-1276(ApacheHTTPLog):SMARTBONDING_ENABLED is false
09-08 14:31:52.978  7028  7246 I System.out: Thread-1276(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,09-08 14:31:52.978   279   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 14:31:52.978   279   963 D Netd    : getNetworkForDns: using netid 503 for uid 10036
,09-08 14:31:52.998  1015  1330 E Watchdog: !@Sync 4
,09-08 14:31:52.998  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:52.998  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 14:31:52.998  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-08 14:31:53.618  7028  7246 I SA      : [RC New] [v2liruge] api execute + 634
,09-08 14:31:53.618  7028  7246 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,09-08 14:31:53.618  7028  7246 I System.out: AsyncTask #1 calls detatch()
,09-08 14:31:53.628  7028  7246 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,09-08 14:31:53.628  7028  7246 I SA      : [OCP] update openData : PL
,09-08 14:31:53.638  7028  7246 I SA      : [TPMU] getNetworkMcc : 
,09-08 14:31:53.638  7028  7246 I SA      : [SCU] saveMccToPreferece Start
,09-08 14:31:53.638  7028  7246 I SA      : [SCU] RegionMCC : 260
,09-08 14:31:53.638  7028  7246 I SA      : [SSP] query invoked
,09-08 14:31:53.648  7028  7246 I SA      : [TPMU] GetMccFromDB : null
,09-08 14:31:53.648  7028  7246 I SA      : [SCU] getMccFromPreferece mcc = 260
,09-08 14:31:53.648  7028  7246 I SA      : [SCU] saveMccToPreferece End
,09-08 14:31:53.648  7028  7246 I SA      : [RC New] executeRequest [v2liruge] end. 701
09-08 14:31:53.648  7028  7246 I SA      : [RC New] Execute end
,09-08 14:31:53.648  7028  7028 I SA      : [OR] GetMyCountryZoneTask mcc = 260
,09-08 14:31:53.648  7028  7028 I SA      : [OR] GetMyCountryZoneTask Success
,09-08 14:31:53.778   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 14:31:54.258  6647  6702 D BluetoothAdapter: disable()
,09-08 14:31:54.258  1015  1327 D SettingsProvider: name = bluetooth_on,
,09-08 14:31:54.268  3149  3240 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-08 14:31:54.268  3149  3240 D BluetoothAdapterProperties: Setting state to 13
,09-08 14:31:54.268  3149  3240 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 14:31:54.268  3149  3240 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-08 14:31:54.268  3149  3240 D BluetoothAdapterService: updateAdapterState state is 13
,09-08 14:31:54.268  1015  1135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 14:31:54.268  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-08 14:31:54.278  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:54.278  1015  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:54.278  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 14:31:54.278  3149  3149 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-08 14:31:54.278  3149  3240 D BluetoothAdapterService: Autoconnection is available 
09-08 14:31:54.278  3149  3240 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-08 14:31:54.278  3149  3240 D BluetoothAdapterService: terminating service from this receiver
,09-08 14:31:54.278  3149  3149 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@67a5fe9, channel: 19, state: LISTENING
,09-08 14:31:54.278  3149  3149 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@67a5fe9, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@7431e58, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@228a046emSocket: android.net.LocalSocket@1d31970f impl:android.net.LocalSocketImpl@2ebe139c fd:FileDescriptor[74]
09-08 14:31:54.278  3149  3149 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1d31970f impl:android.net.LocalSocketImpl@2ebe139c fd:FileDescriptor[74]
,09-08 14:31:54.278  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:54.278  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,09-08 14:31:54.288  1173  1173 D BluetoothTile:  onBluetoothStateChange:,
,09-08 14:31:54.288  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-08 14:31:54.288  1173  1716 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 14:31:54.288  1173  1716 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 14:31:54.298  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
09-08 14:31:54.298  1173  1173 D BluetoothTile:  getBluetoothState : 13
,09-08 14:31:54.298  1173  1716 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-08 14:31:54.298  1873  1873 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 14:31:54.298  1015  1463 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 14:31:54.298  1015  1495 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-08 14:31:54.308  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-08 14:31:54.308  1299  1299 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 14:31:54.308  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-08 14:31:54.308  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:54.308  1015  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 14:31:54.308  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 14:31:54.318  6647  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:54.318  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:54.318  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:54.318  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:54.318  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:54.318  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:31:54.318  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:54.318  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:54.318  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:31:54.318  1015  1464 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 14:31:54.318  3149  3240 D BluetoothAdapterProperties: onBluetoothDisable()
,09-08 14:31:54.318  3149  3240 D BluetoothAdapterProperties: mDiscovering is false
09-08 14:31:54.318  3149  3149 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@179011a5, channel: 5, state: LISTENING
,09-08 14:31:54.318  3149  3149 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@179011a5, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ae2ebb1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3855f97amSocket: android.net.LocalSocket@1cfa952b impl:android.net.LocalSocketImpl@3a66cd88 fd:FileDescriptor[76]
09-08 14:31:54.318  3149  3149 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1cfa952b impl:android.net.LocalSocketImpl@3a66cd88 fd:FileDescriptor[76]
,09-08 14:31:54.318  1015  1490 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-08 14:31:54.318  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-08 14:31:54.318  3149  3240 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-08 14:31:54.318  3149  3149 I BtOppRfcommListener: stopping Accept Thread
,09-08 14:31:54.318  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:54.318  3149  3149 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2f952321, channel: 12, state: LISTENING
09-08 14:31:54.318  1015  1464 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:54.318  3149  3149 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2f952321, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@360b82b3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3fba3346mSocket: android.net.LocalSocket@c0b5907 impl:android.net.LocalSocketImpl@385f3a34 fd:FileDescriptor[80]
09-08 14:31:54.318  3149  3149 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@c0b5907 impl:android.net.LocalSocketImpl@385f3a34 fd:FileDescriptor[80]
,09-08 14:31:54.318  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 14:31:54.318  3149  5157 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-08 14:31:54.318  3149  5157 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-08 14:31:54.328  6647  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:54.328  6647  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:31:54.328  6647  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:54.328  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:31:54.328  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:54.328  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:54.328  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:54.328  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:31:54.328  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:54.328  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:54.328  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:31:54.328  6647  6647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:54.328  6647  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:31:54.338  3149  3243 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-08 14:31:54.338  3149  3243 D BluetoothAdapterProperties: Scan Mode:20
,09-08 14:31:54.338  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:54.348  3149  3240 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-08 14:31:54.348  3149  3240 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-08 14:31:54.348  3149  3240 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-08 14:31:54.348  3149  3240 E bt-btif : cmd socket is not created
,09-08 14:31:54.348  3149  3271 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-08 14:31:54.348  3149  3271 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-08 14:31:54.348  1299  1299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 14:31:54.348  3149  3271 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 14:31:54.348  3149  3271 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 14:31:54.348  3149  3271 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-08 14:31:54.348  3149  3240 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-08 14:31:54.348  1015  1490 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-08 14:31:54.348  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-08 14:31:54.358  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:54.358  1015  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:54.358  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-08 14:31:54.358  3149  3149 V BluetoothOppManager: cleanUp...
,09-08 14:31:54.358  1299  1299 D BluetoothPbap: Proxy object disconnected
09-08 14:31:54.358  1299  1299 D PbapServerProfile: Bluetooth service disconnected
,09-08 14:31:54.368  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:54.368  1299  1299 D DockEventReceiver: finishStartingService: stopping service
,09-08 14:31:54.368  1299  1299 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 14:31:54.378  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 14:31:54.378  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-08 14:31:54.378  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-08 14:31:54.388  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:54.388  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:54.388  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:54.388  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:54.398  1015  1028 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7268 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-08 14:31:54.398  7268  7268 E Zygote  : MountEmulatedStorage()
09-08 14:31:54.398  7268  7268 E Zygote  : v2
09-08 14:31:54.398  7268  7268 I libpersona: KNOX_SDCARD checking this for 10055
09-08 14:31:54.398  7268  7268 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:54.408  7268  7268 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-08 14:31:54.408  7268  7268 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 14:31:54.408  7268  7268 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 14:31:54.438  7268  7268 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:54.438  7268  7268 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:54.468  7268  7268 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-08 14:31:54.498  7268  7268 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-08 14:31:54.498  7268  7268 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-08 14:31:54.498  7268  7268 D UserAnalysis: Create SecureDbHelper
,09-08 14:31:54.508  7268  7268 D IntelligenceServiceApplication: onCreate()
,09-08 14:31:54.508  1015  1490 I ActivityManager: Killing 7049:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-08 14:31:54.518  1015  1464 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-08 14:31:54.518  7268  7268 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-08 14:31:54.518  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:54.518  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:54.518  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:54.518  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:54.538  7286  7286 E Zygote  : MountEmulatedStorage(),
,09-08 14:31:54.538  7286  7286 E Zygote  : v2
,09-08 14:31:54.538  7286  7286 I libpersona: KNOX_SDCARD checking this for 10105
09-08 14:31:54.538  7286  7286 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:54.538  7286  7286 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:31:54.538  1015  1464 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7286 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,09-08 14:31:54.538  7286  7286 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-08 14:31:54.538  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-08 14:31:54.538  7268  7268 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.,
09-08 14:31:54.538  7286  7286 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-08 14:31:54.548  7268  7268 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-08 14:31:54.548  3149  3271 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 14:31:54.548  3149  3316 I bt_userial_mct: exiting userial_read_thread
09-08 14:31:54.548  3149  3316 D bt_userial_mct: Leaving userial_evt_read_thread()
09-08 14:31:54.548  3149  3243 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,09-08 14:31:54.548  3149  3274 I bt_vendor: hw_epilog_process
09-08 14:31:54.548  3149  3271 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 14:31:54.548  3149  3271 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 14:31:54.548  3149  3271 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 14:31:54.548  3149  3271 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 14:31:54.548  3149  3271 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 14:31:54.548  3149  3271 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 14:31:54.548  3149  3271 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 14:31:54.548  3149  3271 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-08 14:31:54.548  3149  3271 W bt-btif : ag scb idx 1 not allocated
09-08 14:31:54.548  3149  3271 W bt-btif : ag scb idx 2 not allocated
09-08 14:31:54.548  3149  3271 E bt-btif : BTA AG is already disabled, ignoring ...
09-08 14:31:54.548  3149  3243 D bt_userial_mct: userial_close
09-08 14:31:54.548  3149  3243 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-08 14:31:54.558  7286  7286 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:54.558  7286  7286 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:54.668   258   548 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-08 14:31:54.668   258   548 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 14:31:54.668  7286  7306 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-08 14:31:54.668   258   548 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-08 14:31:54.668   258   548 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 14:31:54.668  7286  7306 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-08 14:31:54.708  1015  1148 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,09-08 14:31:54.728   292   292 E SMD     : DCD OFF
,09-08 14:31:54.778   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 14:31:54.808  7286  7286 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at java.io.File.exists(File.java:363)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-08 14:31:54.808  7286  7286 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 14:31:54.808  7286  7286 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-08 14:31:54.818  7286  7286 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 14:31:54.818  7286  7286 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.q.v.a(PG,:1161)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.q.e.b(PG:170)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 14:31:54.818  7286  7286 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.q.k.d(PG:583)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.q.e.b(PG:170)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a,(PG:48)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 14:31:54.818  7286  7286 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.io.File.exists(File.java:363)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 14:31:54.818  7286  7286 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.io.File.exists(File.java:363)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 14:31:54.818  7286  7286 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 14:31:54.818  7286  7286 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-08 14:31:54.818  1015  1762 I ActivityManager: Killing 6877:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
09-08 14:31:54.818  1997  1997 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-08 14:31:54.828  1997  1997 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-08 14:31:54.868  3149  3243 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-08 14:31:54.868  3149  3243 I bt_vendor: bluetooth satus is on
09-08 14:31:54.868  3149  3243 I bt_vendor: bt-vendor : resetting BT status
09-08 14:31:54.868  3149  3243 I bt_vendor: Starting hciattach daemon
09-08 14:31:54.868  3149  3243 I bt_vendor: try to set false
09-08 14:31:54.868  3149  3243 I bt_vendor: Starting hciattach daemon
09-08 14:31:54.868  3149  3243 I bt_vendor: try to set false
09-08 14:31:54.868  3149  3243 I bt_vendor: cleanup
09-08 14:31:54.868  3149  3271 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-08 14:31:54.868  3149  3243 I GKI_LINUX: GKI_exit_task 0 done
09-08 14:31:54.868  3149  3243 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-08 14:31:54.878  3149  3240 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-08 14:31:54.878  3149  3240 D BtConfig.SecureMode: isSecureModeOn:false
09-08 14:31:54.878  3149  3240 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-08 14:31:54.878  3149  3240 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-08 14:31:54.878  3149  3240 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-08 14:31:54.878  3149  3240 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-08 14:31:54.878  1015  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 14:31:54.878  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-08 14:31:54.878  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:54.878  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:54.878  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 14:31:54.878  3149  3240 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-08 14:31:54.878  3149  3149 D BtGatt.DebugUtils: handleDebugAction() action=null
09-08 14:31:54.878  3149  3240 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-08 14:31:54.878  3149  3240 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-08 14:31:54.878  1015  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 14:31:54.878  3149  3149 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 14:31:54.878  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-08 14:31:54.878  3149  3149 D BtGatt.GattService: stop()
09-08 14:31:54.878  3149  3149 D BtGatt.AdvertiseManager: advertise clients cleared
09-08 14:31:54.878  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:54.878  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:54.878  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 14:31:54.888  3149  3149 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181e229
09-08 14:31:54.888  3149  3240 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-08 14:31:54.888  3149  3240 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-08 14:31:54.888  3149  3240 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-08 14:31:54.888  1015  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 14:31:54.888  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 14:31:54.888  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:54.888  1015  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:54.888  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 14:31:54.888  3149  3240 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-08 14:31:54.888  3149  3240 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-08 14:31:54.888  3149  3240 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-08 14:31:54.898  1015  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 14:31:54.898  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-08 14:31:54.898  1015  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-08 14:31:54.898  1015  1127 V NetworkStats: updateIfacesLocked()
09-08 14:31:54.898  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
09-08 14:31:54.898  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:54.898  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:54.898  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:54.898  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 14:31:54.898  3149  3240 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-08 14:31:54.898  3149  3240 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-08 14:31:54.898  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:31:54.898  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 14:31:54.898  3149  3240 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-08 14:31:54.898  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 14:31:54.898  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-08 14:31:54.898  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:54.898  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:54.898  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 14:31:54.898  7286  7305 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-08 14:31:54.908  3149  3240 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-08 14:31:54.908  3149  3240 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-08 14:31:54.908  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:54.908  1015  1127 V NetworkStats: performPollLocked() took 9ms
09-08 14:31:54.908  3149  3240 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-08 14:31:54.908  1015  1463 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 14:31:54.908  1015  1463 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-08 14:31:54.908  1015  1463 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:54.908  1015  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:54.908  1015  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 14:31:54.908  3149  3240 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-08 14:31:54.908  3149  3240 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-08 14:31:54.908  3149  3240 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-08 14:31:54.908  1015  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-08 14:31:54.908  1015  1762 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 14:31:54.908  1015  1762 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-08 14:31:54.908  1173  1672 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-08 14:31:54.908  1015  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-08 14:31:54.908  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:54.908  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:31:54.908  1015  1762 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:54.908  1015  1762 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:54.908  1015  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 14:31:54.918  3149  3240 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-08 14:31:54.918  3149  3240 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-08 14:31:54.918  1173  1672 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-08 14:31:54.918  4659  6711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-08 14:31:54.918  3149  3240 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-08 14:31:54.918  1015  1762 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 14:31:54.918  1015  1762 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-08 14:31:54.918  1015  1762 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:54.918  1015  1762 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:31:54.918  1015  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 14:31:54.918  4659  6711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-08 14:31:54.918  3149  3240 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-08 14:31:54.918  3149  3240 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-08 14:31:54.918  3149  3240 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-08 14:31:54.918  3149  3240 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-08 14:31:54.918  3149  3240 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-08 14:31:54.928  3149  3240 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-08 14:31:54.928  3149  3240 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-08 14:31:54.928  3149  3240 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-08 14:31:54.928  3149  3240 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-08 14:31:54.928  3149  3240 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,09-08 14:31:54.928  3149  3240 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-08 14:31:54.928  3149  3240 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-08 14:31:54.928  3149  3240 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-08 14:31:54.928  3149  3149 E BluetoothAdapterService(25289257): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-08 14:31:54.928  3149  3149 D HeadsetService: Received stop request...Stopping profile...
,09-08 14:31:54.928  3149  3149 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181e229
,09-08 14:31:54.928  1299  1299 D HeadsetProfile: Bluetooth service disconnected
,09-08 14:31:54.928  3149  3149 D A2dpService: Received stop request...Stopping profile...
09-08 14:31:54.928  3149  3259 D A2dpStateMachine: Exit Disconnected: -1
09-08 14:31:54.928  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-08 14:31:54.938  3149  3149 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181e229
,09-08 14:31:54.938  1015  1015 D BluetoothA2dp: Proxy object disconnected
,09-08 14:31:54.938  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-08 14:31:54.938  1299  1299 D BluetoothA2dp: Proxy object disconnected
09-08 14:31:54.938  1299  1299 D A2dpProfile: Bluetooth service disconnected
,09-08 14:31:54.938  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-08 14:31:54.938  3149  3149 D HidService: Received stop request...Stopping profile...
09-08 14:31:54.938  3149  3149 D HidService: Stopping Bluetooth HidService
,09-08 14:31:54.938  3149  3149 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 14:31:54.938  3149  3149 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-08 14:31:54.938  3149  3149 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 14:31:54.938  3149  3149 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181e229
09-08 14:31:54.938  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:54.938  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:54.938  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-08 14:31:54.938  3149  3149 D HealthService: Received stop request...Stopping profile...
,09-08 14:31:54.948  3149  3149 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181e229
09-08 14:31:54.948  1299  1299 D BluetoothInputDevice: Proxy object disconnected
09-08 14:31:54.948  1299  1299 D HidProfile: Bluetooth service disconnected
,09-08 14:31:54.948  3149  3149 D PanService: Received stop request...Stopping profile...
,09-08 14:31:54.948  3149  3149 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181e229
,09-08 14:31:54.948  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 14:31:54.948  1299  1299 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 14:31:54.948  1299  1299 D PanProfile: Bluetooth service disconnected
,09-08 14:31:54.948  3149  3149 D BluetoothMapService: Received stop request...Stopping profile...
,09-08 14:31:54.948  3149  3149 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181e229
,09-08 14:31:54.948  3149  3149 D SapService: Received stop request...Stopping profile...
,09-08 14:31:54.948  1299  1299 D BluetoothMap: Proxy object disconnected
09-08 14:31:54.948  1299  1299 D MapProfile: Bluetooth service disconnected
09-08 14:31:54.948  3149  3149 D SapService: Stopping Bluetooth SapService
09-08 14:31:54.948  3149  3149 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@181e229
,09-08 14:31:54.958  1299  1299 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-08 14:31:54.958  1299  1299 D SapProfile: Bluetooth service disconnected
,09-08 14:31:54.958  3149  3149 E BluetoothAdapterService(25289257): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-08 14:31:54.958  3149  3149 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 14:31:54.958  3149  3149 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-08 14:31:54.958  3149  3149 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 14:31:54.958  3149  3149 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-08 14:31:54.958  3149  3149 E BluetoothAdapterService(25289257): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-08 14:31:54.958  3149  3149 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 14:31:54.958  3149  3149 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-08 14:31:54.958  3149  3149 D BluetoothA2dp: Proxy object disconnected
09-08 14:31:54.958  3149  3149 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-08 14:31:54.958  3149  3260 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-08 14:31:54.958  3149  3149 I GKI_LINUX: GKI_exit_task 2 done
,09-08 14:31:54.958  3149  3149 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-08 14:31:54.958  3149  3149 E BluetoothAdapterService(25289257): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-08 14:31:54.958  3149  3149 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 14:31:54.958  3149  3149 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-08 14:31:54.958  3149  3149 E BluetoothAdapterService(25289257): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-08 14:31:54.958  3149  3149 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 14:31:54.958  3149  3149 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-08 14:31:54.958  3149  3149 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 14:31:54.958  3149  3149 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 14:31:54.958  3149  3149 E BluetoothAdapterService(25289257): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-08 14:31:54.958  3149  3149 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 14:31:54.958  3149  3149 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-08 14:31:54.958  3149  3149 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-08 14:31:54.958  3149  3149 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-08 14:31:54.968  3149  3149 E BluetoothAdapterService(25289257): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-08 14:31:54.968  3149  3149 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-08 14:31:54.968  3149  3149 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-08 14:31:54.968  3149  3149 E BluetoothAdapterService(25289257): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-08 14:31:54.968  3149  3149 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,09-08 14:31:54.968  3149  3149 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-08 14:31:54.968  3149  3240 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-08 14:31:54.968  3149  3240 D BluetoothAdapterProperties: Setting state to 10
09-08 14:31:54.968  3149  3240 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-08 14:31:54.968  3149  3240 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-08 14:31:54.968  3149  3240 D BluetoothAdapterService: updateAdapterState state is 10
,09-08 14:31:54.968  3149  3240 D BluetoothAdapterService: Autoconnection is available 
09-08 14:31:54.968  3149  3240 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-08 14:31:54.968  3149  3240 I BluetoothAdapterState: Entering OffState
09-08 14:31:54.968  3149  3244 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 14:31:54.968  1299  1310 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 14:31:54.968  1299  1310 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 14:31:54.968  3149  3163 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-08 14:31:54.968  3149  3163 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 14:31:54.978  1441  1458 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 14:31:54.978  1441  1458 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 14:31:54.978  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 14:31:54.978  1299  1310 D Bluetoothsap: onBluetoothStateChange: up=false
09-08 14:31:54.978  1299  1310 D Bluetoothsap: Unbinding service...
09-08 14:31:54.978  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 14:31:54.978  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 14:31:54.978  1299  1312 D BluetoothMap: onBluetoothStateChange: up=false
,09-08 14:31:54.978  1430  3251 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-08 14:31:54.978  1430  3251 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 14:31:54.978  7286  7297 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 14:31:54.978  7286  7297 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 14:31:54.978  1173  1776 D BluetoothAdapter: onBluetoothStateChange: up=false
09-08 14:31:54.978  1173  1776 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 14:31:54.978  1299  1310 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-08 14:31:54.978  1997  2011 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-08 14:31:54.978  1997  2011 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 14:31:54.978  1299  1312 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 14:31:54.978  1299  1310 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 14:31:54.978  6647  7099 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-08 14:31:54.988  6647  7099 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-08 14:31:54.988  6647  7099 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-08 14:31:54.988  6647  7099 D BluetoothLeAdvertiser: Exit stop advertising
09-08 14:31:54.988  6647  7099 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-08 14:31:54.988  6647  7099 D BluetoothLeScanner: Exiting stopAllScan
,09-08 14:31:54.988  1455  1833 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-08 14:31:54.988  1455  1833 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-08 14:31:54.988  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-08 14:31:54.988  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-08 14:31:54.998  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:54.998  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
09-08 14:31:54.998  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-08 14:31:54.998  1173  1173 D BluetoothAdapter: 328663888: getState() :  mService = null. Returning STATE_OFF
,09-08 14:31:54.998  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-08 14:31:55.008  1173  1716 D BluetoothAdapter: 328663888: getState() :  mService = null. Returning STATE_OFF
09-08 14:31:55.008  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-08 14:31:55.008  1173  1173 D BluetoothTile:  getBluetoothState : 10
09-08 14:31:55.008  1173  1716 D BluetoothAdapter: 328663888: getState() :  mService = null. Returning STATE_OFF
,09-08 14:31:55.008  1173  1173 D BluetoothAdapter: 328663888: getState() :  mService = null. Returning STATE_OFF
09-08 14:31:55.008  1173  1173 D BluetoothAdapter: 328663888: getState() :  mService = null. Returning STATE_OFF
09-08 14:31:55.008  1015  1464 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 14:31:55.008  1015  1319 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-08 14:31:55.008  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-08 14:31:55.008  1997  2162 D BluetoothAdapter: 819583430: getState() :  mService = null. Returning STATE_OFF
,09-08 14:31:55.008  1299  1299 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 14:31:55.008  1997  2162 D BluetoothAdapter: 819583430: getState() :  mService = null. Returning STATE_OFF
,09-08 14:31:55.008  1015  1490 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 14:31:55.018  3149  3243 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-08 14:31:55.018  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-08 14:31:55.018  1873  1873 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 14:31:55.018  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:55.018  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:55.018  1015  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:55.018  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 14:31:55.018  3149  3149 I GKI_LINUX: GKI_exit_task 1 done
09-08 14:31:55.018  3149  3149 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-08 14:31:55.018  3149  3149 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 14:31:55.018  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:55.018  1299  1299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 14:31:55.018  1015  1480 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-08 14:31:55.018  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-08 14:31:55.018  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:55.018  1015  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 14:31:55.018  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-08 14:31:55.018  3149  3149 I art     : System.exit called, status: 0
09-08 14:31:55.018  3149  3149 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 14:31:55.028  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-08 14:31:55.038  1299  1299 D DockEventReceiver: finishStartingService: stopping service
,09-08 14:31:55.038  1299  1299 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 14:31:55.048  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 14:31:55.048  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-08 14:31:55.048  1015  1480 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-08 14:31:55.058  1015  1480 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-08 14:31:55.058  1015  1480 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
09-08 14:31:55.058  1015  1480 W BroadcastQueue: android.os.TransactionTooLargeException
09-08 14:31:55.058  1015  1480 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 14:31:55.058  1015  1480 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 14:31:55.058  1015  1480 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-08 14:31:55.058  1015  1480 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-08 14:31:55.058  1015  1480 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-08 14:31:55.058  1015  1480 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-08 14:31:55.058  1015  1480 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-08 14:31:55.058  1015  1480 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-08 14:31:55.058  1015  1480 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-08 14:31:55.058  1015  1480 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-08 14:31:55.058  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:55.058  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:55.058  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:55.058  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:55.068  7325  7325 E Zygote  : MountEmulatedStorage()
,09-08 14:31:55.068  7325  7325 I libpersona: KNOX_SDCARD checking this for 1002
09-08 14:31:55.068  7325  7325 E Zygote  : v2
09-08 14:31:55.068  7325  7325 I libpersona: KNOX_SDCARD not a persona
09-08 14:31:55.068  7325  7325 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 14:31:55.068  1015  1480 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7325 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
09-08 14:31:55.068  7325  7325 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 14:31:55.068  7325  7325 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 14:31:55.088  7325  7325 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:55.088  7325  7325 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:55.108  7325  7325 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-08 14:31:55.108  7325  7325 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-08 14:31:55.128  7325  7325 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-08 14:31:55.158  7325  7325 D BtSettings.ProfileConfig: Adding GattService
,09-08 14:31:55.158  7325  7325 D BtSettings.ProfileConfig: Adding HeadsetService
,09-08 14:31:55.158  7325  7325 D BtSettings.ProfileConfig: Adding A2dpService
09-08 14:31:55.158  7325  7325 D BtSettings.ProfileConfig: Adding HidService
09-08 14:31:55.158  7325  7325 D BtSettings.ProfileConfig: Adding HealthService
,09-08 14:31:55.158  7325  7325 D BtSettings.ProfileConfig: Adding PanService
09-08 14:31:55.158  7325  7325 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-08 14:31:55.158  7325  7325 D BtSettings.ProfileConfig: Adding SapService
09-08 14:31:55.158  7325  7325 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-08 14:31:55.158  7325  7325 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-08 14:31:55.158  7325  7325 D BtSettings.ProfileConfig: Adding SapClientService
,09-08 14:31:55.158  7325  7325 D BtSettings.ProfileConfig: Adding HidDevService
09-08 14:31:55.158  7325  7325 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-08 14:31:55.168  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-08 14:31:55.168  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 14:31:55.168  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 14:31:55.168  1015  1028 D SettingsProvider: selectionArgs: false
09-08 14:31:55.168  1015  1028 D SettingsProvider: selectionArgs: 1002
09-08 14:31:55.168  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 14:31:55.168  1015  1028 D SettingsProvider: ret = -1
,09-08 14:31:55.168  1015  1327 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-08 14:31:55.168  1015  1327 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 14:31:55.168  1015  1327 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 14:31:55.168  1015  1327 D SettingsProvider: selectionArgs: false
,09-08 14:31:55.168  1015  1327 D SettingsProvider: selectionArgs: 1002
09-08 14:31:55.168  1015  1327 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-08 14:31:55.168  1015  1327 D SettingsProvider: ret = -1
,09-08 14:31:55.168  1015  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-08 14:31:55.168  1015  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 14:31:55.168  1015  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 14:31:55.168  1015  1495 D SettingsProvider: selectionArgs: false
09-08 14:31:55.168  1015  1495 D SettingsProvider: selectionArgs: 1002
09-08 14:31:55.168  1015  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 14:31:55.168  1015  1495 D SettingsProvider: ret = -1
,09-08 14:31:55.168  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-08 14:31:55.168  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 14:31:55.168  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 14:31:55.168  1015  1027 D SettingsProvider: selectionArgs: false
09-08 14:31:55.168  1015  1027 D SettingsProvider: selectionArgs: 1002
09-08 14:31:55.168  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 14:31:55.168  1015  1027 D SettingsProvider: ret = -1
,09-08 14:31:55.168  1015  1475 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-08 14:31:55.168  1015  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 14:31:55.168  1015  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 14:31:55.168  1015  1475 D SettingsProvider: selectionArgs: false
09-08 14:31:55.168  1015  1475 D SettingsProvider: selectionArgs: 1002
09-08 14:31:55.168  1015  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 14:31:55.168  1015  1475 D SettingsProvider: ret = -1
09-08 14:31:55.168  1015  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,09-08 14:31:55.168  1015  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 14:31:55.168  1015  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 14:31:55.168  1015  1480 D SettingsProvider: selectionArgs: false
,09-08 14:31:55.168  1015  1480 D SettingsProvider: selectionArgs: 1002
09-08 14:31:55.168  1015  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-08 14:31:55.168  1015  1480 D SettingsProvider: ret = -1
,09-08 14:31:55.168  1015  1464 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-08 14:31:55.168  1015  1464 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-08 14:31:55.168  1015  1464 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 14:31:55.168  1015  1464 D SettingsProvider: selectionArgs: false
09-08 14:31:55.168  1015  1464 D SettingsProvider: selectionArgs: 1002
09-08 14:31:55.168  1015  1464 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-08 14:31:55.178  1015  1464 D SettingsProvider: ret = -1
,09-08 14:31:55.178  1015  1135 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-08 14:31:55.178  1015  1135 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 14:31:55.178  1015  1135 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 14:31:55.178  1015  1135 D SettingsProvider: selectionArgs: false
,09-08 14:31:55.178  1015  1135 D SettingsProvider: selectionArgs: 1002
09-08 14:31:55.178  1015  1135 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 14:31:55.178  1015  1135 D SettingsProvider: ret = -1
09-08 14:31:55.178  1015  1490 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-08 14:31:55.178  1015  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 14:31:55.178  1015  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-08 14:31:55.178  1015  1490 D SettingsProvider: selectionArgs: false
09-08 14:31:55.178  1015  1490 D SettingsProvider: selectionArgs: 1002
09-08 14:31:55.178  1015  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 14:31:55.178  1015  1490 D SettingsProvider: ret = -1
,09-08 14:31:55.178  1015  1762 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-08 14:31:55.178  1015  1762 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 14:31:55.178  1015  1762 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 14:31:55.178  1015  1762 D SettingsProvider: selectionArgs: false
09-08 14:31:55.178  1015  1762 D SettingsProvider: selectionArgs: 1002
09-08 14:31:55.178  1015  1762 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-08 14:31:55.178  1015  1762 D SettingsProvider: ret = -1
,09-08 14:31:55.178  1015  1463 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-08 14:31:55.178  1015  1463 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 14:31:55.178  1015  1463 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 14:31:55.178  1015  1463 D SettingsProvider: selectionArgs: false
,09-08 14:31:55.178  1015  1463 D SettingsProvider: selectionArgs: 1002
09-08 14:31:55.178  1015  1463 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 14:31:55.178  1015  1463 D SettingsProvider: ret = -1
09-08 14:31:55.178  1015  1319 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-08 14:31:55.178  1015  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-08 14:31:55.178  1015  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 14:31:55.178  1015  1319 D SettingsProvider: selectionArgs: false
09-08 14:31:55.178  1015  1319 D SettingsProvider: selectionArgs: 1002
09-08 14:31:55.178  1015  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
09-08 14:31:55.178  1015  1319 D SettingsProvider: ret = -1
,09-08 14:31:55.188  1015  1028 I ActivityManager: Killing 6846:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-08 14:31:55.188  1997  1997 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-08 14:31:55.188  1015  1135 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 14:31:55.188  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-08 14:31:55.188  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:31:55.188  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:55.188  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:55.198  1997  7341 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-08 14:31:55.198  1997  1997 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-08 14:31:55.198  1015  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:55.198  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:55.208  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:55.208  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:55.218  1015  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:31:55.218  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:55.218  1015  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:55.218  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:55.228  1997  7341 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-08 14:31:55.258  7202  7202 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-08 14:31:55.288   259  1037 I SurfaceFlinger: id=14 Removed Uoast (8/9),
09-08 14:31:55.288   259  1096 I SurfaceFlinger: id=14 Removed Uoast (-2/9)
,09-08 14:31:55.288  1015  1463 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1015) eventTime = 140369
,09-08 14:31:55.288  1015  1463 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015 (0x0)
,09-08 14:31:55.298  1015  1463 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1015, ws=WorkSource{10049}) (elapsedTime=3476)
,09-08 14:31:55.388  1015  1464 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-08 14:31:55.388  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-08 14:31:55.388  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:55.388  1015  1464 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,09-08 14:31:55.388  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-08 14:31:55.778   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 14:31:56.358  1015  3349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-08 14:31:56.778   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 14:31:57.308  6893  6893 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,09-08 14:31:57.308  6893  7343 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,09-08 14:31:57.328  1015  2041 V SAMP_SPCM_test: CSC File load.. ,
,09-08 14:31:57.328  6893  7343 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,09-08 14:31:57.338  6893  7343 I ReactiveServiceManager: Supported : 1
,09-08 14:31:57.338  1015  1027 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,09-08 14:31:57.338  1015  1027 D QSEECOMAPI: : App is not loaded in QSEE
,09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-08 14:31:57.348  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-08 14:31:57.358  1015  1027 D QSEECOMAPI: : Loaded image: APP id = 11
,09-08 14:31:57.368  1015  1027 D QSEECOMAPI: : QSEECom_dealloc_memory 
,09-08 14:31:57.368  1015  1027 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,09-08 14:31:57.368  1015  1027 E terrier : handleString: Failed to handle string(-4)
,09-08 14:31:57.368  1015  1027 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,09-08 14:31:57.368  6893  7343 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
09-08 14:31:57.368  6893  7343 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,09-08 14:31:57.378  6893  7343 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-08 14:31:57.378  6893  7343 I PCWCLIENTTRACE_PushUtil: sales region : global
09-08 14:31:57.378  6893  7343 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-08 14:31:57.378  6893  7343 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi,
09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
,09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-08 14:31:57.388  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-08 14:31:57.398  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,09-08 14:31:57.398  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
09-08 14:31:57.398  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-08 14:31:57.398  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
09-08 14:31:57.398  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,09-08 14:31:57.398  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-08 14:31:57.398  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
,09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
,09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
,09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-08 14:31:57.408  1015  2041 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,09-08 14:31:57.408  1015  2041 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,09-08 14:31:57.418  1015  2041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:57.418  1015  2041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:57.418  1015  2041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:31:57.418  1015  2041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:31:57.438  7345  7345 E Zygote  : MountEmulatedStorage(),
09-08 14:31:57.438  7345  7345 I libpersona: KNOX_SDCARD checking this for 1000
,09-08 14:31:57.438  7345  7345 E Zygote  : v2
09-08 14:31:57.438  7345  7345 I libpersona: KNOX_SDCARD not a persona
,09-08 14:31:57.438  7345  7345 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 14:31:57.448  1015  2041 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7345 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-08 14:31:57.448  7345  7345 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:31:57.448  7345  7345 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-08 14:31:57.458  7345  7345 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:31:57.458  7345  7345 D ActivityThread: Added TimaKeyStore provider
,09-08 14:31:57.478  7345  7345 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-08 14:31:57.528  1015  2041 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-08 14:31:57.738   292   292 E SMD     : DCD OFF
,09-08 14:31:57.778   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 14:31:57.998  1015  3328 D SSRM:n  : SIOP:: AP = 340
,09-08 14:31:58.778   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-08 14:31:59.268  7202  7202 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
,09-08 14:31:59.288  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop,
09-08 14:31:59.288  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:59.288  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:59.288  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:59.288  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:59.288  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:31:59.288  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e1aa721 removed from the list
09-08 14:31:59.288  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:31:59.288  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14cb6746 removed from the list
09-08 14:31:59.288  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:31:59.288  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:59.288  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:31:59.288  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:31:59.288  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ca01959 added. We now have 2 listener(s)
,09-08 14:31:59.288  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-08 14:31:59.288  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:59.288  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:31:59.288  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:31:59.288  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bba191e added. We now have 2 listener(s)
09-08 14:31:59.288  6647  6702 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:31:59.288  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:31:59.298  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:31:59.298  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:59.298  6647  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:59.298  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:31:59.298  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:59.298  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:59.298  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:31:59.298  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:59.298  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:59.298  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:31:59.298  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:59.298  6647  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:59.298  6647  6702 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:31:59.298  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:31:59.298  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:31:59.298  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:31:59.298  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:31:59.298  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ca01959 removed from the list
09-08 14:31:59.298  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:31:59.298  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bba191e removed from the list
09-08 14:31:59.298  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:59.298  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:59.298  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:31:59.298  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:31:59.308  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 14:31:59.308  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17486fcc added. We now have 2 listener(s)
09-08 14:31:59.308  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-08 14:31:59.308  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:31:59.308  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:31:59.308  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:31:59.308  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3faff215 added. We now have 2 listener(s)
09-08 14:31:59.308  6647  6702 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:31:59.308  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:31:59.308  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:31:59.318  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-08 14:31:59.318  6647  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:31:59.318  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-08 14:31:59.318  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:31:59.318  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:31:59.318  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:31:59.318  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:59.318  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:31:59.318  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:31:59.318  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:31:59.318  6647  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:31:59.318  6647  6702 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:31:59.318  6647  6702 D BluetoothAdapter: disable()
09-08 14:31:59.318  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:59.318  1015  1027 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.,
09-08 14:31:59.318  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:59.818  6647  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:31:59.818  6647  6702 D BluetoothAdapter: enable()
,09-08 14:31:59.828  1015  1475 W ActivityManager: Permission Denial: getCurrentUser() from pid=6647, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,09-08 14:31:59.828  1015  1475 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
,09-08 14:31:59.828  1015  1475 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6647, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-08 14:31:59.828  1015  1475 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-08 14:31:59.828  1015  1475 W BluetoothManagerService: ,	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-08 14:31:59.828  1015  1475 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-08 14:31:59.828  1015  1475 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-08 14:31:59.828  1015  1475 W BluetoothManagerService: ,	,at android.os.Binder.execTransact(Binder.java:446)
09-08 14:31:59.828  1015  1475 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 14:31:59.828  1015  1475 D SettingsProvider: name = bluetooth_on
09-08 14:31:59.828  1015  1475 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 14:31:59.848  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-08 14:31:59.848  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-08 14:31:59.848  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,09-08 14:31:59.848  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-08 14:31:59.878  7325  7325 D BluetoothAdapterState: make
,09-08 14:31:59.878  7325  7325 I bluedroid: init
,09-08 14:31:59.888  7325  7366 I BluetoothAdapterState: Entering OffState
,09-08 14:31:59.888  7325  7325 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 14:31:59.888  7325  7325 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 14:31:59.888  7325  7325 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 14:31:59.888  7325  7325 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-08 14:31:59.888  7325  7325 E bt-btif : btif_fetch_local_ble_random_bdaddr
,09-08 14:31:59.888  7325  7325 I bluedroid: get_profile_interface socket
09-08 14:31:59.888  7325  7325 I bluedroid: get_profile_interface map_client
,09-08 14:31:59.888  7325  7369 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-08 14:31:59.898  7325  7325 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-08 14:31:59.908  7325  7369 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
09-08 14:31:59.908  7325  7369 E BluetoothServiceJni: populateRssiValuesNative
09-08 14:31:59.908  7325  7369 I bluedroid: getModelRssiValues
09-08 14:31:59.908  7325  7369 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-08 14:31:59.908  7325  7369 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-08 14:31:59.908  7325  7325 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-08 14:31:59.908  1015  1480 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-08 14:31:59.908  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 14:31:59.908  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:59.908  1015  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 14:31:59.908  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 14:31:59.908  7325  7369 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-08 14:31:59.918  1015  1015 D SettingsProvider: name = bluetooth_name
,09-08 14:31:59.918  7325  7333 I bluedroid: config_hci_snoop_log
,09-08 14:31:59.918  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 14:31:59.928  1015  1045 D BluetoothManagerService: Ble is always on enable gatt
,09-08 14:31:59.928  1015  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-08 14:31:59.928  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-08 14:31:59.928  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-08 14:31:59.928  7325  7325 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-08 14:31:59.938  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 14:31:59.938  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-08 14:31:59.948  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-08 14:31:59.948  7325  7366 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-08 14:31:59.948  7325  7366 D BluetoothAdapterProperties: Setting state to 11
09-08 14:31:59.948  7325  7366 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-08 14:31:59.948  7325  7366 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-08 14:31:59.948  7325  7366 D BluetoothAdapterService: updateAdapterState state is 11
,09-08 14:31:59.948  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-08 14:31:59.948  7325  7366 D BluetoothAdapterService: Autoconnection is available 
,09-08 14:31:59.948  7325  7366 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-08 14:31:59.958  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-08 14:31:59.958  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,09-08 14:31:59.968  1873  1873 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 14:31:59.968  7325  7366 D BluetoothSecureManager: getInstant: null
09-08 14:31:59.968  7325  7366 D BluetoothSecureManager: calling getMethod for getService
09-08 14:31:59.968  7325  7366 D BluetoothSecureManager: calling getService
,09-08 14:31:59.968  7325  7366 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@28d8f974
,09-08 14:31:59.968  1015  1327 D BluetoothSecureManagerService: isSecureModeEnabled
09-08 14:31:59.968  1015  1327 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-08 14:31:59.978  1299  1299 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:59.978  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-08 14:31:59.978  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-08 14:31:59.978  1173  1173 D BluetoothTile:  getBluetoothState : 11
09-08 14:31:59.978  7325  7366 D BtConfig.SecureMode: isSecureModeOn:false
09-08 14:31:59.978  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-08 14:31:59.978  1015  1135 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 14:31:59.978  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-08 14:31:59.978  7325  7366 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-08 14:31:59.978  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-08 14:31:59.978  7325  7366 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-08 14:31:59.978  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-08 14:31:59.978  7325  7366 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-08 14:31:59.978  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-08 14:31:59.978  7325  7366 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-08 14:31:59.978  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-08 14:31:59.978  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:59.988  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:31:59.988  1173  1716 D BluetoothTile:  handleUpdatestate:false name:null
09-08 14:31:59.988  7325  7366 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-08 14:31:59.988  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:31:59.988  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-08 14:31:59.988  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:31:59.988  1173  1716 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-08 14:31:59.988  7325  7366 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-08 14:31:59.988  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-08 14:31:59.988  7325  7366 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-08 14:31:59.988  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-08 14:31:59.988  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:31:59.988  7325  7366 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-08 14:31:59.988  1015  1475 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-08 14:31:59.988  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-08 14:31:59.988  7325  7366 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-08 14:31:59.988  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-08 14:31:59.988  7325  7366 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-08 14:31:59.988  1015  1463 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-08 14:31:59.988  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-08 14:31:59.988  1015  1094 V AlarmManager: waitForAlarm result :8
,09-08 14:31:59.988  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-08 14:31:59.988  7325  7366 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-08 14:31:59.988  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-08 14:31:59.988  7325  7366 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-08 14:31:59.998  7325  7366 D BluetoothBondStateMachine: make
,09-08 14:31:59.998  1299  1299 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 14:31:59.998  7325  7366 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-08 14:31:59.998  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-08 14:31:59.998  7325  7366 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-08 14:31:59.998  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:31:59.998  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-08 14:31:59.998  7325  7373 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 14:32:00.008  1015  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 14:32:00.008  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-08 14:32:00.008  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:00.008  1015  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:00.008  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 14:32:00.008  7325  7366 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,09-08 14:32:00.008  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-08 14:32:00.008  7325  7325 D BtGatt.DebugUtils: handleDebugAction() action=null
09-08 14:32:00.008  7325  7366 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-08 14:32:00.008  7325  7325 D BtGatt.GattService: Received start request. Starting profile...
09-08 14:32:00.008  7325  7325 D BtGatt.GattService: start()
09-08 14:32:00.008  7325  7325 D BtGatt.GattService: start()
09-08 14:32:00.008  7325  7325 I bluedroid: get_profile_interface gatt
,09-08 14:32:00.008  7325  7325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@420834f
,09-08 14:32:00.008  7325  7325 D BtGatt.AdvertiseManager: advertise manager created
09-08 14:32:00.018  1015  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 14:32:00.018  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:00.018  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-08 14:32:00.018  1015  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:00.018  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 14:32:00.018  7325  7366 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-08 14:32:00.018  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-08 14:32:00.018  7325  7366 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-08 14:32:00.018  1015  1464 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 14:32:00.018  1015  1464 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-08 14:32:00.028  1015  1464 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:00.028  1015  1464 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 14:32:00.028  1015  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 14:32:00.028  7325  7366 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-08 14:32:00.028  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 14:32:00.028  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-08 14:32:00.028  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-08 14:32:00.028  7325  7366 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-08 14:32:00.028  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:00.028  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-08 14:32:00.028  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 14:32:00.028  7325  7325 D BtGatt.GattService: mStartError = false
,09-08 14:32:00.028  7325  7325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@420834f
,09-08 14:32:00.028  7325  7325 D HeadsetService: Received start request. Starting profile...
,09-08 14:32:00.028  7325  7325 D HeadsetService: start()
,09-08 14:32:00.038  7325  7366 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-08 14:32:00.038  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-08 14:32:00.038  7325  7366 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-08 14:32:00.038  1015  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 14:32:00.038  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-08 14:32:00.038  7325  7325 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-08 14:32:00.038  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:00.038  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:00.038  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 14:32:00.038  7325  7325 D HeadsetStateMachine: make
,09-08 14:32:00.038  7325  7366 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-08 14:32:00.038  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-08 14:32:00.038  7325  7366 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-08 14:32:00.038  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 14:32:00.038  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-08 14:32:00.038  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:00.038  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:00.038  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 14:32:00.038  7325  7325 E HeadsetStateMachine: # of Max HF connection is 2
,09-08 14:32:00.058  7325  7366 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-08 14:32:00.058  1015  1495 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-08 14:32:00.058  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-08 14:32:00.058  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-08 14:32:00.058  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:00.058  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 14:32:00.058  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-08 14:32:00.058  7325  7366 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-08 14:32:00.058  1015  1762 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP,
09-08 14:32:00.058  1015  1762 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:00.058  1015  1762 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-08 14:32:00.058  1015  1762 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:00.058  1015  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-08 14:32:00.058  1015  1135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 14:32:00.058  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-08 14:32:00.058  7325  7325 I bluedroid: get_profile_interface handsfree
,09-08 14:32:00.058  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:00.058  1015  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:00.058  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 14:32:00.068  7325  7366 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-08 14:32:00.068  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-08 14:32:00.068  7325  7366 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-08 14:32:00.068  1015  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 14:32:00.068  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-08 14:32:00.068  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:00.068  1015  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:00.068  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 14:32:00.068  7325  7366 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-08 14:32:00.068  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-08 14:32:00.068  7325  7366 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-08 14:32:00.068  7325  7366 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-08 14:32:00.068  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-08 14:32:00.068  7325  7366 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-08 14:32:00.068  7325  7366 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-08 14:32:00.068  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-08 14:32:00.068  7325  7366 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-08 14:32:00.068  7325  7366 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-08 14:32:00.068  7325  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-08 14:32:00.068  7325  7366 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-08 14:32:00.068  7325  7366 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-08 14:32:00.078  7325  7325 I DualScoManager: Instantiating Dual Sco Manager
09-08 14:32:00.078  7325  7325 I DualScoManager: Set HeadsetServiceHelper
09-08 14:32:00.078  7325  7325 D BluetoothAtMessage: createCMTIContentObservers
,09-08 14:32:00.078  1015  1028 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-08 14:32:00.078  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 14:32:00.078  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 14:32:00.078  1015  1028 D SettingsProvider: selectionArgs: false
09-08 14:32:00.078  1015  1028 D SettingsProvider: selectionArgs: 1002
09-08 14:32:00.078  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 14:32:00.078  1015  1028 D SettingsProvider: ret = -1
,09-08 14:32:00.078  7325  7376 D HeadsetStateMachine: Enter Disconnected: -2
,09-08 14:32:00.078  7325  7325 D HeadsetService: mStartError = false
09-08 14:32:00.078  7325  7325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@420834f
,09-08 14:32:00.088  7325  7325 D A2dpService: Received start request. Starting profile...
09-08 14:32:00.088  7325  7325 D A2dpService: start()
,09-08 14:32:00.088  7325  7376 D HeadsetStateMachine: Clear mHeadsetBrsf
09-08 14:32:00.088  7325  7376 D HeadsetStateMachine: map size, before remove : 0
09-08 14:32:00.088  7325  7376 D HeadsetStateMachine: map size, after remove: 0
,09-08 14:32:00.088  7325  7325 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-08 14:32:00.088  7325  7325 I bluedroid: get_profile_interface avrcp
,09-08 14:32:00.098  1997  1997 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-08 14:32:00.098  7325  7325 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 14:32:00.098  7325  7325 D Avrcp   : Initialize Media Controller
,09-08 14:32:00.098  7325  7325 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-08 14:32:00.098  7325  7325 E Avrcp   : getActiveSessions
,09-08 14:32:00.108  7325  7325 D Avrcp   : pick active media Controller
09-08 14:32:00.108  7325  7325 D Avrcp   : Get the active Media Controller 
,09-08 14:32:00.108  1997  1997 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-08 14:32:00.118  7325  7325 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-08 14:32:00.118  7325  7380 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
09-08 14:32:00.118  7325  7325 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 14:32:00.118  7325  7325 D A2dpStateMachine: make
,09-08 14:32:00.128  7325  7325 I bluedroid: get_profile_interface a2dp
09-08 14:32:00.128  7325  7382 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-08 14:32:00.128  7325  7325 E bt-btif : warning : media task started media_task_refcnt 1 
,09-08 14:32:00.128  7325  7325 D A2dpService: mStartError = false
,09-08 14:32:00.128  7325  7325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@420834f
09-08 14:32:00.128  7325  7325 E BluetoothAdapterService(69239631): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-08 14:32:00.128  7325  7381 D A2dpStateMachine: Enter Disconnected: -2
09-08 14:32:00.128  7325  7325 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 14:32:00.128  7325  7325 D HidService: Received start request. Starting profile...
09-08 14:32:00.128  7325  7325 D HidService: start()
09-08 14:32:00.128  7325  7325 I bluedroid: get_profile_interface hidhost
09-08 14:32:00.128  7325  7325 D HidService: setHidService(): set to: null
09-08 14:32:00.128  7325  7325 D HidService: mStartError = false
09-08 14:32:00.128  7325  7325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@420834f
,09-08 14:32:00.128  7325  7325 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-08 14:32:00.128  7325  7325 D HealthService: Received start request. Starting profile...
09-08 14:32:00.128  7325  7325 D HealthService: start()
,09-08 14:32:00.138  7325  7325 I bluedroid: get_profile_interface health
09-08 14:32:00.138  7325  7325 D HealthService: mStartError = false
09-08 14:32:00.138  7325  7325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@420834f
,09-08 14:32:00.138  7325  7325 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-08 14:32:00.138  7325  7325 D PanService: Received start request. Starting profile...
09-08 14:32:00.138  7325  7325 D PanService: start()
09-08 14:32:00.138  7325  7325 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 14:32:00.138  7325  7325 I bluedroid: get_profile_interface pan
,09-08 14:32:00.138  7325  7325 D PanService: mStartError = false
09-08 14:32:00.138  7325  7325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@420834f
,09-08 14:32:00.138  7325  7325 D HeadsetStateMachine: Try to query the phonestate on bind
,09-08 14:32:00.138  1430  3251 I Telecom : BluetoothPhoneService: queryPhoneState
,09-08 14:32:00.138  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-08 14:32:00.138  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-08 14:32:00.138  1430  3251 I Telecom : BluetoothPhoneService: Result of Message : true
09-08 14:32:00.138  7325  7325 D HeadsetStateMachine: Proxy object connected
,09-08 14:32:00.138  7325  7380 D BluetoothMediaBrowser: no now playing list
09-08 14:32:00.138  7325  7380 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-08 14:32:00.148  7325  7325 D BluetoothMapService: Received start request. Starting profile...
,09-08 14:32:00.148  7325  7325 D BluetoothMapService: start()
,09-08 14:32:00.148  7325  7325 D BluetoothMapService: mStartError = false
09-08 14:32:00.148  7325  7325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@420834f
,09-08 14:32:00.148  7325  7325 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-08 14:32:00.148  7325  7325 D SapService: Received start request. Starting profile...
09-08 14:32:00.148  7325  7325 D SapService: start()
09-08 14:32:00.148  7325  7325 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-08 14:32:00.148  7325  7325 I bluedroid: get_profile_interface sap
09-08 14:32:00.148  7325  7325 D SapService: mStartError = false
09-08 14:32:00.148  7325  7325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@420834f
09-08 14:32:00.148  7325  7325 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-08 14:32:00.148  7325  7325 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-08 14:32:00.148  7325  7376 D HeadsetStateMachine: Disconnected process message: 11
09-08 14:32:00.148  7325  7325 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-08 14:32:00.148  7325  7325 E BluetoothAdapterService(69239631): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-08 14:32:00.148  7325  7325 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-08 14:32:00.148  7325  7325 D BluetoothA2dp: Proxy object connected
09-08 14:32:00.148  7325  7325 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-08 14:32:00.148  7325  7325 E BluetoothAdapterService(69239631): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-08 14:32:00.148  7325  7325 E BluetoothAdapterService(69239631): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-08 14:32:00.148  7325  7325 E BluetoothAdapterService(69239631): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-08 14:32:00.148  7325  7325 E BluetoothAdapterService(69239631): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-08 14:32:00.148  7325  7376 D HeadsetStateMachine: Disconnected process message: 18
09-08 14:32:00.148  7325  7376 D HeadsetStateMachine: Disconnected process message: 10
,09-08 14:32:00.148  7325  7376 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-08 14:32:00.148  7325  7376 D HeadsetStateMachine: Disconnected process message: 11
,09-08 14:32:00.178  7325  7325 E BluetoothAdapterService(69239631): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-08 14:32:00.178  7325  7325 E BluetoothAdapterService(69239631): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-08 14:32:00.188  7325  7366 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-08 14:32:00.188  7325  7366 I bluedroid: enable
,09-08 14:32:00.188  7325  7366 I bt_hci_bdroid: init
,09-08 14:32:00.188  7325  7387 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-08 14:32:00.188  7325  7366 I bt_vendor: bt-vendor : init
,09-08 14:32:00.188  7325  7366 I bt_vendor: bt-vendor : get_bt_soc_type
09-08 14:32:00.188  7325  7366 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-08 14:32:00.188  7325  7366 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
,09-08 14:32:00.188  7325  7366 D bt_userial_mct: userial_init
,09-08 14:32:00.188  7325  7366 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-08 14:32:00.188  7325  7366 I bt_vendor: Starting hciattach daemon
09-08 14:32:00.188  7325  7366 I bt_vendor: try to set false
,09-08 14:32:00.198  7325  7366 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,09-08 14:32:00.198  7325  7366 I bt_vendor: Starting hciattach daemon
09-08 14:32:00.198  7325  7366 I bt_vendor: try to set true
,09-08 14:32:00.208  7391  7391 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-08 14:32:00.258  7397  7397 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-08 14:32:00.268  7398  7398 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-08 14:32:00.288  7400  7400 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-08 14:32:00.298  7401  7401 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-08 14:32:00.298  7402  7402 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-08 14:32:00.308  7403  7403 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-08 14:32:00.538  7406  7406 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,09-08 14:32:00.548  7407  7407 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-08 14:32:00.598  7325  7366 I bt_vendor: bluetooth satus is on
09-08 14:32:00.598  7325  7389 D bt_userial_mct: userial_open(port:0)
09-08 14:32:00.598  7325  7389 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-08 14:32:00.608  7325  7389 I bt_vendor: Done intiailizing UART,
,09-08 14:32:00.608  7325  7389 I bt_vendor: Done intiailizing UART
09-08 14:32:00.608  7325  7389 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67,
09-08 14:32:00.608  7325  7389 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-08 14:32:00.608  7325  7409 D bt_userial_mct: Entering userial_read_thread()
,09-08 14:32:00.618  7325  7387 I         : BTE_InitTraceLevels -- TRC_HCI
09-08 14:32:00.618  7325  7387 I         : BTE_InitTraceLevels -- TRC_L2CAP,
09-08 14:32:00.618  7325  7387 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 14:32:00.618  7325  7387 I         : BTE_InitTraceLevels -- TRC_AVDT,
09-08 14:32:00.618  7325  7387 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 14:32:00.618  7325  7387 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 14:32:00.618  7325  7387 I         : BTE_InitTraceLevels -- TRC_BNEP,
09-08 14:32:00.618  7325  7387 I         : BTE_InitTraceLevels -- TRC_BTM,
09-08 14:32:00.618  7325  7387 I         : BTE_InitTraceLevels -- TRC_GAP
,09-08 14:32:00.618  7325  7387 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 14:32:00.618  7325  7387 I         : BTE_InitTraceLevels -- TRC_SAP
,09-08 14:32:00.618  7325  7387 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 14:32:00.618  7325  7387 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 14:32:00.618  7325  7387 I         : BTE_InitTraceLevels -- TRC_SMP
,09-08 14:32:00.618  7325  7387 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 14:32:00.618  7325  7387 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 14:32:00.618  7325  7387 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-08 14:32:00.708  7325  7387 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-08 14:32:00.718  7325  7387 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4190ed1 
,09-08 14:32:00.718  7325  7387 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4190ed1 
,09-08 14:32:00.728  7325  7369 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-08 14:32:00.728  7325  7369 E bt-btif : Calling BTA_HhEnable
,09-08 14:32:00.728  7325  7369 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-08 14:32:00.738  7325  7369 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-08 14:32:00.738  7325  7369 E BluetoothServiceJni: populateRssiValuesNative
,09-08 14:32:00.738  7325  7369 I bluedroid: getModelRssiValues
09-08 14:32:00.738   292   292 E SMD     : DCD OFF
,09-08 14:32:00.738  7325  7369 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127,
09-08 14:32:00.738  7325  7369 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
09-08 14:32:00.738  7325  7369 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-08 14:32:00.748  1015  1015 D SettingsProvider: name = bluetooth_name
09-08 14:32:00.748  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:00.748  7325  7369 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-08 14:32:00.748  7325  7369 D BluetoothAdapterProperties: Scan Mode:20
09-08 14:32:00.748  7325  7369 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 14:32:00.748  7325  7369 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
09-08 14:32:00.748  7325  7369 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-08 14:32:00.748  7325  7369 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-08 14:32:00.748  7325  7369 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-08 14:32:00.748  7325  7369 E bt-btif : btif_sock_init: !vhci_init
,09-08 14:32:00.748  7325  7369 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-08 14:32:00.748  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:00.748  7325  7369 D IOP_DB_BT: db_open: db_open : handle 3024867344l, read 13894 bytes onto local cache
,09-08 14:32:00.748  7325  7369 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-08 14:32:00.758  7325  7409 E bt_mct  : hci lib postload completed
,09-08 14:32:00.758  7325  7369 D IOP_DB_BT: db_query: result 1
09-08 14:32:00.758  7325  7369 I         : iop_db_open: iop_db_open status 0
,09-08 14:32:00.758  7325  7369 D bte_conf: Device ID record 1 : primary
09-08 14:32:00.758  7325  7369 D bte_conf:   vendorId            = 0075
09-08 14:32:00.758  7325  7369 D bte_conf:   vendorIdSource      = 0001
09-08 14:32:00.758  7325  7369 D bte_conf:   product             = 0100
09-08 14:32:00.758  7325  7369 D bte_conf:   version             = 0200
09-08 14:32:00.758  7325  7369 D bte_conf:   clientExecutableURL = 
09-08 14:32:00.758  7325  7369 D bte_conf:   serviceDescription  = 
09-08 14:32:00.758  7325  7369 D bte_conf:   documentationURL    = 
09-08 14:32:00.758  7325  7369 D bte_conf: bte_load_did_conf no section named DID2.
,09-08 14:32:00.758  7325  7366 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-08 14:32:00.758  7325  7366 D BluetoothAdapterProperties: ScanMode =  20
09-08 14:32:00.758  7325  7366 D BluetoothAdapterProperties: State =  11
,09-08 14:32:00.758  1015  1327 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-08 14:32:00.768  7325  7369 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 14:32:00.768  7325  7366 D BluetoothAdapterProperties: Setting state to 12
09-08 14:32:00.768  7325  7366 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-08 14:32:00.768  7325  7369 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-08 14:32:00.768  7325  7369 D BluetoothAdapterProperties: Scan Mode:21
,09-08 14:32:00.768  7325  7369 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 14:32:00.768  1015  1480 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-08 14:32:00.768  1015  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 14:32:00.768  1015  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 14:32:00.768  1015  1480 D SettingsProvider: selectionArgs: false
09-08 14:32:00.768  1015  1480 D SettingsProvider: selectionArgs: 1002
09-08 14:32:00.768  1015  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 14:32:00.768  1015  1480 D SettingsProvider: ret = -1
,09-08 14:32:00.768  7325  7366 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-08 14:32:00.768  7325  7366 D BluetoothAdapterService: updateAdapterState state is 12
,09-08 14:32:00.778  1015  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 14:32:00.778  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-08 14:32:00.778  6647  6647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-08 14:32:00.778  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:00.778  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:00.778  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 14:32:00.778  7325  7366 D BluetoothAdapterService: Autoconnection is available 
09-08 14:32:00.778  7325  7366 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-08 14:32:00.778  7325  7366 D BluetoothAdapterService: starting service from this receiver
,09-08 14:32:00.778  1015  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-08 14:32:00.788  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-08 14:32:00.788  1430  1452 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 14:32:00.788  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:00.788  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:00.788  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-08 14:32:00.788  6647  6647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-08 14:32:00.798  7325  7366 I BluetoothAdapterState: Entering On State from state = 11
,09-08 14:32:00.798  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-08 14:32:00.798  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 14:32:00.808  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:00.808  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:00.808  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-08 14:32:00.808  1430  1452 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 14:32:00.808  1299  1312 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-08 14:32:00.808  1299  1312 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 14:32:00.808  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:00.808  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:00.808  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:32:00.808  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:00.808  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:00.808  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:00.808  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:32:00.808  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:32:00.818  6647  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:00.818  1430  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 14:32:00.818  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 14:32:00.818  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 14:32:00.818  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:00.818  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:00.818  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-08 14:32:00.818  1430  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 14:32:00.818  7325  7325 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-08 14:32:00.818  1299  1310 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 14:32:00.818  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:00.818  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:00.818  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:32:00.818  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:00.818  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:00.818  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:00.818  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:32:00.818  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:32:00.838  6647  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:32:00.848  6647  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:00.848  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:00.848  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:00.848  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:32:00.848  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:32:00.848  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17486fcc removed from the list
09-08 14:32:00.848  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:00.848  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3faff215 removed from the list
09-08 14:32:00.848  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:00.848  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:32:00.998  1015  1045 I art     : Explicit concurrent mark sweep GC freed 84819(4MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 24MB/36MB, paused 2.496ms total 175.830ms
09-08 14:32:00.998  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 14:32:00.998  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 14:32:00.998  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:00.998  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:00.998  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-08 14:32:00.998  1299  1310 E BluetoothHeadset: BluetoothHeadset service is binded,
09-08 14:32:00.998  7325  7370 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 14:32:00.998  7325  7370 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 14:32:00.998  1015  1045 D BluetoothPan: Binding service...
,09-08 14:32:00.998  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:32:00.998  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25f1031b added. We now have 2 listener(s)
09-08 14:32:00.998  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-08 14:32:00.998  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-08 14:32:00.998  1441  1466 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 14:32:00.998  1441  1466 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 14:32:00.998  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 14:32:00.998  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-08 14:32:01.008  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-08 14:32:01.008  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-08 14:32:01.008  1015  1015 D BluetoothA2dp: Proxy object connected
,09-08 14:32:01.008  1299  1310 D Bluetoothsap: onBluetoothStateChange: up=true
09-08 14:32:01.008  1299  1310 D Bluetoothsap: Binding service...
,09-08 14:32:01.008  1299  1299 D HeadsetProfile: Bluetooth service connected
09-08 14:32:01.008  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-08 14:32:01.008  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:32:01.008  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:32:01.008  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:32:01.008  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1872bcb8 added. We now have 2 listener(s)
09-08 14:32:01.008  6647  6702 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:32:01.008  7325  7325 I BluetoothPbapService: Handler(): got msg=1
,09-08 14:32:01.008  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:32:01.008  1015  1135 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-08 14:32:01.018  1299  1310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-08 14:32:01.018  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-08 14:32:01.018  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-08 14:32:01.018  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.018  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.018  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 14:32:01.018  1299  1310 D Bluetoothsap: bindService called to Bluetooth SAP Service
09-08 14:32:01.018  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 14:32:01.018  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 14:32:01.018  1299  7413 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 14:32:01.018  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:32:01.018  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-08 14:32:01.018  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-08 14:32:01.028  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:01.028  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.028  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-08 14:32:01.028  7325  7414 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-08 14:32:01.028  1430  3251 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 14:32:01.028  1430  3251 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 14:32:01.028  7286  7295 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 14:32:01.028  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 14:32:01.028  7286  7295 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 14:32:01.028  7325  7371 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 14:32:01.028  1299  1299 D Bluetoothsap: BluetoothSAP Proxy object connected
09-08 14:32:01.028  1299  1299 D SapProfile: Bluetooth service connected
09-08 14:32:01.028  1299  1299 D Bluetoothsap: getConnectedDevices()
,09-08 14:32:01.028  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-08 14:32:01.028  6647  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:32:01.028  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:01.028  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:32:01.028  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:01.028  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:01.028  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:01.028  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:32:01.028  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:32:01.028  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 14:32:01.028  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 14:32:01.028  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
09-08 14:32:01.028  1173  4433 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 14:32:01.028  1173  4433 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 14:32:01.028  1299  1310 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 14:32:01.038  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-08 14:32:01.038  1299  1299 D BluetoothMap: Proxy object connected
09-08 14:32:01.038  1299  1299 D MapProfile: Bluetooth service connected
09-08 14:32:01.038  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-08 14:32:01.038  1299  1299 D BluetoothMap: getConnectedDevices()
09-08 14:32:01.038  6647  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:32:01.038  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.038  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.038  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 14:32:01.038  6647  6702 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:32:01.038  7325  7414 D BluetoothSocket: bindListen(): myUserId = 0
09-08 14:32:01.038  7325  7414 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:32:01.038  1015  1319 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-08 14:32:01.038  1015  1319 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-08 14:32:01.038  1015  1319 D SecContentProvider2: mCursor = null
,09-08 14:32:01.038  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:01.038  7325  7414 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-08 14:32:01.038  7325  7414 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 14:32:01.038  7325  7414 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 14:32:01.038  1015  1319 D WifiService: setWifiEnabled: false pid=6647, uid=10171
09-08 14:32:01.038  7325  7414 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ae2ebb1
09-08 14:32:01.038  7325  7414 D BluetoothSocket: channel: 19
09-08 14:32:01.038  7325  7414 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-08 14:32:01.038  1015  1319 D SettingsProvider: name = wifi_on
,09-08 14:32:01.038  1299  1299 D BluetoothInputDevice: Proxy object connected
09-08 14:32:01.038  1299  1299 D HidProfile: Bluetooth service connected
,09-08 14:32:01.038  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:01.048  1455  1467 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 14:32:01.048  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-08 14:32:01.048  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 14:32:01.048  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.048  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.048  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-08 14:32:01.048  1455  1467 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 14:32:01.048  1997  2011 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 14:32:01.048  1997  2011 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 14:32:01.048  1299  1312 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 14:32:01.048  1015  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 14:32:01.048  7141  7141 I wpa_supplicant: reset timer : RESET_TIMER 0
09-08 14:32:01.048  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-08 14:32:01.048  7141  7141 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-08 14:32:01.048  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-08 14:32:01.058  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.058  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.058  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-08 14:32:01.058  1299  1310 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 14:32:01.058  7141  7141 I wpa_supplicant: P2P: Current p2p state = IDLE
09-08 14:32:01.058  1299  1310 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-08 14:32:01.058  1299  1299 D BluetoothPbap: Proxy object connected
09-08 14:32:01.058  1299  1299 D PbapServerProfile: Bluetooth service connected
09-08 14:32:01.058  7141  7141 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-08 14:32:01.058  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-08 14:32:01.058  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-08 14:32:01.058  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.058  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.058  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-08 14:32:01.058  1299  1299 D BluetoothA2dp: Proxy object connected
09-08 14:32:01.058  1299  1299 D A2dpProfile: Bluetooth service connected
,09-08 14:32:01.058  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:32:01.068  1430  1452 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-08 14:32:01.068  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-08 14:32:01.068  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-08 14:32:01.068  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.068  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.068  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-08 14:32:01.068  1430  1452 E BluetoothHeadset: BluetoothHeadset service is binded
,09-08 14:32:01.068  6647  6658 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-08 14:32:01.068  6647  6658 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 14:32:01.068  1299  7413 D BluetoothPan: Binding service...
,09-08 14:32:01.068  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-08 14:32:01.068  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-08 14:32:01.068  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:01.078  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.078  1015  1125 E WifiNative-wlan0: do suspend true
,09-08 14:32:01.078  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-08 14:32:01.078  1299  1299 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 14:32:01.078  1299  1299 D PanProfile: Bluetooth service connected
,09-08 14:32:01.078  1455  1765 D BluetoothAdapter: onBluetoothStateChange: up=true
09-08 14:32:01.078  1455  1765 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-08 14:32:01.078  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-08 14:32:01.078  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-08 14:32:01.078  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-08 14:32:01.078  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
09-08 14:32:01.078  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-08 14:32:01.088  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-08 14:32:01.088  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@30a13b27, true
,09-08 14:32:01.088  1430  1430 D BluetoothHeadset: registerMessageListener
09-08 14:32:01.088  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-08 14:32:01.088  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:32:01.088  1173  1173 D BluetoothTile:  getBluetoothState : 12
,09-08 14:32:01.088  1873  1873 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-08 14:32:01.088  1173  1716 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 14:32:01.098  1299  1299 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-08 14:32:01.098  1173  1716 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 14:32:01.098  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:01.098  1015  1490 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-08 14:32:01.098  1015  1135 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 14:32:01.098  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-08 14:32:01.098  1015  1762 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-08 14:32:01.098  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.098  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:32:01.098  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 14:32:01.098  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-08 14:32:01.108  7325  7371 D HeadsetService: registerMessageListener
,09-08 14:32:01.108  7325  7371 D HeadsetService: registerMessageListener
,09-08 14:32:01.108  1173  1716 D BluetoothTile:  handleUpdatestate:false name:null
,09-08 14:32:01.108  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:01.108  7325  7376 D HeadsetStateMachine: Disconnected process message: 70
09-08 14:32:01.108  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-08 14:32:01.108  7325  7376 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@12547896
09-08 14:32:01.108  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-08 14:32:01.108  1299  1299 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-08 14:32:01.108  1299  1299 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-08 14:32:01.108  1299  1299 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-08 14:32:01.108  1299  1299 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-08 14:32:01.118  7325  7418 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-08 14:32:01.118  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-08 14:32:01.118  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-08 14:32:01.118  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-08 14:32:01.118  7325  7418 D BluetoothSocket: bindListen(): myUserId = 0
,09-08 14:32:01.128  7325  7418 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:32:01.128  1299  1299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 14:32:01.128  7325  7376 D HeadsetStateMachine: Disconnected process message: 9
,09-08 14:32:01.128  7325  7418 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-08 14:32:01.128  7325  7418 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 14:32:01.128  7325  7418 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 14:32:01.128  7325  7418 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@24b93c17
,09-08 14:32:01.128  7325  7418 D BluetoothSocket: channel: 5
09-08 14:32:01.128  7325  7376 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-08 14:32:01.128  1015  1028 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-08 14:32:01.128  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-08 14:32:01.128  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:01.128  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.128  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-08 14:32:01.138  1299  1299 D DockEventReceiver: finishStartingService: stopping service
,09-08 14:32:01.148  1299  1299 D BluetoothNotiBroadcastReceiver: onReceive
,09-08 14:32:01.148   284  1596 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-08 14:32:01.148   284  1596 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,09-08 14:32:01.148   284  1596 V voice   : voice_set_parameters: exit with code(-2)
09-08 14:32:01.148   284  1596 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-08 14:32:01.148   284  1596 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-08 14:32:01.148   284  1596 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-08 14:32:01.148   284  1596 V audio_hw_primary: adev_set_parameters: exit
,09-08 14:32:01.148  7325  7376 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-08 14:32:01.158  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:32:01.158  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-08 14:32:01.158  7325  7325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@420834f
,09-08 14:32:01.158  7325  7325 D BtConfig.SecureMode: isSecureModeOn:false
,09-08 14:32:01.168  1015  1327 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-08 14:32:01.168  1015  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-08 14:32:01.168  1015  1327 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:01.168  1015  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.168  1015  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-08 14:32:01.178  1997  1997 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-08 14:32:01.178  1015  1327 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 14:32:01.178  1015  1327 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-08 14:32:01.188  1015  1327 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:01.188  1015  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:32:01.188  1015  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:32:01.188  1015  1464 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-08 14:32:01.198  1997  7427 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-08 14:32:01.198  1997  1997 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-08 14:32:01.198  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-08 14:32:01.198  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-08 14:32:01.198  1015  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:32:01.208  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:01.208  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 14:32:01.208  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:32:01.208   279   967 D CommandListener: Clearing all IP addresses on wlan0
,09-08 14:32:01.218  1997  7260 V NativeCrypto: Read error: ssl=0xb856aab0: I/O error during system call, Connection timed out
,09-08 14:32:01.218  1997  7260 V NativeCrypto: SSL shutdown failed: ssl=0xb856aab0: I/O error during system call, Broken pipe
09-08 14:32:01.218  1015  1127 E ConnectivityService: updateNetworkInfo()
09-08 14:32:01.218  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:32:01.218  1015  1127 E ConnectivityService: updateNetworkInfo()
09-08 14:32:01.218  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 3
,09-08 14:32:01.218  1997  7260 E GCM     : Wifi connection closed with errorCode 20
,09-08 14:32:01.218  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-08 14:32:01.218  7325  7428 D BluetoothSocket: bindListen(): myUserId = 0
,09-08 14:32:01.218  7325  7428 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:32:01.228  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:32:01.228  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-08 14:32:01.228  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.228  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.228  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.228  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:01.228  1015  1327 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10011
,09-08 14:32:01.228  1015  7200 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
09-08 14:32:01.228  1015  7200 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:01.228  1015  7200 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-08 14:32:01.228  1015  7200 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:01.228  1015  7200 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,09-08 14:32:01.228  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:32:01.228  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 14:32:01.228  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.228  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.228  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.228  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:01.228  1015  7200 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-08 14:32:01.228  1015  7200 I qtaguid : Tagging socket 374 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
,09-08 14:32:01.228  1015  7200 I qtaguid : Untagging socket 374
,09-08 14:32:01.238  1015  7200 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
,09-08 14:32:01.238  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
09-08 14:32:01.238  1015  1015 D RttService: SCAN_AVAILABLE : 1
09-08 14:32:01.238  1015  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 14:32:01.238  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-08 14:32:01.238  1015  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:01.238  1015  1463 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 14:32:01.238  1015  1463 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-08 14:32:01.238  1015  1463 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:01.238  7325  7428 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
09-08 14:32:01.238  7325  7428 D BluetoothSocket: bindListen(), new LocalSocket 
09-08 14:32:01.238  7325  7428 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 14:32:01.238  7325  7428 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@360b82b3
09-08 14:32:01.238  7325  7428 D BluetoothSocket: channel: 12
09-08 14:32:01.238  7325  7428 I BtOppRfcommListener: Accept thread started.
09-08 14:32:01.238  1015  1124 D WifiP2pService: InactiveState{ what=131204 }
09-08 14:32:01.238  1015  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.238  1015  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-08 14:32:01.238  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-08 14:32:01.248  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-08 14:32:01.248  1603  1603 I Hs20UtilService: Starting #18
,09-08 14:32:01.248  1603  1640 I Hs20UtilService: Message received 5007,
,09-08 14:32:01.248  1015  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-08 14:32:01.248  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:01.248  1015  1127 V NetworkStats: updateIfacesLocked()
09-08 14:32:01.248  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
09-08 14:32:01.248   279   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
09-08 14:32:01.248   279   963 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-08 14:32:01.248  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:32:01.248  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 14:32:01.258  1015  7200 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,09-08 14:32:01.258  1015  7200 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-08 14:32:01.258  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:32:01.258  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
09-08 14:32:01.258  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
,09-08 14:32:01.258  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:01.258  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
09-08 14:32:01.258  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-08 14:32:01.258  1015  1127 V NetworkStats: performPollLocked() took 4ms
09-08 14:32:01.258  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-08 14:32:01.258  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-08 14:32:01.258  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-08 14:32:01.258  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 14:32:01.258  1015  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 14:32:01.258  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 14:32:01.258  1299  2233 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 14:32:01.258  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.258  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:32:01.258  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:32:01.268  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-08 14:32:01.268  1015  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,09-08 14:32:01.268  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-08 14:32:01.268  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-08 14:32:01.268  1173  1672 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-08 14:32:01.268  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 14:32:01.268  1015  7200 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:01.268  1015  1046 D WifiDisplayController: disconnect
09-08 14:32:01.268  4659  6711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-08 14:32:01.268  1015  1046 D WifiDisplayController: updateConnection
09-08 14:32:01.268  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:01.268  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 14:32:01.268  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:01.268  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-08 14:32:01.268  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-08 14:32:01.268  1015  1127 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:01.268  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-08 14:32:01.268  1015  1124 D WifiP2pService: P2pDisablingState
09-08 14:32:01.268  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-08 14:32:01.268  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
09-08 14:32:01.268  1455  1455 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:01.268  1015  1124 D WifiP2pService: p2p socket connection lost
09-08 14:32:01.268  1015  1125 E WifiNative-wlan0: do suspend true
09-08 14:32:01.268  1015  1124 D WifiP2pService: P2pDisabledState
09-08 14:32:01.268  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-08 14:32:01.268  1015  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
09-08 14:32:01.268  1015  1124 D WifiP2pService: DefaultState{ what=143375 }
09-08 14:32:01.278  1015  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-08 14:32:01.278  1015  1127 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=false
09-08 14:32:01.278  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-08 14:32:01.278   279   967 D CommandListener: Clearing all IP addresses on wlan0
,09-08 14:32:01.278  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-08 14:32:01.278  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:32:01.278  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
09-08 14:32:01.278  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 14:32:01.278  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-08 14:32:01.278  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.278  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
09-08 14:32:01.278  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.278  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.278  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:01.278  1997  7427 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-08 14:32:01.278  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-08 14:32:01.278  1015  1327 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-08 14:32:01.278  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-08 14:32:01.288  1015  1127 D ConnectivityService: nai.networkMonitor.doQuit()
09-08 14:32:01.288  1015  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-08 14:32:01.288  1015  1127 E ConnectivityService: updateNetworkInfo()
09-08 14:32:01.288  1015  1127 E ConnectivityService: updateNetworkInfo()
,09-08 14:32:01.288  7141  7141 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-08 14:32:01.288  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-08 14:32:01.288  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-08 14:32:01.298  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:32:01.298  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 14:32:01.298  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:01.298  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.298  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.298  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:01.298  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-08 14:32:01.298  1015  1130 D Tethering: MasterInitialState.processMessage what=3
,09-08 14:32:01.298  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:01.298  1015  1122 V NetworkStats: updateIfacesLocked()
09-08 14:32:01.298  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:32:01.298  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
09-08 14:32:01.298  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 14:32:01.298  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:01.298  1015  1122 V NetworkStats: performPollLocked() took 3ms
09-08 14:32:01.298  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:01.298  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:01.298  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:01.298  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:01.298  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,09-08 14:32:01.298  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-08 14:32:01.298  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-08 14:32:01.298  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-08 14:32:01.298  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-08 14:32:01.298  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-08 14:32:01.298  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-08 14:32:01.308  1015  1762 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.308  1015  1762 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 14:32:01.308  1015  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-08 14:32:01.308  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-08 14:32:01.308  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-08 14:32:01.308  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-08 14:32:01.318  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 14:32:01.318  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 14:32:01.318  1015  1125 D SecContentProvider2: mCursor = null
09-08 14:32:01.318  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 14:32:01.318  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.318  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.318  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.318  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:01.318  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:32:01.318  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-08 14:32:01.318  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.318  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 14:32:01.318  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.318  1173  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-08 14:32:01.318  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-08 14:32:01.318  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.318  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 14:32:01.318  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-08 14:32:01.318  1015  1327 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-08 14:32:01.318  1173  1173 D HotspotTile: onReceive : 0, 0
09-08 14:32:01.318  1015  1327 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-08 14:32:01.318  1015  1327 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-08 14:32:01.318  1015  1327 D BatteryService: stay LED for fully charged
09-08 14:32:01.318  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-08 14:32:01.318  1299  1299 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:32:01.328  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:01.328  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:01.328  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:01.328  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:01.328  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:32:01.328  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:32:01.328  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:01.328  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:32:01.328  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:32:01.328  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:32:01.328  6647  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:32:01.328  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-08 14:32:01.328  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 14:32:01.338  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 14:32:01.338  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-08 14:32:01.338  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 14:32:01.338  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:01.338  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:01.338  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:32:01.338  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:32:01.338  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:01.338  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:32:01.338  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:32:01.338  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:32:01.338  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-08 14:32:01.338  1299  2233 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 14:32:01.338  1015  1015 I MotionRecognitionService: Plugged
09-08 14:32:01.338  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-08 14:32:01.338  6647  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:32:01.338  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-08 14:32:01.338  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-08 14:32:01.338  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-08 14:32:01.338  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-08 14:32:01.348  7325  7325 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-08 14:32:01.348  7325  7376 D HeadsetStateMachine: Disconnected process message: 10
,09-08 14:32:01.358  7141  7141 I wpa_supplicant: Blacklist: Clear (all) 
,09-08 14:32:01.358  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-08 14:32:01.358  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:01.358  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:01.358  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:01.358  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:01.358  1173  1173 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
09-08 14:32:01.358  1173  1173 D SViewCoverView: level :100 plugged : 2
,09-08 14:32:01.368  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-08 14:32:01.368  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-08 14:32:01.368  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-08 14:32:01.368  7434  7434 E Zygote  : MountEmulatedStorage(),
09-08 14:32:01.368  7434  7434 E Zygote  : v2
09-08 14:32:01.368  7434  7434 I libpersona: KNOX_SDCARD checking this for 10064
09-08 14:32:01.368  7434  7434 I libpersona: KNOX_SDCARD not a persona
09-08 14:32:01.378  7434  7434 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 14:32:01.368  1015  1028 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7434 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:32:01.378  7434  7434 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:32:01.378  7434  7434 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 14:32:01.398  7434  7434 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:32:01.398  7434  7434 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:01.418  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:32:01.428  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 14:32:01.428  7434  7434 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-08 14:32:01.428  7141  7141 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-08 14:32:01.428  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 14:32:01.428  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-08 14:32:01.428  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:32:01.428  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-08 14:32:01.428  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 14:32:01.428  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-08 14:32:01.428  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 14:32:01.428  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:32:01.438  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 14:32:01.438  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:32:01.438  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 14:32:01.438  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-08 14:32:01.438  7434  7434 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 14:32:01.438  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:32:01.438  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:32:01.438  7434  7434 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-08 14:32:01.438  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:32:01.438  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:32:01.448  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:32:01.448  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:32:01.448  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-08 14:32:01.448  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-08 14:32:01.448  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-08 14:32:01.448  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:32:01.448  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 14:32:01.448  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 14:32:01.448  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-08 14:32:01.448  7141  7141 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-08 14:32:01.448  7141  7141 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-08 14:32:01.448  7141  7141 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-08 14:32:01.448  7141  7141 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-08 14:32:01.448  7141  7141 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-08 14:32:01.448  1015  1130 D Tethering: InitialState.processMessage what=4
09-08 14:32:01.448  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 14:32:01.448  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-08 14:32:01.448  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 14:32:01.448  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-08 14:32:01.458  1015  1130 E Tethering: No numeric data
09-08 14:32:01.458  1015  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 14:32:01.458  1015  1130 D Tethering: clearTetheredNotification()
,09-08 14:32:01.458  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 14:32:01.458  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-08 14:32:01.458  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-08 14:32:01.458  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
09-08 14:32:01.458  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 14:32:01.458  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 14:32:01.458  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 14:32:01.458  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:01.458  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:32:01.458  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-08 14:32:01.458  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-08 14:32:01.458  1173  1173 D HotspotTile: updateTetherState():false, false
09-08 14:32:01.458  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-08 14:32:01.458  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-08 14:32:01.458  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:32:01.458  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 14:32:01.458  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-08 14:32:01.468  1015  1122 V NetworkStats: performPollLocked() took 9ms
,09-08 14:32:01.468  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:01.468  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:01.468  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:01.468  7434  7434 D FileShare-Client: Outbound.stopDelayTimer - 
,09-08 14:32:01.478  6861  6861 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 14:32:01.478  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.478  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.478  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:32:01.488  1015  1135 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 14:32:01.488  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 14:32:01.488  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:01.488  1015  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.488  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 14:32:01.488  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 14:32:01.488  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-08 14:32:01.488  1603  1603 I Hs20UtilService: Starting #19
,09-08 14:32:01.498  1603  1640 I Hs20UtilService: Message received 5007
,09-08 14:32:01.498  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 14:32:01.498  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-08 14:32:01.498  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 14:32:01.498  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 14:32:01.498  1299  2233 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 14:32:01.498  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:01.498  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 14:32:01.498  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:32:01.508  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:01.508  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.508  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:32:01.508  1015  1319 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 14:32:01.508  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 14:32:01.508  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.508  1015  1464 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
09-08 14:32:01.508  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.508  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 14:32:01.518  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:01.508  1603  1603 I Hs20UtilService: Starting #20
09-08 14:32:01.518  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:01.518  1603  1640 I Hs20UtilService: Message received 5011
09-08 14:32:01.518  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-08 14:32:01.518  1015  1464 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:01.528  7465  7465 E Zygote  : MountEmulatedStorage(),
09-08 14:32:01.528  7465  7465 E Zygote  : v2
09-08 14:32:01.528  7465  7465 I libpersona: KNOX_SDCARD checking this for 1000,
09-08 14:32:01.528  7465  7465 I libpersona: KNOX_SDCARD not a persona
09-08 14:32:01.528  7465  7465 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-08 14:32:01.528  7465  7465 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:32:01.528  1015  1464 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7465 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-08 14:32:01.528  7465  7465 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 14:32:01.548  7465  7465 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:32:01.548  7465  7465 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:01.558  6647  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:01.558  1015  1319 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-08 14:32:01.558  1015  1319 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-08 14:32:01.558  1015  1319 D SecContentProvider2: mCursor = null
09-08 14:32:01.558  1015  1319 D WifiService: setWifiEnabled: true pid=6647, uid=10171,
09-08 14:32:01.558  1015  1319 W WifiService: Failed getting userId using ActivityManagerNative
09-08 14:32:01.558  1015  1319 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6647, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-08 14:32:01.558  1015  1319 W WifiService: ,	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-08 14:32:01.558  1015  1319 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-08 14:32:01.558  1015  1319 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-08 14:32:01.558  1015  1319 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-08 14:32:01.558  1015  1319 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-08 14:32:01.558  1015  1319 W ActivityManager: Permission Denial: getCurrentUser() from pid=6647, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-08 14:32:01.558  1015  1319 D SettingsProvider: name = wifi_on
09-08 14:32:01.558   323   323 I art     : Explicit concurrent mark sweep GC freed 8687(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 621us total 26.030ms
,09-08 14:32:01.578   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 17.027ms
,09-08 14:32:01.578  7465  7465 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-08 14:32:01.578  7465  7465 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-08 14:32:01.578  7465  7465 D SecurityLogAgent: StateMachine : Current State = 1
,09-08 14:32:01.588  7465  7465 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 14:32:01.588  1015  1464 I ActivityManager: Killing 6893:com.sec.pcw.device/1000 (adj 15): empty #21
,09-08 14:32:01.588  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:01.588  1015  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 14:32:01.588  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-08 14:32:01.588   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 16.271ms
,09-08 14:32:01.598  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:01.598  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.598  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:32:01.598  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.598  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.598  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:32:01.598  1015  1015 W ActivityManager: userId = 0, bbcId = -10000,
09-08 14:32:01.598  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.598  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:32:01.608  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.608  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.608  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:32:01.608  1015  1015 W ActivityManager: userId = 0, bbcId = -10000,
09-08 14:32:01.608  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.608  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:32:01.608  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.608  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.608  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:32:01.618  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.618  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.618  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:32:01.618  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.618  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.618  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:32:01.618  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.618  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.618  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:32:01.618  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.618  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.618  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:32:01.628  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.628  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:01.628  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-08 14:32:01.648  7141  7141 I wpa_supplicant: Blacklist: Clear (all) 
,09-08 14:32:01.718  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 14:32:01.718  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 14:32:01.718  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 14:32:01.718  7141  7141 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-08 14:32:01.788  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:01.788  1015  1015 I ApplicationPolicy: updateDataUsageMap
,09-08 14:32:01.798  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:01.808  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:01.808  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-08 14:32:01.818  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:01.818  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:32:01.818  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:01.818  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:01.818  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:01.838  7484  7484 E Zygote  : MountEmulatedStorage()
09-08 14:32:01.838  7484  7484 I libpersona: KNOX_SDCARD checking this for 1000
09-08 14:32:01.838  7484  7484 E Zygote  : v2
09-08 14:32:01.838  7484  7484 I libpersona: KNOX_SDCARD not a persona
09-08 14:32:01.838  7484  7484 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:32:01.838  7484  7484 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-08 14:32:01.838  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-08 14:32:01.838  1015  1041 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7484 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-08 14:32:01.838  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-08 14:32:01.848  7484  7484 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 14:32:01.848  6801  6801 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:32:01.858  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:32:01.858  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-08 14:32:01.858  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.858  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.858  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.858  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:01.858  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 14:32:01.858  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-08 14:32:01.858  1173  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-08 14:32:01.858  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:32:01.858  1997  2162 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:32:01.858  1173  1173 D HotspotTile: onReceive : 1, 0
,09-08 14:32:01.858  1299  1299 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:32:01.858  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:01.868  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:01.878  7484  7484 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:32:01.878  7484  7484 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:01.898  7484  7484 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-08 14:32:01.898  7484  7484 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-08 14:32:01.898  7484  7484 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-08 14:32:01.918  7484  7484 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-08 14:32:01.918  7484  7484 I PCWCLIENTTRACE_PushUtil: sales region : global
09-08 14:32:01.918  7484  7484 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-08 14:32:01.918  7484  7484 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:01.918  1015  1495 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
09-08 14:32:01.918  1015  1495 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-08 14:32:01.918  1015  1495 I ActivityManager: Killing 6910:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,09-08 14:32:01.918  7484  7499 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-08 14:32:01.928  1797  1797 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-08 14:32:01.928  1015  1041 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-08 14:32:01.928  1015  1041 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.sconnect/com.samsung.android.sconnect.periph.PeriphStartReceiver}
09-08 14:32:01.928  1015  1041 W BroadcastQueue: android.os.TransactionTooLargeException
09-08 14:32:01.928  1015  1041 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 14:32:01.928  1015  1041 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-08 14:32:01.928  1015  1041 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-08 14:32:01.928  1015  1041 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-08 14:32:01.928  1015  1041 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-08 14:32:01.928  1015  1041 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:195)
09-08 14:32:01.928  1015  1041 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:32:01.928  1015  1041 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:145)
09-08 14:32:01.928  1015  1041 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 14:32:01.928  1015  1041 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-08 14:32:01.928  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-08 14:32:01.928  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:01.928  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:01.928  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:01.938  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:01.948  7501  7501 E Zygote  : MountEmulatedStorage(),
09-08 14:32:01.948  7501  7501 E Zygote  : v2
09-08 14:32:01.948  7501  7501 I libpersona: KNOX_SDCARD checking this for 10121
09-08 14:32:01.948  7501  7501 I libpersona: KNOX_SDCARD not a persona
,09-08 14:32:01.948  7501  7501 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 14:32:01.948  1015  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7501 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-08 14:32:01.948  7501  7501 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-08 14:32:01.958  7501  7501 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 14:32:01.958  6924  6924 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-08 14:32:01.958  1836  1849 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,09-08 14:32:01.958  1797  1797 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-08 14:32:01.958  1797  1797 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-08 14:32:01.968  1797  1797 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-08 14:32:01.968  1797  1797 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-08 14:32:01.978  1797  1797 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-08 14:32:01.978  1797  1797 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-08 14:32:01.988  2744  7516 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-08 14:32:01.988  7501  7501 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:32:01.988  7501  7501 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:01.988  6986  6986 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-08 14:32:01.998  2744  7516 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-08 14:32:01.998  1015  1135 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-08 14:32:01.998  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-08 14:32:01.998  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:01.998  1015  1135 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-08 14:32:01.998  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-08 14:32:01.998  2744  7516 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-08 14:32:01.998  7028  7028 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-08 14:32:01.998  7028  7028 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-08 14:32:01.998  7028  7028 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-08 14:32:01.998  2744  7516 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-08 14:32:02.008  2744  7516 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-08 14:32:02.008  7501  7501 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 14:32:02.008  7501  7501 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-08 14:32:02.008  7501  7501 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-08 14:32:02.008  6986  7517 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-08 14:32:02.018  7028  7028 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-08 14:32:02.018  7028  7028 I SA      : [OR] == isSIMCardReady false ==
,09-08 14:32:02.018  7028  7028 I SA      : [SCU] == networkStateCheck == false
,09-08 14:32:02.018  1015  1319 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-08 14:32:02.018  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-08 14:32:02.018  7028  7028 I SA      : [OR] onReceive END
09-08 14:32:02.018  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:02.018  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:32:02.018  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-08 14:32:02.028  7501  7501 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:02.028  7501  7501 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-08 14:32:02.028  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:02.028  7501  7501 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-08 14:32:02.038  1015  1040 W libprocessgroup: failed to open /acct/uid_10121/pid_6910/cgroup.procs: No such file or directory
,09-08 14:32:02.038  6801  7518 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-08 14:32:02.048  1015  1319 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 14:32:02.058  1015  1319 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 14:32:02.058  1015  1028 I ActivityManager: Killing 6936:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-08 14:32:02.068  1015  1762 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 14:32:02.068  1015  1762 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-08 14:32:02.068  1015  1762 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:02.068  1015  1762 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 14:32:02.068  1015  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:32:02.078  4659  4659 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 14:32:02.088  4659  7120 I iu.UploadsManager: num queued entries: 0
,09-08 14:32:02.088  4659  7120 I iu.UploadsManager: num updated entries: 0
,09-08 14:32:02.088  4659  7120 I iu.SyncManager: NEXT; no task
,09-08 14:32:02.288  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-08 14:32:02.288  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:02.288  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:02.288  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:02.288  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:02.298  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7520 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:32:02.298  7520  7520 E Zygote  : MountEmulatedStorage()
09-08 14:32:02.298  7520  7520 E Zygote  : v2
09-08 14:32:02.298  7520  7520 I libpersona: KNOX_SDCARD checking this for 10001
09-08 14:32:02.298  7520  7520 I libpersona: KNOX_SDCARD not a persona
,09-08 14:32:02.308  7520  7520 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:32:02.308  7520  7520 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-08 14:32:02.308  7520  7520 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-08 14:32:02.328  7520  7520 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:32:02.328  7520  7520 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:02.378  1015  1043 D Tethering: interfaceRemoved wlan0
09-08 14:32:02.378  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-08 14:32:02.398  7008  7008 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:02.398  7008  7008 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-08 14:32:02.398  7008  7008 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-08 14:32:02.398  7008  7008 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-08 14:32:02.418  1015  1028 I ActivityManager: Killing 7345:com.samsung.android.sm/1000 (adj 15): empty #21
,09-08 14:32:02.428  2843  2843 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Sep 08 14:32:02 GMT+02:00 2016
,09-08 14:32:02.428  1015  1490 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-08 14:32:02.428  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-08 14:32:02.428  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:02.428  1015  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:02.428  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-08 14:32:02.438  2843  2843 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-08 14:32:02.438  1015  1027 I splitIntent: Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,09-08 14:32:02.438  1015  1319 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 14:32:02.438  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 14:32:02.438  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:02.438  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 14:32:02.438  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 14:32:02.448  1603  1603 I Hs20UtilService: Starting #21
,09-08 14:32:02.448  1603  1640 I Hs20UtilService: Message received 5011
,09-08 14:32:02.448  2843  2843 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-08 14:32:02.448  7465  7465 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-08 14:32:02.448  7465  7465 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 14:32:02.448  7465  7465 D SecurityLogAgent: StateMachine : Current State = 1
09-08 14:32:02.448  7465  7465 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 14:32:02.448  2843  2843 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-08 14:32:02.458  2843  2843 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-08 14:32:02.458  2843  7537 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-08 14:32:02.458  2843  7537 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-08 14:32:02.468  2843  7537 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-08 14:32:02.468  2843  7537 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-08 14:32:02.468  2843  2843 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-08 14:32:02.578  1015  1043 D Tethering: interfaceRemoved p2p0
,09-08 14:32:02.578  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-08 14:32:02.688  1015  1495 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,09-08 14:32:02.688  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,09-08 14:32:02.688  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:02.688  1015  1495 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,09-08 14:32:02.688  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-08 14:32:02.708  7077  7077 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,09-08 14:32:02.708  7077  7077 D PreloadUpdateManagerStateMachine: exit::IDLE
,09-08 14:32:02.708  7077  7077 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,09-08 14:32:02.708  7077  7077 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:86400000
,09-08 14:32:02.718  7077  7077 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,09-08 14:32:02.718  7077  7077 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,09-08 14:32:02.718  7077  7077 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,09-08 14:32:02.718  7077  7077 D PreloadUpdateManagerStateMachine: entry::IDLE
,09-08 14:32:03.418  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-08 14:32:03.418  1015  1125 E WifiHW  : ##################### set firmware type 0 #####################
,09-08 14:32:03.738   292   292 E SMD     : DCD OFF
,09-08 14:32:03.758  1015  1043 D Tethering: interfaceAdded wlan0,
,09-08 14:32:03.758  1015  1130 E Tethering: No numeric data
,09-08 14:32:03.768  1015  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-08 14:32:03.768  1015  1130 D Tethering: clearTetheredNotification()
,09-08 14:32:03.768  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:03.768  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
09-08 14:32:03.768  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:32:03.768  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-08 14:32:03.768  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 14:32:03.768  1173  1173 D HotspotTile: updateTetherState():false, false
09-08 14:32:03.768  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 14:32:03.768  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-08 14:32:03.768  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-08 14:32:03.778  1015  1130 D Tethering: InitialState.processMessage what=4
,09-08 14:32:03.778  1015  1130 E Tethering: No numeric data
,09-08 14:32:03.778  1015  1122 V NetworkStats: performPollLocked() took 12ms
09-08 14:32:03.778  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:03.778  1015  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-08 14:32:03.778  1015  1130 D Tethering: clearTetheredNotification()
,09-08 14:32:03.778  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-08 14:32:03.788  1173  1173 D HotspotTile: updateTetherState():false, false
,09-08 14:32:03.788  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:03.788  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:03.788  1015  1043 D Tethering: interfaceAdded p2p0
,09-08 14:32:03.788  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-08 14:32:03.788  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-08 14:32:03.788  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:03.798  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-08 14:32:03.798  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 14:32:03.798  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 14:32:03.798  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-08 14:32:03.798  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-08 14:32:03.808  1015  1122 V NetworkStats: performPollLocked() took 11ms
09-08 14:32:03.808  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:03.808   279   967 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-08 14:32:03.808   279   967 D SoftapController: Softap fwReload - Ok
,09-08 14:32:03.808   279   967 D CommandListener: Setting iface cfg
09-08 14:32:03.808   279   967 D CommandListener: Trying to bring down wlan0
,09-08 14:32:03.808  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:03.808  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:03.808   279   967 D CommandListener: Clearing all IP addresses on wlan0
,09-08 14:32:03.808  1015  1125 E WifiHW  : supplicant_name : p2p_supplicant
,09-08 14:32:03.818  1015  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-08 14:32:03.818  1015  1125 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-08 14:32:03.818  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:32:03.828  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-08 14:32:03.828  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:03.828  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:03.828  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:03.828  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:03.828  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 14:32:03.828  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2),
09-08 14:32:03.828  1173  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-08 14:32:03.828  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:32:03.828  1173  1173 D HotspotTile: onReceive : 2, 0
,09-08 14:32:03.828  1299  1299 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-08 14:32:03.828  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:03.838  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:03.838  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 14:32:03.838  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 14:32:03.838  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:03.838  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:03.838  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 14:32:03.848  1603  1603 I Hs20UtilService: Starting #22
,09-08 14:32:03.848  1603  1640 I Hs20UtilService: Message received 5011
,09-08 14:32:03.848  7465  7465 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-08 14:32:03.848  7465  7465 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 14:32:03.848  7465  7465 D SecurityLogAgent: StateMachine : Current State = 1
09-08 14:32:03.848  7465  7465 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-08 14:32:03.848  7547  7547 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-08 14:32:03.848  7547  7547 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-08 14:32:03.858  7547  7547 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-08 14:32:03.868  7547  7547 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-08 14:32:03.868   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7547
09-08 14:32:03.868   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-08 14:32:03.868  7547  7547 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-08 14:32:03.868  7547  7547 I wpa_supplicant: ssSupport state is = 1
09-08 14:32:03.868  7547  7547 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-08 14:32:03.868  7547  7547 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-08 14:32:03.868   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7547
09-08 14:32:03.868   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-08 14:32:04.038   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,09-08 14:32:04.038  7547  7547 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-08 14:32:04.088  7547  7547 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-08 14:32:04.088  7547  7547 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-08 14:32:04.098  7547  7547 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-08 14:32:04.098   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7547
09-08 14:32:04.098   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-08 14:32:04.098  7547  7547 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-08 14:32:04.098  7547  7547 I wpa_supplicant: ssSupport state is = 1
09-08 14:32:04.098  7547  7547 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 14:32:04.098  7547  7547 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 14:32:04.098  7547  7547 E wpa_supplicant: SIM READ ERROR
09-08 14:32:04.098  7547  7547 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 14:32:04.098  7547  7547 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 14:32:04.098  7547  7547 E wpa_supplicant: SIM READ ERROR
09-08 14:32:04.098  7547  7547 I wpa_supplicant: Blacklist: Clear (all) 
09-08 14:32:04.098  7547  7547 I wpa_supplicant: wpa_default_ap_write_once
09-08 14:32:04.098  7547  7547 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-08 14:32:04.098  7547  7547 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 14:32:04.098  7547  7547 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-08 14:32:04.098  7547  7547 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 14:32:04.098  7547  7547 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 14:32:04.098  7547  7547 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-08 14:32:04.098  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 14:32:04.098  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-08 14:32:04.108  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-08 14:32:04.158  7547  7547 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-08 14:32:04.348  7547  7547 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-08 14:32:04.348  7547  7547 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-08 14:32:04.358  7547  7547 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,09-08 14:32:04.358   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7547
09-08 14:32:04.358   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-08 14:32:04.358  7547  7547 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-08 14:32:04.358  7547  7547 I wpa_supplicant: ssSupport state is = 1,
09-08 14:32:04.368  7547  7547 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-08 14:32:04.368  7547  7547 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-08 14:32:04.378  7547  7547 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-08 14:32:04.378   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7547
09-08 14:32:04.378   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-08 14:32:04.378  7547  7547 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-08 14:32:04.378  7547  7547 I wpa_supplicant: ssSupport state is = 1
09-08 14:32:04.388  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-08 14:32:04.378  7547  7547 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-08 14:32:04.378  7547  7547 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 14:32:04.378  7547  7547 E wpa_supplicant: SIM READ ERROR
09-08 14:32:04.378  7547  7547 I wpa_supplicant: wpa_default_ap_write_once
09-08 14:32:04.378  7547  7547 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-08 14:32:04.378  7547  7547 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-08 14:32:04.388  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 14:32:04.388  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
09-08 14:32:04.388  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-08 14:32:04.388  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-08 14:32:04.388  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-08 14:32:04.518  7547  7547 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-08 14:32:04.518  7547  7547 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-08 14:32:04.598  7547  7547 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-08 14:32:04.598  7547  7547 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-08 14:32:04.598  7547  7547 I wpa_supplicant: Skip scan - bUseNetwork false
,09-08 14:32:04.768  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,09-08 14:32:04.768  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
09-08 14:32:04.768  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-08 14:32:04.818  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-08 14:32:04.818  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-08 14:32:04.818  7547  7547 I wpa_supplicant: HOTSPOT20_ENABLE called
09-08 14:32:04.818  7547  7547 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-08 14:32:04.818  7547  7547 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-08 14:32:04.818  7547  7547 E wpa_supplicant: SIM READ ERROR
,09-08 14:32:04.818  7547  7547 I wpa_supplicant: Blacklist: Clear (all) 
,09-08 14:32:04.828  7547  7547 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-08 14:32:04.848  7547  7547 I wpa_supplicant: Skip scan - bUseNetwork false
,09-08 14:32:04.848  1015  1125 D WifiConfigStore: Loading config and enabling all networks 
,09-08 14:32:04.858  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-08 14:32:04.858  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 14:32:04.858  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
09-08 14:32:04.858  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-08 14:32:04.858  1173  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
09-08 14:32:04.858  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-08 14:32:04.858  1173  1173 D HotspotTile: onReceive : 3, 0
,09-08 14:32:04.858  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-08 14:32:04.858  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:04.858  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-08 14:32:04.858  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-08 14:32:04.858  1299  1299 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,09-08 14:32:04.868  1015  1762 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 14:32:04.868  1015  1762 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 14:32:04.868  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:04.868  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:04.868  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:32:04.868  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:04.868  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:04.868  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:32:04.868  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:32:04.868  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:32:04.868  1015  1762 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:04.868  1015  1762 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:04.868  1015  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-08 14:32:04.868  1603  1603 I Hs20UtilService: Starting #23
,09-08 14:32:04.868  6647  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:32:04.868  1603  1640 I Hs20UtilService: Message received 5011
,09-08 14:32:04.868  1015  1125 E WifiConfigStore: Not a HS20
,09-08 14:32:04.878  1015  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 14:32:04.878  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-08 14:32:04.878  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:04.878  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:04.878  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:32:04.878  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:04.878  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:04.878  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:32:04.878  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:32:04.878  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:32:04.878  7465  7465 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-08 14:32:04.878  7465  7465 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-08 14:32:04.878  7465  7465 D SecurityLogAgent: StateMachine : Current State = 1
09-08 14:32:04.878  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-08 14:32:04.878  7465  7465 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-08 14:32:04.878  7547  7547 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-08 14:32:04.878  7547  7547 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-08 14:32:04.878  7547  7547 I wpa_supplicant: reset timer : RESET_TIMER 0
09-08 14:32:04.878  7547  7547 I wpa_supplicant: P2P: Current p2p state = IDLE
09-08 14:32:04.878  7547  7547 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-08 14:32:04.878  7547  7547 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-08 14:32:04.878  7547  7547 I wpa_supplicant: First Scan Start
,09-08 14:32:04.878  7547  7547 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-08 14:32:04.878  1015  1125 D WifiNative-wlan0: Setting external_sim to 1
,09-08 14:32:04.878  1015  1125 D WifiStateMachine: Setting OUI to DA-A1-19
09-08 14:32:04.878  1015  1125 I WifiNative-HAL: startHal
09-08 14:32:04.878  1015  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d4c288c
09-08 14:32:04.878  1015  1125 I WifiNative-HAL: Could not start hal
,09-08 14:32:04.888  6647  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:32:04.888  1015  1125 E WifiNative-wlan0: do suspend true
,09-08 14:32:04.888  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-08 14:32:04.888  6801  6801 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:32:04.888   279   967 D CommandListener: Setting iface cfg,
09-08 14:32:04.888   279   967 D CommandListener: Trying to bring up p2p0
09-08 14:32:04.888  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 14:32:04.888  1015  1124 D WifiP2pService: P2pEnablingState
,09-08 14:32:04.888  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
09-08 14:32:04.888  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-08 14:32:04.888  1015  1124 D WifiP2pService: P2p socket connection successful
,09-08 14:32:04.898  1015  1124 D WifiP2pService: P2pEnabledState
,09-08 14:32:04.898  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
09-08 14:32:04.898  1015  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:04.898  1015  1149 I WifiNative-HAL: startHal
09-08 14:32:04.898  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-08 14:32:04.898  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-08 14:32:04.898  1015  1125 E WifiNative-wlan0: invaild command id : 215
09-08 14:32:04.898  1015  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9e87c9bc
09-08 14:32:04.898  1015  1149 I WifiNative-HAL: Could not start hal
09-08 14:32:04.898  1015  1149 E WifiScanningService: could not start HAL
,09-08 14:32:04.898  1015  1015 D RttService: SCAN_AVAILABLE : 3
,09-08 14:32:04.898  1015  1150 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:04.898  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-08 14:32:04.898  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-08 14:32:04.898  1015  1125 E WifiNative-wlan0: invaild command id : 215
,09-08 14:32:04.898  7547  7547 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-08 14:32:04.898  7547  7547 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-08 14:32:04.898  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-08 14:32:04.898  1015  1125 E WifiStateMachine: Failed to set frequency band 0
09-08 14:32:04.908  7547  7547 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-08 14:32:04.908  1015  1127 E ConnectivityService: updateNetworkInfo()
09-08 14:32:04.908  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 14:32:04.908  1015  1125 D SecContentProvider2: mCursor = null
,09-08 14:32:04.908  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-08 14:32:04.908  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,09-08 14:32:04.908  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-08 14:32:04.908  1015  1046 D WifiDisplayController: disconnect
09-08 14:32:04.908  1015  1046 D WifiDisplayController: updateConnection
09-08 14:32:04.908  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-08 14:32:04.908  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-08 14:32:04.908  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
09-08 14:32:04.908  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,09-08 14:32:04.908  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 14:32:04.908  1015  1125 D SecContentProvider2: mCursor = null
,09-08 14:32:04.908  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-08 14:32:04.908  1015  1124 D WifiP2pService: DeviceAddress: 0a:76:28
09-08 14:32:04.908  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-08 14:32:04.908  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
09-08 14:32:04.908  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-08 14:32:04.908  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
09-08 14:32:04.908  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-08 14:32:04.908  1015  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-08 14:32:04.908  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
09-08 14:32:04.908  1015  1046 D WifiDisplayController:  secondary type: null
09-08 14:32:04.908  1015  1046 D WifiDisplayController:  wps: 0
09-08 14:32:04.908  1015  1046 D WifiDisplayController:  grpcapab: 0
09-08 14:32:04.908  1015  1046 D WifiDisplayController:  devcapab: 0
09-08 14:32:04.908  1015  1046 D WifiDisplayController:  status: 3
09-08 14:32:04.908  1015  1046 D WifiDisplayController:  wfdInfo: null
09-08 14:32:04.908  1015  1046 D WifiDisplayController:  groupownerAddress: null
09-08 14:32:04.908  1015  1046 D WifiDisplayController:  GOdeviceName: null
09-08 14:32:04.908  1015  1046 D WifiDisplayController:  interfaceAddress: 
09-08 14:32:04.908  1015  1046 D WifiDisplayController:  SConnectInfo : null
,09-08 14:32:04.918  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-08 14:32:04.918  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-08 14:32:04.918  1015  1490 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-08 14:32:04.918  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-08 14:32:04.918  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 14:32:04.918  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-08 14:32:04.918  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 14:32:04.918  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 14:32:04.918  1299  2233 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 14:32:04.928  7434  7434 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 14:32:04.928  7434  7434 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-08 14:32:04.928  7434  7434 D FileShare-Client: Outbound.stopDelayTimer - 
,09-08 14:32:04.928  6861  6861 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-08 14:32:04.938  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-08 14:32:04.938  1015  1124 D WifiP2pService: InactiveState
,09-08 14:32:04.938  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
09-08 14:32:04.938  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-08 14:32:04.938  7547  7547 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-08 14:32:04.938  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
09-08 14:32:04.938  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-08 14:32:05.078  6647  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:05.078  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:05.078  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:05.078  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:32:05.078  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:32:05.078  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25f1031b removed from the list
09-08 14:32:05.078  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:05.078  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1872bcb8 removed from the list
09-08 14:32:05.078  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:05.078  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:32:05.088  6647  7554 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-08 14:32:05.088  6647  7554 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 14:32:05.588   279   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 14:32:05.588   279   963 D Netd    : getNetworkForDns: using netid 0 for uid 10171
,09-08 14:32:05.598  6647  7554 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-08 14:32:05.598  6647  7554 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-08 14:32:05.598  6647  7554 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 14:32:05.598  6647  7554 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 14:32:05.598  6647  7554 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-08 14:32:05.598  6647  7556 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-08 14:32:05.598  6647  7556 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-08 14:32:05.598  6647  7556 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 14:32:05.598  6647  7556 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 14:32:05.608  6647  7556 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 14:32:05.608  6647  7561 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1391, name: IncomingSocketThread/Sender)
,09-08 14:32:05.608  6647  7560 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1390, name: OutgoingSocketThread/Receiver)
,09-08 14:32:05.608  6647  7560 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1390, thread name: OutgoingSocketThread/Receiver)
,09-08 14:32:05.608  6647  7560 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-08 14:32:05.608  6647  7560 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1390, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-08 14:32:05.608  6647  7559 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1389, name: OutgoingSocketThread/Sender)
,09-08 14:32:05.608  6647  7562 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1392, name: IncomingSocketThread/Receiver)
,09-08 14:32:05.608  6647  7562 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1392, thread name: IncomingSocketThread/Receiver)
09-08 14:32:05.608  6647  7562 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 14:32:05.608  6647  7562 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1392, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-08 14:32:05.978  7547  7547 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
09-08 14:32:05.978  7547  7547 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-08 14:32:05.978  7547  7547 I wpa_supplicant: Trying to associate with SSID '4E47373030',
09-08 14:32:05.978  7547  7547 I wpa_supplicant: Trying to associate with  'G700',
09-08 14:32:05.978  7547  7547 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-08 14:32:05.978  7547  7547 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
09-08 14:32:05.978  1015  7552 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-08 14:32:05.998  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 14:32:05.998  1015  1125 D SecContentProvider2: mCursor = null
,09-08 14:32:06.088  6647  6702 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-08 14:32:06.098  6647  6702 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-08 14:32:06.098  6647  6702 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4cede3f Bundle[{}]
,09-08 14:32:06.098  6647  6702 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 14:32:06.098  6647  6702 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-08 14:32:06.098  7547  7547 E wpa_supplicant: Cmd 35605 not handled
09-08 14:32:06.098  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 14:32:06.098  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-08 14:32:06.098  7547  7547 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-08 14:32:06.098  7547  7547 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-08 14:32:06.098  7547  7547 I wpa_supplicant: Associated with F4.99.3E
09-08 14:32:06.108  7547  7547 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
09-08 14:32:06.108  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-08 14:32:06.108  6647  6702 D io.jxcore.node.LifeCycleMonitor: onActivityStarted,
09-08 14:32:06.108  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 14:32:06.108  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-08 14:32:06.108  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-08 14:32:06.108  6647  6702 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-08 14:32:06.108  7547  7547 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-08 14:32:06.108  7547  7547 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-08 14:32:06.108  6647  6702 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-08 14:32:06.108  6647  6702 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 14:32:06.108  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-08 14:32:06.108  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-08 14:32:06.108  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-08 14:32:06.118  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
,09-08 14:32:06.118  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,09-08 14:32:06.118  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-08 14:32:06.118  7547  7547 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
09-08 14:32:06.118  7547  7547 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-08 14:32:06.118  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 14:32:06.118  1015  1125 D SecContentProvider2: mCursor = null
,09-08 14:32:06.118  1015  1130 E Tethering: No numeric data
09-08 14:32:06.128  1015  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-08 14:32:06.128  1015  1130 D Tethering: clearTetheredNotification()
09-08 14:32:06.128  7547  7547 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-08 14:32:06.128  7547  7547 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-08 14:32:06.128  7547  7547 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP],
,09-08 14:32:06.128  7547  7547 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,09-08 14:32:06.128  7547  7547 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-08 14:32:06.128  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
09-08 14:32:06.128  7547  7547 I wpa_supplicant: Blacklist: Clear (temp) 
09-08 14:32:06.128  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-08 14:32:06.128  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:06.128  1173  1173 D HotspotTile: updateTetherState():false, false
09-08 14:32:06.128  7547  7547 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-08 14:32:06.128  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-08 14:32:06.128  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
09-08 14:32:06.128  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
09-08 14:32:06.128  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-08 14:32:06.128  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 14:32:06.138  6647  7563 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-08 14:32:06.138  6647  7563 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-08 14:32:06.138  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 14:32:06.138  1015  1125 D SecContentProvider2: mCursor = null
,09-08 14:32:06.138  1015  1122 V NetworkStats: performPollLocked() took 12ms
09-08 14:32:06.138  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:06.138  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:06.138  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:06.148  1015  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-08 14:32:06.158  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,09-08 14:32:06.158  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:32:06.158  1015  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-08 14:32:06.158  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 14:32:06.158  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:32:06.158  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.158  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.158  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.158  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.158  1015  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-08 14:32:06.158  1015  1127 E ConnectivityService: updateNetworkInfo()
09-08 14:32:06.158  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:32:06.158  1015  1327 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 14:32:06.158  1015  1327 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-08 14:32:06.158  1015  1327 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:06.158  1015  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:06.158  1015  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-08 14:32:06.168  1603  1603 I Hs20UtilService: Starting #24
,09-08 14:32:06.168  1603  1640 I Hs20UtilService: Message received 5007
,09-08 14:32:06.168  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
09-08 14:32:06.168  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-08 14:32:06.168  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-08 14:32:06.168  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-08 14:32:06.168  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-08 14:32:06.168  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-08 14:32:06.168  1299  2233 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-08 14:32:06.178  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:32:06.188   279   967 D CommandListener: Setting iface cfg
,09-08 14:32:06.188  1015  1125 E WifiStateMachine: Start Dhcp Watchdog 3,
,09-08 14:32:06.198  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 14:32:06.198  1015  1125 D SecContentProvider2: mCursor = null
,09-08 14:32:06.198  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-08 14:32:06.198  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 14:32:06.198  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.198  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:06.198  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.198  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:06.208  1015  1125 E WifiNative-wlan0: do suspend false
,09-08 14:32:06.208  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-08 14:32:06.218  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
09-08 14:32:06.218  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-08 14:32:06.218  1015  1125 D SecContentProvider2: mCursor = null
,09-08 14:32:06.288  1015  1027 I ActivityManager: Killing 4236:com.google.process.gapps/u0a11 (adj 15): empty #21
,09-08 14:32:06.428  7567  7567 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-08 14:32:06.438  7567  7567 I dhcpcd  : version 5.5.6 starting
,09-08 14:32:06.438  7567  7567 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-08 14:32:06.488  7567  7567 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-08 14:32:06.488  7567  7567 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-08 14:32:06.488  7567  7567 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-08 14:32:06.488  7567  7567 I dhcpcd  : bssid match
09-08 14:32:06.488  7567  7567 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,09-08 14:32:06.548  7567  7567 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,09-08 14:32:06.618  7567  7567 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,09-08 14:32:06.738   292   292 E SMD     : DCD OFF,
,09-08 14:32:06.768  7325  7367 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-08 14:32:06.828  1015  1125 E WifiNative-wlan0: do suspend true,
,09-08 14:32:06.848  1015  1124 D WifiP2pService: InactiveState{ what=143375 },
09-08 14:32:06.848  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-08 14:32:06.858  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 14:32:06.858  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-08 14:32:06.858  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:06.858  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-08 14:32:06.858  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.858  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:06.858  1015  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-08 14:32:06.858  1015  1125 E WifiStateMachine: VerifyingLinkState enter,
,09-08 14:32:06.868  1015  1127 E ConnectivityService: updateNetworkInfo()
09-08 14:32:06.868  1015  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null,
09-08 14:32:06.868  1015  1127 D ConnectivityService: Adding iface wlan0 to network 504
09-08 14:32:06.868  1015  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,09-08 14:32:06.878  1015  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
09-08 14:32:06.878  1015  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-08 14:32:06.878  1015  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-08 14:32:06.878  1015  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-08 14:32:06.888  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-08 14:32:06.888  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 14:32:06.888  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.888  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-08 14:32:06.888  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.888  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:06.898  1015  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check,
,09-08 14:32:06.898  1015  1475 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 14:32:06.898  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-08 14:32:06.908  1015  1475 W ActivityManager: userId = 0, bbcId = -10000,
09-08 14:32:06.908  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:06.908  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-08 14:32:06.908  1603  1603 I Hs20UtilService: Starting #25
09-08 14:32:06.908  1603  1640 I Hs20UtilService: Message received 5007
09-08 14:32:06.908  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-08 14:32:06.908  1299  1299 I NearbySettings: MountReceiver.onReceive - Keep current state,
,09-08 14:32:06.918  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 14:32:06.918  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-08 14:32:06.918  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-08 14:32:06.918  1015  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,09-08 14:32:06.928  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:32:06.928  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-08 14:32:06.928  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.928  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.928  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.928  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:06.928  1015  1127 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,09-08 14:32:06.928  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-08 14:32:06.928  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
09-08 14:32:06.928  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
,09-08 14:32:06.928  1015  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,09-08 14:32:06.928  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:32:06.928  1015  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 14:32:06.928  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-08 14:32:06.928  1015  1127 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-08 14:32:06.928  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.928  1015  1127 D ConnectivityService: LTETest block dns file not exists
09-08 14:32:06.928  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.928  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.928  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:06.938  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:06.938  1015  1127 V NetworkStats: updateIfacesLocked()
09-08 14:32:06.938  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
,09-08 14:32:06.948  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:32:06.948  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 14:32:06.948  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:06.948  1015  1127 V NetworkStats: performPollLocked() took 5ms
,09-08 14:32:06.948  1015  1127 E ConnectivityService: updateNetworkInfo()
09-08 14:32:06.948  1015  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-08 14:32:06.948  1015  1127 E ConnectivityService: updateNetworkInfo()
09-08 14:32:06.948  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-08 14:32:06.948  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:06.948  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:06.948  1015  1127 V NetworkStats: updateIfacesLocked()
09-08 14:32:06.948  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:06.948  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
,09-08 14:32:06.948  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:32:06.948  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 14:32:06.958  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:06.958  1015  1127 V NetworkStats: performPollLocked() took 5ms
,09-08 14:32:06.958  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-08 14:32:06.958  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-08 14:32:06.958  1015  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-08 14:32:06.958  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,09-08 14:32:06.958  1015  7565 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:06.958  1015  7565 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-08 14:32:06.958  1015  7565 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-08 14:32:06.958  1015  7565 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-08 14:32:06.958  1015  1028 W ActivityManager: userId = 0, bbcId = -10000,
09-08 14:32:06.968  1015  1127 D ConnectivityService:    accepting network in place of null
09-08 14:32:06.958  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:06.958  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-08 14:32:06.958  1015  7565 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-08 14:32:06.968  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:06.968  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:06.968  1603  1603 I Hs20UtilService: Starting #26
09-08 14:32:06.968  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-08 14:32:06.968  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-08 14:32:06.968   279   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 14:32:06.968   279   963 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,09-08 14:32:06.968  1015  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-08 14:32:06.968  1015  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-08 14:32:06.968  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-08 14:32:06.968  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,09-08 14:32:06.968  1455  1455 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-08 14:32:06.968  1015  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-08 14:32:06.968  1603  1640 I Hs20UtilService: Message received 5007
09-08 14:32:06.968  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-08 14:32:06.968  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-08 14:32:06.968  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-08 14:32:06.978  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-08 14:32:06.978  1015  1130 D Tethering: MasterInitialState.processMessage what=3
,09-08 14:32:06.978  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
09-08 14:32:06.978  1015  1122 V NetworkStats: updateIfacesLocked()
09-08 14:32:06.978  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:06.978  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-08 14:32:06.978  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-08 14:32:06.978  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-08 14:32:06.978  1299  1299 I NearbySettings: MountReceiver.onReceive - Keep current state
09-08 14:32:06.978  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:32:06.978  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-08 14:32:06.988  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:06.988  1015  1122 V NetworkStats: performPollLocked() took 5ms
,09-08 14:32:06.988  1173  1672 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-08 14:32:06.988  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-08 14:32:06.988  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,09-08 14:32:06.988  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-08 14:32:06.988  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-08 14:32:06.988  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-08 14:32:06.988  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-08 14:32:06.988  4659  6711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 14:32:06.988  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:06.998  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:06.998  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-08 14:32:06.998  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:06.998  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:06.998  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:06.998  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:06.998  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-08 14:32:06.998  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-08 14:32:06.998  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-08 14:32:06.998  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-08 14:32:06.998  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-08 14:32:06.998  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.998  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.998  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:06.998  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:07.008  1015  1463 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-08 14:32:07.008  1015  1463 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-08 14:32:07.008  1015  1463 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:07.008  1015  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:07.008  1015  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-08 14:32:07.008  1603  1603 I Hs20UtilService: Starting #27
,09-08 14:32:07.008  1603  1640 I Hs20UtilService: Message received 5007
,09-08 14:32:07.018  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-08 14:32:07.018  1299  1299 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-08 14:32:07.018  1015  1028 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-08 14:32:07.018  1015  1135 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-08 14:32:07.018  1015  1135 D SecContentProvider2: mCursor = null
,09-08 14:32:07.018  1015  1495 D SecContentProvider2: uri = 15 selection = getToastGravity,
09-08 14:32:07.018  1015  1495 D SecContentProvider2: mCursor = null
09-08 14:32:07.028  1015  1463 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset,
09-08 14:32:07.028  1015  1463 D SecContentProvider2: mCursor = null
,09-08 14:32:07.028  1015  1475 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-08 14:32:07.028  1015  1475 D SecContentProvider2: mCursor = null
,09-08 14:32:07.028  1015  1464 D SecContentProvider2: uri = 15 selection = getToastEnabledState,
09-08 14:32:07.028  1015  1464 D SecContentProvider2: mCursor = null
09-08 14:32:07.028  1015  1327 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState,
09-08 14:32:07.028  1015  1327 D SecContentProvider2: mCursor = null
,09-08 14:32:07.058   259   259 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,09-08 14:32:07.068  1015  1495 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,09-08 14:32:07.068  1015  7565 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,09-08 14:32:07.078  1173  1173 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-08 14:32:07.148  1015  7565 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 12:32:07 GMT], X-Android-Received-Millis=[1473337927151], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473337927107]}
,09-08 14:32:07.148  1015  7565 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-08 14:32:07.148  1015  7565 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-08 14:32:07.148  1015  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-08 14:32:07.148  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-08 14:32:07.148  1015  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-08 14:32:07.148  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-08 14:32:07.148  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 14:32:07.148  4659  6711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-08 14:32:07.148  1173  1672 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-08 14:32:07.148  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-08 14:32:07.148  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-08 14:32:07.148  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-08 14:32:07.148  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-08 14:32:07.148  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-08 14:32:07.148  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-08 14:32:07.148  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-08 14:32:07.148  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-08 14:32:07.148  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-08 14:32:07.158  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-08 14:32:07.158  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-08 14:32:07.158  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:07.158  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:07.158  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-08 14:32:07.158  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-08 14:32:07.478  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:07.498  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:07.508  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:32:07.508  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:07.508  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:32:07.508  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:07.508  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:07.508  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
09-08 14:32:07.508  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:32:07.508  6647  6647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:32:07.508  7484  7484 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-08 14:32:07.508  7484  7484 I PCWCLIENTTRACE_PushUtil: sales region : global
09-08 14:32:07.508  7484  7484 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-08 14:32:07.508  7484  7484 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:07.508  6647  6647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:32:07.508  1015  1028 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,09-08 14:32:07.518  1015  1028 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-08 14:32:07.528  1797  1797 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-08 14:32:07.528  7501  7501 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:07.538  1015  1463 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-08 14:32:07.538  1015  1463 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,09-08 14:32:07.538  7501  7501 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
09-08 14:32:07.538  7501  7501 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
09-08 14:32:07.538  1836  2335 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,09-08 14:32:07.538  1015  1463 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:07.538  1015  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:07.538  1015  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-08 14:32:07.548  1797  1797 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-08 14:32:07.548  1797  1797 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-08 14:32:07.548  1797  1797 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-08 14:32:07.548  7008  7008 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:07.548  1797  1797 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
09-08 14:32:07.548  7008  7008 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-08 14:32:07.548  7008  7008 I DIAGMON_AGENT: ./extraInfo: "NG700"
,09-08 14:32:07.548  7008  7008 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-08 14:32:07.558  1015  1028 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 14:32:07.558  1015  1135 D RCPManagerService: exchangeData() failure , invalid userId
,09-08 14:32:07.568  1797  1797 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-08 14:32:07.578  1797  1797 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-08 14:32:07.588  7077  7077 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-08 14:32:07.588  2744  7604 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-08 14:32:07.588  1015  1475 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
09-08 14:32:07.588  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,09-08 14:32:07.588  2744  7604 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
09-08 14:32:07.588  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:07.588  1015  1475 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-08 14:32:07.588  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-08 14:32:07.598  2744  7604 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-08 14:32:07.598  1015  1480 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
09-08 14:32:07.598  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,09-08 14:32:07.598  7077  7077 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,09-08 14:32:07.598  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:07.598  1015  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:32:07.598  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,09-08 14:32:07.608  7077  7077 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
09-08 14:32:07.608  7077  7077 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
09-08 14:32:07.608  7077  7077 D InitializeManagerStateMachine: exit::IDLE
09-08 14:32:07.608  7077  7077 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,09-08 14:32:07.608  7077  7077 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
09-08 14:32:07.608  7077  7077 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-08 14:32:07.608  7077  7077 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-08 14:32:07.608  7077  7077 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-08 14:32:07.608  7077  7077 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-08 14:32:07.608  7077  7077 D InitializeManagerStateMachine: entry::SUCCESS
09-08 14:32:07.608  7077  7077 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
09-08 14:32:07.608  6986  6986 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,09-08 14:32:07.618  1015  1135 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 14:32:07.618  7028  7028 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-08 14:32:07.618  7028  7028 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
09-08 14:32:07.618  7028  7028 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
09-08 14:32:07.618  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-08 14:32:07.618  7077  7077 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-08 14:32:07.618  7077  7077 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
09-08 14:32:07.618  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:07.618  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:32:07.618  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 14:32:07.618  7077  7077 D InitializeManagerStateMachine: exit::SUCCESS
09-08 14:32:07.618  7077  7077 D InitializeManagerStateMachine: entry::IDLE
,09-08 14:32:07.628  1015  1475 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-08 14:32:07.628  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-08 14:32:07.628  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:07.628  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:32:07.628  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-08 14:32:07.628   279   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 14:32:07.628   279   963 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,09-08 14:32:07.638  7028  7028 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-08 14:32:07.638  7028  7028 I SA      : [OR] == isSIMCardReady false ==
,09-08 14:32:07.638  7028  7028 I SA      : [SCU] == networkStateCheck == true
,09-08 14:32:07.638  7028  7028 I SA      : [DM] getCountryCodeFromCSC : PL
09-08 14:32:07.638  7028  7028 I SA      : isChinaCountryCode : false
09-08 14:32:07.638  7028  7028 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-08 14:32:07.638  7028  7028 I SA      : [OR] == networkStateCheck true ==
09-08 14:32:07.638  7028  7028 I SA      : [OR] GetMyCountryZoneTask
,09-08 14:32:07.638  7028  7028 I SA      : [OR] onReceive END
,09-08 14:32:07.638  2744  7604 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,09-08 14:32:07.638  2744  7604 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,09-08 14:32:07.648  2744  7604 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,09-08 14:32:07.648  2744  7604 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,09-08 14:32:07.648  7028  7610 I SA      : [SRS] prepareGetMyCountryZone
,09-08 14:32:07.648  6801  7608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-08 14:32:07.648  2744  7604 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,09-08 14:32:07.648  6801  7608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-08 14:32:07.648  2744  7604 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,09-08 14:32:07.648   279   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 14:32:07.648   279   963 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,09-08 14:32:07.648  2744  7604 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,09-08 14:32:07.648  4659  4659 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 14:32:07.648  2744  7604 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,09-08 14:32:07.648  7028  7610 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-08 14:32:07.648  7028  7610 I SA      : [SSP] query invoked
,09-08 14:32:07.658  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:32:07.658  2744  7604 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,09-08 14:32:07.658  7028  7610 I SA      : [TPMU] GetMccFromDB : null
09-08 14:32:07.658  7028  7610 I SA      : [SCU] getMccFromPreferece mcc = 260
09-08 14:32:07.658  7028  7610 I SA      : [LBE] isSupportCheckDomainRegion : false
09-08 14:32:07.658  7028  7610 I SA      : [TPM] isNoProxy(default) : true
09-08 14:32:07.658  7028  7610 I SA      : [RC New] Execute method=[GET] start
,09-08 14:32:07.658  1015  1327 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,09-08 14:32:07.658  1015  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,09-08 14:32:07.658  1015  1327 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:07.658  1015  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 14:32:07.668  1015  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,09-08 14:32:07.668  4659  7120 I iu.UploadsManager: num queued entries: 0
,09-08 14:32:07.668  4659  7120 I iu.UploadsManager: num updated entries: 0
,09-08 14:32:07.668  4659  7120 I iu.SyncManager: NEXT; no task
,09-08 14:32:07.668  2744  7604 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-08 14:32:07.678  1015  1480 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
09-08 14:32:07.678  1015  1480 D SecContentProvider2: mCursor = null
,09-08 14:32:07.698  7028  7610 I SA      : [RC New] Security=[true]
,09-08 14:32:07.698  7028  7610 I System.out: Thread-1278(ApacheHTTPLog):isSBSettingEnabled false
09-08 14:32:07.698  7028  7610 I System.out: Thread-1278(ApacheHTTPLog):isShipBuild true
09-08 14:32:07.698  7028  7610 I System.out: Thread-1278(ApacheHTTPLog):SMARTBONDING_ENABLED is false
09-08 14:32:07.698  7028  7610 I System.out: Thread-1278(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,09-08 14:32:07.698   279   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 14:32:07.698   279   963 D Netd    : getNetworkForDns: using netid 504 for uid 10036
,09-08 14:32:07.698  6801  7608 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-08 14:32:07.698  7101  7101 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-08 14:32:07.708  7101  7101 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,09-08 14:32:07.708  7101  7101 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,09-08 14:32:07.708  7101  7101 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,09-08 14:32:07.718  2843  2843 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Sep 08 14:32:07 GMT+02:00 2016
,09-08 14:32:07.718  1015  1480 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-08 14:32:07.718  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-08 14:32:07.718  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:07.718  1015  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:07.718  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-08 14:32:07.718  2843  2843 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-08 14:32:07.718  1015  1027 I splitIntent: Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,09-08 14:32:07.728  2843  2843 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-08 14:32:07.728  2843  2843 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-08 14:32:07.728  2843  2843 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-08 14:32:07.728  2843  7614 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-08 14:32:07.728  2843  7614 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-08 14:32:07.738  2843  7614 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,09-08 14:32:07.738  2843  7614 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,09-08 14:32:07.738  2843  7614 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,09-08 14:32:07.748  2843  7614 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,09-08 14:32:07.748  2843  7614 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-08 14:32:07.748  2843  2843 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-08 14:32:07.778  6801  7608 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 14:32:07.788  1997  7607 I qtaguid : Tagging socket 47 with tag 1000040700000000{268436487,0} for uid -1, pid: 1997, getuid(): 10011
,09-08 14:32:07.938  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:07.938  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:32:07.938  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-08 14:32:07.978  1015  1127 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 503] cleared because we found a replacement network
,09-08 14:32:08.018  1015  3328 D SSRM:n  : SIOP:: AP = 330
,09-08 14:32:08.268  7028  7610 I SA      : [RC New] [v2liruge] api execute + 572
,09-08 14:32:08.268  7028  7610 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
09-08 14:32:08.268  7028  7610 I System.out: AsyncTask #2 calls detatch(),
09-08 14:32:08.268  7028  7610 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,09-08 14:32:08.268  7028  7610 I SA      : [OCP] update openData : PL,
,09-08 14:32:08.278  7028  7610 I SA      : [TPMU] getNetworkMcc : 
09-08 14:32:08.278  7028  7610 I SA      : [SCU] saveMccToPreferece Start,
09-08 14:32:08.278  7028  7610 I SA      : [SCU] RegionMCC : 260
,09-08 14:32:08.278  7028  7610 I SA      : [SSP] query invoked
,09-08 14:32:08.278  7028  7610 I SA      : [TPMU] GetMccFromDB : null
,09-08 14:32:08.278  7028  7610 I SA      : [SCU] getMccFromPreferece mcc = 260
,09-08 14:32:08.288  7028  7610 I SA      : [SCU] saveMccToPreferece End
,09-08 14:32:08.288  7028  7610 I SA      : [RC New] executeRequest [v2liruge] end. 625
09-08 14:32:08.288  7028  7610 I SA      : [RC New] Execute end
,09-08 14:32:08.288  7028  7028 I SA      : [OR] GetMyCountryZoneTask mcc = 260
09-08 14:32:08.288  7028  7028 I SA      : [OR] GetMyCountryZoneTask Success
,09-08 14:32:08.448  1015  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-08 14:32:08.448  1015  1127 V NetworkStats: updateIfacesLocked()
,09-08 14:32:08.448  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
,09-08 14:32:08.448  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:08.458  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 14:32:08.458  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 14:32:08.458  1015  1127 V NetworkStats: performPollLocked() took 7ms
,09-08 14:32:08.458  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:08.458  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:08.458  1015  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-08 14:32:08.458  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:08.458  1015  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-08 14:32:08.458  1173  1672 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-08 14:32:08.468  4659  6711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-08 14:32:08.468  1173  1672 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-08 14:32:08.468  4659  6711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-08 14:32:09.128   279   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-08 14:32:09.128   279   963 D Netd    : getNetworkForDns: using netid 504 for uid 10171
,09-08 14:32:09.128  6647  7563 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-08 14:32:09.128  6647  7563 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 14:32:09.128  6647  7563 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:09.128  6647  7563 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:09.128  6647  7563 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-08 14:32:09.138  6647  7616 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-08 14:32:09.138  6647  7616 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 14:32:09.138  6647  7616 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:32:09.138  6647  7619 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1403, name: OutgoingSocketThread/Sender)
,09-08 14:32:09.138  6647  7620 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1404, name: OutgoingSocketThread/Receiver)
,09-08 14:32:09.138  6647  7616 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 14:32:09.138  6647  7616 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 14:32:09.138  6647  7620 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1404, thread name: OutgoingSocketThread/Receiver)
,09-08 14:32:09.138  6647  7620 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 14:32:09.138  6647  7620 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1404, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-08 14:32:09.138  6647  7622 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1406, name: IncomingSocketThread/Receiver)
09-08 14:32:09.138  6647  7622 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1406, thread name: IncomingSocketThread/Receiver)
09-08 14:32:09.138  6647  7622 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 14:32:09.138  6647  7622 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1406, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-08 14:32:09.148  6647  7621 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1405, name: IncomingSocketThread/Sender)
,09-08 14:32:09.748   292   292 E SMD     : DCD OFF
,09-08 14:32:09.938  1015  1148 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,09-08 14:32:10.538   259  1096 I SurfaceFlinger: id=15 Removed Uoast (8/9)
,09-08 14:32:10.548   259   451 I SurfaceFlinger: id=15 Removed Uoast (-2/9)
,09-08 14:32:10.548  1015  1027 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1015) eventTime = 155623
,09-08 14:32:10.548  1015  1027 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015 (0x0)
,09-08 14:32:10.548  1015  1027 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1015, ws=WorkSource{10049}) (elapsedTime=3485)
,09-08 14:32:10.608  1015  1135 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-08 14:32:10.608  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-08 14:32:10.608  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:10.608  1015  1135 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-08 14:32:10.608  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-08 14:32:10.678  7567  7567 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-08 14:32:11.378  1015  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-08 14:32:11.378  1015  1490 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
09-08 14:32:11.378  1015  1490 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-08 14:32:11.378  1015  1490 D BatteryService: stay LED for fully charged
09-08 14:32:11.378  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-08 14:32:11.378  1015  1015 I MotionRecognitionService: Plugged,
,09-08 14:32:11.378  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-08 14:32:11.378  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
09-08 14:32:11.378  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-08 14:32:11.388  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-08 14:32:11.388  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,09-08 14:32:11.388  1173  1173 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-08 14:32:11.388  1173  1173 D SViewCoverView: level :100 plugged : 2
,09-08 14:32:11.398  7325  7325 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-08 14:32:11.398  7325  7376 D HeadsetStateMachine: Disconnected process message: 10
,09-08 14:32:11.408  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-08 14:32:11.408  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-08 14:32:11.408  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-08 14:32:12.138  6647  6702 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1415),
,09-08 14:32:12.138  6647  6702 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...,
09-08 14:32:12.138  6647  6702 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1416)
,09-08 14:32:12.138  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 14:32:12.138  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ce22df6 added. We now have 2 listener(s)
,09-08 14:32:12.148  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-08 14:32:12.148  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 14:32:12.148  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 14:32:12.148  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 14:32:12.148  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1892b5f7 added. We now have 2 listener(s)
09-08 14:32:12.148  6647  6702 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:32:12.148  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:32:12.158  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:32:12.158  6647  6702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:32:12.158  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:32:12.158  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:32:12.158  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:32:12.158  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:32:12.158  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:32:12.158  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:32:12.158  6647  6702 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:32:12.178  6647  6702 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:32:12.178  6647  6702 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:32:12.178  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:32:12.188  6647  6647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-08 14:32:12.188  6647  6661 I art     : Background sticky concurrent mark sweep GC freed 42830(2MB) AllocSpace objects, 12(192KB) LOS objects, 17% free, 10MB/12MB, paused 8.764ms total 59.254ms
,09-08 14:32:12.188  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:12.188  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:12.188  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:32:12.188  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:32:12.188  6647  6702 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ce22df6 removed from the list
09-08 14:32:12.188  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:12.188  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1892b5f7 removed from the list
09-08 14:32:12.188  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:12.188  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:32:12.198  6647  6702 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,09-08 14:32:12.198  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,09-08 14:32:12.198  6647  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 14:32:12.198  6647  6702 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-08 14:32:12.198  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-08 14:32:12.198  6647  6657 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3b4c1b3c, channel: 6, state: CLOSED
,09-08 14:32:12.198  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-08 14:32:12.208  6647  6657 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@47295d4, channel: 6, state: CLOSED
,09-08 14:32:12.208  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
09-08 14:32:12.208  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 14:32:12.208  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 14:32:12.208  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-08 14:32:12.208  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 14:32:12.208  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:32:12.208  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:32:12.208  6647  6647 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 14:32:12.208  6647  6657 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3882fc22, channel: 6, state: CLOSED
09-08 14:32:12.208  6647  6657 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1db58e34, channel: -1, state: CLOSED
09-08 14:32:12.208  6647  6657 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1cfbb535, channel: 6, state: CLOSED
,09-08 14:32:12.208  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 14:32:12.218  6647  7626 D BluetoothSocket: bindListen(): myUserId = 0
09-08 14:32:12.218  6647  7626 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:32:12.218  6647  7626 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]},
09-08 14:32:12.218  6647  7626 D BluetoothSocket: bindListen(), new LocalSocket 
,09-08 14:32:12.218  6647  7626 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 14:32:12.218  6647  7626 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1dfb3382
09-08 14:32:12.218  6647  7626 D BluetoothSocket: channel: 6
09-08 14:32:12.218  6647  7626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-08 14:32:12.218  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 14:32:12.218  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:32:12.218  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-08 14:32:12.228  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27",
09-08 14:32:12.228  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 08 EC A9 50 76 27
09-08 14:32:12.228  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 14:32:12.228  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 14:32:12.228  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-08 14:32:12.228  7325  7371 D BtGatt.GattService: registerClient() - UUID=109e4d99-5c0e-4957-8efc-c264ba5672e4
,09-08 14:32:12.278  7325  7369 D BtGatt.GattService: onClientRegistered() - UUID=109e4d99-5c0e-4957-8efc-c264ba5672e4, clientIf=6
,09-08 14:32:12.278  6647  7099 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-08 14:32:12.278  7325  7374 D BtGatt.AdvertiseManager: message : 0
,09-08 14:32:12.278  7325  7374 D BtGatt.AdvertiseManager: number of adv instance running0,
09-08 14:32:12.278  7325  7374 D BtGatt.AdvertiseManager: size of list is =0
09-08 14:32:12.278  7325  7374 D BtGatt.AdvertiseManager: starting advertising,
09-08 14:32:12.278  7325  7374 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-08 14:32:12.288  7325  7369 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-08 14:32:12.298  7325  7374 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 14:32:12.298  7325  7369 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-08 14:32:12.298  7325  7374 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-08 14:32:12.298  7325  7374 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-08 14:32:12.298  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 14:32:12.298  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 14:32:12.308  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 14:32:12.308  6647  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 14:32:12.308  6647  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-08 14:32:12.308  6647  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-08 14:32:12.308  6647  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-08 14:32:12.308  6647  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-08 14:32:12.308  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 14:32:12.318  6647  6647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 14:32:12.318  6647  6647 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 14:32:12.518  7484  7484 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,09-08 14:32:12.528  7484  7629 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,09-08 14:32:12.558  7484  7629 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,09-08 14:32:12.558  7484  7629 I ReactiveServiceManager: Supported : 1
,09-08 14:32:12.558  1015  1495 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,09-08 14:32:12.558  1015  1495 D QSEECOMAPI: : App is not loaded in QSEE
,09-08 14:32:12.568  1015  1495 D QSEECOMAPI: : Loaded image: APP id = 12
,09-08 14:32:12.578  1015  1495 D QSEECOMAPI: : QSEECom_dealloc_memory 
,09-08 14:32:12.578  1015  1495 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 12
09-08 14:32:12.578  1015  1495 E terrier : handleString: Failed to handle string(-4)
,09-08 14:32:12.578  1015  1495 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,09-08 14:32:12.578  7484  7629 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
09-08 14:32:12.578  7484  7629 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,09-08 14:32:12.578  7484  7629 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-08 14:32:12.588  7484  7629 I PCWCLIENTTRACE_PushUtil: sales region : global
09-08 14:32:12.588  7484  7629 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-08 14:32:12.588  7484  7629 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,09-08 14:32:12.748   292   292 E SMD     : DCD OFF,
,09-08 14:32:12.818  6647  6647 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true,
09-08 14:32:12.818  6647  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-08 14:32:12.818  6647  6647 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:32:13.778   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 14:32:14.688  7567  7567 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-08 14:32:14.778   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,09-08 14:32:15.318  6647  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything,
09-08 14:32:15.318  6647  6702 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 14:32:15.318  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 14:32:15.318  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 14:32:15.318  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 14:32:15.318  6647  6702 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@19246ad0, channel: 6, state: LISTENING
09-08 14:32:15.318  6647  6702 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@19246ad0, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1dfb3382, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@39ed0ac9mSocket: android.net.LocalSocket@3ad05ce impl:android.net.LocalSocketImpl@13c46cef fd:FileDescriptor[109]
,09-08 14:32:15.318  6647  6702 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3ad05ce impl:android.net.LocalSocketImpl@13c46cef fd:FileDescriptor[109]
09-08 14:32:15.318  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:32:15.318  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 14:32:15.318  6647  7626 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@19246ad0, channel: 6, state: CLOSED
09-08 14:32:15.318  6647  7626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 14:32:15.318  6647  7626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 14:32:15.318  6647  7626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 14:32:15.318  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 14:32:15.318  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:32:15.318  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:32:15.318  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:32:15.318  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 14:32:15.318  6647  6647 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 14:32:15.318  6647  6702 D BluetoothLeScanner: could not find callback wrapper
09-08 14:32:15.318  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 14:32:15.318  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-08 14:32:15.328  7325  7374 D BtGatt.AdvertiseManager: message : 1
,09-08 14:32:15.328  7325  7374 D BtGatt.AdvertiseManager: stop advertise for client 6
09-08 14:32:15.328  7325  7374 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-08 14:32:15.328  7325  7374 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-08 14:32:15.328  7325  7369 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-08 14:32:15.328  7325  7369 D BtGatt.GattService: Client app is not null!
09-08 14:32:15.338  7325  7371 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-08 14:32:15.338  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 14:32:15.338  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-08 14:32:15.338  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-08 14:32:15.338  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-08 14:32:15.338  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-08 14:32:15.338  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:32:15.338  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 14:32:15.338  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:32:15.338  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-08 14:32:15.338  6647  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:32:15.338  6647  6647 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:32:15.338  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:32:15.338  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:32:15.338  6647  6647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 14:32:15.338  6647  6647 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:32:15.348  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:32:15.348  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:15.348  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:32:15.348  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ce22df6 not in the list
09-08 14:32:15.348  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:15.348  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1892b5f7 not in the list
,09-08 14:32:15.348  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:15.348  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:15.348  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:32:15.348  6647  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 14:32:15.348  6647  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:32:15.348  6647  6702 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:32:15.348  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:32:15.348  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:32:15.348  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 14:32:15.348  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 14:32:15.358  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 14:32:15.358  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:32:15.368  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 14:32:15.368  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 14:32:15.368  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 14:32:15.368  7325  7417 D BtGatt.GattService: registerClient() - UUID=791caf6b-07a5-40cb-b3ef-6acce479222a
,09-08 14:32:15.418  7325  7369 D BtGatt.GattService: onClientRegistered() - UUID=791caf6b-07a5-40cb-b3ef-6acce479222a, clientIf=6
,09-08 14:32:15.418  6647  6655 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-08 14:32:15.418  7325  7334 D BtGatt.GattService: start scan with filters
,09-08 14:32:15.418  7325  7375 D BtGatt.ScanManager: handling starting scan
,09-08 14:32:15.418  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 14:32:15.418  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 14:32:15.418  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-08 14:32:15.418  7325  7375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@420834f
,09-08 14:32:15.418  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 14:32:15.428  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 14:32:15.428  6647  6647 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 14:32:15.428  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 14:32:15.428  7325  7369 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-08 14:32:15.428  7325  7369 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 14:32:15.428  7325  7375 D BtGatt.ScanManager: allow scan with filters
09-08 14:32:15.428  7325  7375 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-08 14:32:15.428  7325  7375 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-08 14:32:15.438  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 14:32:15.438  7325  7369 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-08 14:32:15.438  7325  7369 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 14:32:15.438  7325  7375 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 14:32:15.438  7325  7375 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-08 14:32:15.448  7325  7369 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-08 14:32:15.448  7325  7369 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 14:32:15.458  7325  7369 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-08 14:32:15.458  7325  7369 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 14:32:15.748   292   292 E SMD     : DCD OFF,
,09-08 14:32:15.788   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 14:32:15.928  6647  6647 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 14:32:15.928  6647  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:32:15.928  6647  6647 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:32:15.958  1015  1094 V AlarmManager: waitForAlarm result :4
,09-08 14:32:15.958  7325  7325 D BtGatt.ScanManager: awakened up at time 161038
,09-08 14:32:15.968  7325  7375 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-08 14:32:15.978  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-08 14:32:15.978  1173  1173 D KeyguardUpdateMonitor: handleTimeUpdate
,09-08 14:32:15.978  7325  7369 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=5
,09-08 14:32:15.978  7325  7369 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 14:32:15.978  7325  7369 D BtGatt.GattService: current time is 161056354208
09-08 14:32:15.978  7325  7369 D BtGatt.GattService: Batch record : [18, 7, 126, -79, 34, 107, 1, -128, -91, -47, 1, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -8, -49, -59, -39, -27, 97, 0, 37, -47, 14, -113, 116, -46, 1, -128, -72, 37, 1, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -78, 66, 1, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -80, 117, 1, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -70, -83, 1, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-08 14:32:15.998  7325  7369 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -8, -49, -59, -39, -27, 97]
,09-08 14:32:15.998  7325  7369 D ScanRecord: parseFromBytes
09-08 14:32:15.998  1173  1173 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-08 14:32:15.998  1173  1173 D SecKeyguardClockView: HomeTimezone(): 1
,09-08 14:32:15.998  7325  7369 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 14:32:15.998  7325  7369 D ScanRecord: parseFromBytes
,09-08 14:32:15.998  7325  7369 D ScanRecord: first manudata for manu ID
,09-08 14:32:15.998  7325  7369 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 14:32:15.998  7325  7369 D ScanRecord: parseFromBytes
,09-08 14:32:15.998  7325  7369 D ScanRecord: first manudata for manu ID
,09-08 14:32:16.008  7325  7369 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 14:32:16.008  7325  7369 D ScanRecord: parseFromBytes
09-08 14:32:16.008  7325  7369 D ScanRecord: first manudata for manu ID
09-08 14:32:16.008  7325  7369 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 14:32:16.008  7325  7369 D ScanRecord: parseFromBytes
09-08 14:32:16.008  7325  7369 D ScanRecord: first manudata for manu ID
,09-08 14:32:16.008  7325  7369 D BtGatt.GattService: result: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-70, mTimestampNanos=139606903271}
,09-08 14:32:16.008  7325  7369 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
09-08 14:32:16.008  7325  7369 D BtGatt.GattService: result: ScanResult{mDevice=6B:22:B1:7E:07:12, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -8, -49, -59, -39, -27, 97]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-91, mTimestampNanos=137806903271}
,09-08 14:32:16.008  7325  7369 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
09-08 14:32:16.008  1173  1173 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-08 14:32:16.008  7325  7369 D BtGatt.GattService: result: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-72, mTimestampNanos=146406903271}
09-08 14:32:16.008  1173  1173 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
09-08 14:32:16.008  1173  1173 I KeyguardEffectViewController: *** don't update sliding image ***
09-08 14:32:16.008  7325  7369 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 14:32:16.008  7325  7369 D BtGatt.GattService: result: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=142406903271}
09-08 14:32:16.008  7325  7369 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
09-08 14:32:16.008  7325  7369 D BtGatt.GattService: result: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-78, mTimestampNanos=144956903271}
09-08 14:32:16.008  7325  7369 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 14:32:16.008  1173  1173 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,09-08 14:32:16.008  6647  7099 D ScanRecord: parseFromBytes
09-08 14:32:16.008  6647  7099 D ScanRecord: first manudata for manu ID
09-08 14:32:16.008  6647  7099 D ScanRecord: parseFromBytes
,09-08 14:32:16.018  6647  7099 D ScanRecord: parseFromBytes
09-08 14:32:16.018  6647  7099 D ScanRecord: first manudata for manu ID
,09-08 14:32:16.018  6647  7099 D ScanRecord: parseFromBytes
09-08 14:32:16.018  6647  7099 D ScanRecord: first manudata for manu ID
09-08 14:32:16.018  6647  7099 D ScanRecord: parseFromBytes
09-08 14:32:16.018  6647  7099 D ScanRecord: first manudata for manu ID
,09-08 14:32:16.018  6647  6647 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> F8:CF:C5:D9:E5:61 6], added - the peer count is 1
,09-08 14:32:16.018  6647  6647 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> F8:CF:C5:D9:E5:61 6], Bluetooth address: F8:CF:C5:D9:E5:61, device name: '', device address: ''
,09-08 14:32:16.048  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-08 14:32:16.058  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-08 14:32:16.058  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-08 14:32:16.068  1173  1173 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-08 14:32:16.358  1015  3349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-08 14:32:16.488  1015  1094 V AlarmManager: waitForAlarm result :4
,09-08 14:32:16.488  7325  7325 D BtGatt.ScanManager: awakened up at time 161564
,09-08 14:32:16.488  7325  7375 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-08 14:32:16.498  7325  7369 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-08 14:32:16.498  7325  7369 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 14:32:16.778   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 14:32:16.998  1015  1094 V AlarmManager: waitForAlarm result :4
,09-08 14:32:16.998  7325  7325 D BtGatt.ScanManager: awakened up at time 162078
,09-08 14:32:17.008  7325  7375 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-08 14:32:17.008  7325  7369 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-08 14:32:17.008  7325  7369 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 14:32:17.508  1015  1094 V AlarmManager: waitForAlarm result :4
,09-08 14:32:17.508  7325  7325 D BtGatt.ScanManager: awakened up at time 162587
,09-08 14:32:17.508  7325  7375 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-08 14:32:17.518  7325  7369 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-08 14:32:17.518  7325  7369 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 14:32:17.608  1015  1027 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
09-08 14:32:17.608  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,09-08 14:32:17.608  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:17.608  1015  1027 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-08 14:32:17.608  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-08 14:32:17.608  7077  7077 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
09-08 14:32:17.608  7077  7077 D PreloadUpdateManagerStateMachine: exit::IDLE
09-08 14:32:17.608  7077  7077 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,09-08 14:32:17.608  7077  7077 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,09-08 14:32:17.608  7077  7077 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,09-08 14:32:17.618  7077  7077 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
09-08 14:32:17.618  7077  7077 D PreloadUpdateManagerStateMachine: entry::IDLE
,09-08 14:32:17.788   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,09-08 14:32:18.018  1015  1094 V AlarmManager: waitForAlarm result :4
,09-08 14:32:18.028  7325  7325 D BtGatt.ScanManager: awakened up at time 163101
,09-08 14:32:18.028  7325  7375 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-08 14:32:18.028  7325  7369 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
09-08 14:32:18.028  7325  7369 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 14:32:18.048  1015  3328 D SSRM:n  : SIOP:: AP = 320
,09-08 14:32:18.448  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:32:18.448  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:18.448  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:32:18.448  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ce22df6 not in the list
09-08 14:32:18.448  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:32:18.448  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:32:18.448  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:32:18.448  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 14:32:18.448  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 14:32:18.448  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 14:32:18.448  7325  7370 D BtGatt.GattService: stopScan() - queue size =1
,09-08 14:32:18.448  7325  7333 D BtGatt.GattService: unregisterClient() - clientIf=6,
,09-08 14:32:18.448  7325  7375 D BtGatt.ScanManager: filter size is 1,
09-08 14:32:18.458  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 14:32:18.458  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 14:32:18.458  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 14:32:18.458  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 14:32:18.458  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 14:32:18.458  7325  7375 D BtGatt.ScanManager: delete FilterIndex - 3
,09-08 14:32:18.458  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:32:18.458  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
09-08 14:32:18.458  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 14:32:18.458  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:32:18.458  7325  7369 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-08 14:32:18.458  7325  7369 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 14:32:18.458  7325  7375 D BtGatt.ScanManager: stopping BLe Batch
09-08 14:32:18.458  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:18.458  6647  6702 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,09-08 14:32:18.458  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 14:32:18.458  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 14:32:18.458  6647  6647 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:32:18.468  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1892b5f7 not in the list,
09-08 14:32:18.468  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:18.468  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:18.468  7325  7369 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-08 14:32:18.468  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 14:32:18.468  7325  7369 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-08 14:32:18.468  6647  6702 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-08 14:32:18.468  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-08 14:32:18.468  6647  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 14:32:18.468  6647  6702 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-08 14:32:18.468  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 14:32:18.468  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:32:18.468  7325  7375 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-08 14:32:18.468  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-08 14:32:18.468  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 14:32:18.468  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 14:32:18.468  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 14:32:18.468  6647  6647 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-08 14:32:18.468  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 14:32:18.468  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:32:18.468  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 14:32:18.478  7325  7369 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-08 14:32:18.478  7325  7369 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-08 14:32:18.478  6647  6702 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 14:32:18.478  6647  7635 D BluetoothSocket: bindListen(): myUserId = 0
,09-08 14:32:18.478  6647  7635 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:32:18.488  6647  7635 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
,09-08 14:32:18.488  6647  7635 D BluetoothSocket: bindListen(), new LocalSocket 
,09-08 14:32:18.488  6647  7635 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-08 14:32:18.488  6647  7635 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@135000a6
,09-08 14:32:18.488  6647  7635 D BluetoothSocket: channel: 6
09-08 14:32:18.488  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 14:32:18.488  6647  7635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-08 14:32:18.488  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:32:18.488  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-08 14:32:18.488  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-08 14:32:18.488  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 08 EC A9 50 76 27
,09-08 14:32:18.498  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 14:32:18.498  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 14:32:18.498  6647  6702 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-08 14:32:18.498  7325  7333 D BtGatt.GattService: registerClient() - UUID=ac59bd86-4d0a-4a33-ab8a-33b528f1319c
,09-08 14:32:18.538  7325  7369 D BtGatt.GattService: onClientRegistered() - UUID=ac59bd86-4d0a-4a33-ab8a-33b528f1319c, clientIf=6
,09-08 14:32:18.538  6647  6658 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-08 14:32:18.538  7325  7374 D BtGatt.AdvertiseManager: message : 0
,09-08 14:32:18.538  7325  7374 D BtGatt.AdvertiseManager: number of adv instance running0
,09-08 14:32:18.538  7325  7374 D BtGatt.AdvertiseManager: size of list is =0
,09-08 14:32:18.548  7325  7374 D BtGatt.AdvertiseManager: starting advertising
,09-08 14:32:18.548  7325  7374 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-08 14:32:18.558  7325  7369 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-08 14:32:18.558  7325  7374 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 14:32:18.558  7325  7369 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-08 14:32:18.558  7325  7374 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-08 14:32:18.558  7325  7374 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-08 14:32:18.568  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 14:32:18.568  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 14:32:18.568  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 14:32:18.568  6647  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 14:32:18.568  6647  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-08 14:32:18.568  6647  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-08 14:32:18.568  6647  6647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-08 14:32:18.568  6647  6647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-08 14:32:18.568  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 14:32:18.578  6647  6647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 14:32:18.578  6647  6647 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 14:32:18.688  7567  7567 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-08 14:32:18.688  7567  7567 I dhcpcd  : wlan0: no IPv6 Routers available
,09-08 14:32:18.748   292   292 E SMD     : DCD OFF,
,09-08 14:32:18.778   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-08 14:32:19.088  6647  6647 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-08 14:32:19.088  6647  6647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 14:32:19.088  6647  6647 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:32:21.438  1015  1762 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-08 14:32:21.448  1015  1762 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-08 14:32:21.448  1015  1762 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-08 14:32:21.448  1015  1762 D BatteryService: stay LED for fully charged
,09-08 14:32:21.448  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-08 14:32:21.448  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-08 14:32:21.448  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-08 14:32:21.458  1015  1015 I MotionRecognitionService: Plugged
,09-08 14:32:21.458  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-08 14:32:21.458  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-08 14:32:21.458  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-08 14:32:21.468  7325  7325 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-08 14:32:21.468  7325  7376 D HeadsetStateMachine: Disconnected process message: 10
,09-08 14:32:21.478  1173  1173 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-08 14:32:21.478  1173  1173 D SViewCoverView: level :100 plugged : 2
,09-08 14:32:21.478  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-08 14:32:21.478  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-08 14:32:21.478  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-08 14:32:21.578  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:32:21.578  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 14:32:21.578  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-08 14:32:21.578  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 14:32:21.578  6647  6702 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@151c3694, channel: 6, state: LISTENING
,09-08 14:32:21.588  6647  6702 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@151c3694, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@135000a6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@201c853dmSocket: android.net.LocalSocket@26eb8132 impl:android.net.LocalSocketImpl@324f6e83 fd:FileDescriptor[109]
09-08 14:32:21.588  6647  6702 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@26eb8132 impl:android.net.LocalSocketImpl@324f6e83 fd:FileDescriptor[109]
09-08 14:32:21.588  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:32:21.588  6647  6702 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-08 14:32:21.588  6647  7635 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@151c3694, channel: 6, state: CLOSED
09-08 14:32:21.588  6647  7635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 14:32:21.588  6647  6647 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 14:32:21.588  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ce22df6 not in the list
09-08 14:32:21.588  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:32:21.588  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:32:21.588  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:32:21.588  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:32:21.588  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 14:32:21.588  6647  7635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 14:32:21.588  6647  7635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-08 14:32:21.588  6647  6702 D BluetoothLeScanner: could not find callback wrapper
,09-08 14:32:21.588  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 14:32:21.588  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-08 14:32:21.588  7325  7374 D BtGatt.AdvertiseManager: message : 1
,09-08 14:32:21.588  7325  7374 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-08 14:32:21.588  7325  7374 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-08 14:32:21.598  7325  7374 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-08 14:32:21.598  7325  7369 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-08 14:32:21.598  7325  7369 D BtGatt.GattService: Client app is not null!
,09-08 14:32:21.608  7325  7333 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-08 14:32:21.608  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 14:32:21.608  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-08 14:32:21.608  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-08 14:32:21.608  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-08 14:32:21.608  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 14:32:21.608  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:32:21.608  6647  6702 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 14:32:21.608  6647  6702 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 14:32:21.618  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:32:21.618  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 14:32:21.618  6647  6647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 14:32:21.618  6647  6647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-08 14:32:21.618  6647  6647 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:32:21.618  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1892b5f7 not in the list
,09-08 14:32:21.618  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:32:21.618  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:32:21.618  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:32:21.618  6647  6702 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:32:21.618  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:21.618  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:32:21.618  6647  6702 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ce22df6 not in the list
09-08 14:32:21.618  6647  6702 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:32:21.618  6647  6702 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1892b5f7 not in the list
09-08 14:32:21.618  6647  6702 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:32:21.618  6647  6702 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:32:21.618  6647  6702 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 14:32:21.628  6647  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-08 14:32:21.628  6647  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-08 14:32:21.628  6647  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-08 14:32:21.628  6647  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:32:21.628  6647  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-08 14:32:21.628  6647  6702 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 14:32:21.638  6647  7638 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1436, name: My test thread name)
,09-08 14:32:21.748   292   292 E SMD     : DCD OFF
,09-08 14:32:22.118  6647  6647 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,09-08 14:32:22.138  4659  4989 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient,
,09-08 14:32:22.768  1015  1048 I PowerManagerService: [PWL] Off : 105s ago,
,09-08 14:32:22.998  1015  1330 E Watchdog: !@Sync 5,
,09-08 14:32:23.148  1997  3075 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient,
,09-08 14:32:23.638  6647  6702 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 1436
,09-08 14:32:23.638  6647  6702 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 1436, name: My test thread name)
,09-08 14:32:23.638  6647  7642 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1437, name: My test thread name)
,09-08 14:32:23.638  6647  7642 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1437, thread name: My test thread name)
09-08 14:32:23.638  6647  7642 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1437, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-08 14:32:23.638  6647  6702 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 14:32:23.648  6647  7643 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1441, name: My test thread name)
,09-08 14:32:23.648  6647  7643 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 1441, thread name: My test thread name): Test exception.
,09-08 14:32:23.648  6647  7643 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1441, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-08 14:32:23.648  6647  6702 I jxcore-log: Total number of executed tests:  82
09-08 14:32:23.648  6647  6702 I jxcore-log: 
,09-08 14:32:23.648  6647  6702 I jxcore-log: Number of passed tests:  82
09-08 14:32:23.648  6647  6702 I jxcore-log: 
,09-08 14:32:23.648  6647  6702 I jxcore-log: Number of failed tests:  0
09-08 14:32:23.648  6647  6702 I jxcore-log: 
,09-08 14:32:23.648  6647  6702 I jxcore-log: Number of ignored tests:  0
09-08 14:32:23.648  6647  6702 I jxcore-log: 
,09-08 14:32:23.648  6647  6702 I jxcore-log: Total duration:  41711
09-08 14:32:23.648  6647  6702 I jxcore-log: 
,09-08 14:32:23.658  6647  6702 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-08 14:32:23.658  6647  6702 I jxcore-log: 
,09-08 14:32:23.658  6647  6702 I jxcore-log: My device name is: samsung-SM-A300FU
09-08 14:32:23.658  6647  6702 I jxcore-log: 
09-08 14:32:23.668  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:23.668  6647  6702 I jxcore-log: 
09-08 14:32:23.668  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:23.668  6647  6702 I jxcore-log: 
09-08 14:32:23.668  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 14:32:23.668  6647  6702 I jxcore-log: 
09-08 14:32:23.678  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 14:32:23.678  6647  6702 I jxcore-log: 
09-08 14:32:23.678  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:23.678  6647  6702 I jxcore-log: 
09-08 14:32:23.678  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 14:32:23.678  6647  6702 I jxcore-log: 
,09-08 14:32:23.688  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:23.688  6647  6702 I jxcore-log: 
,09-08 14:32:23.688  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 14:32:23.688  6647  6702 I jxcore-log: 
09-08 14:32:23.688  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:23.688  6647  6702 I jxcore-log: 
,09-08 14:32:23.688  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:23.688  6647  6702 I jxcore-log: 
,09-08 14:32:23.688  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:23.688  6647  6702 I jxcore-log: 
,09-08 14:32:23.688  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 14:32:23.688  6647  6702 I jxcore-log: 
,09-08 14:32:23.698  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:32:23.698  6647  6702 I jxcore-log: 
,09-08 14:32:23.698  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:32:23.698  6647  6702 I jxcore-log: 
,09-08 14:32:23.698  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-08 14:32:23.698  6647  6702 I jxcore-log: 
,09-08 14:32:23.698  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 14:32:23.698  6647  6702 I jxcore-log: 
,09-08 14:32:23.698  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:23.698  6647  6702 I jxcore-log: 
,09-08 14:32:23.708  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:23.708  6647  6702 I jxcore-log: 
,09-08 14:32:23.708  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:23.708  6647  6702 I jxcore-log: 
,09-08 14:32:23.708  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:23.708  6647  6702 I jxcore-log: 
,09-08 14:32:23.708  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:23.708  6647  6702 I jxcore-log: 
,09-08 14:32:23.708  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:23.708  6647  6702 I jxcore-log: 
,09-08 14:32:23.708  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:23.708  6647  6702 I jxcore-log: 
,09-08 14:32:23.708  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-08 14:32:23.708  6647  6702 I jxcore-log: 
,09-08 14:32:23.718  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:23.718  6647  6702 I jxcore-log: 
,09-08 14:32:23.718  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
09-08 14:32:23.718  6647  6702 I jxcore-log: 
,09-08 14:32:23.718  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:32:23.718  6647  6702 I jxcore-log: 
,09-08 14:32:23.718  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 14:32:23.718  6647  6702 I jxcore-log: 
,09-08 14:32:23.718  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 14:32:23.718  6647  6702 I jxcore-log: 
,09-08 14:32:23.718  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:23.718  6647  6702 I jxcore-log: 
,09-08 14:32:23.718  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:32:23.718  6647  6702 I jxcore-log: 
,09-08 14:32:23.728  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 14:32:23.728  6647  6702 I jxcore-log: 
,09-08 14:32:23.728  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 14:32:23.728  6647  6702 I jxcore-log: 
,09-08 14:32:23.728  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-08 14:32:23.728  6647  6702 I jxcore-log: 
,09-08 14:32:23.728  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 14:32:23.728  6647  6702 I jxcore-log: 
,09-08 14:32:23.728  6647  6702 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 14:32:23.728  6647  6702 I jxcore-log: 
,09-08 14:32:23.748  6647  7638 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1436, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-08 14:32:23.938  7644  7644 D AndroidRuntime: ,
09-08 14:32:23.938  7644  7644 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-08 14:32:23.938  7644  7644 D AndroidRuntime: CheckJNI is OFF,
09-08 14:32:23.938  7644  7644 D AndroidRuntime: readGMSProperty: start
09-08 14:32:23.938  7644  7644 D AndroidRuntime: readGMSProperty: already setted!!,
09-08 14:32:23.938  7644  7644 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-08 14:32:23.938  7644  7644 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-08 14:32:23.938  7644  7644 D AndroidRuntime: readGMSProperty: end,
09-08 14:32:23.938  7644  7644 D AndroidRuntime: addProductProperty: start
,09-08 14:32:24.068  7644  7644 E AffinityControl: AffinityControl: registerfunction enter,
,09-08 14:32:24.088  7644  7644 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,09-08 14:32:24.108  1015  1327 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-08 14:32:24.108  1015  1327 D PackageManager: START PACKAGE DELETE: observer{608843672}
09-08 14:32:24.108  1015  1327 D PackageManager: pkg{<packageName>}
09-08 14:32:24.108  1015  1327 D PackageManager: user{0}
09-08 14:32:24.108  1015  1327 D PackageManager: caller{2000}
09-08 14:32:24.108  1015  1327 D PackageManager: flags{2}
09-08 14:32:24.108  1015  1327 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-08 14:32:24.108  1015  1327 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
09-08 14:32:24.108  1015  1327 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-08 14:32:24.108  1015  1327 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-08 14:32:24.108  1015  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
09-08 14:32:24.108  1015  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-08 14:32:24.108  1015  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-08 14:32:24.108  1015  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
09-08 14:32:24.108  1015  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-08 14:32:24.118  1015  1056 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,09-08 14:32:24.118  1015  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg,
,09-08 14:32:24.118  1015  1041 I ActivityManager: Killing 6647:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg,
,09-08 14:32:24.118  1015  1041 I ActivityManager:   Force finishing activity ActivityRecord{1f1dae37 u0 com.test.thalitest/.MainActivity t2}
,09-08 14:32:24.138  1015  1041 D InputDispatcher: Focus left window: 6647
,09-08 14:32:24.138   259   447 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,09-08 14:32:24.138   259  1096 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,09-08 14:32:24.158  1015  1041 D InputDispatcher: Focused application released
,09-08 14:32:24.168  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-08 14:32:24.168  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-08 14:32:24.168  1015  1041 D FocusedStackFrame: Set to : 0
,09-08 14:32:24.168  1015  1041 W ActivityManager: mDVFSHelper.acquire()
,09-08 14:32:24.228  1015  1056 W PackageSettings: Skipping PackageSetting{34d1a932 com.example.hello/10168} due to missing metadata
,09-08 14:32:24.278  1015  1041 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,09-08 14:32:24.288  1015  1056 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-08 14:32:24.308  1481  1481 D Launcher: onRestart, Launcher: 170751973
09-08 14:32:24.308  1015  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-08 14:32:24.338  2629  2629 I art     : Explicit concurrent mark sweep GC freed 19797(1144KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 930us total 42.585ms
,09-08 14:32:24.378  1015  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-08 14:32:24.378  4659  4659 I art     : Explicit concurrent mark sweep GC freed 4355(167KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 12MB/16MB, paused 1.561ms total 87.315ms
,09-08 14:32:24.378  1873  1873 E SamsungIME: mOCRHelper is null
,09-08 14:32:24.388  1997  2156 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-08 14:32:24.388  1455  1455 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-08 14:32:24.408  1481  1481 D Launcher: onStart, Launcher: 170751973
09-08 14:32:24.408  1481  1481 D Launcher.HomeView: onStart
,09-08 14:32:24.408  1481  1481 D Launcher: onResume, Launcher: 170751973
,09-08 14:32:24.408  1015  1319 D SettingsProvider: name = kids_home_mode
09-08 14:32:24.408  1015  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-08 14:32:24.408  1015  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-08 14:32:24.408  1015  1319 D SettingsProvider: selectionArgs: false
09-08 14:32:24.408  1015  1319 D SettingsProvider: selectionArgs: 10006
09-08 14:32:24.408  1015  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-08 14:32:24.408  1015  1319 D SettingsProvider: ret = -1
,09-08 14:32:24.408  2843  2843 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Sep 08 14:32:24 GMT+02:00 2016
,09-08 14:32:24.408  1481  1481 D Launcher.HomeView: onResume
,09-08 14:32:24.418  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,09-08 14:32:24.418  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-08 14:32:24.418  1015  1122 V NetworkStats: removeUidsLocked() for UIDs [10171]
09-08 14:32:24.418  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 14:32:24.418  1015  1122 V NetworkStats: performPollLocked(flags=0x3)
,09-08 14:32:24.428  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-08 14:32:24.428  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 14:32:24.428  1015  1463 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-08 14:32:24.428  1015  1463 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
09-08 14:32:24.438  1015  1122 V NetworkStats: performPollLocked() took 11ms
,09-08 14:32:24.438  1015  1463 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:24.438  1015  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:24.438  1015  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-08 14:32:24.438  1441  1441 D RegisteredServicesCache: empty dynamic service
09-08 14:32:24.438  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:24.438  1481  1481 D MenuAppsGridFragment: onResume
,09-08 14:32:24.438  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-08 14:32:24.448  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-08 14:32:24.448  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:24.448  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 14:32:24.458  2843  2843 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-08 14:32:24.458  1015  1480 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
09-08 14:32:24.458  1015  1480 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-08 14:32:24.458  1015  1480 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-08 14:32:24.458  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.458  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.458  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.458  1015  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:24.478  7657  7657 E Zygote  : MountEmulatedStorage(),
09-08 14:32:24.478  7657  7657 E Zygote  : v2
09-08 14:32:24.478  7657  7657 I libpersona: KNOX_SDCARD checking this for 10090
09-08 14:32:24.478  7657  7657 I libpersona: KNOX_SDCARD not a persona
,09-08 14:32:24.488  7657  7657 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-08 14:32:24.488  1015  1762 D ActivityManager: handle home activity for 0
09-08 14:32:24.488  1015  1480 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7657 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
09-08 14:32:24.488  1015  1762 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
09-08 14:32:24.488  1015  1762 D KnoxTimeoutHandler: post home show event for user 0
09-08 14:32:24.488  1015  1762 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-08 14:32:24.488  1015  1762 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-08 14:32:24.488  1015  1762 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-08 14:32:24.488  1481  1481 D Launcher.HomeView: onPause
09-08 14:32:24.488  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-08 14:32:24.498  7657  7657 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:32:24.498  7657  7657 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 14:32:24.498  1441  1441 D RegisteredComponentCache: Collect Tech packages for Knox
09-08 14:32:24.498  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-08 14:32:24.498  2843  2843 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
09-08 14:32:24.498  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.498  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.498  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.498  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:24.518  2843  2843 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-08 14:32:24.518  1015  1027 I TactileAssist: enable value -1
,09-08 14:32:24.518  1015  1027 I TactileAssist: internal enable value -1
09-08 14:32:24.518  1015  1027 I TactileAssist: intensity value -1
09-08 14:32:24.518  1015  1027 I TactileAssist: saveAppList value true
,09-08 14:32:24.518  1015  1027 I TactileAssist: List of disabled apps :
,09-08 14:32:24.518  1015  1015 I art     : Explicit concurrent mark sweep GC freed 109873(6MB) AllocSpace objects, 17(320KB) LOS objects, 33% free, 25MB/37MB, paused 2.861ms total 210.815ms
,09-08 14:32:24.518  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,09-08 14:32:24.518  7671  7671 E Zygote  : MountEmulatedStorage()
09-08 14:32:24.518  7671  7671 E Zygote  : v2
09-08 14:32:24.518  7671  7671 I libpersona: KNOX_SDCARD checking this for 1000
09-08 14:32:24.518  7671  7671 I libpersona: KNOX_SDCARD not a persona
,09-08 14:32:24.518  7671  7671 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-08 14:32:24.528  1015  1041 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7671 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-08 14:32:24.528  1015  1480 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-08 14:32:24.528  1015  1480 D SecContentProvider2: mCursor = null
,09-08 14:32:24.528  7671  7671 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 14:32:24.528  7671  7671 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 14:32:24.528  1015  1056 I art     : WaitForGcToComplete blocked for 118.127ms for cause Explicit
,09-08 14:32:24.528  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,09-08 14:32:24.528  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.528  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.528  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.528  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:24.538  7657  7657 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:32:24.538  7657  7657 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:24.548  7681  7681 E Zygote  : MountEmulatedStorage()
09-08 14:32:24.548  7681  7681 I libpersona: KNOX_SDCARD checking this for 1000
09-08 14:32:24.548  7681  7681 E Zygote  : v2
09-08 14:32:24.548  7681  7681 I libpersona: KNOX_SDCARD not a persona
09-08 14:32:24.558  1015  1041 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7681 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-08 14:32:24.558  7681  7681 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:32:24.558  2843  2843 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-08 14:32:24.558  7681  7681 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:32:24.558  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,09-08 14:32:24.558  7681  7681 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 14:32:24.558  7671  7671 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:32:24.558  7671  7671 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:24.568  2843  7656 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-08 14:32:24.568   259   259 I SurfaceFlinger: id=16 createSurf (540x960),1 flag=4, Mauncher
09-08 14:32:24.568  2843  7656 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,09-08 14:32:24.578  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-08 14:32:24.578  2843  7656 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,09-08 14:32:24.588  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-08 14:32:24.588  1015  1319 D InputDispatcher: Focus entered window: 1481
09-08 14:32:24.588  7681  7681 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 14:32:24.588  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-08 14:32:24.588  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
09-08 14:32:24.588  7681  7681 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:24.588  2843  7656 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
09-08 14:32:24.588  1481  1481 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-08 14:32:24.608  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,09-08 14:32:24.618  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-08 14:32:24.618  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-08 14:32:24.618  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-08 14:32:24.618  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,09-08 14:32:24.628  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,09-08 14:32:24.638  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-08 14:32:24.638  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{b0e82b1 token=android.os.BinderProxy@2dd31f20 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,09-08 14:32:24.638  1481  1481 D Launcher.HomeView: onStop
,09-08 14:32:24.638  1015  1135 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-08 14:32:24.648  1015  7703 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-08 14:32:24.648  1015  1135 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6647 uid 10171
,09-08 14:32:24.658  1015  1762 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,09-08 14:32:24.658  1873  1873 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
09-08 14:32:24.658  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.658  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.658  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.658  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:24.668  7705  7705 E Zygote  : MountEmulatedStorage()
,09-08 14:32:24.668  7705  7705 E Zygote  : v2
,09-08 14:32:24.668  7705  7705 I libpersona: KNOX_SDCARD checking this for 10048
09-08 14:32:24.668  1015  1041 W ActivityManager: mDVFSHelper.release(),
09-08 14:32:24.668  7705  7705 I libpersona: KNOX_SDCARD not a persona
,09-08 14:32:24.678  7705  7705 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-08 14:32:24.678  1015  1762 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7705 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,09-08 14:32:24.688  7705  7705 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:32:24.688  7705  7705 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,09-08 14:32:24.718  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-08 14:32:24.718  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-08 14:32:24.718  7705  7705 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 14:32:24.718  7705  7705 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:24.718  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-08 14:32:24.718  1015  1015 V EnterpriseBillingPolicy: uID is 10171,
09-08 14:32:24.718  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-08 14:32:24.718  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-08 14:32:24.718  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-08 14:32:24.718  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,09-08 14:32:24.718  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-08 14:32:24.718  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest,
09-08 14:32:24.718  7681  7681 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
09-08 14:32:24.728  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null,
,09-08 14:32:24.728  7671  7671 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-08 14:32:24.728  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-08 14:32:24.728  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-08 14:32:24.728  1015  1015 V EnterpriseBillingPolicy: uID is 10171
09-08 14:32:24.728  1015  3328 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-08 14:32:24.728  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-08 14:32:24.728  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-08 14:32:24.738  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-08 14:32:24.738  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-08 14:32:24.738  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-08 14:32:24.738  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-08 14:32:24.738  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{296657cb u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:169813
09-08 14:32:24.738  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-08 14:32:24.738  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
09-08 14:32:24.738  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
09-08 14:32:24.738  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
09-08 14:32:24.738  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-08 14:32:24.738  1015  1160 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,09-08 14:32:24.738  1015  1762 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,09-08 14:32:24.738  1015  1762 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-08 14:32:24.748   292   292 E SMD     : DCD OFF
09-08 14:32:24.748  7657  7657 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-08 14:32:24.748  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,09-08 14:32:24.748  7657  7657 D elm:15121: ELMEngine.ELMEngine( context ).
,09-08 14:32:24.758  1015  1762 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:24.758  1015  1762 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 14:32:24.758  1015  1028 D SecContentProvider2: uri = -1 selection = getSealedState
09-08 14:32:24.758  1015  1028 D SecContentProvider2: mCursor = null
09-08 14:32:24.758  7657  7657 D elm:15121: MDMBridge.setEnterpriseBridge()
09-08 14:32:24.758  7681  7681 I PopupuiReceiver_KNOX: getSealedState : true
,09-08 14:32:24.758  1015  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-08 14:32:24.758  1015  1464 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
,09-08 14:32:24.758  1015  1464 D SecContentProvider2: mCursor = null
,09-08 14:32:24.758  7681  7681 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
09-08 14:32:24.758  2843  7656 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-08 14:32:24.758  1015  1480 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,09-08 14:32:24.758  1015  1480 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-08 14:32:24.768  1015  1464 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
,09-08 14:32:24.768  1015  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:24.768  1015  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:24.768  1015  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-08 14:32:24.768  1015  1464 D SecContentProvider2: mCursor = null
,09-08 14:32:24.768  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-08 14:32:24.768  7681  7681 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
09-08 14:32:24.768  7681  7681 D PopupuiReceiver: Action package removed
09-08 14:32:24.768  7657  7657 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-08 14:32:24.768  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.768  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.768  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.768  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:24.778  2843  7656 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-08 14:32:24.778  2843  7656 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,09-08 14:32:24.788  7723  7723 E Zygote  : MountEmulatedStorage(),
09-08 14:32:24.788  7723  7723 E Zygote  : v2
09-08 14:32:24.788  7723  7723 I libpersona: KNOX_SDCARD checking this for 1000
09-08 14:32:24.788  7723  7723 I libpersona: KNOX_SDCARD not a persona
,09-08 14:32:24.788  7723  7723 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-08 14:32:24.788  7723  7723 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:32:24.788  7723  7723 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 14:32:24.788  1015  1028 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7723 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-08 14:32:24.798  2843  2843 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-08 14:32:24.798  1173  1173 I StatusBar: Icon Only
,09-08 14:32:24.798  1173  1173 D PanelView: There is/are notification(s) 
,09-08 14:32:24.798  7657  7657 D elm:15121: ElmAgentService : onCreate()
,09-08 14:32:24.798  7657  7722 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
09-08 14:32:24.798  7657  7722 D elm:15121: MainReceiver.listeningToPackageRemoved()
09-08 14:32:24.808  7657  7722 D elm:15121: MDMBridge.getInstance()
09-08 14:32:24.808  7657  7722 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
09-08 14:32:24.808  7705  7705 D Compatibility: onReceive() it will make start service
,09-08 14:32:24.808  1015  1319 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
09-08 14:32:24.808  7657  7722 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
09-08 14:32:24.808  1015  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.808  1015  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.808  1015  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.808  1015  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:24.818  7723  7723 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:32:24.818  7723  7723 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:24.828  1015  1056 I art     : Explicit concurrent mark sweep GC freed 16094(1162KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 24MB/36MB, paused 8.315ms total 296.814ms
,09-08 14:32:24.828  7738  7738 E Zygote  : MountEmulatedStorage()
,09-08 14:32:24.828  7738  7738 E Zygote  : v2
09-08 14:32:24.828  7738  7738 I libpersona: KNOX_SDCARD checking this for 10145
,09-08 14:32:24.828  7738  7738 I libpersona: KNOX_SDCARD not a persona
09-08 14:32:24.838  1015  1319 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7738 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-08 14:32:24.838  7738  7738 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:32:24.838  7738  7738 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:32:24.838  7738  7738 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-08 14:32:24.838  1015  1319 I ActivityManager: Killing 7268:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-08 14:32:24.838  1015  1762 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-08 14:32:24.838  1015  1762 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,09-08 14:32:24.838  1015  1762 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:24.838  1015  1762 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:24.838  1015  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-08 14:32:24.858  7738  7738 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:32:24.858  7738  7738 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:24.858  7484  7484 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-08 14:32:24.858  7484  7484 I PCWCLIENTTRACE_PushUtil: sales region : global
09-08 14:32:24.858  7484  7484 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-08 14:32:24.858  7484  7484 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-08 14:32:24.868  1015  1463 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-08 14:32:24.868  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.868  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.868  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.868  1015  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:24.868  7705  7748 D Compatibility: onHandleIntent()
,09-08 14:32:24.868  7705  7748 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,09-08 14:32:24.878  7705  7748 D Compatibility: found: 2
,09-08 14:32:24.878  7723  7723 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-08 14:32:24.878  7755  7755 E Zygote  : MountEmulatedStorage()
09-08 14:32:24.878  7755  7755 E Zygote  : v2
09-08 14:32:24.878  7755  7755 I libpersona: KNOX_SDCARD checking this for 10052
09-08 14:32:24.878  7755  7755 I libpersona: KNOX_SDCARD not a persona
,09-08 14:32:24.878  7755  7755 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:32:24.878  7705  7748 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-08 14:32:24.878  7755  7755 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:32:24.888  7705  7748 D Compatibility: skipping ResolveInfo{2d173744 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000},
09-08 14:32:24.888  7705  7748 D Compatibility: considering ResolveInfo{851702d com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-08 14:32:24.888  7705  7748 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
09-08 14:32:24.888  7705  7748 D Compatibility: enabling receiver ResolveInfo{aa8a962 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-08 14:32:24.888  7755  7755 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-08 14:32:24.888  1015  1463 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7755 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,09-08 14:32:24.898  7657  7657 D elm:15121: ElmAgentService : onDestroy().
,09-08 14:32:24.908  7705  7748 D Compatibility: enabling receiver ResolveInfo{11382af3 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-08 14:32:24.908  1015  1056 D PackageManager: delete codoeFile: 
,09-08 14:32:24.908  1015  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
,09-08 14:32:24.908  1015  1040 W TextServicesManagerService: no available spell checker services found
09-08 14:32:24.908  1015  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-08 14:32:24.918  1015  1495 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-08 14:32:24.918  7705  7748 D Compatibility: enabling receiver ResolveInfo{1cf283b0 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
09-08 14:32:24.918  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.918  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.918  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.918  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:24.918  7723  7723 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,09-08 14:32:24.918  1015  1056 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,09-08 14:32:24.918  7755  7755 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:32:24.928  7755  7755 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:24.928  1015  1056 I AASA_removePackage: UID=10171 Target=com.test.thalitest,
09-08 14:32:24.928  1015  1056 D PackageManager: result of delete: 1{608843672}
,09-08 14:32:24.928  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
09-08 14:32:24.928  1015  1319 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
09-08 14:32:24.928  7771  7771 I libpersona: KNOX_SDCARD checking this for 10029
09-08 14:32:24.928  1015  1319 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
09-08 14:32:24.928  7771  7771 I libpersona: KNOX_SDCARD not a persona
09-08 14:32:24.928  7771  7771 E Zygote  : MountEmulatedStorage()
09-08 14:32:24.928  7771  7771 E Zygote  : v2
,09-08 14:32:24.938  7771  7771 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-08 14:32:24.938  7771  7771 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 14:32:24.938  1015  1495 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7771 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
09-08 14:32:24.938  7771  7771 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 14:32:24.938  1015  1495 I ActivityManager: Killing 7286:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-08 14:32:24.948  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-08 14:32:24.948  1015  1495 I ActivityManager: Killing 7465:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,09-08 14:32:24.948  7705  7748 D Compatibility: enabling receiver ResolveInfo{181e229 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
09-08 14:32:24.948  1015  1762 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,09-08 14:32:24.958  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:24.958  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.958  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:24.958  1015  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:24.958   323   323 I art     : Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 622us total 20.974ms
09-08 14:32:24.958  7705  7748 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
09-08 14:32:24.958  7644  7644 D AndroidRuntime: Shutting down VM
,09-08 14:32:24.968  7771  7771 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:32:24.968  7771  7771 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:24.968  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 14:32:24.978  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-08 14:32:24.978  1015  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-08 14:32:24.978  1015  1056 D PackageManager: userId{-1}
09-08 14:32:24.978  1015  1056 D PackageManager: andCode{true}
,09-08 14:32:24.978   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 22.966ms
,09-08 14:32:24.998   323   323 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.170ms
,09-08 14:32:25.008  7786  7786 E Zygote  : MountEmulatedStorage(),
09-08 14:32:25.008  7786  7786 E Zygote  : v2
09-08 14:32:25.008  7786  7786 I libpersona: KNOX_SDCARD checking this for 10087
09-08 14:32:25.008  7786  7786 I libpersona: KNOX_SDCARD not a persona
09-08 14:32:25.008  1015  1762 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7786 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
09-08 14:32:25.008  7786  7786 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:32:25.008  1015  1762 I ActivityManager: Killing 7434:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-08 14:32:25.018  7786  7786 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 14:32:25.018  1015  1327 D PersonaManager: isKioskContainerExistOnDevice
,09-08 14:32:25.018  7786  7786 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-08 14:32:25.038  7786  7786 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:32:25.038  7786  7786 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:25.038  1015  1490 I ActivityManager: Killing 6861:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,09-08 14:32:25.038  7738  7738 D ThemeInfoUtil: getCurrentFestivalName is [null]
09-08 14:32:25.038  7738  7738 D ThemeInfoUtil: isCurrentFestival = false
,09-08 14:32:25.048  1015  1327 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,09-08 14:32:25.048  1015  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:25.048  1015  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:25.048  1015  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:25.048  1015  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:25.068  1015  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
09-08 14:32:25.068  7802  7802 E Zygote  : MountEmulatedStorage(),
09-08 14:32:25.068  7802  7802 E Zygote  : v2
09-08 14:32:25.068  7802  7802 I libpersona: KNOX_SDCARD checking this for 10148,
09-08 14:32:25.078  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-08 14:32:25.078  7802  7802 I libpersona: KNOX_SDCARD not a persona,
09-08 14:32:25.078  7802  7802 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:32:25.078  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-08 14:32:25.078  1015  1327 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7802 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
09-08 14:32:25.078  7802  7802 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:32:25.078  7802  7802 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 14:32:25.078  1015  1135 I ActivityManager: Killing 7501:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,09-08 14:32:25.098  1015  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-08 14:32:25.098  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 14:32:25.108  1015  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-08 14:32:25.108  1015  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 14:32:25.108  1015  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-08 14:32:25.108  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 14:32:25.108  1015  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:25.118  7802  7802 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:32:25.118  1015  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:25.118  1015  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:25.118  7802  7802 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:25.118  1015  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:25.118  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 14:32:25.118  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 14:32:25.128  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-08 14:32:25.128  1015  1475 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-08 14:32:25.128  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-08 14:32:25.128  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-08 14:32:25.128  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-08 14:32:25.128  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-08 14:32:25.138  7817  7817 E Zygote  : MountEmulatedStorage()
09-08 14:32:25.138  7817  7817 E Zygote  : v2
09-08 14:32:25.138  7817  7817 I libpersona: KNOX_SDCARD checking this for 10003
09-08 14:32:25.138  7817  7817 I libpersona: KNOX_SDCARD not a persona
09-08 14:32:25.138  7817  7817 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:32:25.138  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-08 14:32:25.138  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-08 14:32:25.138  7817  7817 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-08 14:32:25.138  1015  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7817 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-08 14:32:25.138  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 14:32:25.138  7817  7817 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 14:32:25.148  1015  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-08 14:32:25.148  1015  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-08 14:32:25.168  7644  7644 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-08 14:32:25.168  7817  7817 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:32:25.178  7817  7817 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:25.178  1015  1135 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-08 14:32:25.178  1015  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-08 14:32:25.188  1015  1135 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:25.188  1015  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:32:25.188  1015  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-08 14:32:25.188  1015  1464 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-08 14:32:25.188  1015  1028 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
,09-08 14:32:25.198  1015  1490 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-08 14:32:25.198  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-08 14:32:25.198  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
09-08 14:32:25.198  1015  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 14:32:25.198  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-08 14:32:25.208  7802  7802 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,09-08 14:32:25.208  1481  1481 I Choreographer: Skipped 32 frames!  The application may be doing too much work on its main thread.
,09-08 14:32:25.208  1481  1481 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2dd31f20 time:170286
,09-08 14:32:25.218  1015  1319 I ActivityManager: Killing 7520:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-08 14:32:25.218  7771  7832 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,09-08 14:32:25.218  1015  1490 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
09-08 14:32:25.218  1015  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,09-08 14:32:25.218  1015  1490 W ActivityManager: userId = 0, bbcId = -10000
,09-08 14:32:25.218  1015  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 14:32:25.218  1015  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,09-08 14:32:25.228  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-08 14:32:25.228  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:25.228  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:25.228  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:25.228  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:25.238  7839  7839 E Zygote  : MountEmulatedStorage(),
09-08 14:32:25.238  7839  7839 E Zygote  : v2
09-08 14:32:25.238  7839  7839 I libpersona: KNOX_SDCARD checking this for 10055
,09-08 14:32:25.238  7839  7839 I libpersona: KNOX_SDCARD not a persona
,09-08 14:32:25.238  1015  1027 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7839 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
09-08 14:32:25.248  7839  7839 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:32:25.248  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-08 14:32:25.248  7839  7839 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:32:25.248  7839  7839 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 14:32:25.248  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:25.248  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:25.248  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:25.248  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 14:32:25.268  7839  7839 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:32:25.268  7839  7839 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:25.278  7771  7832 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-08 14:32:25.278  7771  7832 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 14:32:25.278  7771  7832 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 14:32:25.278  7771  7832 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-08 14:32:25.278  7771  7832 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-08 14:32:25.278  7854  7854 E Zygote  : MountEmulatedStorage(),
09-08 14:32:25.278  7854  7854 E Zygote  : v2
09-08 14:32:25.278  7854  7854 I libpersona: KNOX_SDCARD checking this for 10032
09-08 14:32:25.278  7854  7854 I libpersona: KNOX_SDCARD not a persona
,09-08 14:32:25.288  7854  7854 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:32:25.288  1015  1027 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7854 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 14:32:25.288  7771  7832 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-08 14:32:25.288  7771  7832 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-08 14:32:25.288  7771  7832 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-08 14:32:25.288  7771  7832 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 14:32:25.288  7771  7832 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 14:32:25.288  7771  7832 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-08 14:32:25.288  1015  1027 I ActivityManager: Killing 6924:com.sec.android.soagent/u0a31 (adj 15): empty #21
09-08 14:32:25.288  7854  7854 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:32:25.288  7854  7854 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-08 14:32:25.308  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,09-08 14:32:25.318  7771  7832 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
09-08 14:32:25.318  7771  7832 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 14:32:25.318  7771  7832 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 14:32:25.318  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:25.318  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:25.318  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 14:32:25.318  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-08 14:32:25.328  7771  7832 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-08 14:32:25.328  7771  7832 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 14:32:25.328  7771  7832 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-08 14:32:25.348  7854  7854 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:32:25.348  7854  7854 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:25.348  7869  7869 E Zygote  : MountEmulatedStorage()
,09-08 14:32:25.348  7869  7869 E Zygote  : v2
09-08 14:32:25.348  7869  7869 I libpersona: KNOX_SDCARD checking this for 10152
,09-08 14:32:25.348  7869  7869 I libpersona: KNOX_SDCARD not a persona
,09-08 14:32:25.358  1015  1027 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7869 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,09-08 14:32:25.358  7869  7869 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-08 14:32:25.358  7869  7869 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-08 14:32:25.368  7869  7869 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 14:32:25.368  7771  7832 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-08 14:32:25.368  7771  7832 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 14:32:25.368  7771  7832 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 14:32:25.368  7771  7832 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-08 14:32:25.368  7771  7832 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-08 14:32:25.368  7771  7832 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-08 14:32:25.368  7771  7832 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-08 14:32:25.378  1015  1027 I ActivityManager: Killing 7008:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,09-08 14:32:25.378  7869  7869 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 14:32:25.378  7869  7869 D ActivityThread: Added TimaKeyStore provider
,09-08 14:32:25.388  7771  7832 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 14:32:25.388  7771  7832 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-08 14:32:25.388  7771  7832 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-08 14:32:25.398  7771  7832 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-08 14:32:25.398  7771  7832 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-08 14:32:25.398  7771  7832 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 14:32:25.398  7771  7832 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-08 14:32:25.408  7839  7839 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-08 14:32:25.408  7771  7832 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-08 14:32:25.408  7771  7832 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 14:32:25.408  7771  7832 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-08 14:32:25.408  7771  7832 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-08 14:32:25.418  7869  7869 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,09-08 14:32:25.418  7869  7869 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10

```
