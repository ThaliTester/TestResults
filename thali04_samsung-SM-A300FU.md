#### Test 79763830bc83054_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
08-25 10:46:17.847   289   289 E SMD     : DCD OFF
,08-25 10:46:18.127  6730  6730 D AndroidRuntime: 
08-25 10:46:18.127  6730  6730 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 10:46:18.137  6730  6730 D AndroidRuntime: CheckJNI is OFF
08-25 10:46:18.137  6730  6730 D AndroidRuntime: readGMSProperty: start
08-25 10:46:18.137  6730  6730 D AndroidRuntime: readGMSProperty: already setted!!
08-25 10:46:18.137  6730  6730 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-25 10:46:18.137  6730  6730 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-25 10:46:18.137  6730  6730 D AndroidRuntime: readGMSProperty: end
08-25 10:46:18.137  6730  6730 D AndroidRuntime: addProductProperty: start
08-25 10:46:18.257  6730  6730 E AffinityControl: AffinityControl: registerfunction enter
08-25 10:46:18.287  6730  6730 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-25 10:46:18.297  1016  1028 E PersonaManagerService: inState():  stateMachine is null !!
08-25 10:46:18.307  1016  1028 I PersonaManagerService: PersonaId don't exist
08-25 10:46:18.307  1016  1028 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-25 10:46:18.307  1016  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-25 10:46:18.327  1016  1028 W ActivityManager: mDVFSHelper.acquire()
08-25 10:46:18.327   259   259 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-25 10:46:18.327   259   259 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-25 10:46:18.337  1016  1028 D FocusedStackFrame: Set to : 0
08-25 10:46:18.347  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:18.347  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:18.347  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:18.347  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:18.347  1016  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-25 10:46:18.347  1016  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-25 10:46:18.357  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-25 10:46:18.357  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-25 10:46:18.357   259   259 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-25 10:46:18.367  6741  6741 E Zygote  : MountEmulatedStorage()
08-25 10:46:18.367  6741  6741 E Zygote  : v2
08-25 10:46:18.367  6741  6741 I libpersona: KNOX_SDCARD checking this for 10171
08-25 10:46:18.367  6741  6741 I libpersona: KNOX_SDCARD not a persona
08-25 10:46:18.367  6741  6741 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 10:46:18.367  1016  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-25 10:46:18.367  1016  1028 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6741 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-25 10:46:18.367  1016  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-25 10:46:18.367  1016  1028 D InputDispatcher: Focused application set to: xxxx
08-25 10:46:18.367  1016  1028 D InputDispatcher: Focus left window: 1475
08-25 10:46:18.367  6730  6730 D AndroidRuntime: Shutting down VM
08-25 10:46:18.377  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-25 10:46:18.377  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-25 10:46:18.377  6741  6741 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 10:46:18.377  6741  6741 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-25 10:46:18.397  6741  6741 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 10:46:18.397  6741  6741 D ActivityThread: Added TimaKeyStore provider
08-25 10:46:18.407  1016  1549 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-25 10:46:18.407  1016  1016 V ActivityManager: Display changed displayId=0
08-25 10:46:18.407  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-25 10:46:18.417  1016  1549 D PersonaManager: isKioskContainerExistOnDevice
08-25 10:46:18.437  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-25 10:46:18.457   259   704 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-25 10:46:18.457   259   705 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-25 10:46:18.467  1475  1475 V ActivityThread: updateVisibility : ActivityRecord{3306545a token=android.os.BinderProxy@2b6966c7 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-25 10:46:18.467  1475  1475 D Launcher: onTrimMemory. Level: 20
08-25 10:46:18.537  6741  6741 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-25 10:46:18.557  6741  6741 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 7518-7520)
08-25 10:46:18.557  6741  6741 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-25 10:46:18.577  6730  6730 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-25 10:46:18.577  6741  6741 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b6eb8ee}
08-25 10:46:18.577  6741  6741 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-25 10:46:18.587  6741  6741 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 10:46:18.627  6741  6741 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-25 10:46:18.627  6741  6741 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 10:46:18.637  6741  6741 E SysUtils: ApplicationContext is null in ApplicationStatus
08-25 10:46:18.677  6741  6741 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 10:46:18.677  6741  6741 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 10:46:18.677  6741  6741 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 10:46:18.677  6741  6741 I Adreno-EGL: Local Branch: 
08-25 10:46:18.677  6741  6741 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 10:46:18.677  6741  6741 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 10:46:18.677  6741  6741 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-25 10:46:18.767  6741  6741 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 10:46:18.787  6741  6741 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-25 10:46:18.787  6741  6741 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-25 10:46:18.797  6741  6741 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-25 10:46:18.797  6741  6741 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-25 10:46:18.887  1016  1303 E Watchdog: !@Sync 3
08-25 10:46:18.927  1016  1041 W ActivityManager: Activity pause timeout for ActivityRecord{27e8944 u0 com.test.thalitest/.MainActivity t2}
08-25 10:46:18.937  6741  6741 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 10:46:18.947  6741  6741 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-25 10:46:18.957  6741  6741 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-25 10:46:18.957  6741  6741 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-25 10:46:18.967  6741  6741 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-25 10:46:18.967  6741  6741 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 10:46:18.967  6741  6741 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 10:46:19.077  6741  6781 D OpenGLRenderer: Render dirty regions requested: true
08-25 10:46:19.077  1016  1549 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-25 10:46:19.087  1016  1549 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-25 10:46:19.087  1016  1549 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-25 10:46:19.087  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-25 10:46:19.087  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-25 10:46:19.087  6741  6768 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-25 10:46:19.097  6741  6741 V ActivityThread: updateVisibility : ActivityRecord{22d464e token=android.os.BinderProxy@2a42c913 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-25 10:46:19.097  6741  6741 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-25 10:46:19.097  6741  6741 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-25 10:46:19.107   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-25 10:46:19.127  1016  1134 D InputDispatcher: Focus entered window: 6741
08-25 10:46:19.137  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-25 10:46:19.137  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-25 10:46:19.137  6741  6741 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-25 10:46:19.137  6741  6781 I OpenGLRenderer: Initialized EGL, version 1.4
08-25 10:46:19.137  6741  6781 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-25 10:46:19.147  6741  6781 D OpenGLRenderer: Enabling debug mode 0
08-25 10:46:19.157  1016  1216 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-25 10:46:19.167  1176  1176 I StatusBar: Icon Only
08-25 10:46:19.167  1176  1176 D PanelView: There is/are notification(s) 
08-25 10:46:19.167  1016  6785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-25 10:46:19.177  1016  1046 I ActivityManager: Displayed Component not be shown by security: +751ms (total +837ms)
08-25 10:46:19.177  1016  1046 W ActivityManager: mDVFSHelper.release()
08-25 10:46:19.177  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{27e8944 u0 com.test.thalitest/.MainActivity t2} time:108147
08-25 10:46:19.187  6741  6741 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-25 10:46:19.187   259   704 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-25 10:46:19.187   259   705 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-25 10:46:19.197  6741  6741 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2a42c913 time:108160
08-25 10:46:19.217  1875  1875 I SamsungIME: getCurrentCandidateView
08-25 10:46:19.267  6741  6741 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6741
08-25 10:46:19.327  1875  1875 D SamsungIME: Dismiss ExpandCandiate
,08-25 10:46:19.467  1875  1875 I SamsungIME: getDebugLevel  : 0x4f4c
,08-25 10:46:19.477  6741  6741 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 10:46:19.517  1875  1875 I SamsungIME: getDebugLevel  : 0x4f4c
,08-25 10:46:19.527  1875  1875 I SamsungIME: KeybaordView init() : load resources
,08-25 10:46:19.557  1875  1875 I SamsungIME: getCurrentKeyboard
08-25 10:46:19.557  1875  1875 I SamsungIME: getTextKeyboard
,08-25 10:46:19.577  6741  6787 D jxcore_app_log: JniHelper::setJavaVM(0xb8a512b0), pthread_self() = -1191347368
,08-25 10:46:19.577  1875  1875 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-25 10:46:19.577  6741  6787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 10:46:19.577  6741  6787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 10:46:19.577  6741  6787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 10:46:19.577  6741  6787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 10:46:19.577  6741  6787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-25 10:46:19.577  6741  6787 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d6dbb14 added. We now have 1 listener(s)
,08-25 10:46:19.587  6741  6787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-25 10:46:19.587  6741  6787 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 10:46:19.587  6741  6787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 10:46:19.587  6741  6787 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 10:46:19.597  6741  6787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 10:46:19.597  6741  6787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 10:46:19.597  6741  6787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 10:46:19.597  6741  6787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-25 10:46:19.597  6741  6787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 10:46:19.597  6741  6787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 10:46:19.597  6741  6787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 10:46:19.597  6741  6787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 10:46:19.597  6741  6787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 10:46:19.597  6741  6787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 10:46:19.597  6741  6787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 10:46:19.597  6741  6787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 10:46:19.597  6741  6787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 10:46:19.597  6741  6787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-25 10:46:19.597  6741  6787 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33c01d03 added. We now have 1 listener(s)
,08-25 10:46:19.597  6741  6787 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:46:19.607  6741  6787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 10:46:19.607  6741  6787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-25 10:46:19.607  6741  6787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 10:46:19.607  6741  6787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 10:46:19.607  6741  6787 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-25 10:46:19.607  6741  6787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:46:19.607  6741  6787 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-25 10:46:19.617  6741  6787 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-25 10:46:19.617  6741  6787 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:19.617  6741  6787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:19.617  6741  6787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:19.617  6741  6787 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:19.617  6741  6787 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:19.617  6741  6787 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:19.617  6741  6787 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:19.617  6741  6787 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:46:19.617  6741  6787 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 10:46:19.617  6741  6787 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 10:46:19.617  6741  6787 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 10:46:19.627  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-25 10:46:19.627  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:19.667  6741  6741 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 10:46:19.907   316   316 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-25 10:46:19.907   316   316 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-25 10:46:20.197  6741  6794 W jxcore-log: Initializing JXcore engine
08-25 10:46:20.197  6741  6794 W jxcore-log: JXcore engine is ready
,08-25 10:46:20.257  1999  1999 E audit   : type=1400 msg=audit(1472114780.257:205): avc:  denied  { ioctl } for  pid=6794 comm="Thread-1235" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-25 10:46:20.257  1999  1999 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-25 10:46:20.257  1999  1999 E audit   : type=1300 msg=audit(1472114780.257:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f4fb8f8 items=0 ppid=305 ppcomm=main pid=6794 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1235" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-25 10:46:20.257  1999  1999 E audit   : type=1320 msg=audit(1472114780.257:205): 
,08-25 10:46:20.267  6741  6794 W jxcore-log: Starting JXcore engine
,08-25 10:46:20.377  6741  6794 W jxcore-log: Platform android
08-25 10:46:20.377  6741  6794 W jxcore-log: 
08-25 10:46:20.377  6741  6794 W jxcore-log: Process ARCH arm
08-25 10:46:20.377  6741  6794 W jxcore-log: 
,08-25 10:46:20.587  6741  6794 I jxcore-log: JXcore Cordova bridge is ready!
08-25 10:46:20.587  6741  6794 I jxcore-log: 
,08-25 10:46:20.587  6741  6794 W jxcore-log: JXcore engine is started
,08-25 10:46:20.587  6741  6787 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-25 10:46:20.587  6741  6741 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 10:46:20.847   289   289 E SMD     : DCD OFF
,08-25 10:46:23.827  1016  1048 I PowerManagerService: [PWL] Off : 50s ago
,08-25 10:46:23.857   289   289 E SMD     : DCD OFF,
,08-25 10:46:23.897  1016  3343 D SSRM:n  : SIOP:: AP = 320
,08-25 10:46:24.907   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 10:46:25.147  5618  5618 D FactoryTest: Not factory mode
,08-25 10:46:25.147  5618  5618 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-25 10:46:25.147  5618  5618 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-25 10:46:25.147  5618  5618 D MTPRx   : still no open session command from host, so toast
,08-25 10:46:25.157  5618  5618 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-25 10:46:25.157  5618  5618 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-25 10:46:25.157  5618  5618 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114126
,08-25 10:46:25.157  1016  1028 E PersonaManagerService: inState():  stateMachine is null !!
,08-25 10:46:25.157  1016  1028 I PersonaManagerService: PersonaId don't exist
08-25 10:46:25.157  1016  1028 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-25 10:46:25.167  1016  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-25 10:46:25.167  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:25.167  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:25.167  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
08-25 10:46:25.167  1016  1028 W ActivityManager: mDVFSHelper.acquire()
,08-25 10:46:25.187  1016  1028 D PersonaManager: isKioskContainerExistOnDevice
,08-25 10:46:25.187  1016  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-25 10:46:25.187  1016  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-25 10:46:25.187  1016  1028 D InputDispatcher: Focused application set to: xxxx
08-25 10:46:25.187  1016  1028 D InputDispatcher: Focus left window: 6741
08-25 10:46:25.197  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-25 10:46:25.197  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 10:46:25.207  5618  5618 E MTPRx   : started activity for popup
,08-25 10:46:25.227  5618  5618 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-25 10:46:25.227  5618  5618 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-25 10:46:25.227  5618  5618 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-25 10:46:25.227  5618  5618 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 10:46:25.227  5618  5618 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-25 10:46:25.227  5618  5618 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 10:46:25.247  5618  5618 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-25 10:46:25.257  1016  1134 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-25 10:46:25.257  1016  1134 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-25 10:46:25.257  1016  1134 D InputDispatcher: Focused application set to: xxxx
08-25 10:46:25.257  1016  1134 D InputDispatcher: Focus entered window: 6741
,08-25 10:46:25.257  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-25 10:46:25.267  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 10:46:25.267  1016  1483 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-25 10:46:25.267  1016  1483 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@9aa1527 attribute=null, token = android.os.BinderProxy@2482b037
,08-25 10:46:25.297  5618  5618 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-25 10:46:25.307  5618  5618 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-25 10:46:25.307  5618  5618 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-25 10:46:25.327  6741  6741 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-25 10:46:25.327  6741  6741 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-25 10:46:25.327  6741  6741 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-25 10:46:25.327  6741  6741 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-25 10:46:25.327  1016  1380 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-25 10:46:25.337  1016  1380 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-25 10:46:25.337  1016  1380 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-25 10:46:25.337  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-25 10:46:25.337  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-25 10:46:25.347  6741  6741 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 10:46:25.347  6741  6741 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-25 10:46:25.347  6741  6741 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3b77dc7f Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@9d926b4, 16908290=android.view.AbsSavedState$1@9d926b4}, android:focusedViewId=100}]}]
08-25 10:46:25.347  6741  6741 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-25 10:46:25.347  6741  6741 V ActivityThread: updateVisibility : ActivityRecord{22d464e token=android.os.BinderProxy@2a42c913 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-25 10:46:25.347  6741  6741 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 10:46:25.347  6741  6741 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-25 10:46:25.347  6741  6741 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2a42c913 time:114316
,08-25 10:46:25.357  1016  1216 D PersonaManager: isKioskContainerExistOnDevice
,08-25 10:46:25.907   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 10:46:26.857   289   289 E SMD     : DCD OFF
,08-25 10:46:26.907   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 10:46:27.247  1016  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 10:46:27.247  1016  1481 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-25 10:46:27.247  1016  1481 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-25 10:46:27.247  1016  1481 D BatteryService: stay LED for fully charged
,08-25 10:46:27.247  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-25 10:46:27.247  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-25 10:46:27.247  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-25 10:46:27.257  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-25 10:46:27.257  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-25 10:46:27.257  1016  1016 I MotionRecognitionService: Plugged
08-25 10:46:27.257  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 10:46:27.267  3167  3167 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-25 10:46:27.267  3167  3282 D HeadsetStateMachine: Disconnected process message: 10
,08-25 10:46:27.277  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 10:46:27.277  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-25 10:46:27.277  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 10:46:27.907   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 10:46:28.167  1016  1041 W ActivityManager: mDVFSHelper.release(),
,08-25 10:46:28.387  1016  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-25 10:46:28.907   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 10:46:29.857   289   289 E SMD     : DCD OFF,
,08-25 10:46:29.907   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-25 10:46:31.037  1016  1094 V AlarmManager: waitForAlarm result :4
,08-25 10:46:31.047  1016  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-25 10:46:31.067  1954  1954 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-25 10:46:31.107  1016  1483 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 10:46:31.107  1016  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-25 10:46:31.107  1016  1483 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:31.107  1016  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:31.107  1016  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:31.197  4811  4811 D ConnectivityManager: CallingUid : 10011, CallingPid : 4811
,08-25 10:46:31.207  1016  1549 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-25 10:46:31.207  1016  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-25 10:46:31.207  1016  1126 D ConnectivityService: apparently satisfied.  currentScore=60
,08-25 10:46:31.207  1016  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
08-25 10:46:31.207  4811  6803 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-25 10:46:31.257  4811  6804 W DriveInitializer: Background init thread started
,08-25 10:46:31.277   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-25 10:46:31.277   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 10:46:31.287  4811  6804 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-25 10:46:31.347  1016  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 10:46:31.347  1016  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-25 10:46:31.347  1016  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:31.347  1016  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:31.347  1016  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:31.367  1016  1485 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-25 10:46:31.367  1016  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-25 10:46:31.387  1016  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 10:46:31.387  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-25 10:46:31.387  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:31.387  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:31.387  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:31.427  1954  1954 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-25 10:46:31.447  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:31.447  1016  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:31.447  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:31.467  1016  1380 I art     : Explicit concurrent mark sweep GC freed 36421(2023KB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 24MB/36MB, paused 2.705ms total 171.154ms
,08-25 10:46:31.487  4811  6807 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-25 10:46:31.487  4811  6807 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-25 10:46:31.557  4811  6804 W DriveInitializer: Background init thread ended
,08-25 10:46:31.617  1016  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 10:46:31.617  1016  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-25 10:46:31.617  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:31.617  1016  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:31.617  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:31.657  1016  1483 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 10:46:31.657  1016  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-25 10:46:31.667  1016  1483 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:31.667  1016  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:31.667  1016  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:31.727  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:31.727  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:31.727  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:31.727  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:31.737  1016  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:31.747  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:31.747  1016  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:31.747  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:31.827  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:31.827  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:31.827  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:31.827  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:31.837  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:31.837  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:31.837  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:31.837  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:31.847  6819  6819 E Zygote  : MountEmulatedStorage()
08-25 10:46:31.847  6819  6819 E Zygote  : v2
08-25 10:46:31.847  6819  6819 I libpersona: KNOX_SDCARD checking this for 10011
,08-25 10:46:31.847  6819  6819 I libpersona: KNOX_SDCARD not a persona
,08-25 10:46:31.847  1016  1029 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6819 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,08-25 10:46:31.867  6819  6819 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-25 10:46:31.867  6819  6819 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 10:46:31.867  6819  6819 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 10:46:31.887   305   305 I art     : Explicit concurrent mark sweep GC freed 8706(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 42.804ms
,08-25 10:46:31.907  6819  6819 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:31.907  6819  6819 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:31.907   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 17.225ms
,08-25 10:46:31.927   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 16.812ms
,08-25 10:46:31.927  6819  6819 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-25 10:46:31.927  6819  6819 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-25 10:46:31.967  6819  6819 I MultiDex: VM with version 2.1.0 has multidex support
08-25 10:46:31.967  6819  6819 I MultiDex: install
08-25 10:46:31.967  6819  6819 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-25 10:46:31.997  6819  6819 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-25 10:46:32.057  1016  1380 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-25 10:46:32.067  1016  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:32.067  6819  6819 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-25 10:46:32.067  6819  6819 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d74ed0a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-25 10:46:32.067  6819  6819 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-25 10:46:32.067  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:32.067  1016  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:32.067  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:32.087  1016  1550 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:32.087  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:32.087  1016  1550 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:32.087  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:32.087  6819  6819 D ChimeraCfgMgr: Reading stored module config
,08-25 10:46:32.137  1954  1954 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=fd88120d-4385-4bab-a63e-4649e00b9745
,08-25 10:46:32.137  6819  6832 W art     : Suspending all threads took: 8.262ms
,08-25 10:46:32.167  6819  6832 I art     : Background sticky concurrent mark sweep GC freed 28416(1331KB) AllocSpace objects, 2(32KB) LOS objects, 2% free, 7MB/7MB, paused 12.435ms total 61.516ms
,08-25 10:46:32.167  1016  1481 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-25 10:46:32.167  1016  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-25 10:46:32.167  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:32.167  1016  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:32.167  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:32.177  1954  1954 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-25 10:46:32.177  1954  1954 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-25 10:46:32.197  1016  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:32.207  1016  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:32.207  1016  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:32.207  1016  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:32.207  6819  6838 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-25 10:46:32.227  6819  6819 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-25 10:46:32.227  6819  6819 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-25 10:46:32.317   284   992 D WVCdm   : Instantiating CDM.
,08-25 10:46:32.317   284   284 I WVCdm   : CdmEngine::OpenSession
,08-25 10:46:32.317   284   284 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-25 10:46:32.337   284   284 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-25 10:46:32.367   284   284 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-25 10:46:32.417   284   284 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-25 10:46:32.417  4273  4285 I art     : Explicit concurrent mark sweep GC freed 1424(48KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 687us total 21.160ms
,08-25 10:46:32.417   284   694 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-25 10:46:32.417   284   694 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-25 10:46:32.417   284   694 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-25 10:46:32.427   284   694 D WVCdm   : PrepareKeyRequest: nonce=2118456214
,08-25 10:46:32.437  6819  6833 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-25 10:46:32.437  6819  6833 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 10:46:32.437  6819  6833 I System.out: (HTTPLog)-Static: isShipBuild true
08-25 10:46:32.437  6819  6833 I System.out: (HTTPLog)-Thread-1215-995804495: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-25 10:46:32.447  6819  6833 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 10:46:32.447   276  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 10:46:32.447   276  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-25 10:46:32.457  1954  2137 I art     : Explicit concurrent mark sweep GC freed 56268(3MB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 11MB/18MB, paused 1.630ms total 153.730ms
,08-25 10:46:32.497  6819  6833 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-25 10:46:32.497  6819  6833 I qtaguid : Tagging socket 33 with tag 1000180300000000{268441603,0} for uid -1, pid: 6819, getuid(): 10011
,08-25 10:46:32.497  1954  2124 W GCoreFlp: No location to return for getLastLocation()
,08-25 10:46:32.527  1016  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:32.527  1016  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:32.527  1016  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:32.527  1016  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:32.537  1016  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:32.537  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:32.537  1016  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:32.537  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:32.547  1016  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:32.547  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:32.547  1016  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 10:46:32.547  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:32.567  4811  6815 D UdcContextInitService: registered all accounts: true
,08-25 10:46:32.567  1954  2127 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-25 10:46:32.607  1954  2137 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-25 10:46:32.667  1016  3375 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-25 10:46:32.777  1016  1483 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-25 10:46:32.777  1016  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-25 10:46:32.777  1016  1483 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:32.777  1016  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:32.777  1016  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:32.787  6819  6833 I qtaguid : Untagging socket 33
,08-25 10:46:32.797  1016  1481 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-25 10:46:32.797  1016  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-25 10:46:32.807  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:32.807  1016  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:32.807  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-25 10:46:32.807  1954  2137 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-25 10:46:32.817   276  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 10:46:32.817   276  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
08-25 10:46:32.817  1954  2137 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-25 10:46:32.817  1954  2137 I qtaguid : Tagging socket 65 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1954, getuid(): 10011
,08-25 10:46:32.857   289   289 E SMD     : DCD OFF
,08-25 10:46:32.877  1954  2137 I qtaguid : Tagging socket 69 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1954, getuid(): 10011
,08-25 10:46:33.377  6852  6852 I dex2oat : ----------------------------------------------------
08-25 10:46:33.377  6852  6852 I dex2oat : <SS>: S T A R T I N G . . .
08-25 10:46:33.377  6852  6852 I dex2oat : <SS>: Zip is absent. Canceled.
08-25 10:46:33.377  6852  6852 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-25 10:46:33.427  6852  6852 I dex2oat : dex2oat took 43.862ms (threads: 4)
,08-25 10:46:33.437  6819  6833 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 10:46:33.437  6819  6833 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 10:46:33.437  6819  6833 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 10:46:33.437  6819  6833 I Adreno-EGL: Local Branch: 
08-25 10:46:33.437  6819  6833 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 10:46:33.437  6819  6833 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 10:46:33.437  6819  6833 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 10:46:33.577  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-25 10:46:33.577  6741  6794 I jxcore-log: 
,08-25 10:46:33.577  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-25 10:46:33.577  6741  6794 I jxcore-log: 
,08-25 10:46:33.587  6741  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:33.587  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:33.587  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:33.587  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:33.587  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:33.587  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:33.587  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:33.587  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 10:46:33.587  6741  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 10:46:33.587  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 10:46:33.587  6741  6794 I jxcore-log: 
,08-25 10:46:33.597  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 10:46:33.597  6741  6794 I jxcore-log: 
,08-25 10:46:33.617  6819  6833 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 10:46:33.617  6819  6833 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 10:46:33.617  6819  6833 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 10:46:33.617  6819  6833 I Adreno-EGL: Local Branch: 
08-25 10:46:33.617  6819  6833 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 10:46:33.617  6819  6833 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 10:46:33.617  6819  6833 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 10:46:33.657  6819  6833 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 10:46:33.657  6819  6833 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 10:46:33.657  6819  6833 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 10:46:33.657  6819  6833 I Adreno-EGL: Local Branch: 
08-25 10:46:33.657  6819  6833 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 10:46:33.657  6819  6833 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 10:46:33.657  6819  6833 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 10:46:33.757  1954  6817 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 10:46:33.757  1954  6817 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-25 10:46:33.757  1954  6817 I qtaguid : Tagging socket 70 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1954, getuid(): 10011
,08-25 10:46:33.807  1954  6817 I qtaguid : Tagging socket 73 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1954, getuid(): 10011
,08-25 10:46:33.917  1016  3343 D SSRM:n  : SIOP:: AP = 340
,08-25 10:46:33.937  1954  2137 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-25 10:46:33.947  1954  2137 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-25 10:46:33.947  1954  2137 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-25 10:46:32.694+0200, stopTime=2016-08-25 10:46:33.958+0200, duration=1264ms
,08-25 10:46:33.987  1954  6863 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 10:46:33.987   284   992 I WVCdm   : CdmEngine::CloseSession
,08-25 10:46:33.987   284   992 I WVCdm   : L3 Terminate.
,08-25 10:46:33.997   276  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 10:46:33.997   276  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-25 10:46:33.997  1954  6863 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-25 10:46:33.997  1954  6863 I qtaguid : Tagging socket 74 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1954, getuid(): 10011
,08-25 10:46:34.037  1954  6863 I qtaguid : Tagging socket 77 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1954, getuid(): 10011
,08-25 10:46:34.267  1954  6863 I qtaguid : Untagging socket 74
,08-25 10:46:34.287  6741  6794 D executeNativeTests: Running unit tests
,08-25 10:46:34.297  1016  1371 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 10:46:34.297  1016  1371 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-25 10:46:34.297  1016  1371 W ActivityManager: userId = 0, bbcId = -10000,
08-25 10:46:34.297  1016  1371 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:34.297  1016  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:34.327  1954  2137 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-25 10:46:34.397  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:34.397  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:34.397  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:34.397  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:34.407  6741  6755 I art     : Background sticky concurrent mark sweep GC freed 43433(2MB) AllocSpace objects, 7(993KB) LOS objects, 19% free, 10MB/13MB, paused 8.404ms total 60.379ms
,08-25 10:46:34.417  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:46:34.417  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d added. We now have 2 listener(s)
,08-25 10:46:34.417  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 10:46:34.417  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:46:34.417  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:46:34.417  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:46:34.417  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 added. We now have 2 listener(s)
08-25 10:46:34.417  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:46:34.417  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 10:46:34.427  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:46:34.427  6741  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:34.427  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:34.427  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:34.427  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:34.427  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:34.427  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:34.427  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:34.427  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 10:46:34.427  6741  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:34.427  6741  6794 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 10:46:34.437  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-25 10:46:34.437  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 10:46:34.437  6741  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 10:46:34.437  6741  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 10:46:34.437  6741  6794 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-25 10:46:34.437  6741  6794 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 10:46:34.437  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 10:46:34.437  6741  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 10:46:34.437  6741  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 10:46:34.437  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 10:46:34.437  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.437  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:34.437  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.437  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.437  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:46:34.437  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:46:34.437  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d removed from the list
,08-25 10:46:34.437  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.437  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 removed from the list
08-25 10:46:34.437  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:34.437  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.437  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.437  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.437  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.447  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:34.447  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.447  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.447  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-25 10:46:34.447  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:34.447  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.447  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:34.447  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.447  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.447  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.447  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.447  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.447  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.447  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.447  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.447  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.447  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.447  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:34.447  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.447  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.447  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 10:46:34.447  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 10:46:34.457  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:34.457  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.457  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:34.457  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.457  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.457  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.457  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.457  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.457  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.457  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.457  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.457  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.457  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.457  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.457  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:34.457  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.457  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.457  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.457  6741  6794 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 10:46:34.457  1016  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-25 10:46:34.457  1016  1485 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:34.457  1016  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:34.457  1016  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-25 10:46:34.467  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:46:34.467  6741  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:34.467  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:34.467  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:34.467  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:34.467  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:34.467  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:34.467  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:34.467  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:46:34.477  6741  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:34.477  6741  6794 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:46:34.477  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:46:34.477  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 10:46:34.477  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 10:46:34.477  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:46:34.477  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 10:46:34.477  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 10:46:34.477  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:34.477  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:34.487  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 10:46:34.487  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 10:46:34.497  6741  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-25 10:46:34.497  6741  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-25 10:46:34.497  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 10:46:34.497  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 10:46:34.497  6741  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 10:46:34.517  3167  5143 D BtGatt.GattService: registerClient() - UUID=d2f3ccfe-7698-4f66-80a4-20f224fde04c
,08-25 10:46:34.537  1016  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:34.537  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:34.537  1016  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:34.537  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:34.537  1954  6869 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-25 10:46:34.537  1954  6867 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-25 10:46:34.537  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:34.537  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:34.537  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:34.537  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:34.567  1016  1134 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:34.567  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:34.567  3167  3273 D BtGatt.GattService: onClientRegistered() - UUID=d2f3ccfe-7698-4f66-80a4-20f224fde04c, clientIf=6
,08-25 10:46:34.567  1016  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 10:46:34.567  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:34.567  6741  6750 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 10:46:34.567  3167  3180 D BtGatt.GattService: start scan with filters
,08-25 10:46:34.577  1954  6869 E CommitToConfigurationOperation: Malformed snapshot token (size): ,
08-25 10:46:34.577  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 10:46:34.577  1954  6867 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-25 10:46:34.577  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 10:46:34.577  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 10:46:34.577  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 10:46:34.577  3167  3281 D BtGatt.ScanManager: handling starting scan,
,08-25 10:46:34.577  1016  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:34.577  1016  1483 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:34.577  3167  3281 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:34.577  1016  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:34.577  1016  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:34.587  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 10:46:34.587  6741  6741 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 10:46:34.587  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 10:46:34.587  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 10:46:34.597  6741  6794 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 10:46:34.597  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 10:46:34.597  6741  6794 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 10:46:34.597  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 10:46:34.597  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 10:46:34.597  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:34.597  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 10:46:34.597  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 10:46:34.597  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-25 10:46:34.597  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 10:46:34.597  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 10:46:34.607  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 10:46:34.607  3167  3273 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-25 10:46:34.607  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 10:46:34.607  3167  3281 D BtGatt.ScanManager: allow scan with filters
,08-25 10:46:34.607  3167  3281 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-25 10:46:34.607  3167  3281 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-25 10:46:34.607  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 10:46:34.607  3167  3180 D BtGatt.GattService: stopScan() - queue size =1,
08-25 10:46:34.607  3167  5143 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 10:46:34.607  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:46:34.607  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 10:46:34.607  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 10:46:34.607  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 10:46:34.607  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 10:46:34.607  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 10:46:34.607  3167  3273 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-25 10:46:34.607  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 10:46:34.607  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 10:46:34.607  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 10:46:34.607  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 10:46:34.617  3167  3281 D BtGatt.ScanManager: Starting BLE batch scan
08-25 10:46:34.617  3167  3281 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 10:46:34.617  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-25 10:46:34.617  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.617  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.617  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:46:34.617  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.617  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.617  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.617  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.617  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:34.617  6741  6794 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 10:46:34.617  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 10:46:34.617  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:46:34.617  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 10:46:34.617  6741  6741 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 10:46:34.627  3167  3273 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-25 10:46:34.627  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:34.627  1016  1216 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:34.627  1016  1216 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:34.627  1016  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:34.627  1016  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:34.627  6741  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:34.627  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:34.627  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:34.627  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:34.627  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:34.627  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:34.627  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:34.627  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 10:46:34.627  1954  6869 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-25 10:46:34.627  1954  6867 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-25 10:46:34.627  1954  6867 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-25 10:46:34.627  3167  3273 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-25 10:46:34.627  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:34.637  6741  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 10:46:34.637  6741  6794 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 10:46:34.637  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:34.637  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:46:34.637  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 10:46:34.637  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 10:46:34.637  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:46:34.637  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 10:46:34.637  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:34.647  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 10:46:34.647  3167  3281 D BtGatt.ScanManager: filter size is 1
08-25 10:46:34.647  3167  3281 D BtGatt.ScanManager: delete FilterIndex - 3
,08-25 10:46:34.647  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 10:46:34.647  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 10:46:34.647  3167  3273 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-25 10:46:34.647  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:34.647  3167  3281 D BtGatt.ScanManager: stopping BLe Batch
,08-25 10:46:34.647  1954  6867 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-25 10:46:34.657  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 10:46:34.657  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 10:46:34.657  6741  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 10:46:34.657  3167  3273 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-25 10:46:34.657  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:34.657  3167  3281 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 10:46:34.657  3167  3370 D BtGatt.GattService: registerClient() - UUID=c2a9369f-f109-4c12-9f09-e6d2a726c929
,08-25 10:46:34.667  3167  3273 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-25 10:46:34.667  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:34.697  1016  1216 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-25 10:46:34.697  3167  3273 D BtGatt.GattService: onClientRegistered() - UUID=c2a9369f-f109-4c12-9f09-e6d2a726c929, clientIf=6
,08-25 10:46:34.697  6741  6749 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 10:46:34.707  3167  3180 D BtGatt.GattService: start scan with filters
,08-25 10:46:34.707  3167  3281 D BtGatt.ScanManager: handling starting scan
,08-25 10:46:34.707  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 10:46:34.707  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 10:46:34.707  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 10:46:34.707  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 10:46:34.707  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 10:46:34.707  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 10:46:34.707  6741  6741 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 10:46:34.707  3167  3273 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-25 10:46:34.707  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:34.717  3167  3281 D BtGatt.ScanManager: allow scan with filters
,08-25 10:46:34.717  3167  3281 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 10:46:34.717  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 10:46:34.717  3167  3281 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-25 10:46:34.717  6741  6794 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 10:46:34.717  3167  3273 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-25 10:46:34.717  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:34.717  3167  3281 D BtGatt.ScanManager: Starting BLE batch scan
,08-25 10:46:34.717  3167  3281 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 10:46:34.727  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 10:46:34.727  6741  6794 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 10:46:34.727  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 10:46:34.727  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 10:46:34.727  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:34.727  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 10:46:34.727  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 10:46:34.727  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 10:46:34.727  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 10:46:34.727  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 10:46:34.727  3167  3273 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-25 10:46:34.727  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:34.727  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 10:46:34.727  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 10:46:34.727  3167  3176 D BtGatt.GattService: stopScan() - queue size =1
,08-25 10:46:34.737  3167  3370 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 10:46:34.737  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:46:34.737  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 10:46:34.737  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 10:46:34.737  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 10:46:34.737  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 10:46:34.737  3167  3273 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-25 10:46:34.737  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:34.737  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 10:46:34.737  3167  3281 D BtGatt.ScanManager: filter size is 1
08-25 10:46:34.737  3167  3281 D BtGatt.ScanManager: delete FilterIndex - 4
08-25 10:46:34.737  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 10:46:34.737  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 10:46:34.737  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 10:46:34.737  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:46:34.737  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.737  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.737  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:46:34.737  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.737  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.737  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.737  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.737  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.737  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.737  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:34.747  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:34.747  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.747  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.747  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
,08-25 10:46:34.747  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:46:34.747  6741  6794 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 10:46:34.747  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 10:46:34.747  6741  6741 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 10:46:34.747  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:46:34.747  3167  3273 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 10:46:34.747  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 10:46:34.747  3167  3281 D BtGatt.ScanManager: stopping BLe Batch
,08-25 10:46:34.747  6741  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:34.747  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:34.747  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:34.747  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:34.747  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:34.747  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:34.747  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:34.747  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 10:46:34.747  6741  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 10:46:34.747  6741  6794 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:46:34.747  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:46:34.747  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 10:46:34.747  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 10:46:34.747  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:46:34.747  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 10:46:34.757  3167  3273 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-25 10:46:34.757  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 10:46:34.757  3167  3281 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 10:46:34.757  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:34.757  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 10:46:34.757  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:34.757  3167  3273 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-25 10:46:34.757  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:34.767  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 10:46:34.767  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 10:46:34.767  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 10:46:34.767  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 10:46:34.767  6741  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 10:46:34.777  3167  3370 D BtGatt.GattService: registerClient() - UUID=f63081a4-da8b-4461-9cb0-2967e6ab8482
,08-25 10:46:34.787  1954  6867 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 10:46:34.787   276  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 10:46:34.787   276  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-25 10:46:34.797  1954  6867 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
08-25 10:46:34.797  1954  6867 I qtaguid : Tagging socket 86 with tag fffffca200000000{4294966434,0} for uid -1, pid: 1954, getuid(): 10011
,08-25 10:46:34.817  3167  3273 D BtGatt.GattService: onClientRegistered() - UUID=f63081a4-da8b-4461-9cb0-2967e6ab8482, clientIf=6
,08-25 10:46:34.817  6741  6750 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-25 10:46:34.817  3167  3180 D BtGatt.GattService: start scan with filters
,08-25 10:46:34.817  3167  3281 D BtGatt.ScanManager: handling starting scan
,08-25 10:46:34.817  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 10:46:34.817  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 10:46:34.817  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 10:46:34.817  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 10:46:34.827  3167  3273 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-25 10:46:34.827  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:34.827  3167  3281 D BtGatt.ScanManager: allow scan with filters
,08-25 10:46:34.827  3167  3281 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-25 10:46:34.827  3167  3281 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-25 10:46:34.827  3167  3273 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-25 10:46:34.827  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:34.827  3167  3281 D BtGatt.ScanManager: Starting BLE batch scan
08-25 10:46:34.827  3167  3281 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 10:46:34.837  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 10:46:34.837  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 10:46:34.837  6741  6741 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 10:46:34.837  3167  3273 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-25 10:46:34.837  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:34.837  1954  6867 I qtaguid : Tagging socket 89 with tag fffffca200000000{4294966434,0} for uid -1, pid: 1954, getuid(): 10011
,08-25 10:46:34.837  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 10:46:34.837  3167  3273 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-25 10:46:34.837  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:34.847  6741  6794 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 10:46:34.847  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 10:46:34.847  6741  6794 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 10:46:34.847  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.847  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 10:46:34.847  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:34.847  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 10:46:34.847  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 10:46:34.847  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 10:46:34.857  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 10:46:34.857  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 10:46:34.857  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 10:46:34.857  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 10:46:34.857  3167  3370 D BtGatt.GattService: stopScan() - queue size =1
,08-25 10:46:34.857  3167  3281 D BtGatt.ScanManager: filter size is 1
,08-25 10:46:34.857  3167  3281 D BtGatt.ScanManager: delete FilterIndex - 5
,08-25 10:46:34.857  3167  3273 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-25 10:46:34.857  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 10:46:34.857  3167  3281 D BtGatt.ScanManager: stopping BLe Batch
08-25 10:46:34.857  3167  3180 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 10:46:34.857  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:46:34.867  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 10:46:34.867  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 10:46:34.867  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 10:46:34.867  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 10:46:34.867  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 10:46:34.867  3167  3273 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-25 10:46:34.867  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 10:46:34.867  3167  3281 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 10:46:34.867  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 10:46:34.867  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 10:46:34.867  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 10:46:34.867  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:46:34.867  3167  3273 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-25 10:46:34.867  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:34.867  6741  6794 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 10:46:34.867  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.867  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:34.867  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.867  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.867  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:46:34.867  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.867  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.867  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.867  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.867  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:34.867  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:46:34.877  3167  3273 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 10:46:34.877  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 10:46:34.877  6741  6741 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 10:46:34.877  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.877  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:34.877  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:34.877  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.877  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.877  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
,08-25 10:46:34.877  6741  6794 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-25 10:46:34.877  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:34.877  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.877  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:34.877  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.877  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.877  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.877  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.877  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.877  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.877  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.877  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.877  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.877  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.877  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:34.877  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:34.877  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.877  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.877  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
,08-25 10:46:34.877  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 10:46:34.877  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:34.877  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.877  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:34.877  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.877  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.877  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.877  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.877  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.877  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.877  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.877  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.877  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.877  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.877  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:34.877  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:34.877  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.877  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.877  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
,08-25 10:46:34.877  6741  6794 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-25 10:46:34.877  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:34.877  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.877  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 10:46:34.877  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.877  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.877  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:34.877  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.877  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.877  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.877  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 10:46:34.877  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.877  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.877  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:34.877  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:34.887  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:34.887  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.887  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.887  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
,08-25 10:46:34.887  6741  6794 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 10:46:34.887  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:34.887  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.887  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:34.887  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.887  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.887  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.887  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.887  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.887  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.887  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.887  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.887  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.887  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.887  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:34.887  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 10:46:34.887  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.887  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:46:34.887  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
,08-25 10:46:34.887  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 10:46:34.897  6741  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 10:46:34.897  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-25 10:46:34.897  6741  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 10:46:34.897  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 10:46:34.897  6741  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 10:46:34.897  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 10:46:34.897  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.907  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:34.907  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.907  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.907  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.907  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.907  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.907  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.907  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.907  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.907  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.907  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:34.907  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 10:46:34.907  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.907  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:46:34.907  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
,08-25 10:46:34.907  6741  6794 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 10:46:34.907  6741  6794 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-25 10:46:34.907  6741  6794 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 10:46:34.907  6741  6794 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-25 10:46:34.907  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 10:46:34.907  6741  6794 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 10:46:34.907  6741  6794 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 10:46:34.907  6741  6794 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 10:46:34.907  6741  6794 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 10:46:34.907  6741  6794 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 10:46:34.907  6741  6794 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 10:46:34.907  6741  6794 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 10:46:34.907  6741  6794 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 10:46:34.907  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 10:46:34.917   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 10:46:34.917  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55,
,08-25 10:46:34.917  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 10:46:34.917  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-25 10:46:34.917  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 10:46:34.917  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 10:46:34.917  6741  6794 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-25 10:46:34.917  6741  6794 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 10:46:34.917  6741  6794 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 10:46:34.917  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 10:46:34.917  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.917  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:34.917  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.917  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.917  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:34.917  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 10:46:34.917  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.917  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.917  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.917  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.917  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.917  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.917  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.917  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-25 10:46:34.917  6741  6876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1299
08-25 10:46:34.917  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:34.917  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.917  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-25 10:46:34.917  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.917  6741  6794 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported,
08-25 10:46:34.917  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-25 10:46:34.917  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.917  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:34.917  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 10:46:34.917  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.917  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.917  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.917  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.917  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
,08-25 10:46:34.917  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.917  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.917  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-25 10:46:34.917  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:34.917  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.917  6741  6875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1299)
08-25 10:46:34.917  6741  6875 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1299),
08-25 10:46:34.917  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:34.917  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.917  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-25 10:46:34.917  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.927  6741  6794 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-25 10:46:34.927  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:34.927  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.927  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-25 10:46:34.927  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.927  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
,08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.927  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.927  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.927  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.927  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.927  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.927  6741  6794 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 10:46:34.927  6741  6794 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 10:46:34.927  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 10:46:34.927  6741  6794 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 10:46:34.927  6741  6794 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 10:46:34.927  6741  6794 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 10:46:34.927  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 10:46:34.927  6741  6794 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 10:46:34.927  6741  6794 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 10:46:34.927  6741  6794 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 10:46:34.927  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 10:46:34.927  6741  6794 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 10:46:34.927  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:34.927  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.927  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-,25 10:46:34.927  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.927  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.927  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.927  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.927  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:34.927  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.927  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.927  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.927  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.927  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.927  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.927  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-25 10:46:34.927  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.927  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.927  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.927  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:34.927  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.927  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.927  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.927  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.927  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.927  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.927  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.927  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.927  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
,08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 10:46:34.927  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.927  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 10:46:34.927  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.927  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.937  6741  6741 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 10:46:34.937  6741  6741 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-25 10:46:34.937  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 10:46:34.937  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.937  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:46:34.937  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:34.937  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:46:34.937  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.937  6741  6741 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 10:46:34.937  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 10:46:34.937  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.937  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.937  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.937  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.937  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.937  6741  6877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 10:46:34.937  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
,08-25 10:46:34.937  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.937  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.937  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.937  6741  6877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 10:46:34.937  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.937  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.937  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:34.937  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.937  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:46:34.937  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.937  6741  6741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 10:46:34.937  6741  6794 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 10:46:34.937  6741  6794 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 10:46:34.937  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 10:46:34.937  6741  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 10:46:34.937  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:34.937  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 10:46:34.937  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:34.937  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.937  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.937  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.937  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.937  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.937  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.937  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.937  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.937  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.937  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:34.937  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.937  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:34.937  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.937  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.937  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
,08-25 10:46:34.947  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:34.947  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.947  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:34.947  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.947  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.947  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.947  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.947  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.947  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.947  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.947  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.947  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.947  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.947  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:34.947  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:34.947  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.947  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.947  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.947  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:34.947  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:34.947  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:34.947  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:34.947  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.947  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.947  6741  6794 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@344dd4d not in the list
08-25 10:46:34.947  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.947  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
08-25 10:46:34.947  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:34.947  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.947  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:34.947  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:34.947  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:34.947  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:34.947  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:34.947  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:34.947  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@164de002 not in the list
,08-25 10:46:34.947  6741  6794 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 10:46:34.947  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-25 10:46:34.947  6741  6794 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 10:46:34.947  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 10:46:34.947  6741  6794 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 10:46:34.947  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-25 10:46:34.947  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-25 10:46:34.947  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 10:46:34.947  6741  6794 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-25 10:46:34.947  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 10:46:34.947  6741  6794 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 10:46:34.947  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 10:46:34.947  6741  6794 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 10:46:34.947  6741  6794 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 10:46:34.947  6741  6794 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 10:46:34.947  6741  6794 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 10:46:34.947  6741  6794 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 10:46:34.957  6741  6794 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 10:46:34.957  6741  6794 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 10:46:34.957  6741  6794 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-25 10:46:34.957  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:46:34.957  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f60f14 added. We now have 2 listener(s)
08-25 10:46:34.957  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:46:34.957  6741  6794 D BluetoothAdapter: enable()
,08-25 10:46:34.957  6741  6794 D BluetoothAdapter: enable(): BT is already enabled..!
,08-25 10:46:34.957  1016  1371 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-25 10:46:34.957  1016  1371 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 10:46:34.957  1016  1371 D SecContentProvider2: mCursor = null
,08-25 10:46:34.957  1016  1371 D WifiService: setWifiEnabled: true pid=6741, uid=10171
,08-25 10:46:34.967  1016  1371 W ActivityManager: Permission Denial: getCurrentUser() from pid=6741, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-25 10:46:34.967  1016  1371 W WifiService: Failed getting userId using ActivityManagerNative
08-25 10:46:34.967  1016  1371 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6741, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 10:46:34.967  1016  1371 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 10:46:34.967  1016  1371 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-25 10:46:34.967  1016  1371 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-25 10:46:34.967  1016  1371 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-25 10:46:34.967  1016  1371 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 10:46:34.967  1016  1371 D SettingsProvider: name = wifi_on
,08-25 10:46:34.967  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 10:46:34.967  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bd4b3bd added. We now have 3 listener(s)
08-25 10:46:34.967  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:46:34.977  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 10:46:34.977  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19824db2 added. We now have 4 listener(s)
,08-25 10:46:34.977  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:46:34.977  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 10:46:34.977  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19d38103 added. We now have 5 listener(s)
08-25 10:46:34.977  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:46:34.987  1016  1485 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-25 10:46:34.987  1016  1485 D WifiService: setWifiEnabled: false pid=6741, uid=10171
08-25 10:46:34.987  1016  1485 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 10:46:34.987  1016  1485 D SecContentProvider2: mCursor = null
08-25 10:46:34.987  1016  1485 D SettingsProvider: name = wifi_on
,08-25 10:46:34.987  1016  1124 E WifiStateMachine: WifiStateMachine: Leaving Connected state,
08-25 10:46:34.987  1397  1397 I wpa_supplicant: reset timer : RESET_TIMER 0
08-25 10:46:34.987  1397  1397 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-25 10:46:34.997  1397  1397 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-25 10:46:34.997  1397  1397 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-25 10:46:34.997  6741  6794 D BluetoothAdapter: disable()
,08-25 10:46:34.997  1016  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 10:46:34.997  1016  1028 D SettingsProvider: name = bluetooth_on
,08-25 10:46:35.007  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:46:35.007  3167  3269 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-25 10:46:35.007  3167  3269 D BluetoothAdapterProperties: Setting state to 13
08-25 10:46:35.007  3167  3269 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 10:46:35.007  3167  3269 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 10:46:35.007  3167  3269 D BluetoothAdapterService: updateAdapterState state is 13
08-25 10:46:35.007  1016  1380 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:35.007  1016  1380 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-25 10:46:35.007  1016  1380 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:35.007  1016  1380 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:35.007  1016  1380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:35.007  3167  3167 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-25 10:46:35.007  3167  3269 D BluetoothAdapterService: Autoconnection is available 
08-25 10:46:35.007  3167  3269 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-25 10:46:35.007  3167  3269 D BluetoothAdapterService: terminating service from this receiver
08-25 10:46:35.017  1016  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-25 10:46:35.017  3167  3167 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@168efdb0, channel: 19, state: LISTENING
08-25 10:46:35.017  3167  3167 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@168efdb0, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@13bd5398, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@124dd429mSocket: android.net.LocalSocket@27e03ae impl:android.net.LocalSocketImpl@3b5ac54f fd:FileDescriptor[74]
08-25 10:46:35.017  3167  3167 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@27e03ae impl:android.net.LocalSocketImpl@3b5ac54f fd:FileDescriptor[74]
,08-25 10:46:35.017  1016  1485 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:35.017  1016  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:35.017  1016  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:35.017  3167  3269 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 10:46:35.017  3167  3269 D BluetoothAdapterProperties: mDiscovering is false
,08-25 10:46:35.017  1016  1124 E WifiNative-wlan0: do suspend true
08-25 10:46:35.017  1016  1029 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled,
08-25 10:46:35.017  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:35.017  6741  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:35.017  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:35.017  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:35.017  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-25 10:46:35.017  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:35.017  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:35.017  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:35.017  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:46:35.017  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:35.017  3167  3269 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 10:46:35.017  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
08-25 10:46:35.017  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 10:46:35.017  6741  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:35.017  6741  6794 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 10:46:35.027  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:35.027  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:35.027  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-25 10:46:35.037  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 10:46:35.037  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:35.037  1176  1176 D BluetoothTile:  getBluetoothState : 13
,08-25 10:46:35.037  1176  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 10:46:35.037  1875  1875 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-25 10:46:35.037  1176  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 10:46:35.037  1176  1728 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 10:46:35.037  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:46:35.047  1016  1134 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 10:46:35.047  1016  1549 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 10:46:35.047  1016  1549 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 10:46:35.047  1016  1483 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 10:46:35.047  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:35.047  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:35.047  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:35.047  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:35.047  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:35.047  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:35.047  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 10:46:35.047  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 10:46:35.047  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:46:35.047  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-25 10:46:35.047  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:35.047  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 10:46:35.047  1016  1549 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:35.047  1016  1549 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:35.047  1016  1549 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:35.057  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:35.057  3167  3273 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 10:46:35.057  3167  3273 D BluetoothAdapterProperties: Scan Mode:20
,08-25 10:46:35.057  3167  3269 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true,
08-25 10:46:35.057  3167  3269 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-25 10:46:35.057  3167  3269 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-25 10:46:35.057  3167  3269 E bt-btif : cmd socket is not created
,08-25 10:46:35.067  3167  5126 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-25 10:46:35.067  3167  3269 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-25 10:46:35.067  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 10:46:35.067  3167  3302 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-25 10:46:35.067  3167  3302 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-25 10:46:35.067  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:35.067  1016  1028 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-25 10:46:35.067  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 10:46:35.067  3167  3167 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@17de44dc, channel: 5, state: LISTENING
08-25 10:46:35.067  3167  3167 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@17de44dc, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16a517f1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@c689e5mSocket: android.net.LocalSocket@1eaaacba impl:android.net.LocalSocketImpl@2128676b fd:FileDescriptor[76]
08-25 10:46:35.067  3167  3167 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1eaaacba impl:android.net.LocalSocketImpl@2128676b fd:FileDescriptor[76]
08-25 10:46:35.067  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:35.067  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:35.067  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 10:46:35.067  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:35.077  1315  1315 D BluetoothPbap: Proxy object disconnected
08-25 10:46:35.077  1315  1315 D PbapServerProfile: Bluetooth service disconnected
,08-25 10:46:35.077  3167  3167 I BtOppRfcommListener: stopping Accept Thread
08-25 10:46:35.077  3167  3167 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1578d2c8, channel: 12, state: LISTENING
08-25 10:46:35.077  3167  3167 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1578d2c8, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19f24cf3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@35adf61mSocket: android.net.LocalSocket@3c6da86 impl:android.net.LocalSocketImpl@3be40f47 fd:FileDescriptor[81]
08-25 10:46:35.077  3167  3167 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3c6da86 impl:android.net.LocalSocketImpl@3be40f47 fd:FileDescriptor[81]
08-25 10:46:35.077  3167  5126 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-25 10:46:35.077  3167  3302 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 10:46:35.077  3167  3302 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:46:35.077  3167  3302 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-25 10:46:35.077  1315  1315 D DockEventReceiver: finishStartingService: stopping service
,08-25 10:46:35.077  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 10:46:35.087  3167  3167 V BluetoothOppManager: cleanUp...
08-25 10:46:35.087  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:35.087  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-25 10:46:35.097  1016  1134 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-25 10:46:35.097  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:35.097  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:35.097  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:35.097  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:35.107  6883  6883 E Zygote  : MountEmulatedStorage(),
08-25 10:46:35.107  6883  6883 E Zygote  : v2
08-25 10:46:35.107  6883  6883 I libpersona: KNOX_SDCARD checking this for 10055
,08-25 10:46:35.107  6883  6883 I libpersona: KNOX_SDCARD not a persona
08-25 10:46:35.107  6883  6883 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:35.107  1016  1134 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6883 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-25 10:46:35.117  6883  6883 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 10:46:35.117  6883  6883 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-25 10:46:35.147  6883  6883 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:35.147  6883  6883 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:35.177  6883  6883 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-25 10:46:35.207  6883  6883 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-25 10:46:35.207  6883  6883 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-25 10:46:35.207  6883  6883 D UserAnalysis: Create SecureDbHelper
,08-25 10:46:35.217  6883  6883 D IntelligenceServiceApplication: onCreate()
,08-25 10:46:35.217  1016  1028 I ActivityManager: Killing 6407:com.samsung.helphub/1000 (adj 15): empty #21
,08-25 10:46:35.217  1016  1382 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-25 10:46:35.227  6883  6883 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-25 10:46:35.227  1016  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:35.227  1016  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:35.227  1016  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:35.227  1016  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:35.237  6901  6901 E Zygote  : MountEmulatedStorage()
,08-25 10:46:35.237  6901  6901 E Zygote  : v2
08-25 10:46:35.237  6901  6901 I libpersona: KNOX_SDCARD checking this for 10105
08-25 10:46:35.237  6901  6901 I libpersona: KNOX_SDCARD not a persona
,08-25 10:46:35.237  1016  1382 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6901 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-25 10:46:35.237  6901  6901 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:35.237  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0,
08-25 10:46:35.247  6901  6901 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 10:46:35.247  6883  6883 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-25 10:46:35.247  6901  6901 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 10:46:35.247  6883  6883 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-25 10:46:35.257  6901  6901 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:35.257  6901  6901 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:35.267  3167  3302 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 10:46:35.267  3167  3345 I bt_userial_mct: exiting userial_read_thread
08-25 10:46:35.267  3167  3345 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 10:46:35.267  3167  3302 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:46:35.267  3167  3302 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 10:46:35.267  3167  3302 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 10:46:35.267  3167  3302 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:46:35.267  3167  3302 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 10:46:35.267  3167  3302 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 10:46:35.267  3167  3302 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:46:35.267  3167  3302 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 10:46:35.267  3167  3302 W bt-btif : ag scb idx 1 not allocated
08-25 10:46:35.267  3167  3302 W bt-btif : ag scb idx 2 not allocated
08-25 10:46:35.267  3167  3302 E bt-btif : BTA AG is already disabled, ignoring ...
,08-25 10:46:35.267  3167  3273 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 10:46:35.267  3167  3304 I bt_vendor: hw_epilog_process
08-25 10:46:35.267  3167  3273 D bt_userial_mct: userial_close
08-25 10:46:35.267  3167  3273 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-25 10:46:35.357   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 10:46:35.357   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 10:46:35.367  6901  6921 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-25 10:46:35.367   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 10:46:35.367   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 10:46:35.367  6901  6921 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-25 10:46:35.437  6741  6741 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 10:46:35.467  3167  3273 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 10:46:35.467  3167  3273 I bt_vendor: bluetooth satus is on
08-25 10:46:35.467  3167  3273 I bt_vendor: bt-vendor : resetting BT status
08-25 10:46:35.467  3167  3273 I bt_vendor: Starting hciattach daemon
08-25 10:46:35.467  3167  3273 I bt_vendor: try to set false
,08-25 10:46:35.467  3167  3273 I bt_vendor: Starting hciattach daemon
08-25 10:46:35.467  3167  3273 I bt_vendor: try to set false
,08-25 10:46:35.467  3167  3273 I bt_vendor: cleanup
,08-25 10:46:35.467  3167  3302 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-25 10:46:35.467  3167  3273 I GKI_LINUX: GKI_exit_task 0 done
,08-25 10:46:35.467  3167  3273 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-25 10:46:35.467  3167  3269 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-25 10:46:35.467  3167  3269 D BtConfig.SecureMode: isSecureModeOn:false
,08-25 10:46:35.467  3167  3269 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-25 10:46:35.467  3167  3269 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-25 10:46:35.467  3167  3269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-25 10:46:35.467  3167  3269 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-25 10:46:35.477  1016  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:35.477  1016  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-25 10:46:35.477  1016  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:35.477  1016  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 10:46:35.477  1016  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:35.477  3167  3269 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-25 10:46:35.477  3167  3269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-25 10:46:35.477  3167  3167 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 10:46:35.477  3167  3167 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 10:46:35.477  3167  3269 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-25 10:46:35.477  3167  3167 D BtGatt.GattService: stop()
08-25 10:46:35.477  3167  3167 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 10:46:35.477  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:35.477  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-25 10:46:35.477  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:35.477  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:35.477  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 10:46:35.477  3167  3269 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-25 10:46:35.477  3167  3269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-25 10:46:35.477  3167  3269 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-25 10:46:35.477  3167  3167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:35.477  1016  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:35.477  1016  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-25 10:46:35.477  1016  1216 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:35.477  1016  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:35.487  1016  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:35.487  3167  3269 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-25 10:46:35.487  3167  3269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-25 10:46:35.487  3167  3269 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-25 10:46:35.487  3167  3167 D HeadsetService: Received stop request...Stopping profile...
,08-25 10:46:35.487  1016  1382 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:35.487  1016  1382 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 10:46:35.487  3167  3167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:35.487  1016  1382 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:35.487  1016  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:35.487  1016  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:35.487  3167  3269 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-25 10:46:35.487  3167  3269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-25 10:46:35.487  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 10:46:35.487  1315  1315 D HeadsetProfile: Bluetooth service disconnected
08-25 10:46:35.487  3167  3269 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-25 10:46:35.497  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:35.497  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-25 10:46:35.497  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:35.497  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:35.497  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 10:46:35.497  3167  3269 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-25 10:46:35.497  3167  3269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 10:46:35.497  3167  3269 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-25 10:46:35.497  1016  1550 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 10:46:35.497  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-25 10:46:35.497  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:35.497  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:35.497  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:35.497  3167  3269 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:35.497  3167  3269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:35.497  3167  3269 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:35.497  1016  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:35.497  1016  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 10:46:35.497  1016  1485 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:35.497  1016  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:35.497  1016  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 10:46:35.497  3167  3269 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-25 10:46:35.497  3167  3269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-25 10:46:35.507  3167  3269 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-25 10:46:35.507  1016  1549 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:35.507  1016  1549 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:35.507  1016  1549 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-25 10:46:35.507  1016  1549 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:35.507  1016  1549 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 10:46:35.507  3167  3269 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-25 10:46:35.507  3167  3269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 10:46:35.507  3167  3269 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-25 10:46:35.507  3167  3269 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 10:46:35.507  3167  3269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-25 10:46:35.507  3167  3269 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 10:46:35.507  3167  3269 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 10:46:35.507  3167  3269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-25 10:46:35.507  3167  3269 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 10:46:35.507  3167  3269 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-25 10:46:35.507  3167  3269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-25 10:46:35.507  3167  3269 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-25 10:46:35.507  3167  3269 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 10:46:35.507  3167  3167 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-25 10:46:35.507  3167  3167 D A2dpService: Received stop request...Stopping profile...
08-25 10:46:35.507  3167  3290 D A2dpStateMachine: Exit Disconnected: -1
,08-25 10:46:35.507  3167  3167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:35.507  1016  1016 D BluetoothA2dp: Proxy object disconnected
08-25 10:46:35.507  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 10:46:35.507  3167  3167 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-25 10:46:35.507  3167  3167 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 10:46:35.507  3167  3167 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-25 10:46:35.517  3167  3167 D HidService: Received stop request...Stopping profile...
08-25 10:46:35.517  3167  3167 D HidService: Stopping Bluetooth HidService
08-25 10:46:35.517  3167  3167 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 10:46:35.517  3167  3167 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-25 10:46:35.517  3167  3167 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 10:46:35.517  3167  3167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:35.517  1315  1315 D BluetoothA2dp: Proxy object disconnected
08-25 10:46:35.517  1315  1315 D A2dpProfile: Bluetooth service disconnected
08-25 10:46:35.517  1315  1315 D BluetoothInputDevice: Proxy object disconnected
,08-25 10:46:35.517  1315  1315 D HidProfile: Bluetooth service disconnected
,08-25 10:46:35.517  3167  3167 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 10:46:35.517  3167  3167 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-25 10:46:35.517  3167  3167 D HealthService: Received stop request...Stopping profile...
,08-25 10:46:35.517  3167  3167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:35.527  3167  3167 D PanService: Received stop request...Stopping profile...
,08-25 10:46:35.527  3167  3167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
08-25 10:46:35.527  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 10:46:35.527  3167  3167 D BluetoothMapService: Received stop request...Stopping profile...
,08-25 10:46:35.527  1315  1315 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 10:46:35.527  3167  3167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:35.527  3167  3167 D SapService: Received stop request...Stopping profile...
,08-25 10:46:35.527  3167  3167 D SapService: Stopping Bluetooth SapService
,08-25 10:46:35.527  3167  3167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
08-25 10:46:35.537  1315  1315 D PanProfile: Bluetooth service disconnected
08-25 10:46:35.537  1315  1315 D BluetoothMap: Proxy object disconnected
08-25 10:46:35.537  1315  1315 D MapProfile: Bluetooth service disconnected
,08-25 10:46:35.537  3167  3167 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-25 10:46:35.537  3167  3167 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 10:46:35.537  3167  3167 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-25 10:46:35.537  3167  3167 D BluetoothA2dp: Proxy object disconnected
08-25 10:46:35.537  3167  3167 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-25 10:46:35.537  3167  3291 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-25 10:46:35.537  1315  1315 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-25 10:46:35.537  3167  3167 I GKI_LINUX: GKI_exit_task 2 done
08-25 10:46:35.537  3167  3167 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 10:46:35.537  1315  1315 D SapProfile: Bluetooth service disconnected
,08-25 10:46:35.537  3167  3167 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-25 10:46:35.537  3167  3167 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:35.537  3167  3167 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:35.537  3167  3167 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,08-25 10:46:35.537  3167  3167 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:35.537  3167  3167 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:35.537  3167  3167 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-25 10:46:35.547  3167  3167 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object,
,08-25 10:46:35.547  3167  3167 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-25 10:46:35.547  3167  3167 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 10:46:35.547  3167  3167 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:35.547  3167  3167 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 10:46:35.547  3167  3167 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-25 10:46:35.547  3167  3167 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-25 10:46:35.547  3167  3167 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 10:46:35.547  3167  3167 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-25 10:46:35.547  3167  3167 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-25 10:46:35.547  3167  3167 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-25 10:46:35.547  3167  3167 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-25 10:46:35.547  3167  3269 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-25 10:46:35.547  3167  3269 D BluetoothAdapterProperties: Setting state to 10
,08-25 10:46:35.547  3167  3269 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 10:46:35.547  3167  3269 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 10:46:35.547  3167  3269 D BluetoothAdapterService: updateAdapterState state is 10
,08-25 10:46:35.547  3167  3269 D BluetoothAdapterService: Autoconnection is available 
08-25 10:46:35.547  3167  3269 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-25 10:46:35.547  3167  3269 I BluetoothAdapterState: Entering OffState
08-25 10:46:35.547  1315  1338 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 10:46:35.557  1315  1325 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 10:46:35.557  1315  1325 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 10:46:35.557  3167  3176 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 10:46:35.557  1423  1459 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 10:46:35.557  1423  1459 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 10:46:35.557  1315  1338 D Bluetoothsap: onBluetoothStateChange: up=false
,08-25 10:46:35.557  1315  1338 D Bluetoothsap: Unbinding service...
,08-25 10:46:35.557  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 10:46:35.557  1016  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 10:46:35.557  1315  1325 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 10:46:35.567  1954  2134 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 10:46:35.567  1954  2134 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 10:46:35.567  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 10:46:35.567  1315  1338 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 10:46:35.567  1176  1590 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 10:46:35.567  1176  1590 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 10:46:35.567  3167  3180 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 10:46:35.567  3167  3180 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 10:46:35.567  6741  6749 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 10:46:35.567  6741  6749 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 10:46:35.567  6741  6749 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-25 10:46:35.567  6741  6749 D BluetoothLeAdvertiser: Exit stop advertising
,08-25 10:46:35.567  6741  6749 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-25 10:46:35.567  6741  6749 D BluetoothLeScanner: Exiting stopAllScan
,08-25 10:46:35.567  1315  1338 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 10:46:35.577  1430  1441 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 10:46:35.577  1430  1441 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-25 10:46:35.577  1443  1652 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 10:46:35.577  1443  1652 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 10:46:35.577  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-25 10:46:35.577  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-25 10:46:35.577  6901  6901 D StrictMode: StrictMode policy violation; ~duration=201 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 10:46:35.577  6901  6901 D StrictMode: StrictMode policy violation; ~duration=200 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 10:46:35.577  6901  6901 D StrictMode: StrictMode policy violation; ~duration=199 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 10:46:35.577  6901  6901 D StrictMode: StrictMode policy violation; ~duration=198 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 10:46:35.577  6901  6901 D StrictMode: StrictMode policy violation; ~duration=195 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.q.k.d(PG:583)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 10:46:35.577  6901  6901 D StrictMode: StrictMode policy violation; ~duration=176 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 10:46:35.577  6901  6901 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 10:46:35.577  6901  6901 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 10:46:35.577  6901  6901 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 10:46:35.587  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:35.587  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
08-25 10:46:35.587  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-25 10:46:35.587  1176  1176 D BluetoothAdapter: 484904329: getState() :  mService = null. Returning STATE_OFF
08-25 10:46:35.597  1176  1728 D BluetoothAdapter: 484904329: getState() :  mService = null. Returning STATE_OFF
08-25 10:46:35.597  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 10:46:35.597  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:35.597  1176  1176 D BluetoothTile:  getBluetoothState : 10
08-25 10:46:35.597  1176  1176 D BluetoothAdapter: 484904329: getState() :  mService = null. Returning STATE_OFF
08-25 10:46:35.597  1875  1875 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-25 10:46:35.597  1954  2135 D BluetoothAdapter: 590593450: getState() :  mService = null. Returning STATE_OFF
08-25 10:46:35.597  1954  2135 D BluetoothAdapter: 590593450: getState() :  mService = null. Returning STATE_OFF
08-25 10:46:35.597  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:35.597  1176  1176 D BluetoothAdapter: 484904329: getState() :  mService = null. Returning STATE_OFF
08-25 10:46:35.597  1016  1134 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-25 10:46:35.597  1016  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-25 10:46:35.597  1176  1728 D BluetoothAdapter: 484904329: getState() :  mService = null. Returning STATE_OFF
08-25 10:46:35.607  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-25 10:46:35.607  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:35.607  1016  1485 I ActivityManager: Killing 6441:com.google.android.apps.plus/u0a117 (adj 15): empty #21
08-25 10:46:35.607  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:35.607  1016  1371 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 10:46:35.607  1016  1371 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-25 10:46:35.607  1016  1371 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:35.607  1016  1371 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:35.607  1016  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-25 10:46:35.617  3167  3273 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-25 10:46:35.617  3167  3167 I GKI_LINUX: GKI_exit_task 1 done
08-25 10:46:35.617  3167  3167 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 10:46:35.617  3167  3167 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 10:46:35.617  1954  1954 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-25 10:46:35.617  3167  3167 I art     : System.exit called, status: 0
08-25 10:46:35.617  3167  3167 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 10:46:35.627  1397  1397 I wpa_supplicant: nl80211: Received scan results (14 BSSes)
08-25 10:46:35.627  1016  1123 D WifiP2pService: InactiveState{ what=147461 }
08-25 10:46:35.627  1016  1123 D WifiP2pService: P2pEnabledState{ what=147461 }
08-25 10:46:35.627  1016  1123 D WifiP2pService: DefaultState{ what=147461 }
08-25 10:46:35.627  1954  1954 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-25 10:46:35.627  1016  1123 D WifiP2pService: InactiveState{ what=143375 }
08-25 10:46:35.627  1016  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
08-25 10:46:35.637   276  1015 D CommandListener: Clearing all IP addresses on wlan0
08-25 10:46:35.637  1954  3010 V NativeCrypto: Read error: ssl=0xb8f4f9e8: I/O error during system call, Connection timed out
08-25 10:46:35.637  1954  3010 V NativeCrypto: SSL shutdown failed: ssl=0xb8f4f9e8: I/O error during system call, Broken pipe
08-25 10:46:35.637  1016  1126 E ConnectivityService: updateNetworkInfo()
08-25 10:46:35.637  1016  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 10:46:35.637  1016  1126 E ConnectivityService: updateNetworkInfo()
08-25 10:46:35.637  1016  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-25 10:46:35.637  1954  3010 E GCM     : Wifi connection closed with errorCode 20
08-25 10:46:35.637  1016  1483 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
08-25 10:46:35.637  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 10:46:35.637  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 10:46:35.637  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.637  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.637  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.637  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.647  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 10:46:35.647  1016  1123 D WifiP2pService: InactiveState{ what=131204 }
08-25 10:46:35.657  1016  1134 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-25 10:46:35.657  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-25 10:46:35.657  1016  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
08-25 10:46:35.657  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:35.657  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:35.657  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 10:46:35.657  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-25 10:46:35.657  1016  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-25 10:46:35.667  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-25 10:46:35.667  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-25 10:46:35.667  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.667  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.667  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.667  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-25 10:46:35.667  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 10:46:35.667  1016  1016 D RttService: SCAN_AVAILABLE : 1
08-25 10:46:35.667  1016  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:46:35.667  1016  1149 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:46:35.667  1016  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost,
,08-25 10:46:35.667  1315  1315 D DockEventReceiver: finishStartingService: stopping service
08-25 10:46:35.667  6901  6922 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-25 10:46:35.677  1954  6867 D Uploader: Network request failed class javax.net.ssl.SSLException(Read error: ssl=0xb91363c0: I/O error during system call, Connection timed out)
,08-25 10:46:35.677  1016  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-24ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 10:46:35.677  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:46:35.677  1016  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-24ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:46:35.677  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-25 10:46:35.677  1016  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,08-25 10:46:35.677  1016  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:46:35.677  1016  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-25 10:46:35.687  1016  1729 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-25 10:46:35.687  1016  1729 I qtaguid : Tagging socket 342 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1016, getuid(): 1000
,08-25 10:46:35.687  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 10:46:35.697  1016  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-25 10:46:35.697  1016  1729 I qtaguid : Untagging socket 342
08-25 10:46:35.697  1016  1729 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
08-25 10:46:35.697  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-25 10:46:35.697  1016  1481 I ActivityManager: Process com.android.bluetooth (pid 3167)(adj 0) has died(35,706)
,08-25 10:46:35.707  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
08-25 10:46:35.707  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
08-25 10:46:35.707  1016  1380 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-25 10:46:35.717  1016  1380 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:35.717  1016  1380 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:35.717  1016  1380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-25 10:46:35.717  1016  1123 D WifiP2pService: P2pDisablingState,
08-25 10:46:35.717  1016  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
08-25 10:46:35.717  1016  1123 D WifiP2pService: p2p socket connection lost
,08-25 10:46:35.717  1016  1123 D WifiP2pService: P2pDisabledState
,08-25 10:46:35.717  1016  1124 E WifiNative-wlan0: do suspend true
08-25 10:46:35.717  1016  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-25 10:46:35.717  1016  1123 D WifiP2pService: DefaultState{ what=143375 }
,08-25 10:46:35.727  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 10:46:35.727  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 10:46:35.727  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.727  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.727  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.727  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:35.727  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
08-25 10:46:35.727  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:35.727  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:35.727  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:35.727  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:35.727  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 10:46:35.727  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-25 10:46:35.727  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-25 10:46:35.727  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-25 10:46:35.727  1016  1046 D WifiDisplayController: disconnect
08-25 10:46:35.727  1016  1046 D WifiDisplayController: updateConnection
08-25 10:46:35.727  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 10:46:35.727  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 10:46:35.727  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-25 10:46:35.727  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 10:46:35.727  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-25 10:46:35.727  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 10:46:35.727   276  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,08-25 10:46:35.727   276  1015 D CommandListener: Clearing all IP addresses on wlan0
08-25 10:46:35.727   276  1011 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-25 10:46:35.727  1016  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-25 10:46:35.727  1016  1126 V NetworkStats: updateIfacesLocked()
08-25 10:46:35.727  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:35.727  1016  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-25 10:46:35.737  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 10:46:35.737  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 10:46:35.737  1016  1126 V NetworkStats: performPollLocked() took 5ms,
08-25 10:46:35.737  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:35.737  1016  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-25 10:46:35.737  1016  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-25 10:46:35.737  6947  6947 E Zygote  : MountEmulatedStorage()
,08-25 10:46:35.737  6947  6947 E Zygote  : v2
08-25 10:46:35.737  6947  6947 I libpersona: KNOX_SDCARD checking this for 1002
08-25 10:46:35.737  6947  6947 I libpersona: KNOX_SDCARD not a persona
,08-25 10:46:35.747  6947  6947 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:35.747  6947  6947 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 10:46:35.747  6947  6947 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 10:46:35.747  1016  1028 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6947 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-25 10:46:35.747  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-25 10:46:35.757  1397  1397 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED,
08-25 10:46:35.757  1176  1711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 10:46:35.757  1016  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-25 10:46:35.757  1016  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:46:35.757  1016  1126 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:46:35.757  1016  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-25 10:46:35.757  1016  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-25 10:46:35.757  4811  6803 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 10:46:35.757  1016  1126 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-25 10:46:35.757  1443  1443 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-25 10:46:35.757  1443  1443 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-25 10:46:35.757  1016  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false,
08-25 10:46:35.757  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 10:46:35.757  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 10:46:35.757  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.757  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.757  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:35.757  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.757  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:35.757  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:35.767  1016  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-25 10:46:35.767  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-25 10:46:35.767  1016  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
08-25 10:46:35.767  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 10:46:35.767  1016  1124 D SecContentProvider2: mCursor = null
,08-25 10:46:35.767  1016  1485 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
08-25 10:46:35.777  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 10:46:35.777  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 10:46:35.777  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-25 10:46:35.777  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.777  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 10:46:35.777  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.777  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.777  1176  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 10:46:35.777  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.777  1176  1176 D HotspotTile: onReceive : 0, 0
08-25 10:46:35.777  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 10:46:35.777  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-25 10:46:35.777  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 10:46:35.777  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-25 10:46:35.777  1016  1129 D Tethering: MasterInitialState.processMessage what=3
,08-25 10:46:35.777  1016  1121 V NetworkStats: updateIfacesLocked()
08-25 10:46:35.777  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:35.777  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-25 10:46:35.787  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 10:46:35.787  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 10:46:35.787  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:35.787  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:35.787  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:35.787  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:35.787  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:35.787  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:35.787  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:35.787  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:35.787  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:46:35.787  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:35.787  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:35.787  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:35.787  1016  1121 V NetworkStats: performPollLocked() took 4ms
08-25 10:46:35.787  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:35.787  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:35.787  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:35.787  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:35.787  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:35.787  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:35.787  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:35.787  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:35.787  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 10:46:35.787  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:35.787  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:35.787  1016  1126 D ConnectivityService: nai.networkMonitor.doQuit()
08-25 10:46:35.787  1016  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-25 10:46:35.787  1016  1126 E ConnectivityService: updateNetworkInfo()
08-25 10:46:35.787  1016  1126 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 10:46:35.787  1016  1126 E ConnectivityService: updateNetworkInfo()
08-25 10:46:35.787  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
08-25 10:46:35.787  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-25 10:46:35.787  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-25 10:46:35.787  1176  1176 D StatusBar.NetworkController: updateDataNetType()
08-25 10:46:35.787  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-25 10:46:35.787  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-25 10:46:35.787  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:35.787  1016  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-25 10:46:35.787  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:35.787  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:35.787  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:35.787  1016  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-25 10:46:35.797  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:35.797  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:35.797  6947  6947 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 10:46:35.797  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-25 10:46:35.797  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-25 10:46:35.797  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-25 10:46:35.797  6947  6947 D ActivityThread: Added TimaKeyStore provider
08-25 10:46:35.797  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 10:46:35.797  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 10:46:35.797  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.797  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.797  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:35.797  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:35.817  6947  6947 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-25 10:46:35.817  6947  6947 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 10:46:35.847  6947  6947 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-25 10:46:35.857  1397  1397 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 10:46:35.857   289   289 E SMD     : DCD OFF,
,08-25 10:46:35.877  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 10:46:35.877  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 10:46:35.877  6947  6947 D BtSettings.ProfileConfig: Adding GattService
,08-25 10:46:35.877  6947  6947 D BtSettings.ProfileConfig: Adding HeadsetService
08-25 10:46:35.877  6947  6947 D BtSettings.ProfileConfig: Adding A2dpService
08-25 10:46:35.877  6947  6947 D BtSettings.ProfileConfig: Adding HidService
08-25 10:46:35.877  6947  6947 D BtSettings.ProfileConfig: Adding HealthService
,08-25 10:46:35.877  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 10:46:35.877  6947  6947 D BtSettings.ProfileConfig: Adding PanService
08-25 10:46:35.877  6947  6947 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-25 10:46:35.877  6947  6947 D BtSettings.ProfileConfig: Adding SapService
08-25 10:46:35.877  6947  6947 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-25 10:46:35.877  6947  6947 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-25 10:46:35.877  6947  6947 D BtSettings.ProfileConfig: Adding SapClientService
08-25 10:46:35.877  6947  6947 D BtSettings.ProfileConfig: Adding HidDevService
08-25 10:46:35.877  6947  6947 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-25 10:46:35.877  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 10:46:35.877  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 10:46:35.877  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 10:46:35.877  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 10:46:35.877  1016  1382 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-25 10:46:35.877  1016  1382 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:35.877  1016  1382 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:35.877  1016  1382 D SettingsProvider: selectionArgs: false
08-25 10:46:35.877  1016  1382 D SettingsProvider: selectionArgs: 1002
08-25 10:46:35.887  1016  1382 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:35.887  1016  1382 D SettingsProvider: ret = -1
,08-25 10:46:35.887  1016  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-25 10:46:35.887  1016  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:35.887  1016  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:35.887  1016  1481 D SettingsProvider: selectionArgs: false
08-25 10:46:35.887  1016  1481 D SettingsProvider: selectionArgs: 1002
08-25 10:46:35.887  1016  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:35.887  1016  1481 D SettingsProvider: ret = -1
08-25 10:46:35.887  1016  1371 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-25 10:46:35.887  1016  1371 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:35.887  1016  1371 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 10:46:35.887  1016  1371 D SettingsProvider: selectionArgs: false
08-25 10:46:35.887  1016  1371 D SettingsProvider: selectionArgs: 1002
08-25 10:46:35.887  1016  1371 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:35.887  1016  1371 D SettingsProvider: ret = -1
08-25 10:46:35.887  1016  1371 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-25 10:46:35.887  1016  1371 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:35.887  1016  1371 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:35.887  1016  1371 D SettingsProvider: selectionArgs: false
08-25 10:46:35.887  1016  1371 D SettingsProvider: selectionArgs: 1002
08-25 10:46:35.887  1016  1371 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:35.887  1016  1371 D SettingsProvider: ret = -1
,08-25 10:46:35.887  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 10:46:35.887  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 10:46:35.887  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-25 10:46:35.887  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:35.887  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:35.887  1016  1028 D SettingsProvider: selectionArgs: false
08-25 10:46:35.887  1016  1028 D SettingsProvider: selectionArgs: 1002
08-25 10:46:35.887  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
,08-25 10:46:35.887  1016  1028 D SettingsProvider: ret = -1
08-25 10:46:35.887  1016  1550 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-25 10:46:35.887  1016  1550 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:35.887  1016  1550 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 10:46:35.887  1016  1550 D SettingsProvider: selectionArgs: false
08-25 10:46:35.887  1016  1550 D SettingsProvider: selectionArgs: 1002
08-25 10:46:35.887  1016  1550 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:35.887  1016  1550 D SettingsProvider: ret = -1
,08-25 10:46:35.887  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 10:46:35.887  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 10:46:35.887  1016  1216 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:35.887  1016  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:35.887  1016  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:35.887  1016  1216 D SettingsProvider: selectionArgs: false
08-25 10:46:35.887  1016  1216 D SettingsProvider: selectionArgs: 1002
08-25 10:46:35.887  1016  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:35.887  1016  1216 D SettingsProvider: ret = -1
08-25 10:46:35.887  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-25 10:46:35.887  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 10:46:35.887  1016  1382 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-25 10:46:35.887  1016  1382 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:35.887  1016  1382 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 10:46:35.887  1016  1382 D SettingsProvider: selectionArgs: false
08-25 10:46:35.887  1016  1382 D SettingsProvider: selectionArgs: 1002
08-25 10:46:35.887  1016  1382 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:35.887  1016  1382 D SettingsProvider: ret = -1
08-25 10:46:35.887  1016  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-25 10:46:35.887  1016  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-25 10:46:35.887  1016  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:35.887  1016  1481 D SettingsProvider: selectionArgs: false
08-25 10:46:35.887  1016  1481 D SettingsProvider: selectionArgs: 1002,
08-25 10:46:35.887  1016  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:35.887  1016  1481 D SettingsProvider: ret = -1
08-25 10:46:35.887  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 10:46:35.887  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 10:46:35.897  1016  1483 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService,
08-25 10:46:35.897  1016  1483 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:35.897  1016  1483 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:35.897  1016  1483 D SettingsProvider: selectionArgs: false
08-25 10:46:35.897  1016  1483 D SettingsProvider: selectionArgs: 1002
,08-25 10:46:35.897  1016  1483 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:35.897  1016  1483 D SettingsProvider: ret = -1
08-25 10:46:35.897  1016  1134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-25 10:46:35.897  1016  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
,08-25 10:46:35.897  1016  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:35.897  1016  1134 D SettingsProvider: selectionArgs: false
08-25 10:46:35.897  1016  1134 D SettingsProvider: selectionArgs: 1002,
08-25 10:46:35.897  1016  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:35.897  1016  1134 D SettingsProvider: ret = -1
,08-25 10:46:35.897  1016  1550 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-25 10:46:35.897  1016  1550 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:35.897  1016  1550 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:35.897  1016  1550 D SettingsProvider: selectionArgs: false
08-25 10:46:35.897  1016  1550 D SettingsProvider: selectionArgs: 1002
,08-25 10:46:35.897  1016  1550 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:35.897  1016  1550 D SettingsProvider: ret = -1
08-25 10:46:35.897  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 10:46:35.897  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 10:46:35.897  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 10:46:35.897  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-25 10:46:35.897  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 10:46:35.897  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 10:46:35.907  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 10:46:35.907  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 10:46:35.907  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 10:46:35.907  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 10:46:35.907  1016  1216 I ActivityManager: Killing 6479:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-25 10:46:35.907  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 10:46:35.907  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 10:46:35.907  1954  1954 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-25 10:46:35.907  1016  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 10:46:35.907  1016  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-25 10:46:35.917  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-25 10:46:35.917  1016  1485 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:35.917  1016  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:35.917  1016  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:35.917  1443  1443 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-25 10:46:35.917   316   316 I ServiceManager: Waiting for service AtCmdFwd...
08-25 10:46:35.917  1443  1443 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-25 10:46:35.937  1954  6977 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-25 10:46:35.967  1397  1397 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-25 10:46:35.967  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-25 10:46:35.967  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 10:46:35.967  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-25 10:46:35.987  1397  1397 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-25 10:46:35.987  1397  1397 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-25 10:46:35.987  1397  1397 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-25 10:46:35.987  1397  1397 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-25 10:46:35.987  1397  1397 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-25 10:46:35.987  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 10:46:35.987  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 10:46:35.987  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 10:46:35.997  1016  1129 D Tethering: InitialState.processMessage what=4
,08-25 10:46:35.997  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-25 10:46:35.997  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 10:46:35.997  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 10:46:36.047   269   269 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb71fa7c8
08-25 10:46:36.047   269   269 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-25 10:46:36.047   269   269 I rmt_storage: wakelock acquired: 1, error no: 42
08-25 10:46:36.047   269   359 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1222662856)
,08-25 10:46:36.077  1016  1371 I art     : Explicit concurrent mark sweep GC freed 44990(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 24MB/36MB, paused 16.911ms total 167.098ms
,08-25 10:46:36.087  1016  1129 E Tethering: No numeric data
08-25 10:46:36.087  1016  1380 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-25 10:46:36.087  1954  1954 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 10:46:36.087  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 10:46:36.087  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 10:46:36.087  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 10:46:36.097   269   359 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504,
08-25 10:46:36.097   269   359 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,08-25 10:46:36.097   269   359 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1222662856) wakelock released: 1, error no: 0
08-25 10:46:36.097   269   359 I rmt_storage: 
08-25 10:46:36.097  1016  1380 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:36.097  1016  1380 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:36.097  1016  1380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-25 10:46:36.097   269   269 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb71fa7c8
08-25 10:46:36.097  1016  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 10:46:36.097  1016  1129 D Tethering: clearTetheredNotification()
,08-25 10:46:36.107  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:36.107  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-25 10:46:36.107  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 10:46:36.107  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 10:46:36.107  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 10:46:36.107  1176  1176 D HotspotTile: updateTetherState():false, false
08-25 10:46:36.107  1016  1121 V NetworkStats: performPollLocked() took 6ms
,08-25 10:46:36.117  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:36.117  1016  1549 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 10:46:36.117  1016  1549 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 10:46:36.117  1016  1549 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:36.117  1016  1549 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 10:46:36.117  1016  1549 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 10:46:36.127  2201  2201 I Hs20UtilService: Starting #8
,08-25 10:46:36.127  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:36.127  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:36.127  2201  2218 I Hs20UtilService: Message received 5007
,08-25 10:46:36.127  1016  1371 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:36.127  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 10:46:36.127  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-25 10:46:36.127  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 10:46:36.127  1016  1371 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:36.127  1016  1371 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:36.127  1016  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:36.137  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 10:46:36.137  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 10:46:36.137  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 10:46:36.137  1315  2242 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 10:46:36.137  1016  1549 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:36.137  1016  1549 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:36.137  1016  1549 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-25 10:46:36.137  1016  1549 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-25 10:46:36.137  1954  6977 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-25 10:46:36.137  1016  1549 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.137  1016  1549 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.137  1016  1549 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.137  1016  1549 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:36.157  6980  6980 E Zygote  : MountEmulatedStorage(),
,08-25 10:46:36.157  6980  6980 E Zygote  : v2
08-25 10:46:36.157  6980  6980 I libpersona: KNOX_SDCARD checking this for 10102
08-25 10:46:36.157  6980  6980 I libpersona: KNOX_SDCARD not a persona
08-25 10:46:36.157  1016  1549 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6980 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
08-25 10:46:36.157  6980  6980 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:36.157  6980  6980 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 10:46:36.157  6980  6980 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-25 10:46:36.167  1397  1397 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 10:46:36.177  6980  6980 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:36.177  6980  6980 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:36.187  1954  2137 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-25 10:46:36.187  1954  2137 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-25 10:46:36.197  6980  6980 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 10:46:36.257  1397  1397 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 10:46:36.257  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 10:46:36.257  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 10:46:36.257  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 10:46:36.277  1016  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:36.287  1016  1016 I ApplicationPolicy: updateDataUsageMap
,08-25 10:46:36.297  1016  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:36.307  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 10:46:36.307  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:36.307  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:36.307  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:36.307  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:36.307  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:36.307  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:36.307  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:36.307  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:36.307  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 10:46:36.307  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:36.307  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:36.307  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:36.307  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:36.307  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:36.307  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:36.307  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:36.307  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:36.357  1016  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-25 10:46:36.357  1016  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-25 10:46:36.367  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 10:46:36.367  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 10:46:36.367  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:36.367  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:36.367  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:36.367  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:36.367  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 10:46:36.367  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-25 10:46:36.367  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 10:46:36.367  1176  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-25 10:46:36.367  1176  1176 D HotspotTile: onReceive : 1, 0
,08-25 10:46:36.367  1954  2135 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 10:46:36.377  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:36.377  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:36.377  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 10:46:36.417  6980  7000 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-25 10:46:36.417  6980  7000 I Babel_SMS: MmsConfig.loadMmsSettings
,08-25 10:46:36.417  6980  7000 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-25 10:46:36.427  6980  7000 I Babel_SMS: MmsConfig.loadFromDatabase
,08-25 10:46:36.437  6980  7000 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-25 10:46:36.437  6980  7000 I Babel_SMS: MmsConfig.loadFromResources
,08-25 10:46:36.437  6980  7000 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-25 10:46:36.447  6980  7000 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-25 10:46:36.477  1016  1380 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-25 10:46:36.477  1016  1380 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-25 10:46:36.477  1016  1380 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:36.477  1016  1380 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:36.477  1016  1380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-25 10:46:36.497  6980  6980 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 10:46:36.497  6980  6980 I Babel_Crash: startup - clean
,08-25 10:46:36.537  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 10:46:36.537  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 10:46:36.537  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 10:46:36.537  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 10:46:36.537  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 10:46:36.537  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 10:46:36.537  1315  2242 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-25 10:46:36.537  1016  1371 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-25 10:46:36.537  1016  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.537  1016  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.537  1016  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.537  1016  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:36.547  6980  6980 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 10:46:36.547  7003  7003 I libpersona: KNOX_SDCARD checking this for 10064
08-25 10:46:36.547  6980  6980 W AudioCapabilities: Unsupported mime audio/evrc
08-25 10:46:36.547  7003  7003 I libpersona: KNOX_SDCARD not a persona
08-25 10:46:36.547  6980  6980 W AudioCapabilities: Unsupported mime audio/qcelp
08-25 10:46:36.547  7003  7003 E Zygote  : MountEmulatedStorage()
08-25 10:46:36.547  7003  7003 E Zygote  : v2
08-25 10:46:36.547  7003  7003 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:36.557  7003  7003 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 10:46:36.557  1016  1371 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7003 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 10:46:36.557  7003  7003 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 10:46:36.557  6980  6980 W AudioCapabilities: Unsupported mime audio/mpeg-L1
08-25 10:46:36.557  6980  6980 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-25 10:46:36.567  6980  6980 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-25 10:46:36.567  6980  6980 W AudioCapabilities: Unsupported mime audio/x-ima
,08-25 10:46:36.567  6980  6980 W AudioCapabilities: Unsupported mime audio/qcelp
,08-25 10:46:36.567  6980  6980 W AudioCapabilities: Unsupported mime audio/evrc
,08-25 10:46:36.577  6980  6980 W VideoCapabilities: Unsupported mime video/wvc1
,08-25 10:46:36.577  6980  6980 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-25 10:46:36.587  7003  7003 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:36.587  7003  7003 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:36.597  7003  7003 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-25 10:46:36.597  6980  6980 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-25 10:46:36.607  6980  6980 W VideoCapabilities: Unsupported mime video/wvc1
,08-25 10:46:36.607  6980  6980 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-25 10:46:36.607  6980  6980 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-25 10:46:36.607  6980  6980 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-25 10:46:36.617  6980  6980 W VideoCapabilities: Unsupported mime video/mp43
,08-25 10:46:36.617  6980  6980 W VideoCapabilities: Unsupported mime video/sorenson
,08-25 10:46:36.627  6980  6980 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-25 10:46:36.627  7003  7003 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 10:46:36.627  7003  7003 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-25 10:46:36.637  6980  6980 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-25 10:46:36.657  7003  7003 D FileShare-Client: Outbound.stopDelayTimer - 
,08-25 10:46:36.667  1016  1549 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-25 10:46:36.667  6980  6980 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 10:46:36.667  1016  1549 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:36.667  1016  1549 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.667  6980  6980 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-25 10:46:36.667  1016  1549 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:36.667  1016  1549 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:36.667  6980  6980 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 10:46:36.667  6980  6980 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 10:46:36.677  7018  7018 E Zygote  : MountEmulatedStorage()
08-25 10:46:36.677  1016  1549 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7018 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 10:46:36.677  7018  7018 E Zygote  : v2
08-25 10:46:36.677  7018  7018 I libpersona: KNOX_SDCARD checking this for 10065
08-25 10:46:36.677  7018  7018 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 10:46:36.677  7018  7018 I libpersona: KNOX_SDCARD not a persona
08-25 10:46:36.687  7018  7018 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 10:46:36.687  1016  1481 I ActivityManager: Killing 6519:com.samsung.android.sm/1000 (adj 15): empty #21
,08-25 10:46:36.687  7018  7018 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 10:46:36.687  6980  6980 I vclib   : onServiceConnected
,08-25 10:46:36.697  7018  7018 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:36.697  7018  7018 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:36.717  7018  7018 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 10:46:36.727  1016  1483 I ActivityManager: Killing 6471:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-25 10:46:36.727  1016  1382 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 10:46:36.727  1016  1382 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 10:46:36.727  1016  1382 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:36.727  1016  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:36.727  1016  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 10:46:36.737  2201  2201 I Hs20UtilService: Starting #9
,08-25 10:46:36.737  2201  2218 I Hs20UtilService: Message received 5007
,08-25 10:46:36.737  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 10:46:36.737  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 10:46:36.737  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 10:46:36.737  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 10:46:36.737  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 10:46:36.737  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 10:46:36.737  1315  2242 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 10:46:36.747  1016  1216 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 10:46:36.747  1016  1216 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 10:46:36.747  1016  1216 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:36.747  1016  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:36.747  1016  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 10:46:36.747  2201  2201 I Hs20UtilService: Starting #10
,08-25 10:46:36.747  2201  2218 I Hs20UtilService: Message received 5011
,08-25 10:46:36.747  6540  6540 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 10:46:36.747  6540  6540 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 10:46:36.747  6540  6540 D SecurityLogAgent: StateMachine : Current State = 1
,08-25 10:46:36.747  6540  6540 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 10:46:36.757  1016  1382 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:36.757  1016  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:36.757  1016  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 10:46:36.767  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:36.767  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:36.767  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 10:46:36.767  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:36.767  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:36.767  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 10:46:36.767  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:36.767  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:36.767  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 10:46:36.777  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:36.777  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:36.777  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 10:46:36.777  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:36.777  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:36.777  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 10:46:36.777  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:36.777  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:36.777  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 10:46:36.777  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:36.777  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:36.777  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 10:46:36.787  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:36.787  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:36.787  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 10:46:36.787  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:36.787  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:36.787  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 10:46:36.787  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:36.787  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:36.787  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 10:46:36.787  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:36.787  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:36.787  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 10:46:36.797  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:36.797  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:36.797  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 10:46:36.797  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:36.797  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:36.797  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 10:46:36.797  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:36.797  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:36.797  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-25 10:46:36.797  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-25 10:46:36.807  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.807  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.807  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.807  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:36.817  1016  1016 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7034 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-25 10:46:36.817  7034  7034 E Zygote  : MountEmulatedStorage(),
08-25 10:46:36.817  7034  7034 I libpersona: KNOX_SDCARD checking this for 1000
08-25 10:46:36.817  7034  7034 E Zygote  : v2
08-25 10:46:36.817  7034  7034 I libpersona: KNOX_SDCARD not a persona
08-25 10:46:36.817  7034  7034 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:36.817  7034  7034 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 10:46:36.827  7034  7034 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-25 10:46:36.847  7034  7034 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:36.847  7034  7034 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:36.867  1016  1043 D Tethering: interfaceRemoved wlan0
,08-25 10:46:36.867  1016  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-25 10:46:36.867  7034  7034 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-25 10:46:36.867  7034  7034 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-25 10:46:36.867  7034  7034 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-25 10:46:36.887  7034  7034 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-25 10:46:36.887  7034  7034 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-25 10:46:36.887  7034  7034 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-25 10:46:36.887  7034  7034 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:36.887  1016  1550 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-25 10:46:36.887  1016  1550 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-25 10:46:36.887  7034  7049 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-25 10:46:36.897  1016  1550 I ActivityManager: Killing 6573:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-25 10:46:36.897  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-25 10:46:36.897  1735  1735 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-25 10:46:36.897  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:36.897  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.897  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:36.897  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:36.917   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
08-25 10:46:36.917  7051  7051 E Zygote  : MountEmulatedStorage()
,08-25 10:46:36.917  7051  7051 E Zygote  : v2
08-25 10:46:36.917  7051  7051 I libpersona: KNOX_SDCARD checking this for 10121
08-25 10:46:36.917  7051  7051 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 10:46:36.917  7051  7051 I libpersona: KNOX_SDCARD not a persona,
08-25 10:46:36.917  1016  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7051 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-25 10:46:36.917  1016  1550 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-25 10:46:36.917  7051  7051 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 10:46:36.917  1016  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.917  7051  7051 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 10:46:36.917  1016  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.917  1016  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.917  1016  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-25 10:46:36.937  7061  7061 E Zygote  : MountEmulatedStorage()
08-25 10:46:36.937  7061  7061 I libpersona: KNOX_SDCARD checking this for 10031
08-25 10:46:36.937  7061  7061 E Zygote  : v2
08-25 10:46:36.937  7061  7061 I libpersona: KNOX_SDCARD not a persona
,08-25 10:46:36.937  7061  7061 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:36.947  7061  7061 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 10:46:36.947  7061  7061 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 10:46:36.947  1016  1550 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7061 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-25 10:46:36.957  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-25 10:46:36.957  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.957  7051  7051 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:36.957  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.957  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.957  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:36.957  7051  7051 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:36.967  2607  5028 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,08-25 10:46:36.967  7061  7061 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:36.967  7061  7061 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:36.987  7082  7082 E Zygote  : MountEmulatedStorage()
,08-25 10:46:36.987  1016  1016 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7082 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 10:46:36.987  7082  7082 E Zygote  : v2
08-25 10:46:36.987  7082  7082 I libpersona: KNOX_SDCARD checking this for 10001
08-25 10:46:36.987  7082  7082 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 10:46:36.987  7082  7082 I libpersona: KNOX_SDCARD not a persona
08-25 10:46:36.997  1735  1735 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-25 10:46:36.997  1735  1735 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-25 10:46:36.997  7082  7082 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 10:46:36.997  1735  1735 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-25 10:46:36.997  1735  1735 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
08-25 10:46:36.997  7082  7082 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 10:46:37.007  1016  1043 D Tethering: interfaceRemoved p2p0
,08-25 10:46:37.007  1016  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-25 10:46:37.017  7082  7082 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:37.027  7082  7082 D ActivityThread: Added TimaKeyStore provider
08-25 10:46:37.027  1735  1735 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-25 10:46:37.027  1735  1735 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-25 10:46:37.027  1016  1382 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-25 10:46:37.027  7051  7051 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 10:46:37.027  1016  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.027  1016  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.027  1016  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.027  1016  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.027  7051  7051 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-25 10:46:37.027  7051  7051 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 10:46:37.047  7051  7051 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
,08-25 10:46:37.047  7097  7097 E Zygote  : MountEmulatedStorage()
08-25 10:46:37.047  1016  1382 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7097 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 10:46:37.047  7097  7097 E Zygote  : v2
08-25 10:46:37.047  7097  7097 I libpersona: KNOX_SDCARD checking this for 10077
,08-25 10:46:37.047  7097  7097 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 10:46:37.047  7097  7097 I libpersona: KNOX_SDCARD not a persona
,08-25 10:46:37.047  7097  7097 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 10:46:37.057  7097  7097 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-25 10:46:37.067  7051  7051 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-25 10:46:37.067  7061  7061 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-25 10:46:37.067  7051  7051 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-25 10:46:37.067  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-25 10:46:37.067   305   305 I art     : Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 22.269ms
,08-25 10:46:37.067  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.067  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.067  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.067  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:37.077  7097  7097 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 10:46:37.077  7097  7097 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:37.087   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 17.346ms
,08-25 10:46:37.107   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 650us total 17.974ms
,08-25 10:46:37.127  7114  7114 E Zygote  : MountEmulatedStorage()
08-25 10:46:37.127  7114  7114 I libpersona: KNOX_SDCARD checking this for 10141
08-25 10:46:37.127  7114  7114 E Zygote  : v2
08-25 10:46:37.127  7114  7114 I libpersona: KNOX_SDCARD not a persona
,08-25 10:46:37.127  7114  7114 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:37.127  1016  1029 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7114 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,08-25 10:46:37.127  1016  1029 I ActivityManager: Killing 6589:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-25 10:46:37.127  7114  7114 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 10:46:37.127  7114  7114 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 10:46:37.137  1016  1029 I ActivityManager: Killing 6603:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-25 10:46:37.147  7114  7114 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:37.157  7114  7114 D ActivityThread: Added TimaKeyStore provider
08-25 10:46:37.157  1016  1485 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
08-25 10:46:37.157  1016  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.157  1016  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.157  1016  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.157  1016  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:37.157  2763  7129 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-25 10:46:37.157  2763  7129 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-25 10:46:37.157  2763  7129 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-25 10:46:37.157  2763  7129 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-25 10:46:37.167  2763  7129 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-25 10:46:37.177  7130  7130 E Zygote  : MountEmulatedStorage(),
08-25 10:46:37.177  7130  7130 E Zygote  : v2
08-25 10:46:37.177  1016  1485 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7130 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-25 10:46:37.177  7130  7130 I libpersona: KNOX_SDCARD checking this for 1000
08-25 10:46:37.177  7130  7130 I libpersona: KNOX_SDCARD not a persona
08-25 10:46:37.177  1016  1485 I ActivityManager: Killing 6621:com.qualcomm.timeservice/1000 (adj 15): empty #21
08-25 10:46:37.177  7130  7130 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-25 10:46:37.177  1016  1485 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
08-25 10:46:37.177  1016  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.177  1016  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.177  1016  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.177  1016  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.177  7130  7130 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 10:46:37.177  7130  7130 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 10:46:37.197  7143  7143 E Zygote  : MountEmulatedStorage()
08-25 10:46:37.197  7143  7143 E Zygote  : v2
08-25 10:46:37.197  7143  7143 I libpersona: KNOX_SDCARD checking this for 10032
08-25 10:46:37.197  7143  7143 I libpersona: KNOX_SDCARD not a persona
,08-25 10:46:37.197  7143  7143 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 10:46:37.197  1016  1485 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7143 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 10:46:37.197  7143  7143 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-25 10:46:37.207  7143  7143 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-25 10:46:37.207  7130  7130 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:37.207  7130  7130 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:37.227  7114  7114 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-25 10:46:37.227  7114  7114 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 10:46:37.227  7114  7114 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-25 10:46:37.227  7114  7114 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-25 10:46:37.277  7143  7143 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 10:46:37.277  7143  7143 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:37.297  7130  7130 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-25 10:46:37.317  1016  1485 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 10:46:37.317  1016  1485 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4315, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-25 10:46:37.317  1016  1485 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-25 10:46:37.317  1016  1485 D BatteryService: stay LED for fully charged
,08-25 10:46:37.317  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-25 10:46:37.317  1016  1016 I MotionRecognitionService: Plugged
,08-25 10:46:37.317  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 10:46:37.327  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-25 10:46:37.327  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-25 10:46:37.327  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-25 10:46:37.327  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-25 10:46:37.337  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 10:46:37.337  7143  7162 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-25 10:46:37.337  7143  7162 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-25 10:46:37.347  7143  7162 D SPPClientService: PushLog.txt file is not deleted.
,08-25 10:46:37.347  7143  7162 D SPPClientService: PushLog.txt file is not deleted.
,08-25 10:46:37.347  7143  7162 D SPPClientService: ============PushLog. stop!
,08-25 10:46:37.357  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 10:46:37.357  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 10:46:37.387  7143  7143 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-25 10:46:37.387  1016  1382 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-25 10:46:37.387  1016  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:37.387  1016  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.387  1016  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.387  1016  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:37.407  1016  1382 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7165 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 10:46:37.407  1016  1382 I ActivityManager: Killing 6546:com.android.providers.calendar/u0a37 (adj 15): empty #21,
08-25 10:46:37.407  7165  7165 E Zygote  : MountEmulatedStorage()
08-25 10:46:37.407  7165  7165 I libpersona: KNOX_SDCARD checking this for 10036,
08-25 10:46:37.407  7165  7165 E Zygote  : v2
08-25 10:46:37.407  7165  7165 I libpersona: KNOX_SDCARD not a persona
08-25 10:46:37.407  7165  7165 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 10:46:37.407  1016  1380 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-25 10:46:37.407  1016  1380 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:37.407  1016  1380 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-25 10:46:37.407  1016  1380 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-25 10:46:37.407  1016  1380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
08-25 10:46:37.417  7165  7165 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 10:46:37.417  7165  7165 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-25 10:46:37.437  7165  7165 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:37.437  7165  7165 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:37.437  7130  7130 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-25 10:46:37.447  7130  7130 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-25 10:46:37.447  7130  7130 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:37.457  7130  7130 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-25 10:46:37.457  7130  7130 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-25 10:46:37.457  7130  7130 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-25 10:46:37.457  1016  1380 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-25 10:46:37.457  1016  1380 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:37.457  1016  1380 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.457  1016  1380 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.457  1016  1380 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:37.477  7165  7165 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@1cd91d16
,08-25 10:46:37.487  7165  7165 I SA      : [SSP] onCreated
,08-25 10:46:37.487  7182  7182 E Zygote  : MountEmulatedStorage()
08-25 10:46:37.487  7182  7182 I libpersona: KNOX_SDCARD checking this for 10008
08-25 10:46:37.487  7182  7182 E Zygote  : v2
08-25 10:46:37.487  7182  7182 I libpersona: KNOX_SDCARD not a persona
08-25 10:46:37.487  7182  7182 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 10:46:37.487  1016  1380 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7182 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 10:46:37.487  7182  7182 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 10:46:37.497  7182  7182 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-25 10:46:37.507  7165  7165 I SA      : [TPM] There is no property file
,08-25 10:46:37.507  7165  7165 I SA      : [SCU] isHaveSA() - false
,08-25 10:46:37.507  7182  7182 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:37.507  7182  7182 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:37.507  7165  7165 I SA      : [TPM] getModelProperty : null
08-25 10:46:37.507  7165  7165 I SA      : [TPM] getCSCProperty : null
,08-25 10:46:37.517  7165  7165 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-25 10:46:37.517  7165  7165 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-25 10:46:37.517  7165  7165 I SA      : [DM] TFT FEATURE: false
,08-25 10:46:37.517  7165  7165 I SA      : [DM] init START
,08-25 10:46:37.517  7165  7165 I SA      : [DM] This device is not a Vodafone
,08-25 10:46:37.527  7165  7165 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
08-25 10:46:37.527  7165  7165 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-25 10:46:37.527  7165  7165 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-25 10:46:37.527  7165  7165 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-25 10:46:37.527  7165  7165 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-25 10:46:37.527  7165  7165 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-25 10:46:37.527  7165  7165 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-25 10:46:37.527  7165  7165 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-25 10:46:37.537  7165  7165 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-25 10:46:37.547  7165  7165 I SA      : [SCU] isHaveSA() - false
08-25 10:46:37.547  7165  7165 I SA      : support phone number id : false
08-25 10:46:37.547  7165  7165 I SA      : [DM] Supports Ref Jpn : true
08-25 10:46:37.547  7165  7165 I SA      : [DM] init END
,08-25 10:46:37.547  7165  7165 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-25 10:46:37.547  7165  7165 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-25 10:46:37.547  7165  7165 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-25 10:46:37.587  1016  1028 I ActivityManager: Killing 6052:com.android.mms/u0a41 (adj 15): empty #21
,08-25 10:46:37.597  2919  2919 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Aug 25 10:46:37 GMT+02:00 2016
,08-25 10:46:37.597  1016  1483 D RCPManagerService: exchangeData() failure , invalid userId
08-25 10:46:37.597  1016  1481 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-25 10:46:37.597  1016  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-25 10:46:37.597  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:37.597  1016  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 10:46:37.597  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-25 10:46:37.607  2919  2919 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-25 10:46:37.607  2919  2919 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-25 10:46:37.607  2919  2919 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-25 10:46:37.607  7165  7165 I SA      : [SLFUCHKMGR] constructor called
,08-25 10:46:37.607  2919  2919 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-25 10:46:37.617  2919  7202 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-25 10:46:37.617  2919  7202 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-25 10:46:37.627  7165  7165 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-25 10:46:37.627  7165  7165 I SA      : [OR] == isSIMCardReady false ==
,08-25 10:46:37.627  2919  7202 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-25 10:46:37.627  2919  7202 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-25 10:46:37.627  2919  2919 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-25 10:46:37.647  1016  1485 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 10:46:37.657  1016  1371 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-25 10:46:37.657  1016  1371 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-25 10:46:37.657  1016  1371 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:37.657  1016  1371 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:37.657  1016  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-25 10:46:37.667  1016  1481 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-25 10:46:37.667  7165  7165 I SA      : [SCU] == networkStateCheck == false
08-25 10:46:37.667  7165  7165 I SA      : [OR] onReceive END
,08-25 10:46:37.667  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:37.667  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.667  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.667  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:37.677  7143  7171 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-25 10:46:37.677  7207  7207 E Zygote  : MountEmulatedStorage()
08-25 10:46:37.677  7207  7207 E Zygote  : v2
08-25 10:46:37.677  7207  7207 I libpersona: KNOX_SDCARD checking this for 10110
08-25 10:46:37.677  7207  7207 I libpersona: KNOX_SDCARD not a persona
,08-25 10:46:37.677  7207  7207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:37.687  1016  1481 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7207 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 10:46:37.687  7207  7207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 10:46:37.687  1016  1380 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-25 10:46:37.687  1016  1380 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-25 10:46:37.687  1016  1380 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:37.687  1016  1549 D CountryDetector: No listener is left
08-25 10:46:37.687  1016  1380 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:37.687  1016  1380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-25 10:46:37.687  7207  7207 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 10:46:37.687  1016  1481 I ActivityManager: Killing 6647:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-25 10:46:37.697  6980  7206 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-25 10:46:37.697  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:37.697  1016  1371 I ActivityManager: Killing 6665:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-25 10:46:37.707  1016  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-25 10:46:37.717  1016  1485 I ActivityManager: Killing 6503:com.android.calendar/u0a131 (adj 15): empty #21
,08-25 10:46:37.717  7207  7207 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:37.717  7207  7207 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:37.807  1016  1550 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 10:46:37.807  1016  1382 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 10:46:37.857  1016  1371 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-25 10:46:37.857  1016  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:37.857  1016  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.857  1016  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.857  1016  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:37.867  7228  7228 E Zygote  : MountEmulatedStorage()
,08-25 10:46:37.877  7228  7228 E Zygote  : v2
08-25 10:46:37.877  7228  7228 I libpersona: KNOX_SDCARD checking this for 10068
08-25 10:46:37.877  7228  7228 I libpersona: KNOX_SDCARD not a persona
,08-25 10:46:37.877  7228  7228 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:37.877  7228  7228 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-25 10:46:37.877  1016  1371 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7228 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-25 10:46:37.877  7228  7228 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-25 10:46:37.897  7228  7228 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:37.897  7228  7228 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:37.897  7114  7213 W art     : Verification of boolean com.android.email.activity.MessageListItemOuterContainer.onTouchEvent(android.view.MotionEvent) took 147.587ms
,08-25 10:46:37.917  7228  7228 D BadgeProvider: onCreate
,08-25 10:46:37.917  7228  7228 D BadgeProvider: DatabaseHelper
08-25 10:46:37.917   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 10:46:37.927  1016  1216 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 10:46:37.927  1016  1549 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-25 10:46:37.927  7228  7239 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-25 10:46:37.947  1016  1028 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 10:46:37.947  1016  1134 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 10:46:37.967  1016  1028 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 10:46:37.967  1016  1371 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-25 10:46:37.967  1016  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:37.967  1016  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.967  1016  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:37.967  1016  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:37.977  7244  7244 E Zygote  : MountEmulatedStorage()
08-25 10:46:37.977  7244  7244 E Zygote  : v2
08-25 10:46:37.977  7244  7244 I libpersona: KNOX_SDCARD checking this for 10009
08-25 10:46:37.977  7244  7244 I libpersona: KNOX_SDCARD not a persona
,08-25 10:46:37.977  7244  7244 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:37.987  1016  1371 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7244 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-25 10:46:37.987  1016  1371 I ActivityManager: Killing 6013:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-25 10:46:37.987  7244  7244 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 10:46:37.987  1016  1371 I ActivityManager: Killing 6681:com.google.android.gms:car/u0a11 (adj 15): empty #22
,08-25 10:46:37.987  7228  7239 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-25 10:46:37.987  7228  7239 D BadgeProvider: sendNotify, [notify] : null
08-25 10:46:37.987  7228  7239 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-25 10:46:37.987  7228  7239 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-25 10:46:37.987  7228  7239 D BadgeProvider: update, [UpdateCount] : 1
08-25 10:46:37.987  7244  7244 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-25 10:46:37.987  1475  1475 D Launcher.Model: reloadBadges entered.
,08-25 10:46:38.017  7244  7244 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:38.017  7244  7244 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:38.027  1016  1028 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-25 10:46:38.027  1016  1028 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 10:46:38.027  1016  1028 D SecContentProvider2: mCursor = null
,08-25 10:46:38.027  1016  1028 D WifiService: setWifiEnabled: true pid=6741, uid=10171
08-25 10:46:38.027  1016  1028 W ActivityManager: Permission Denial: getCurrentUser() from pid=6741, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-25 10:46:38.027  1016  1028 W WifiService: Failed getting userId using ActivityManagerNative
08-25 10:46:38.027  1016  1028 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6741, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 10:46:38.027  1016  1028 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 10:46:38.027  1016  1028 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-25 10:46:38.027  1016  1028 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-25 10:46:38.027  1016  1028 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-25 10:46:38.027  1016  1028 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-25 10:46:38.027  1016  1028 D SettingsProvider: name = wifi_on
,08-25 10:46:38.027  1016  1124 E WifiHW  : ##################### set firmware type 0 #####################
,08-25 10:46:38.127   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-25 10:46:38.127   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 10:46:38.127  7207  7265 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-25 10:46:38.137   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-25 10:46:38.137   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 10:46:38.137  7207  7265 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-25 10:46:38.147  1016  1549 I ActivityManager: Killing 5828:com.android.vending/u0a26 (adj 15): empty #21
,08-25 10:46:38.147  1016  1382 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 10:46:38.147  1016  1382 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-25 10:46:38.157  1016  1382 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:38.157  1016  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:38.157  1016  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:38.167  4811  7267 I iu.SyncManager: SYNC; picasa accounts
,08-25 10:46:38.177   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-25 10:46:38.177   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 10:46:38.177  7207  7266 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-25 10:46:38.177  4811  4811 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-25 10:46:38.177  7207  7207 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-25 10:46:38.177  7207  7207 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-25 10:46:38.177  7207  7207 I GAv4    :   adb logcat -s GAv4
,08-25 10:46:38.187   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-25 10:46:38.187   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 10:46:38.187  7207  7266 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-25 10:46:38.207  7207  7207 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-25 10:46:38.207  1016  1216 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-25 10:46:38.217  7207  7207 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-25 10:46:38.227  1016  1382 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-25 10:46:38.227  1016  1382 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-25 10:46:38.237  1016  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-25 10:46:38.237  1016  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-25 10:46:38.237  7207  7270 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-25 10:46:38.417  1016  1043 D Tethering: interfaceAdded wlan0
,08-25 10:46:38.427  1016  1129 E Tethering: No numeric data,
08-25 10:46:38.427  1016  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 10:46:38.427  1016  1129 D Tethering: clearTetheredNotification()
,08-25 10:46:38.427  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:38.427  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
08-25 10:46:38.427  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 10:46:38.427  1016  1121 V NetworkStats: performPollLocked() took 4ms
08-25 10:46:38.427  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 10:46:38.427  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:38.437  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 10:46:38.437  1176  1176 D HotspotTile: updateTetherState():false, false
08-25 10:46:38.437  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 10:46:38.437  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 10:46:38.437  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 10:46:38.437  1016  1129 D Tethering: InitialState.processMessage what=4
,08-25 10:46:38.437  1016  1129 E Tethering: No numeric data
,08-25 10:46:38.437  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:38.437  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:38.437  1016  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-25 10:46:38.437  1016  1129 D Tethering: clearTetheredNotification()
,08-25 10:46:38.437  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
08-25 10:46:38.437  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:38.437  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 10:46:38.437  1176  1176 D HotspotTile: updateTetherState():false, false
08-25 10:46:38.437  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 10:46:38.437  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 10:46:38.447  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 10:46:38.447  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 10:46:38.447  1016  1121 V NetworkStats: performPollLocked() took 6ms
08-25 10:46:38.447  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:38.447   276  1015 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-25 10:46:38.447  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
08-25 10:46:38.447   276  1015 D SoftapController: Softap fwReload - Ok
,08-25 10:46:38.447  1016  1043 D Tethering: interfaceAdded p2p0
08-25 10:46:38.447  1016  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-25 10:46:38.447   276  1015 D CommandListener: Setting iface cfg
08-25 10:46:38.447   276  1015 D CommandListener: Trying to bring down wlan0
08-25 10:46:38.447  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:38.447  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:38.447   276  1015 D CommandListener: Clearing all IP addresses on wlan0
,08-25 10:46:38.447  1016  1124 E WifiHW  : supplicant_name : p2p_supplicant
,08-25 10:46:38.467  1016  1550 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:38.477  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:38.477  1016  1550 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:38.477  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-25 10:46:38.527  7207  7207 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-25 10:46:38.527  7292  7292 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-25 10:46:38.527  7292  7292 I wpa_supplicant: Successfully initialized wpa_supplicant
08-25 10:46:38.527  7292  7292 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
,08-25 10:46:38.547  7207  7207 I cr.library_loader: Time to load native libraries: 1 ms (timestamps 7508-7509)
08-25 10:46:38.547  7207  7207 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-25 10:46:38.557  1016  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-25 10:46:38.557  7207  7207 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {124dd429},
08-25 10:46:38.557  1176  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 10:46:38.557  7207  7207 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-25 10:46:38.557  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 10:46:38.557  7207  7207 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 10:46:38.557  1176  1176 D HotspotTile: onReceive : 2, 0
08-25 10:46:38.557  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-25 10:46:38.557  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 10:46:38.557  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:38.557  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:38.557  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:38.557  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:38.557  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 10:46:38.557  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-25 10:46:38.557  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 10:46:38.567  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-25 10:46:38.567  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:38.567  7292  7292 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-25 10:46:38.567   380   380 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7292
08-25 10:46:38.567   380   380 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-25 10:46:38.567  7292  7292 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-25 10:46:38.567  7292  7292 I wpa_supplicant: ssSupport state is = 1
08-25 10:46:38.567  7292  7292 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-25 10:46:38.567  7292  7292 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-25 10:46:38.567   380   380 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7292
08-25 10:46:38.567   380   380 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-25 10:46:38.577  7207  7207 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-25 10:46:38.587  7207  7207 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 10:46:38.587  7207  7207 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 10:46:38.607  7207  7207 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-25 10:46:38.607  7207  7207 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-25 10:46:38.607  7207  7207 I Adreno-EGL: Build Date: 04/06/15 Mon
08-25 10:46:38.607  7207  7207 I Adreno-EGL: Local Branch: 
08-25 10:46:38.607  7207  7207 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-25 10:46:38.607  7207  7207 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-25 10:46:38.607  7207  7207 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-25 10:46:38.667  7207  7207 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 10:46:38.677  7207  7307 W cr.media: Requires BLUETOOTH permission
,08-25 10:46:38.677  7207  7207 I NSApplication: Starting up...
,08-25 10:46:38.687  1016  1216 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-25 10:46:38.687  1016  1483 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-25 10:46:38.687  1016  1485 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-25 10:46:38.687  1016  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:38.687  1016  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:38.687  1016  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:38.687  1016  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:38.707  7312  7312 E Zygote  : MountEmulatedStorage()
08-25 10:46:38.707  7312  7312 I libpersona: KNOX_SDCARD checking this for 10117
,08-25 10:46:38.707  7312  7312 E Zygote  : v2
08-25 10:46:38.707  7312  7312 I libpersona: KNOX_SDCARD not a persona
08-25 10:46:38.707  7312  7312 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 10:46:38.707  7312  7312 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 10:46:38.707  7312  7312 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 10:46:38.727  1016  1485 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7312 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-25 10:46:38.727  1016  1485 I ActivityManager: Killing 6883:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-25 10:46:38.737  7312  7312 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:38.737  7312  7312 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:38.747  1016  1028 I ActivityManager: Killing 6947:com.android.bluetooth/1002 (adj 15): empty #21
,08-25 10:46:38.757  7312  7312 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 10:46:38.767   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,08-25 10:46:38.767  7292  7292 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-25 10:46:38.817  7292  7292 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-25 10:46:38.817  7292  7292 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-25 10:46:38.827  7292  7292 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-25 10:46:38.827   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7292
08-25 10:46:38.827   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-25 10:46:38.827  7292  7292 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-25 10:46:38.827  7292  7292 I wpa_supplicant: ssSupport state is = 1
08-25 10:46:38.827  7292  7292 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-25 10:46:38.827  7292  7292 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 10:46:38.827  7292  7292 E wpa_supplicant: SIM READ ERROR
,08-25 10:46:38.837  7292  7292 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 10:46:38.837  7292  7292 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 10:46:38.837  7292  7292 E wpa_supplicant: SIM READ ERROR
08-25 10:46:38.837  7292  7292 I wpa_supplicant: Blacklist: Clear (all) 
08-25 10:46:38.837  7292  7292 I wpa_supplicant: wpa_default_ap_write_once
08-25 10:46:38.837  7292  7292 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-25 10:46:38.837  7292  7292 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 10:46:38.837  7292  7292 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-25 10:46:38.837  7292  7292 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 10:46:38.837  7292  7292 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-25 10:46:38.837  7292  7292 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 10:46:38.837  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 10:46:38.837  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 10:46:38.837  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 10:46:38.857   289   289 E SMD     : DCD OFF
,08-25 10:46:38.917   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-25 10:46:38.917  7292  7292 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-25 10:46:39.057  7292  7292 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-25 10:46:39.057  7292  7292 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-25 10:46:39.077  7292  7292 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-25 10:46:39.077   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7292
08-25 10:46:39.077   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-25 10:46:39.077  7292  7292 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-25 10:46:39.077  7292  7292 I wpa_supplicant: ssSupport state is = 1
,08-25 10:46:39.097  7292  7292 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-25 10:46:39.097  7292  7292 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-25 10:46:39.107  7292  7292 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-25 10:46:39.107   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7292
08-25 10:46:39.107   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-25 10:46:39.107  7292  7292 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-25 10:46:39.107  7292  7292 I wpa_supplicant: ssSupport state is = 1
08-25 10:46:39.107  7292  7292 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 10:46:39.107  7292  7292 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 10:46:39.107  7292  7292 E wpa_supplicant: SIM READ ERROR
08-25 10:46:39.107  7292  7292 I wpa_supplicant: wpa_default_ap_write_once
08-25 10:46:39.107  7292  7292 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-25 10:46:39.107  7292  7292 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 10:46:39.117  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 10:46:39.117  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 10:46:39.117  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-25 10:46:39.117  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-25 10:46:39.117  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 10:46:39.117  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-25 10:46:39.127  1016  1485 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-25 10:46:39.137  1016  1485 I ActivityManager: Killing 6901:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-25 10:46:39.147  1016  1382 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 10:46:39.147  1016  1382 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 10:46:39.147  1016  1382 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:39.147  1016  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:39.147  1016  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 10:46:39.147  2201  2201 I Hs20UtilService: Starting #11
,08-25 10:46:39.147  2201  2218 I Hs20UtilService: Message received 5011
,08-25 10:46:39.157  6540  6540 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 10:46:39.157  6540  6540 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 10:46:39.157  6540  6540 D SecurityLogAgent: StateMachine : Current State = 1
08-25 10:46:39.157  6540  6540 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 10:46:39.167  1016  1481 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 10:46:39.167  1016  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 10:46:39.167  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:39.167  1016  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:39.167  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 10:46:39.167  2201  2201 I Hs20UtilService: Starting #12
,08-25 10:46:39.167  2201  2218 I Hs20UtilService: Message received 5011
,08-25 10:46:39.177  6540  6540 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 10:46:39.177  6540  6540 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 10:46:39.177  6540  6540 D SecurityLogAgent: StateMachine : Current State = 1
08-25 10:46:39.177  6540  6540 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 10:46:39.267  7292  7292 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-25 10:46:39.267  7292  7292 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-25 10:46:39.307  7292  7292 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-25 10:46:39.307  7292  7292 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-25 10:46:39.307  7292  7292 I wpa_supplicant: Skip scan - bUseNetwork false
,08-25 10:46:39.317  1016  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-25 10:46:39.317  1016  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-25 10:46:39.317  7292  7292 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-25 10:46:39.317  7292  7292 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-25 10:46:39.317  7292  7292 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 10:46:39.317  7292  7292 E wpa_supplicant: SIM READ ERROR,
08-25 10:46:39.317  7292  7292 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 10:46:39.357  7292  7292 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-25 10:46:39.367  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-25 10:46:39.367  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 10:46:39.367  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-25 10:46:39.367  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:39.367  1176  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 10:46:39.367  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:39.367  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 10:46:39.367  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:39.367  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 10:46:39.367  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-25 10:46:39.377  7292  7292 I wpa_supplicant: Skip scan - bUseNetwork false
08-25 10:46:39.377  1176  1176 D HotspotTile: onReceive : 3, 0
08-25 10:46:39.377  1016  1124 D WifiConfigStore: Loading config and enabling all networks 
,08-25 10:46:39.377  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:39.377  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:39.377  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:39.377  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:39.377  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:39.377  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:39.377  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:39.377  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:39.377  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:46:39.377  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:39.377  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:39.377  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 10:46:39.377  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:39.377  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:39.377  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:39.377  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:39.377  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:39.377  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:39.377  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:39.377  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:46:39.377  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 10:46:39.377  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:46:39.377  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-25 10:46:39.377  1016  1371 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 10:46:39.377  1016  1371 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
08-25 10:46:39.377  1016  1371 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:39.377  1016  1371 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:39.377  1016  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 10:46:39.387  2201  2201 I Hs20UtilService: Starting #13
,08-25 10:46:39.387  1016  1124 E WifiConfigStore: Not a HS20
,08-25 10:46:39.387  2201  2218 I Hs20UtilService: Message received 5011
08-25 10:46:39.387  1016  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 10:46:39.387  6540  6540 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-25 10:46:39.387  6540  6540 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 10:46:39.387  6540  6540 D SecurityLogAgent: StateMachine : Current State = 1
,08-25 10:46:39.387  1016  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-25 10:46:39.387  6540  6540 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 10:46:39.397  1016  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13],
08-25 10:46:39.397  7292  7292 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-25 10:46:39.397  7292  7292 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-25 10:46:39.397  7292  7292 I wpa_supplicant: reset timer : RESET_TIMER 0
08-25 10:46:39.397  7292  7292 I wpa_supplicant: P2P: Current p2p state = IDLE
08-25 10:46:39.397  7292  7292 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-25 10:46:39.397  7292  7292 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,08-25 10:46:39.397  7292  7292 I wpa_supplicant: First Scan Start
08-25 10:46:39.397  7292  7292 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-25 10:46:39.397  1016  1124 D WifiNative-wlan0: Setting external_sim to 1
,08-25 10:46:39.397  1016  1124 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 10:46:39.397  1016  1124 I WifiNative-HAL: startHal
08-25 10:46:39.397  1016  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9e9d588c
08-25 10:46:39.397  1016  1124 I WifiNative-HAL: Could not start hal
,08-25 10:46:39.397  6980  6980 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 10:46:39.407  1016  1124 E WifiNative-wlan0: do suspend true
,08-25 10:46:39.407  1016  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-25 10:46:39.407  1016  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
08-25 10:46:39.407  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 10:46:39.407  1016  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:46:39.407  1016  1148 I WifiNative-HAL: startHal
08-25 10:46:39.407  1016  1148 E wifi    : getStaticLongField sWifiHalHandle 0x98ffe9bc
08-25 10:46:39.407  1016  1148 I WifiNative-HAL: Could not start hal
08-25 10:46:39.407  1016  1148 E WifiScanningService: could not start HAL
08-25 10:46:39.407  1016  1016 D RttService: SCAN_AVAILABLE : 3
08-25 10:46:39.407  1016  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:46:39.407  1016  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-25 10:46:39.407  1016  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 10:46:39.407  1016  1124 E WifiNative-wlan0: invaild command id : 215
08-25 10:46:39.407   276  1015 D CommandListener: Setting iface cfg
08-25 10:46:39.407   276  1015 D CommandListener: Trying to bring up p2p0
08-25 10:46:39.407  1016  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-25 10:46:39.407  1016  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,08-25 10:46:39.407  1016  1124 E WifiNative-wlan0: invaild command id : 215
08-25 10:46:39.407  1016  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 10:46:39.407  7292  7292 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-25 10:46:39.407  1016  1123 D WifiP2pService: P2pEnablingState
08-25 10:46:39.407  1016  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
08-25 10:46:39.407  1016  1123 D WifiP2pService: P2p socket connection successful
08-25 10:46:39.407  1016  1123 D WifiP2pService: P2pEnabledState
08-25 10:46:39.417  1016  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-25 10:46:39.417  7292  7292 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-25 10:46:39.417  1016  1126 E ConnectivityService: updateNetworkInfo()
08-25 10:46:39.417  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-25 10:46:39.417  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-25 10:46:39.417  7292  7292 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-25 10:46:39.417  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 10:46:39.417  1016  1046 D WifiDisplayController: disconnect
08-25 10:46:39.417  1016  1046 D WifiDisplayController: updateConnection
08-25 10:46:39.417  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 10:46:39.417  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 10:46:39.417  1016  1124 E WifiStateMachine: Failed to set frequency band 0
,08-25 10:46:39.417  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 10:46:39.417  1016  1124 D SecContentProvider2: mCursor = null
,08-25 10:46:39.417  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 10:46:39.417  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-25 10:46:39.417  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 10:46:39.417  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-25 10:46:39.417  1016  1123 D WifiNative-p2p0: p2pGetDeviceAddress
,08-25 10:46:39.417  1016  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-25 10:46:39.417  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-25 10:46:39.417  1016  1380 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 10:46:39.417  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-25 10:46:39.427  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-25 10:46:39.427  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 10:46:39.427  1016  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-25 10:46:39.427  1016  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-25 10:46:39.427  1016  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-25 10:46:39.427  1016  1046 D WifiDisplayController:  secondary type: null
08-25 10:46:39.427  1016  1046 D WifiDisplayController:  wps: 0
08-25 10:46:39.427  1016  1046 D WifiDisplayController:  grpcapab: 0
08-25 10:46:39.427  1016  1046 D WifiDisplayController:  devcapab: 0
08-25 10:46:39.427  1016  1046 D WifiDisplayController:  status: 3
08-25 10:46:39.427  1016  1046 D WifiDisplayController:  wfdInfo: null
08-25 10:46:39.427  1016  1046 D WifiDisplayController:  groupownerAddress: null
08-25 10:46:39.427  1016  1046 D WifiDisplayController:  GOdeviceName: null
08-25 10:46:39.427  1016  1046 D WifiDisplayController:  interfaceAddress: 
08-25 10:46:39.427  1016  1046 D WifiDisplayController:  SConnectInfo : null
08-25 10:46:39.427  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-25 10:46:39.427  1016  1123 D WifiP2pService: DeviceAddress: 0a:76:28
08-25 10:46:39.427  1016  1124 D SecContentProvider2: mCursor = null
,08-25 10:46:39.427  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 10:46:39.427  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 10:46:39.427  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 10:46:39.427  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 10:46:39.427  1315  2242 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 10:46:39.427  7003  7003 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 10:46:39.437  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 10:46:39.437  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 10:46:39.437  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-25 10:46:39.437  7003  7003 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-25 10:46:39.437  7003  7003 D FileShare-Client: Outbound.stopDelayTimer - 
,08-25 10:46:39.437  7018  7018 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 10:46:39.447  1016  1123 D WifiP2pService: sending p2p persistent groups changed broadcast,
08-25 10:46:39.447  1016  1123 D WifiP2pService: InactiveState
,08-25 10:46:39.447  1016  1123 D WifiP2pService: InactiveState{ what=143376 }
,08-25 10:46:39.447  1016  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 10:46:39.447  7292  7292 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-25 10:46:39.447  1016  1123 D WifiP2pService: InactiveState{ what=143376 }
08-25 10:46:39.447  1016  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 10:46:39.917   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-25 10:46:40.617  7292  7292 I wpa_supplicant: nl80211: Received scan results (33 BSSes)
08-25 10:46:40.617  7292  7292 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,08-25 10:46:40.627  7292  7292 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-25 10:46:40.627  7292  7292 I wpa_supplicant: Trying to associate with  'G700'
08-25 10:46:40.627  7292  7292 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-25 10:46:40.627  7292  7292 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,08-25 10:46:40.627  1016  7338 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-25 10:46:40.647  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 10:46:40.647  1016  1124 D SecContentProvider2: mCursor = null
,08-25 10:46:40.737  7292  7292 E wpa_supplicant: Cmd 35605 not handled
,08-25 10:46:40.737  7292  7292 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-25 10:46:40.737  7292  7292 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-25 10:46:40.737  7292  7292 I wpa_supplicant: Associated with F4.99.3E
08-25 10:46:40.737  7292  7292 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-25 10:46:40.737  7292  7292 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-25 10:46:40.737  7292  7292 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-25 10:46:40.737  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 10:46:40.747  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 10:46:40.747  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 10:46:40.747  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 10:46:40.747  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-25 10:46:40.747  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-25 10:46:40.747  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 10:46:40.747  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 10:46:40.747  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-25 10:46:40.747  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-25 10:46:40.747  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true,
,08-25 10:46:40.747  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-25 10:46:40.747  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 10:46:40.747  1016  1124 D SecContentProvider2: mCursor = null
08-25 10:46:40.757  7292  7292 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-25 10:46:40.757  7292  7292 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-25 10:46:40.757  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 10:46:40.757  1016  1124 D SecContentProvider2: mCursor = null
08-25 10:46:40.757  1016  1129 E Tethering: No numeric data
08-25 10:46:40.757  7292  7292 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-25 10:46:40.757  7292  7292 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-25 10:46:40.757  7292  7292 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 10:46:40.757  7292  7292 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-25 10:46:40.757  7292  7292 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-25 10:46:40.757  7292  7292 I wpa_supplicant: Blacklist: Clear (temp) 
08-25 10:46:40.757  7292  7292 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-25 10:46:40.757  1016  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 10:46:40.757  1016  1129 D Tethering: clearTetheredNotification()
,08-25 10:46:40.757  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
,08-25 10:46:40.757  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-25 10:46:40.757  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
08-25 10:46:40.767  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:40.767  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
08-25 10:46:40.767  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 10:46:40.767  1176  1176 D HotspotTile: updateTetherState():false, false
08-25 10:46:40.767  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 10:46:40.767  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 10:46:40.767  1016  1121 V NetworkStats: performPollLocked() took 4ms
08-25 10:46:40.767  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:40.767  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:40.767  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:40.777  1016  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-25 10:46:40.777  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 10:46:40.777  1016  1124 E WifiConfigStore: setLastSelectedConfiguration -1
08-25 10:46:40.777  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 10:46:40.777  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:40.787  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:40.787  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:40.787  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:40.787  1016  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-25 10:46:40.787  1016  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-25 10:46:40.787  1016  1126 E ConnectivityService: updateNetworkInfo()
08-25 10:46:40.787  1016  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-25 10:46:40.787  1016  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 10:46:40.787  1016  1549 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 10:46:40.787  1016  1549 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 10:46:40.787  1016  1549 W ActivityManager: userId = 0, bbcId = -10000,
08-25 10:46:40.787  1016  1549 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:40.787  1016  1549 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-25 10:46:40.797  2201  2201 I Hs20UtilService: Starting #14
,08-25 10:46:40.797  2201  2218 I Hs20UtilService: Message received 5007
,08-25 10:46:40.797  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 10:46:40.797  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 10:46:40.797  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 10:46:40.797  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 10:46:40.797  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-25 10:46:40.797  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 10:46:40.797  1315  2242 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 10:46:40.807  1016  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 10:46:40.817   276  1015 D CommandListener: Setting iface cfg
,08-25 10:46:40.817  1016  1124 E WifiStateMachine: Start Dhcp Watchdog 2
,08-25 10:46:40.827  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 10:46:40.827  1016  1124 D SecContentProvider2: mCursor = null
,08-25 10:46:40.827  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 10:46:40.827  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-25 10:46:40.837  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-25 10:46:40.837  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:40.837  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:40.837  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:40.837  1016  1124 E WifiNative-wlan0: do suspend false
,08-25 10:46:40.837  1016  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-25 10:46:40.847  1016  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
08-25 10:46:40.847  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 10:46:40.847  1016  1124 D SecContentProvider2: mCursor = null
,08-25 10:46:41.027  1016  1550 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-25 10:46:41.027  1016  1550 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-25 10:46:41.027  1016  1550 D SecContentProvider2: mCursor = null
,08-25 10:46:41.037  1016  1550 D WifiService: setWifiEnabled: false pid=6741, uid=10171
,08-25 10:46:41.037  1016  1550 D SettingsProvider: name = wifi_on
,08-25 10:46:41.047  1016  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-25 10:46:41.057  7345  7345 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-25 10:46:41.067  1016  1124 E WifiNative-wlan0: do suspend true,
,08-25 10:46:41.067  7345  7345 I dhcpcd  : version 5.5.6 starting,
,08-25 10:46:41.097  7345  7345 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-25 10:46:41.107  1016  1123 D WifiP2pService: InactiveState{ what=143375 },
08-25 10:46:41.107  1016  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 10:46:41.107   276  1015 D CommandListener: Clearing all IP addresses on wlan0
08-25 10:46:41.107  1016  1126 E ConnectivityService: updateNetworkInfo()
08-25 10:46:41.107  1016  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 10:46:41.107  1016  1126 E ConnectivityService: updateNetworkInfo()
08-25 10:46:41.107  1016  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-25 10:46:41.107   276  1015 E Netd    : no such netId 503
,08-25 10:46:41.117  1016  1123 D WifiP2pService: InactiveState{ what=131204 },
08-25 10:46:41.117  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:41.117  1016  1123 D WifiP2pService: P2pEnabledState{ what=131204 },
08-25 10:46:41.117  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 10:46:41.117  1016  1126 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-25 10:46:41.117  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-25 10:46:41.117  1016  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-25 10:46:41.117  1016  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-25 10:46:41.117  1016  1126 V NetworkStats: updateIfacesLocked(),
08-25 10:46:41.117  1016  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 10:46:41.117  1016  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-25 10:46:41.117  1016  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-25 10:46:41.117  1016  1123 D WifiP2pService: P2pDisablingState
08-25 10:46:41.117  1016  1123 D WifiP2pService: P2pDisablingState{ what=147458 },
08-25 10:46:41.117  1016  1123 D WifiP2pService: p2p socket connection lost
08-25 10:46:41.117  1016  1123 D WifiP2pService: P2pDisabledState
,08-25 10:46:41.117  1016  1124 E WifiNative-wlan0: do suspend true
,08-25 10:46:41.127  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:41.127  1016  1126 V NetworkStats: performPollLocked() took 9ms
08-25 10:46:41.127  1016  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-25 10:46:41.127  1016  7342 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler },
08-25 10:46:41.127  1016  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-25 10:46:41.127  1016  7342 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 10:46:41.127  1016  1126 D ConnectivityService: nai.networkMonitor.doQuit()
08-25 10:46:41.127  1016  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-25 10:46:41.127  1016  1126 E ConnectivityService: updateNetworkInfo()
08-25 10:46:41.127  1016  1126 E ConnectivityService: updateNetworkInfo()
,08-25 10:46:41.147  1016  1382 I ActivityManager: Killing 7034:com.sec.pcw.device/1000 (adj 15): empty #21
,08-25 10:46:41.157  1016  1123 D WifiP2pService: P2pDisabledState{ what=143375 },
08-25 10:46:41.157   276  1015 D CommandListener: Clearing all IP addresses on wlan0
08-25 10:46:41.157  1016  1123 D WifiP2pService: DefaultState{ what=143375 }
,08-25 10:46:41.167  7292  7292 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED,
,08-25 10:46:41.167  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-25 10:46:41.177  1016  1124 D SecContentProvider2: mCursor = null
,08-25 10:46:41.177  7345  7345 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-25 10:46:41.177  7345  7345 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-25 10:46:41.177  7345  7345 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
,08-25 10:46:41.177  7345  7345 I dhcpcd  : bssid match
08-25 10:46:41.177  7345  7345 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-25 10:46:41.187  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-25 10:46:41.197  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 10:46:41.197  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 10:46:41.197  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:41.197  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:41.197  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:41.197  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:41.197  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 10:46:41.197  1016  1016 D RttService: SCAN_AVAILABLE : 1
08-25 10:46:41.197  1016  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:46:41.197  1016  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 10:46:41.197  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 10:46:41.197  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 10:46:41.197  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:41.197  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:41.197  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:41.197  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:41.197  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 10:46:41.197  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-25 10:46:41.197  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 10:46:41.197  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-25 10:46:41.207  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-25 10:46:41.207  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-25 10:46:41.207  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 10:46:41.207  1016  1046 D WifiDisplayController: disconnect
08-25 10:46:41.207  1016  1046 D WifiDisplayController: updateConnection
08-25 10:46:41.207  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 10:46:41.207  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 10:46:41.207  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:41.207  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-25 10:46:41.217  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 10:46:41.217  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 10:46:41.217  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:41.217  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:41.217  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:41.217  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:41.227  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling,
,08-25 10:46:41.227  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 10:46:41.227  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 10:46:41.227  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:41.227  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:41.227  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:41.227  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:41.237  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 10:46:41.237  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-25 10:46:41.237  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:41.237  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:41.237  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:41.237  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:41.237  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 10:46:41.237  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-25 10:46:41.237  1176  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-25 10:46:41.237  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 10:46:41.237  1176  1176 D HotspotTile: onReceive : 0, 0
,08-25 10:46:41.247  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 10:46:41.247  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:41.247  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:41.247  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:41.247  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:41.247  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:41.247  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:41.247  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:41.247  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:41.247  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:46:41.247  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:41.247  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:41.247  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:41.247  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:41.247  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:41.247  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:41.247  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:41.247  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:41.247  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:41.247  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:41.247  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:46:41.247  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:41.247  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:41.257  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-25 10:46:41.257  1016  1483 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 10:46:41.257  1016  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 10:46:41.257  1016  1481 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-25 10:46:41.257  1016  1483 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:41.257  7345  7345 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
08-25 10:46:41.257  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-25 10:46:41.257  1016  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:41.257  1016  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 10:46:41.257  2201  2201 I Hs20UtilService: Starting #15
08-25 10:46:41.257  2201  2218 I Hs20UtilService: Message received 5007
08-25 10:46:41.257  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 10:46:41.257  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-25 10:46:41.257  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-25 10:46:41.267  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 10:46:41.267  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 10:46:41.267  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 10:46:41.267  1315  2242 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-25 10:46:41.267  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 10:46:41.267  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-25 10:46:41.267  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-25 10:46:41.277  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 10:46:41.277  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 10:46:41.277  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 10:46:41.277  1315  2242 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-25 10:46:41.277  7003  7003 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-25 10:46:41.277  7003  7003 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-25 10:46:41.277  7003  7003 D FileShare-Client: Outbound.stopDelayTimer - 
08-25 10:46:41.287  7018  7018 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-25 10:46:41.287  1016  1550 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 10:46:41.287  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 10:46:41.287  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:41.287  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:41.287  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 10:46:41.297  2201  2201 I Hs20UtilService: Starting #16
08-25 10:46:41.297  2201  2218 I Hs20UtilService: Message received 5007
08-25 10:46:41.297  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 10:46:41.297  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-25 10:46:41.297  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-25 10:46:41.297  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 10:46:41.297  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 10:46:41.297  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 10:46:41.297  1315  2242 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-25 10:46:41.307  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 10:46:41.307  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 10:46:41.307  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:41.307  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:41.307  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 10:46:41.317  2201  2201 I Hs20UtilService: Starting #17
08-25 10:46:41.317  2201  2218 I Hs20UtilService: Message received 5011
08-25 10:46:41.317  6540  6540 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 10:46:41.317  6540  6540 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 10:46:41.317  6540  6540 D SecurityLogAgent: StateMachine : Current State = 1
08-25 10:46:41.317  6540  6540 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 10:46:41.337  7292  7292 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 10:46:41.387  7345  7345 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-25 10:46:41.427  7292  7292 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,08-25 10:46:41.427  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-25 10:46:41.427  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 10:46:41.427  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-25 10:46:41.447  7292  7292 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-25 10:46:41.447  7292  7292 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-25 10:46:41.447  7292  7292 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e,
08-25 10:46:41.447  7292  7292 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-25 10:46:41.447  7292  7292 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
08-25 10:46:41.457  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-25 10:46:41.457  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 10:46:41.457  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-25 10:46:41.457  1016  1129 D Tethering: InitialState.processMessage what=4,
,08-25 10:46:41.457  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 10:46:41.457  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 10:46:41.457  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-25 10:46:41.457  1016  1129 E Tethering: No numeric data
08-25 10:46:41.457  1016  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 10:46:41.457  1016  1129 D Tethering: clearTetheredNotification(),
08-25 10:46:41.467  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:41.467  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
08-25 10:46:41.467  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 10:46:41.467  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 10:46:41.467  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 10:46:41.467  1176  1176 D HotspotTile: updateTetherState():false, false
,08-25 10:46:41.467  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 10:46:41.467  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 10:46:41.467  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-25 10:46:41.467  1016  1121 V NetworkStats: performPollLocked() took 5ms
08-25 10:46:41.467  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:41.467  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:41.467  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:41.737  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-25 10:46:41.737  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 10:46:41.737  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 10:46:41.817  7292  7292 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 10:46:41.857   289   289 E SMD     : DCD OFF,
,08-25 10:46:41.897  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-25 10:46:41.897  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 10:46:41.897  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-25 10:46:41.897  7292  7292 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-25 10:46:42.007  6980  6980 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 10:46:42.007  1016  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-25 10:46:42.007  1016  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-25 10:46:42.017  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 10:46:42.017  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-25 10:46:42.017  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:42.017  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:42.017  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:42.017  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-25 10:46:42.017  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 10:46:42.017  1176  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-25 10:46:42.017  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-25 10:46:42.027  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-25 10:46:42.027  1176  1176 D HotspotTile: onReceive : 1, 0
,08-25 10:46:42.027  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:42.027  1954  2135 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 10:46:42.027  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:42.037  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 10:46:42.037  1016  1481 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 10:46:42.037  1016  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
,08-25 10:46:42.047  1016  1481 W ActivityManager: userId = 0, bbcId = -10000,
,08-25 10:46:42.047  1016  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:42.047  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 10:46:42.047  2201  2201 I Hs20UtilService: Starting #18
08-25 10:46:42.047  2201  2218 I Hs20UtilService: Message received 5011
,08-25 10:46:42.057  6540  6540 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-25 10:46:42.057  6540  6540 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-25 10:46:42.057  6540  6540 D SecurityLogAgent: StateMachine : Current State = 1
,08-25 10:46:42.057  6540  6540 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 10:46:42.657   276  1009 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-25 10:46:42.657  1016  1043 D Tethering: interfaceRemoved wlan0
,08-25 10:46:42.667  1016  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-25 10:46:42.777  1016  1043 D Tethering: interfaceRemoved p2p0
08-25 10:46:42.777  1016  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-25 10:46:43.477  1016  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-25 10:46:43.937  1016  3343 D SSRM:n  : SIOP:: AP = 340
,08-25 10:46:44.047  6741  6794 D BluetoothAdapter: enable()
,08-25 10:46:44.047  1016  1371 W ActivityManager: Permission Denial: getCurrentUser() from pid=6741, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-25 10:46:44.057  1016  1371 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-25 10:46:44.057  1016  1371 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6741, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 10:46:44.057  1016  1371 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 10:46:44.057  1016  1371 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-25 10:46:44.057  1016  1371 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-25 10:46:44.057  1016  1371 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-25 10:46:44.057  1016  1371 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 10:46:44.057  1016  1371 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 10:46:44.057  1016  1371 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 10:46:44.057  1016  1371 D SettingsProvider: name = bluetooth_on
,08-25 10:46:44.057  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 10:46:44.067  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 10:46:44.067  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-25 10:46:44.067  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-25 10:46:44.067  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:44.067  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:44.067  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:44.067  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:44.087  7377  7377 E Zygote  : MountEmulatedStorage()
,08-25 10:46:44.087  7377  7377 E Zygote  : v2
08-25 10:46:44.087  7377  7377 I libpersona: KNOX_SDCARD checking this for 1002
08-25 10:46:44.087  7377  7377 I libpersona: KNOX_SDCARD not a persona
,08-25 10:46:44.087  1016  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7377 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-25 10:46:44.087  7377  7377 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:44.097  7377  7377 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 10:46:44.097  7377  7377 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-25 10:46:44.127  7377  7377 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:44.127  7377  7377 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:44.147  7377  7377 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-25 10:46:44.147  7377  7377 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 10:46:44.177  7377  7377 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-25 10:46:44.217  7377  7377 D BtSettings.ProfileConfig: Adding GattService
,08-25 10:46:44.217  7377  7377 D BtSettings.ProfileConfig: Adding HeadsetService,
08-25 10:46:44.217  7377  7377 D BtSettings.ProfileConfig: Adding A2dpService
08-25 10:46:44.217  7377  7377 D BtSettings.ProfileConfig: Adding HidService
08-25 10:46:44.217  7377  7377 D BtSettings.ProfileConfig: Adding HealthService,
08-25 10:46:44.217  7377  7377 D BtSettings.ProfileConfig: Adding PanService
08-25 10:46:44.217  7377  7377 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-25 10:46:44.217  7377  7377 D BtSettings.ProfileConfig: Adding SapService
08-25 10:46:44.217  7377  7377 D BtSettings.ProfileConfig: Adding HeadsetClientService,
08-25 10:46:44.217  7377  7377 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-25 10:46:44.217  7377  7377 D BtSettings.ProfileConfig: Adding SapClientService
08-25 10:46:44.217  7377  7377 D BtSettings.ProfileConfig: Adding HidDevService
,08-25 10:46:44.217  7377  7377 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-25 10:46:44.217  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-25 10:46:44.217  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:44.217  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:44.217  1016  1028 D SettingsProvider: selectionArgs: false
08-25 10:46:44.217  1016  1028 D SettingsProvider: selectionArgs: 1002
08-25 10:46:44.227  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:44.227  1016  1028 D SettingsProvider: ret = -1
,08-25 10:46:44.227  1016  1483 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-25 10:46:44.227  1016  1483 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:44.227  1016  1483 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:44.227  1016  1483 D SettingsProvider: selectionArgs: false
08-25 10:46:44.227  1016  1483 D SettingsProvider: selectionArgs: 1002
08-25 10:46:44.227  1016  1483 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:44.227  1016  1483 D SettingsProvider: ret = -1
,08-25 10:46:44.227  1016  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-25 10:46:44.227  1016  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 10:46:44.227  1016  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 10:46:44.227  1016  1029 D SettingsProvider: selectionArgs: false
,08-25 10:46:44.227  1016  1029 D SettingsProvider: selectionArgs: 1002
08-25 10:46:44.227  1016  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:44.227  1016  1029 D SettingsProvider: ret = -1
08-25 10:46:44.227  1016  1216 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-25 10:46:44.227  1016  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:44.227  1016  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:44.227  1016  1216 D SettingsProvider: selectionArgs: false
08-25 10:46:44.227  1016  1216 D SettingsProvider: selectionArgs: 1002
08-25 10:46:44.227  1016  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:44.227  1016  1216 D SettingsProvider: ret = -1
08-25 10:46:44.227  1016  1382 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-25 10:46:44.227  1016  1382 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 10:46:44.227  1016  1382 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:44.227  1016  1382 D SettingsProvider: selectionArgs: false
08-25 10:46:44.227  1016  1382 D SettingsProvider: selectionArgs: 1002
,08-25 10:46:44.227  1016  1382 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:44.227  1016  1382 D SettingsProvider: ret = -1
08-25 10:46:44.227  1016  1380 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-25 10:46:44.227  1016  1380 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:44.227  1016  1380 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:44.227  1016  1380 D SettingsProvider: selectionArgs: false
08-25 10:46:44.227  1016  1380 D SettingsProvider: selectionArgs: 1002
08-25 10:46:44.227  1016  1380 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:44.227  1016  1380 D SettingsProvider: ret = -1
08-25 10:46:44.227  1016  1485 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:44.227  1016  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:44.227  1016  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:44.227  1016  1485 D SettingsProvider: selectionArgs: false
08-25 10:46:44.227  1016  1485 D SettingsProvider: selectionArgs: 1002,
08-25 10:46:44.227  1016  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:44.227  1016  1485 D SettingsProvider: ret = -1
,08-25 10:46:44.227  1016  1371 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-25 10:46:44.227  1016  1371 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:44.227  1016  1371 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-25 10:46:44.227  1016  1371 D SettingsProvider: selectionArgs: false
08-25 10:46:44.227  1016  1371 D SettingsProvider: selectionArgs: 1002
,08-25 10:46:44.227  1016  1371 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:44.227  1016  1371 D SettingsProvider: ret = -1
,08-25 10:46:44.227  1016  1550 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 10:46:44.227  1016  1550 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 10:46:44.227  1016  1550 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:44.227  1016  1550 D SettingsProvider: selectionArgs: false
08-25 10:46:44.227  1016  1550 D SettingsProvider: selectionArgs: 1002,
08-25 10:46:44.227  1016  1550 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:44.227  1016  1550 D SettingsProvider: ret = -1
08-25 10:46:44.227  1016  1549 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-25 10:46:44.227  1016  1549 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 10:46:44.227  1016  1549 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:44.227  1016  1549 D SettingsProvider: selectionArgs: false
,08-25 10:46:44.227  1016  1549 D SettingsProvider: selectionArgs: 1002
08-25 10:46:44.227  1016  1549 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:44.227  1016  1549 D SettingsProvider: ret = -1
,08-25 10:46:44.227  1016  1134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-25 10:46:44.227  1016  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 10:46:44.227  1016  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:44.227  1016  1134 D SettingsProvider: selectionArgs: false,
08-25 10:46:44.227  1016  1134 D SettingsProvider: selectionArgs: 1002
,08-25 10:46:44.227  1016  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 10:46:44.227  1016  1134 D SettingsProvider: ret = -1
08-25 10:46:44.227  1016  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService,
08-25 10:46:44.227  1016  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 10:46:44.227  1016  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:44.227  1016  1481 D SettingsProvider: selectionArgs: false
08-25 10:46:44.227  1016  1481 D SettingsProvider: selectionArgs: 1002,
08-25 10:46:44.227  1016  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:44.227  1016  1481 D SettingsProvider: ret = -1
,08-25 10:46:44.247  7377  7377 D BluetoothAdapterState: make
,08-25 10:46:44.257  7377  7377 I bluedroid: init
,08-25 10:46:44.257  7377  7392 I BluetoothAdapterState: Entering OffState
,08-25 10:46:44.257  7377  7377 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
08-25 10:46:44.257  7377  7377 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 10:46:44.257  7377  7377 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 10:46:44.257  7377  7377 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 10:46:44.257  7377  7377 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-25 10:46:44.257  7377  7377 I bluedroid: get_profile_interface socket
08-25 10:46:44.257  7377  7377 I bluedroid: get_profile_interface map_client
08-25 10:46:44.257  7377  7395 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-25 10:46:44.267  7377  7377 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
08-25 10:46:44.267  7377  7395 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-25 10:46:44.267  7377  7395 E BluetoothServiceJni: populateRssiValuesNative
08-25 10:46:44.267  7377  7395 I bluedroid: getModelRssiValues
,08-25 10:46:44.267  7377  7395 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-25 10:46:44.267  7377  7395 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-25 10:46:44.267  7377  7395 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-25 10:46:44.267  1016  1016 D SettingsProvider: name = bluetooth_name
,08-25 10:46:44.277  7377  7377 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 10:46:44.277  1016  1134 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 10:46:44.277  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 10:46:44.277  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:44.277  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:44.277  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:44.277  7377  7385 I bluedroid: config_hci_snoop_log,
,08-25 10:46:44.287  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-25 10:46:44.287  1016  1045 D BluetoothManagerService: Ble is always on enable gatt
08-25 10:46:44.287  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-25 10:46:44.287  1016  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
08-25 10:46:44.287  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-25 10:46:44.287  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 10:46:44.287  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 10:46:44.287  7377  7377 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-25 10:46:44.297  1016  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-25 10:46:44.297  7377  7392 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-25 10:46:44.297  7377  7392 D BluetoothAdapterProperties: Setting state to 11
08-25 10:46:44.297  7377  7392 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 10:46:44.297  7377  7392 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 10:46:44.297  7377  7392 D BluetoothAdapterService: updateAdapterState state is 11
08-25 10:46:44.297  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-25 10:46:44.297  7377  7392 D BluetoothAdapterService: Autoconnection is available 
,08-25 10:46:44.297  7377  7392 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-25 10:46:44.307  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:46:44.307  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
,08-25 10:46:44.307  7377  7392 D BluetoothSecureManager: getInstant: null
,08-25 10:46:44.307  7377  7392 D BluetoothSecureManager: calling getMethod for getService
08-25 10:46:44.307  7377  7392 D BluetoothSecureManager: calling getService
,08-25 10:46:44.307  7377  7392 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@10f0f7c6
,08-25 10:46:44.307  1016  1371 D BluetoothSecureManagerService: isSecureModeEnabled
08-25 10:46:44.307  1016  1371 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-25 10:46:44.307  7377  7392 D BtConfig.SecureMode: isSecureModeOn:false
08-25 10:46:44.307  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-25 10:46:44.307  7377  7392 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-25 10:46:44.307  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-25 10:46:44.307  7377  7392 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-25 10:46:44.307  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-25 10:46:44.317  7377  7392 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-25 10:46:44.317  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-25 10:46:44.317  7377  7392 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-25 10:46:44.317  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-25 10:46:44.317  7377  7392 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-25 10:46:44.317  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-25 10:46:44.317  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 10:46:44.317  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:44.317  1176  1176 D BluetoothTile:  getBluetoothState : 11
,08-25 10:46:44.317  7377  7392 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-25 10:46:44.317  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:44.317  7377  7392 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-25 10:46:44.317  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-25 10:46:44.317  7377  7392 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,08-25 10:46:44.317  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 10:46:44.327  1176  1728 D BluetoothTile:  handleUpdatestate:false name:null
08-25 10:46:44.327  1176  1728 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 10:46:44.327  7377  7392 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 10:46:44.327  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-25 10:46:44.327  1875  1875 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 10:46:44.327  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:46:44.327  7377  7392 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,08-25 10:46:44.327  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-25 10:46:44.337  7377  7392 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,08-25 10:46:44.337  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-25 10:46:44.337  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:44.337  7377  7392 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-25 10:46:44.337  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:44.347  1016  1371 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 10:46:44.347  1016  1216 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 10:46:44.347  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 10:46:44.347  7377  7392 D BluetoothBondStateMachine: make
,08-25 10:46:44.357  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-25 10:46:44.357  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-25 10:46:44.357  7377  7392 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-25 10:46:44.357  7377  7397 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 10:46:44.487  1016  1028 I art     : Explicit concurrent mark sweep GC freed 74532(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.418ms total 165.323ms
,08-25 10:46:44.487  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:44.487  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-25 10:46:44.497  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:44.497  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:44.497  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 10:46:44.497  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 10:46:44.497  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-25 10:46:44.497  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-25 10:46:44.497  7377  7392 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-25 10:46:44.497  1016  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:44.497  7377  7377 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 10:46:44.497  1016  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-25 10:46:44.497  1016  1483 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:44.497  7377  7377 D BtGatt.GattService: Received start request. Starting profile...
08-25 10:46:44.497  7377  7377 D BtGatt.GattService: start()
08-25 10:46:44.497  7377  7377 D BtGatt.GattService: start()
08-25 10:46:44.497  7377  7377 I bluedroid: get_profile_interface gatt
,08-25 10:46:44.497  1016  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:44.497  1016  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:44.497  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:44.497  7377  7377 D BtGatt.AdvertiseManager: advertise manager created
,08-25 10:46:44.497  1016  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 10:46:44.497  1016  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 10:46:44.497  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-25 10:46:44.497  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 10:46:44.497  7377  7392 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-25 10:46:44.497  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:44.497  1016  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:44.497  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:44.507  1016  1371 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 10:46:44.507  1016  1371 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 10:46:44.507  1016  1371 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:44.507  1016  1371 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:44.507  1016  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 10:46:44.507  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:44.507  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-25 10:46:44.517  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-25 10:46:44.517  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 10:46:44.517  7377  7392 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-25 10:46:44.517  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-25 10:46:44.527  7377  7377 D BtGatt.GattService: mStartError = false
08-25 10:46:44.527  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:44.527  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:44.527  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:44.527  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:44.527  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:44.537  7377  7377 D HeadsetService: Received start request. Starting profile...,
08-25 10:46:44.537  7377  7377 D HeadsetService: start()
08-25 10:46:44.537  7377  7377 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 10:46:44.537  7377  7377 D HeadsetStateMachine: make
,08-25 10:46:44.537  7377  7377 E HeadsetStateMachine: # of Max HF connection is 2
,08-25 10:46:44.537  7402  7402 E Zygote  : MountEmulatedStorage()
,08-25 10:46:44.547  7402  7402 E Zygote  : v2
08-25 10:46:44.547  7402  7402 I libpersona: KNOX_SDCARD checking this for 10055
08-25 10:46:44.547  7402  7402 I libpersona: KNOX_SDCARD not a persona
,08-25 10:46:44.547  1016  1029 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7402 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-25 10:46:44.547  1016  1549 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:44.547  1016  1549 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-25 10:46:44.547  1016  1549 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:44.547  1016  1549 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:44.547  1016  1549 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 10:46:44.547  7402  7402 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:44.547  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-25 10:46:44.547  1016  1481 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-25 10:46:44.547  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-25 10:46:44.547  1016  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-25 10:46:44.547  7377  7392 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-25 10:46:44.557  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:44.557  1016  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:44.557  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-25 10:46:44.557  7402  7402 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 10:46:44.557  1016  1550 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:44.557  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-25 10:46:44.557  7402  7402 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 10:46:44.557  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:44.557  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:44.557  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 10:46:44.557  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-25 10:46:44.557  1016  1481 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-25 10:46:44.557  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 10:46:44.557  1016  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-25 10:46:44.557  7377  7392 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-25 10:46:44.557  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:44.557  1016  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:44.557  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-25 10:46:44.557  7377  7377 I bluedroid: get_profile_interface handsfree
08-25 10:46:44.557  1016  1382 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 10:46:44.557  1016  1382 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 10:46:44.557  1016  1382 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:44.557  1016  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:44.557  1016  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:44.567   305   305 I art     : Explicit concurrent mark sweep GC freed 8699(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 996us total 21.710ms
,08-25 10:46:44.577  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-25 10:46:44.577  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 10:46:44.577  7377  7392 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:44.577  1016  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:44.577  1016  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 10:46:44.577  1016  1216 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:44.577  1016  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:44.577  1016  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:44.577  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-25 10:46:44.577  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 10:46:44.577  7377  7392 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-25 10:46:44.587  1016  1371 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:44.587  1016  1371 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 10:46:44.587   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 17.457ms
08-25 10:46:44.587  1016  1371 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:44.587  1016  1371 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:44.587  1016  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:44.587  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 10:46:44.587  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 10:46:44.587  7377  7392 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 10:46:44.587  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 10:46:44.587  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 10:46:44.587  7377  7392 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-25 10:46:44.587  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 10:46:44.587  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-25 10:46:44.587  7377  7392 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 10:46:44.587  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-25 10:46:44.587  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 10:46:44.587  7377  7392 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-25 10:46:44.587  7377  7392 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-25 10:46:44.587  7402  7402 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 10:46:44.587  7402  7402 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:44.597  7377  7377 I DualScoManager: Instantiating Dual Sco Manager
08-25 10:46:44.597  7377  7377 I DualScoManager: Set HeadsetServiceHelper
,08-25 10:46:44.597  7377  7377 D BluetoothAtMessage: createCMTIContentObservers
,08-25 10:46:44.597  1016  1134 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-25 10:46:44.597  1016  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:44.597  1016  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:44.597  1016  1134 D SettingsProvider: selectionArgs: false
08-25 10:46:44.597  1016  1134 D SettingsProvider: selectionArgs: 1002
08-25 10:46:44.597  1016  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:44.597  1016  1134 D SettingsProvider: ret = -1
08-25 10:46:44.597  7377  7401 D HeadsetStateMachine: Enter Disconnected: -2
,08-25 10:46:44.597  7377  7377 D HeadsetService: mStartError = false
08-25 10:46:44.597  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:44.597  7377  7401 D HeadsetStateMachine: Clear mHeadsetBrsf
08-25 10:46:44.597  7377  7401 D HeadsetStateMachine: map size, before remove : 0
08-25 10:46:44.607  7377  7401 D HeadsetStateMachine: map size, after remove: 0
,08-25 10:46:44.607   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.658ms
,08-25 10:46:44.607  7377  7377 D A2dpService: Received start request. Starting profile...
08-25 10:46:44.607  7377  7377 D A2dpService: start()
,08-25 10:46:44.607  7377  7377 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 10:46:44.607  7377  7377 I bluedroid: get_profile_interface avrcp
,08-25 10:46:44.617  7377  7377 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 10:46:44.617  7377  7377 D Avrcp   : Initialize Media Controller
08-25 10:46:44.617  7377  7377 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-25 10:46:44.617  7377  7377 E Avrcp   : getActiveSessions
08-25 10:46:44.617  7377  7377 D Avrcp   : pick active media Controller
08-25 10:46:44.617  7377  7377 D Avrcp   : Get the active Media Controller 
,08-25 10:46:44.627  7402  7402 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
08-25 10:46:44.627  7377  7377 I Avrcp   :  Updating now playing list upon AVRCP Start
08-25 10:46:44.627  7377  7420 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-25 10:46:44.637  7377  7377 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 10:46:44.637  7377  7377 D A2dpStateMachine: make
,08-25 10:46:44.637  7377  7377 I bluedroid: get_profile_interface a2dp
08-25 10:46:44.637  7377  7422 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-25 10:46:44.637  7377  7377 E bt-btif : warning : media task started media_task_refcnt 1 
,08-25 10:46:44.637  7377  7377 D A2dpService: mStartError = false
08-25 10:46:44.637  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:44.637  7377  7377 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-25 10:46:44.637  7377  7421 D A2dpStateMachine: Enter Disconnected: -2
08-25 10:46:44.637  7377  7377 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 10:46:44.637  7377  7377 D HidService: Received start request. Starting profile...
08-25 10:46:44.637  7377  7377 D HidService: start()
08-25 10:46:44.637  7377  7377 I bluedroid: get_profile_interface hidhost
08-25 10:46:44.637  7377  7377 D HidService: setHidService(): set to: null
08-25 10:46:44.637  7377  7377 D HidService: mStartError = false
08-25 10:46:44.637  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:44.637  7377  7377 D HeadsetStateMachine: Try to query the phonestate on bind
,08-25 10:46:44.647  1423  6931 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 10:46:44.647  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-25 10:46:44.647  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-25 10:46:44.647  1423  6931 I Telecom : BluetoothPhoneService: Result of Message : true
,08-25 10:46:44.647  7377  7377 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 10:46:44.647  7377  7377 D HealthService: Received start request. Starting profile...
08-25 10:46:44.647  7377  7377 D HealthService: start()
,08-25 10:46:44.647  7377  7377 I bluedroid: get_profile_interface health
08-25 10:46:44.647  7377  7377 D HealthService: mStartError = false
08-25 10:46:44.647  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:44.647  7377  7377 D HeadsetStateMachine: Proxy object connected
,08-25 10:46:44.647  7377  7377 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-25 10:46:44.647  7377  7377 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 10:46:44.647  7377  7401 D HeadsetStateMachine: Disconnected process message: 11
,08-25 10:46:44.657  7377  7377 D PanService: Received start request. Starting profile...
08-25 10:46:44.657  7377  7377 D PanService: start()
08-25 10:46:44.657  7377  7377 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 10:46:44.657  7377  7377 I bluedroid: get_profile_interface pan
,08-25 10:46:44.657  7377  7377 D PanService: mStartError = false
08-25 10:46:44.657  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:44.657  7402  7402 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-25 10:46:44.657  7402  7402 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-25 10:46:44.657  7402  7402 D UserAnalysis: Create SecureDbHelper
,08-25 10:46:44.657  7377  7377 D BluetoothMapService: Received start request. Starting profile...,
08-25 10:46:44.657  7377  7377 D BluetoothMapService: start()
,08-25 10:46:44.657  7377  7377 D BluetoothMapService: mStartError = false
08-25 10:46:44.657  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
08-25 10:46:44.657  7377  7377 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-25 10:46:44.657  7377  7377 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-25 10:46:44.657  7377  7401 D HeadsetStateMachine: Disconnected process message: 18
08-25 10:46:44.657  7377  7377 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
08-25 10:46:44.657  7377  7420 D BluetoothMediaBrowser: no now playing list
08-25 10:46:44.657  7377  7420 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-25 10:46:44.657  7377  7377 D SapService: Received start request. Starting profile...,
08-25 10:46:44.657  7377  7377 D SapService: start()
08-25 10:46:44.657  7377  7377 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-25 10:46:44.657  7377  7377 I bluedroid: get_profile_interface sap
08-25 10:46:44.657  7377  7377 D SapService: mStartError = false
08-25 10:46:44.657  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:44.657  7377  7377 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-25 10:46:44.667  7377  7377 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-25 10:46:44.667  7377  7377 D BluetoothA2dp: Proxy object connected
08-25 10:46:44.667  7377  7377 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-25 10:46:44.667  7377  7401 D HeadsetStateMachine: Disconnected process message: 10
,08-25 10:46:44.667  7377  7377 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-25 10:46:44.667  7377  7401 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 10:46:44.667  7377  7377 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-25 10:46:44.667  7377  7401 D HeadsetStateMachine: Disconnected process message: 11
08-25 10:46:44.667  7377  7377 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-25 10:46:44.667  7377  7377 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-25 10:46:44.667  7402  7402 D IntelligenceServiceApplication: onCreate()
,08-25 10:46:44.667  1016  1550 I ActivityManager: Killing 7061:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-25 10:46:44.677  7402  7402 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-25 10:46:44.677  1016  1371 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-25 10:46:44.677  7402  7402 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-25 10:46:44.687  7402  7402 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-25 10:46:44.697  7377  7377 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-25 10:46:44.697  7377  7377 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-25 10:46:44.697  1016  1380 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-25 10:46:44.707  1016  1380 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:44.707  1016  1380 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:44.707  1016  1380 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:44.707  1016  1380 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:44.717  7427  7427 E Zygote  : MountEmulatedStorage(),
,08-25 10:46:44.717  7427  7427 E Zygote  : v2
08-25 10:46:44.717  7427  7427 I libpersona: KNOX_SDCARD checking this for 10105
08-25 10:46:44.717  7427  7427 I libpersona: KNOX_SDCARD not a persona
08-25 10:46:44.717  7427  7427 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 10:46:44.717  1016  1380 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7427 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-25 10:46:44.717  7427  7427 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 10:46:44.727  7427  7427 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-25 10:46:44.727  7377  7392 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-25 10:46:44.727  7377  7392 I bluedroid: enable
08-25 10:46:44.727  7377  7392 I bt_hci_bdroid: init
08-25 10:46:44.727  7377  7434 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-25 10:46:44.727  7377  7392 I bt_vendor: bt-vendor : init
08-25 10:46:44.727  7377  7392 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 10:46:44.727  7377  7392 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 10:46:44.727  7377  7392 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-25 10:46:44.727  7377  7392 D bt_userial_mct: userial_init
,08-25 10:46:44.727  7377  7392 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-25 10:46:44.727  7377  7392 I bt_vendor: Starting hciattach daemon
08-25 10:46:44.737  7377  7392 I bt_vendor: try to set false
,08-25 10:46:44.737  7377  7392 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 10:46:44.737  7377  7392 I bt_vendor: Starting hciattach daemon
08-25 10:46:44.737  7377  7392 I bt_vendor: try to set true
,08-25 10:46:44.757  7446  7446 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 10:46:44.757  7427  7427 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-25 10:46:44.757  7427  7427 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:44.807  7452  7452 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-25 10:46:44.817  7453  7453 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-25 10:46:44.837  7455  7455 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-25 10:46:44.837  7458  7458 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-25 10:46:44.847  7459  7459 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 10:46:44.857  7460  7460 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-25 10:46:44.867   289   289 E SMD     : DCD OFF,
,08-25 10:46:44.887   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 10:46:44.887   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 10:46:44.897  7427  7464 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-25 10:46:44.897   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-25 10:46:44.897   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 10:46:44.897  7427  7464 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-25 10:46:45.037  7427  7427 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 10:46:45.037  7427  7427 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 10:46:45.037  7427  7427 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-25 10:46:45.047  7427  7427 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 10:46:45.047  7427  7427 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 10:46:45.047  7427  7427 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 10:46:45.047  7427  7427 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.q.k.d(PG:583)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.q.e.b(PG:170)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 10:46:45.047  7427  7427 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 10:46:45.047  7427  7427 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.io.File.exists(File.java:363)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 10:46:45.047  1016  1134 I ActivityManager: Killing 7051:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
08-25 10:46:45.047  7427  7427 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-25 10:46:45.047  7427  7427 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-25 10:46:45.047  1954  1954 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-25 10:46:45.057  1954  1954 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 10:46:45.107  7427  7468 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-25 10:46:45.117  7475  7475 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,08-25 10:46:45.127  7476  7476 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-25 10:46:45.147  1016  1134 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:45.147  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:45.147  1016  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:45.147  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-25 10:46:45.197  7377  7392 I bt_vendor: bluetooth satus is on
,08-25 10:46:45.197  7377  7438 D bt_userial_mct: userial_open(port:0)
08-25 10:46:45.197  7377  7438 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 10:46:45.197  7377  7438 I bt_vendor: Done intiailizing UART
,08-25 10:46:45.197  7377  7438 I bt_vendor: Done intiailizing UART
,08-25 10:46:45.197  7377  7438 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
,08-25 10:46:45.197  7377  7438 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-25 10:46:45.197  7377  7434 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 10:46:45.197  7377  7434 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 10:46:45.197  7377  7434 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-25 10:46:45.197  7377  7434 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 10:46:45.197  7377  7434 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-25 10:46:45.197  7377  7434 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 10:46:45.197  7377  7434 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 10:46:45.197  7377  7434 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 10:46:45.197  7377  7434 I         : BTE_InitTraceLevels -- TRC_GAP
,08-25 10:46:45.197  7377  7434 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 10:46:45.197  7377  7434 I         : BTE_InitTraceLevels -- TRC_SAP
08-25 10:46:45.197  7377  7434 I         : BTE_InitTraceLevels -- TRC_SDP
,08-25 10:46:45.197  7377  7434 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 10:46:45.197  7377  7434 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 10:46:45.197  7377  7434 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-25 10:46:45.207  7377  7480 D bt_userial_mct: Entering userial_read_thread()
08-25 10:46:45.207  7377  7434 I         : BTE_InitTraceLevels -- TRC_BTIF
08-25 10:46:45.207  7377  7434 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-25 10:46:45.297  7377  7434 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-25 10:46:45.297  7377  7434 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41c6ed1 
,08-25 10:46:45.297  7377  7434 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41c6ed1 
,08-25 10:46:45.317  7377  7395 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-25 10:46:45.317  7377  7395 E bt-btif : Calling BTA_HhEnable
,08-25 10:46:45.317  7377  7395 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-25 10:46:45.317  7377  7395 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-25 10:46:45.317  7377  7395 E BluetoothServiceJni: populateRssiValuesNative
,08-25 10:46:45.317  7377  7395 I bluedroid: getModelRssiValues
,08-25 10:46:45.327  7377  7395 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-25 10:46:45.327  7377  7395 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-25 10:46:45.327  1016  1016 D SettingsProvider: name = bluetooth_name
,08-25 10:46:45.327  7377  7395 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-25 10:46:45.337  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:45.337  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:45.337  7377  7395 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 10:46:45.337  7377  7395 D BluetoothAdapterProperties: Scan Mode:20
08-25 10:46:45.337  7377  7395 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 10:46:45.337  7377  7395 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-25 10:46:45.337  7377  7395 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-25 10:46:45.337  7377  7395 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-25 10:46:45.337  7377  7395 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-25 10:46:45.337  7377  7395 E bt-btif : btif_sock_init: !vhci_init
,08-25 10:46:45.337  7377  7395 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-25 10:46:45.347  7377  7480 E bt_mct  : hci lib postload completed
,08-25 10:46:45.347  7377  7395 D IOP_DB_BT: db_open: db_open : handle 3028381712l, read 13894 bytes onto local cache
,08-25 10:46:45.347  7377  7395 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-25 10:46:45.347  7377  7395 D IOP_DB_BT: db_query: result 1
,08-25 10:46:45.347  7377  7395 I         : iop_db_open: iop_db_open status 0
,08-25 10:46:45.347  7377  7395 D bte_conf: Device ID record 1 : primary
08-25 10:46:45.347  7377  7395 D bte_conf:   vendorId            = 0075
08-25 10:46:45.347  7377  7395 D bte_conf:   vendorIdSource      = 0001
08-25 10:46:45.347  7377  7395 D bte_conf:   product             = 0100
08-25 10:46:45.347  7377  7395 D bte_conf:   version             = 0200
08-25 10:46:45.347  7377  7395 D bte_conf:   clientExecutableURL = 
08-25 10:46:45.347  7377  7395 D bte_conf:   serviceDescription  = 
08-25 10:46:45.347  7377  7395 D bte_conf:   documentationURL    = 
08-25 10:46:45.347  7377  7395 D bte_conf: bte_load_did_conf no section named DID2.
08-25 10:46:45.347  7377  7395 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 10:46:45.347  7377  7392 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-25 10:46:45.347  7377  7392 D BluetoothAdapterProperties: ScanMode =  20
,08-25 10:46:45.347  7377  7392 D BluetoothAdapterProperties: State =  11,
08-25 10:46:45.357  1016  1382 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-25 10:46:45.357  7377  7392 D BluetoothAdapterProperties: Setting state to 12
08-25 10:46:45.357  7377  7392 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-25 10:46:45.357  7377  7395 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 10:46:45.357  7377  7395 D BluetoothAdapterProperties: Scan Mode:21
08-25 10:46:45.357  7377  7395 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 10:46:45.357  1016  1485 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-25 10:46:45.367  1016  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 10:46:45.367  1016  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 10:46:45.367  1016  1485 D SettingsProvider: selectionArgs: false
08-25 10:46:45.367  1016  1485 D SettingsProvider: selectionArgs: 1002
,08-25 10:46:45.367  1016  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:45.367  1016  1485 D SettingsProvider: ret = -1
08-25 10:46:45.367  7377  7392 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-25 10:46:45.367  7377  7392 D BluetoothAdapterService: updateAdapterState state is 12
,08-25 10:46:45.367  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:45.367  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:45.367  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:45.367  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:45.367  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:45.367  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:45.367  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:45.367  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:45.367  1016  1549 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:45.367  1016  1549 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 10:46:45.367  1016  1549 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:45.367  1016  1549 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 10:46:45.367  1016  1549 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:45.387  7377  7392 D BluetoothAdapterService: Autoconnection is available 
08-25 10:46:45.387  7377  7392 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-25 10:46:45.387  7377  7392 D BluetoothAdapterService: starting service from this receiver
,08-25 10:46:45.387  1315  1338 D BluetoothPan: Binding service...
,08-25 10:46:45.387  1016  1550 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 10:46:45.387  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-25 10:46:45.387  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:45.387  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:45.387  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:45.397  7377  7392 I BluetoothAdapterState: Entering On State from state = 11
,08-25 10:46:45.397  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-25 10:46:45.397  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 10:46:45.397  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:45.397  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:45.397  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:45.397  7377  7377 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-25 10:46:45.397  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:45.397  1315  1325 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 10:46:45.397  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-25 10:46:45.397  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 10:46:45.407  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:45.407  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:45.407  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:45.407  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:45.407  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:45.407  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:45.407  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:45.407  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:45.407  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:45.407  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:45.407  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:45.407  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:45.407  1315  1338 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 10:46:45.407  1315  1338 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 10:46:45.407  7377  7387 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 10:46:45.407  7427  7437 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 10:46:45.407  7427  7437 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 10:46:45.417  1423  1459 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 10:46:45.417  1423  1459 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 10:46:45.417  7377  7396 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 10:46:45.417  7377  7396 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 10:46:45.417  1315  1325 D Bluetoothsap: onBluetoothStateChange: up=true
,08-25 10:46:45.417  7377  7377 I BluetoothPbapService: Handler(): got msg=1
08-25 10:46:45.417  1315  1325 D Bluetoothsap: Binding service...
,08-25 10:46:45.417  1016  1382 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-25 10:46:45.417  7377  7484 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-25 10:46:45.427  1315  1315 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 10:46:45.427  1315  1325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
08-25 10:46:45.427  1315  1315 D PanProfile: Bluetooth service connected
,08-25 10:46:45.427  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-25 10:46:45.427  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 10:46:45.427  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:45.427  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:45.427  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:45.427  1315  1325 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-25 10:46:45.427  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 10:46:45.427  1016  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 10:46:45.427  1315  1338 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 10:46:45.427  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-25 10:46:45.427  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 10:46:45.427  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:45.427  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:45.427  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:45.427  1016  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 10:46:45.427  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 10:46:45.427  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 10:46:45.427  1315  1315 D BluetoothMap: Proxy object connected
08-25 10:46:45.427  1016  1045 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 10:46:45.427  1016  1045 D BluetoothPan: Binding service...
08-25 10:46:45.427  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-25 10:46:45.427  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 10:46:45.437  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 10:46:45.437  7377  7484 D BluetoothSocket: bindListen(): myUserId = 0
08-25 10:46:45.437  7377  7484 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 10:46:45.437  1315  1315 D MapProfile: Bluetooth service connected
08-25 10:46:45.437  1315  1315 D BluetoothMap: getConnectedDevices()
,08-25 10:46:45.437  1423  1463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 10:46:45.437  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 10:46:45.437  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 10:46:45.437  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:45.437  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 10:46:45.437  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:45.437  7377  7484 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-25 10:46:45.437  7377  7484 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 10:46:45.437  7377  7484 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 10:46:45.437  7377  7484 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@abe297b
08-25 10:46:45.437  1315  1315 D Bluetoothsap: BluetoothSAP Proxy object connected
08-25 10:46:45.437  1315  1315 D SapProfile: Bluetooth service connected
08-25 10:46:45.437  1315  1315 D Bluetoothsap: getConnectedDevices()
,08-25 10:46:45.437  1423  1463 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 10:46:45.437  7377  7484 D BluetoothSocket: channel: 19
08-25 10:46:45.437  7377  7484 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-25 10:46:45.437  1954  7352 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 10:46:45.437  1954  7352 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 10:46:45.437  1423  1459 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 10:46:45.437  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 10:46:45.437  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 10:46:45.437  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:45.437  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:45.437  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-25 10:46:45.437  1315  1315 D BluetoothPbap: Proxy object connected
08-25 10:46:45.437  1315  1315 D PbapServerProfile: Bluetooth service connected
,08-25 10:46:45.447  1423  1459 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 10:46:45.447  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 10:46:45.447  1016  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-25 10:46:45.447  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 10:46:45.447  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-25 10:46:45.447  1016  1016 D BluetoothA2dp: Proxy object connected
,08-25 10:46:45.447  1315  7485 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 10:46:45.447  1315  7485 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 10:46:45.447  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 10:46:45.447  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 10:46:45.447  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:45.447  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:45.447  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:45.447  1315  1315 D BluetoothA2dp: Proxy object connected
,08-25 10:46:45.447  1315  1315 D A2dpProfile: Bluetooth service connected
08-25 10:46:45.447  1176  1982 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 10:46:45.447  1176  1982 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 10:46:45.447  6741  6750 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 10:46:45.447  6741  6750 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 10:46:45.447  1443  1474 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 10:46:45.447  1016  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 10:46:45.447  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 10:46:45.457  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:45.457  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:45.457  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:45.457  1443  1474 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 10:46:45.457  1423  1463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 10:46:45.457  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 10:46:45.457  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 10:46:45.457  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:45.457  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:45.457  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:45.457  1423  1463 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 10:46:45.457  1315  1325 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 10:46:45.457  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 10:46:45.457  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 10:46:45.457  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:45.457  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:45.457  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:45.467  1315  1315 D HeadsetProfile: Bluetooth service connected
08-25 10:46:45.467  1315  1325 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 10:46:45.467  1315  7485 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 10:46:45.467  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-25 10:46:45.467  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 10:46:45.467  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:45.467  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:45.467  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:45.467  1430  1453 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 10:46:45.467  1430  1453 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 10:46:45.467  1443  1652 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 10:46:45.467  1443  1652 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 10:46:45.467  1315  1315 D BluetoothInputDevice: Proxy object connected
08-25 10:46:45.467  1315  1315 D HidProfile: Bluetooth service connected
08-25 10:46:45.467  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-25 10:46:45.467  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-25 10:46:45.467  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:46:45.467  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
,08-25 10:46:45.477  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 10:46:45.477  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-25 10:46:45.477  1423  1423 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2cf1d167, true,
08-25 10:46:45.477  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 10:46:45.477  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:45.477  1176  1176 D BluetoothTile:  getBluetoothState : 12
,08-25 10:46:45.477  1423  1423 D BluetoothHeadset: registerMessageListener
08-25 10:46:45.477  1875  1875 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 10:46:45.477  1176  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 10:46:45.487  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:46:45.487  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:45.487  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 10:46:45.487  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 10:46:45.487  7377  7387 D HeadsetService: registerMessageListener
,08-25 10:46:45.487  7377  7387 D HeadsetService: registerMessageListener
08-25 10:46:45.487  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:45.487  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 10:46:45.487  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-25 10:46:45.487  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-25 10:46:45.487  7377  7401 D HeadsetStateMachine: Disconnected process message: 70
08-25 10:46:45.497  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-25 10:46:45.497  7377  7401 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@13bd5398
08-25 10:46:45.497  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 10:46:45.497  1176  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 10:46:45.497  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-25 10:46:45.497  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-25 10:46:45.497  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-25 10:46:45.497  1016  1134 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 10:46:45.497  1016  1380 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-25 10:46:45.497  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 10:46:45.497  1315  1315 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-25 10:46:45.497  1176  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 10:46:45.497  1315  1315 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-25 10:46:45.497  1315  1315 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-25 10:46:45.497  1315  1315 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-25 10:46:45.507  7377  7401 D HeadsetStateMachine: Disconnected process message: 9
,08-25 10:46:45.507  7377  7401 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-25 10:46:45.507  7377  7487 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-25 10:46:45.517   284   992 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-25 10:46:45.517   284   992 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-25 10:46:45.517   284   992 V voice   : voice_set_parameters: exit with code(-2)
08-25 10:46:45.517   284   992 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-25 10:46:45.517   284   992 V msm8974_platform: platform_set_parameters: exit with code(-2)
,08-25 10:46:45.517   284   992 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-25 10:46:45.517   284   992 V audio_hw_primary: adev_set_parameters: exit
,08-25 10:46:45.517  7377  7401 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-25 10:46:45.517  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 10:46:45.517  1016  1028 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-25 10:46:45.517  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 10:46:45.517  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:45.517  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 10:46:45.517  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 10:46:45.517  7377  7487 D BluetoothSocket: bindListen(): myUserId = 0
08-25 10:46:45.517  7377  7487 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 10:46:45.517  7377  7487 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-25 10:46:45.517  7377  7487 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 10:46:45.517  7377  7487 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 10:46:45.517  7377  7487 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16a517f1
,08-25 10:46:45.527  7377  7487 D BluetoothSocket: channel: 5
,08-25 10:46:45.527  1315  1315 D DockEventReceiver: finishStartingService: stopping service
,08-25 10:46:45.527  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 10:46:45.537  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:45.537  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-25 10:46:45.537  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:45.537  7377  7377 D BtConfig.SecureMode: isSecureModeOn:false
,08-25 10:46:45.547  1016  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 10:46:45.547  1016  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-25 10:46:45.547  1016  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:45.547  1016  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:45.547  1016  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:45.557  1954  1954 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 10:46:45.557  1016  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 10:46:45.557  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-25 10:46:45.557  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:45.557  1016  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:45.557  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:45.577  1016  1481 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-25 10:46:45.577  1954  7494 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-25 10:46:45.577  1954  1954 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 10:46:45.587  1016  1550 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:45.587  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:45.587  1016  1550 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:45.587  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:45.597  7377  7497 D BluetoothSocket: bindListen(): myUserId = 0
08-25 10:46:45.597  7377  7497 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 10:46:45.597  1016  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:45.597  1016  1483 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:45.597  1016  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:45.597  1016  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:45.607  7377  7497 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-25 10:46:45.607  7377  7497 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 10:46:45.607  7377  7497 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 10:46:45.607  7377  7497 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19f24cf3
,08-25 10:46:45.607  7377  7497 D BluetoothSocket: channel: 12
,08-25 10:46:45.607  7377  7497 I BtOppRfcommListener: Accept thread started.
,08-25 10:46:45.617  1954  7494 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-25 10:46:47.067  6741  6794 D BluetoothAdapter: disable()
,08-25 10:46:47.067  1016  1550 D SettingsProvider: name = bluetooth_on
,08-25 10:46:47.097  7377  7392 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
08-25 10:46:47.097  1016  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:47.097  7377  7392 D BluetoothAdapterProperties: Setting state to 13,
08-25 10:46:47.097  1016  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-25 10:46:47.097  7377  7392 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13,
08-25 10:46:47.097  7377  7392 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 10:46:47.097  7377  7392 D BluetoothAdapterService: updateAdapterState state is 13,
08-25 10:46:47.097  1016  1485 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:47.097  1016  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:47.097  1016  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:47.097  7377  7377 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-25 10:46:47.107  7377  7392 D BluetoothAdapterService: Autoconnection is available 
08-25 10:46:47.107  7377  7392 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-25 10:46:47.107  7377  7392 D BluetoothAdapterService: terminating service from this receiver
,08-25 10:46:47.107  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-25 10:46:47.107  7377  7377 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@168efdb0, channel: 19, state: LISTENING
08-25 10:46:47.107  7377  7377 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@168efdb0, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@abe297b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@124dd429mSocket: android.net.LocalSocket@27e03ae impl:android.net.LocalSocketImpl@3b5ac54f fd:FileDescriptor[74]
08-25 10:46:47.107  7377  7377 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@27e03ae impl:android.net.LocalSocketImpl@3b5ac54f fd:FileDescriptor[74]
,08-25 10:46:47.107  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:47.107  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:47.107  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:47.107  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:47.107  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
,08-25 10:46:47.107  7377  7392 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 10:46:47.107  7377  7392 D BluetoothAdapterProperties: mDiscovering is false
,08-25 10:46:47.107  1016  1549 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-25 10:46:47.117  7377  7392 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-25 10:46:47.117  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-25 10:46:47.127  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:47.127  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-25 10:46:47.127  1875  1875 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-25 10:46:47.127  1176  1176 D BluetoothTile:  getBluetoothState : 13
,08-25 10:46:47.127  1176  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 10:46:47.127  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:46:47.127  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:47.127  1016  1549 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-25 10:46:47.127  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:47.127  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:47.127  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:47.127  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:47.127  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:47.127  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:47.127  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:47.127  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:47.127  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:47.127  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:47.137  1016  1028 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 10:46:47.137  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 10:46:47.137  7377  7395 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-25 10:46:47.137  7377  7395 D BluetoothAdapterProperties: Scan Mode:20
,08-25 10:46:47.137  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:47.137  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:47.137  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:47.137  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:47.137  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:47.137  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 10:46:47.137  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:47.137  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:47.137  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:47.137  1176  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 10:46:47.137  6741  6741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 10:46:47.137  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:47.147  1016  1216 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 10:46:47.147  1016  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 10:46:47.147  1176  1728 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 10:46:47.147  1016  1216 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:47.147  1016  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:47.147  1016  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:47.147  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 10:46:47.147  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:47.147  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:47.147  7377  7392 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 10:46:47.147  7377  7392 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-25 10:46:47.157  1016  1371 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-25 10:46:47.157  1016  1371 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 10:46:47.157  7377  7392 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-25 10:46:47.157  7377  7392 E bt-btif : cmd socket is not created
08-25 10:46:47.157  7377  7497 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-25 10:46:47.157  7377  7392 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-25 10:46:47.157  1016  1371 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:47.157  7377  7434 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-25 10:46:47.157  7377  7434 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-25 10:46:47.157  7377  7434 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 10:46:47.157  7377  7434 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:46:47.157  7377  7434 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 10:46:47.157  1016  1371 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:47.157  1016  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 10:46:47.167  1315  1315 D BluetoothPbap: Proxy object disconnected
08-25 10:46:47.167  1315  1315 D PbapServerProfile: Bluetooth service disconnected
,08-25 10:46:47.167  1315  1315 D DockEventReceiver: finishStartingService: stopping service
,08-25 10:46:47.177  7377  7377 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@17de44dc, channel: 5, state: LISTENING
08-25 10:46:47.177  7377  7377 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@17de44dc, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16a517f1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@c689e5mSocket: android.net.LocalSocket@1eaaacba impl:android.net.LocalSocketImpl@2128676b fd:FileDescriptor[76]
08-25 10:46:47.177  7377  7377 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1eaaacba impl:android.net.LocalSocketImpl@2128676b fd:FileDescriptor[76]
08-25 10:46:47.177  7377  7377 I BtOppRfcommListener: stopping Accept Thread
08-25 10:46:47.177  7377  7377 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1578d2c8, channel: 12, state: LISTENING
08-25 10:46:47.177  7377  7377 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1578d2c8, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19f24cf3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@35adf61mSocket: android.net.LocalSocket@3c6da86 impl:android.net.LocalSocketImpl@3be40f47 fd:FileDescriptor[79]
08-25 10:46:47.177  7377  7377 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3c6da86 impl:android.net.LocalSocketImpl@3be40f47 fd:FileDescriptor[79]
,08-25 10:46:47.177  7377  7497 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-25 10:46:47.177  7377  7377 V BluetoothOppManager: cleanUp...
,08-25 10:46:47.177  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 10:46:47.187  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:47.187  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-25 10:46:47.197  1954  1954 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 10:46:47.207  1954  1954 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 10:46:47.357  7377  7434 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 10:46:47.357  7377  7434 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:46:47.357  7377  7434 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-25 10:46:47.357  7377  7434 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 10:46:47.357  7377  7434 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-25 10:46:47.357  7377  7434 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 10:46:47.357  7377  7434 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 10:46:47.357  7377  7434 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 10:46:47.357  7377  7434 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 10:46:47.357  7377  7434 W bt-btif : ag scb idx 1 not allocated
,08-25 10:46:47.357  7377  7434 W bt-btif : ag scb idx 2 not allocated
08-25 10:46:47.357  7377  7434 E bt-btif : BTA AG is already disabled, ignoring ...
,08-25 10:46:47.357  7377  7480 I bt_userial_mct: exiting userial_read_thread
08-25 10:46:47.357  7377  7480 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 10:46:47.357  7377  7395 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 10:46:47.357  7377  7438 I bt_vendor: hw_epilog_process
,08-25 10:46:47.357  7377  7395 D bt_userial_mct: userial_close
08-25 10:46:47.357  7377  7395 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-25 10:46:47.377  1016  1549 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 10:46:47.377  1016  1549 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-25 10:46:47.377  1016  1549 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-25 10:46:47.377  1016  1549 D BatteryService: stay LED for fully charged
08-25 10:46:47.377  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,08-25 10:46:47.387  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-25 10:46:47.387  1016  1016 I MotionRecognitionService: Plugged
,08-25 10:46:47.387  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-25 10:46:47.387  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false,
,08-25 10:46:47.397  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-25 10:46:47.397  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-25 10:46:47.407  7377  7377 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-25 10:46:47.407  7377  7401 D HeadsetStateMachine: Disconnected process message: 10
,08-25 10:46:47.417  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 10:46:47.417  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 10:46:47.417  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-25 10:46:47.867   289   289 E SMD     : DCD OFF
,08-25 10:46:47.947  7377  7395 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-25 10:46:47.947  7377  7395 I bt_vendor: bluetooth satus is on
,08-25 10:46:47.947  7377  7395 I bt_vendor: bt-vendor : resetting BT status
,08-25 10:46:47.957  7377  7395 I bt_vendor: Starting hciattach daemon
08-25 10:46:47.957  7377  7395 I bt_vendor: try to set false
,08-25 10:46:47.957  7377  7395 I bt_vendor: Starting hciattach daemon,
08-25 10:46:47.957  7377  7395 I bt_vendor: try to set false
,08-25 10:46:47.957  7377  7395 I bt_vendor: cleanup,
08-25 10:46:47.957  7377  7434 I GKI_LINUX: gki_task task_id=0 [BTU] terminating,
,08-25 10:46:47.957  7377  7395 I GKI_LINUX: GKI_exit_task 0 done
,08-25 10:46:47.957  7377  7395 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-25 10:46:47.957  7377  7392 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
,08-25 10:46:47.957  7377  7392 D BtConfig.SecureMode: isSecureModeOn:false
08-25 10:46:47.957  7377  7392 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12,
08-25 10:46:47.967  1016  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:47.967  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-25 10:46:47.967  1016  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0,
08-25 10:46:47.967  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-25 10:46:47.967  7377  7392 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService,
08-25 10:46:47.967  1016  1216 W ActivityManager: userId = 0, bbcId = -10000,
08-25 10:46:47.967  1016  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:47.967  1016  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 10:46:47.967  1016  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 10:46:47.967  1016  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-25 10:46:47.967  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-25 10:46:47.967  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-25 10:46:47.967  7377  7392 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-25 10:46:47.967  7377  7377 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 10:46:47.967  7377  7377 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 10:46:47.967  7377  7377 D BtGatt.GattService: stop()
08-25 10:46:47.967  7377  7377 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 10:46:47.967  1016  1216 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:47.967  1016  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:47.967  1016  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:47.967  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-25 10:46:47.967  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
08-25 10:46:47.967  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 10:46:47.967  7377  7392 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-25 10:46:47.967  1016  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:47.967  1016  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 10:46:47.977  1016  1483 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:47.977  1016  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 10:46:47.977  1016  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:47.977  7377  7377 D HeadsetService: Received stop request...Stopping profile...
08-25 10:46:47.977  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-25 10:46:47.977  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 10:46:47.977  7377  7392 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-25 10:46:47.977  1016  1371 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 10:46:47.977  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:47.977  1016  1371 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 10:46:47.977  1016  1371 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:47.977  1016  1371 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 10:46:47.977  1016  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:47.987  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-25 10:46:47.987  1315  1315 D HeadsetProfile: Bluetooth service disconnected
,08-25 10:46:47.987  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-25 10:46:47.987  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-25 10:46:47.987  7377  7392 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-25 10:46:47.987  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:47.987  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-25 10:46:47.987  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:47.987  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 10:46:47.987  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:47.997  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-25 10:46:47.997  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-25 10:46:47.997  7377  7392 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-25 10:46:47.997  1016  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 10:46:47.997  1016  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 10:46:47.997  1016  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:47.997  1016  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 10:46:47.997  1016  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:47.997  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:47.997  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:47.997  7377  7392 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:48.007  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 10:46:48.007  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 10:46:48.007  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:48.007  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:48.007  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:48.007  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService,
08-25 10:46:48.007  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 10:46:48.007  7377  7392 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-25 10:46:48.007  1016  1382 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-25 10:46:48.007  1016  1382 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 10:46:48.007  1016  1382 W ActivityManager: userId = 0, bbcId = -10000,
08-25 10:46:48.007  1016  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 10:46:48.007  1016  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:48.017  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-25 10:46:48.017  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 10:46:48.017  7377  7392 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 10:46:48.017  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 10:46:48.017  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 10:46:48.017  7377  7392 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 10:46:48.017  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 10:46:48.017  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-25 10:46:48.017  7377  7392 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 10:46:48.017  7377  7392 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-25 10:46:48.017  7377  7392 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 10:46:48.017  7377  7392 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-25 10:46:48.017  7377  7392 D BluetoothAdapterState: Stopping profile services that were post enabled,
,08-25 10:46:48.017  7377  7377 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-25 10:46:48.017  7377  7377 D A2dpService: Received stop request...Stopping profile...
,08-25 10:46:48.017  7377  7421 D A2dpStateMachine: Exit Disconnected: -1
,08-25 10:46:48.017  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:48.017  1016  1016 D BluetoothA2dp: Proxy object disconnected
,08-25 10:46:48.017  7377  7377 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-25 10:46:48.017  7377  7377 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 10:46:48.017  7377  7377 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-25 10:46:48.017  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-25 10:46:48.017  7377  7377 D HidService: Received stop request...Stopping profile...
08-25 10:46:48.017  7377  7377 D HidService: Stopping Bluetooth HidService
08-25 10:46:48.017  7377  7377 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 10:46:48.017  7377  7377 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-25 10:46:48.017  7377  7377 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 10:46:48.017  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:48.027  1315  1315 D BluetoothA2dp: Proxy object disconnected
08-25 10:46:48.027  1315  1315 D A2dpProfile: Bluetooth service disconnected
,08-25 10:46:48.027  1315  1315 D BluetoothInputDevice: Proxy object disconnected
08-25 10:46:48.027  1315  1315 D HidProfile: Bluetooth service disconnected
,08-25 10:46:48.027  7377  7377 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-25 10:46:48.027  7377  7377 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-25 10:46:48.027  7377  7377 D HealthService: Received stop request...Stopping profile...
,08-25 10:46:48.027  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:48.027  7377  7377 D PanService: Received stop request...Stopping profile...
,08-25 10:46:48.027  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:48.027  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 10:46:48.027  7377  7377 D BluetoothMapService: Received stop request...Stopping profile...
,08-25 10:46:48.037  1315  1315 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 10:46:48.037  1315  1315 D PanProfile: Bluetooth service disconnected
,08-25 10:46:48.037  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:48.037  7377  7377 D SapService: Received stop request...Stopping profile...
08-25 10:46:48.037  7377  7377 D SapService: Stopping Bluetooth SapService
08-25 10:46:48.037  7377  7377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae71669
,08-25 10:46:48.037  7377  7377 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-25 10:46:48.037  7377  7377 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 10:46:48.037  7377  7377 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-25 10:46:48.037  7377  7377 D BluetoothA2dp: Proxy object disconnected
08-25 10:46:48.037  7377  7377 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-25 10:46:48.037  7377  7377 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-25 10:46:48.037  7377  7377 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 10:46:48.037  7377  7377 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:48.037  7377  7422 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-25 10:46:48.037  1315  1315 D BluetoothMap: Proxy object disconnected
08-25 10:46:48.037  1315  1315 D MapProfile: Bluetooth service disconnected
08-25 10:46:48.037  1315  1315 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-25 10:46:48.037  1315  1315 D SapProfile: Bluetooth service disconnected
08-25 10:46:48.037  7377  7377 I GKI_LINUX: GKI_exit_task 2 done
08-25 10:46:48.037  7377  7377 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-25 10:46:48.037  7377  7377 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-25 10:46:48.037  7377  7377 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 10:46:48.037  7377  7377 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:48.047  7377  7377 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 10:46:48.047  7377  7377 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 10:46:48.047  7377  7377 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-25 10:46:48.047  7377  7377 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 10:46:48.047  7377  7377 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:48.047  7377  7377 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 10:46:48.047  7377  7377 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-25 10:46:48.047  7377  7377 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-25 10:46:48.047  7377  7377 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-25 10:46:48.047  7377  7377 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-25 10:46:48.047  7377  7377 E BluetoothAdapterService(182916713): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-25 10:46:48.047  7377  7377 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-25 10:46:48.047  7377  7377 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-25 10:46:48.047  7377  7392 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-25 10:46:48.047  7377  7392 D BluetoothAdapterProperties: Setting state to 10
,08-25 10:46:48.047  7377  7392 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 10:46:48.047  7377  7392 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-25 10:46:48.047  7377  7392 D BluetoothAdapterService: updateAdapterState state is 10
,08-25 10:46:48.047  7377  7392 D BluetoothAdapterService: Autoconnection is available 
,08-25 10:46:48.047  7377  7392 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-25 10:46:48.047  7377  7392 I BluetoothAdapterState: Entering OffState
,08-25 10:46:48.057  1315  7485 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 10:46:48.057  1315  1338 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 10:46:48.057  1315  1338 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 10:46:48.057  7377  7385 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 10:46:48.057  7427  7439 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 10:46:48.057  7427  7439 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 10:46:48.057  1423  1463 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 10:46:48.057  1423  1463 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 10:46:48.057  7377  7387 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 10:46:48.057  7377  7387 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 10:46:48.057  1315  1325 D Bluetoothsap: onBluetoothStateChange: up=false
08-25 10:46:48.057  1315  1325 D Bluetoothsap: Unbinding service...
,08-25 10:46:48.057  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 10:46:48.057  1016  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 10:46:48.057  1315  7485 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 10:46:48.067  1954  2134 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 10:46:48.067  1954  2134 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan,
08-25 10:46:48.067  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 10:46:48.067  1315  1338 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 10:46:48.067  1176  1590 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 10:46:48.067  1176  1590 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 10:46:48.067  6741  6750 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 10:46:48.067  6741  6750 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 10:46:48.067  6741  6750 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-25 10:46:48.067  6741  6750 D BluetoothLeAdvertiser: Exit stop advertising
08-25 10:46:48.067  6741  6750 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-25 10:46:48.067  6741  6750 D BluetoothLeScanner: Exiting stopAllScan
,08-25 10:46:48.067  1315  7485 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 10:46:48.067  1430  1453 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-25 10:46:48.067  1430  1453 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 10:46:48.067  1443  1462 D BluetoothAdapter: onBluetoothStateChange: up=false
08-25 10:46:48.067  1443  1462 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-25 10:46:48.077  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-25 10:46:48.077  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-25 10:46:48.087  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:46:48.087  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
08-25 10:46:48.087  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 10:46:48.087  1176  1176 D BluetoothAdapter: 484904329: getState() :  mService = null. Returning STATE_OFF
,08-25 10:46:48.087  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 10:46:48.087  1176  1728 D BluetoothAdapter: 484904329: getState() :  mService = null. Returning STATE_OFF
,08-25 10:46:48.087  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:48.087  1176  1176 D BluetoothTile:  getBluetoothState : 10
,08-25 10:46:48.087  1176  1728 D BluetoothAdapter: 484904329: getState() :  mService = null. Returning STATE_OFF
08-25 10:46:48.087  1176  1176 D BluetoothAdapter: 484904329: getState() :  mService = null. Returning STATE_OFF
08-25 10:46:48.087  1176  1176 D BluetoothAdapter: 484904329: getState() :  mService = null. Returning STATE_OFF
,08-25 10:46:48.087  1016  1481 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 10:46:48.087  1016  1216 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 10:46:48.087  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 10:46:48.097  1875  1875 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 10:46:48.097  7377  7395 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-25 10:46:48.097  7377  7377 I GKI_LINUX: GKI_exit_task 1 done
08-25 10:46:48.097  7377  7377 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-25 10:46:48.097  7377  7377 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 10:46:48.097  1954  2135 D BluetoothAdapter: 590593450: getState() :  mService = null. Returning STATE_OFF
08-25 10:46:48.097  1954  2135 D BluetoothAdapter: 590593450: getState() :  mService = null. Returning STATE_OFF
,08-25 10:46:48.097  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:46:48.097  7377  7377 I art     : System.exit called, status: 0
,08-25 10:46:48.097  7377  7377 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 10:46:48.097  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:48.097  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:48.097  1016  1550 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 10:46:48.097  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-25 10:46:48.097  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:48.097  1016  1550 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:48.097  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:48.107  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 10:46:48.107  1016  1216 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-25 10:46:48.107  1016  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 10:46:48.107  1016  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:48.107  1016  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 10:46:48.107  1016  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 10:46:48.117  1315  1315 D DockEventReceiver: finishStartingService: stopping service
,08-25 10:46:48.117  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 10:46:48.117  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:48.117  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-25 10:46:48.127  1016  1481 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-25 10:46:48.127  1016  1481 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-25 10:46:48.127  1016  1481 W BroadcastQueue: android.os.TransactionTooLargeException
08-25 10:46:48.127  1016  1481 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 10:46:48.127  1016  1481 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 10:46:48.127  1016  1481 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-25 10:46:48.127  1016  1481 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-25 10:46:48.127  1016  1481 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-25 10:46:48.127  1016  1481 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-25 10:46:48.127  1016  1481 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-25 10:46:48.127  1016  1481 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-25 10:46:48.127  1016  1481 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 10:46:48.127  1016  1481 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-25 10:46:48.137  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:48.137  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:48.137  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:48.137  1016  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:48.147  7511  7511 E Zygote  : MountEmulatedStorage(),
,08-25 10:46:48.147  7511  7511 E Zygote  : v2
08-25 10:46:48.147  7511  7511 I libpersona: KNOX_SDCARD checking this for 1002
,08-25 10:46:48.147  7511  7511 I libpersona: KNOX_SDCARD not a persona
,08-25 10:46:48.147  1016  1481 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7511 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-25 10:46:48.147  7511  7511 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:48.157  7511  7511 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 10:46:48.157  7511  7511 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 10:46:48.177  7511  7511 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:48.177  7511  7511 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:48.187  7511  7511 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-25 10:46:48.187  7511  7511 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 10:46:48.207  7511  7511 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-25 10:46:48.247  7511  7511 D BtSettings.ProfileConfig: Adding GattService
,08-25 10:46:48.247  7511  7511 D BtSettings.ProfileConfig: Adding HeadsetService
,08-25 10:46:48.247  7511  7511 D BtSettings.ProfileConfig: Adding A2dpService
08-25 10:46:48.247  7511  7511 D BtSettings.ProfileConfig: Adding HidService
08-25 10:46:48.247  7511  7511 D BtSettings.ProfileConfig: Adding HealthService
08-25 10:46:48.247  7511  7511 D BtSettings.ProfileConfig: Adding PanService
,08-25 10:46:48.247  7511  7511 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-25 10:46:48.247  7511  7511 D BtSettings.ProfileConfig: Adding SapService
08-25 10:46:48.247  7511  7511 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-25 10:46:48.247  7511  7511 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-25 10:46:48.247  7511  7511 D BtSettings.ProfileConfig: Adding SapClientService
08-25 10:46:48.257  7511  7511 D BtSettings.ProfileConfig: Adding HidDevService
,08-25 10:46:48.257  7511  7511 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-25 10:46:48.257  1016  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-25 10:46:48.257  1016  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 10:46:48.257  1016  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:48.257  1016  1029 D SettingsProvider: selectionArgs: false
,08-25 10:46:48.257  1016  1029 D SettingsProvider: selectionArgs: 1002
08-25 10:46:48.257  1016  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 10:46:48.257  1016  1029 D SettingsProvider: ret = -1
,08-25 10:46:48.257  1016  1549 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-25 10:46:48.257  1016  1549 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:48.257  1016  1549 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 10:46:48.257  1016  1549 D SettingsProvider: selectionArgs: false
08-25 10:46:48.257  1016  1549 D SettingsProvider: selectionArgs: 1002
,08-25 10:46:48.257  1016  1549 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:48.257  1016  1549 D SettingsProvider: ret = -1
,08-25 10:46:48.267  1016  1134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-25 10:46:48.267  1016  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:48.267  1016  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 10:46:48.267  1016  1134 D SettingsProvider: selectionArgs: false
08-25 10:46:48.267  1016  1134 D SettingsProvider: selectionArgs: 1002
,08-25 10:46:48.267  1016  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 10:46:48.267  1016  1134 D SettingsProvider: ret = -1
,08-25 10:46:48.267  1016  1550 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-25 10:46:48.267  1016  1550 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:48.267  1016  1550 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:48.267  1016  1550 D SettingsProvider: selectionArgs: false,
08-25 10:46:48.267  1016  1550 D SettingsProvider: selectionArgs: 1002
,08-25 10:46:48.267  1016  1550 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-25 10:46:48.267  1016  1550 D SettingsProvider: ret = -1
,08-25 10:46:48.267  1016  1371 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService,
08-25 10:46:48.267  1016  1371 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-25 10:46:48.267  1016  1371 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 10:46:48.267  1016  1371 D SettingsProvider: selectionArgs: false
08-25 10:46:48.267  1016  1371 D SettingsProvider: selectionArgs: 1002
08-25 10:46:48.267  1016  1371 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:48.267  1016  1371 D SettingsProvider: ret = -1
08-25 10:46:48.267  1016  1485 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-25 10:46:48.267  1016  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:48.267  1016  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:48.267  1016  1485 D SettingsProvider: selectionArgs: false
08-25 10:46:48.267  1016  1485 D SettingsProvider: selectionArgs: 1002
08-25 10:46:48.267  1016  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:48.267  1016  1485 D SettingsProvider: ret = -1
08-25 10:46:48.267  1016  1380 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-25 10:46:48.267  1016  1380 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:48.267  1016  1380 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:48.267  1016  1380 D SettingsProvider: selectionArgs: false
08-25 10:46:48.267  1016  1380 D SettingsProvider: selectionArgs: 1002
08-25 10:46:48.267  1016  1380 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:48.267  1016  1380 D SettingsProvider: ret = -1
08-25 10:46:48.267  1016  1481 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-25 10:46:48.267  1016  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:48.267  1016  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:48.267  1016  1481 D SettingsProvider: selectionArgs: false
08-25 10:46:48.267  1016  1481 D SettingsProvider: selectionArgs: 1002
08-25 10:46:48.267  1016  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:48.267  1016  1481 D SettingsProvider: ret = -1
08-25 10:46:48.267  1016  1382 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-25 10:46:48.267  1016  1382 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:48.267  1016  1382 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:48.267  1016  1382 D SettingsProvider: selectionArgs: false
08-25 10:46:48.267  1016  1382 D SettingsProvider: selectionArgs: 1002
08-25 10:46:48.267  1016  1382 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:48.267  1016  1382 D SettingsProvider: ret = -1
08-25 10:46:48.267  1016  1483 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-25 10:46:48.267  1016  1483 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:48.267  1016  1483 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:48.267  1016  1483 D SettingsProvider: selectionArgs: false
08-25 10:46:48.267  1016  1483 D SettingsProvider: selectionArgs: 1002
08-25 10:46:48.267  1016  1483 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:48.267  1016  1483 D SettingsProvider: ret = -1
08-25 10:46:48.267  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-25 10:46:48.267  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:48.267  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:48.267  1016  1028 D SettingsProvider: selectionArgs: false
08-25 10:46:48.267  1016  1028 D SettingsProvider: selectionArgs: 1002
08-25 10:46:48.267  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:48.267  1016  1028 D SettingsProvider: ret = -1
08-25 10:46:48.267  1016  1216 D SettingsProvider: name, = bt_svcst_com.android.bluetooth.hid.HidDevService
08-25 10:46:48.267  1016  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:48.267  1016  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-25 10:46:48.267  1016  1216 D SettingsProvider: selectionArgs: false
08-25 10:46:48.267  1016  1216 D SettingsProvider: selectionArgs: 1002
08-25 10:46:48.277  1016  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:48.277  1016  1216 D SettingsProvider: ret = -1
,08-25 10:46:48.287  1954  1954 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 10:46:48.287  1016  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 10:46:48.287  1016  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-25 10:46:48.287  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:48.287  1016  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 10:46:48.287  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:48.297  1954  7530 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-25 10:46:48.297  1954  1954 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 10:46:48.397  1954  2123 I art     : Explicit concurrent mark sweep GC freed 57231(3MB) AllocSpace objects, 29(1061KB) LOS objects, 39% free, 11MB/19MB, paused 1.322ms total 88.622ms
,08-25 10:46:48.397  1016  1550 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:48.397  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:48.397  1016  1550 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 10:46:48.407  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:48.407  1954  7530 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-25 10:46:48.827  1016  1048 I PowerManagerService: [PWL] Off : 75s ago
,08-25 10:46:48.827  1016  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-25 10:46:48.827  1016  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,08-25 10:46:48.827  1016  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1016, ws=null) (elapsedTime=13037)
,08-25 10:46:48.887  1016  1303 E Watchdog: !@Sync 4,
,08-25 10:46:49.927   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 10:46:50.097  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop,
08-25 10:46:50.097  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:50.867   289   289 E SMD     : DCD OFF,
,08-25 10:46:50.927   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 10:46:51.927   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 10:46:52.667  1016  3375 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-25 10:46:52.917   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 10:46:53.097  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-25 10:46:53.097  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@111dceb9 added. We now have 6 listener(s)
08-25 10:46:53.097  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-25 10:46:53.097  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:46:53.097  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ac392fe added. We now have 7 listener(s)
08-25 10:46:53.097  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-25 10:46:53.097  6741  6794 I System.out: IsBluetoothEnabled
08-25 10:46:53.097  6741  6794 D BluetoothAdapter: disable(),
08-25 10:46:53.097  1016  1485 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-25 10:46:53.107  6741  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-25 10:46:53.107  6741  6794 D BluetoothAdapter: enable()
,08-25 10:46:53.107  1016  1382 W ActivityManager: Permission Denial: getCurrentUser() from pid=6741, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,08-25 10:46:53.107  1016  1382 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-25 10:46:53.107  1016  1382 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6741, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 10:46:53.107  1016  1382 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 10:46:53.107  1016  1382 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-25 10:46:53.107  1016  1382 W BluetoothManagerService: 	,at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-25 10:46:53.107  1016  1382 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-25 10:46:53.107  1016  1382 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 10:46:53.107  1016  1382 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 10:46:53.107  1016  1382 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 10:46:53.117  1016  1382 D SettingsProvider: name = bluetooth_on
,08-25 10:46:53.117  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 10:46:53.117  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 10:46:53.117  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-25 10:46:53.117  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-25 10:46:53.157  7511  7511 D BluetoothAdapterState: make
,08-25 10:46:53.157  7511  7511 I bluedroid: init
,08-25 10:46:53.167  7511  7536 I BluetoothAdapterState: Entering OffState
,08-25 10:46:53.167  7511  7511 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 10:46:53.167  7511  7511 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 10:46:53.167  7511  7511 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 10:46:53.167  7511  7511 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-25 10:46:53.167  7511  7511 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-25 10:46:53.167  7511  7511 I bluedroid: get_profile_interface socket
08-25 10:46:53.167  7511  7511 I bluedroid: get_profile_interface map_client
,08-25 10:46:53.167  7511  7539 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 10:46:53.167  7511  7539 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-25 10:46:53.167  7511  7539 E BluetoothServiceJni: populateRssiValuesNative
08-25 10:46:53.167  7511  7539 I bluedroid: getModelRssiValues
08-25 10:46:53.167  7511  7539 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-25 10:46:53.167  7511  7539 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
08-25 10:46:53.167  7511  7511 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-25 10:46:53.177  7511  7539 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-25 10:46:53.177  1016  1016 D SettingsProvider: name = bluetooth_name
,08-25 10:46:53.177  7511  7511 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 10:46:53.187  1016  1382 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-25 10:46:53.187  1016  1382 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 10:46:53.187  1016  1382 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:53.187  1016  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:53.187  1016  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:53.187  7511  7528 I bluedroid: config_hci_snoop_log
,08-25 10:46:53.187  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 10:46:53.197  1016  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-25 10:46:53.197  1016  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-25 10:46:53.197  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-25 10:46:53.197  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-25 10:46:53.207  7511  7511 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-25 10:46:53.217  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-25 10:46:53.217  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-25 10:46:53.217  1016  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-25 10:46:53.217  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-25 10:46:53.227  7511  7536 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-25 10:46:53.227  7511  7536 D BluetoothAdapterProperties: Setting state to 11
,08-25 10:46:53.227  7511  7536 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 10:46:53.227  7511  7536 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 10:46:53.227  7511  7536 D BluetoothAdapterService: updateAdapterState state is 11
,08-25 10:46:53.227  7511  7536 D BluetoothAdapterService: Autoconnection is available 
,08-25 10:46:53.227  7511  7536 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-25 10:46:53.227  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:46:53.227  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
,08-25 10:46:53.227  7511  7536 D BluetoothSecureManager: getInstant: null
08-25 10:46:53.227  7511  7536 D BluetoothSecureManager: calling getMethod for getService
08-25 10:46:53.227  7511  7536 D BluetoothSecureManager: calling getService
,08-25 10:46:53.227  7511  7536 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@130ad2b4
,08-25 10:46:53.227  1016  1485 D BluetoothSecureManagerService: isSecureModeEnabled
08-25 10:46:53.227  1016  1485 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-25 10:46:53.227  7511  7536 D BtConfig.SecureMode: isSecureModeOn:false
08-25 10:46:53.227  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-25 10:46:53.227  7511  7536 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-25 10:46:53.227  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-25 10:46:53.227  7511  7536 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-25 10:46:53.227  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-25 10:46:53.237  7511  7536 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-25 10:46:53.237  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-25 10:46:53.237  7511  7536 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-25 10:46:53.237  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-25 10:46:53.237  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 10:46:53.237  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:46:53.237  1176  1176 D BluetoothTile:  getBluetoothState : 11
,08-25 10:46:53.237  7511  7536 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-25 10:46:53.237  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-25 10:46:53.237  1875  1875 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 10:46:53.237  7511  7536 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-25 10:46:53.237  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:53.237  7511  7536 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-25 10:46:53.237  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-25 10:46:53.237  7511  7536 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-25 10:46:53.237  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 10:46:53.237  7511  7536 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-25 10:46:53.237  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-25 10:46:53.237  7511  7536 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-25 10:46:53.237  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-25 10:46:53.247  7511  7536 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-25 10:46:53.247  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 10:46:53.247  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:46:53.247  1016  1550 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 10:46:53.247  7511  7536 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-25 10:46:53.247  1016  1134 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-25 10:46:53.247  7511  7536 D BluetoothBondStateMachine: make
,08-25 10:46:53.247  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-25 10:46:53.247  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:53.247  7511  7536 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-25 10:46:53.247  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-25 10:46:53.247  7511  7536 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-25 10:46:53.247  7511  7540 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 10:46:53.247  1176  1728 D BluetoothTile:  handleUpdatestate:false name:null
08-25 10:46:53.247  1176  1728 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-25 10:46:53.247  1016  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 10:46:53.247  1016  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-25 10:46:53.247  1016  1485 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:53.247  1016  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:53.247  1016  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:53.257  1016  1371 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 10:46:53.257  1016  1371 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-25 10:46:53.257  1016  1371 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:53.257  1016  1371 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 10:46:53.257  1016  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 10:46:53.257  7511  7536 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-25 10:46:53.257  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-25 10:46:53.257  7511  7536 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-25 10:46:53.257  7511  7511 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 10:46:53.257  7511  7511 D BtGatt.GattService: Received start request. Starting profile...
08-25 10:46:53.257  7511  7511 D BtGatt.GattService: start()
08-25 10:46:53.257  7511  7511 D BtGatt.GattService: start()
08-25 10:46:53.257  7511  7511 I bluedroid: get_profile_interface gatt
,08-25 10:46:53.257  7511  7511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1091718f
08-25 10:46:53.257  7511  7511 D BtGatt.AdvertiseManager: advertise manager created
,08-25 10:46:53.267  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 10:46:53.267  1016  1550 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 10:46:53.267  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-25 10:46:53.267  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:53.267  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:53.267  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:53.267  7511  7536 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-25 10:46:53.267  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-25 10:46:53.267  7511  7536 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-25 10:46:53.277  1016  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:53.277  1016  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 10:46:53.277  1016  1481 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:53.277  1016  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:53.277  1016  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:53.277  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:46:53.277  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-25 10:46:53.277  7511  7536 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-25 10:46:53.277  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-25 10:46:53.277  7511  7536 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-25 10:46:53.277  1016  1380 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 10:46:53.277  1016  1380 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 10:46:53.277  1016  1380 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:53.277  1016  1380 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:53.277  1016  1380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:53.287  7511  7536 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-25 10:46:53.287  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-25 10:46:53.287  7511  7536 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-25 10:46:53.287  1016  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:53.287  1016  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-25 10:46:53.287  1016  1216 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:53.287  1016  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:53.287  1016  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:53.297  7511  7536 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-25 10:46:53.297  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-25 10:46:53.297  7511  7536 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-25 10:46:53.297  1016  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:53.297  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 10:46:53.297  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:53.297  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:53.297  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:53.297  7511  7536 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:53.297  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-25 10:46:53.297  7511  7536 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-25 10:46:53.297  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:53.297  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 10:46:53.297  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:53.297  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:53.297  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:53.297  7511  7536 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-25 10:46:53.297  7511  7511 D BtGatt.GattService: mStartError = false
08-25 10:46:53.297  7511  7511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1091718f
,08-25 10:46:53.307  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-25 10:46:53.307  7511  7536 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-25 10:46:53.307  1016  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:53.307  1016  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 10:46:53.307  1016  1483 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:53.307  1016  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:53.307  1016  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:53.307  7511  7511 D HeadsetService: Received start request. Starting profile...
,08-25 10:46:53.307  7511  7511 D HeadsetService: start()
,08-25 10:46:53.307  7511  7511 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-25 10:46:53.307  7511  7511 D HeadsetStateMachine: make
,08-25 10:46:53.307  7511  7511 E HeadsetStateMachine: # of Max HF connection is 2
,08-25 10:46:53.307  7511  7536 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 10:46:53.307  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-25 10:46:53.317  7511  7536 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-25 10:46:53.317  7511  7536 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-25 10:46:53.317  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-25 10:46:53.317  7511  7536 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-25 10:46:53.317  7511  7536 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-25 10:46:53.317  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-25 10:46:53.317  7511  7536 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-25 10:46:53.317  7511  7536 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-25 10:46:53.317  7511  7536 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-25 10:46:53.317  7511  7536 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-25 10:46:53.317  7511  7536 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-25 10:46:53.317  1016  2035 V SAMP_SPCM_test: CSC File load.. 
,08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
,08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-25 10:46:53.327  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-25 10:46:53.357  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
,08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage,
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages,
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
,08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming,
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
,08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
,08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-25 10:46:53.367  1016  2035 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-25 10:46:53.367  1016  1028 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-25 10:46:53.367  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-25 10:46:53.367  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:53.367  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:53.367  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-25 10:46:53.367  1016  2035 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,08-25 10:46:53.377  1016  2035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:53.377  1016  2035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:53.377  1016  2035 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:53.377  1016  2035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:53.387  7549  7549 E Zygote  : MountEmulatedStorage()
,08-25 10:46:53.387  7549  7549 E Zygote  : v2
08-25 10:46:53.387  7549  7549 I libpersona: KNOX_SDCARD checking this for 1000
08-25 10:46:53.387  7549  7549 I libpersona: KNOX_SDCARD not a persona
,08-25 10:46:53.387  7549  7549 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:53.387  1016  2035 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7549 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-25 10:46:53.387  1016  1380 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-25 10:46:53.387  1016  1380 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-25 10:46:53.387  1016  1380 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:53.387  1016  1380 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:53.387  1016  1380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-25 10:46:53.387  7549  7549 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 10:46:53.387  7511  7511 I bluedroid: get_profile_interface handsfree
,08-25 10:46:53.387  7549  7549 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 10:46:53.407  7511  7511 I DualScoManager: Instantiating Dual Sco Manager
,08-25 10:46:53.407  7511  7511 I DualScoManager: Set HeadsetServiceHelper
,08-25 10:46:53.407  7511  7511 D BluetoothAtMessage: createCMTIContentObservers
,08-25 10:46:53.407  1016  1371 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-25 10:46:53.407  1016  1371 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:53.407  1016  1371 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
,08-25 10:46:53.407  1016  1371 D SettingsProvider: selectionArgs: false
08-25 10:46:53.407  1016  1371 D SettingsProvider: selectionArgs: 1002
08-25 10:46:53.407  1016  1371 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:53.407  1016  1371 D SettingsProvider: ret = -1
08-25 10:46:53.407  7511  7548 D HeadsetStateMachine: Enter Disconnected: -2
,08-25 10:46:53.407  7511  7511 D HeadsetService: mStartError = false
08-25 10:46:53.407  7511  7511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1091718f
,08-25 10:46:53.417  7511  7548 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-25 10:46:53.417  7549  7549 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 10:46:53.417  7511  7548 D HeadsetStateMachine: map size, before remove : 0
08-25 10:46:53.417  7511  7548 D HeadsetStateMachine: map size, after remove: 0
,08-25 10:46:53.417  7549  7549 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:53.417  7511  7511 D A2dpService: Received start request. Starting profile...
08-25 10:46:53.417  7511  7511 D A2dpService: start()
,08-25 10:46:53.417  7511  7511 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-25 10:46:53.427  7511  7511 I bluedroid: get_profile_interface avrcp
,08-25 10:46:53.427  7511  7511 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 10:46:53.427  7511  7511 D Avrcp   : Initialize Media Controller
08-25 10:46:53.427  7511  7511 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-25 10:46:53.427  7511  7511 E Avrcp   : getActiveSessions
08-25 10:46:53.427  7511  7511 D Avrcp   : pick active media Controller
08-25 10:46:53.427  7511  7511 D Avrcp   : Get the active Media Controller 
,08-25 10:46:53.437  7549  7549 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-25 10:46:53.447  7511  7511 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-25 10:46:53.447  7511  7564 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-25 10:46:53.447  7511  7511 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 10:46:53.447  7511  7511 D A2dpStateMachine: make
,08-25 10:46:53.457  7511  7511 I bluedroid: get_profile_interface a2dp
,08-25 10:46:53.457  7511  7566 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-25 10:46:53.457  7511  7564 D BluetoothMediaBrowser: no now playing list
,08-25 10:46:53.457  7511  7564 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-25 10:46:53.467  7511  7511 E bt-btif : warning : media task started media_task_refcnt 1 
,08-25 10:46:53.467  7511  7511 D A2dpService: mStartError = false
08-25 10:46:53.467  7511  7511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1091718f
,08-25 10:46:53.467  7511  7511 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 10:46:53.467  7511  7565 D A2dpStateMachine: Enter Disconnected: -2,
,08-25 10:46:53.467  7511  7511 D HidService: Received start request. Starting profile...
,08-25 10:46:53.467  7511  7511 D HidService: start()
08-25 10:46:53.467  7511  7511 I bluedroid: get_profile_interface hidhost
,08-25 10:46:53.467  7511  7511 D HidService: setHidService(): set to: null
08-25 10:46:53.467  7511  7511 D HidService: mStartError = false
,08-25 10:46:53.467  7511  7511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1091718f
,08-25 10:46:53.467  7511  7511 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 10:46:53.477  7511  7511 D HealthService: Received start request. Starting profile...
08-25 10:46:53.477  7511  7511 D HealthService: start()
,08-25 10:46:53.477  7511  7511 I bluedroid: get_profile_interface health
,08-25 10:46:53.477  7511  7511 D HealthService: mStartError = false
08-25 10:46:53.477  7511  7511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1091718f
,08-25 10:46:53.477  7511  7511 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 10:46:53.477  7511  7511 D PanService: Received start request. Starting profile...
08-25 10:46:53.477  7511  7511 D PanService: start()
08-25 10:46:53.477  7511  7511 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 10:46:53.477  7511  7511 I bluedroid: get_profile_interface pan
,08-25 10:46:53.477  7511  7511 D PanService: mStartError = false
08-25 10:46:53.477  7511  7511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1091718f
,08-25 10:46:53.477  7511  7511 D BluetoothMapService: Received start request. Starting profile...
08-25 10:46:53.477  7511  7511 D BluetoothMapService: start()
,08-25 10:46:53.487  7511  7511 D BluetoothMapService: mStartError = false
08-25 10:46:53.487  7511  7511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1091718f
,08-25 10:46:53.487  7511  7511 E BluetoothAdapterService(277967247): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-25 10:46:53.487  7511  7511 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-25 10:46:53.487  7511  7511 D SapService: Received start request. Starting profile...
08-25 10:46:53.487  7511  7511 D SapService: start()
08-25 10:46:53.487  7511  7511 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-25 10:46:53.487  7511  7511 I bluedroid: get_profile_interface sap
08-25 10:46:53.487  7511  7511 D SapService: mStartError = false
08-25 10:46:53.487  7511  7511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1091718f
,08-25 10:46:53.487  7511  7511 D HeadsetStateMachine: Try to query the phonestate on bind
,08-25 10:46:53.487  1016  2035 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-25 10:46:53.497  1423  1459 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 10:46:53.497  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-25 10:46:53.497  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-25 10:46:53.497  1423  1459 I Telecom : BluetoothPhoneService: Result of Message : true
,08-25 10:46:53.497  7511  7511 D HeadsetStateMachine: Proxy object connected
,08-25 10:46:53.497  1954  1954 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-25 10:46:53.497  7511  7511 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-25 10:46:53.497  7511  7511 D HeadsetPhoneState: sendDeviceDataStateChanged
08-25 10:46:53.497  7511  7548 D HeadsetStateMachine: Disconnected process message: 11
08-25 10:46:53.497  7511  7548 D HeadsetStateMachine: Disconnected process message: 18
08-25 10:46:53.497  7511  7511 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-25 10:46:53.497  7511  7511 E BluetoothAdapterService(277967247): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-25 10:46:53.497  7511  7511 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-25 10:46:53.497  7511  7511 D BluetoothA2dp: Proxy object connected
08-25 10:46:53.497  7511  7511 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-25 10:46:53.497  7511  7548 D HeadsetStateMachine: Disconnected process message: 10
,08-25 10:46:53.497  7511  7548 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 10:46:53.497  7511  7548 D HeadsetStateMachine: Disconnected process message: 11
,08-25 10:46:53.497  1954  1954 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 10:46:53.507  7511  7511 E BluetoothAdapterService(277967247): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true,
08-25 10:46:53.507  7511  7511 E BluetoothAdapterService(277967247): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-25 10:46:53.507  7511  7511 E BluetoothAdapterService(277967247): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-25 10:46:53.507  7511  7511 E BluetoothAdapterService(277967247): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-25 10:46:53.527  7511  7511 E BluetoothAdapterService(277967247): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-25 10:46:53.527  7511  7511 E BluetoothAdapterService(277967247): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-25 10:46:53.527  1016  1485 I ActivityManager: Killing 7082:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-25 10:46:53.527  7511  7536 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-25 10:46:53.527  7511  7536 I bluedroid: enable
,08-25 10:46:53.527  7511  7536 I bt_hci_bdroid: init
,08-25 10:46:53.527  7511  7536 I bt_vendor: bt-vendor : init
08-25 10:46:53.527  7511  7536 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 10:46:53.527  7511  7536 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 10:46:53.527  7511  7536 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-25 10:46:53.527  7511  7536 D bt_userial_mct: userial_init
,08-25 10:46:53.537  7511  7570 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 10:46:53.537  7511  7536 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 10:46:53.537  7511  7536 I bt_vendor: Starting hciattach daemon
08-25 10:46:53.537  7511  7536 I bt_vendor: try to set false
,08-25 10:46:53.537  7511  7536 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 10:46:53.537  7511  7536 I bt_vendor: Starting hciattach daemon
,08-25 10:46:53.537  7511  7536 I bt_vendor: try to set true
,08-25 10:46:53.547  7574  7574 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-25 10:46:53.607  7580  7580 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 10:46:53.617  7581  7581 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-25 10:46:53.637  7583  7583 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-25 10:46:53.647  7584  7584 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-25 10:46:53.657  7585  7585 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-25 10:46:53.667  7586  7586 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-25 10:46:53.867   289   289 E SMD     : DCD OFF
,08-25 10:46:53.917  7589  7589 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-25 10:46:53.927   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-25 10:46:53.927  7590  7590 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-25 10:46:53.937  7511  7536 I bt_vendor: bluetooth satus is on,
08-25 10:46:53.937  7511  7572 D bt_userial_mct: userial_open(port:0)
08-25 10:46:53.937  7511  7572 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 10:46:53.947  7511  7572 I bt_vendor: Done intiailizing UART
,08-25 10:46:53.947  7511  7572 I bt_vendor: Done intiailizing UART,
08-25 10:46:53.947  7511  7572 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 10:46:53.947  7511  7572 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-25 10:46:53.947  7511  7592 D bt_userial_mct: Entering userial_read_thread()
,08-25 10:46:53.957  7511  7570 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 10:46:53.957  7511  7570 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-25 10:46:53.957  7511  7570 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 10:46:53.957  7511  7570 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-25 10:46:53.957  7511  7570 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 10:46:53.957  7511  7570 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 10:46:53.957  7511  7570 I         : BTE_InitTraceLevels -- TRC_BNEP,
08-25 10:46:53.957  7511  7570 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 10:46:53.957  7511  7570 I         : BTE_InitTraceLevels -- TRC_GAP
,08-25 10:46:53.957  7511  7570 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 10:46:53.957  7511  7570 I         : BTE_InitTraceLevels -- TRC_SAP
08-25 10:46:53.957  7511  7570 I         : BTE_InitTraceLevels -- TRC_SDP
,08-25 10:46:53.957  7511  7570 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 10:46:53.957  7511  7570 I         : BTE_InitTraceLevels -- TRC_SMP
,08-25 10:46:53.957  7511  7570 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 10:46:53.957  7511  7570 I         : BTE_InitTraceLevels -- TRC_BTIF
08-25 10:46:53.957  7511  7570 I         : BTE_InitTraceLevels -- TRC_PROTOCOL,
,08-25 10:46:53.967  1016  3343 D SSRM:n  : SIOP:: AP = 320
,08-25 10:46:54.047  7511  7570 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-25 10:46:54.057  7511  7570 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa42d0ed1 
,08-25 10:46:54.057  7511  7570 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa42d0ed1 
,08-25 10:46:54.067  7511  7539 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-25 10:46:54.077  7511  7539 E bt-btif : Calling BTA_HhEnable
,08-25 10:46:54.077  7511  7539 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-25 10:46:54.077  7511  7539 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-25 10:46:54.077  7511  7539 E BluetoothServiceJni: populateRssiValuesNative
08-25 10:46:54.077  7511  7539 I bluedroid: getModelRssiValues
,08-25 10:46:54.077  7511  7539 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-25 10:46:54.077  7511  7539 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-25 10:46:54.077  1016  1016 D SettingsProvider: name = bluetooth_name
,08-25 10:46:54.077  7511  7539 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-25 10:46:54.087  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:54.087  7511  7539 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-25 10:46:54.087  7511  7539 D BluetoothAdapterProperties: Scan Mode:20
,08-25 10:46:54.087  7511  7539 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 10:46:54.097  7511  7539 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-25 10:46:54.097  7511  7539 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-25 10:46:54.097  7511  7539 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-25 10:46:54.097  7511  7592 E bt_mct  : hci lib postload completed
,08-25 10:46:54.097  7511  7539 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-25 10:46:54.097  7511  7539 E bt-btif : btif_sock_init: !vhci_init
,08-25 10:46:54.097  7511  7539 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-25 10:46:54.097  7511  7539 D IOP_DB_BT: db_open: db_open : handle 2965852176l, read 13894 bytes onto local cache
08-25 10:46:54.097  7511  7539 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1,
08-25 10:46:54.097  7511  7539 D IOP_DB_BT: db_query: result 1
08-25 10:46:54.097  7511  7539 I         : iop_db_open: iop_db_open status 0
,08-25 10:46:54.097  7511  7539 D bte_conf: Device ID record 1 : primary
08-25 10:46:54.097  7511  7539 D bte_conf:   vendorId            = 0075
08-25 10:46:54.097  7511  7539 D bte_conf:   vendorIdSource      = 0001
08-25 10:46:54.097  7511  7539 D bte_conf:   product             = 0100,
08-25 10:46:54.097  7511  7539 D bte_conf:   version             = 0200
08-25 10:46:54.097  7511  7539 D bte_conf:   clientExecutableURL = 
08-25 10:46:54.097  7511  7539 D bte_conf:   serviceDescription  = 
08-25 10:46:54.097  7511  7539 D bte_conf:   documentationURL    = 
08-25 10:46:54.097  7511  7539 D bte_conf: bte_load_did_conf no section named DID2.
,08-25 10:46:54.107  7511  7539 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 10:46:54.107  7511  7536 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-25 10:46:54.107  7511  7536 D BluetoothAdapterProperties: ScanMode =  20
,08-25 10:46:54.107  7511  7536 D BluetoothAdapterProperties: State =  11
,08-25 10:46:54.107  1016  1371 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-25 10:46:54.107  7511  7536 D BluetoothAdapterProperties: Setting state to 12
,08-25 10:46:54.107  7511  7536 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-25 10:46:54.117  7511  7539 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-25 10:46:54.117  7511  7539 D BluetoothAdapterProperties: Scan Mode:21
,08-25 10:46:54.117  7511  7539 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 10:46:54.117  1016  1550 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-25 10:46:54.117  1016  1550 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-25 10:46:54.117  1016  1550 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-25 10:46:54.117  1016  1550 D SettingsProvider: selectionArgs: false
,08-25 10:46:54.117  1016  1550 D SettingsProvider: selectionArgs: 1002
,08-25 10:46:54.117  1016  1550 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:54.117  1016  1550 D SettingsProvider: ret = -1
,08-25 10:46:54.117  7511  7536 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-25 10:46:54.117  7511  7536 D BluetoothAdapterService: updateAdapterState state is 12
,08-25 10:46:54.127  1016  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 10:46:54.127  1016  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 10:46:54.127  1016  1483 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:54.127  1016  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:54.127  1016  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:54.127  7511  7527 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 10:46:54.137  7511  7536 D BluetoothAdapterService: Autoconnection is available 
,08-25 10:46:54.137  7511  7536 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-25 10:46:54.137  7511  7536 D BluetoothAdapterService: starting service from this receiver
08-25 10:46:54.137  1016  1550 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-25 10:46:54.137  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-25 10:46:54.137  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:54.137  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:54.137  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-25 10:46:54.137  7511  7536 I BluetoothAdapterState: Entering On State from state = 11
08-25 10:46:54.137  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:54.137  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:54.137  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:54.137  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:54.137  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:54.137  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:54.137  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:54.137  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:46:54.137  1315  7485 D BluetoothPan: Binding service...
,08-25 10:46:54.157  7511  7511 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-25 10:46:54.167  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:54.167  6741  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:54.167  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:54.167  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:54.167  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 10:46:54.167  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:54.167  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:54.167  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:54.167  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:54.167  6741  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:54.167  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 10:46:54.177  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a832a5f added. We now have 8 listener(s)
,08-25 10:46:54.177  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:46:54.177  1016  1382 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-25 10:46:54.177  1016  1382 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-25 10:46:54.177  1016  1382 D SecContentProvider2: mCursor = null
,08-25 10:46:54.177  1016  1382 D WifiService: setWifiEnabled: false pid=6741, uid=10171
,08-25 10:46:54.177  1016  1382 D SettingsProvider: name = wifi_on
,08-25 10:46:54.187  6741  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:54.187  1016  1134 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-25 10:46:54.187  1016  1134 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-25 10:46:54.187  1016  1134 D SecContentProvider2: mCursor = null
,08-25 10:46:54.187  1016  1134 D WifiService: setWifiEnabled: true pid=6741, uid=10171
,08-25 10:46:54.187  1016  1134 W ActivityManager: Permission Denial: getCurrentUser() from pid=6741, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-25 10:46:54.187  1016  1134 W WifiService: Failed getting userId using ActivityManagerNative
08-25 10:46:54.187  1016  1134 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6741, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-25 10:46:54.187  1016  1134 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-25 10:46:54.187  1016  1134 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-25 10:46:54.187  1016  1134 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-25 10:46:54.187  1016  1134 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-25 10:46:54.187  1016  1134 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 10:46:54.197  1016  1134 D SettingsProvider: name = wifi_on
,08-25 10:46:54.197  1016  1124 E WifiHW  : ##################### set firmware type 0 #####################
,08-25 10:46:54.327  1016  1045 I art     : Explicit concurrent mark sweep GC freed 30925(1787KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.522ms total 177.448ms
08-25 10:46:54.327  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-25 10:46:54.327  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 10:46:54.327  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:54.327  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:54.327  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:54.327  7511  7527 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 10:46:54.327  7511  7527 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 10:46:54.327  1315  1338 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 10:46:54.327  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-25 10:46:54.327  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-25 10:46:54.327  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:54.327  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:54.327  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:54.327  1315  1325 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 10:46:54.327  1315  1325 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 10:46:54.327  7427  7439 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 10:46:54.327  7427  7439 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 10:46:54.337  1423  1463 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 10:46:54.337  1423  1463 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 10:46:54.337  1315  1325 D Bluetoothsap: onBluetoothStateChange: up=true
08-25 10:46:54.337  1315  1325 D Bluetoothsap: Binding service...
,08-25 10:46:54.337  1315  1325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-25 10:46:54.337  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-25 10:46:54.337  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-25 10:46:54.337  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:54.337  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:54.337  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:54.337  7511  7511 I BluetoothPbapService: Handler(): got msg=1
,08-25 10:46:54.337  1315  1325 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-25 10:46:54.337  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 10:46:54.337  1016  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 10:46:54.337  1315  1338 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 10:46:54.337  1016  1371 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-25 10:46:54.337  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-25 10:46:54.337  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-25 10:46:54.337  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:54.337  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:54.337  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:54.337  1016  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 10:46:54.347  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 10:46:54.347  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 10:46:54.347  1016  1045 E BluetoothHeadset: BluetoothHeadset service is binded
08-25 10:46:54.347  1016  1045 D BluetoothPan: Binding service...
08-25 10:46:54.347  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-25 10:46:54.347  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-25 10:46:54.347  1423  1463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-25 10:46:54.347  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
,08-25 10:46:54.347  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 10:46:54.347  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 10:46:54.347  7511  7599 V BluetoothPbapService: PBAP Service initSocket try: 0
08-25 10:46:54.347  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:54.347  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:54.347  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-25 10:46:54.347  1423  1463 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 10:46:54.347  1315  1315 D BluetoothPan: BluetoothPAN Proxy object connected
,08-25 10:46:54.347  1954  7352 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-25 10:46:54.347  1954  7352 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 10:46:54.347  1315  1315 D PanProfile: Bluetooth service connected
,08-25 10:46:54.357  1423  6931 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 10:46:54.357  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 10:46:54.357  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 10:46:54.357  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:54.357  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-25 10:46:54.357  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:54.357  7511  7599 D BluetoothSocket: bindListen(): myUserId = 0
08-25 10:46:54.357  7511  7599 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 10:46:54.357  1423  6931 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 10:46:54.357  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 10:46:54.357  1016  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 10:46:54.357  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 10:46:54.357  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 10:46:54.357  1016  1016 D BluetoothA2dp: Proxy object connected
,08-25 10:46:54.357  1315  1315 D BluetoothMap: Proxy object connected
08-25 10:46:54.357  1315  1315 D MapProfile: Bluetooth service connected
08-25 10:46:54.357  1315  1315 D BluetoothMap: getConnectedDevices()
,08-25 10:46:54.367  1315  7485 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 10:46:54.367  7511  7599 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-25 10:46:54.367  7511  7599 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 10:46:54.367  7511  7599 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 10:46:54.367  7511  7599 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16a517f1
08-25 10:46:54.367  7511  7599 D BluetoothSocket: channel: 19
08-25 10:46:54.367  7511  7599 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-25 10:46:54.367  1315  7485 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-25 10:46:54.367  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-25 10:46:54.367  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-25 10:46:54.367  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:54.367  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:54.367  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:54.367  1315  1315 D Bluetoothsap: BluetoothSAP Proxy object connected
08-25 10:46:54.367  1315  1315 D SapProfile: Bluetooth service connected
08-25 10:46:54.367  1315  1315 D Bluetoothsap: getConnectedDevices()
,08-25 10:46:54.367  1176  3267 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 10:46:54.367  1176  3267 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 10:46:54.367  6741  6749 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 10:46:54.367  6741  6749 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 10:46:54.367  1315  1315 D BluetoothPbap: Proxy object connected
,08-25 10:46:54.367  1315  1315 D PbapServerProfile: Bluetooth service connected
08-25 10:46:54.367  1315  1315 D BluetoothA2dp: Proxy object connected
08-25 10:46:54.367  1315  1315 D A2dpProfile: Bluetooth service connected
08-25 10:46:54.367  1443  1474 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 10:46:54.367  1016  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-25 10:46:54.367  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 10:46:54.367  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:54.367  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:54.367  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:54.377  1443  1474 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 10:46:54.377  1423  1459 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 10:46:54.377  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 10:46:54.377  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 10:46:54.377  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:54.377  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:54.377  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:54.377  1423  1459 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 10:46:54.377  1315  1338 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-25 10:46:54.377  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-25 10:46:54.387  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-25 10:46:54.387  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:54.387  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:54.387  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:54.387  1315  1315 D HeadsetProfile: Bluetooth service connected
,08-25 10:46:54.387  1315  1338 E BluetoothHeadset: BluetoothHeadset service is binded
,08-25 10:46:54.387  1315  7485 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 10:46:54.387  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-25 10:46:54.387  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-25 10:46:54.387  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:54.387  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:54.387  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:54.397  1430  1441 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 10:46:54.397  1430  1441 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-25 10:46:54.397  1315  1315 D BluetoothInputDevice: Proxy object connected
08-25 10:46:54.397  1315  1315 D HidProfile: Bluetooth service connected
08-25 10:46:54.397  1443  1943 D BluetoothAdapter: onBluetoothStateChange: up=true
08-25 10:46:54.397  1443  1943 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-25 10:46:54.397  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-25 10:46:54.397  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-25 10:46:54.397  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:46:54.397  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
,08-25 10:46:54.397  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-25 10:46:54.407  1423  1423 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2d6dbb14, true
,08-25 10:46:54.407  1423  1423 D BluetoothHeadset: registerMessageListener
,08-25 10:46:54.407  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-25 10:46:54.407  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-25 10:46:54.407  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-25 10:46:54.407  1176  1176 D BluetoothTile:  getBluetoothState : 12
,08-25 10:46:54.407  1875  1875 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-25 10:46:54.407  1176  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 10:46:54.417  1016  1481 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 10:46:54.417  1016  1382 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-25 10:46:54.417  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-25 10:46:54.417  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:54.417  1176  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 10:46:54.427  1016  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-25 10:46:54.427  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-25 10:46:54.427  7511  7528 D HeadsetService: registerMessageListener
08-25 10:46:54.427  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:46:54.427  7511  7528 D HeadsetService: registerMessageListener
08-25 10:46:54.427  7511  7548 D HeadsetStateMachine: Disconnected process message: 70
08-25 10:46:54.427  7511  7548 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@26fccfd6
08-25 10:46:54.427  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-25 10:46:54.427  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-25 10:46:54.427  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:54.427  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:54.427  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:54.427  1176  1728 D BluetoothTile:  handleUpdatestate:false name:null
,08-25 10:46:54.427  7511  7608 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-25 10:46:54.427  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-25 10:46:54.427  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-25 10:46:54.427  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-25 10:46:54.427  1315  1315 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-25 10:46:54.427  1315  1315 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-25 10:46:54.427  1315  1315 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-25 10:46:54.427  1315  1315 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-25 10:46:54.437  7511  7548 D HeadsetStateMachine: Disconnected process message: 9
,08-25 10:46:54.437  7511  7548 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-25 10:46:54.437   284   695 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-25 10:46:54.437   284   695 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,08-25 10:46:54.437   284   695 V voice   : voice_set_parameters: exit with code(-2)
,08-25 10:46:54.437   284   695 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-25 10:46:54.447   284   695 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-25 10:46:54.447   284   695 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-25 10:46:54.447   284   695 V audio_hw_primary: adev_set_parameters: exit
08-25 10:46:54.447  7511  7608 D BluetoothSocket: bindListen(): myUserId = 0
08-25 10:46:54.447  7511  7608 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 10:46:54.447  7511  7548 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-25 10:46:54.447  7511  7608 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-25 10:46:54.447  7511  7608 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 10:46:54.447  7511  7608 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 10:46:54.447  7511  7608 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@367be257
,08-25 10:46:54.447  7511  7608 D BluetoothSocket: channel: 5
,08-25 10:46:54.457  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 10:46:54.457  1016  1028 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-25 10:46:54.457  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-25 10:46:54.457  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:54.457  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:54.457  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-25 10:46:54.457  1315  1315 D DockEventReceiver: finishStartingService: stopping service
,08-25 10:46:54.467  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,08-25 10:46:54.467  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-25 10:46:54.467  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-25 10:46:54.477  7511  7511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1091718f
,08-25 10:46:54.477  7511  7511 D BtConfig.SecureMode: isSecureModeOn:false
,08-25 10:46:54.477  1016  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-25 10:46:54.477  1016  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-25 10:46:54.477  1016  1483 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:54.477  1016  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:54.477  1016  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-25 10:46:54.487  1954  1954 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-25 10:46:54.487  1016  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-25 10:46:54.497  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-25 10:46:54.497  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:54.497  1016  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 10:46:54.497  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:54.507  1954  7615 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-25 10:46:54.507  1016  1483 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-25 10:46:54.507  1954  1954 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-25 10:46:54.507  1016  1382 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:54.507  1016  1382 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:54.507  1016  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:54.507  1016  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:54.517  7511  7618 D BluetoothSocket: bindListen(): myUserId = 0
08-25 10:46:54.517  7511  7618 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 10:46:54.527  7511  7618 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-25 10:46:54.527  7511  7618 D BluetoothSocket: bindListen(), new LocalSocket 
08-25 10:46:54.527  7511  7618 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-25 10:46:54.527  7511  7618 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19f24cf3
08-25 10:46:54.527  7511  7618 D BluetoothSocket: channel: 12
08-25 10:46:54.527  7511  7618 I BtOppRfcommListener: Accept thread started.
,08-25 10:46:54.527  1016  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-25 10:46:54.537  1016  1485 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:54.537  1016  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:54.537  1016  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-25 10:46:54.547  1016  1043 D Tethering: interfaceAdded wlan0
08-25 10:46:54.547  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 10:46:54.547  1954  7615 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
08-25 10:46:54.547  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 10:46:54.547  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 10:46:54.547  1016  1129 E Tethering: No numeric data
08-25 10:46:54.547  1016  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 10:46:54.547  1016  1129 D Tethering: clearTetheredNotification()
08-25 10:46:54.547  1016  1129 D Tethering: InitialState.processMessage what=4
08-25 10:46:54.547  1016  1129 E Tethering: No numeric data
,08-25 10:46:54.557  1016  1043 D Tethering: interfaceAdded p2p0
08-25 10:46:54.557  1016  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-25 10:46:54.557  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:54.557  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-25 10:46:54.557  1016  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
,08-25 10:46:54.557  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 10:46:54.557  1016  1129 D Tethering: clearTetheredNotification()
08-25 10:46:54.557  1176  1176 D HotspotTile: updateTetherState():false, false
08-25 10:46:54.557  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 10:46:54.557  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 10:46:54.557  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 10:46:54.557  1176  1176 D HotspotTile: updateTetherState():false, false
08-25 10:46:54.557  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:54.557  1016  1121 V NetworkStats: performPollLocked() took 6ms
,08-25 10:46:54.557  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
08-25 10:46:54.557  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:54.567  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 10:46:54.567  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-25 10:46:54.567  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 10:46:54.567  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
08-25 10:46:54.567  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 10:46:54.567  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:54.567  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:54.567   276  1015 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-25 10:46:54.567   276  1015 D SoftapController: Softap fwReload - Ok
,08-25 10:46:54.567  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:54.567  1016  1121 V NetworkStats: performPollLocked() took 4ms
,08-25 10:46:54.567   276  1015 D CommandListener: Setting iface cfg
,08-25 10:46:54.567   276  1015 D CommandListener: Trying to bring down wlan0
08-25 10:46:54.567  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:54.567  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:54.567   276  1015 D CommandListener: Clearing all IP addresses on wlan0
,08-25 10:46:54.567  1016  1124 E WifiHW  : supplicant_name : p2p_supplicant,
,08-25 10:46:54.607  7620  7620 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-25 10:46:54.607  7620  7620 I wpa_supplicant: Successfully initialized wpa_supplicant
08-25 10:46:54.607  7620  7620 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-25 10:46:54.617  7620  7620 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-25 10:46:54.617   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7620
08-25 10:46:54.617   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-25 10:46:54.617  7620  7620 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-25 10:46:54.617  7620  7620 I wpa_supplicant: ssSupport state is = 1
08-25 10:46:54.617  7620  7620 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-25 10:46:54.617  7620  7620 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-25 10:46:54.617   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7620
08-25 10:46:54.617   380   380 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-25 10:46:54.677  1016  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
08-25 10:46:54.677  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 10:46:54.677  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
08-25 10:46:54.677  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:54.677  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:54.677  1176  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-25 10:46:54.677  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:54.677  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 10:46:54.677  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:54.677  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 10:46:54.677  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-25 10:46:54.677  1176  1176 D HotspotTile: onReceive : 2, 0
,08-25 10:46:54.687  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-25 10:46:54.687  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:54.687  1016  1549 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 10:46:54.687  1016  1549 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 10:46:54.697  1016  1549 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:54.697  1016  1549 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:54.697  1016  1549 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 10:46:54.697  2201  2201 I Hs20UtilService: Starting #19,
08-25 10:46:54.697  2201  2218 I Hs20UtilService: Message received 5011
08-25 10:46:54.697  6540  6540 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-25 10:46:54.697  6540  6540 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 10:46:54.697  6540  6540 D SecurityLogAgent: StateMachine : Current State = 1
08-25 10:46:54.697  6540  6540 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 10:46:54.777   380   380 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-25 10:46:54.777  7620  7620 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-25 10:46:54.817  7620  7620 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-25 10:46:54.827  7620  7620 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-25 10:46:54.837  7620  7620 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-25 10:46:54.837   380   380 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7620
08-25 10:46:54.837   380   380 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-25 10:46:54.837  7620  7620 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-25 10:46:54.837  7620  7620 I wpa_supplicant: ssSupport state is = 1
08-25 10:46:54.837  7620  7620 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 10:46:54.837  7620  7620 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 10:46:54.837  7620  7620 E wpa_supplicant: SIM READ ERROR,
08-25 10:46:54.837  7620  7620 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 10:46:54.837  7620  7620 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 10:46:54.837  7620  7620 E wpa_supplicant: SIM READ ERROR
08-25 10:46:54.837  7620  7620 I wpa_supplicant: Blacklist: Clear (all) ,
08-25 10:46:54.837  7620  7620 I wpa_supplicant: wpa_default_ap_write_once
08-25 10:46:54.837  7620  7620 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-25 10:46:54.837  7620  7620 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 10:46:54.837  7620  7620 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-25 10:46:54.837  7620  7620 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 10:46:54.837  7620  7620 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-25 10:46:54.837  7620  7620 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 10:46:54.837  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-25 10:46:54.837  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 10:46:54.837  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 10:46:54.877  7620  7620 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-25 10:46:54.927   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-25 10:46:55.107  7620  7620 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-25 10:46:55.107  7620  7620 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-25 10:46:55.127  7620  7620 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-25 10:46:55.127   380   380 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7620
08-25 10:46:55.127   380   380 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-25 10:46:55.127  7620  7620 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-25 10:46:55.127  7620  7620 I wpa_supplicant: ssSupport state is = 1
,08-25 10:46:55.127  7620  7620 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-25 10:46:55.127  7620  7620 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-25 10:46:55.137  7620  7620 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-25 10:46:55.137   380   380 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7620
08-25 10:46:55.137   380   380 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-25 10:46:55.137  7620  7620 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-25 10:46:55.137  7620  7620 I wpa_supplicant: ssSupport state is = 1,
08-25 10:46:55.137  7620  7620 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 10:46:55.137  7620  7620 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-25 10:46:55.137  7620  7620 E wpa_supplicant: SIM READ ERROR
,08-25 10:46:55.137  7620  7620 I wpa_supplicant: wpa_default_ap_write_once,
,08-25 10:46:55.147  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 10:46:55.137  7620  7620 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-25 10:46:55.147  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 10:46:55.137  7620  7620 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 10:46:55.147  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-25 10:46:55.147  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
08-25 10:46:55.147  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-25 10:46:55.147  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-25 10:46:55.307  7620  7620 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-25 10:46:55.307  7620  7620 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-25 10:46:55.387  7620  7620 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-25 10:46:55.387  7620  7620 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
08-25 10:46:55.387  7620  7620 I wpa_supplicant: Skip scan - bUseNetwork false
,08-25 10:46:55.397  1016  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-25 10:46:55.397  1016  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-25 10:46:55.397  7620  7620 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-25 10:46:55.397  7620  7620 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-25 10:46:55.397  7620  7620 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-25 10:46:55.397  7620  7620 E wpa_supplicant: SIM READ ERROR
08-25 10:46:55.397  7620  7620 I wpa_supplicant: Blacklist: Clear (all) 
,08-25 10:46:55.427  7620  7620 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-25 10:46:55.437  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-25 10:46:55.437  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 10:46:55.437  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:55.437  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:55.437  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:55.437  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:55.437  7620  7620 I wpa_supplicant: Skip scan - bUseNetwork false
08-25 10:46:55.437  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 10:46:55.437  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-25 10:46:55.447  1016  1124 D WifiConfigStore: Loading config and enabling all networks 
08-25 10:46:55.447  1176  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-25 10:46:55.447  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-25 10:46:55.447  1176  1176 D HotspotTile: onReceive : 3, 0
,08-25 10:46:55.447  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-25 10:46:55.457  1016  1550 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 10:46:55.457  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 10:46:55.457  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:55.457  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:55.457  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:55.457  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:55.457  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:55.457  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:55.457  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:55.457  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:55.457  6741  6741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:55.467  1016  1124 E WifiConfigStore: Not a HS20
,08-25 10:46:55.467  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:55.467  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 10:46:55.467  1016  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 10:46:55.467  6741  6741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:46:55.467  2201  2201 I Hs20UtilService: Starting #20
,08-25 10:46:55.467  2201  2218 I Hs20UtilService: Message received 5011
,08-25 10:46:55.467  1016  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-25 10:46:55.467  6540  6540 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-25 10:46:55.467  6540  6540 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-25 10:46:55.467  6540  6540 D SecurityLogAgent: StateMachine : Current State = 1
,08-25 10:46:55.467  6540  6540 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-25 10:46:55.477  1016  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-25 10:46:55.477  7620  7620 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-25 10:46:55.477  7620  7620 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-25 10:46:55.477  7620  7620 I wpa_supplicant: reset timer : RESET_TIMER 0
08-25 10:46:55.477  7620  7620 I wpa_supplicant: P2P: Current p2p state = IDLE
08-25 10:46:55.477  7620  7620 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-25 10:46:55.477  7620  7620 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-25 10:46:55.477  7620  7620 I wpa_supplicant: First Scan Start
,08-25 10:46:55.477  7620  7620 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-25 10:46:55.477  1016  1124 D WifiNative-wlan0: Setting external_sim to 1
,08-25 10:46:55.477  1016  1124 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 10:46:55.477  1016  1124 I WifiNative-HAL: startHal
08-25 10:46:55.477  1016  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9e9d588c
08-25 10:46:55.477  1016  1124 I WifiNative-HAL: Could not start hal
,08-25 10:46:55.477  1016  1124 E WifiNative-wlan0: do suspend true
,08-25 10:46:55.487  6980  6980 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 10:46:55.487  1016  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3,
08-25 10:46:55.487  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 10:46:55.487  1016  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
08-25 10:46:55.487  1016  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:46:55.487  1016  1148 I WifiNative-HAL: startHal
08-25 10:46:55.487  1016  1148 E wifi    : getStaticLongField sWifiHalHandle 0x98ffe9bc
08-25 10:46:55.487  1016  1148 I WifiNative-HAL: Could not start hal
08-25 10:46:55.487  1016  1148 E WifiScanningService: could not start HAL
,08-25 10:46:55.487  1016  1016 D RttService: SCAN_AVAILABLE : 3
08-25 10:46:55.487  1016  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 10:46:55.487   276  1015 D CommandListener: Setting iface cfg
08-25 10:46:55.487   276  1015 D CommandListener: Trying to bring up p2p0
,08-25 10:46:55.487  1016  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-25 10:46:55.487  1016  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 10:46:55.487  1016  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 10:46:55.487  1016  1124 E WifiNative-wlan0: invaild command id : 215
,08-25 10:46:55.487  1016  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-25 10:46:55.487  1016  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-25 10:46:55.487  1016  1124 E WifiNative-wlan0: invaild command id : 215
,08-25 10:46:55.487  1016  1123 D WifiP2pService: P2pEnablingState
,08-25 10:46:55.487  1016  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
08-25 10:46:55.487  7620  7620 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-25 10:46:55.487  1016  1123 D WifiP2pService: P2p socket connection successful
08-25 10:46:55.487  1016  1123 D WifiP2pService: P2pEnabledState
,08-25 10:46:55.497  7620  7620 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-25 10:46:55.497  7620  7620 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-25 10:46:55.497  1016  1124 E WifiStateMachine: Failed to set frequency band 0
,08-25 10:46:55.497  1016  1126 E ConnectivityService: updateNetworkInfo(),
08-25 10:46:55.497  1016  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-25 10:46:55.497  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-25 10:46:55.497  1016  1124 D SecContentProvider2: mCursor = null
08-25 10:46:55.497  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-25 10:46:55.497  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-25 10:46:55.497  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 10:46:55.497  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-25 10:46:55.497  1016  1124 D SecContentProvider2: mCursor = null
08-25 10:46:55.497  1016  1046 D WifiDisplayController: disconnect
08-25 10:46:55.497  1016  1046 D WifiDisplayController: updateConnection
08-25 10:46:55.497  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-25 10:46:55.497  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 10:46:55.497  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-25 10:46:55.497  1016  1028 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-25 10:46:55.507  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-25 10:46:55.507  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 10:46:55.507  1016  1123 D WifiNative-p2p0: p2pGetDeviceAddress
08-25 10:46:55.507  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-25 10:46:55.507  1016  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-25 10:46:55.507  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-25 10:46:55.507  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-25 10:46:55.507  1016  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-25 10:46:55.507  1016  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-25 10:46:55.507  1016  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-25 10:46:55.507  1016  1046 D WifiDisplayController:  secondary type: null
08-25 10:46:55.507  1016  1046 D WifiDisplayController:  wps: 0
08-25 10:46:55.507  1016  1046 D WifiDisplayController:  grpcapab: 0
08-25 10:46:55.507  1016  1046 D WifiDisplayController:  devcapab: 0
08-25 10:46:55.507  1016  1046 D WifiDisplayController:  status: 3
08-25 10:46:55.507  1016  1046 D WifiDisplayController:  wfdInfo: null
08-25 10:46:55.507  1016  1046 D WifiDisplayController:  groupownerAddress: null
08-25 10:46:55.507  1016  1046 D WifiDisplayController:  GOdeviceName: null
08-25 10:46:55.507  1016  1046 D WifiDisplayController:  interfaceAddress: 
08-25 10:46:55.507  1016  1046 D WifiDisplayController:  SConnectInfo : null
08-25 10:46:55.507  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 10:46:55.507  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 10:46:55.507  1016  1123 D WifiP2pService: DeviceAddress: 0a:76:28
,08-25 10:46:55.507  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 10:46:55.517  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 10:46:55.517  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 10:46:55.517  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 10:46:55.517  1315  2242 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 10:46:55.517  7003  7003 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 10:46:55.517  7003  7003 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-25 10:46:55.517  7003  7003 D FileShare-Client: Outbound.stopDelayTimer - 
,08-25 10:46:55.517  7018  7018 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-25 10:46:55.537  1016  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-25 10:46:55.537  1016  1123 D WifiP2pService: InactiveState
,08-25 10:46:55.537  1016  1123 D WifiP2pService: InactiveState{ what=143376 }
,08-25 10:46:55.537  1016  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 10:46:55.537  7620  7620 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-25 10:46:55.537  1016  1123 D WifiP2pService: InactiveState{ what=143376 }
,08-25 10:46:55.537  1016  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-25 10:46:55.547  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-25 10:46:55.547  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-25 10:46:55.547  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-25 10:46:56.217  6741  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 10:46:56.217  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:56.217  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:56.217  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:56.217  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:56.217  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:56.217  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:56.217  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:56.217  6741  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:56.227  6741  6794 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-25 10:46:56.227  6741  6794 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-25 10:46:56.227  6741  6794 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3b77dc7f Bundle[{}]
,08-25 10:46:56.227  6741  6794 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 10:46:56.227  6741  6794 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-25 10:46:56.237  6741  6794 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-25 10:46:56.237  6741  6794 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-25 10:46:56.237  6741  6794 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-25 10:46:56.237  6741  6794 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 10:46:56.237  6741  6794 I System.out: Running OutgoingSocketThread
,08-25 10:46:56.247  6741  7628 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1329)
,08-25 10:46:56.247  6741  7628 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 52927
,08-25 10:46:56.247  6741  7628 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 10:46:56.747  7620  7620 I wpa_supplicant: nl80211: Received scan results (36 BSSes),
,08-25 10:46:56.747  7620  7620 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-25 10:46:56.747  7620  7620 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-25 10:46:56.747  7620  7620 I wpa_supplicant: Trying to associate with  'G700'
08-25 10:46:56.747  7620  7620 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-25 10:46:56.747  7620  7620 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-25 10:46:56.757  1016  7625 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-25 10:46:56.767  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
,08-25 10:46:56.767  1016  1124 D SecContentProvider2: mCursor = null
,08-25 10:46:56.867  7620  7620 E wpa_supplicant: Cmd 35605 not handled
,08-25 10:46:56.867  7620  7620 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-25 10:46:56.867  7620  7620 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-25 10:46:56.867  7620  7620 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-25 10:46:56.867  7620  7620 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-25 10:46:56.867  7620  7620 I wpa_supplicant: Associated with F4.99.3E
08-25 10:46:56.867  7620  7620 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-25 10:46:56.867  7620  7620 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-25 10:46:56.867  7620  7620 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-25 10:46:56.867   289   289 E SMD     : DCD OFF
,08-25 10:46:56.867  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 10:46:56.877  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 10:46:56.877  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 10:46:56.877  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-25 10:46:56.877  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-25 10:46:56.877  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-25 10:46:56.877  7620  7620 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-25 10:46:56.877  7620  7620 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-25 10:46:56.877  7620  7620 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-25 10:46:56.877  7620  7620 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-25 10:46:56.877  7620  7620 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 10:46:56.877  7620  7620 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-25 10:46:56.877  7620  7620 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-25 10:46:56.877  7620  7620 I wpa_supplicant: Blacklist: Clear (temp) 
08-25 10:46:56.877  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-25 10:46:56.877  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-25 10:46:56.877  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-25 10:46:56.877  7620  7620 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-25 10:46:56.887  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-25 10:46:56.887  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-25 10:46:56.887  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
08-25 10:46:56.887  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-25 10:46:56.887  1016  1124 D SecContentProvider2: mCursor = null
,08-25 10:46:56.887  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-25 10:46:56.887  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-25 10:46:56.887  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
08-25 10:46:56.887  1016  1129 E Tethering: No numeric data
,08-25 10:46:56.887  1016  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 10:46:56.887  1016  1129 D Tethering: clearTetheredNotification()
,08-25 10:46:56.897  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
08-25 10:46:56.897  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:56.897  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-25 10:46:56.897  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 10:46:56.897  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 10:46:56.897  1176  1176 D HotspotTile: updateTetherState():false, false
,08-25 10:46:56.897  1016  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-25 10:46:56.897  1016  1121 V NetworkStats: performPollLocked() took 8ms
,08-25 10:46:56.897  1016  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,08-25 10:46:56.897  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:56.907  1016  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-25 10:46:56.907  1016  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-25 10:46:56.907  1016  1126 E ConnectivityService: updateNetworkInfo()
,08-25 10:46:56.907  1016  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-25 10:46:56.917  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 10:46:56.917  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-25 10:46:56.917  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:56.917  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:56.917  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:56.917  1016  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 10:46:56.917  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:56.917  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:56.917  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:56.917  1016  1550 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 10:46:56.917  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 10:46:56.917  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:56.917  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:56.917  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 10:46:56.927  2201  2201 I Hs20UtilService: Starting #21
,08-25 10:46:56.927  2201  2218 I Hs20UtilService: Message received 5007
,08-25 10:46:56.927  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 10:46:56.927  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 10:46:56.927  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-25 10:46:56.927  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-25 10:46:56.927  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-25 10:46:56.927  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-25 10:46:56.927  1315  2242 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-25 10:46:56.937  1016  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 10:46:56.947   276  1015 D CommandListener: Setting iface cfg
,08-25 10:46:56.947  1016  1124 E WifiStateMachine: Start Dhcp Watchdog 3
,08-25 10:46:56.947  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 10:46:56.947  1016  1124 D SecContentProvider2: mCursor = null
,08-25 10:46:56.957  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 10:46:56.957  1016  1124 D SecContentProvider2: mCursor = null
,08-25 10:46:56.957  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 10:46:56.967  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-25 10:46:56.967  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:56.967  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:56.967  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:56.967  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:56.967  1016  1124 E WifiNative-wlan0: do suspend false
,08-25 10:46:56.967  1016  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-25 10:46:56.977  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-25 10:46:56.977  1016  1124 D SecContentProvider2: mCursor = null
,08-25 10:46:56.977  1016  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 10:46:57.197  7633  7633 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-25 10:46:57.197  7633  7633 I dhcpcd  : version 5.5.6 starting
,08-25 10:46:57.197  7633  7633 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-25 10:46:57.247  6741  6794 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1330),
08-25 10:46:57.247  6741  6794 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1330)
08-25 10:46:57.247  6741  6794 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1335)
,08-25 10:46:57.247  6741  6794 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-25 10:46:57.247  6741  6794 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1336)
08-25 10:46:57.247  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-25 10:46:57.247  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@153c2cac added. We now have 2 listener(s)
,08-25 10:46:57.257  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 10:46:57.257  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:46:57.257  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:46:57.257  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-25 10:46:57.257  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19439d75 added. We now have 9 listener(s)
08-25 10:46:57.257  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:46:57.257  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 10:46:57.267  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:46:57.267  6741  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:57.267  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:57.267  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:57.267  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:57.267  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:57.267  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:57.267  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:57.267  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:57.277  7633  7633 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-25 10:46:57.277  7633  7633 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-25 10:46:57.277  7633  7633 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-25 10:46:57.277  7633  7633 I dhcpcd  : bssid match
08-25 10:46:57.277  7633  7633 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-25 10:46:57.277  6741  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:57.277  6741  6794 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 10:46:57.277  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:57.277  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:57.277  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 10:46:57.277  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b5a0d7b added. We now have 3 listener(s)
,08-25 10:46:57.287  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 10:46:57.287  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 10:46:57.287  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 10:46:57.287  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:46:57.287  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d956798 added. We now have 10 listener(s)
,08-25 10:46:57.287  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:46:57.287  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:57.287  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 10:46:57.287  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 10:46:57.287  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:57.287  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:57.287  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:46:57.287  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 10:46:57.287  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@153c2cac removed from the list
08-25 10:46:57.287  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:46:57.287  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19439d75 removed from the list
08-25 10:46:57.287  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 10:46:57.287  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:57.287  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:57.287  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:57.297  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 10:46:57.297  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:57.297  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:46:57.297  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19439d75 not in the list
,08-25 10:46:57.297  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:57.297  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:57.297  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 10:46:57.297  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:57.297  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:46:57.297  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d956798 removed from the list
08-25 10:46:57.297  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 10:46:57.297  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:57.297  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:57.297  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:46:57.297  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b5a0d7b removed from the list
,08-25 10:46:57.297  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 10:46:57.297  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5bd9bf1 added. We now have 2 listener(s)
,08-25 10:46:57.307  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 10:46:57.307  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 10:46:57.307  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:46:57.307  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 10:46:57.307  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a503d6 added. We now have 9 listener(s)
08-25 10:46:57.307  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:46:57.307  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 10:46:57.307  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:46:57.317  6741  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:57.317  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:57.317  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:57.317  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:57.317  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:57.317  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:57.317  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:57.317  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:57.317  6741  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:46:57.317  6741  6794 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 10:46:57.317  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:46:57.317  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19456544 added. We now have 3 listener(s)
,08-25 10:46:57.317  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:57.317  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 10:46:57.317  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:46:57.317  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:46:57.317  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:46:57.317  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dff062d added. We now have 10 listener(s)
08-25 10:46:57.317  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:46:57.317  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:46:57.317  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 10:46:57.317  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 10:46:57.317  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:46:57.317  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 10:46:57.317  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:57.317  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 10:46:57.327  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 10:46:57.327  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 10:46:57.327  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 10:46:57.327  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 10:46:57.327  6741  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 10:46:57.327  7511  7607 D BtGatt.GattService: registerClient() - UUID=dabfb454-6404-45b7-8fc5-68180c54ecf7
,08-25 10:46:57.377  7633  7633 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
08-25 10:46:57.377  7511  7539 D BtGatt.GattService: onClientRegistered() - UUID=dabfb454-6404-45b7-8fc5-68180c54ecf7, clientIf=6
,08-25 10:46:57.377  6741  6750 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-25 10:46:57.377  7511  7528 D BtGatt.GattService: start scan with filters
08-25 10:46:57.377  7511  7544 D BtGatt.ScanManager: handling starting scan
,08-25 10:46:57.377  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 10:46:57.377  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 10:46:57.377  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 10:46:57.377  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 10:46:57.387  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 10:46:57.387  6741  6741 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 10:46:57.387  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 10:46:57.387  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 10:46:57.397  7511  7544 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1091718f
,08-25 10:46:57.397  7511  7539 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-25 10:46:57.397  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 10:46:57.397  7511  7544 D BtGatt.ScanManager: allow scan with filters
08-25 10:46:57.397  6741  6794 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 10:46:57.397  7511  7544 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 10:46:57.397  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:57.397  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 10:46:57.397  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:57.397  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 10:46:57.397  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 10:46:57.397  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 10:46:57.397  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 10:46:57.397  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 10:46:57.397  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 10:46:57.397  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 10:46:57.397  7511  7544 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-25 10:46:57.397  7511  7539 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-25 10:46:57.397  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 10:46:57.397  7511  7544 D BtGatt.ScanManager: Starting BLE batch scan
,08-25 10:46:57.397  7511  7544 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 10:46:57.407  7511  7606 D BtGatt.GattService: stopScan() - queue size =1
,08-25 10:46:57.407  7511  7539 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-25 10:46:57.407  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:57.407  7511  7527 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 10:46:57.407  7511  7539 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-25 10:46:57.407  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:57.407  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:46:57.407  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 10:46:57.407  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 10:46:57.407  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 10:46:57.407  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 10:46:57.417  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 10:46:57.417  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 10:46:57.417  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 10:46:57.417  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 10:46:57.417  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:46:57.417  7511  7544 D BtGatt.ScanManager: filter size is 1
,08-25 10:46:57.417  7511  7544 D BtGatt.ScanManager: delete FilterIndex - 3
,08-25 10:46:57.417  7511  7539 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-25 10:46:57.417  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:57.417  7511  7544 D BtGatt.ScanManager: stopping BLe Batch
,08-25 10:46:57.427  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-25 10:46:57.427  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:46:57.427  6741  6741 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 10:46:57.427  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:57.427  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:57.427  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:57.427  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:57.427  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:57.427  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:46:57.427  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:46:57.427  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5bd9bf1 removed from the list
08-25 10:46:57.427  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:57.427  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a503d6 removed from the list
08-25 10:46:57.427  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:57.427  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:57.427  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:57.427  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:57.427  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:57.427  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:57.427  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:57.427  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a503d6 not in the list
08-25 10:46:57.427  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:57.427  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:57.427  7511  7539 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-25 10:46:57.427  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 10:46:57.427  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:57.427  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:57.427  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:57.427  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dff062d removed from the list
08-25 10:46:57.427  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:57.427  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:57.427  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) l,eft
08-25 10:46:57.427  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:46:57.427  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19456544 removed from the list
08-25 10:46:57.427  7511  7544 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-25 10:46:57.427  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:46:57.427  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3372d829 added. We now have 2 listener(s)
08-25 10:46:57.437  7511  7539 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-25 10:46:57.437  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:57.437  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 10:46:57.447  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:46:57.447  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:46:57.447  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:46:57.447  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e78b7ae added. We now have 9 listener(s)
08-25 10:46:57.447  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:46:57.447  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 10:46:57.447  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:46:57.457  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-25 10:46:57.457  6741  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:57.457  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:57.457  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:57.457  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:57.457  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:57.457  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:57.457  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:57.457  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:57.457  1016  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-25 10:46:57.457  1016  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-25 10:46:57.457  1016  1028 D BatteryService: stay LED for fully charged
08-25 10:46:57.457  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-25 10:46:57.457  1016  1016 I MotionRecognitionService: Plugged
,08-25 10:46:57.457  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-25 10:46:57.467  7633  7633 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-25 10:46:57.467  6741  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:57.467  6741  6794 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:46:57.467  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:46:57.467  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29fa18dc added. We now have 3 listener(s)
,08-25 10:46:57.467  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-25 10:46:57.467  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-25 10:46:57.477  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-25 10:46:57.477  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-25 10:46:57.477  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:57.477  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:57.507  7511  7511 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-25 10:46:57.507  7511  7548 D HeadsetStateMachine: Disconnected process message: 10
08-25 10:46:57.507  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-25 10:46:57.507  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-25 10:46:57.507  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-25 10:46:57.507  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-25 10:46:57.507  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:46:57.507  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:46:57.507  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-25 10:46:57.507  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2937cde5 added. We now have 10 listener(s)
08-25 10:46:57.507  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:46:57.507  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-25 10:46:57.507  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:46:57.507  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 10:46:57.507  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-25 10:46:57.507  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:46:57.507  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,08-25 10:46:57.517  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-25 10:46:57.527  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 10:46:57.527  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 10:46:57.527  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 10:46:57.527  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 10:46:57.527  6741  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
08-25 10:46:57.537  7511  7541 D BtGatt.GattService: registerClient() - UUID=9f02715c-c894-4114-8725-0d26e0f55c4d
,08-25 10:46:57.577  7511  7539 D BtGatt.GattService: onClientRegistered() - UUID=9f02715c-c894-4114-8725-0d26e0f55c4d, clientIf=6
,08-25 10:46:57.577  6741  6749 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-25 10:46:57.577  7511  7606 D BtGatt.GattService: start scan with filters,
08-25 10:46:57.577  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 10:46:57.577  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 10:46:57.577  7511  7544 D BtGatt.ScanManager: handling starting scan
,08-25 10:46:57.577  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 10:46:57.577  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 10:46:57.577  7511  7539 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-25 10:46:57.577  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:57.577  7511  7544 D BtGatt.ScanManager: allow scan with filters
08-25 10:46:57.577  7511  7544 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 10:46:57.577  7511  7544 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-25 10:46:57.587  7511  7539 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
08-25 10:46:57.587  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 10:46:57.587  7511  7544 D BtGatt.ScanManager: Starting BLE batch scan
08-25 10:46:57.587  7511  7544 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 10:46:57.587  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 10:46:57.587  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 10:46:57.587  6741  6741 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 10:46:57.587  7511  7539 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-25 10:46:57.587  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:57.587  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 10:46:57.597  7511  7539 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-25 10:46:57.597  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:57.597  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
08-25 10:46:57.597  6741  6794 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-25 10:46:57.597  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 10:46:57.597  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:57.597  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:57.607  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:57.607  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:57.607  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 10:46:57.607  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:46:57.607  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3372d829 removed from the list
08-25 10:46:57.607  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-25 10:46:57.607  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e78b7ae removed from the list
08-25 10:46:57.607  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:57.607  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-25 10:46:57.607  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-25 10:46:57.607  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 10:46:57.607  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:57.607  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:46:57.617  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:57.617  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:57.617  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:57.617  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e78b7ae not in the list
,08-25 10:46:57.617  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 10:46:57.617  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 10:46:57.617  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 10:46:57.617  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 10:46:57.617  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 10:46:57.617  7511  7541 D BtGatt.GattService: stopScan() - queue size =1,
08-25 10:46:57.617  7511  7544 D BtGatt.ScanManager: filter size is 1
08-25 10:46:57.617  7511  7544 D BtGatt.ScanManager: delete FilterIndex - 4
08-25 10:46:57.617  7511  7527 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 10:46:57.617  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:46:57.617  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 10:46:57.617  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 10:46:57.617  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 10:46:57.617  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 10:46:57.627  7511  7539 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 10:46:57.627  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 10:46:57.627  7511  7544 D BtGatt.ScanManager: stopping BLe Batch
,08-25 10:46:57.627  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-25 10:46:57.627  7511  7539 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-25 10:46:57.627  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 10:46:57.627  7511  7544 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 10:46:57.627  7511  7539 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-25 10:46:57.627  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:57.627  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 10:46:57.627  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 10:46:57.627  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 10:46:57.627  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:57.637  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:57.637  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,08-25 10:46:57.637  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-25 10:46:57.637  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2937cde5 removed from the list
08-25 10:46:57.637  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 10:46:57.637  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:57.637  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:57.637  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 10:46:57.637  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29fa18dc removed from the list
08-25 10:46:57.637  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:46:57.637  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 10:46:57.637  6741  6741 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 10:46:57.637  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:46:57.637  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b9c6361 added. We now have 2 listener(s)
08-25 10:46:57.637  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 10:46:57.637  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:46:57.637  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-25 10:46:57.637  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:46:57.637  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e40e86 added. We now have 9 listener(s)
08-25 10:46:57.637  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:46:57.637  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 10:46:57.637  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:46:57.647  6741  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:57.647  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:57.647  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:57.647  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:57.647  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:57.647  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:57.647  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:57.647  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 10:46:57.647  6741  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 10:46:57.657  6741  6794 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:46:57.657  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:46:57.657  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2beea774 added. We now have 3 listener(s)
,08-25 10:46:57.657  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-25 10:46:57.657  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:46:57.657  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:46:57.657  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:46:57.657  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@235ad49d added. We now have 10 listener(s)
08-25 10:46:57.657  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 10:46:57.657  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:46:57.657  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 10:46:57.657  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 10:46:57.657  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 10:46:57.657  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 10:46:57.657  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:57.657  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:57.657  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 10:46:57.667  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 10:46:57.667  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 10:46:57.677  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 10:46:57.677  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 10:46:57.677  6741  6794 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 10:46:57.677  7511  7606 D BtGatt.GattService: registerClient() - UUID=52fafb55-3283-4f22-b9aa-ff2514d8964d
,08-25 10:46:57.717  7511  7539 D BtGatt.GattService: onClientRegistered() - UUID=52fafb55-3283-4f22-b9aa-ff2514d8964d, clientIf=6
,08-25 10:46:57.717  6741  6749 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-25 10:46:57.717  7511  7607 D BtGatt.GattService: start scan with filters
,08-25 10:46:57.727  7511  7544 D BtGatt.ScanManager: handling starting scan,
08-25 10:46:57.727  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 10:46:57.727  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 10:46:57.727  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-25 10:46:57.727  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 10:46:57.727  7511  7539 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
,08-25 10:46:57.727  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 10:46:57.727  7511  7544 D BtGatt.ScanManager: allow scan with filters
,08-25 10:46:57.737  7511  7544 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-25 10:46:57.737  7511  7544 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-25 10:46:57.737  7511  7539 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-25 10:46:57.737  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:57.737  7511  7544 D BtGatt.ScanManager: Starting BLE batch scan
,08-25 10:46:57.737  7511  7544 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-25 10:46:57.737  7511  7539 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-25 10:46:57.737  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:57.737  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 10:46:57.737  6741  6741 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 10:46:57.747  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 10:46:57.747  7511  7539 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-25 10:46:57.747  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:57.747  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 10:46:57.757  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 10:46:57.757  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 10:46:57.757  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 10:46:57.757  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 10:46:57.757  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:57.757  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 10:46:57.757  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 10:46:57.757  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b9c6361 removed from the list
08-25 10:46:57.757  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:46:57.757  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e40e86 removed from the list
,08-25 10:46:57.767  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:57.767  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:46:57.767  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:57.767  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 10:46:57.767  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:57.767  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 10:46:57.767  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:57.767  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:57.767  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:57.767  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e40e86 not in the list
,08-25 10:46:57.767  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 10:46:57.767  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 10:46:57.767  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 10:46:57.767  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 10:46:57.767  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 10:46:57.767  7511  7528 D BtGatt.GattService: stopScan() - queue size =1
,08-25 10:46:57.767  7511  7544 D BtGatt.ScanManager: filter size is 1
,08-25 10:46:57.767  7511  7544 D BtGatt.ScanManager: delete FilterIndex - 5
,08-25 10:46:57.767  7511  7539 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-25 10:46:57.767  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:57.767  7511  7544 D BtGatt.ScanManager: stopping BLe Batch
08-25 10:46:57.767  7511  7527 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-25 10:46:57.767  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 10:46:57.767  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 10:46:57.767  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 10:46:57.767  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 10:46:57.767  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 10:46:57.777  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 10:46:57.777  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 10:46:57.777  6741  6794 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 10:46:57.777  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 10:46:57.777  7511  7539 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-25 10:46:57.777  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-25 10:46:57.777  7511  7544 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-25 10:46:57.777  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:57.777  7511  7539 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-25 10:46:57.777  7511  7539 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-25 10:46:57.777  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 10:46:57.777  6741  6741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 10:46:57.777  6741  6741 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 10:46:57.777  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:57.777  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:57.777  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 10:46:57.777  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@235ad49d removed from the list
08-25 10:46:57.777  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 10:46:57.787  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:57.787  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:57.787  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:46:57.787  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2beea774 removed from the list
,08-25 10:46:57.787  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 10:46:57.787  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30951d99 added. We now have 2 listener(s)
,08-25 10:46:57.787  1016  1124 E WifiNative-wlan0: do suspend true
,08-25 10:46:57.787  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 10:46:57.787  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 10:46:57.787  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 10:46:57.797  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:46:57.797  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bd8685e added. We now have 9 listener(s)
08-25 10:46:57.797  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:46:57.797  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 10:46:57.797  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 10:46:57.797  6741  6794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 10:46:57.797  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 10:46:57.797  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 10:46:57.797  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 10:46:57.797  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 10:46:57.797  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 10:46:57.797  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 10:46:57.797  6741  6794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 10:46:57.807  6741  6794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 10:46:57.807  6741  6794 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 10:46:57.807  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 10:46:57.807  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3710c added. We now have 3 listener(s)
,08-25 10:46:57.807  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:57.807  6741  6741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 10:46:57.807  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-25 10:46:57.807  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 10:46:57.807  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 10:46:57.807  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 10:46:57.807  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3990fa55 added. We now have 10 listener(s)
08-25 10:46:57.807  6741  6794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 10:46:57.807  6741  6794 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 10:46:57.807  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 10:46:57.807  6741  6794 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 10:46:57.807  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 10:46:57.807  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:57.807  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 10:46:57.807  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:46:57.807  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30951d99 removed from the list
08-25 10:46:57.807  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:57.807  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bd8685e removed from the list
08-25 10:46:57.807  6741  6794 D io.jxcore.node.ConnectivityMonitor: stop
08-25 10:46:57.807  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:57.807  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:57.807  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:57.807  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:57.817  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:57.817  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:57.817  6741  6794 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bd8685e not in the list
08-25 10:46:57.817  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:57.817  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 10:46:57.817  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 10:46:57.817  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 10:46:57.817  6741  6794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 10:46:57.817  6741  6794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3990fa55 removed from the list
08-25 10:46:57.817  6741  6794 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 10:46:57.817  6741  6794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 10:46:57.817  6741  6794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 10:46:57.817  6741  6794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 10:46:57.817  6741  6794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35e3710c removed from the list
,08-25 10:46:57.817  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 10:46:57.817  1016  1123 D WifiP2pService: InactiveState{ what=143375 }
08-25 10:46:57.817  1016  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-25 10:46:57.817  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 10:46:57.817  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 10:46:57.817  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 10:46:57.817  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-25 10:46:57.817  6741  6794 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 10:46:57.817  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 10:46:57.817  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 10:46:57.817  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:57.817  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:57.827  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:57.827  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:57.827  1016  1124 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-25 10:46:57.827  1016  1124 E WifiStateMachine: VerifyingLinkState enter
,08-25 10:46:57.827  1016  1126 E ConnectivityService: updateNetworkInfo()
,08-25 10:46:57.827  6741  7664 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1343, name: My test thread name)
08-25 10:46:57.827  6741  7664 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1343, thread name: My test thread name)
08-25 10:46:57.827  6741  7664 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1343, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 10:46:57.827  1016  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-25 10:46:57.827  1016  1126 D ConnectivityService: Adding iface wlan0 to network 504
,08-25 10:46:57.837  6741  7666 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1345, name: My test thread name)
,08-25 10:46:57.837  6741  7666 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1345, thread name: My test thread name)
08-25 10:46:57.837  6741  7666 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1345, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 10:46:57.837  1016  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-25 10:46:57.837  1016  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-25 10:46:57.837  1016  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-25 10:46:57.837  1016  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-25 10:46:57.837  1016  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-25 10:46:57.837  6741  6794 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80,
,08-25 10:46:57.837  6741  6794 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 10:46:57.837  6741  6794 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-25 10:46:57.837  6741  6794 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-25 10:46:57.837  6741  6794 D com.test.thalitest.ThaliTestRunner: Total duration: 23424 ms
08-25 10:46:57.837  6741  6794 I jxcore-log: Total number of executed tests:  80
08-25 10:46:57.837  6741  6794 I jxcore-log: ,
,08-25 10:46:57.837  6741  6794 I jxcore-log: Number of passed tests:  80
08-25 10:46:57.837  6741  6794 I jxcore-log: 
,08-25 10:46:57.837  6741  6794 I jxcore-log: Number of failed tests:  0
08-25 10:46:57.837  6741  6794 I jxcore-log: 
,08-25 10:46:57.837  6741  6794 I jxcore-log: Number of ignored tests:  0
08-25 10:46:57.837  6741  6794 I jxcore-log: 
08-25 10:46:57.837  6741  6794 I jxcore-log: Total duration:  23424
08-25 10:46:57.837  6741  6794 I jxcore-log: 
08-25 10:46:57.837  6741  6794 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 10:46:57.837  6741  6794 I jxcore-log: 
08-25 10:46:57.847  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:46:57.847  6741  6794 I jxcore-log: 
,08-25 10:46:57.847  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 10:46:57.847  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 10:46:57.847  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:57.847  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:57.847  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:57.847  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:57.847  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:46:57.847  6741  6794 I jxcore-log: 
08-25 10:46:57.857  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:46:57.857  6741  6794 I jxcore-log: 
08-25 10:46:57.857  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:46:57.857  6741  6794 I jxcore-log: 
08-25 10:46:57.857  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:46:57.857  6741  6794 I jxcore-log: 
08-25 10:46:57.857  1016  1124 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-25 10:46:57.857  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:46:57.857  6741  6794 I jxcore-log: 
08-25 10:46:57.867  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 10:46:57.867  6741  6794 I jxcore-log: 
08-25 10:46:57.867  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 10:46:57.867  6741  6794 I jxcore-log: 
08-25 10:46:57.867  1016  1126 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-25 10:46:57.867  1016  1382 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 10:46:57.867  1016  1382 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-25 10:46:57.867  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 10:46:57.867  6741  6794 I jxcore-log: 
08-25 10:46:57.867  1016  1382 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:57.867  1016  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:57.867  1016  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 10:46:57.867  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 10:46:57.867  6741  6794 I jxcore-log: 
08-25 10:46:57.867  1016  1126 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
08-25 10:46:57.867  6741  6741 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 10:46:57.867  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 10:46:57.867  6741  6794 I jxcore-log: 
08-25 10:46:57.867  2201  2201 I Hs20UtilService: Starting #22
08-25 10:46:57.867  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 10:46:57.867  6741  6794 I jxcore-log: 
08-25 10:46:57.867  2201  2218 I Hs20UtilService: Message received 5007
08-25 10:46:57.867  1016  1126 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-25 10:46:57.867  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-25 10:46:57.867  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 10:46:57.867  6741  6794 I jxcore-log: 
08-25 10:46:57.867  1016  1126 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 10:46:57.867  1016  1126 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-25 10:46:57.877  1016  1126 D ConnectivityService: LTETest block dns file not exists
08-25 10:46:57.877  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 10:46:57.877  6741  6794 I jxcore-log: 
08-25 10:46:57.877  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 10:46:57.877  6741  6794 I jxcore-log: 
08-25 10:46:57.877  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 10:46:57.877  6741  6794 I jxcore-log: 
08-25 10:46:57.877  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 10:46:57.877  6741  6794 I jxcore-log: 
08-25 10:46:57.877  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 10:46:57.877  6741  6794 I jxcore-log: 
,08-25 10:46:57.877  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 10:46:57.877  6741  6794 I jxcore-log: 
08-25 10:46:57.877  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 10:46:57.877  6741  6794 I jxcore-log: 
,08-25 10:46:57.877  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 10:46:57.877  6741  6794 I jxcore-log: 
08-25 10:46:57.877  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 10:46:57.877  6741  6794 I jxcore-log: 
08-25 10:46:57.877  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 10:46:57.877  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-25 10:46:57.877  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:57.877  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:57.877  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:57.877  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:57.877  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 10:46:57.877  6741  6794 I jxcore-log: 
08-25 10:46:57.877  1016  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 10:46:57.877  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 10:46:57.877  6741  6794 I jxcore-log: 
08-25 10:46:57.877  1016  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 10:46:57.877  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 10:46:57.877  6741  6794 I jxcore-log: 
,08-25 10:46:57.877  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 10:46:57.877  6741  6794 I jxcore-log: 
08-25 10:46:57.887  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-25 10:46:57.887  1016  1016 I WifiTrafficPoller: mBoosterFLAG : 0
,08-25 10:46:57.887  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 10:46:57.887  6741  6794 I jxcore-log: 
08-25 10:46:57.887  1016  1016 I WifiTrafficPoller: current booster mode : FullMode
,08-25 10:46:57.887  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-25 10:46:57.887  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 10:46:57.887  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:57.887  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:57.887  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:57.887  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:57.897  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-25 10:46:57.897  1315  1315 I NearbySettings: MountReceiver.onReceive - Keep current state
08-25 10:46:57.897  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:57.897  1016  1126 V NetworkStats: updateIfacesLocked()
08-25 10:46:57.897  1016  1126 V NetworkStats: performPollLocked(flags=0x1)
08-25 10:46:57.897  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 10:46:57.897  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 10:46:57.897  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:57.897  1016  1126 V NetworkStats: performPollLocked() took 4ms
,08-25 10:46:57.907  1016  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-25 10:46:57.907  1016  1126 E ConnectivityService: updateNetworkInfo()
08-25 10:46:57.907  1016  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 10:46:57.907  1016  1126 E ConnectivityService: updateNetworkInfo()
08-25 10:46:57.907  1016  1126 V NetworkStats: updateIfacesLocked()
08-25 10:46:57.907  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:57.907  1016  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-25 10:46:57.907  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:57.907  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:57.907  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 10:46:57.907  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 10:46:57.917  1016  1126 V NetworkStats: performPollLocked() took 5ms
08-25 10:46:57.917  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:57.917  1016  1134 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-25 10:46:57.917  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 10:46:57.917  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:57.917  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:57.917  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-25 10:46:57.917  1016  1126 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-25 10:46:57.917  2201  2201 I Hs20UtilService: Starting #23
08-25 10:46:57.917  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:57.917  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:57.917  2201  2218 I Hs20UtilService: Message received 5007
08-25 10:46:57.917  1016  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-25 10:46:57.917  1016  7629 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:46:57.917  1016  7629 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-25 10:46:57.917  1016  7629 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 10:46:57.917  1016  7629 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-25 10:46:57.917  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 10:46:57.917  1016  7629 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 10:46:57.917  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-25 10:46:57.917  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-25 10:46:57.917   276  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 10:46:57.917   276  1011 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-25 10:46:57.917  1016  1126 D ConnectivityService:    accepting network in place of null
08-25 10:46:57.927  1016  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-25 10:46:57.927  1016  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-25 10:46:57.927  6741  6741 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 10:46:57.927  1016  1126 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-25 10:46:57.927  1443  1443 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-25 10:46:57.927  1016  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 10:46:57.927  1016  1126 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 10:46:57.927  1016  1126 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-25 10:46:57.927  1443  1443 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 10:46:57.927  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-25 10:46:57.927  1016  1129 D Tethering: MasterInitialState.processMessage what=3
08-25 10:46:57.927  1016  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-25 10:46:57.927  1016  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-25 10:46:57.927  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 10:46:57.927  6741  6794 I jxcore-log: 
08-25 10:46:57.927  1176  1711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 10:46:57.927  4811  6803 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-25 10:46:57.927  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:57.927  1016  1121 V NetworkStats: updateIfacesLocked()
08-25 10:46:57.927  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 10:46:57.927  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
08-25 10:46:57.927  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-25 10:46:57.927  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:57.927  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-25 10:46:57.927  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-25 10:46:57.927  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-25 10:46:57.937  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:57.937  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:57.937  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:57.937  1016  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-25 10:46:57.937  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
08-25 10:46:57.937  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-25 10:46:57.937  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,08-25 10:46:57.937  1176  1176 D StatusBar.NetworkController: updateDataNetType()
08-25 10:46:57.937  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-25 10:46:57.937  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-25 10:46:57.937  1315  2242 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-25 10:46:57.937  1016  1121 V NetworkStats: performPollLocked() took 6ms
08-25 10:46:57.937  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:57.937  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:57.937  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:57.947  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-25 10:46:57.947  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-25 10:46:57.947  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-25 10:46:57.947  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 10:46:57.947  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-25 10:46:57.947  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:57.947  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:57.947  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:57.947  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:57.947  1016  1550 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-25 10:46:57.947  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-25 10:46:57.957  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:57.957  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:57.957  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-25 10:46:57.957  2201  2201 I Hs20UtilService: Starting #24
08-25 10:46:57.957  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-25 10:46:57.957  1315  1315 I NearbySettings: MountReceiver.onReceive - Keep current state
08-25 10:46:57.957  2201  2218 I Hs20UtilService: Message received 5007
08-25 10:46:57.967  1016  1028 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
08-25 10:46:57.967  1016  1134 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-25 10:46:57.967  1016  1134 D SecContentProvider2: mCursor = null
08-25 10:46:57.967  1016  1216 D SecContentProvider2: uri = 15 selection = getToastGravity
08-25 10:46:57.967  1016  1216 D SecContentProvider2: mCursor = null
08-25 10:46:57.967  1016  1550 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-25 10:46:57.967  1016  1550 D SecContentProvider2: mCursor = null
08-25 10:46:57.977  1016  1382 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-25 10:46:57.977  1016  1382 D SecContentProvider2: mCursor = null
08-25 10:46:57.977  1016  1029 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-25 10:46:57.977  1016  1029 D SecContentProvider2: mCursor = null
,08-25 10:46:57.977  1016  1371 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-25 10:46:57.977  1016  1371 D SecContentProvider2: mCursor = null
,08-25 10:46:58.007   259   259 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-25 10:46:58.017  1016  1216 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,08-25 10:46:58.017  1016  7629 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-25 10:46:58.027  1176  1176 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
,08-25 10:46:58.077  1016  7629 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 08:46:58 GMT], X-Android-Received-Millis=[1472114818091], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472114818061]}
,08-25 10:46:58.077  1016  7629 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 10:46:58.077  1016  7629 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-25 10:46:58.077  1016  1126 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-25 10:46:58.077  1016  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-25 10:46:58.077  1016  1126 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-25 10:46:58.087  1016  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-25 10:46:58.087  1016  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 10:46:58.087  4811  6803 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 10:46:58.087  1176  1711 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-25 10:46:58.087  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
08-25 10:46:58.087  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-25 10:46:58.087  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE,
08-25 10:46:58.087  1176  1176 D StatusBar.NetworkController: updateDataNetType()
08-25 10:46:58.087  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-25 10:46:58.087  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-25 10:46:58.087  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-25 10:46:58.087  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-25 10:46:58.087  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-25 10:46:58.087  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-25 10:46:58.087  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-25 10:46:58.087  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:58.087  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:58.087  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-25 10:46:58.087  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-25 10:46:58.137  6741  6741 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-25 10:46:58.137  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 10:46:58.137  6741  6794 I jxcore-log: 
,08-25 10:46:58.147  7671  7671 D AndroidRuntime: 
08-25 10:46:58.147  7671  7671 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-25 10:46:58.147  7671  7671 D AndroidRuntime: CheckJNI is OFF
,08-25 10:46:58.147  7671  7671 D AndroidRuntime: readGMSProperty: start
,08-25 10:46:58.147  7671  7671 D AndroidRuntime: readGMSProperty: already setted!!
08-25 10:46:58.147  7671  7671 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-25 10:46:58.147  7671  7671 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-25 10:46:58.147  7671  7671 D AndroidRuntime: readGMSProperty: end
08-25 10:46:58.147  7671  7671 D AndroidRuntime: addProductProperty: start
,08-25 10:46:58.277  7671  7671 E AffinityControl: AffinityControl: registerfunction enter
,08-25 10:46:58.277  6741  6741 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 10:46:58.287  6741  6794 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 10:46:58.287  6741  6794 I jxcore-log: 
,08-25 10:46:58.307  7671  7671 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-25 10:46:58.327  1016  1382 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-25 10:46:58.327  1016  1382 D PackageManager: START PACKAGE DELETE: observer{271315752}
08-25 10:46:58.327  1016  1382 D PackageManager: pkg{<packageName>}
08-25 10:46:58.327  1016  1382 D PackageManager: user{0}
08-25 10:46:58.327  1016  1382 D PackageManager: caller{2000}
08-25 10:46:58.327  1016  1382 D PackageManager: flags{2}
08-25 10:46:58.327  1016  1382 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
08-25 10:46:58.327  1016  1382 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-25 10:46:58.327  1016  1382 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
08-25 10:46:58.327  1016  1382 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-25 10:46:58.337  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-25 10:46:58.337  1016  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-25 10:46:58.337  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-25 10:46:58.337  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
08-25 10:46:58.337  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-25 10:46:58.347  1016  1056 D PackageManager: !@killApplicatoin: 10171, uninstall pkg,
,08-25 10:46:58.377  1016  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-25 10:46:58.377  1016  1041 I ActivityManager: Killing 6741:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-25 10:46:58.427  1016  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:58.437  1016  1056 W PackageSettings: Skipping PackageSetting{193c15be com.example.hello/10168} due to missing metadata
,08-25 10:46:58.467  1016  1041 I ActivityManager:   Force finishing activity ActivityRecord{27e8944 u0 com.test.thalitest/.MainActivity t2}
,08-25 10:46:58.477  1016  1041 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-25 10:46:58.487  1016  1041 D InputDispatcher: Focus left window: 6741
,08-25 10:46:58.487   259   448 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-25 10:46:58.487   259   705 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-25 10:46:58.507  1016  1041 D InputDispatcher: Focused application released
,08-25 10:46:58.507  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
08-25 10:46:58.507  1016  1041 D FocusedStackFrame: Set to : 0
08-25 10:46:58.507  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 10:46:58.517  1016  1041 W ActivityManager: mDVFSHelper.acquire()
,08-25 10:46:58.517  1016  1041 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-25 10:46:58.547  1016  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:58.557  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-25 10:46:58.557  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:58.557  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:58.557  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:58.557  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:58.557  1475  1475 D Launcher: onRestart, Launcher: 408006693
,08-25 10:46:58.577  7682  7682 E Zygote  : MountEmulatedStorage()
,08-25 10:46:58.577  7682  7682 E Zygote  : v2
08-25 10:46:58.577  7682  7682 I libpersona: KNOX_SDCARD checking this for 1000
08-25 10:46:58.577  7682  7682 I libpersona: KNOX_SDCARD not a persona
08-25 10:46:58.577  1016  1041 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7682 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-25 10:46:58.577  1475  1475 D Launcher: onStart, Launcher: 408006693
08-25 10:46:58.577  1016  1056 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
08-25 10:46:58.577  1475  1475 D Launcher.HomeView: onStart
08-25 10:46:58.577  1475  1475 D Launcher: onResume, Launcher: 408006693
,08-25 10:46:58.577  7682  7682 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-25 10:46:58.577  1016  1550 D SettingsProvider: name = kids_home_mode
08-25 10:46:58.577  1016  1550 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-25 10:46:58.577  1016  1550 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-25 10:46:58.577  1016  1550 D SettingsProvider: selectionArgs: false
08-25 10:46:58.577  1016  1550 D SettingsProvider: selectionArgs: 10006
08-25 10:46:58.577  1016  1550 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-25 10:46:58.577  1016  1550 D SettingsProvider: ret = -1
08-25 10:46:58.577  1475  1475 D Launcher.HomeView: onResume
,08-25 10:46:58.587  7682  7682 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-25 10:46:58.587  7682  7682 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 10:46:58.587  1475  1475 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-25 10:46:58.597  1016  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-25 10:46:58.647  7682  7682 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:58.647  2643  2643 I art     : Explicit concurrent mark sweep GC freed 19553(1116KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 804us total 38.549ms
,08-25 10:46:58.647  7682  7682 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:58.657  1016  1483 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-25 10:46:58.657  1016  1483 D SecContentProvider2: mCursor = null
,08-25 10:46:58.677  4811  4811 I art     : Explicit concurrent mark sweep GC freed 23316(1400KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 12MB/21MB, paused 1.791ms total 85.082ms
,08-25 10:46:58.677  1016  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 10:46:58.687  1954  2127 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-25 10:46:58.687  1875  1875 E SamsungIME: mOCRHelper is null
,08-25 10:46:58.697  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,08-25 10:46:58.697  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-25 10:46:58.697  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-25 10:46:58.697  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-25 10:46:58.697  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-25 10:46:58.707  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,08-25 10:46:58.707  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-25 10:46:58.717  1016  1121 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-25 10:46:58.717  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:58.717  1016  1121 V NetworkStats: performPollLocked(flags=0x3)
,08-25 10:46:58.717  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-25 10:46:58.717  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-25 10:46:58.717  1016  1121 V NetworkStats: performPollLocked() took 8ms
,08-25 10:46:58.727  1475  1475 D MenuAppsGridFragment: onResume
,08-25 10:46:58.727  1475  1475 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-25 10:46:58.727  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:58.737  1475  1475 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-25 10:46:58.747  1016  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
08-25 10:46:58.747  1016  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-25 10:46:58.747  1016  1040 W TextServicesManagerService: no available spell checker services found
,08-25 10:46:58.747  1430  1430 D PersonaManager: isKioskContainerExistOnDevice
,08-25 10:46:58.757  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-25 10:46:58.757  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-25 10:46:58.767  1016  1485 D ActivityManager: handle home activity for 0
,08-25 10:46:58.767  1016  1485 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,08-25 10:46:58.767  1016  1485 D KnoxTimeoutHandler: post home show event for user 0
08-25 10:46:58.767  1016  1485 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-25 10:46:58.767  1016  1485 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-25 10:46:58.767  1016  1485 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-25 10:46:58.767  1475  1475 D Launcher.HomeView: onPause
,08-25 10:46:58.767  1475  1475 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-25 10:46:58.777  1430  1430 D RegisteredServicesCache: empty dynamic service
,08-25 10:46:58.787  7682  7682 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-25 10:46:58.787  7682  7682 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-25 10:46:58.787  7682  7682 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-25 10:46:58.787   259   259 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-25 10:46:58.797  1016  1549 D InputDispatcher: Focus entered window: 1475
,08-25 10:46:58.797  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-25 10:46:58.817  1475  1475 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-25 10:46:58.817  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-25 10:46:58.817  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-25 10:46:58.827  1430  1430 D RegisteredComponentCache: Collect Tech packages for Knox
,08-25 10:46:58.827  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-25 10:46:58.827  7682  7682 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-25 10:46:58.827  7682  7682 I PCWCLIENTTRACE_PushUtil: sales region : global
08-25 10:46:58.827  7682  7682 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-25 10:46:58.827  7682  7682 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:58.827  1430  1430 D PersonaManager: isKioskContainerExistOnDevice
,08-25 10:46:58.827  1016  1550 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 6 r.nextReceiver= 1 receivers.size=28
,08-25 10:46:58.827  1016  1550 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-25 10:46:58.837  1475  1475 V ActivityThread: updateVisibility : ActivityRecord{3306545a token=android.os.BinderProxy@2b6966c7 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-25 10:46:58.837  1475  1475 D Launcher.HomeView: onStop
,08-25 10:46:58.847  1016  1549 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-25 10:46:58.847  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 10:46:58.847  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-25 10:46:58.847  1016  7701 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-25 10:46:58.857  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-25 10:46:58.857  1016  1549 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6741 uid 10171
,08-25 10:46:58.857  1016  1056 I art     : Explicit concurrent mark sweep GC freed 73074(4MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 24MB/37MB, paused 12.116ms total 233.777ms,
,08-25 10:46:58.867  1735  1735 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-25 10:46:58.867  1875  1875 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-25 10:46:58.867  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-25 10:46:58.867  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:58.867  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:58.867  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:58.867  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:58.867  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-25 10:46:58.867  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-25 10:46:58.867  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-25 10:46:58.867  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-25 10:46:58.867  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-25 10:46:58.867  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-25 10:46:58.867  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,08-25 10:46:58.877  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-25 10:46:58.877  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-25 10:46:58.877  7703  7703 E Zygote  : MountEmulatedStorage()
,08-25 10:46:58.877  7703  7703 E Zygote  : v2
08-25 10:46:58.877  7703  7703 I libpersona: KNOX_SDCARD checking this for 10121
08-25 10:46:58.877  7703  7703 I libpersona: KNOX_SDCARD not a persona
,08-25 10:46:58.877  7703  7703 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:58.887  7703  7703 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 10:46:58.887  1016  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7703 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-25 10:46:58.887  7703  7703 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 10:46:58.887  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 10:46:58.887  1016  1029 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-25 10:46:58.887  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-25 10:46:58.897  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:58.897  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:58.897  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-25 10:46:58.897  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-25 10:46:58.897  1016  1016 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-25 10:46:58.907  1016  1550 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-25 10:46:58.907  2607  5028 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,08-25 10:46:58.917  1016  1134 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-25 10:46:58.917  1016  1134 D SecContentProvider2: mCursor = null
,08-25 10:46:58.917  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 10:46:58.927  1016  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:58.927  1016  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:58.927  1016  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:58.927  1016  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:58.927  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 10:46:58.927  1016  1126 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-25 10:46:58.937  7703  7703 D TimaKeyStoreProvider: TimaSignature is unavailable
08-25 10:46:58.937  7703  7703 D ActivityThread: Added TimaKeyStore provider
08-25 10:46:58.937  7718  7718 E Zygote  : MountEmulatedStorage()
08-25 10:46:58.937  7718  7718 E Zygote  : v2
08-25 10:46:58.937  7718  7718 I libpersona: KNOX_SDCARD checking this for 10031
08-25 10:46:58.937  7718  7718 I libpersona: KNOX_SDCARD not a persona
08-25 10:46:58.937  7718  7718 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:58.937  1016  1550 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7718 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-25 10:46:58.947  7718  7718 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 10:46:58.947  7718  7718 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 10:46:58.947  1016  3343 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-25 10:46:58.947  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-25 10:46:58.947  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-25 10:46:58.947  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
,08-25 10:46:58.957  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-25 10:46:58.957  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-25 10:46:58.957  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-25 10:46:58.957  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-25 10:46:58.957  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-25 10:46:58.957  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-25 10:46:58.957  1735  1735 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-25 10:46:58.957  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-25 10:46:58.957  1735  1735 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-25 10:46:58.957  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-25 10:46:58.957  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-25 10:46:58.957  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-25 10:46:58.957  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-25 10:46:58.957  1735  1735 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-25 10:46:58.967  1016  1159 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-25 10:46:58.967  1016  1046 W ActivityManager: mDVFSHelper.release()
08-25 10:46:58.967  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1ac8eccc u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:147936
,08-25 10:46:58.967  1735  1735 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-25 10:46:58.977  7718  7718 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:58.977  7718  7718 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:58.997  1176  1176 I StatusBar: Icon Only
,08-25 10:46:58.997  1176  1176 D PanelView: There is/are notification(s) 
,08-25 10:46:58.997  1735  1735 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-25 10:46:58.997  1735  1735 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-25 10:46:58.997  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-25 10:46:59.007  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:59.007  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:59.007  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:59.007  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:59.017  7734  7734 E Zygote  : MountEmulatedStorage()
,08-25 10:46:59.017  7734  7734 E Zygote  : v2
08-25 10:46:59.017  7734  7734 I libpersona: KNOX_SDCARD checking this for 10001
08-25 10:46:59.017  7734  7734 I libpersona: KNOX_SDCARD not a persona
,08-25 10:46:59.017  7734  7734 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:59.017  7734  7734 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-25 10:46:59.017  1016  1016 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7734 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 10:46:59.017  1016  1056 D PackageManager: delete codoeFile: 
,08-25 10:46:59.017  7734  7734 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-25 10:46:59.027  7703  7703 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 10:46:59.027  7703  7703 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-25 10:46:59.027  7703  7703 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 10:46:59.037  1016  1056 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,08-25 10:46:59.037  1016  1056 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-25 10:46:59.037  1016  1056 D PackageManager: result of delete: 1{271315752}
,08-25 10:46:59.047  7734  7734 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:59.047  7734  7734 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:59.047  7703  7703 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:59.057  7671  7671 D AndroidRuntime: Shutting down VM
,08-25 10:46:59.057  1016  1382 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
,08-25 10:46:59.057  1016  1382 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-25 10:46:59.057  1016  1382 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:59.057  7703  7703 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-25 10:46:59.057  1016  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-25 10:46:59.057  1016  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-25 10:46:59.067  7703  7703 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-25 10:46:59.077  1016  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-25 10:46:59.077  1016  1056 D PackageManager: userId{-1}
08-25 10:46:59.077  1016  1056 D PackageManager: andCode{true}
,08-25 10:46:59.077  1016  1216 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-25 10:46:59.077  1016  1483 D RCPManagerService: exchangeData() failure , invalid userId
08-25 10:46:59.077  1016  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-25 10:46:59.077  1016  1216 W ActivityManager: userId = 0, bbcId = -10000
08-25 10:46:59.077  1016  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-25 10:46:59.077  1016  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-25 10:46:59.077  1016  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-25 10:46:59.077  1016  1481 D RCPManagerService: exchangeData() failure , invalid userId
,08-25 10:46:59.087  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 10:46:59.087  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 10:46:59.087  1016  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-25 10:46:59.097  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:59.097  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:59.097  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:59.097  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:59.097  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 10:46:59.097  1016  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-25 10:46:59.097  1016  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 10:46:59.097  1016  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-25 10:46:59.107  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 10:46:59.117  7752  7752 E Zygote  : MountEmulatedStorage()
,08-25 10:46:59.117  7752  7752 E Zygote  : v2
08-25 10:46:59.117  7752  7752 I libpersona: KNOX_SDCARD checking this for 10003
,08-25 10:46:59.117  7752  7752 I libpersona: KNOX_SDCARD not a persona
08-25 10:46:59.117  7752  7752 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:59.117  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 10:46:59.117  7752  7752 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 10:46:59.117  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 10:46:59.117  6980  7751 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-25 10:46:59.117  1016  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7752 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-25 10:46:59.117  6980  7751 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-25 10:46:59.117  7752  7752 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-25 10:46:59.117  6980  7751 I System.out: (HTTPLog)-Static: isShipBuild true
08-25 10:46:59.117  6980  7751 I System.out: (HTTPLog)-Thread-1245-83195008: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-25 10:46:59.117  6980  7751 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-25 10:46:59.127  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 10:46:59.127  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-25 10:46:59.127   276  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-25 10:46:59.127   276  1011 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,08-25 10:46:59.127  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 10:46:59.127  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 10:46:59.127  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-25 10:46:59.137  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-25 10:46:59.137  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-25 10:46:59.137  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-25 10:46:59.147  1016  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-25 10:46:59.147  1016  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-25 10:46:59.157  7244  7244 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-25 10:46:59.167  7752  7752 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:59.167  7752  7752 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:59.167  6980  7751 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-25 10:46:59.167  2763  7772 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-25 10:46:59.177  2763  7772 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-25 10:46:59.177  7143  7143 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-25 10:46:59.177  2763  7772 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-25 10:46:59.187  7165  7165 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-25 10:46:59.187  7165  7165 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-25 10:46:59.187  7165  7165 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-25 10:46:59.197  7165  7165 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-25 10:46:59.197  7165  7165 I SA      : [OR] == isSIMCardReady false ==
08-25 10:46:59.197  7130  7130 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:59.197  7130  7130 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-25 10:46:59.197  7130  7130 I DIAGMON_AGENT: ./extraInfo: "NG700"
08-25 10:46:59.197  7130  7130 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-25 10:46:59.197  7165  7165 I SA      : [SCU] == networkStateCheck == true
,08-25 10:46:59.207  7165  7165 I SA      : [DM] getCountryCodeFromCSC : PL
08-25 10:46:59.207  7165  7165 I SA      : isChinaCountryCode : false
08-25 10:46:59.207  7165  7165 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-25 10:46:59.207  7165  7165 I SA      : [OR] == networkStateCheck true ==
,08-25 10:46:59.217  7165  7165 I SA      : [OR] GetMyCountryZoneTask
,08-25 10:46:59.217  7165  7165 I SA      : [OR] onReceive END
,08-25 10:46:59.227  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-25 10:46:59.227  1016  1483 I ActivityManager: Killing 7182:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-25 10:46:59.227  2763  7772 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-25 10:46:59.227  1016  1028 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,08-25 10:46:59.227  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
08-25 10:46:59.227  2763  7772 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-25 10:46:59.237  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-25 10:46:59.237  2763  7772 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
08-25 10:46:59.237  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-25 10:46:59.237  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-25 10:46:59.237  2763  7772 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-25 10:46:59.237  2763  7772 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-25 10:46:59.237  2763  7772 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-25 10:46:59.237  6980  7751 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 10:46:59.237  2763  7772 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-25 10:46:59.247  2763  7772 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-25 10:46:59.247  1016  1550 I ActivityManager: Killing 7228:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-25 10:46:59.257  2763  7772 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-25 10:46:59.257  7671  7671 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-25 10:46:59.277  1016  1485 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-25 10:46:59.277  1016  1485 D SecContentProvider2: mCursor = null
,08-25 10:46:59.277  7165  7775 I SA      : [SRS] prepareGetMyCountryZone
08-25 10:46:59.277  2763  7772 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-25 10:46:59.287  1016  1481 D PersonaManager: isKioskContainerExistOnDevice
,08-25 10:46:59.297  7165  7775 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-25 10:46:59.297  7165  7775 I SA      : [SSP] query invoked
,08-25 10:46:59.307  7165  7775 I SA      : [TPMU] GetMccFromDB : null
,08-25 10:46:59.307  7165  7775 I SA      : [SCU] getMccFromPreferece mcc = 260
08-25 10:46:59.307  7165  7775 I SA      : [LBE] isSupportCheckDomainRegion : false
08-25 10:46:59.307  7165  7775 I SA      : [TPM] isNoProxy(default) : true
,08-25 10:46:59.317  7165  7775 E File    : fail readDirectory() errno=2
,08-25 10:46:59.327  1016  1134 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,08-25 10:46:59.327  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:59.327  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:59.327  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-25 10:46:59.327  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-25 10:46:59.337  7781  7781 E Zygote  : MountEmulatedStorage()
08-25 10:46:59.337  7781  7781 E Zygote  : v2
08-25 10:46:59.337  7781  7781 I libpersona: KNOX_SDCARD checking this for 10008
08-25 10:46:59.337  7781  7781 I libpersona: KNOX_SDCARD not a persona
,08-25 10:46:59.337  7781  7781 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-25 10:46:59.347  7781  7781 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-25 10:46:59.347  7781  7781 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-25 10:46:59.347  1016  1134 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7781 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 10:46:59.367  7781  7781 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-25 10:46:59.367  7781  7781 D ActivityThread: Added TimaKeyStore provider
,08-25 10:46:59.377  1016  1094 V AlarmManager: waitForAlarm result :4
,08-25 10:46:59.427  1475  1475 I Choreographer: Skipped 33 frames!  The application may be doing too much work on its main thread.
,08-25 10:46:59.427  1475  1475 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2b6966c7 time:148397
,08-25 10:46:59.467  1016  1380 I ActivityManager: Killing 6819:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,08-25 10:46:59.487  7781  7781 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-25 10:46:59.487  7781  7781 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-25 10:46:59.487  7781  7781 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-25 10:46:59.497  7781  7781 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-25 10:46:59.497  1016  1481 I ActivityManager: Killing 7549:com.samsung.android.sm/1000 (adj 15): empty #21

```
