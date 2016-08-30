#### Test 82642184ea62b6e_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main,
08-30 23:10:51.327   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-30 23:10:51.327   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
08-30 23:10:51.617  6819  6819 D AndroidRuntime: 
08-30 23:10:51.617  6819  6819 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 23:10:51.617  6819  6819 D AndroidRuntime: CheckJNI is OFF
08-30 23:10:51.617  6819  6819 D AndroidRuntime: readGMSProperty: start
08-30 23:10:51.617  6819  6819 D AndroidRuntime: readGMSProperty: already setted!!
08-30 23:10:51.617  6819  6819 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 23:10:51.617  6819  6819 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 23:10:51.617  6819  6819 D AndroidRuntime: readGMSProperty: end
08-30 23:10:51.617  6819  6819 D AndroidRuntime: addProductProperty: start
08-30 23:10:51.777  6819  6819 E AffinityControl: AffinityControl: registerfunction enter
08-30 23:10:51.807  6819  6819 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 23:10:51.827  1017  1337 E PersonaManagerService: inState():  stateMachine is null !!
08-30 23:10:51.827  1017  1337 I PersonaManagerService: PersonaId don't exist
08-30 23:10:51.827  1017  1337 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-30 23:10:51.827  1017  1337 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-30 23:10:51.847  1017  1337 W ActivityManager: mDVFSHelper.acquire()
08-30 23:10:51.847   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-30 23:10:51.857   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-30 23:10:51.867  1017  1337 D FocusedStackFrame: Set to : 0
08-30 23:10:51.867  1017  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-30 23:10:51.867  1017  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-30 23:10:51.877  1017  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:10:51.877  1017  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:10:51.877  1017  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:10:51.877  1017  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:10:51.877  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-30 23:10:51.877  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-30 23:10:51.877   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-30 23:10:51.887  6830  6830 E Zygote  : MountEmulatedStorage()
08-30 23:10:51.887  6830  6830 E Zygote  : v2
08-30 23:10:51.887  6830  6830 I libpersona: KNOX_SDCARD checking this for 10171
08-30 23:10:51.887  6830  6830 I libpersona: KNOX_SDCARD not a persona
08-30 23:10:51.887  6830  6830 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 23:10:51.897  1017  1337 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6830 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 23:10:51.897  1017  1337 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-30 23:10:51.897  1017  1337 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 23:10:51.897  6830  6830 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 23:10:51.897  6830  6830 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-30 23:10:51.907  1017  1337 D InputDispatcher: Focused application set to: xxxx
08-30 23:10:51.907  1017  1337 D InputDispatcher: Focus left window: 1481
08-30 23:10:51.907  6819  6819 D AndroidRuntime: Shutting down VM
08-30 23:10:51.907  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 23:10:51.907  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 23:10:51.927  6830  6830 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:10:51.927  6830  6830 D ActivityThread: Added TimaKeyStore provider
08-30 23:10:51.927  1017  1479 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-30 23:10:51.927  1017  1017 V ActivityManager: Display changed displayId=0
08-30 23:10:51.937  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-30 23:10:51.947  1017  1479 D PersonaManager: isKioskContainerExistOnDevice
08-30 23:10:51.957  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-30 23:10:51.987   258  1039 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-30 23:10:51.987   258   443 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-30 23:10:51.997  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{196e9757 token=android.os.BinderProxy@20c8ffd5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-30 23:10:51.997  1481  1481 D Launcher: onTrimMemory. Level: 20
08-30 23:10:52.097  6830  6830 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-30 23:10:52.117  6819  6819 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-30 23:10:52.137  6830  6830 I cr.library_loader: Time to load native libraries: 14 ms (timestamps 9894-9908)
08-30 23:10:52.137  6830  6830 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-30 23:10:52.157  6830  6830 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1b4096ee}
08-30 23:10:52.157  6830  6830 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-30 23:10:52.167  6830  6830 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 23:10:52.197  6830  6830 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-30 23:10:52.197  6830  6830 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 23:10:52.207  6830  6830 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 23:10:52.247  6830  6830 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 23:10:52.247  6830  6830 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 23:10:52.247  6830  6830 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 23:10:52.247  6830  6830 I Adreno-EGL: Local Branch: 
08-30 23:10:52.247  6830  6830 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 23:10:52.247  6830  6830 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 23:10:52.247  6830  6830 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-30 23:10:52.257   288   288 E SMD     : DCD OFF
08-30 23:10:52.327  6830  6830 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 23:10:52.337  6830  6830 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-30 23:10:52.337  6830  6830 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-30 23:10:52.347  6830  6830 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-30 23:10:52.347  6830  6830 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-30 23:10:52.457  6830  6830 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 23:10:52.457  1017  1043 W ActivityManager: Activity pause timeout for ActivityRecord{15caff9b u0 com.test.thalitest/.MainActivity t2}
08-30 23:10:52.467  6830  6830 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 23:10:52.477  6830  6830 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-30 23:10:52.477  6830  6830 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-30 23:10:52.487  6830  6830 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-30 23:10:52.497  6830  6830 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 23:10:52.497  6830  6830 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 23:10:52.617  6830  6870 D OpenGLRenderer: Render dirty regions requested: true
08-30 23:10:52.617  1017  3822 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-30 23:10:52.617  1017  3822 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 23:10:52.617  1017  3822 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-30 23:10:52.617  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-30 23:10:52.617  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
08-30 23:10:52.627  6830  6857 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-30 23:10:52.627  6830  6830 V ActivityThread: updateVisibility : ActivityRecord{446244e token=android.os.BinderProxy@25c0ef13 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-30 23:10:52.637  6830  6830 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-30 23:10:52.637  6830  6830 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-30 23:10:52.647   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-30 23:10:52.667  1017  1480 D InputDispatcher: Focus entered window: 6830
08-30 23:10:52.667  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 23:10:52.667  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 23:10:52.667  6830  6830 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-30 23:10:52.667  6830  6870 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 23:10:52.677  6830  6870 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-30 23:10:52.677  6830  6870 D OpenGLRenderer: Enabling debug mode 0
08-30 23:10:52.707  1017  1476 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-30 23:10:52.717  1173  1173 I StatusBar: Icon Only
08-30 23:10:52.717  1173  1173 D PanelView: There is/are notification(s) 
08-30 23:10:52.717  1017  6875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-30 23:10:52.727  1017  1048 I ActivityManager: Displayed Component not be shown by security: +772ms (total +855ms)
08-30 23:10:52.727  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{15caff9b u0 com.test.thalitest/.MainActivity t2} time:110497
08-30 23:10:52.727  1017  1048 W ActivityManager: mDVFSHelper.release()
08-30 23:10:52.737   258  6068 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-30 23:10:52.737   258  1039 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-30 23:10:52.737  1862  1862 I SamsungIME: getCurrentCandidateView
08-30 23:10:52.737  6830  6830 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-30 23:10:52.737  6830  6830 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25c0ef13 time:110509
08-30 23:10:52.757  6830  6830 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6830
08-30 23:10:52.847  1862  1862 D SamsungIME: Dismiss ExpandCandiate
,08-30 23:10:52.937  6830  6830 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 23:10:53.017  1862  1862 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 23:10:53.027  6830  6874 D jxcore_app_log: JniHelper::setJavaVM(0xb85052b0), pthread_self() = -1196891632
,08-30 23:10:53.037  6830  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 23:10:53.037  6830  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 23:10:53.037  6830  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 23:10:53.037  6830  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 23:10:53.037  6830  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 23:10:53.037  6830  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36408914 added. We now have 1 listener(s)
,08-30 23:10:53.047  6830  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-30 23:10:53.047  6830  6874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-30 23:10:53.047  6830  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 23:10:53.047  6830  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 23:10:53.047  6830  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 23:10:53.047  6830  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 23:10:53.047  6830  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 23:10:53.047  6830  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-30 23:10:53.047  6830  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 23:10:53.047  6830  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 23:10:53.047  6830  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 23:10:53.047  6830  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 23:10:53.047  6830  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 23:10:53.047  6830  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 23:10:53.047  6830  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 23:10:53.047  6830  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 23:10:53.047  6830  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 23:10:53.047  6830  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 23:10:53.047  6830  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1613c303 added. We now have 1 listener(s)
08-30 23:10:53.047  6830  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 23:10:53.057  1862  1862 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 23:10:53.057  6830  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 23:10:53.057  6830  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-30 23:10:53.057  6830  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 23:10:53.057  6830  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 23:10:53.057  6830  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 23:10:53.067  6830  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 23:10:53.067  6830  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-30 23:10:53.077  6830  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 23:10:53.077  6830  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 23:10:53.077  6830  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 23:10:53.077  6830  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 23:10:53.077  6830  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 23:10:53.077  6830  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 23:10:53.077  6830  6874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 23:10:53.077  6830  6874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 23:10:53.077  6830  6874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 23:10:53.077  6830  6874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 23:10:53.077  6830  6874 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 23:10:53.077  6830  6874 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 23:10:53.077  6830  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 23:10:53.077  6830  6830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 23:10:53.087  1862  1862 I SamsungIME: KeybaordView init() : load resources
,08-30 23:10:53.107  1862  1862 I SamsungIME: getCurrentKeyboard
,08-30 23:10:53.107  1862  1862 I SamsungIME: getTextKeyboard
,08-30 23:10:53.117  6830  6830 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,08-30 23:10:53.127  1862  1862 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-30 23:10:53.707  6830  6884 W jxcore-log: Initializing JXcore engine
08-30 23:10:53.707  6830  6884 W jxcore-log: JXcore engine is ready
,08-30 23:10:53.767  1974  1974 E audit   : type=1400 msg=audit(1472591453.767:205): avc:  denied  { ioctl } for  pid=6884 comm="Thread-1276" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-30 23:10:53.767  1974  1974 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
,08-30 23:10:53.767  1974  1974 E audit   : type=1300 msg=audit(1472591453.767:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9fc188f8 items=0 ppid=304 ppcomm=main pid=6884 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1276" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-30 23:10:53.767  1974  1974 E audit   : type=1320 msg=audit(1472591453.767:205): 
08-30 23:10:53.777  6830  6884 W jxcore-log: Starting JXcore engine
,08-30 23:10:53.887  6830  6884 W jxcore-log: Platform android
08-30 23:10:53.887  6830  6884 W jxcore-log: 
08-30 23:10:53.887  6830  6884 W jxcore-log: Process ARCH arm
08-30 23:10:53.887  6830  6884 W jxcore-log: 
,08-30 23:10:54.087  6830  6884 I jxcore-log: JXcore Cordova bridge is ready!
08-30 23:10:54.087  6830  6884 I jxcore-log: 
,08-30 23:10:54.087  6830  6884 W jxcore-log: JXcore engine is started
,08-30 23:10:54.097  6830  6874 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 23:10:54.097  6830  6830 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 23:10:55.257   288   288 E SMD     : DCD OFF
,08-30 23:10:55.607  1017  1050 I PowerManagerService: [PWL] Off : 50s ago,
,08-30 23:10:55.687  1017  3368 D SSRM:n  : SIOP:: AP = 330
,08-30 23:10:56.327   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 23:10:57.327   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 23:10:57.607  5680  5680 D FactoryTest: Not factory mode
,08-30 23:10:57.607  5680  5680 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-30 23:10:57.617  5680  5680 D MTPRx   : DRIVER_TIME_OUT 60s lapsed,
08-30 23:10:57.617  5680  5680 D MTPRx   : still no open session command from host, so toast
,08-30 23:10:57.617  5680  5680 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
08-30 23:10:57.617  5680  5680 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-30 23:10:57.627  5680  5680 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115390,
08-30 23:10:57.627  1017  1479 E PersonaManagerService: inState():  stateMachine is null !!
08-30 23:10:57.627  1017  1479 I PersonaManagerService: PersonaId don't exist
08-30 23:10:57.627  1017  1479 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-30 23:10:57.627  1017  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 23:10:57.637  1017  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:10:57.637  1017  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 23:10:57.637  1017  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-30 23:10:57.637  1017  1479 W ActivityManager: mDVFSHelper.acquire()
,08-30 23:10:57.657  1017  1479 D PersonaManager: isKioskContainerExistOnDevice
,08-30 23:10:57.667  1017  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 23:10:57.667  1017  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 23:10:57.667  1017  1479 D InputDispatcher: Focused application set to: xxxx
,08-30 23:10:57.667  1017  1479 D InputDispatcher: Focus left window: 6830
08-30 23:10:57.667  5680  5680 E MTPRx   : started activity for popup
08-30 23:10:57.667  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 23:10:57.667  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 23:10:57.697  5680  5680 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-30 23:10:57.697  5680  5680 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 23:10:57.697  5680  5680 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-30 23:10:57.697  5680  5680 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 23:10:57.697  5680  5680 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 23:10:57.697  5680  5680 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 23:10:57.717  5680  5680 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-30 23:10:57.727  1017  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 23:10:57.727  1017  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 23:10:57.727  1017  1479 D InputDispatcher: Focused application set to: xxxx
,08-30 23:10:57.727  1017  1479 D InputDispatcher: Focus entered window: 6830
,08-30 23:10:57.727  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 23:10:57.737  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 23:10:57.737  1017  1030 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-30 23:10:57.737  1017  1030 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@628a2ba attribute=null, token = android.os.BinderProxy@be9630a
,08-30 23:10:57.777  5680  5680 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-30 23:10:57.787  5680  5680 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-30 23:10:57.787  5680  5680 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-30 23:10:57.807  6830  6830 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 23:10:57.807  6830  6830 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-30 23:10:57.807  6830  6830 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 23:10:57.807  6830  6830 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-30 23:10:57.807  1017  1370 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-30 23:10:57.807  1017  1370 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 23:10:57.807  1017  1370 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 23:10:57.817  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-30 23:10:57.817  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 23:10:57.827  6830  6830 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 23:10:57.827  6830  6830 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED,
08-30 23:10:57.827  6830  6830 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25c0ef13 time:115594
,08-30 23:10:57.827  6830  6830 V ActivityThread: updateVisibility : ActivityRecord{446244e token=android.os.BinderProxy@25c0ef13 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-30 23:10:57.827  6830  6830 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1764e27f Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@32d8d583, 16908290=android.view.AbsSavedState$1@32d8d583}, android:focusedViewId=100}]}]
08-30 23:10:57.827  6830  6830 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 23:10:57.827  6830  6830 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 23:10:57.827  6830  6830 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 23:10:57.837  1017  3640 D PersonaManager: isKioskContainerExistOnDevice
,08-30 23:10:58.257   288   288 E SMD     : DCD OFF
,08-30 23:10:58.327   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 23:10:58.447  1017  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 23:10:58.447  1017  1218 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-30 23:10:58.447  1017  1218 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-30 23:10:58.447  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 23:10:58.457  1017  1218 D BatteryService: stay LED for fully charged
,08-30 23:10:58.457  1017  1017 I MotionRecognitionService: Plugged
08-30 23:10:58.457  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 23:10:58.457  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 23:10:58.457  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 23:10:58.457  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 23:10:58.457  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-30 23:10:58.467  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 23:10:58.467  3157  3263 D HeadsetStateMachine: Disconnected process message: 10
,08-30 23:10:58.477  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 23:10:58.477  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 23:10:58.477  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 23:10:59.327   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 23:10:59.987  1017  1096 V AlarmManager: waitForAlarm result :8
,08-30 23:11:00.327   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 23:11:00.637  1017  1043 W ActivityManager: mDVFSHelper.release()
,08-30 23:11:01.257   288   288 E SMD     : DCD OFF
,08-30 23:11:01.327   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-30 23:11:01.927  1017  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-30 23:11:02.237  1017  1096 V AlarmManager: waitForAlarm result :4
,08-30 23:11:02.247  1017  1096 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-30 23:11:02.257  1017  1017 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-30 23:11:02.257  1017  1017 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-30 23:11:02.257  1989  1989 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-30 23:11:02.257  1017  1017 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-30 23:11:02.267  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-30 23:11:02.267  1173  1173 D KeyguardUpdateMonitor: handleTimeUpdate
,08-30 23:11:02.277  1173  1173 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-30 23:11:02.277  1173  1173 D SecKeyguardClockView: HomeTimezone(): 1
,08-30 23:11:02.287  1173  1173 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 23:11:02.287  1173  1173 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-30 23:11:02.287  1173  1173 I KeyguardEffectViewController: *** don't update sliding image ***
,08-30 23:11:02.317  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 23:11:02.317  1017  3822 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 23:11:02.317  1017  3822 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-30 23:11:02.317  1017  3822 W ActivityManager: userId = 0, bbcId = -10000
08-30 23:11:02.317  1017  3822 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:02.317  1017  3822 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:02.327  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 23:11:02.327  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 23:11:02.347  1173  1173 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 23:11:02.387  4862  4862 D ConnectivityManager: CallingUid : 10011, CallingPid : 4862
,08-30 23:11:02.397  1017  3822 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 23:11:02.397  1017  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,08-30 23:11:02.397  1017  1129 D ConnectivityService: apparently satisfied.  currentScore=60
,08-30 23:11:02.397  1017  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-30 23:11:02.397  4862  6893 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-30 23:11:02.447  4862  6894 W DriveInitializer: Background init thread started
,08-30 23:11:02.497   257   537 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-30 23:11:02.497   257   537 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 23:11:02.497  4862  6894 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-30 23:11:02.557  1017  3822 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 23:11:02.557  1017  3822 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.net.NetworkReportService; callingUser = 0; userId(target) = 0
,08-30 23:11:02.557  1017  3822 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:02.557  1017  3822 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:02.557  1017  3822 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:02.597  1017  1337 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 23:11:02.597  1017  1337 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-30 23:11:02.597  1017  1337 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:02.597  1017  1337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:02.597  1017  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:02.617  4862  5198 D NetworkUsageDbReporter: Started reporting usage
,08-30 23:11:02.617  1017  4466 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-30 23:11:02.617  4862  6894 W DriveInitializer: Background init thread ended
,08-30 23:11:02.627  1017  4466 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-30 23:11:02.637  1017  1337 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-30 23:11:02.637  1017  1337 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,08-30 23:11:02.637  1017  1337 W ActivityManager: userId = 0, bbcId = -10000
08-30 23:11:02.637  1017  1337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:02.637  1017  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:02.667  1989  1989 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 23:11:02.697  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:02.697  1017  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:02.697  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1932
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: keeping row: 1605
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 6565
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: keeping row: 1604
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 4397
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: keeping row: 1603
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 10174
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: keeping row: 1602
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1515
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: keeping row: 1601
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 15692
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: keeping row: 1600
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 7381
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: keeping row: 1599
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 154233
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: keeping row: 1598
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 15025
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: keeping row: 1597
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 28359
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: keeping row: 1596
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 290029
08-30 23:11:02.727  4862  5198 D NetworkUsageDbReporter: keeping row: 1595
,08-30 23:11:02.747  4862  5198 D NetworkUsageDbReporter: Finished reporting usage.
,08-30 23:11:02.787  1017  1370 I art     : Explicit concurrent mark sweep GC freed 36709(2021KB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 24MB/36MB, paused 2.569ms total 170.964ms
,08-30 23:11:02.857  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 23:11:02.857  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-30 23:11:02.857  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:02.857  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:02.857  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:02.887  4862  6907 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-30 23:11:02.887  4862  6907 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-30 23:11:02.907  1017  1370 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 23:11:02.907  1017  1370 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-30 23:11:02.907  1017  1370 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:02.907  1017  1370 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:02.907  1017  1370 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:02.967  1017  3822 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 23:11:02.967  1017  3822 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:02.967  1017  3822 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:02.967  1017  3822 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:03.027  1017  1338 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 23:11:03.027  1017  1338 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:03.027  1017  1338 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:03.027  1017  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:03.027  1017  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 23:11:03.037  1017  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:03.037  1017  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 23:11:03.037  1017  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 23:11:03.047  6910  6910 E Zygote  : MountEmulatedStorage()
08-30 23:11:03.047  6910  6910 I libpersona: KNOX_SDCARD checking this for 10011
08-30 23:11:03.047  6910  6910 E Zygote  : v2
,08-30 23:11:03.047  6910  6910 I libpersona: KNOX_SDCARD not a persona
,08-30 23:11:03.047  1017  1338 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6910 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-30 23:11:03.057  6910  6910 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 23:11:03.057  6910  6910 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-30 23:11:03.057  6910  6910 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-30 23:11:03.077  6910  6910 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 23:11:03.077  6910  6910 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:03.097  6910  6910 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-30 23:11:03.097  6910  6910 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 23:11:03.127  6910  6910 I MultiDex: VM with version 2.1.0 has multidex support
,08-30 23:11:03.127  6910  6910 I MultiDex: install
08-30 23:11:03.127  6910  6910 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 23:11:03.157  6910  6910 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 23:11:03.217  6910  6910 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-30 23:11:03.217  6910  6910 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5e92b0a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-30 23:11:03.217  6910  6910 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-30 23:11:03.247  6910  6910 D ChimeraCfgMgr: Reading stored module config,
,08-30 23:11:03.337  6910  6927 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-30 23:11:03.347  6910  6910 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-30 23:11:03.347  6910  6910 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-30 23:11:03.367  6910  6924 W art     : Suspending all threads took: 15.053ms
,08-30 23:11:03.367  6910  6924 I art     : Background partial concurrent mark sweep GC freed 1218(222KB) AllocSpace objects, 1(101KB) LOS objects, 40% free, 7MB/12MB, paused 19.419ms total 54.102ms
,08-30 23:11:03.437   283   699 D WVCdm   : Instantiating CDM.
,08-30 23:11:03.447   283   681 I WVCdm   : CdmEngine::OpenSession
08-30 23:11:03.447   283   681 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-30 23:11:03.457   283   681 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-30 23:11:03.477   283   681 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-30 23:11:03.527  6910  6921 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-30 23:11:03.527  6910  6921 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 23:11:03.527  6910  6921 I System.out: (HTTPLog)-Static: isShipBuild true
08-30 23:11:03.527  6910  6921 I System.out: (HTTPLog)-Thread-1255-726682447: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-30 23:11:03.527  6910  6921 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 23:11:03.527   278   989 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 23:11:03.527   278   989 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 23:11:03.537   283   681 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-30 23:11:03.537   283   283 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-30 23:11:03.537   283   283 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-30 23:11:03.537   283   283 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-30 23:11:03.547   283   283 D WVCdm   : PrepareKeyRequest: nonce=3125499637
,08-30 23:11:03.577  6910  6921 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,08-30 23:11:03.577  6910  6921 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6910, getuid(): 10011
,08-30 23:11:03.837  6910  6921 I qtaguid : Untagging socket 30
,08-30 23:11:04.177  6933  6933 I dex2oat : ----------------------------------------------------,
,08-30 23:11:04.177  6933  6933 I dex2oat : <SS>: S T A R T I N G . . .
08-30 23:11:04.177  6933  6933 I dex2oat : <SS>: Zip is absent. Canceled.
08-30 23:11:04.177  6933  6933 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 23:11:04.227  6933  6933 I dex2oat : dex2oat took 47.302ms (threads: 4)
,08-30 23:11:04.237  6910  6921 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 23:11:04.237  6910  6921 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 23:11:04.237  6910  6921 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 23:11:04.237  6910  6921 I Adreno-EGL: Local Branch: 
08-30 23:11:04.237  6910  6921 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 23:11:04.237  6910  6921 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 23:11:04.237  6910  6921 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 23:11:04.257   288   288 E SMD     : DCD OFF,
,08-30 23:11:04.307  6910  6921 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-30 23:11:04.307  6910  6921 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 23:11:04.307  6910  6921 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 23:11:04.307  6910  6921 I Adreno-EGL: Local Branch: 
08-30 23:11:04.307  6910  6921 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 23:11:04.307  6910  6921 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 23:11:04.307  6910  6921 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 23:11:04.347  6910  6921 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 23:11:04.347  6910  6921 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 23:11:04.347  6910  6921 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 23:11:04.347  6910  6921 I Adreno-EGL: Local Branch: 
08-30 23:11:04.347  6910  6921 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 23:11:04.347  6910  6921 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 23:11:04.347  6910  6921 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 23:11:04.807  1017  1479 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-30 23:11:04.807  1017  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-30 23:11:04.807  1017  1479 W ActivityManager: userId = 0, bbcId = -10000
08-30 23:11:04.807  1017  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:04.807  1017  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:04.837  1989  6909 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-30 23:11:04.837  1989  6909 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 23:11:04.837  1989  6909 I System.out: (HTTPLog)-Static: isShipBuild true
,08-30 23:11:04.837  1989  6909 I System.out: (HTTPLog)-Thread-267-949478206: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-30 23:11:04.837  1989  6909 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 23:11:04.837   278   989 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 23:11:04.837   278   989 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 23:11:04.837  1989  6909 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 23:11:04.847  1989  6909 I qtaguid : Tagging socket 57 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1989, getuid(): 10011
,08-30 23:11:04.857  1017  3397 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 23:11:04.887  1989  6909 I qtaguid : Tagging socket 61 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1989, getuid(): 10011
,08-30 23:11:05.087  1017  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 23:11:05.087  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-30 23:11:05.087  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-30 23:11:05.087  1017  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:05.087  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:05.087   283   699 I WVCdm   : CdmEngine::CloseSession
,08-30 23:11:05.097   283   699 I WVCdm   : L3 Terminate.
,08-30 23:11:05.137  1017  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 23:11:05.137  1017  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:05.137  1017  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:05.137  1017  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:05.207  1989  6909 I art     : Explicit concurrent mark sweep GC freed 80250(4MB) AllocSpace objects, 15(381KB) LOS objects, 39% free, 10MB/18MB, paused 4.337ms total 94.659ms
,08-30 23:11:05.437  1017  1337 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-30 23:11:05.447  1017  1338 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 23:11:05.447  1017  1338 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:05.447  1017  1338 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:05.447  1017  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:05.457  1017  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 23:11:05.467  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:05.467  1017  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:05.467  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:05.497  1989  1989 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=1f17aaa4-f0c1-47b6-b915-3708faaefaf8
,08-30 23:11:05.507  1017  1030 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-30 23:11:05.507  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-30 23:11:05.507  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-30 23:11:05.507  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:05.507  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:05.507  1989  1989 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 23:11:05.507  1989  1989 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 23:11:05.537  1017  1370 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 23:11:05.537  1017  1370 W ActivityManager: userId = 0, bbcId = -10000
08-30 23:11:05.537  1017  1370 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:05.537  1017  1370 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:05.567  4380  4395 I art     : Explicit concurrent mark sweep GC freed 1568(54KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 698us total 22.535ms
,08-30 23:11:05.647  1989  2146 W GCoreFlp: No location to return for getLastLocation()
,08-30 23:11:05.667  1017  1139 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 23:11:05.667  1017  1139 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:05.667  1017  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:05.667  1017  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:05.677  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 23:11:05.677  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:05.677  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:05.677  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:05.677  1017  1218 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 23:11:05.677  1017  1218 W ActivityManager: userId = 0, bbcId = -10000
08-30 23:11:05.677  1017  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:05.677  1017  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:05.697  4862  6944 D UdcContextInitService: registered all accounts: true
,08-30 23:11:05.697  1989  2149 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 23:11:05.707  1017  3368 D SSRM:n  : SIOP:: AP = 360
,08-30 23:11:05.717  1989  2166 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-30 23:11:05.827  1017  1338 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 23:11:05.827  1017  1338 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-30 23:11:05.837  1017  1338 W ActivityManager: userId = 0, bbcId = -10000
08-30 23:11:05.837  1017  1338 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:05.837  1017  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:05.877  1017  3822 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-30 23:11:05.877  1017  3822 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-30 23:11:05.877  1017  3822 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:05.877  1017  3822 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:05.877  1017  3822 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:05.937  1017  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 23:11:05.937  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:05.937  1017  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:05.937  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:05.957  1989  2166 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 23:11:05.957  1017  1338 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 23:11:05.957  1017  1338 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:05.957  1017  1338 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:05.957  1017  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:05.967  1989  2166 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-30 23:11:05.977  1989  6954 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 23:11:05.977   278   989 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 23:11:05.987   278   989 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 23:11:05.987  1989  6954 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 23:11:05.987  1989  6954 I qtaguid : Tagging socket 72 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1989, getuid(): 10011
,08-30 23:11:06.027  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 23:11:06.027  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-30 23:11:06.027  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:06.027  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:06.027  1989  6958 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 23:11:06.027  1989  6950 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 23:11:06.027  1017  1370 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 23:11:06.027  1017  1370 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:06.027  1017  1370 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:06.037  1017  1370 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:06.037  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-30 23:11:06.037  1989  6954 I qtaguid : Tagging socket 74 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1989, getuid(): 10011
,08-30 23:11:06.067  1017  3822 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 23:11:06.067  1017  3822 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:06.067  1017  3822 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:06.067  1017  3822 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:06.067  1989  6958 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 23:11:06.067  1989  6950 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 23:11:06.067  1017  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 23:11:06.067  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:06.067  1017  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:06.077  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:06.097  1017  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 23:11:06.097  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-30 23:11:06.097  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:06.097  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:06.097  1989  6958 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 23:11:06.097  1989  6950 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 23:11:06.097  1989  6950 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-30 23:11:06.117  1989  6950 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 23:11:06.167  1017  1337 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 23:11:06.217  1989  6950 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 23:11:06.217   278   989 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-30 23:11:06.217   278   989 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-30 23:11:06.227  1989  6950 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 23:11:06.227  1989  6950 I qtaguid : Tagging socket 77 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1989, getuid(): 10011
,08-30 23:11:06.257  1989  6950 I qtaguid : Tagging socket 80 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1989, getuid(): 10011
,08-30 23:11:06.327  1989  6954 I qtaguid : Untagging socket 72
,08-30 23:11:06.327   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 23:11:06.337  1989  2166 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-30 23:11:06.587  1989  6950 I art     : Explicit concurrent mark sweep GC freed 52401(2MB) AllocSpace objects, 18(503KB) LOS objects, 39% free, 11MB/19MB, paused 1.497ms total 69.769ms
,08-30 23:11:06.607  1017  1029 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 23:11:06.617  1989  6950 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 23:11:06.617  1989  6950 I qtaguid : Tagging socket 77 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1989, getuid(): 10011
,08-30 23:11:06.777  1017  3640 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 23:11:06.777  1989  6950 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 23:11:06.777  1989  6950 I qtaguid : Tagging socket 77 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1989, getuid(): 10011
,08-30 23:11:07.257   288   288 E SMD     : DCD OFF
,08-30 23:11:07.337   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 23:11:08.067  1989  6953 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 23:11:08.067  1989  6953 I qtaguid : Tagging socket 72 with tag 1000310200000000{268448002,0} for uid 10011, pid: 1989, getuid(): 10011
,08-30 23:11:08.277  1989  6953 I qtaguid : Untagging socket 72
,08-30 23:11:08.277  1989  2166 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-30 23:11:08.297  1017  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-30 23:11:08.337   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 23:11:08.507  1017  1370 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 23:11:08.507  1017  1370 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-30 23:11:08.507  1017  1370 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 23:11:08.507  1017  1370 D BatteryService: stay LED for fully charged
,08-30 23:11:08.507  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 23:11:08.507  1017  1017 I MotionRecognitionService: Plugged
,08-30 23:11:08.507  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 23:11:08.517  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 23:11:08.517  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 23:11:08.517  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 23:11:08.517  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-30 23:11:08.537  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-30 23:11:08.537  3157  3263 D HeadsetStateMachine: Disconnected process message: 10
,08-30 23:11:08.547  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 23:11:08.547  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 23:11:08.547  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 23:11:09.337   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 23:11:09.787  1017  1479 I ActivityManager: Killing 6531:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-30 23:11:10.257   288   288 E SMD     : DCD OFF,
,08-30 23:11:10.337   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 23:11:11.337   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-30 23:11:12.807  6830  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-30 23:11:12.807  6830  6884 I jxcore-log: 
,08-30 23:11:12.807  6830  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-30 23:11:12.807  6830  6884 I jxcore-log: 
,08-30 23:11:12.817  6830  6884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 23:11:12.817  6830  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 23:11:12.817  6830  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 23:11:12.817  6830  6884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 23:11:12.817  6830  6884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 23:11:12.817  6830  6884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 23:11:12.817  6830  6884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 23:11:12.817  6830  6884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 23:11:12.817  6830  6884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 23:11:12.817  6830  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 23:11:12.817  6830  6884 I jxcore-log: 
,08-30 23:11:12.817  6830  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 23:11:12.817  6830  6884 I jxcore-log: 
,08-30 23:11:13.257   288   288 E SMD     : DCD OFF
,08-30 23:11:13.307  6830  6884 I jxcore-log: Running unit tests
08-30 23:11:13.307  6830  6884 I jxcore-log: 
,08-30 23:11:13.307  6830  6884 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 23:11:13.307  6830  6884 I jxcore-log: Failed to execute UT.
08-30 23:11:13.307  6830  6884 I jxcore-log: 
,08-30 23:11:13.307  6830  6884 I jxcore-log: Unit Test app is loaded
08-30 23:11:13.307  6830  6884 I jxcore-log: 
,08-30 23:11:13.307  6830  6884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 23:11:13.307  6830  6884 I jxcore-log: 
,08-30 23:11:13.317  6830  6830 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 23:11:13.327  6830  6884 I jxcore-log: My device name is: samsung-SM-A300FU
08-30 23:11:13.327  6830  6884 I jxcore-log: 
,08-30 23:11:15.737  1017  3368 D SSRM:n  : SIOP:: AP = 350
,08-30 23:11:16.267   288   288 E SMD     : DCD OFF
,08-30 23:11:16.587  6830  6884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 23:11:16.587  6830  6884 I jxcore-log: 
,08-30 23:11:17.157  6830  6884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 23:11:17.157  6830  6884 I jxcore-log: 
,08-30 23:11:17.187  6830  6884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 23:11:17.187  6830  6884 I jxcore-log: 
,08-30 23:11:18.557  1017  1139 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 23:11:18.557  1017  1139 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-30 23:11:18.557  1017  1139 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-30 23:11:18.557  1017  1139 D BatteryService: stay LED for fully charged
,08-30 23:11:18.567  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 23:11:18.567  1017  1017 I MotionRecognitionService: Plugged
,08-30 23:11:18.567  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 23:11:18.567  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-30 23:11:18.567  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
08-30 23:11:18.567  1410  1410 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-30 23:11:18.567  1410  1410 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-30 23:11:18.577  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 23:11:18.577  3157  3263 D HeadsetStateMachine: Disconnected process message: 10
,08-30 23:11:18.587  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 23:11:18.587  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 23:11:18.587  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-30 23:11:18.977  6830  6884 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js,
08-30 23:11:18.977  6830  6884 I jxcore-log: 
,08-30 23:11:19.267  6830  6884 I jxcore-log: ERROR runTests: ,
08-30 23:11:19.267  6830  6884 I jxcore-log: 
08-30 23:11:19.267   288   288 E SMD     : DCD OFF
,08-30 23:11:19.267  6830  6884 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger',
08-30 23:11:19.267  6830  6884 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 23:11:19.277  6830  6884 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',,
08-30 23:11:19.277  6830  6884 I jxcore-log:     _functionName: 'loadFile',
08-30 23:11:19.277  6830  6884 I jxcore-log:     _lineNumber: '26',
08-30 23:11:19.277  6830  6884 I jxcore-log:     _columnNumber: '11',
08-30 23:11:19.277  6830  6884 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 23:11:19.277  6830  6884 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 23:11:19.277  6830  6884 I jxcore-log:     _functionName: '',
08-30 23:11:19.277  6830  6884 I jxcore-log:     _lineNumber: '38',
08-30 23:11:19.277  6830  6884 I jxcore-log:     _columnNumber: '7',
08-30 23:11:19.277  6830  6884 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 23:11:19.277  6830  6884 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 23:11:19.277  6830  6884 I jxcore-log:     _functionName: '',
08-30 23:11:19.277  6830  6884 I jxcore-log:     _lineNumber: '35',,
08-30 23:11:19.277  6830  6884 I jxcore-log:     _columnNumber: '3',
08-30 23:11:19.277  6830  6884 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 23:11:19.277  6830  6884 I jxcore-log:   { _fileName: 'module.js',
08-30 23:11:19.277  6830  6884 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 23:11:19.277  6830  6884 I jxcore-log:     _lineNumber: '621',
08-30 23:11:19.277  6830  6884 I jxcore-log:     _columnNumber: '8',
08-30 23:11:19.277  6830  6884 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 23:11:19.277  6830  6884 I jxcore-log:   { _fileName: 'module.js',
08-30 23:11:19.277  6830  6884 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 23:11:19.277  6830  6884 I jxcore-log:     _lineNumber: '651',
08-30 23:11:19.277  6830  6884 I jxcore-log:     _columnNumber: '1',
08-30 23:11:19.277  6830  6884 I jxcore-log:    
08-30 23:11:19.277  6830  6884 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 23:11:19.277  6830  6884 I jxcore-log: 
,08-30 23:11:19.277  6830  6884 E jxcore-log: Error: 
08-30 23:11:19.277  6830  6884 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 23:11:19.277  6830  6884 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 23:11:19.277  6830  6884 E jxcore-log: 
,08-30 23:11:19.567  6968  6968 D AndroidRuntime: ,
08-30 23:11:19.567  6968  6968 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 23:11:19.577  6968  6968 D AndroidRuntime: CheckJNI is OFF,
08-30 23:11:19.577  6968  6968 D AndroidRuntime: readGMSProperty: start
08-30 23:11:19.577  6968  6968 D AndroidRuntime: readGMSProperty: already setted!!
08-30 23:11:19.577  6968  6968 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 23:11:19.577  6968  6968 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 23:11:19.577  6968  6968 D AndroidRuntime: readGMSProperty: end
08-30 23:11:19.577  6968  6968 D AndroidRuntime: addProductProperty: start
,08-30 23:11:19.697  6968  6968 E AffinityControl: AffinityControl: registerfunction enter,
,08-30 23:11:19.717  6968  6968 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-30 23:11:19.737  1017  1218 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-30 23:11:19.737  1017  1218 D PackageManager: START PACKAGE DELETE: observer{1072193410}
08-30 23:11:19.737  1017  1218 D PackageManager: pkg{<packageName>}
08-30 23:11:19.737  1017  1218 D PackageManager: user{0}
08-30 23:11:19.737  1017  1218 D PackageManager: caller{2000}
08-30 23:11:19.737  1017  1218 D PackageManager: flags{2}
08-30 23:11:19.737  1017  1218 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
08-30 23:11:19.737  1017  1218 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-30 23:11:19.737  1017  1218 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-30 23:11:19.737  1017  1218 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
,08-30 23:11:19.737  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
08-30 23:11:19.737  1017  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-30 23:11:19.737  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-30 23:11:19.737  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
,08-30 23:11:19.737  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-30 23:11:19.747  1017  1057 D PackageManager: !@killApplicatoin: 10171, uninstall pkg,
,08-30 23:11:19.747  1017  1043 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
08-30 23:11:19.747  1017  1043 I ActivityManager: Killing 6830:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-30 23:11:19.767  1017  1043 I ActivityManager:   Force finishing activity ActivityRecord{15caff9b u0 com.test.thalitest/.MainActivity t2}
,08-30 23:11:19.767  1017  1043 D InputDispatcher: Focus left window: 6830
,08-30 23:11:19.767   258  6068 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,08-30 23:11:19.767   258  6065 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-30 23:11:19.787  1017  1043 D InputDispatcher: Focused application released
,08-30 23:11:19.787  1017  1043 D FocusedStackFrame: Set to : 0
,08-30 23:11:19.787  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 23:11:19.787  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 23:11:19.787  1017  1043 W ActivityManager: mDVFSHelper.acquire()
,08-30 23:11:19.887  1017  1057 W PackageSettings: Skipping PackageSetting{26675c1f com.example.hello/10168} due to missing metadata
,08-30 23:11:19.917  1017  1043 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false,
,08-30 23:11:19.927  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-30 23:11:19.947  1017  1057 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-30 23:11:19.947  1481  1481 D Launcher: onRestart, Launcher: 213624357
,08-30 23:11:19.967  1017  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-30 23:11:19.997  1481  1481 D Launcher: onStart, Launcher: 213624357
08-30 23:11:19.997  1481  1481 D Launcher.HomeView: onStart
,08-30 23:11:19.997  1481  1481 D Launcher: onResume, Launcher: 213624357
,08-30 23:11:19.997  1017  4466 D SettingsProvider: name = kids_home_mode
08-30 23:11:19.997  1017  4466 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 23:11:19.997  1017  4466 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 23:11:19.997  1017  4466 D SettingsProvider: selectionArgs: false
08-30 23:11:19.997  1017  4466 D SettingsProvider: selectionArgs: 10006
08-30 23:11:19.997  1017  4466 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 23:11:19.997  1017  4466 D SettingsProvider: ret = -1
,08-30 23:11:19.997  1481  1481 D Launcher.HomeView: onResume
,08-30 23:11:20.017  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-30 23:11:20.037  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 23:11:20.037  6424  6424 I art     : Explicit concurrent mark sweep GC freed 401(27KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/8MB, paused 1.045ms total 81.760ms
,08-30 23:11:20.047  2714  2714 I art     : Explicit concurrent mark sweep GC freed 22644(1246KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 954us total 85.017ms
,08-30 23:11:20.057  1989  2149 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 23:11:20.057  1862  1862 E SamsungIME: mOCRHelper is null
,08-30 23:11:20.077  1017  1124 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-30 23:11:20.077  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 23:11:20.077  1017  1124 V NetworkStats: performPollLocked(flags=0x3)
,08-30 23:11:20.077  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 23:11:20.077  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 23:11:20.087  1017  1124 V NetworkStats: performPollLocked() took 10ms
,08-30 23:11:20.087  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 23:11:20.097  1481  1481 D MenuAppsGridFragment: onResume
,08-30 23:11:20.097  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-30 23:11:20.107  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-30 23:11:20.107  4862  4862 I art     : Explicit concurrent mark sweep GC freed 22326(1362KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 12MB/17MB, paused 1.307ms total 155.085ms
,08-30 23:11:20.107  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 23:11:20.107  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 23:11:20.117  2979  2979 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 30 23:11:20 GMT+02:00 2016
,08-30 23:11:20.117  1017  4466 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-30 23:11:20.117  1017  4466 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-30 23:11:20.117  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,08-30 23:11:20.117  1017  4466 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:20.117  1017  4466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 23:11:20.117  1017  4466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-30 23:11:20.127  1440  1440 D RegisteredServicesCache: empty dynamic service
,08-30 23:11:20.127  2979  2979 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-30 23:11:20.127  1017  1029 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-30 23:11:20.127  1017  1029 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-30 23:11:20.137  6731  6731 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-30 23:11:20.137  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-30 23:11:20.147  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.147  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.147  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.147  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 23:11:20.147  1017  3822 I TactileAssist: enable value -1
08-30 23:11:20.147  1017  3822 I TactileAssist: internal enable value -1
08-30 23:11:20.147  1017  3822 I TactileAssist: intensity value -1
08-30 23:11:20.147  1017  3822 I TactileAssist: saveAppList value true
,08-30 23:11:20.157  1017  3822 I TactileAssist: List of disabled apps :
,08-30 23:11:20.157  6982  6982 E Zygote  : MountEmulatedStorage()
,08-30 23:11:20.157  6982  6982 E Zygote  : v2
08-30 23:11:20.157  6982  6982 I libpersona: KNOX_SDCARD checking this for 1000
08-30 23:11:20.157  6982  6982 I libpersona: KNOX_SDCARD not a persona
,08-30 23:11:20.167  6982  6982 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-30 23:11:20.167  6982  6982 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 23:11:20.167  1017  1043 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6982 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 23:11:20.167  6982  6982 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 23:11:20.167  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
08-30 23:11:20.167  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.167  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.167  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.167  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.167  2979  2979 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
08-30 23:11:20.177  2979  2979 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 23:11:20.177  2979  2979 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 23:11:20.197  6997  6997 E Zygote  : MountEmulatedStorage(),
08-30 23:11:20.197  6997  6997 E Zygote  : v2
08-30 23:11:20.197  6997  6997 I libpersona: KNOX_SDCARD checking this for 1000
,08-30 23:11:20.197  6997  6997 I libpersona: KNOX_SDCARD not a persona
,08-30 23:11:20.197  6997  6997 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 23:11:20.197  6997  6997 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 23:11:20.197  1017  1337 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-30 23:11:20.197  1017  1337 D SecContentProvider2: mCursor = null
,08-30 23:11:20.197  6997  6997 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 23:11:20.197  1017  1043 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6997 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 23:11:20.197  2979  6981 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-30 23:11:20.207  1017  1476 D ActivityManager: handle home activity for 0
08-30 23:11:20.207  1017  1139 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-30 23:11:20.207  1017  1476 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-30 23:11:20.207  1017  1139 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-30 23:11:20.207  1017  1476 D KnoxTimeoutHandler: post home show event for user 0
08-30 23:11:20.207  1017  1476 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-30 23:11:20.207  1017  1476 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 23:11:20.207  1017  1476 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 23:11:20.207  2979  6981 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
08-30 23:11:20.207  1017  1139 W ActivityManager: userId = 0, bbcId = -10000
08-30 23:11:20.207  1017  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 23:11:20.207  1017  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-30 23:11:20.207  1481  1481 D Launcher.HomeView: onPause
08-30 23:11:20.207  2979  6981 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
08-30 23:11:20.207  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-30 23:11:20.217  6731  6731 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-30 23:11:20.217  6731  6731 D elm:15121: ElmAgentService : onCreate()
,08-30 23:11:20.217  2979  6981 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
08-30 23:11:20.217  6982  6982 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:20.217  6731  7005 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-30 23:11:20.227  6982  6982 D ActivityThread: Added TimaKeyStore provider
08-30 23:11:20.227  6731  7005 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-30 23:11:20.227  6731  7005 D elm:15121: MDMBridge.getInstance()
08-30 23:11:20.227  6731  7005 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-30 23:11:20.227  1017  1017 I art     : Explicit concurrent mark sweep GC freed 40176(2MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 24MB/36MB, paused 14.368ms total 258.355ms
,08-30 23:11:20.227  1017  1057 I art     : WaitForGcToComplete blocked for 247.734ms for cause Explicit
,08-30 23:11:20.267  6731  7005 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-30 23:11:20.267  6997  6997 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:20.267  6997  6997 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:20.297  1440  1440 D RegisteredComponentCache: Collect Tech packages for Knox
,08-30 23:11:20.297   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,08-30 23:11:20.297  6731  6731 D elm:15121: ElmAgentService : onDestroy().
,08-30 23:11:20.297  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-30 23:11:20.307  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-30 23:11:20.307  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,08-30 23:11:20.317  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,08-30 23:11:20.317  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-30 23:11:20.317  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-30 23:11:20.317  1017  1043 W ActivityManager: mDVFSHelper.release()
,08-30 23:11:20.317  2979  6981 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-30 23:11:20.317  1017  3822 D InputDispatcher: Focus entered window: 1481
,08-30 23:11:20.317  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-30 23:11:20.317  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-30 23:11:20.317  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-30 23:11:20.327  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.327  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.327  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.327  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 23:11:20.327  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 23:11:20.327  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 23:11:20.327  1481  1481 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-30 23:11:20.337  1017  1029 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7014 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,08-30 23:11:20.347  7014  7014 E Zygote  : MountEmulatedStorage()
08-30 23:11:20.347  7014  7014 I libpersona: KNOX_SDCARD checking this for 10048
08-30 23:11:20.347  7014  7014 E Zygote  : v2
08-30 23:11:20.347  7014  7014 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:20.347  7014  7014 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 23:11:20.347  7014  7014 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 23:11:20.347  7014  7014 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-30 23:11:20.357  1481  1481 D Launcher.HomeView: onStop
08-30 23:11:20.357  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{196e9757 token=android.os.BinderProxy@20c8ffd5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-30 23:11:20.377  6997  6997 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,08-30 23:11:20.377   304   304 I art     : Explicit concurrent mark sweep GC freed 8701(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 621us total 43.047ms
,08-30 23:11:20.387  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,08-30 23:11:20.387  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-30 23:11:20.397  1017  1218 D SecContentProvider2: uri = -1 selection = getSealedState
08-30 23:11:20.397  1017  1218 D SecContentProvider2: mCursor = null
08-30 23:11:20.397  6997  6997 I PopupuiReceiver_KNOX: getSealedState : true
,08-30 23:11:20.397  1017  1139 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-30 23:11:20.397  1017  1139 D SecContentProvider2: mCursor = null
,08-30 23:11:20.397  7014  7014 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:20.397  7014  7014 D ActivityThread: Added TimaKeyStore provider
08-30 23:11:20.397   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 17.965ms
,08-30 23:11:20.397  6997  6997 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,08-30 23:11:20.397  1017  1479 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
,08-30 23:11:20.407  1017  1479 D SecContentProvider2: mCursor = null
,08-30 23:11:20.407  6982  6982 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-30 23:11:20.407  1017  1218 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-30 23:11:20.407  1017  1218 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-30 23:11:20.407  1017  1218 W ActivityManager: userId = 0, bbcId = -10000
08-30 23:11:20.407  1017  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 23:11:20.407  1017  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-30 23:11:20.417  1017  1370 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
08-30 23:11:20.417   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 16.821ms
,08-30 23:11:20.417  2979  6981 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
08-30 23:11:20.417  1017  1370 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.417  1017  1370 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.417  1017  1370 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.417  1017  1370 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 23:11:20.417  6997  6997 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-30 23:11:20.417  6997  6997 D PopupuiReceiver: Action package removed
,08-30 23:11:20.417  1017  1030 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 23:11:20.427  1017  7030 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 23:11:20.427  1017  1030 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6830 uid 10171
,08-30 23:11:20.437  2979  6981 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-30 23:11:20.437  1862  1862 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-30 23:11:20.437  7032  7032 E Zygote  : MountEmulatedStorage(),
08-30 23:11:20.437  7032  7032 I libpersona: KNOX_SDCARD checking this for 1000
08-30 23:11:20.437  7032  7032 E Zygote  : v2
08-30 23:11:20.437  7032  7032 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:20.437  7032  7032 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 23:11:20.447  7032  7032 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 23:11:20.447  7032  7032 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 23:11:20.457  1017  1370 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7032 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 23:11:20.467  1017  1370 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-30 23:11:20.467  7032  7032 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:20.467  1017  1370 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.467  1017  1370 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.467  1017  1370 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.467  7032  7032 D ActivityThread: Added TimaKeyStore provider
08-30 23:11:20.467  1017  1370 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 23:11:20.477  7014  7014 D Compatibility: onReceive() it will make start service
,08-30 23:11:20.487  7047  7047 E Zygote  : MountEmulatedStorage(),
08-30 23:11:20.487  7047  7047 I libpersona: KNOX_SDCARD checking this for 10145
08-30 23:11:20.487  7047  7047 E Zygote  : v2
08-30 23:11:20.487  7047  7047 I libpersona: KNOX_SDCARD not a persona
,08-30 23:11:20.487  7047  7047 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 23:11:20.487  1017  1057 I art     : Explicit concurrent mark sweep GC freed 9552(567KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 23.816ms total 257.381ms,
08-30 23:11:20.487  1017  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
08-30 23:11:20.487  1017  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-30 23:11:20.487  1017  1042 W TextServicesManagerService: no available spell checker services found
,08-30 23:11:20.487  1017  1370 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7047 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 23:11:20.487  7047  7047 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 23:11:20.497  7047  7047 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 23:11:20.497  1017  1370 I ActivityManager: Killing 6562:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-30 23:11:20.497  2979  2979 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-30 23:11:20.507  1017  1337 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-30 23:11:20.507  1017  1337 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-30 23:11:20.507  1017  1337 W ActivityManager: userId = 0, bbcId = -10000
08-30 23:11:20.507  1017  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 23:11:20.507  1017  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-30 23:11:20.517  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e36ddcd u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:138287
,08-30 23:11:20.527  7014  7062 D Compatibility: onHandleIntent()
,08-30 23:11:20.527  7014  7062 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-30 23:11:20.527  1017  1139 I ActivityManager: Killing 6592:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-30 23:11:20.527  7047  7047 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 23:11:20.527  7047  7047 D ActivityThread: Added TimaKeyStore provider
08-30 23:11:20.527  7014  7062 D Compatibility: found: 2
,08-30 23:11:20.537  7032  7032 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 23:11:20.557  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,08-30 23:11:20.557  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 23:11:20.557  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-30 23:11:20.557  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-30 23:11:20.557  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:20.557  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-30 23:11:20.557  7014  7062 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-30 23:11:20.567  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 23:11:20.567  7014  7062 D Compatibility: skipping ResolveInfo{16788e84 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-30 23:11:20.567  7014  7062 D Compatibility: considering ResolveInfo{ad9166d com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-30 23:11:20.567  7014  7062 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-30 23:11:20.577  7014  7062 D Compatibility: enabling receiver ResolveInfo{891f2a2 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-30 23:11:20.577  7032  7032 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-30 23:11:20.577  1017  1057 D PackageManager: delete codoeFile: 
,08-30 23:11:20.577  1017  1480 D PersonaManager: isKioskContainerExistOnDevice
,08-30 23:11:20.577  1017  1305 E Watchdog: !@Sync 4
,08-30 23:11:20.587  1017  1057 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-30 23:11:20.587  1017  1057 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-30 23:11:20.587  1017  1057 D PackageManager: result of delete: 1{1072193410}
,08-30 23:11:20.587  7014  7062 D Compatibility: enabling receiver ResolveInfo{295ddb33 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-30 23:11:20.587  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 23:11:20.587  6968  6968 D AndroidRuntime: Shutting down VM
,08-30 23:11:20.597  1017  1479 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,08-30 23:11:20.597  1017  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-30 23:11:20.597  7014  7062 D Compatibility: enabling receiver ResolveInfo{32320ef0 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-30 23:11:20.597  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 23:11:20.597  1017  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-30 23:11:20.597  1017  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:20.597  1017  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-30 23:11:20.607  1017  1050 I PowerManagerService: [PWL] Off : 75s ago
,08-30 23:11:20.607  1017  1476 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-30 23:11:20.607  1017  1476 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-30 23:11:20.607  1017  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 23:11:20.607  1017  1057 D PackageManager: userId{-1}
08-30 23:11:20.607  1017  1057 D PackageManager: andCode{true}
,08-30 23:11:20.607  7047  7047 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-30 23:11:20.607  7047  7047 D ThemeInfoUtil: isCurrentFestival = false
,08-30 23:11:20.607  7014  7062 D Compatibility: enabling receiver ResolveInfo{1d7dac69 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-30 23:11:20.617  7014  7062 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-30 23:11:20.617  1017  3640 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-30 23:11:20.617  1017  3640 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 23:11:20.617  1017  3640 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.617  1017  3640 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.617  1017  3640 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 23:11:20.637  7065  7065 E Zygote  : MountEmulatedStorage(),
08-30 23:11:20.637  7065  7065 I libpersona: KNOX_SDCARD checking this for 10087,
08-30 23:11:20.637  7065  7065 E Zygote  : v2
08-30 23:11:20.637  7065  7065 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:20.637  7065  7065 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 23:11:20.637  1017  3640 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7065 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
08-30 23:11:20.637  7065  7065 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 23:11:20.637  7065  7065 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 23:11:20.637  1017  3640 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-30 23:11:20.647  1017  3640 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.647  1017  3640 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.647  1017  3640 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.647  1017  3640 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 23:11:20.657  7073  7073 E Zygote  : MountEmulatedStorage()
08-30 23:11:20.657  7073  7073 E Zygote  : v2
08-30 23:11:20.657  7073  7073 I libpersona: KNOX_SDCARD checking this for 10148
08-30 23:11:20.657  7073  7073 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:20.657  7073  7073 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-30 23:11:20.657  7073  7073 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 23:11:20.657  1017  3640 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7073 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
08-30 23:11:20.657  1017  3640 I ActivityManager: Killing 6612:com.samsung.android.sm/1000 (adj 15): empty #21
,08-30 23:11:20.667  7073  7073 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 23:11:20.667  6424  7064 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-30 23:11:20.667  1017  3640 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-30 23:11:20.667  1017  3640 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.667  1017  3640 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.667  1017  3640 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.667  1017  3640 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 23:11:20.667  7065  7065 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:20.667  7065  7065 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:20.687  7089  7089 E Zygote  : MountEmulatedStorage()
08-30 23:11:20.687  7089  7089 E Zygote  : v2
08-30 23:11:20.687  7089  7089 I libpersona: KNOX_SDCARD checking this for 10055
08-30 23:11:20.687  7089  7089 I libpersona: KNOX_SDCARD not a persona
,08-30 23:11:20.687  7089  7089 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 23:11:20.687  7089  7089 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 23:11:20.687  1017  3640 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7089 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-30 23:11:20.687  1017  3640 I ActivityManager: Killing 6630:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-30 23:11:20.687  7089  7089 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 23:11:20.697  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-30 23:11:20.707  7073  7073 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 23:11:20.707  7073  7073 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:20.727  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 23:11:20.727  1017  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-30 23:11:20.727  7089  7089 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 23:11:20.727  7089  7089 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:20.737  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 23:11:20.737  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-30 23:11:20.737  1017  1017 V EnterpriseBillingPolicy: uID is 10171
08-30 23:11:20.737  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 23:11:20.737  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-30 23:11:20.737  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 23:11:20.737  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 23:11:20.737  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,08-30 23:11:20.737  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-30 23:11:20.737  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 23:11:20.737  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 23:11:20.737  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-30 23:11:20.747  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 23:11:20.747  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-30 23:11:20.747  1017  1017 V EnterpriseBillingPolicy: uID is 10171
08-30 23:11:20.747  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 23:11:20.747  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-30 23:11:20.747  1017  1161 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-30 23:11:20.747  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 23:11:20.747  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 23:11:20.747  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 23:11:20.747  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-30 23:11:20.747  1017  3368 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-30 23:11:20.747  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-30 23:11:20.747  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-30 23:11:20.747  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-30 23:11:20.747  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
08-30 23:11:20.747  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-30 23:11:20.747  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 23:11:20.757  1017  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 23:11:20.757  1017  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 23:11:20.757  1017  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 23:11:20.757  1017  3640 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-30 23:11:20.757  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 23:11:20.757  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-30 23:11:20.757  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.757  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.757  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.757  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 23:11:20.767  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 23:11:20.777  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 23:11:20.787  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 23:11:20.787  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-30 23:11:20.787  7112  7112 E Zygote  : MountEmulatedStorage()
,08-30 23:11:20.787  7112  7112 E Zygote  : v2
08-30 23:11:20.787  7112  7112 I libpersona: KNOX_SDCARD checking this for 1000
08-30 23:11:20.787  7112  7112 I libpersona: KNOX_SDCARD not a persona
,08-30 23:11:20.787  7112  7112 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 23:11:20.787  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-30 23:11:20.787  1017  1017 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7112 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-30 23:11:20.797  7112  7112 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 23:11:20.797  7112  7112 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 23:11:20.797  7073  7073 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-30 23:11:20.797  6968  6968 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-30 23:11:20.797  1017  1017 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-30 23:11:20.807  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 23:11:20.807  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-30 23:11:20.807  1017  1480 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
08-30 23:11:20.807  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-30 23:11:20.807  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-30 23:11:20.807  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 23:11:20.807  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
08-30 23:11:20.807  1017  1029 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-30 23:11:20.807  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 23:11:20.807  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-30 23:11:20.817  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 23:11:20.817  1017  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-30 23:11:20.817  1017  1218 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-30 23:11:20.817  7089  7089 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-30 23:11:20.817  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.817  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.817  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.817  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 23:11:20.827  7112  7112 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 23:11:20.827  7112  7112 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:20.827  1017  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-30 23:11:20.837  7129  7129 E Zygote  : MountEmulatedStorage(),
08-30 23:11:20.837  7129  7129 I libpersona: KNOX_SDCARD checking this for 10152
08-30 23:11:20.837  7129  7129 E Zygote  : v2,
08-30 23:11:20.837  7129  7129 I libpersona: KNOX_SDCARD not a persona
08-30 23:11:20.837  7129  7129 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 23:11:20.837  7129  7129 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-30 23:11:20.837  1017  1218 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7129 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,08-30 23:11:20.837  7129  7129 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 23:11:20.847  1017  1218 I ActivityManager: Killing 6660:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-30 23:11:20.877  7112  7112 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-30 23:11:20.877  7112  7112 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-30 23:11:20.877  7112  7112 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-30 23:11:20.877  7129  7129 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 23:11:20.877  7129  7129 D ActivityThread: Added TimaKeyStore provider
,08-30 23:11:20.877  7089  7089 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-30 23:11:20.877  7089  7089 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-30 23:11:20.877  7089  7089 D UserAnalysis: Create SecureDbHelper
,08-30 23:11:20.887  7089  7089 D IntelligenceServiceApplication: onCreate()
,08-30 23:11:20.887  7089  7089 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-30 23:11:20.897  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,08-30 23:11:20.897  1173  1173 I StatusBar: Icon Only
,08-30 23:11:20.897  1173  1173 D PanelView: There is/are notification(s) 
08-30 23:11:20.897  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.897  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.897  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.897  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 23:11:20.897  7089  7089 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-30 23:11:20.917  7129  7129 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,08-30 23:11:20.917  7129  7129 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,08-30 23:11:20.917  7145  7145 E Zygote  : MountEmulatedStorage()
,08-30 23:11:20.917  7145  7145 E Zygote  : v2
08-30 23:11:20.917  7145  7145 I libpersona: KNOX_SDCARD checking this for 1000
08-30 23:11:20.917  7145  7145 I libpersona: KNOX_SDCARD not a persona
,08-30 23:11:20.917  7145  7145 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-30 23:11:20.917  1017  1029 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7145 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-30 23:11:20.927  7145  7145 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-30 23:11:20.927  1017  1029 I ActivityManager: Killing 6679:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-30 23:11:20.927  1017  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 23:11:20.927  7129  7129 I TapandpayWidget:Utils: Clear T&P info.
,08-30 23:11:20.927  7145  7145 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 23:11:20.927  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-30 23:11:20.927  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:20.927  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,08-30 23:11:20.937  7129  7129 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,08-30 23:11:20.937  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-30 23:11:20.947  7089  7089 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-30 23:11:20.957  7089  7089 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-30 23:11:20.957  7089  7089 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
08-30 23:11:20.957  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 23:11:20.957  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,08-30 23:11:20.957  1017  1030 W ActivityManager: userId = 0, bbcId = -10000,
08-30 23:11:20.957  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:20.957  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:20.967  1017  3640 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 23:11:20.967  7112  7112 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-30 23:11:20.967  1017  3640 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-30 23:11:20.967  7112  7112 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-30 23:11:20.967  7112  7112 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-30 23:11:20.967  7112  7112 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-30 23:11:20.967  1017  3640 W ActivityManager: userId = 0, bbcId = -10000
08-30 23:11:20.967  1017  3640 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 23:11:20.967  1017  3640 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 23:11:20.967  7089  7089 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 23:11:20.967  7089  7089 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-30 23:11:20.967  7089  7089 D AndroidRuntime: Shutting down VM
08-30 23:11:20.967  7089  7089 E AndroidRuntime: FATAL EXCEPTION: main
08-30 23:11:20.967  7089  7089 E AndroidRuntime: Process: com.samsung.android.intelligenceservice, PID: 7089
08-30 23:11:20.967  7089  7089 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 23:11:20.967  7089  7089 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 23:11:20.977  7145  7145 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 23:11:20.977  7145  7145 D ActivityThread: Added TimaKeyStore provider
08-30 23:11:20.977  1017  3822 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
08-30 23:11:20.977  1989  1989 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-30 23:11:20.977  1989  1989 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-30 23:11:20.977  1989  1989 D AndroidRuntime: Shutting down VM
08-30 23:11:20.987  1017  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.987  1017  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.987  1017  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.987  1017  3822 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 23:11:20.997  7162  7162 E Zygote  : MountEmulatedStorage()
08-30 23:11:20.997  7162  7162 E Zygote  : v2
08-30 23:11:20.997  7162  7162 I libpersona: KNOX_SDCARD checking this for 10029
08-30 23:11:20.997  7162  7162 I libpersona: KNOX_SDCARD not a persona
,08-30 23:11:20.997  7162  7162 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-30 23:11:20.997  1017  3822 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7162 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
08-30 23:11:21.007  1017  3822 I ActivityManager: Killing 6688:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21

```
