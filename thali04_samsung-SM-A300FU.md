#### Test 8359140042466a2_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
09-01 10:59:08.099  1015  1323 E Watchdog: !@Sync 3
,--------- beginning of main
09-01 10:59:08.419  6715  6715 D AndroidRuntime: 
09-01 10:59:08.419  6715  6715 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-01 10:59:08.429  6715  6715 D AndroidRuntime: CheckJNI is OFF
09-01 10:59:08.429  6715  6715 D AndroidRuntime: readGMSProperty: start
09-01 10:59:08.429  6715  6715 D AndroidRuntime: readGMSProperty: already setted!!
09-01 10:59:08.429  6715  6715 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-01 10:59:08.429  6715  6715 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-01 10:59:08.429  6715  6715 D AndroidRuntime: readGMSProperty: end
09-01 10:59:08.429  6715  6715 D AndroidRuntime: addProductProperty: start
09-01 10:59:08.559  6715  6715 E AffinityControl: AffinityControl: registerfunction enter
09-01 10:59:08.589  6715  6715 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-01 10:59:08.609  1015  1472 E PersonaManagerService: inState():  stateMachine is null !!
09-01 10:59:08.609  1015  1472 I PersonaManagerService: PersonaId don't exist
09-01 10:59:08.609  1015  1472 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-01 10:59:08.609  1015  1472 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-01 10:59:08.629  1015  1472 W ActivityManager: mDVFSHelper.acquire()
09-01 10:59:08.639   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-01 10:59:08.639   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
09-01 10:59:08.649  1015  1472 D FocusedStackFrame: Set to : 0
09-01 10:59:08.649  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:08.649  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:08.649  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:08.649  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:08.659  1015  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-01 10:59:08.659  1015  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-01 10:59:08.659  6726  6726 E Zygote  : MountEmulatedStorage()
09-01 10:59:08.659  6726  6726 E Zygote  : v2
09-01 10:59:08.659  6726  6726 I libpersona: KNOX_SDCARD checking this for 10171
09-01 10:59:08.659  6726  6726 I libpersona: KNOX_SDCARD not a persona
09-01 10:59:08.669  6726  6726 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 10:59:08.669  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-01 10:59:08.669  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-01 10:59:08.669  1015  1472 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6726 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-01 10:59:08.669  1015  1472 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-01 10:59:08.669  1015  1472 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-01 10:59:08.669  6726  6726 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 10:59:08.669   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
09-01 10:59:08.669  6726  6726 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-01 10:59:08.679  1015  1472 D InputDispatcher: Focused application set to: xxxx
09-01 10:59:08.679  1015  1472 D InputDispatcher: Focus left window: 1479
09-01 10:59:08.679  6715  6715 D AndroidRuntime: Shutting down VM
09-01 10:59:08.679  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-01 10:59:08.679  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-01 10:59:08.689  6726  6726 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 10:59:08.699  6726  6726 D ActivityThread: Added TimaKeyStore provider
09-01 10:59:08.699  1015  1134 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-01 10:59:08.699  1015  1015 V ActivityManager: Display changed displayId=0
09-01 10:59:08.709  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-01 10:59:08.729  1015  1134 D PersonaManager: isKioskContainerExistOnDevice
09-01 10:59:08.739  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-01 10:59:08.759   258   445 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
09-01 10:59:08.759   258   453 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
09-01 10:59:08.759  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{98c3e56 token=android.os.BinderProxy@1d04f3e0 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-01 10:59:08.759  1479  1479 D Launcher: onTrimMemory. Level: 20
09-01 10:59:08.829  6726  6726 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-01 10:59:08.849  6726  6726 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 8624-8626)
09-01 10:59:08.849  6726  6726 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-01 10:59:08.869  6726  6726 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3fdb4c6e}
09-01 10:59:08.869  6726  6726 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-01 10:59:08.869  6726  6726 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
09-01 10:59:08.879  6715  6715 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-01 10:59:08.909  6726  6726 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,09-01 10:59:08.909  6726  6726 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,09-01 10:59:08.909  6726  6726 E SysUtils: ApplicationContext is null in ApplicationStatus,
,09-01 10:59:08.929  6726  6726 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-01 10:59:08.929  6726  6726 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-01 10:59:08.929  6726  6726 I Adreno-EGL: Build Date: 04/06/15 Mon
09-01 10:59:08.929  6726  6726 I Adreno-EGL: Local Branch: 
09-01 10:59:08.929  6726  6726 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-01 10:59:08.929  6726  6726 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-01 10:59:08.929  6726  6726 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-01 10:59:08.989  6726  6726 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-01 10:59:08.999  6726  6726 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-01 10:59:08.999  6726  6726 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-01 10:59:09.009  6726  6726 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-01 10:59:09.009  6726  6726 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-01 10:59:09.029   319   319 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-01 10:59:09.029   319   319 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-01 10:59:09.119  6726  6726 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 10:59:09.139  6726  6726 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-01 10:59:09.149  6726  6726 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-01 10:59:09.149  6726  6726 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-01 10:59:09.159  6726  6726 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-01 10:59:09.159  6726  6726 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 10:59:09.159  6726  6726 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 10:59:09.199  6726  6766 D OpenGLRenderer: Render dirty regions requested: true
,09-01 10:59:09.199  1015  1467 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-01 10:59:09.209  1015  1467 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-01 10:59:09.209  1015  1467 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-01 10:59:09.209  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-01 10:59:09.209  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,09-01 10:59:09.209  6726  6753 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-01 10:59:09.219  6726  6726 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-01 10:59:09.219  6726  6726 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-01 10:59:09.229   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-01 10:59:09.239  1015  1495 D InputDispatcher: Focus entered window: 6726
,09-01 10:59:09.239  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-01 10:59:09.249  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-01 10:59:09.249  6726  6726 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-01 10:59:09.249  6726  6766 I OpenGLRenderer: Initialized EGL, version 1.4
,09-01 10:59:09.249  6726  6766 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-01 10:59:09.249  6726  6766 D OpenGLRenderer: Enabling debug mode 0
,09-01 10:59:09.269  6726  6726 V ActivityThread: updateVisibility : ActivityRecord{122770ef token=android.os.BinderProxy@2dad7e93 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-01 10:59:09.299  1015  1467 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-01 10:59:09.299  1176  1176 I StatusBar: Icon Only
,09-01 10:59:09.299  1176  1176 D PanelView: There is/are notification(s) 
,09-01 10:59:09.309  1015  6770 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-01 10:59:09.319  1015  1045 I ActivityManager: Displayed Component not be shown by security: +585ms (total +663ms)
,09-01 10:59:09.319  1015  1045 W ActivityManager: mDVFSHelper.release()
,09-01 10:59:09.319  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3a27daf5 u0 com.test.thalitest/.MainActivity t2} time:109094
,09-01 10:59:09.319  6726  6726 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-01 10:59:09.319  6726  6726 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2dad7e93 time:109094
,09-01 10:59:09.319   258  1095 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-01 10:59:09.349  1874  1874 I SamsungIME: getCurrentCandidateView
,09-01 10:59:09.449  1874  1874 D SamsungIME: Dismiss ExpandCandiate
,09-01 10:59:09.469  6726  6726 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6726
,09-01 10:59:09.599  1874  1874 I SamsungIME: getDebugLevel  : 0x4f4c
,09-01 10:59:09.639  1874  1874 I SamsungIME: getDebugLevel  : 0x4f4c
,09-01 10:59:09.649  1874  1874 I SamsungIME: KeybaordView init() : load resources
,09-01 10:59:09.669  1874  1874 I SamsungIME: getCurrentKeyboard
09-01 10:59:09.669  1874  1874 I SamsungIME: getTextKeyboard
,09-01 10:59:09.689  6726  6726 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-01 10:59:09.709  1874  1874 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-01 10:59:09.769  6726  6772 D jxcore_app_log: JniHelper::setJavaVM(0xb795e2b0), pthread_self() = -1209050000
,09-01 10:59:09.779  6726  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-01 10:59:09.779  6726  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-01 10:59:09.779  6726  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-01 10:59:09.779  6726  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-01 10:59:09.779  6726  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-01 10:59:09.779  6726  6772 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@355f6a94 added. We now have 1 listener(s)
,09-01 10:59:09.779  6726  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,09-01 10:59:09.779  6726  6772 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-01 10:59:09.779  6726  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 10:59:09.789  6726  6772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 10:59:09.789  6726  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-01 10:59:09.789  6726  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-01 10:59:09.789  6726  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-01 10:59:09.789  6726  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
09-01 10:59:09.789  6726  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-01 10:59:09.789  6726  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-01 10:59:09.789  6726  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-01 10:59:09.789  6726  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-01 10:59:09.789  6726  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-01 10:59:09.789  6726  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-01 10:59:09.789  6726  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-01 10:59:09.789  6726  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-01 10:59:09.789  6726  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-01 10:59:09.789  6726  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-01 10:59:09.789  6726  6772 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33283 added. We now have 1 listener(s)
09-01 10:59:09.789  6726  6772 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:09.799  6726  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 10:59:09.799  6726  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-01 10:59:09.799  6726  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-01 10:59:09.799  6726  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3,
09-01 10:59:09.799  6726  6772 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-01 10:59:09.799  6726  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:09.799  6726  6772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,09-01 10:59:09.809  6726  6772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-01 10:59:09.809  6726  6772 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:09.809  6726  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:09.809  6726  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:09.809  6726  6772 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:09.809  6726  6772 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:09.809  6726  6772 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:09.809  6726  6772 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:09.809  6726  6772 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 10:59:09.809  6726  6772 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-01 10:59:09.809  6726  6772 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:09.809  6726  6772 I io.jxcore.node.LifeCycleMonitor: start: OK
09-01 10:59:09.809  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:09.819  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:09.849  6726  6726 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-01 10:59:10.029   288   288 E SMD     : DCD OFF
,09-01 10:59:10.179  1015  1473 I art     : Explicit concurrent mark sweep GC freed 34467(1859KB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 24MB/36MB, paused 2.400ms total 151.322ms
,09-01 10:59:10.379  6726  6780 W jxcore-log: Initializing JXcore engine
09-01 10:59:10.379  6726  6780 W jxcore-log: JXcore engine is ready
,09-01 10:59:10.439  1947  1947 E audit   : type=1400 msg=audit(1472720350.439:205): avc:  denied  { ioctl } for  pid=6780 comm="Thread-1231" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2066 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-01 10:59:10.439  1947  1947 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-01 10:59:10.439  1947  1947 E audit   : type=1300 msg=audit(1472720350.439:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9f2bd8f8 items=0 ppid=307 ppcomm=main pid=6780 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1231" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-01 10:59:10.439  1947  1947 E audit   : type=1320 msg=audit(1472720350.439:205): 
,09-01 10:59:10.449  6726  6780 W jxcore-log: Starting JXcore engine,
,09-01 10:59:10.559  6726  6780 W jxcore-log: Platform android
09-01 10:59:10.559  6726  6780 W jxcore-log: 
09-01 10:59:10.559  6726  6780 W jxcore-log: Process ARCH arm
09-01 10:59:10.559  6726  6780 W jxcore-log: 
,09-01 10:59:10.759  6726  6780 I jxcore-log: JXcore Cordova bridge is ready!
09-01 10:59:10.759  6726  6780 I jxcore-log: 
,09-01 10:59:10.759  6726  6780 W jxcore-log: JXcore engine is started
,09-01 10:59:10.769  6726  6772 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-01 10:59:10.769  6726  6726 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-01 10:59:13.029   288   288 E SMD     : DCD OFF
,09-01 10:59:13.339  1015  1047 I PowerManagerService: [PWL] Off : 50s ago,
,09-01 10:59:13.649  1015  3326 D SSRM:n  : SIOP:: AP = 320
,09-01 10:59:14.039   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-01 10:59:15.029  5635  5635 D FactoryTest: Not factory mode
,09-01 10:59:15.029  5635  5635 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-01 10:59:15.029  5635  5635 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-01 10:59:15.039  5635  5635 D MTPRx   : still no open session command from host, so toast
,09-01 10:59:15.039   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:15.039  5635  5635 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-01 10:59:15.039  5635  5635 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-01 10:59:15.039  5635  5635 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114817
,09-01 10:59:15.039  1015  1473 E PersonaManagerService: inState():  stateMachine is null !!
,09-01 10:59:15.039  1015  1473 I PersonaManagerService: PersonaId don't exist
09-01 10:59:15.039  1015  1473 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-01 10:59:15.049  1015  1473 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-01 10:59:15.049  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:15.049  1015  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:15.049  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
09-01 10:59:15.059  1015  1473 W ActivityManager: mDVFSHelper.acquire()
,09-01 10:59:15.069  1015  1473 D PersonaManager: isKioskContainerExistOnDevice
,09-01 10:59:15.099  1015  1473 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-01 10:59:15.099  1015  1473 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-01 10:59:15.099  1015  1473 D InputDispatcher: Focused application set to: xxxx
09-01 10:59:15.099  1015  1473 D InputDispatcher: Focus left window: 6726
09-01 10:59:15.099  5635  5635 E MTPRx   : started activity for popup
,09-01 10:59:15.099  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-01 10:59:15.109  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-01 10:59:15.129  5635  5635 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-01 10:59:15.129  5635  5635 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-01 10:59:15.129  5635  5635 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-01 10:59:15.129  5635  5635 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-01 10:59:15.129  5635  5635 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-01 10:59:15.129  5635  5635 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-01 10:59:15.169  5635  5635 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-01 10:59:15.179  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-01 10:59:15.179  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-01 10:59:15.179  1015  1027 D InputDispatcher: Focused application set to: xxxx
,09-01 10:59:15.179  1015  1027 D InputDispatcher: Focus entered window: 6726
,09-01 10:59:15.189  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-01 10:59:15.189  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-01 10:59:15.189  1015  1481 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-01 10:59:15.189  1015  1481 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@343b98bc attribute=null, token = android.os.BinderProxy@168bf48c
,09-01 10:59:15.229  5635  5635 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-01 10:59:15.229  5635  5635 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-01 10:59:15.239  5635  5635 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-01 10:59:15.259  6726  6726 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-01 10:59:15.259  6726  6726 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-01 10:59:15.259  6726  6726 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-01 10:59:15.259  6726  6726 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-01 10:59:15.259  1015  1472 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-01 10:59:15.259  1015  1472 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-01 10:59:15.259  1015  1472 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-01 10:59:15.259  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-01 10:59:15.259  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,09-01 10:59:15.269  6726  6726 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-01 10:59:15.269  6726  6726 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-01 10:59:15.279  6726  6726 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2dad7e93 time:115051
,09-01 10:59:15.279  6726  6726 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1ef209ff Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3e251634, 16908290=android.view.AbsSavedState$1@3e251634}, android:focusedViewId=100}]}]
,09-01 10:59:15.279  6726  6726 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-01 10:59:15.279  6726  6726 V ActivityThread: updateVisibility : ActivityRecord{122770ef token=android.os.BinderProxy@2dad7e93 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-01 10:59:15.279  6726  6726 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-01 10:59:15.279  6726  6726 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-01 10:59:15.289  1015  1467 D PersonaManager: isKioskContainerExistOnDevice
,09-01 10:59:16.029   288   288 E SMD     : DCD OFF,
,09-01 10:59:16.039   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:16.439  1015  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-01 10:59:16.439  1015  1322 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-01 10:59:16.439  1015  1322 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-01 10:59:16.439  1015  1322 D BatteryService: stay LED for fully charged
09-01 10:59:16.439  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-01 10:59:16.449  1015  1015 I MotionRecognitionService: Plugged
09-01 10:59:16.449  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-01 10:59:16.449  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-01 10:59:16.449  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-01 10:59:16.449  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-01 10:59:16.449  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-01 10:59:16.459  3153  3153 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-01 10:59:16.459  3153  3255 D HeadsetStateMachine: Disconnected process message: 10
,09-01 10:59:16.469  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
09-01 10:59:16.469  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-01 10:59:16.469  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-01 10:59:17.039   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-01 10:59:18.039   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-01 10:59:18.059  1015  1040 W ActivityManager: mDVFSHelper.release(),
,09-01 10:59:18.699  1015  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-01 10:59:19.039   288   288 E SMD     : DCD OFF
,09-01 10:59:19.039   319   319 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-01 10:59:20.229  1015  1093 V AlarmManager: waitForAlarm result :4,
,09-01 10:59:20.239  1015  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0,
,09-01 10:59:20.249  1015  1015 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-01 10:59:20.249  1015  1015 V AlarmManagerEXT: <AppSync3 Whitelist>
,09-01 10:59:20.249  1015  1015 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-01 10:59:20.259  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-01 10:59:20.259  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,09-01 10:59:20.269  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-01 10:59:20.269  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,09-01 10:59:20.279  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-01 10:59:20.279  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
09-01 10:59:20.279  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,09-01 10:59:20.279  1937  1937 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos,
,09-01 10:59:20.309  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-01 10:59:20.319  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-01 10:59:20.319  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-01 10:59:20.339  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-01 10:59:20.349  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:20.349  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-01 10:59:20.349  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:20.349  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:20.349  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:20.409  4760  4760 D ConnectivityManager: CallingUid : 10011, CallingPid : 4760
,09-01 10:59:20.409  1015  1481 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-01 10:59:20.409  1015  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,09-01 10:59:20.409  1015  1126 D ConnectivityService: apparently satisfied.  currentScore=60
,09-01 10:59:20.409  1015  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-01 10:59:20.409  4760  6790 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-01 10:59:20.459  4760  6791 W DriveInitializer: Background init thread started
,09-01 10:59:20.489   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-01 10:59:20.489   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:20.489  4760  6791 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-01 10:59:20.549  1015  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:20.549  1015  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-01 10:59:20.549  1015  1481 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:20.549  1015  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:20.549  1015  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:20.569  1015  1319 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-01 10:59:20.569  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-01 10:59:20.579  4760  6791 W DriveInitializer: Background init thread ended
,09-01 10:59:20.599  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:20.599  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-01 10:59:20.599  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:20.599  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:20.599  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:20.629  4760  6799 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.,
09-01 10:59:20.629  4760  6799 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-01 10:59:20.649  1937  1937 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-01 10:59:20.679  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:20.679  1015  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:20.679  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:20.749  1015  1462 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:20.749  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-01 10:59:20.749  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:20.749  1015  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:20.749  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:20.789  1015  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:20.789  1015  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-01 10:59:20.789  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:20.789  1015  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:20.789  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:20.849  1015  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:20.849  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:20.849  1015  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:20.849  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:20.889  1015  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:20.889  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:20.889  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:20.889  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:20.949  1015  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:20.949  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:20.949  1015  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:20.949  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:20.949  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:20.949  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:20.949  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:20.949  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:20.969  6804  6804 E Zygote  : MountEmulatedStorage()
09-01 10:59:20.969  6804  6804 E Zygote  : v2
09-01 10:59:20.969  6804  6804 I libpersona: KNOX_SDCARD checking this for 10011
09-01 10:59:20.969  6804  6804 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:20.969  6804  6804 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:20.979  6804  6804 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:20.979  1015  1472 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6804 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-01 10:59:20.979  6804  6804 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-01 10:59:21.019  6804  6804 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:21.019  6804  6804 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:21.039  6804  6804 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-01 10:59:21.039  6804  6804 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-01 10:59:21.079  6804  6804 I MultiDex: VM with version 2.1.0 has multidex support
09-01 10:59:21.079  6804  6804 I MultiDex: install
09-01 10:59:21.079  6804  6804 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-01 10:59:21.109  6804  6804 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-01 10:59:21.169  6804  6804 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-01 10:59:21.169  6804  6804 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e3cd88a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-01 10:59:21.169  6804  6804 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-01 10:59:21.199  6804  6804 D ChimeraCfgMgr: Reading stored module config
,09-01 10:59:21.209  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-01 10:59:21.219  1015  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:21.229  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:21.229  1015  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.229  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.229  1015  1462 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:21.229  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:21.229  1015  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.229  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.269  1937  1937 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=87a8d09e-26f0-4100-afc1-2179fa3b3e2b
,09-01 10:59:21.279  1015  1467 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-01 10:59:21.279  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-01 10:59:21.279  6804  6818 I art     : Background sticky concurrent mark sweep GC freed 27855(1323KB) AllocSpace objects, 2(32KB) LOS objects, 1% free, 7MB/7MB, paused 11.348ms total 81.320ms
,09-01 10:59:21.289  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:21.289  1015  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.289  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.289  1937  1937 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-01 10:59:21.299  1937  1937 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-01 10:59:21.299  6804  6822 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
09-01 10:59:21.329  1015  1473 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-01 10:59:21.329  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:21.329  1015  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.329  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.339  6804  6804 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-01 10:59:21.339  6804  6804 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-01 10:59:21.419   283   698 D WVCdm   : Instantiating CDM.
,09-01 10:59:21.419   283   283 I WVCdm   : CdmEngine::OpenSession
09-01 10:59:21.419   283   283 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-01 10:59:21.439  1937  2154 W GCoreFlp: No location to return for getLastLocation()
,09-01 10:59:21.449   283   283 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-01 10:59:21.469  4260  4271 I art     : Explicit concurrent mark sweep GC freed 1671(60KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 694us total 23.915ms
,09-01 10:59:21.469   283   283 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,09-01 10:59:21.499  4760  6800 D UdcContextInitService: registered all accounts: true
,09-01 10:59:21.519  1937  2157 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-01 10:59:21.529  1937  2170 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-01 10:59:21.549   283   283 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-01 10:59:21.549   283   698 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,09-01 10:59:21.549   283   698 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,09-01 10:59:21.549   283   698 I WVCdm   : CdmEngine::GenerateKeyRequest
,09-01 10:59:21.549   283   698 D WVCdm   : PrepareKeyRequest: nonce=3558116031
,09-01 10:59:21.579  6804  6813 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,09-01 10:59:21.579  6804  6813 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:21.579  6804  6813 I System.out: (HTTPLog)-Static: isShipBuild true
,09-01 10:59:21.579  6804  6813 I System.out: (HTTPLog)-Thread-1209-785388239: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,09-01 10:59:21.579  6804  6813 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:21.589   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-01 10:59:21.589   278  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-01 10:59:21.599  1937  2154 I art     : Explicit concurrent mark sweep GC freed 55936(3MB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 11MB/19MB, paused 4.030ms total 124.725ms
,09-01 10:59:21.639  6804  6813 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-01 10:59:21.639  6804  6813 I qtaguid : Tagging socket 33 with tag 1000180300000000{268441603,0} for uid -1, pid: 6804, getuid(): 10011
,09-01 10:59:21.659  1015  1462 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:21.659  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:21.669  1015  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.669  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.669  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:21.679  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:21.679  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.679  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.679  1015  1473 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:21.689  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:21.689  1015  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.689  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.709  1015  1322 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-01 10:59:21.709  1015  1322 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-01 10:59:21.709  1015  1322 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:21.709  1015  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.709  1015  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.749  1015  1322 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:21.749  1015  1322 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-01 10:59:21.749  1015  1322 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:21.749  1015  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.749  1015  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.819  1015  1467 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-01 10:59:21.819  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-01 10:59:21.819  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:21.819  1015  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.819  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.839  1937  2170 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:21.839   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-01 10:59:21.839   278  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-01 10:59:21.849  1937  2170 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-01 10:59:21.849  1937  2170 I qtaguid : Tagging socket 75 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1937, getuid(): 10011
,09-01 10:59:21.879  6804  6813 I qtaguid : Untagging socket 33
,09-01 10:59:21.899  1937  2170 I qtaguid : Tagging socket 76 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1937, getuid(): 10011
,09-01 10:59:21.909  1015  1322 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:21.919  1015  1322 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:21.919  1015  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.919  1015  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.969  1015  1134 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:21.979  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:21.979  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.979  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:22.019  1015  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:22.019  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:22.019  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:22.019  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:22.019  1937  6839 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-01 10:59:22.019  1937  6835 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-01 10:59:22.029  1015  1473 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:22.029  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:22.029  1015  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:22.029  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:22.039   288   288 E SMD     : DCD OFF
,09-01 10:59:22.059  1015  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:22.059  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:22.059  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:22.059  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:22.059  1937  6839 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-01 10:59:22.059  1937  6835 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-01 10:59:22.059  1015  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:22.059  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:22.069  1015  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:22.069  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:22.089  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:22.089  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:22.089  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:22.089  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:22.089  1937  6839 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-01 10:59:22.089  1937  6835 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-01 10:59:22.089  1937  6835 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-01 10:59:22.109  1937  6835 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-01 10:59:22.199  1015  1473 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-01 10:59:22.259  1937  6835 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:22.269   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-01 10:59:22.269   278  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-01 10:59:22.269  1937  6835 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-01 10:59:22.269  1937  6835 I qtaguid : Tagging socket 82 with tag fffffca200000000{4294966434,0} for uid -1, pid: 1937, getuid(): 10011
,09-01 10:59:22.309  1937  6835 I qtaguid : Tagging socket 85 with tag fffffca200000000{4294966434,0} for uid -1, pid: 1937, getuid(): 10011
,09-01 10:59:22.379  1015  3358 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-01 10:59:22.569  1015  1319 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-01 10:59:22.579  1937  6835 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:22.579  1937  6835 I qtaguid : Tagging socket 82 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1937, getuid(): 10011
,09-01 10:59:22.629  6843  6843 I dex2oat : ----------------------------------------------------
09-01 10:59:22.629  6843  6843 I dex2oat : <SS>: S T A R T I N G . . .
09-01 10:59:22.629  6843  6843 I dex2oat : <SS>: Zip is absent. Canceled.
,09-01 10:59:22.629  6843  6843 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-01 10:59:22.699  6843  6843 I dex2oat : dex2oat took 60.637ms (threads: 4)
,09-01 10:59:22.709  6804  6813 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-01 10:59:22.709  6804  6813 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-01 10:59:22.709  6804  6813 I Adreno-EGL: Build Date: 04/06/15 Mon
09-01 10:59:22.709  6804  6813 I Adreno-EGL: Local Branch: 
09-01 10:59:22.709  6804  6813 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-01 10:59:22.709  6804  6813 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-01 10:59:22.709  6804  6813 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-01 10:59:22.719  1015  1481 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-01 10:59:22.729  1937  6835 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:22.729  1937  6835 I qtaguid : Tagging socket 82 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1937, getuid(): 10011
,09-01 10:59:22.789  6804  6813 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-01 10:59:22.789  6804  6813 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-01 10:59:22.789  6804  6813 I Adreno-EGL: Build Date: 04/06/15 Mon
09-01 10:59:22.789  6804  6813 I Adreno-EGL: Local Branch: 
09-01 10:59:22.789  6804  6813 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-01 10:59:22.789  6804  6813 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-01 10:59:22.789  6804  6813 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-01 10:59:22.829  6804  6813 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-01 10:59:22.829  6804  6813 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-01 10:59:22.829  6804  6813 I Adreno-EGL: Build Date: 04/06/15 Mon
09-01 10:59:22.829  6804  6813 I Adreno-EGL: Local Branch: 
09-01 10:59:22.829  6804  6813 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-01 10:59:22.829  6804  6813 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-01 10:59:22.829  6804  6813 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-01 10:59:22.859  1015  1472 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-01 10:59:22.859  1937  6835 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:22.859  1937  6835 I qtaguid : Tagging socket 82 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1937, getuid(): 10011
,09-01 10:59:22.909  1937  6802 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:22.909  1937  6802 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-01 10:59:22.909  1937  6802 I qtaguid : Tagging socket 79 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1937, getuid(): 10011
,09-01 10:59:22.949  1937  6802 I qtaguid : Tagging socket 88 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1937, getuid(): 10011
,09-01 10:59:23.109  1937  2170 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-01 10:59:23.109  1937  2170 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-01 10:59:23.119  1937  2170 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-01 10:59:21.635+0200, stopTime=2016-09-01 10:59:23.125+0200, duration=1490ms
,09-01 10:59:23.119  1937  6852 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:23.119   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-01 10:59:23.119   278  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-01 10:59:23.129  1937  6852 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-01 10:59:23.129  1937  6852 I qtaguid : Tagging socket 69 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1937, getuid(): 10011
,09-01 10:59:23.169  1937  6852 I qtaguid : Tagging socket 72 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1937, getuid(): 10011
,09-01 10:59:23.169   283   676 I WVCdm   : CdmEngine::CloseSession
,09-01 10:59:23.169   283   676 I WVCdm   : L3 Terminate.
,09-01 10:59:23.349  1937  6852 I qtaguid : Untagging socket 69
,09-01 10:59:23.349  1937  2170 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-01 10:59:23.669  1015  3326 D SSRM:n  : SIOP:: AP = 350
,09-01 10:59:24.039   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:24.139  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-01 10:59:24.139  6726  6780 I jxcore-log: 
,09-01 10:59:24.139  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-01 10:59:24.139  6726  6780 I jxcore-log: 
,09-01 10:59:24.149  6726  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:24.149  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:24.149  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:24.149  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:24.149  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:24.149  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:24.149  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:24.149  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:24.149  6726  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:24.149  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-01 10:59:24.149  6726  6780 I jxcore-log: 
,09-01 10:59:24.159  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-01 10:59:24.159  6726  6780 I jxcore-log: 
,09-01 10:59:24.819  6726  6780 D executeNativeTests: Running unit tests
,09-01 10:59:24.909  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:24.909  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd added. We now have 2 listener(s)
,09-01 10:59:24.919  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-01 10:59:24.919  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:24.919  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:24.919  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:24.919  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 added. We now have 2 listener(s)
09-01 10:59:24.919  6726  6780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:24.919  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 10:59:24.919  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:24.919  6726  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:24.919  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:24.919  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:24.919  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:24.919  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:24.919  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:24.919  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:24.919  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:24.919  6726  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:24.919  6726  6780 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 10:59:24.929  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:24.929  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:24.929  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-01 10:59:24.929  6726  6780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 10:59:24.929  6726  6780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-01 10:59:24.929  6726  6780 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-01 10:59:24.929  6726  6780 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 10:59:24.929  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 10:59:24.929  6726  6780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 10:59:24.929  6726  6780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-01 10:59:24.929  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:24.939  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:24.939  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 10:59:24.939  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:24.939  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:24.939  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-01 10:59:24.939  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:24.939  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd removed from the list
09-01 10:59:24.939  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:24.939  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 removed from the list
09-01 10:59:24.939  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:24.939  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:24.939  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:24.939  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:24.939  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:24.939  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:24.939  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:24.939  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
,09-01 10:59:24.939  6726  6780 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-01 10:59:24.939  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:24.939  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:24.939  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:24.939  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:24.939  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:24.939  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:24.939  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:24.939  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:24.939  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:24.939  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:24.939  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:24.939  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:24.939  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:24.939  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:24.939  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:24.939  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:24.939  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:24.939  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 10:59:24.949  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:24.949  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:24.949  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:24.949  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:24.949  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:24.949  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:24.949  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:24.949  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:24.949  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:24.949  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:24.949  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:24.949  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:24.949  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:24.949  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:24.949  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:24.949  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:24.949  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:24.949  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:24.949  6726  6780 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 10:59:24.959  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:24.959  6726  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:24.959  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:24.959  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:24.959  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:24.959  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:24.959  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:24.959  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:24.959  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 10:59:24.959  6726  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:24.959  6726  6780 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:24.959  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:24.959  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 10:59:24.959  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 10:59:24.959  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:24.959  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 10:59:24.969  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:24.969  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 10:59:24.969  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:24.969  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 10:59:24.979  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 10:59:24.979  6726  6780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-01 10:59:24.989  6726  6780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-01 10:59:24.989  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 10:59:24.989  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 10:59:24.989  6726  6780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-01 10:59:24.999  3153  3163 D BtGatt.GattService: registerClient() - UUID=7ad38d6e-01f4-4144-8bac-a49a7fb5c76a
,09-01 10:59:25.039   288   288 E SMD     : DCD OFF
09-01 10:59:25.039   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:25.049  3153  3248 D BtGatt.GattService: onClientRegistered() - UUID=7ad38d6e-01f4-4144-8bac-a49a7fb5c76a, clientIf=6
,09-01 10:59:25.049  6726  6734 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-01 10:59:25.049  3153  3161 D BtGatt.GattService: start scan with filters
,09-01 10:59:25.049  3153  3254 D BtGatt.ScanManager: handling starting scan
,09-01 10:59:25.049  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-01 10:59:25.059  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-01 10:59:25.059  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 10:59:25.059  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 10:59:25.059  3153  3254 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:25.059  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:25.059  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 10:59:25.059  6726  6726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:25.069  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 10:59:25.069  3153  3248 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-01 10:59:25.069  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:25.069  3153  3254 D BtGatt.ScanManager: allow scan with filters
,09-01 10:59:25.069  3153  3254 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-01 10:59:25.079  3153  3254 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-01 10:59:25.079  6726  6780 I io.jxcore.node.ConnectionHelper: start: OK
,09-01 10:59:25.079  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:25.079  6726  6780 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 10:59:25.079  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:25.079  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 10:59:25.079  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.079  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 10:59:25.079  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 10:59:25.079  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:25.079  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 10:59:25.079  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:25.079  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 10:59:25.079  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 10:59:25.079  3153  3248 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-01 10:59:25.079  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:25.079  3153  3254 D BtGatt.ScanManager: Starting BLE batch scan
09-01 10:59:25.079  3153  3254 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-01 10:59:25.089  3153  3323 D BtGatt.GattService: stopScan() - queue size =1
,09-01 10:59:25.089  3153  3163 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-01 10:59:25.089  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-01 10:59:25.089  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-01 10:59:25.089  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-01 10:59:25.089  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-01 10:59:25.089  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 10:59:25.099  3153  3248 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-01 10:59:25.099  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:25.099  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:25.099  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-01 10:59:25.099  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 10:59:25.099  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 10:59:25.099  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 10:59:25.099  6726  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 10:59:25.099  6726  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 10:59:25.099  6726  6726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:25.099  3153  3248 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-01 10:59:25.099  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:25.109  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.109  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.109  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 10:59:25.109  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.109  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.109  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.109  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:25.109  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.109  6726  6780 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-01 10:59:25.109  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:25.109  3153  3254 D BtGatt.ScanManager: filter size is 1
,09-01 10:59:25.109  3153  3254 D BtGatt.ScanManager: delete FilterIndex - 3
,09-01 10:59:25.119  6726  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:25.119  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:25.119  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:25.119  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:25.119  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:25.119  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:25.119  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:25.119  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:25.119  6726  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:25.119  6726  6780 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:25.119  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:25.119  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 10:59:25.119  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 10:59:25.119  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:25.119  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 10:59:25.119  3153  3248 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-01 10:59:25.119  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:25.119  3153  3254 D BtGatt.ScanManager: stopping BLe Batch
,09-01 10:59:25.119  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 10:59:25.119  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:25.129  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:25.129  3153  3248 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-01 10:59:25.129  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:25.129  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 10:59:25.129  3153  3254 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-01 10:59:25.129  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 10:59:25.129  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 10:59:25.129  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-01 10:59:25.129  6726  6780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 10:59:25.139  3153  3248 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-01 10:59:25.139  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:25.139  3153  3161 D BtGatt.GattService: registerClient() - UUID=68c0458a-98f2-48bc-a83d-155276d279b2
,09-01 10:59:25.179  3153  3248 D BtGatt.GattService: onClientRegistered() - UUID=68c0458a-98f2-48bc-a83d-155276d279b2, clientIf=6
,09-01 10:59:25.179  6726  6736 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-01 10:59:25.179  3153  3323 D BtGatt.GattService: start scan with filters
,09-01 10:59:25.189  3153  3254 D BtGatt.ScanManager: handling starting scan
,09-01 10:59:25.189  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-01 10:59:25.189  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 10:59:25.189  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-01 10:59:25.189  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 10:59:25.189  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:25.189  6726  6726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:25.189  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 10:59:25.189  3153  3248 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-01 10:59:25.189  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:25.189  3153  3254 D BtGatt.ScanManager: allow scan with filters
09-01 10:59:25.189  3153  3254 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-01 10:59:25.189  3153  3254 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-01 10:59:25.199  3153  3248 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-01 10:59:25.199  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:25.199  3153  3254 D BtGatt.ScanManager: Starting BLE batch scan
09-01 10:59:25.199  3153  3254 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-01 10:59:25.199  3153  3248 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-01 10:59:25.199  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:25.199  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 10:59:25.199  3153  3248 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-01 10:59:25.199  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:25.199  6726  6780 I io.jxcore.node.ConnectionHelper: start: OK
,09-01 10:59:25.209  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:25.209  6726  6780 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 10:59:25.209  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:25.209  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 10:59:25.209  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.209  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 10:59:25.209  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 10:59:25.209  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:25.209  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 10:59:25.209  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:25.209  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 10:59:25.209  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 10:59:25.209  3153  3163 D BtGatt.GattService: stopScan() - queue size =1
,09-01 10:59:25.209  3153  3254 D BtGatt.ScanManager: filter size is 1
,09-01 10:59:25.209  3153  3254 D BtGatt.ScanManager: delete FilterIndex - 4
,09-01 10:59:25.209  3153  3161 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-01 10:59:25.209  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 10:59:25.209  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 10:59:25.209  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 10:59:25.209  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 10:59:25.209  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 10:59:25.209  3153  3248 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-01 10:59:25.209  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:25.209  3153  3254 D BtGatt.ScanManager: stopping BLe Batch
,09-01 10:59:25.219  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:25.219  1937  6850 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:25.219  1937  6850 I qtaguid : Tagging socket 69 with tag 1000310200000000{268448002,0} for uid 10011, pid: 1937, getuid(): 10011
,09-01 10:59:25.219  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 10:59:25.219  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 10:59:25.219  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 10:59:25.219  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 10:59:25.219  6726  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 10:59:25.219  6726  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:25.219  6726  6726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:25.219  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.219  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.219  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:25.219  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.219  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.219  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.219  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:25.219  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.219  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.219  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:25.219  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:25.219  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:25.219  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:25.219  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
,09-01 10:59:25.229  3153  3248 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-01 10:59:25.229  6726  6780 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-01 10:59:25.229  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:25.229  3153  3254 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-01 10:59:25.229  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:25.229  3153  3248 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-01 10:59:25.229  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:25.229  6726  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:25.229  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:25.229  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:25.229  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:25.229  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:25.229  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:25.229  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:25.229  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:25.239  6726  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:25.239  6726  6780 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:25.239  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:25.239  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 10:59:25.239  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 10:59:25.239  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:25.239  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 10:59:25.239  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:25.239  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 10:59:25.239  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:25.239  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 10:59:25.249  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 10:59:25.249  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 10:59:25.249  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 10:59:25.249  6726  6780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 10:59:25.249  3153  3323 D BtGatt.GattService: registerClient() - UUID=c05f0dbb-a67d-409c-94f6-6d81dbc6e4a4
,09-01 10:59:25.289  3153  3248 D BtGatt.GattService: onClientRegistered() - UUID=c05f0dbb-a67d-409c-94f6-6d81dbc6e4a4, clientIf=6
,09-01 10:59:25.289  6726  6734 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-01 10:59:25.289  3153  3161 D BtGatt.GattService: start scan with filters
,09-01 10:59:25.289  3153  3254 D BtGatt.ScanManager: handling starting scan
,09-01 10:59:25.299  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 10:59:25.299  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 10:59:25.299  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 10:59:25.299  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 10:59:25.299  3153  3248 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-01 10:59:25.299  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:25.299  3153  3254 D BtGatt.ScanManager: allow scan with filters
,09-01 10:59:25.299  3153  3254 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-01 10:59:25.299  3153  3254 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-01 10:59:25.299  3153  3248 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-01 10:59:25.299  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:25.299  3153  3254 D BtGatt.ScanManager: Starting BLE batch scan
09-01 10:59:25.299  3153  3254 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-01 10:59:25.309  3153  3248 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-01 10:59:25.309  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:25.309  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:25.309  6726  6726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:25.309  3153  3248 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-01 10:59:25.309  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:25.309  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 10:59:25.319  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 10:59:25.319  6726  6780 I io.jxcore.node.ConnectionHelper: start: OK
,09-01 10:59:25.319  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:25.319  6726  6780 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-01 10:59:25.319  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:25.319  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-01 10:59:25.319  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.319  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-01 10:59:25.319  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 10:59:25.319  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:25.319  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
09-01 10:59:25.319  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-01 10:59:25.329  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 10:59:25.329  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 10:59:25.329  3153  3163 D BtGatt.GattService: stopScan() - queue size =1
,09-01 10:59:25.329  3153  3323 D BtGatt.GattService: unregisterClient() - clientIf=6,
09-01 10:59:25.329  3153  3254 D BtGatt.ScanManager: filter size is 1
09-01 10:59:25.329  3153  3254 D BtGatt.ScanManager: delete FilterIndex - 5
,09-01 10:59:25.329  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 10:59:25.329  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 10:59:25.329  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 10:59:25.329  3153  3248 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-01 10:59:25.329  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:25.329  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 10:59:25.329  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-01 10:59:25.329  3153  3254 D BtGatt.ScanManager: stopping BLe Batch
,09-01 10:59:25.329  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:25.329  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-01 10:59:25.329  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 10:59:25.329  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 10:59:25.329  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 10:59:25.339  3153  3248 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-01 10:59:25.339  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:25.339  3153  3254 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-01 10:59:25.339  6726  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:25.339  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:25.339  6726  6780 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 10:59:25.339  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:25.339  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:25.339  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.339  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.339  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:25.339  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.339  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.339  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.339  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:25.339  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.339  6726  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:25.339  6726  6726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:25.339  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.339  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:25.339  3153  3248 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-01 10:59:25.339  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:25.339  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:25.339  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.339  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
,09-01 10:59:25.339  6726  6780 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-01 10:59:25.339  3153  3248 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:25.339  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:25.339  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:25.339  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:25.339  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.339  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.339  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.339  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.339  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.339  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.339  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:25.339  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.339  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.339  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.339  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:25.339  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:25.339  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:25.339  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:25.339  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
,09-01 10:59:25.339  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 10:59:25.339  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:25.339  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-01 10:59:25.339  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:25.339  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.339  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.339  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:25.339  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.339  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.339  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
,09-01 10:59:25.339  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:25.339  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.339  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.339  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:25.339  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.339  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:25.339  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:25.339  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.339  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.349  6726  6780 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-01 10:59:25.349  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:25.349  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:25.349  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 10:59:25.349  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.349  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.349  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.349  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.349  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop,
09-01 10:59:25.349  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.349  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.349  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:25.349  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.349  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
,09-01 10:59:25.349  6726  6780 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-01 10:59:25.349  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:25.349  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:25.349  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-01 10:59:25.349  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.349  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.349  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
,09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.349  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.349  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:25.349  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.349  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:25.349  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.349  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:25.349  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 10:59:25.349  6726  6780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 10:59:25.349  6726  6780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 10:59:25.349  6726  6780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 10:59:25.349  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:25.349  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,09-01 10:59:25.349  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.349  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.349  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:25.349  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.349  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.349  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:25.349  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:25.349  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.349  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.349  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:25.349  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.349  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.349  6726  6780 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 10:59:25.349  6726  6780 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-01 10:59:25.349  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-01 10:59:25.359  6726  6780 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 10:59:25.359  6726  6780 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710],
,09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 10:59:25.359  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 10:59:25.359  6726  6780 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-01 10:59:25.359  6726  6780 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 10:59:25.359  6726  6780 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-01 10:59:25.359  6726  6780 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 10:59:25.359  6726  6780 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 10:59:25.359  6726  6780 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-01 10:59:25.359  6726  6780 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 10:59:25.359  6726  6780 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 10:59:25.359  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-01 10:59:25.359  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-01 10:59:25.359  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-01 10:59:25.359  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-01 10:59:25.359  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-01 10:59:25.359  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-01 10:59:25.359  6726  6780 I io.jxcore.node.ConnectionHelper: connect: Connection proces,s successfully started (peer ID: 00:11:22:33:44:55)
09-01 10:59:25.359  6726  6780 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 10:59:25.359  6726  6780 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-01 10:59:25.359  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:25.359  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:25.359  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:25.369  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.369  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.369  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.369  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-01 10:59:25.369  6726  6860 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1295)
09-01 10:59:25.369  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.369  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.369  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.369  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:25.369  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.369  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.369  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.369  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:25.369  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:25.369  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:25.369  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.369  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
,09-01 10:59:25.369  6726  6780 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-01 10:59:25.369  6726  6861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1295
,09-01 10:59:25.369  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:25.369  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:25.369  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:25.369  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.369  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.369  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.369  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.369  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.369  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.369  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:25.369  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.369  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.369  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.369  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:25.369  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:25.369  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:25.369  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.369  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
,09-01 10:59:25.369  6726  6780 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-01 10:59:25.369  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:25.369  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:25.369  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:25.369  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.369  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.369  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.369  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.369  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.379  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.379  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:25.379  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.379  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.379  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.379  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:25.379  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:25.379  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:25.379  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.379  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
,09-01 10:59:25.379  6726  6780 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-01 10:59:25.379  6726  6780 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-01 10:59:25.379  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-01 10:59:25.379  6726  6780 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-01 10:59:25.379  6726  6780 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 10:59:25.379  6726  6780 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-01 10:59:25.379  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 10:59:25.379  6726  6780 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-01 10:59:25.379  6726  6780 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-01 10:59:25.379  6726  6780 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 10:59:25.379  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 10:59:25.379  6726  6780 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-01 10:59:25.379  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:25.379  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-01 10:59:25.379  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:25.379  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.379  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.379  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.379  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
,09-01 10:59:25.379  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.379  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.379  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:25.379  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.379  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.379  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.379  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-01 10:59:25.379  6726  6860 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-01 10:59:25.379  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:25.379  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:25.379  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.379  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.379  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.379  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.379  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.379  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.379  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.379  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list,
09-01 10:59:25.379  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:25.379  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.379  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.379  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.379  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.379  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.379  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.379  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:25.379  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.379  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:25.379  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:25.379  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:25.379  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.379  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:25.379  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.379  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.379  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.379  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.379  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:25.379  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.379  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.379  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.379  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.379  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:25.379  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:25.379  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.379  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
,09-01 10:59:25.389  6726  6780 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-01 10:59:25.389  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:25.389  6726  6860 D BluetoothSocket: connect(): myUserId = 0
09-01 10:59:25.389  6726  6860 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 10:59:25.389  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-01 10:59:25.389  6726  6780 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-01 10:59:25.389  6726  6780 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-01 10:59:25.389  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-01 10:59:25.389  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 10:59:25.389  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.389  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-01 10:59:25.389  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-01 10:59:25.389  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-01 10:59:25.389  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.389  6726  6780 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-01 10:59:25.389  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.389  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.389  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-01 10:59:25.389  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 10:59:25.389  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:25.389  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.389  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.389  6726  6726 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-01 10:59:25.389  6726  6726 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-01 10:59:25.389  3153  3323 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:25.389  6726  6860 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
09-01 10:59:25.389  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:25.389  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.389  6726  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:25.389  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:25.389  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:25.389  6726  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:25.389  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:25.389  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.389  6726  6726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:25.389  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.389  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.389  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.389  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.389  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.389  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:25.389  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.389  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.389  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.389  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:25.399  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:25.399  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:25.399  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.399  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.399  6726  6862 D BluetoothSocket: bindListen(): myUserId = 0
09-01 10:59:25.399  6726  6862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 10:59:25.399  6726  6780 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-01 10:59:25.399  6726  6780 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 10:59:25.399  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 10:59:25.399  6726  6780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 10:59:25.399  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:25.399  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:25.399  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:25.399  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.399  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.399  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.399  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.399  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.399  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.399  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:25.399  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.399  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:25.399  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.399  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.399  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:25.399  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:25.399  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.399  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
,09-01 10:59:25.399  6726  6862 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
09-01 10:59:25.399  6726  6862 D BluetoothSocket: bindListen(), new LocalSocket 
,09-01 10:59:25.399  6726  6862 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 10:59:25.399  6726  6862 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@13efbe94
09-01 10:59:25.399  6726  6862 D BluetoothSocket: channel: 6
09-01 10:59:25.399  6726  6862 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@39d6d3d, channel: 6, state: LISTENING
09-01 10:59:25.399  6726  6862 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@39d6d3d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@13efbe94, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3b7e4932mSocket: android.net.LocalSocket@1dbe9683 impl:android.net.LocalSocketImpl@28543000 fd:FileDescriptor[109]
09-01 10:59:25.399  6726  6862 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1dbe9683 impl:android.net.LocalSocketImpl@28543000 fd:FileDescriptor[109]
09-01 10:59:25.399  6726  6862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-01 10:59:25.399  6726  6862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-01 10:59:25.399  6726  6862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-01 10:59:25.399  6726  6726 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-01 10:59:25.399  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:25.399  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:25.399  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:25.399  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.399  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.399  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.399  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.399  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.399  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.399  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:25.399  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.399  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.399  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.399  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:25.409  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:25.409  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:25.409  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.409  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.409  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:25.409  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:25.409  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:25.409  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:25.409  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:25.409  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.409  6726  6780 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21c436cd not in the list
09-01 10:59:25.409  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.409  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.409  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:25.409  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.409  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:25.409  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:25.409  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:25.409  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:25.409  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:25.409  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:25.409  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18cbfb82 not in the list
09-01 10:59:25.409  6726  6780 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-01 10:59:25.409  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 10:59:25.409  6726  6780 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-01 10:59:25.409  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 10:59:25.409  6726  6780 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-01 10:59:25.409  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 10:59:25.409  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 10:59:25.409  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-01 10:59:25.409  6726  6780 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-01 10:59:25.409  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 10:59:25.409  6726  6780 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-01 10:59:25.409  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 10:59:25.409  6726  6780 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-01 10:59:25.409  6726  6780 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-01 10:59:25.409  6726  6780 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-01 10:59:25.409  6726  6780 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-01 10:59:25.409  6726  6780 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-01 10:59:25.409  6726  6780 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-01 10:59:25.409  6726  6780 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-01 10:59:25.409  6726  6780 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-01 10:59:25.409  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:25.409  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3278a039 added. We now have 2 listener(s)
09-01 10:59:25.409  6726  6780 D org.thaliproject,.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:25.409  6726  6780 D BluetoothAdapter: enable()
,09-01 10:59:25.419  6726  6780 D BluetoothAdapter: enable(): BT is already enabled..!
,09-01 10:59:25.419  1015  1472 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-01 10:59:25.419  1015  1472 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-01 10:59:25.419  1015  1472 D SecContentProvider2: mCursor = null
,09-01 10:59:25.419  1015  1472 D WifiService: setWifiEnabled: true pid=6726, uid=10171
,09-01 10:59:25.419  1015  1472 W ActivityManager: Permission Denial: getCurrentUser() from pid=6726, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-01 10:59:25.429  1015  1472 W WifiService: Failed getting userId using ActivityManagerNative
09-01 10:59:25.429  1015  1472 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6726, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-01 10:59:25.429  1015  1472 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-01 10:59:25.429  1015  1472 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-01 10:59:25.429  1015  1472 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-01 10:59:25.429  1015  1472 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-01 10:59:25.429  1015  1472 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-01 10:59:25.429  1015  1472 D SettingsProvider: name = wifi_on
,09-01 10:59:25.429  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:25.429  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2343c67e added. We now have 3 listener(s)
09-01 10:59:25.429  6726  6780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:25.429  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 10:59:25.429  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2dca17df added. We now have 4 listener(s)
09-01 10:59:25.429  6726  6780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:25.429  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:25.429  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27cc4c2c added. We now have 5 listener(s)
09-01 10:59:25.429  6726  6780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:25.439  1015  1322 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-01 10:59:25.439  1015  1322 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-01 10:59:25.439  1015  1322 D SecContentProvider2: mCursor = null
,09-01 10:59:25.439  1015  1322 D WifiService: setWifiEnabled: false pid=6726, uid=10171
,09-01 10:59:25.439  1015  1322 D SettingsProvider: name = wifi_on
,09-01 10:59:25.439  1015  1124 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-01 10:59:25.449  6726  6780 D BluetoothAdapter: disable()
,09-01 10:59:25.449  1368  1368 I wpa_supplicant: reset timer : RESET_TIMER 0,
09-01 10:59:25.449  1368  1368 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-01 10:59:25.449  1368  1368 I wpa_supplicant: P2P: Current p2p state = IDLE
09-01 10:59:25.449  1368  1368 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-01 10:59:25.449  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 10:59:25.459  1015  1462 D SettingsProvider: name = bluetooth_on,
,09-01 10:59:25.459  3153  3244 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-01 10:59:25.459  3153  3244 D BluetoothAdapterProperties: Setting state to 13
,09-01 10:59:25.459  3153  3244 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-01 10:59:25.459  3153  3244 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-01 10:59:25.459  3153  3244 D BluetoothAdapterService: updateAdapterState state is 13
,09-01 10:59:25.459  1015  1472 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:25.469  1015  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-01 10:59:25.469  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:25.469  1015  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:25.469  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:25.469  3153  3244 D BluetoothAdapterService: Autoconnection is available 
09-01 10:59:25.469  3153  3244 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-01 10:59:25.469  3153  3244 D BluetoothAdapterService: terminating service from this receiver
,09-01 10:59:25.469  3153  3153 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-01 10:59:25.469  1015  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-01 10:59:25.469  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:25.469  1015  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:25.469  3153  3153 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1c050530, channel: 19, state: LISTENING
09-01 10:59:25.469  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:25.469  3153  3153 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1c050530, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2067eb18, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@28d805a9mSocket: android.net.LocalSocket@3f6a172e impl:android.net.LocalSocketImpl@2ed012cf fd:FileDescriptor[74]
09-01 10:59:25.469  3153  3153 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3f6a172e impl:android.net.LocalSocketImpl@2ed012cf fd:FileDescriptor[74]
,09-01 10:59:25.469  3153  3244 D BluetoothAdapterProperties: onBluetoothDisable()
09-01 10:59:25.469  3153  3244 D BluetoothAdapterProperties: mDiscovering is false
,09-01 10:59:25.469  1015  1322 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-01 10:59:25.469  3153  3244 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-01 10:59:25.469  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:25.479  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:25.479  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,09-01 10:59:25.479  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:25.479  6726  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:25.479  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:25.479  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:25.479  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:25.479  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:25.479  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:25.479  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:25.479  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:25.479  3153  3248 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-01 10:59:25.479  3153  3248 D BluetoothAdapterProperties: Scan Mode:20
,09-01 10:59:25.479  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,09-01 10:59:25.489  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:25.489  6726  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:25.489  6726  6780 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 10:59:25.489  1015  1124 E WifiNative-wlan0: do suspend true
,09-01 10:59:25.489  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-01 10:59:25.489  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:25.489  1176  1176 D BluetoothTile:  getBluetoothState : 13
,09-01 10:59:25.489  1176  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:25.489  1874  1874 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
09-01 10:59:25.489  1176  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:25.499  1015  1319 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 10:59:25.499  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:25.499  1176  1729 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-01 10:59:25.499  1015  1495 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-01 10:59:25.499  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-01 10:59:25.499  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:25.499  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:25.499  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:25.499  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:25.499  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:25.499  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:25.499  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:25.499  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:25.499  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:25.499  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:25.499  6726  6726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:25.509  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:25.509  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:25.509  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 10:59:25.509  1015  1467 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:25.509  3153  3244 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-01 10:59:25.509  3153  3244 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-01 10:59:25.509  3153  3244 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-01 10:59:25.519  3153  3244 E bt-btif : cmd socket is not created
09-01 10:59:25.519  3153  5221 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-01 10:59:25.519  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-01 10:59:25.519  3153  3269 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-01 10:59:25.519  3153  3269 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-01 10:59:25.519  6726  6860 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1851cc8a, channel: -1, state: INIT
09-01 10:59:25.519  6726  6860 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1851cc8a, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e252fb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@5c7ff18mSocket: android.net.LocalSocket@a711d71 impl:android.net.LocalSocketImpl@1f882756 fd:FileDescriptor[107]
09-01 10:59:25.519  6726  6860 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@a711d71 impl:android.net.LocalSocketImpl@1f882756 fd:FileDescriptor[107]
,09-01 10:59:25.519  6726  6860 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1295)
,09-01 10:59:25.519  3153  3244 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-01 10:59:25.519  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:25.529  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:25.529  1015  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:25.529  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-01 10:59:25.529  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:25.529  3153  3269 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 10:59:25.529  3153  3269 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 10:59:25.529  3153  3269 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-01 10:59:25.529  1015  1322 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-01 10:59:25.529  1015  1322 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0,
,09-01 10:59:25.529  1015  1322 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:25.529  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:25.529  1015  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:25.529  1015  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-01 10:59:25.539  1300  1300 D BluetoothPbap: Proxy object disconnected
09-01 10:59:25.539  1300  1300 D PbapServerProfile: Bluetooth service disconnected
,09-01 10:59:25.539  1300  1300 D DockEventReceiver: finishStartingService: stopping service
,09-01 10:59:25.549  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 10:59:25.549  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:25.549  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-01 10:59:25.549  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-01 10:59:25.549  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:25.549  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:25.549  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:25.549  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:25.569  6869  6869 E Zygote  : MountEmulatedStorage(),
09-01 10:59:25.569  6869  6869 E Zygote  : v2
09-01 10:59:25.569  6869  6869 I libpersona: KNOX_SDCARD checking this for 10055
09-01 10:59:25.569  6869  6869 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:25.569  1015  1028 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6869 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
09-01 10:59:25.569  6869  6869 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 10:59:25.569  3153  3153 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2f6d445c, channel: 5, state: LISTENING
09-01 10:59:25.569  3153  3153 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2f6d445c, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22709971, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37825365mSocket: android.net.LocalSocket@3d04783a impl:android.net.LocalSocketImpl@e650ceb fd:FileDescriptor[76]
09-01 10:59:25.569  3153  3153 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3d04783a impl:android.net.LocalSocketImpl@e650ceb fd:FileDescriptor[76]
,09-01 10:59:25.569  6869  6869 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:25.569  3153  3153 I BtOppRfcommListener: stopping Accept Thread
09-01 10:59:25.569  3153  3153 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@13b84a48, channel: 12, state: LISTENING
09-01 10:59:25.569  3153  3153 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@13b84a48, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@5e5c273, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@7c9c0e1mSocket: android.net.LocalSocket@18b1de06 impl:android.net.LocalSocketImpl@34058cc7 fd:FileDescriptor[80]
09-01 10:59:25.569  3153  3153 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@18b1de06 impl:android.net.LocalSocketImpl@34058cc7 fd:FileDescriptor[80]
09-01 10:59:25.569  6869  6869 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:25.579  3153  5221 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-01 10:59:25.589  3153  3153 V BluetoothOppManager: cleanUp...
,09-01 10:59:25.589   307   307 I art     : Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 24.981ms
,09-01 10:59:25.609  6869  6869 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 10:59:25.609  6869  6869 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:25.609   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.812ms,
,09-01 10:59:25.629   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 16.631ms
,09-01 10:59:25.649  6869  6869 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-01 10:59:25.679  6869  6869 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-01 10:59:25.679  6869  6869 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() ,
09-01 10:59:25.679  6869  6869 D UserAnalysis: Create SecureDbHelper
,09-01 10:59:25.689  6869  6869 D IntelligenceServiceApplication: onCreate(),
,09-01 10:59:25.699  1015  1322 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-01 10:59:25.699  1015  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:25.699  1015  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:25.699  1015  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:25.699  6869  6869 D IntelligenceServiceApplication: no applications having user consent for prediction
09-01 10:59:25.699  1015  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:25.709  6884  6884 E Zygote  : MountEmulatedStorage()
,09-01 10:59:25.709  6884  6884 E Zygote  : v2
09-01 10:59:25.709  6884  6884 I libpersona: KNOX_SDCARD checking this for 10105
09-01 10:59:25.709  6884  6884 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:25.719  1015  1322 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6884 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-01 10:59:25.719  6884  6884 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-01 10:59:25.719  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0,
09-01 10:59:25.719  3153  3269 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-01 10:59:25.719  3153  3269 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 10:59:25.719  3153  3269 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 10:59:25.719  3153  3269 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 10:59:25.719  3153  3269 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
09-01 10:59:25.719  3153  3269 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 10:59:25.719  3153  3269 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 10:59:25.719  3153  3269 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 10:59:25.719  3153  3269 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 10:59:25.719  3153  3269 W bt-btif : ag scb idx 1 not allocated,
09-01 10:59:25.719  3153  3269 W bt-btif : ag scb idx 2 not allocated
09-01 10:59:25.719  3153  3269 E bt-btif : BTA AG is already disabled, ignoring ...
09-01 10:59:25.719  3153  3308 I bt_userial_mct: exiting userial_read_thread
09-01 10:59:25.719  3153  3308 D bt_userial_mct: Leaving userial_evt_read_thread()
09-01 10:59:25.719  6869  6869 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.,
09-01 10:59:25.719  3153  3248 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-01 10:59:25.719  3153  3271 I bt_vendor: hw_epilog_process
09-01 10:59:25.719  3153  3248 D bt_userial_mct: userial_close,
09-01 10:59:25.719  3153  3248 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-01 10:59:25.719  6884  6884 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 10:59:25.719  6884  6884 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-01 10:59:25.729  6869  6869 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-01 10:59:25.739  6884  6884 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:25.739  6884  6884 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:25.789  1015  1481 I art     : Explicit concurrent mark sweep GC freed 35543(1916KB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 24MB/36MB, paused 2.685ms total 161.428ms
,09-01 10:59:25.799  1015  1319 I ActivityManager: Killing 6426:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-01 10:59:25.819  1015  1093 V AlarmManager: waitForAlarm result :4
,09-01 10:59:25.849   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-01 10:59:25.849   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:25.849  6884  6907 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-01 10:59:25.859   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-01 10:59:25.859   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:25.859  6884  6907 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-01 10:59:25.889  6726  6726 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 10:59:25.959  3153  3248 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-01 10:59:25.959  3153  3248 I bt_vendor: bluetooth satus is on
09-01 10:59:25.959  3153  3248 I bt_vendor: bt-vendor : resetting BT status
09-01 10:59:25.959  3153  3248 I bt_vendor: Starting hciattach daemon
09-01 10:59:25.959  3153  3248 I bt_vendor: try to set false
,09-01 10:59:25.959  3153  3248 I bt_vendor: Starting hciattach daemon
,09-01 10:59:25.959  3153  3248 I bt_vendor: try to set false
,09-01 10:59:25.959  3153  3248 I bt_vendor: cleanup
,09-01 10:59:25.959  3153  3269 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-01 10:59:25.959  3153  3248 I GKI_LINUX: GKI_exit_task 0 done
,09-01 10:59:25.959  3153  3248 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-01 10:59:25.959  3153  3244 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-01 10:59:25.959  3153  3244 D BtConfig.SecureMode: isSecureModeOn:false
09-01 10:59:25.959  3153  3244 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-01 10:59:25.959  3153  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,09-01 10:59:25.959  3153  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-01 10:59:25.969  3153  3244 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-01 10:59:25.969  1015  1472 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:25.969  1015  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-01 10:59:25.969  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:25.969  1015  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:25.969  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:25.969  3153  3153 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 10:59:25.969  3153  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-01 10:59:25.969  3153  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-01 10:59:25.969  3153  3244 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-01 10:59:25.969  3153  3153 D BtGatt.GattService: Received stop request...Stopping profile...
09-01 10:59:25.969  3153  3153 D BtGatt.GattService: stop()
09-01 10:59:25.969  3153  3153 D BtGatt.AdvertiseManager: advertise clients cleared
,09-01 10:59:25.969  1015  1462 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:25.969  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-01 10:59:25.969  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:25.969  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:25.969  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:25.969  3153  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-01 10:59:25.969  3153  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-01 10:59:25.979  3153  3153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
09-01 10:59:25.979  3153  3244 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-01 10:59:25.979  1015  1473 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:25.979  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 10:59:25.979  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:25.979  1015  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:25.979  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:25.979  3153  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-01 10:59:25.979  3153  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-01 10:59:25.979  3153  3244 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-01 10:59:25.979  1015  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:25.979  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-01 10:59:25.979  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:25.979  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:25.979  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:25.979  3153  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-01 10:59:25.979  3153  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-01 10:59:25.979  3153  3244 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-01 10:59:25.979  1015  1467 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:25.979  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-01 10:59:25.979  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:25.979  1015  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:25.989  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:25.989  3153  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-01 10:59:25.989  3153  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-01 10:59:25.989  3153  3244 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-01 10:59:25.989  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:25.989  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 10:59:25.989  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:25.989  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:25.989  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:25.989  3153  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-01 10:59:25.989  3153  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-01 10:59:25.989  3153  3244 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-01 10:59:25.989  1015  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:25.989  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-01 10:59:25.989  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:25.989  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:25.989  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:25.989  3153  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-01 10:59:25.999  3153  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-01 10:59:25.999  3153  3244 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-01 10:59:25.999  1015  1472 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:25.999  1015  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-01 10:59:25.999  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:25.999  1015  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:25.999  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:25.999  3153  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:25.999  3153  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-01 10:59:25.999  3153  3244 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:25.999  3153  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:25.999  3153  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-01 10:59:25.999  3153  3244 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:25.999  3153  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-01 10:59:25.999  3153  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-01 10:59:25.999  3153  3244 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-01 10:59:25.999  3153  3244 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-01 10:59:25.999  3153  3244 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-01 10:59:25.999  3153  3244 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-01 10:59:25.999  3153  3244 D BluetoothAdapterState: Stopping profile services that were post enabled
09-01 10:59:25.999  3153  3153 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-01 10:59:25.999  3153  3153 D HeadsetService: Received stop request...Stopping profile...
,09-01 10:59:25.999  3153  3153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:26.009  1300  1300 D HeadsetProfile: Bluetooth service disconnected
,09-01 10:59:26.009  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-01 10:59:26.009  3153  3153 D A2dpService: Received stop request...Stopping profile...
09-01 10:59:26.009  3153  3258 D A2dpStateMachine: Exit Disconnected: -1
,09-01 10:59:26.019  3153  3153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:26.019  1015  1015 D BluetoothA2dp: Proxy object disconnected
,09-01 10:59:26.019  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-01 10:59:26.019  3153  3153 D HidService: Received stop request...Stopping profile...
09-01 10:59:26.019  3153  3153 D HidService: Stopping Bluetooth HidService
09-01 10:59:26.019  3153  3153 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 10:59:26.019  3153  3153 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-01 10:59:26.019  3153  3153 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 10:59:26.019  1300  1300 D BluetoothA2dp: Proxy object disconnected
09-01 10:59:26.019  1300  1300 D A2dpProfile: Bluetooth service disconnected
09-01 10:59:26.019  3153  3153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:26.019  3153  3153 D HealthService: Received stop request...Stopping profile...
,09-01 10:59:26.019  3153  3153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:26.019  1300  1300 D BluetoothInputDevice: Proxy object disconnected
09-01 10:59:26.019  1300  1300 D HidProfile: Bluetooth service disconnected
,09-01 10:59:26.019  3153  3153 D PanService: Received stop request...Stopping profile...
,09-01 10:59:26.019  3153  3153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:26.029  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-01 10:59:26.029  3153  3153 D BluetoothMapService: Received stop request...Stopping profile...
,09-01 10:59:26.029  1300  1300 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 10:59:26.029  1300  1300 D PanProfile: Bluetooth service disconnected
,09-01 10:59:26.029  3153  3153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:26.029  3153  3153 D SapService: Received stop request...Stopping profile...
,09-01 10:59:26.029  3153  3153 D SapService: Stopping Bluetooth SapService
,09-01 10:59:26.029  3153  3153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:26.029  1300  1300 D BluetoothMap: Proxy object disconnected
09-01 10:59:26.029  1300  1300 D MapProfile: Bluetooth service disconnected
,09-01 10:59:26.039  3153  3153 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,09-01 10:59:26.039  3153  3153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-01 10:59:26.039  3153  3153 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-01 10:59:26.039  1300  1300 D Bluetoothsap: BluetoothSAP Proxy object disconnected,
09-01 10:59:26.039   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:26.039  3153  3153 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-01 10:59:26.039  3153  3153 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 10:59:26.039  1300  1300 D SapProfile: Bluetooth service disconnected
,09-01 10:59:26.039  3153  3153 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-01 10:59:26.039  3153  3153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-01 10:59:26.039  3153  3153 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-01 10:59:26.039  3153  3259 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-01 10:59:26.039  3153  3153 I GKI_LINUX: GKI_exit_task 2 done
09-01 10:59:26.039  3153  3153 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-01 10:59:26.039  3153  3153 D BluetoothA2dp: Proxy object disconnected
09-01 10:59:26.049  3153  3153 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-01 10:59:26.049  3153  3153 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-01 10:59:26.049  3153  3153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:26.049  3153  3153 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-01 10:59:26.049  3153  3153 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-01 10:59:26.049  3153  3153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:26.049  3153  3153 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:26.049  3153  3153 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-01 10:59:26.049  3153  3153 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 10:59:26.049  3153  3153 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-01 10:59:26.049  3153  3153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:26.049  3153  3153 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:26.049  3153  3153 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 10:59:26.049  3153  3153 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-01 10:59:26.049  3153  3153 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-01 10:59:26.049  3153  3153 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-01 10:59:26.049  3153  3153 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-01 10:59:26.049  3153  3153 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-01 10:59:26.049  3153  3153 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-01 10:59:26.049  3153  3153 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-01 10:59:26.049  3153  3244 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-01 10:59:26.049  3153  3244 D BluetoothAdapterProperties: Setting state to 10
09-01 10:59:26.049  3153  3244 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-01 10:59:26.049  3153  3244 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 10:59:26.049  3153  3244 D BluetoothAdapterService: updateAdapterState state is 10
,09-01 10:59:26.049  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:26.049  6884  6884 D StrictMode: StrictMode policy violation; ~duration=180 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.io.File.exists(File.java:363)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:26.049  6884  6884 D StrictMode: StrictMode policy violation; ~duration=179 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.shared.i,.h.a(PG:252)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:26.049  6884  6884 D StrictMode: StrictMode policy violation; ~duration=179 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread$H.handl,eMessage(ActivityThread.java:1543)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:26.049  6884  6884 D StrictMode: StrictMode policy violation; ~duration=177 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.q.e.b(PG:170)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:26.049  6884  6884 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.q.k.d(PG:583)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.q.e.b(PG:170)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:26.059  1015  1028 I ActivityManager: Killing 6316:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
09-01 10:59:26.049  6884  6884 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.io.File.exists(File.java:363)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:26.049  6884  6884 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.io.File.exists(File.java:363)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:26.049  6884  6884 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:26.049  6884  6884 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:26.059  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:26.059  3153  3244 D BluetoothAdapterService: Autoconnection is available 
09-01 10:59:26.059  3153  3244 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-01 10:59:26.059  3153  3244 I BluetoothAdapterState: Entering OffState
09-01 10:59:26.059  1300  1313 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 10:59:26.059  6726  6736 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:26.059  6726  6736 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:26.059  6726  6736 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-01 10:59:26.059  6726  6736 D BluetoothLeAdvertiser: Exit stop advertising
09-01 10:59:26.059  6726  6736 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-01 10:59:26.059  6726  6736 D BluetoothLeScanner: Exiting stopAllScan
09-01 10:59:26.059  1937  1937 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-01 10:59:26.059  1439  6185 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:26.059  1439  6185 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:26.059  1176  1792 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:26.059  1176  1792 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:26.059  1300  1309 D Bluetoothsap: onBluetoothStateChange: up=false
09-01 10:59:26.059  1300  1309 D Bluetoothsap: Unbinding service...
09-01 10:59:26.069  1937  1937 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-01 10:59:26.069  3153  3161 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:26.069  3153  3161 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:26.079  1422  1445 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:26.079  1422  1445 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:26.079  1300  1309 D BluetoothMap: onBluetoothStateChange: up=false
09-01 10:59:26.079  1300  1313 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 10:59:26.079  1451  2463 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:26.079  1451  2463 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:26.079  1300  1309 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:26.079  1300  1309 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:26.079  3153  3163 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 10:59:26.079  1937  2164 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:26.079  1937  2164 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:26.079  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 10:59:26.079  1300  1309 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 10:59:26.079  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-01 10:59:26.089  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-01 10:59:26.089  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:26.089  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
09-01 10:59:26.089  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
09-01 10:59:26.099  3153  3248 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-01 10:59:26.099  3153  3153 I GKI_LINUX: GKI_exit_task 1 done
09-01 10:59:26.099  3153  3153 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-01 10:59:26.099  3153  3153 I BluetoothServiceJni: cleanupNative: return from cleanup
09-01 10:59:26.099  1176  1176 D BluetoothAdapter: 171507465: getState() :  mService = null. Returning STATE_OFF
09-01 10:59:26.099  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-01 10:59:26.099  1176  1729 D BluetoothAdapter: 171507465: getState() :  mService = null. Returning STATE_OFF
09-01 10:59:26.099  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:26.099  1176  1176 D BluetoothTile:  getBluetoothState : 10
09-01 10:59:26.099  1176  1729 D BluetoothAdapter: 171507465: getState() :  mService = null. Returning STATE_OFF
09-01 10:59:26.099  1176  1176 D BluetoothAdapter: 171507465: getState() :  mService = null. Returning STATE_OFF
09-01 10:59:26.099  1176  1176 D BluetoothAdapter: 171507465: getState() :  mService = null. Returning STATE_OFF
09-01 10:59:26.099  1015  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-01 10:59:26.099  1015  1467 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-01 10:59:26.099  1874  1874 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-01 10:59:26.099  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-01 10:59:26.099  3153  3153 I art     : System.exit called, status: 0
09-01 10:59:26.099  3153  3153 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-01 10:59:26.109  1937  2165 D BluetoothAdapter: 600275001: getState() :  mService = null. Returning STATE_OFF
09-01 10:59:26.109  1937  2165 D BluetoothAdapter: 600275001: getState() :  mService = null. Returning STATE_OFF
09-01 10:59:26.109  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:26.109  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:26.109  1015  1473 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:26.109  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-01 10:59:26.109  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:26.109  1015  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:26.109  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-01 10:59:26.109  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:26.119  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 10:59:26.119  1015  1462 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-01 10:59:26.119  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-01 10:59:26.119  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:26.119  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:26.119  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-01 10:59:26.129  6884  6911 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-01 10:59:26.129  1300  1300 D DockEventReceiver: finishStartingService: stopping service
,09-01 10:59:26.129  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 10:59:26.139  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:26.139  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-01 10:59:26.139  1015  1481 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-01 10:59:26.149  1015  1481 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-01 10:59:26.149  1015  1481 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
09-01 10:59:26.149  1015  1481 W BroadcastQueue: android.os.TransactionTooLargeException
09-01 10:59:26.149  1015  1481 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-01 10:59:26.149  1015  1481 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-01 10:59:26.149  1015  1481 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-01 10:59:26.149  1015  1481 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-01 10:59:26.149  1015  1481 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-01 10:59:26.149  1015  1481 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-01 10:59:26.149  1015  1481 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-01 10:59:26.149  1015  1481 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-01 10:59:26.149  1015  1481 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
09-01 10:59:26.149  1015  1481 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-01 10:59:26.149  1015  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:26.149  1015  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:26.149  1015  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:26.149  1015  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:26.169  6926  6926 E Zygote  : MountEmulatedStorage(),
09-01 10:59:26.169  6926  6926 I libpersona: KNOX_SDCARD checking this for 1002
09-01 10:59:26.169  6926  6926 E Zygote  : v2
09-01 10:59:26.169  6926  6926 I libpersona: KNOX_SDCARD not a persona
09-01 10:59:26.169  6926  6926 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:26.169  6926  6926 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 10:59:26.169  1015  1481 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6926 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-01 10:59:26.169  6926  6926 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-01 10:59:26.169  1015  1134 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:26.169  1015  1134 W ActivityManager: userId = 0, bbcId = -10000,
09-01 10:59:26.169  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:26.169  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-01 10:59:26.199  6926  6926 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:26.199  6926  6926 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:26.199  1368  1368 I wpa_supplicant: nl80211: Received scan results (6 BSSes),
09-01 10:59:26.199  1015  1123 D WifiP2pService: InactiveState{ what=147461 }
,09-01 10:59:26.209  1015  1123 D WifiP2pService: P2pEnabledState{ what=147461 }
,09-01 10:59:26.209  1015  1123 D WifiP2pService: DefaultState{ what=147461 }
,09-01 10:59:26.209  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
09-01 10:59:26.209   278  1014 D CommandListener: Clearing all IP addresses on wlan0
09-01 10:59:26.209  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-01 10:59:26.209  1937  3043 V NativeCrypto: Read error: ssl=0xb7e5c270: I/O error during system call, Connection timed out
,09-01 10:59:26.219  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:26.219  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-01 10:59:26.219  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.219  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.219  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.219  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.219  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-01 10:59:26.219  1015  1126 E ConnectivityService: updateNetworkInfo()
09-01 10:59:26.219  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 10:59:26.219  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
09-01 10:59:26.219  1937  3043 V NativeCrypto: SSL shutdown failed: ssl=0xb7e5c270: I/O error during system call, Broken pipe
09-01 10:59:26.219  1937  6850 I qtaguid : Untagging socket 69
09-01 10:59:26.219  1937  3043 E GCM     : Wifi connection closed with errorCode 20
,09-01 10:59:26.219  6926  6926 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.,
09-01 10:59:26.219  6926  6926 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-01 10:59:26.219  1937  2170 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-01 10:59:26.229  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-01 10:59:26.229  1015  1462 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,09-01 10:59:26.239  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-01 10:59:26.239  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:26.239  1015  1123 D WifiP2pService: InactiveState{ what=131204 }
09-01 10:59:26.239  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.239  1015  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
09-01 10:59:26.239  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.239  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.239  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-01 10:59:26.239  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
09-01 10:59:26.239  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:26.239  1015  1015 D RttService: SCAN_AVAILABLE : 1
09-01 10:59:26.239  1015  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 10:59:26.239  1015  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-01 10:59:26.259  1015  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-26ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:26.259  1015  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-26ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:26.259  1015  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-01 10:59:26.259  1015  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:26.259  1015  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,09-01 10:59:26.259  1015  1735 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
09-01 10:59:26.259  1015  1735 I qtaguid : Tagging socket 373 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
09-01 10:59:26.259  1015  1735 I qtaguid : Untagging socket 373,
09-01 10:59:26.259  1015  1735 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:26.279  6926  6926 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-01 10:59:26.279  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-01 10:59:26.279  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-01 10:59:26.279  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
,09-01 10:59:26.289  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-01 10:59:26.289  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-01 10:59:26.289  1015  1123 D WifiP2pService: P2pDisablingState
,09-01 10:59:26.289  1015  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
09-01 10:59:26.289  1015  1123 D WifiP2pService: p2p socket connection lost
09-01 10:59:26.289  1015  1123 D WifiP2pService: P2pDisabledState
,09-01 10:59:26.299  1015  1124 E WifiNative-wlan0: do suspend true,
,09-01 10:59:26.299  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-01 10:59:26.299  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-01 10:59:26.299  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-01 10:59:26.299  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 10:59:26.299  1015  1045 D WifiDisplayController: disconnect
,09-01 10:59:26.299  1015  1045 D WifiDisplayController: updateConnection
09-01 10:59:26.299  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 10:59:26.299  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-01 10:59:26.299  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-01 10:59:26.299  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-01 10:59:26.299  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-01 10:59:26.299  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-01 10:59:26.299  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-01 10:59:26.299  1015  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-01 10:59:26.299  1015  1123 D WifiP2pService: DefaultState{ what=143375 }
,09-01 10:59:26.299  1015  1462 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
09-01 10:59:26.299  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-01 10:59:26.309  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:26.309  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:26.309  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:26.309  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.309  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.309  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:26.319  6926  6926 D BtSettings.ProfileConfig: Adding GattService,
09-01 10:59:26.319  6926  6926 D BtSettings.ProfileConfig: Adding HeadsetService
09-01 10:59:26.319  6926  6926 D BtSettings.ProfileConfig: Adding A2dpService,
09-01 10:59:26.319  6926  6926 D BtSettings.ProfileConfig: Adding HidService
09-01 10:59:26.319  6926  6926 D BtSettings.ProfileConfig: Adding HealthService
09-01 10:59:26.319  6926  6926 D BtSettings.ProfileConfig: Adding PanService
,09-01 10:59:26.319  6926  6926 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-01 10:59:26.319  6926  6926 D BtSettings.ProfileConfig: Adding SapService
09-01 10:59:26.319  6926  6926 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-01 10:59:26.319  6926  6926 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-01 10:59:26.319  6926  6926 D BtSettings.ProfileConfig: Adding SapClientService
09-01 10:59:26.319  6926  6926 D BtSettings.ProfileConfig: Adding HidDevService
09-01 10:59:26.319  6926  6926 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-01 10:59:26.319  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-01 10:59:26.319  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:26.319  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:26.319  1015  1028 D SettingsProvider: selectionArgs: false
09-01 10:59:26.319  1015  1028 D SettingsProvider: selectionArgs: 1002
09-01 10:59:26.319  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:26.319  1015  1028 D SettingsProvider: ret = -1,
,09-01 10:59:26.319  1015  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-01 10:59:26.319  1015  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:26.319  1015  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:26.319  1015  1495 D SettingsProvider: selectionArgs: false
09-01 10:59:26.319  1015  1495 D SettingsProvider: selectionArgs: 1002
09-01 10:59:26.319  1015  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:26.319  1015  1495 D SettingsProvider: ret = -1
09-01 10:59:26.329  1015  1472 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-01 10:59:26.329  1015  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:26.329  1015  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:26.329  1015  1472 D SettingsProvider: selectionArgs: false
09-01 10:59:26.329  1015  1472 D SettingsProvider: selectionArgs: 1002
09-01 10:59:26.329  1015  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:26.329  1015  1472 D SettingsProvider: ret = -1
09-01 10:59:26.329  1015  1319 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-01 10:59:26.329  1015  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:26.329  1015  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:26.329  1015  1319 D SettingsProvider: selectionArgs: false
09-01 10:59:26.329  1015  1319 D SettingsProvider: selectionArgs: 1002
09-01 10:59:26.329  1015  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-01 10:59:26.329  1015  1319 D SettingsProvider: ret = -1
,09-01 10:59:26.329  1015  1134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,09-01 10:59:26.329  1015  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:26.329  1015  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:26.329  1015  1134 D SettingsProvider: selectionArgs: false
09-01 10:59:26.329  1015  1134 D SettingsProvider: selectionArgs: 1002
09-01 10:59:26.329  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
09-01 10:59:26.329  1015  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:26.329  1015  1134 D SettingsProvider: ret = -1
,09-01 10:59:26.329  1015  1322 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,09-01 10:59:26.329  1015  1322 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:26.339  1015  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-01 10:59:26.329  1015  1322 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-01 10:59:26.339  1015  1126 V NetworkStats: updateIfacesLocked()
09-01 10:59:26.329  1015  1322 D SettingsProvider: selectionArgs: false,
09-01 10:59:26.339  1015  1126 V NetworkStats: performPollLocked(flags=0x1),
09-01 10:59:26.329  1015  1322 D SettingsProvider: selectionArgs: 1002
09-01 10:59:26.329  1015  1322 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:26.329  1015  1322 D SettingsProvider: ret = -1
09-01 10:59:26.329  1015  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-01 10:59:26.329  1015  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:26.329  1015  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:26.329  1015  1481 D SettingsProvider: selectionArgs: false
09-01 10:59:26.329  1015  1481 D SettingsProvider: selectionArgs: 1002
09-01 10:59:26.329  1015  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:26.329  1015  1481 D SettingsProvider: ret = -1
09-01 10:59:26.329  1015  1467 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-01 10:59:26.329  1015  1467 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
09-01 10:59:26.329  1015  1467 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:26.339  1015  1126 V NetworkStats: performPollLocked() took 6ms
09-01 10:59:26.329  1015  1467 D SettingsProvider: selectionArgs: false
09-01 10:59:26.329  1015  1467 D SettingsProvider: selectionArgs: 1002
09-01 10:59:26.329  1015  1467 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:26.329  1015  1467 D SettingsProvider: ret = -1
,09-01 10:59:26.329  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:26.329  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:26.329  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:26.329  1015  1028 D SettingsProvider: selectionArgs: false
09-01 10:59:26.329  1015  1028 D SettingsProvider: selectionArgs: 1002
09-01 10:59:26.329  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:26.329  1015  1028 D SettingsProvider: ret = -1
09-01 10:59:26.339  1015  1472 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:26.339  1015  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:26.339  1015  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:26.339  1015  1472 D SettingsProvider: selectionArgs: false
09-01 10:59:26.339  1015  1472 D SettingsProvider: selectionArgs: 1002
09-01 10:59:26.339  1015  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:26.339  1015  1472 D SettingsProvider: ret = -1
09-01 10:59:26.339   278  1014 D CommandListener: Clearing all IP addresses on wlan0
,09-01 10:59:26.339  1015  1319 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-01 10:59:26.339   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-01 10:59:26.339  1015  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:26.339   278  1010 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-01 10:59:26.339  1015  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-01 10:59:26.339  1015  1319 D SettingsProvider: selectionArgs: false
09-01 10:59:26.339  1015  1319 D SettingsProvider: selectionArgs: 1002
09-01 10:59:26.339  1015  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:26.339  1015  1319 D SettingsProvider: ret = -1
09-01 10:59:26.339  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:26.339  1015  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-01 10:59:26.339  1015  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:26.339  1015  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:26.339  1015  1495 D SettingsProvider: selectionArgs: false
09-01 10:59:26.339  1015  1495 D SettingsProvider: selectionArgs: 1002
09-01 10:59:26.339  1015  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:26.339  1015  1495 D SettingsProvider: ret = -1
09-01 10:59:26.339  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:26.339  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 10:59:26.339  1015  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-01 10:59:26.339  1015  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-01 10:59:26.339  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:26.349  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-01 10:59:26.349  1368  1368 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-01 10:59:26.359  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:26.359  1015  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-01 10:59:26.359  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:26.359  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:26.359  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:26.359  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.359  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:26.359  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.359  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.359  1176  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-01 10:59:26.359  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-01 10:59:26.359  1015  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 10:59:26.359  4760  6790 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-01 10:59:26.359  1015  1126 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-01 10:59:26.359  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-01 10:59:26.359  1451  1451 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-01 10:59:26.359  1015  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-01 10:59:26.359  1451  1451 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 10:59:26.359  1015  1126 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,09-01 10:59:26.369  1937  1937 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-01 10:59:26.369  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-01 10:59:26.369  1015  1473 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:26.369  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-01 10:59:26.369  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:26.369  1015  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:26.369  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-01 10:59:26.369  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-01 10:59:26.369  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:26.369  1015  1124 D SecContentProvider2: mCursor = null
,09-01 10:59:26.379  1015  1126 D ConnectivityService: nai.networkMonitor.doQuit()
09-01 10:59:26.379  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 10:59:26.379  1015  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-01 10:59:26.379  1015  1126 E ConnectivityService: updateNetworkInfo()
09-01 10:59:26.379  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-01 10:59:26.379  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:26.379  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-01 10:59:26.379  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.379  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.379  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.379  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.379  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-01 10:59:26.389  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 10:59:26.389  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-01 10:59:26.389  1176  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-01 10:59:26.389  1937  6949 D EasyUnlockInitService: Handling intent for initializer IntentService.
09-01 10:59:26.389  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:26.389  1176  1176 D HotspotTile: onReceive : 0, 0
,09-01 10:59:26.389  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:26.389  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-01 10:59:26.389  1015  1129 D Tethering: MasterInitialState.processMessage what=3
09-01 10:59:26.389  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:26.389  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:26.389  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:26.389  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:26.389  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:26.389  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:26.389  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:26.389  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:26.389  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:26.389  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:26.389  6726  6726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:26.389  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:26.389  1015  1121 V NetworkStats: updateIfacesLocked()
09-01 10:59:26.389  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,09-01 10:59:26.399  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:26.399  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:26.399  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:26.399  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:26.399  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:26.399  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:26.399  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:26.399  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:26.399  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:26.399  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:26.399  6726  6726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
09-01 10:59:26.399  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:26.399  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-01 10:59:26.399  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
09-01 10:59:26.399  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-01 10:59:26.399  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-01 10:59:26.399  1176  1176 D StatusBar.NetworkController: updateDataNetType()
09-01 10:59:26.399  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-01 10:59:26.399  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-01 10:59:26.399  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:26.399  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:26.399  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-01 10:59:26.399  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:26.399  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:26.399  1015  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:26.399  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:26.399  1015  1121 V NetworkStats: performPollLocked() took 9ms
09-01 10:59:26.399  1015  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:26.399  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-01 10:59:26.399  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:26.399  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-01 10:59:26.399  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-01 10:59:26.409  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-01 10:59:26.409  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:26.409  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-01 10:59:26.409  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.409  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.409  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.409  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:26.419  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:26.419  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:26.419  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:26.419  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:26.429  1937  1937 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-01 10:59:26.429  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:26.429  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:26.439  1368  1368 I wpa_supplicant: Blacklist: Clear (all) 
09-01 10:59:26.439  1937  6949 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-01 10:59:26.449  1015  1473 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-01 10:59:26.449  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:26.449  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:26.449  1015  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:26.449  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 10:59:26.449  1627  1627 I Hs20UtilService: Starting #8
,09-01 10:59:26.459  1627  1701 I Hs20UtilService: Message received 5007
,09-01 10:59:26.459  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-01 10:59:26.459  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:26.459  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 10:59:26.459  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-01 10:59:26.459  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 10:59:26.459  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-01 10:59:26.459  1300  2241 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 10:59:26.469  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:26.469  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:26.469  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-01 10:59:26.469  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-01 10:59:26.469  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:26.469  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:26.469  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:26.469  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:26.489  6952  6952 E Zygote  : MountEmulatedStorage()
09-01 10:59:26.489  6952  6952 E Zygote  : v2
,09-01 10:59:26.489  6952  6952 I libpersona: KNOX_SDCARD checking this for 10102
09-01 10:59:26.489  6952  6952 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:26.489  6952  6952 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 10:59:26.489  1015  1027 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6952 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-01 10:59:26.489  6952  6952 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:26.489  6952  6952 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-01 10:59:26.509  1015  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-01 10:59:26.509  1015  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-01 10:59:26.509  1015  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-01 10:59:26.509  1015  1028 D BatteryService: stay LED for fully charged
09-01 10:59:26.509  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-01 10:59:26.509  1015  1015 I MotionRecognitionService: Plugged
09-01 10:59:26.509  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
09-01 10:59:26.509  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-01 10:59:26.509  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-01 10:59:26.509  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-01 10:59:26.509  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-01 10:59:26.519  1368  1368 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-01 10:59:26.519  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
09-01 10:59:26.519  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 10:59:26.519  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
09-01 10:59:26.519  6952  6952 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-01 10:59:26.519  6952  6952 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:26.539  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-01 10:59:26.539  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-01 10:59:26.539  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-01 10:59:26.539  1368  1368 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
09-01 10:59:26.539  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:26.539  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:26.539  1368  1368 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-01 10:59:26.539  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-01 10:59:26.539  1368  1368 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-01 10:59:26.539  1368  1368 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-01 10:59:26.539  1368  1368 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-01 10:59:26.539  1015  1129 D Tethering: InitialState.processMessage what=4
,09-01 10:59:26.549  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:26.549  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:26.549  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:26.549  1015  1129 E Tethering: No numeric data
,09-01 10:59:26.549  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-01 10:59:26.549  1015  1129 D Tethering: clearTetheredNotification()
,09-01 10:59:26.549  6952  6952 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-01 10:59:26.549  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 10:59:26.549  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:26.549  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:26.559  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-01 10:59:26.559  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:26.559  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:26.559  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 10:59:26.559  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 10:59:26.559  1176  1176 D HotspotTile: updateTetherState():false, false
,09-01 10:59:26.559  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:26.559  1015  1121 V NetworkStats: performPollLocked() took 6ms
,09-01 10:59:26.559  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:26.559  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:26.569  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:26.579  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-01 10:59:26.579  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:26.579  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-01 10:59:26.579  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:26.579  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-01 10:59:26.579  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:26.579  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-01 10:59:26.589  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:26.589  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-01 10:59:26.589  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:26.589  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-01 10:59:26.589  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:26.589  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-01 10:59:26.589  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:26.589  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-01 10:59:26.599  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:26.599  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-01 10:59:26.599   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7ea87c8
09-01 10:59:26.599   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,09-01 10:59:26.599   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
09-01 10:59:26.599   273   335 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1209366392)
09-01 10:59:26.599  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:26.609  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 10:59:26.609  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:26.609  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
,09-01 10:59:26.609  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-01 10:59:26.609  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
,09-01 10:59:26.609  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-01 10:59:26.609  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-01 10:59:26.609  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:26.609  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-01 10:59:26.609  1451  1451 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:26.619  1451  1451 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-01 10:59:26.649   273   335 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504,
09-01 10:59:26.649   273   335 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
09-01 10:59:26.649   273   335 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1209366392) wakelock released: 1, error no: 0
09-01 10:59:26.649   273   335 I rmt_storage: 
,09-01 10:59:26.649   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7ea87c8,
,09-01 10:59:26.679  1368  1368 I wpa_supplicant: Blacklist: Clear (all) 
,09-01 10:59:26.749  6952  6987 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-01 10:59:26.749  6952  6987 I Babel_SMS: MmsConfig.loadMmsSettings
,09-01 10:59:26.749  6952  6987 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-01 10:59:26.749  6952  6987 I Babel_SMS: MmsConfig.loadFromDatabase
,09-01 10:59:26.769  6952  6987 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-01 10:59:26.769  6952  6987 I Babel_SMS: MmsConfig.loadFromResources
,09-01 10:59:26.769  6952  6987 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-01 10:59:26.769  6952  6987 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-01 10:59:26.799  1368  1368 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-01 10:59:26.799  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-01 10:59:26.799  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-01 10:59:26.799  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:26.799  1015  1462 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
09-01 10:59:26.799  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:26.799  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
09-01 10:59:26.799  1015  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:26.799  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-01 10:59:26.819  6952  6952 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 10:59:26.829  6952  6952 I Babel_Crash: startup - clean
,09-01 10:59:26.859  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-01 10:59:26.859  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:26.859  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 10:59:26.859  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 10:59:26.859  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 10:59:26.859  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-01 10:59:26.859  1300  2241 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 10:59:26.859  1015  1472 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-01 10:59:26.859  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:26.859  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:26.859  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:26.859  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:26.879  6990  6990 E Zygote  : MountEmulatedStorage()
,09-01 10:59:26.879  6990  6990 E Zygote  : v2
09-01 10:59:26.879  6990  6990 I libpersona: KNOX_SDCARD checking this for 10064
09-01 10:59:26.879  6990  6990 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:26.879  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-01 10:59:26.879  6990  6990 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:26.879  1015  1472 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6990 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 10:59:26.879  6990  6990 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 10:59:26.879  6990  6990 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:26.879  6952  6952 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-01 10:59:26.889  1015  1015 I ApplicationPolicy: updateDataUsageMap
,09-01 10:59:26.889  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:26.899  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:26.899  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:26.899  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-01 10:59:26.899  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-01 10:59:26.909  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:26.909  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-01 10:59:26.909  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.909  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.909  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:26.909  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:26.909  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 10:59:26.909  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-01 10:59:26.909  1176  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-01 10:59:26.909  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:26.929  1176  1176 D HotspotTile: onReceive : 1, 0
,09-01 10:59:26.929  1937  2165 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 10:59:26.929  6990  6990 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:26.929  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:26.929  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:26.929  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:26.929  6952  6952 W AudioCapabilities: Unsupported mime audio/evrc
,09-01 10:59:26.929  6990  6990 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:26.939  6952  6952 W AudioCapabilities: Unsupported mime audio/qcelp
,09-01 10:59:26.949  6952  6952 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-01 10:59:26.949  6952  6952 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-01 10:59:26.949  6952  6952 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-01 10:59:26.949  6952  6952 W AudioCapabilities: Unsupported mime audio/x-ima
,09-01 10:59:26.959  6952  6952 W AudioCapabilities: Unsupported mime audio/qcelp
,09-01 10:59:26.959  6952  6952 W AudioCapabilities: Unsupported mime audio/evrc
,09-01 10:59:26.959  6990  6990 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-01 10:59:26.969  6952  6952 W VideoCapabilities: Unsupported mime video/wvc1
,09-01 10:59:26.969  6952  6952 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-01 10:59:26.969  6990  6990 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 10:59:26.979  6990  6990 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-01 10:59:26.979  6952  6952 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-01 10:59:26.979  6952  6952 W VideoCapabilities: Unsupported mime video/wvc1
,09-01 10:59:26.979  6952  6952 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-01 10:59:26.979  6952  6952 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-01 10:59:26.989  6952  6952 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-01 10:59:26.989  6952  6952 W VideoCapabilities: Unsupported mime video/mp43
,09-01 10:59:26.989  6952  6952 W VideoCapabilities: Unsupported mime video/sorenson
,09-01 10:59:26.989  6952  6952 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-01 10:59:27.009  6952  6952 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-01 10:59:27.019  6990  6990 D FileShare-Client: Outbound.stopDelayTimer - 
,09-01 10:59:27.019  1015  1467 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-01 10:59:27.019  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:27.019  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.019  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.019  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:27.039  7005  7005 E Zygote  : MountEmulatedStorage(),
09-01 10:59:27.039  7005  7005 E Zygote  : v2,
09-01 10:59:27.039  7005  7005 I libpersona: KNOX_SDCARD checking this for 10065
09-01 10:59:27.039  1015  1467 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7005 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-01 10:59:27.039  7005  7005 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:27.039  7005  7005 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:27.039  1015  1467 I ActivityManager: Killing 6455:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,09-01 10:59:27.039   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:27.039  7005  7005 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:27.039  7005  7005 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:27.049  6952  6952 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-01 10:59:27.049  6952  6952 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-01 10:59:27.049  6952  6952 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-01 10:59:27.059  7005  7005 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:27.059  6952  6952 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-01 10:59:27.059  7005  7005 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:27.069  1015  1495 I ActivityManager: Killing 6483:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-01 10:59:27.069  6952  6952 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 10:59:27.069  6952  6952 I vclib   : onServiceConnected
,09-01 10:59:27.089  7005  7005 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 10:59:27.089  1015  1481 I ActivityManager: Killing 6524:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-01 10:59:27.109  1015  1322 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 10:59:27.109  1015  1322 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:27.109  1015  1322 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:27.109  1015  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:27.109  1015  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:27.109  1627  1627 I Hs20UtilService: Starting #9
,09-01 10:59:27.109  1627  1701 I Hs20UtilService: Message received 5007
,09-01 10:59:27.109  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-01 10:59:27.109  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:27.109  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 10:59:27.109  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-01 10:59:27.109  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 10:59:27.109  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-01 10:59:27.109  1300  2241 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 10:59:27.119  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 10:59:27.119  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:27.119  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:27.119  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:27.119  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:27.119  1627  1627 I Hs20UtilService: Starting #10
,09-01 10:59:27.119  1627  1701 I Hs20UtilService: Message received 5011
,09-01 10:59:27.129  6553  6553 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-01 10:59:27.129  6553  6553 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 10:59:27.129  6553  6553 D SecurityLogAgent: StateMachine : Current State = 1
,09-01 10:59:27.129  6553  6553 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 10:59:27.139  1015  1322 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:27.139  1015  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:27.139  1015  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:27.399  1015  1042 D Tethering: interfaceRemoved wlan0
,09-01 10:59:27.399  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-01 10:59:27.409  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:27.409  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:27.409  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:27.409  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:27.409  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:27.409  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:27.409  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:27.409  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:27.409  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:27.409  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:27.409  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:27.409  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:27.419  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:27.419  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:27.419  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:27.419  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:27.419  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:27.419  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:27.419  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:27.419  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:27.419  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:27.419  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:27.419  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:27.419  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:27.429  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:27.429  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:27.429  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:27.429  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:27.429  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:27.429  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:27.429  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:27.429  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:27.429  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:27.429  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:27.429  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:27.429  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:27.439  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:27.439  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:27.439  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:27.439  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:27.439  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:27.439  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:27.439  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-01 10:59:27.439  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.439  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.439  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.439  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:27.449  1015  1015 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7021 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-01 10:59:27.449  7021  7021 E Zygote  : MountEmulatedStorage()
09-01 10:59:27.449  7021  7021 I libpersona: KNOX_SDCARD checking this for 1000
09-01 10:59:27.449  7021  7021 E Zygote  : v2
09-01 10:59:27.449  7021  7021 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:27.449  7021  7021 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:27.459  7021  7021 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-01 10:59:27.459  7021  7021 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:27.479  7021  7021 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 10:59:27.479  7021  7021 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:27.499  7021  7021 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-01 10:59:27.499  7021  7021 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-01 10:59:27.499  7021  7021 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-01 10:59:27.519  7021  7021 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-01 10:59:27.519  7021  7021 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-01 10:59:27.519  7021  7021 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-01 10:59:27.519  7021  7021 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:27.519  1015  1495 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,09-01 10:59:27.519  7021  7036 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-01 10:59:27.519  1015  1495 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-01 10:59:27.529  1015  1495 I ActivityManager: Killing 6569:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,09-01 10:59:27.539  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-01 10:59:27.539  1777  1777 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-01 10:59:27.539  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:27.539  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:27.539  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.539  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:27.559  7038  7038 E Zygote  : MountEmulatedStorage(),
09-01 10:59:27.559  7038  7038 I libpersona: KNOX_SDCARD checking this for 10121
09-01 10:59:27.559  7038  7038 E Zygote  : v2
09-01 10:59:27.559  7038  7038 I libpersona: KNOX_SDCARD not a persona
09-01 10:59:27.559  7038  7038 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:27.559  7038  7038 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:27.559  7038  7038 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:27.559  1015  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7038 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-01 10:59:27.569  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-01 10:59:27.569  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:27.569  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.569  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.569  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:27.579  1015  1042 D Tethering: interfaceRemoved p2p0
09-01 10:59:27.579  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-01 10:59:27.579  2609  5133 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,09-01 10:59:27.589  7038  7038 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:27.589  7038  7038 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:27.589  7052  7052 E Zygote  : MountEmulatedStorage()
,09-01 10:59:27.589  7052  7052 E Zygote  : v2
,09-01 10:59:27.599  7052  7052 I libpersona: KNOX_SDCARD checking this for 10001
09-01 10:59:27.599  7052  7052 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:27.599  7052  7052 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-01 10:59:27.599  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7052 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 10:59:27.599  7052  7052 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:27.599  7052  7052 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-01 10:59:27.609  1777  1777 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
09-01 10:59:27.609  1777  1777 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
09-01 10:59:27.609  1777  1777 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
09-01 10:59:27.609  1777  1777 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-01 10:59:27.609  1015  1481 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-01 10:59:27.609  1015  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.619  1015  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.619  1015  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.619  1015  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:27.629  7068  7068 E Zygote  : MountEmulatedStorage()
,09-01 10:59:27.629  7068  7068 E Zygote  : v2
09-01 10:59:27.629  7068  7068 I libpersona: KNOX_SDCARD checking this for 10031
09-01 10:59:27.629  7068  7068 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:27.629  7052  7052 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 10:59:27.629  7038  7038 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 10:59:27.629  7052  7052 D ActivityThread: Added TimaKeyStore provider
09-01 10:59:27.629  7068  7068 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 10:59:27.629  7038  7038 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-01 10:59:27.639  7038  7038 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-01 10:59:27.639  1015  1481 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7068 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
09-01 10:59:27.639  7068  7068 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:27.639  7068  7068 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:27.659  7038  7038 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:27.659  7038  7038 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-01 10:59:27.659  1777  1777 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-01 10:59:27.659  1777  1777 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-01 10:59:27.659  1015  1473 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-01 10:59:27.669  7038  7038 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-01 10:59:27.669  1015  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.669  1015  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.669  1015  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.669  1015  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:27.669  7068  7068 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:27.669  7068  7068 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:27.679  7083  7083 E Zygote  : MountEmulatedStorage()
,09-01 10:59:27.679  7083  7083 E Zygote  : v2
09-01 10:59:27.679  7083  7083 I libpersona: KNOX_SDCARD checking this for 10077
09-01 10:59:27.679  7083  7083 I libpersona: KNOX_SDCARD not a persona,
,09-01 10:59:27.689  7083  7083 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:27.689  1015  1473 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7083 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-01 10:59:27.689  7083  7083 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:27.689  7083  7083 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-01 10:59:27.699  1015  1473 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-01 10:59:27.699  1015  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.699  1015  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.699  1015  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.699  1015  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:27.709  7083  7083 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:27.709  7083  7083 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:27.719  7098  7098 E Zygote  : MountEmulatedStorage(),
09-01 10:59:27.719  7098  7098 E Zygote  : v2
09-01 10:59:27.719  7098  7098 I libpersona: KNOX_SDCARD checking this for 10141
09-01 10:59:27.719  7098  7098 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:27.719  7098  7098 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:27.729  1015  1473 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7098 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-01 10:59:27.729  1015  1473 I ActivityManager: Killing 6586:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
09-01 10:59:27.729  7098  7098 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-01 10:59:27.729  7098  7098 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:27.749  7098  7098 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:27.749  7098  7098 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:27.759   307   307 I art     : Explicit concurrent mark sweep GC freed 8707(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 895us total 36.333ms
,09-01 10:59:27.769  7068  7068 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-01 10:59:27.779  1015  1473 I ActivityManager: Killing 6049:com.android.mms/u0a41 (adj 15): empty #21
,09-01 10:59:27.789   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 855us total 25.443ms
,09-01 10:59:27.799  1015  1462 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
09-01 10:59:27.799  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.799  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.799  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.799  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.799  7098  7098 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-01 10:59:27.799  7098  7098 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 10:59:27.799  7098  7098 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 10:59:27.799  7098  7098 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-01 10:59:27.799  2779  7115 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-01 10:59:27.809   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 693us total 17.394ms
,09-01 10:59:27.809  2779  7115 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-01 10:59:27.809  2779  7115 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
09-01 10:59:27.809  2779  7115 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-01 10:59:27.819  2779  7115 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-01 10:59:27.819  7116  7116 E Zygote  : MountEmulatedStorage()
09-01 10:59:27.819  7116  7116 E Zygote  : v2
09-01 10:59:27.819  7116  7116 I libpersona: KNOX_SDCARD checking this for 10032
09-01 10:59:27.819  7116  7116 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:27.819  7116  7116 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-01 10:59:27.829  7116  7116 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 10:59:27.829  1015  1462 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7116 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-01 10:59:27.829  7116  7116 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-01 10:59:27.839  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-01 10:59:27.839  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.839  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.839  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.839  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:27.859  7116  7116 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-01 10:59:27.859  7116  7116 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:27.859  7131  7131 E Zygote  : MountEmulatedStorage()
09-01 10:59:27.859  7131  7131 I libpersona: KNOX_SDCARD checking this for 1000
09-01 10:59:27.859  7131  7131 E Zygote  : v2
09-01 10:59:27.859  7131  7131 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:27.859  7131  7131 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:27.859  1015  1028 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7131 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-01 10:59:27.859  7131  7131 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:27.869  7131  7131 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-01 10:59:27.869  1015  1028 I ActivityManager: Killing 6606:com.qualcomm.timeservice/1000 (adj 15): empty #21
09-01 10:59:27.869  1015  1134 D CountryDetector: No listener is left
,09-01 10:59:27.879  1015  1028 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 10:59:27.889  1015  1467 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 10:59:27.889  7131  7131 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 10:59:27.889  7131  7131 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:27.899  1015  1322 I ActivityManager: Killing 6539:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-01 10:59:27.929  1015  1462 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 10:59:27.939  7116  7151 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-01 10:59:27.939  7116  7151 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-01 10:59:27.949  1015  1134 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 10:59:27.949  7116  7116 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-01 10:59:27.949  1015  1495 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-01 10:59:27.949  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:27.949  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.949  7116  7151 D SPPClientService: PushLog.txt file is not deleted.
09-01 10:59:27.949  7116  7151 D SPPClientService: PushLog.txt file is not deleted.
09-01 10:59:27.949  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:27.949  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:27.949  7116  7151 D SPPClientService: ============PushLog. stop!
,09-01 10:59:27.959  7131  7131 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-01 10:59:27.979  7154  7154 E Zygote  : MountEmulatedStorage(),
,09-01 10:59:27.979  7154  7154 E Zygote  : v2,
09-01 10:59:27.979  7154  7154 I libpersona: KNOX_SDCARD checking this for 10036
09-01 10:59:27.979  7154  7154 I libpersona: KNOX_SDCARD not a persona,
,09-01 10:59:27.979  7154  7154 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-01 10:59:27.989  7154  7154 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-01 10:59:27.989  1015  1495 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7154 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 10:59:27.989  1015  1495 I ActivityManager: Killing 6627:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,09-01 10:59:27.999  7154  7154 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-01 10:59:27.999  1015  1481 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-01 10:59:27.999  1015  1481 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-01 10:59:27.999  1015  1481 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:27.999  1015  1481 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-01 10:59:27.999  1015  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-01 10:59:28.009  1015  1134 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-01 10:59:28.009  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-01 10:59:28.019  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:28.019  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-01 10:59:28.019  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-01 10:59:28.019  1015  1473 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 10:59:28.029  1015  1481 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 10:59:28.029  7173  7173 E Zygote  : MountEmulatedStorage()
,09-01 10:59:28.029  7173  7173 E Zygote  : v2
09-01 10:59:28.029  7173  7173 I libpersona: KNOX_SDCARD checking this for 10068
09-01 10:59:28.029  7173  7173 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:28.039  7173  7173 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:28.039   288   288 E SMD     : DCD OFF,
,09-01 10:59:28.039   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:28.039  7173  7173 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:28.049  7154  7154 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 10:59:28.049  1015  1134 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7173 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
09-01 10:59:28.049  7154  7154 D ActivityThread: Added TimaKeyStore provider
09-01 10:59:28.049  7173  7173 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-01 10:59:28.069  7173  7173 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 10:59:28.069  7173  7173 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:28.079  1015  1481 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 10:59:28.099  7173  7173 D BadgeProvider: onCreate
,09-01 10:59:28.099  7173  7173 D BadgeProvider: DatabaseHelper
,09-01 10:59:28.109  7116  7163 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-01 10:59:28.109  7154  7154 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@6e4c096
,09-01 10:59:28.119  7154  7154 I SA      : [SSP] onCreated
,09-01 10:59:28.129  1015  1322 D RCPManagerService: exchangeData() failure , invalid userId
09-01 10:59:28.129  1015  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
09-01 10:59:28.129  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:28.129  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:28.129  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:28.129  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:28.139  7173  7181 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-01 10:59:28.149  7190  7190 E Zygote  : MountEmulatedStorage(),
,09-01 10:59:28.149  7190  7190 E Zygote  : v2
09-01 10:59:28.149  7190  7190 I libpersona: KNOX_SDCARD checking this for 10009,
09-01 10:59:28.149  7190  7190 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:28.159  7190  7190 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-01 10:59:28.159  7131  7131 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,09-01 10:59:28.159  7190  7190 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-01 10:59:28.159  7190  7190 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-01 10:59:28.169  1015  1495 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7190 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-01 10:59:28.169  1015  1495 I ActivityManager: Killing 6647:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,09-01 10:59:28.169  7131  7131 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
09-01 10:59:28.169  7131  7131 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:28.179  7131  7131 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-01 10:59:28.179  7131  7131 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
09-01 10:59:28.179  7131  7131 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-01 10:59:28.179  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-01 10:59:28.179  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:28.179  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:28.179  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:28.179  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:28.199  7154  7154 I SA      : [TPM] There is no property file
,09-01 10:59:28.199  7154  7154 I SA      : [SCU] isHaveSA() - false
,09-01 10:59:28.199  7207  7207 E Zygote  : MountEmulatedStorage()
09-01 10:59:28.199  7207  7207 E Zygote  : v2
09-01 10:59:28.199  7207  7207 I libpersona: KNOX_SDCARD checking this for 10008
09-01 10:59:28.199  7207  7207 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:28.209  7207  7207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:28.209  7154  7154 I SA      : [TPM] getModelProperty : null
,09-01 10:59:28.209  7207  7207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 10:59:28.209  7154  7154 I SA      : [TPM] getCSCProperty : null
,09-01 10:59:28.209  7207  7207 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-01 10:59:28.209  7154  7154 I SA      : [DM] FLOATING AMOLED FEATURE: true
,09-01 10:59:28.209  7190  7190 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:28.219  7154  7154 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-01 10:59:28.219  7190  7190 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:28.219  7154  7154 I SA      : [DM] TFT FEATURE: false
,09-01 10:59:28.219  7154  7154 I SA      : [DM] init START
,09-01 10:59:28.219  7154  7154 I SA      : [DM] This device is not a Vodafone
,09-01 10:59:28.229  1015  1134 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7207 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-01 10:59:28.229  1015  1134 I ActivityManager: Killing 6466:com.android.calendar/u0a131 (adj 15): empty #21
09-01 10:59:28.229  7207  7207 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 10:59:28.229  7207  7207 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:28.239  1479  1479 D Launcher.Model: reloadBadges entered.
09-01 10:59:28.239  7173  7187 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-01 10:59:28.239  7173  7187 D BadgeProvider: sendNotify, [notify] : null
09-01 10:59:28.239  7173  7187 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-01 10:59:28.239  7173  7187 D BadgeProvider: update, [BadgeCount] : badgecount=0
,09-01 10:59:28.239  7173  7187 D BadgeProvider: update, [UpdateCount] : 1
,09-01 10:59:28.249  1015  1134 I ActivityManager: Killing 6662:com.google.android.gms:car/u0a11 (adj 15): empty #21
,09-01 10:59:28.249  7154  7154 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
09-01 10:59:28.249  7154  7154 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
09-01 10:59:28.249  7154  7154 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
09-01 10:59:28.249  7154  7154 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
09-01 10:59:28.249  7154  7154 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-01 10:59:28.249  1015  1495 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-01 10:59:28.249  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-01 10:59:28.249  7154  7154 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-01 10:59:28.249  7154  7154 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
09-01 10:59:28.249  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:28.249  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:28.249  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-01 10:59:28.259  1015  1322 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-01 10:59:28.259  1015  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:28.259  1015  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:28.259  1015  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:28.259  1015  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:28.259  7154  7154 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-01 10:59:28.259  7154  7154 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-01 10:59:28.269  7154  7154 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-01 10:59:28.279  7154  7154 I SA      : [SCU] isHaveSA() - false,
09-01 10:59:28.279  7154  7154 I SA      : support phone number id : false
09-01 10:59:28.279  7154  7154 I SA      : [DM] Supports Ref Jpn : true
09-01 10:59:28.279  7154  7154 I SA      : [DM] init END
09-01 10:59:28.279  7154  7154 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-01 10:59:28.279  7154  7154 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,09-01 10:59:28.279  7154  7154 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-01 10:59:28.289  7225  7225 E Zygote  : MountEmulatedStorage()
09-01 10:59:28.289  7225  7225 I libpersona: KNOX_SDCARD checking this for 10110
09-01 10:59:28.289  7225  7225 E Zygote  : v2
09-01 10:59:28.289  7225  7225 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:28.289  7225  7225 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:28.289  7154  7154 I SA      : [SLFUCHKMGR] constructor called,
09-01 10:59:28.289  7225  7225 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 10:59:28.289  1015  1322 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7225 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 10:59:28.289  7225  7225 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-01 10:59:28.289  1015  1472 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-01 10:59:28.289  1015  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-01 10:59:28.299  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:28.299  1015  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:28.299  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-01 10:59:28.309  6952  7223 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-01 10:59:28.319  1015  1134 I ActivityManager: Killing 6011:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-01 10:59:28.329  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-01 10:59:28.339  7154  7154 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-01 10:59:28.339  7154  7154 I SA      : [OR] == isSIMCardReady false ==
,09-01 10:59:28.339  7225  7225 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:28.339  7154  7154 I SA      : [SCU] == networkStateCheck == false
09-01 10:59:28.339  7154  7154 I SA      : [OR] onReceive END
,09-01 10:59:28.339  7225  7225 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:28.339  1015  1028 I ActivityManager: Killing 5823:com.android.vending/u0a26 (adj 15): empty #21
,09-01 10:59:28.349  1226  1226 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:28.369  1015  1473 I ActivityManager: Killing 6502:com.samsung.android.sm/1000 (adj 15): empty #21
,09-01 10:59:28.379  1015  1027 I ActivityManager: Killing 6869:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-01 10:59:28.379  1015  1462 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:28.379  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-01 10:59:28.379  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:28.379  1015  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:28.379  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:28.389  2922  2922 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Sep 01 10:59:28 GMT+02:00 2016
,09-01 10:59:28.389  1015  1134 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-01 10:59:28.389  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-01 10:59:28.389  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:28.389  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:28.389  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-01 10:59:28.399  4760  7243 I iu.SyncManager: SYNC; picasa accounts
,09-01 10:59:28.399  2922  2922 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-01 10:59:28.399  2922  2922 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-01 10:59:28.409  4760  4760 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-01 10:59:28.409  2922  2922 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-01 10:59:28.409  2922  2922 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-01 10:59:28.419  2922  7244 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-01 10:59:28.419  2922  7244 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-01 10:59:28.419  2922  7244 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-01 10:59:28.419  2922  7244 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-01 10:59:28.429  2922  2922 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-01 10:59:28.429  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0,
09-01 10:59:28.429  1015  1319 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-01 10:59:28.439  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-01 10:59:28.439  1015  1322 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-01 10:59:28.489  1015  1322 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-01 10:59:28.489  1015  1322 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-01 10:59:28.489  1015  1322 D SecContentProvider2: mCursor = null
,09-01 10:59:28.489  1015  1322 D WifiService: setWifiEnabled: true pid=6726, uid=10171
,09-01 10:59:28.489  1015  1322 W ActivityManager: Permission Denial: getCurrentUser() from pid=6726, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-01 10:59:28.489  1015  1322 W WifiService: Failed getting userId using ActivityManagerNative
09-01 10:59:28.489  1015  1322 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6726, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-01 10:59:28.489  1015  1322 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-01 10:59:28.489  1015  1322 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-01 10:59:28.489  1015  1322 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-01 10:59:28.489  1015  1322 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-01 10:59:28.489  1015  1322 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-01 10:59:28.489  1015  1322 D SettingsProvider: name = wifi_on
,09-01 10:59:28.499  1015  1124 E WifiHW  : ##################### set firmware type 0 #####################
,09-01 10:59:28.579  1015  1467 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-01 10:59:28.719   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-01 10:59:28.719   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:28.719  7225  7249 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache,
,09-01 10:59:28.719   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-01 10:59:28.719   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:28.719  7225  7249 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-01 10:59:28.729   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-01 10:59:28.729   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:28.729  7225  7256 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-01 10:59:28.729   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-01 10:59:28.729   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:28.729  7225  7256 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-01 10:59:28.759  7225  7225 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-01 10:59:28.759  7225  7225 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-01 10:59:28.759  7225  7225 I GAv4    :   adb logcat -s GAv4
,09-01 10:59:28.779  7225  7225 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-01 10:59:28.779  1015  1467 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-01 10:59:28.799  7225  7225 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-01 10:59:28.799  7225  7258 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-01 10:59:28.869  1015  1042 D Tethering: interfaceAdded wlan0
,09-01 10:59:28.869  1015  1129 E Tethering: No numeric data
,09-01 10:59:28.879  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-01 10:59:28.879  1015  1129 D Tethering: clearTetheredNotification()
,09-01 10:59:28.879  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-01 10:59:28.879  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:28.879  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:28.879  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-01 10:59:28.879  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 10:59:28.879  1176  1176 D HotspotTile: updateTetherState():false, false
,09-01 10:59:28.879  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-01 10:59:28.879  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:28.879  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-01 10:59:28.879  1015  1121 V NetworkStats: performPollLocked() took 5ms
09-01 10:59:28.879  1015  1129 D Tethering: InitialState.processMessage what=4
09-01 10:59:28.879  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:28.879  1015  1129 E Tethering: No numeric data
,09-01 10:59:28.889  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:28.889  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-01 10:59:28.889  1015  1129 D Tethering: clearTetheredNotification()
,09-01 10:59:28.889  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:28.889  1015  1042 D Tethering: interfaceAdded p2p0
09-01 10:59:28.889  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 10:59:28.889  1176  1176 D HotspotTile: updateTetherState():false, false
,09-01 10:59:28.889  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-01 10:59:28.889  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:28.889  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-01 10:59:28.889  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:28.889  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-01 10:59:28.889  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 10:59:28.889  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
09-01 10:59:28.889  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 10:59:28.899  1015  1121 V NetworkStats: performPollLocked() took 4ms
09-01 10:59:28.899  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:28.899   278  1014 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
09-01 10:59:28.899   278  1014 D SoftapController: Softap fwReload - Ok
,09-01 10:59:28.899  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:28.899  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:28.899   278  1014 D CommandListener: Setting iface cfg
09-01 10:59:28.899   278  1014 D CommandListener: Trying to bring down wlan0
,09-01 10:59:28.899   278  1014 D CommandListener: Clearing all IP addresses on wlan0
,09-01 10:59:28.899  1015  1124 E WifiHW  : supplicant_name : p2p_supplicant
,09-01 10:59:28.909  1015  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-01 10:59:28.909  1015  1124 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-01 10:59:28.909  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 10:59:28.909  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-01 10:59:28.909  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:28.909  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:28.909  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:28.909  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:28.909  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:28.909  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 10:59:28.909  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-01 10:59:28.909  1176  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-01 10:59:28.919  1176  1176 D HotspotTile: onReceive : 2, 0,
,09-01 10:59:28.919  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:28.929  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:28.929  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:28.959  7261  7261 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-01 10:59:28.959  7261  7261 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-01 10:59:28.959  7261  7261 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-01 10:59:28.979  7261  7261 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-01 10:59:28.979   405   405 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7261
09-01 10:59:28.979   405   405 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
09-01 10:59:28.979  7261  7261 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-01 10:59:28.979  7261  7261 I wpa_supplicant: ssSupport state is = 1
09-01 10:59:28.979  7261  7261 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-01 10:59:28.979  7261  7261 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-01 10:59:28.979   405   405 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7261
09-01 10:59:28.979   405   405 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-01 10:59:29.039   319   319 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,09-01 10:59:29.059  1015  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:29.059  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:29.059  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:29.059  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-01 10:59:29.099  7225  7225 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-01 10:59:29.119  7225  7225 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 8892-8894)
,09-01 10:59:29.119  7225  7225 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-01 10:59:29.129  7225  7225 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {28d805a9}
,09-01 10:59:29.129  7225  7225 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-01 10:59:29.129  7225  7225 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-01 10:59:29.149   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,09-01 10:59:29.149  7225  7225 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,09-01 10:59:29.149  7225  7225 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,09-01 10:59:29.149  7225  7225 E SysUtils: ApplicationContext is null in ApplicationStatus,
,09-01 10:59:29.159  7261  7261 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,09-01 10:59:29.169  7225  7225 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-01 10:59:29.169  7225  7225 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-01 10:59:29.169  7225  7225 I Adreno-EGL: Build Date: 04/06/15 Mon
09-01 10:59:29.169  7225  7225 I Adreno-EGL: Local Branch: 
09-01 10:59:29.169  7225  7225 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-01 10:59:29.169  7225  7225 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-01 10:59:29.169  7225  7225 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-01 10:59:29.209  7261  7261 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-01 10:59:29.209  7261  7261 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-01 10:59:29.219  7261  7261 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-01 10:59:29.219   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7261
09-01 10:59:29.219   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-01 10:59:29.219  7261  7261 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-01 10:59:29.219  7261  7261 I wpa_supplicant: ssSupport state is = 1
09-01 10:59:29.219  7261  7261 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-01 10:59:29.219  7261  7261 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 10:59:29.219  7261  7261 E wpa_supplicant: SIM READ ERROR
09-01 10:59:29.219  7261  7261 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:29.219  7261  7261 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 10:59:29.219  7261  7261 E wpa_supplicant: SIM READ ERROR
09-01 10:59:29.219  7261  7261 I wpa_supplicant: Blacklist: Clear (all) 
09-01 10:59:29.229  7261  7261 I wpa_supplicant: wpa_default_ap_write_once
09-01 10:59:29.229  7261  7261 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-01 10:59:29.229  7261  7261 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:29.229  7261  7261 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
09-01 10:59:29.229  7261  7261 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:29.229  7261  7261 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-01 10:59:29.229  7261  7261 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-01 10:59:29.229  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-01 10:59:29.229  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:29.229  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:29.239  7225  7290 W cr.media: Requires BLUETOOTH permission
,09-01 10:59:29.239  7225  7225 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-01 10:59:29.249  7225  7225 I NSApplication: Starting up...
,09-01 10:59:29.249  1015  1472 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-01 10:59:29.259  1015  1319 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-01 10:59:29.259  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-01 10:59:29.269  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:29.269  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:29.269  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:29.269  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:29.279  7295  7295 E Zygote  : MountEmulatedStorage()
,09-01 10:59:29.279  7295  7295 E Zygote  : v2
09-01 10:59:29.279  7295  7295 I libpersona: KNOX_SDCARD checking this for 10117
09-01 10:59:29.279  7295  7295 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:29.279  7295  7295 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:29.279  1015  1134 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7295 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
09-01 10:59:29.279  1015  1134 I ActivityManager: Killing 6926:com.android.bluetooth/1002 (adj 15): empty #21
09-01 10:59:29.279  7295  7295 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:29.279  7295  7295 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-01 10:59:29.299  7261  7261 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-01 10:59:29.309  7295  7295 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:29.309  7295  7295 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:29.329  7295  7295 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-01 10:59:29.489  7261  7261 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-01 10:59:29.489  7261  7261 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-01 10:59:29.509  7261  7261 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-01 10:59:29.509   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7261
09-01 10:59:29.509   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-01 10:59:29.509  7261  7261 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-01 10:59:29.509  7261  7261 I wpa_supplicant: ssSupport state is = 1,
,09-01 10:59:29.509  7261  7261 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-01 10:59:29.509  7261  7261 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-01 10:59:29.519  7261  7261 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-01 10:59:29.519   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7261
09-01 10:59:29.519   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-01 10:59:29.519  7261  7261 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-01 10:59:29.519  7261  7261 I wpa_supplicant: ssSupport state is = 1
09-01 10:59:29.519  7261  7261 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:29.519  7261  7261 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 10:59:29.519  7261  7261 E wpa_supplicant: SIM READ ERROR
09-01 10:59:29.519  7261  7261 I wpa_supplicant: wpa_default_ap_write_once,
09-01 10:59:29.519  7261  7261 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-01 10:59:29.519  7261  7261 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-01 10:59:29.519  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-01 10:59:29.519  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 10:59:29.519  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
09-01 10:59:29.529  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-01 10:59:29.529  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,09-01 10:59:29.529  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-01 10:59:29.639  7261  7261 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-01 10:59:29.639  7261  7261 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-01 10:59:29.699  1015  1467 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-01 10:59:29.699  1015  1467 I ActivityManager: Killing 6884:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-01 10:59:29.699  1015  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 10:59:29.699  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:29.709  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:29.709  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:29.709  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:29.709  1627  1627 I Hs20UtilService: Starting #11
,09-01 10:59:29.709  1627  1701 I Hs20UtilService: Message received 5011
,09-01 10:59:29.709  6553  6553 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-01 10:59:29.709  6553  6553 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 10:59:29.709  6553  6553 D SecurityLogAgent: StateMachine : Current State = 1
09-01 10:59:29.709  6553  6553 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 10:59:29.719  7261  7261 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
09-01 10:59:29.719  7261  7261 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-01 10:59:29.719  7261  7261 I wpa_supplicant: Skip scan - bUseNetwork false
,09-01 10:59:29.729  1015  1319 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 10:59:29.729  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:29.729  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:29.729  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:29.729  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
09-01 10:59:29.729  1627  1627 I Hs20UtilService: Starting #12
09-01 10:59:29.729  1627  1701 I Hs20UtilService: Message received 5011
,09-01 10:59:29.729  6553  6553 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-01 10:59:29.729  6553  6553 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 10:59:29.729  6553  6553 D SecurityLogAgent: StateMachine : Current State = 1
09-01 10:59:29.729  6553  6553 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 10:59:29.879  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-01 10:59:29.879  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-01 10:59:29.879  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-01 10:59:29.909  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-01 10:59:29.909  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-01 10:59:29.919  7261  7261 I wpa_supplicant: HOTSPOT20_ENABLE called
09-01 10:59:29.919  7261  7261 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:29.919  7261  7261 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 10:59:29.919  7261  7261 E wpa_supplicant: SIM READ ERROR
09-01 10:59:29.919  7261  7261 I wpa_supplicant: Blacklist: Clear (all) 
,09-01 10:59:29.939  7261  7261 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-01 10:59:29.949  7261  7261 I wpa_supplicant: Skip scan - bUseNetwork false
,09-01 10:59:29.949  1015  1124 D WifiConfigStore: Loading config and enabling all networks ,
,09-01 10:59:29.949  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:29.949  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-01 10:59:29.959  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.959  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.959  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.959  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:29.959  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 10:59:29.959  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-01 10:59:29.959  1176  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-01 10:59:29.959  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:29.959  1176  1176 D HotspotTile: onReceive : 3, 0
,09-01 10:59:29.959  1015  1124 E WifiConfigStore: Not a HS20
,09-01 10:59:29.959  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:29.969  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:29.969  1015  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-01 10:59:29.969  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:29.969  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:29.969  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:29.969  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:29.969  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:29.969  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:29.969  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:29.969  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:29.969  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:29.969  6726  6726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:29.969  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:29.969  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:29.969  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:29.969  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:29.969  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:29.969  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:29.969  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:29.969  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:29.969  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:29.969  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:29.969  6726  6726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:29.969  1015  1462 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 10:59:29.969  1015  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-01 10:59:29.969  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
09-01 10:59:29.969  1015  1462 W ActivityManager: userId = 0, bbcId = -10000,
09-01 10:59:29.969  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:29.969  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 10:59:29.979  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,09-01 10:59:29.979  7261  7261 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
,09-01 10:59:29.979  7261  7261 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-01 10:59:29.979  1627  1627 I Hs20UtilService: Starting #13,
09-01 10:59:29.979  7261  7261 I wpa_supplicant: reset timer : RESET_TIMER 0
09-01 10:59:29.979  7261  7261 I wpa_supplicant: P2P: Current p2p state = IDLE
09-01 10:59:29.979  7261  7261 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-01 10:59:29.979  7261  7261 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,09-01 10:59:29.979  7261  7261 I wpa_supplicant: First Scan Start
09-01 10:59:29.979  7261  7261 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-01 10:59:29.979  1627  1701 I Hs20UtilService: Message received 5011
09-01 10:59:29.979  6553  6553 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-01 10:59:29.979  6553  6553 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 10:59:29.979  6553  6553 D SecurityLogAgent: StateMachine : Current State = 1
,09-01 10:59:29.979  1015  1124 D WifiNative-wlan0: Setting external_sim to 1
09-01 10:59:29.979  1015  1124 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 10:59:29.979  1015  1124 I WifiNative-HAL: startHal
09-01 10:59:29.979  1015  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9eef688c
09-01 10:59:29.979  1015  1124 I WifiNative-HAL: Could not start hal
09-01 10:59:29.979  6952  6952 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 10:59:29.979  6553  6553 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 10:59:29.979  1015  1124 E WifiNative-wlan0: do suspend true
,09-01 10:59:29.989  1015  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-01 10:59:29.989   278  1014 D CommandListener: Setting iface cfg
09-01 10:59:29.989   278  1014 D CommandListener: Trying to bring up p2p0
,09-01 10:59:29.989  1015  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-01 10:59:29.989  1015  1123 D WifiP2pService: P2pEnablingState
09-01 10:59:29.989  1015  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
09-01 10:59:29.989  1015  1123 D WifiP2pService: P2p socket connection successful
,09-01 10:59:29.989  1015  1123 D WifiP2pService: P2pEnabledState
,09-01 10:59:29.989  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-01 10:59:29.989  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-01 10:59:29.989  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-01 10:59:29.999  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-01 10:59:29.999  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-01 10:59:29.999  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-01 10:59:29.999  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 10:59:29.999  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-01 10:59:29.999  1015  1045 D WifiDisplayController: disconnect
09-01 10:59:29.999  1015  1124 E WifiNative-wlan0: invaild command id : 215
09-01 10:59:29.999  1015  1045 D WifiDisplayController: updateConnection
09-01 10:59:29.999  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 10:59:29.999  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-01 10:59:29.999  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
09-01 10:59:29.999  1015  1015 D RttService: SCAN_AVAILABLE : 3
09-01 10:59:29.999  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:29.999  1015  1148 I WifiNative-HAL: startHal
09-01 10:59:29.999  1015  1148 E wifi    : getStaticLongField sWifiHalHandle 0x993e09bc
09-01 10:59:29.999  1015  1148 I WifiNative-HAL: Could not start hal
09-01 10:59:29.999  1015  1148 E WifiScanningService: could not start HAL
09-01 10:59:29.999  1015  1149 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 10:59:29.999  7261  7261 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-01 10:59:29.999  7261  7261 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-01 10:59:29.999  7261  7261 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands,
09-01 10:59:30.009  1015  1124 E WifiStateMachine: Failed to set frequency band 0
,09-01 10:59:30.009  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-01 10:59:30.009  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-01 10:59:30.009  1015  1124 E WifiNative-wlan0: invaild command id : 215
,09-01 10:59:30.009  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:30.009  1015  1124 D SecContentProvider2: mCursor = null
09-01 10:59:30.009  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-01 10:59:30.009  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-01 10:59:30.009  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-01 10:59:30.009  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-01 10:59:30.009  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress
09-01 10:59:30.009  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,09-01 10:59:30.009  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-01 10:59:30.009  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:30.009  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-01 10:59:30.009  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-01 10:59:30.009  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 10:59:30.009  1015  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-01 10:59:30.009  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-01 10:59:30.009  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-01 10:59:30.009  1015  1123 D WifiP2pService: DeviceAddress: 0a:76:28
09-01 10:59:30.009  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:30.009  1015  1124 D SecContentProvider2: mCursor = null
09-01 10:59:30.009  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-01 10:59:30.009  1300  2241 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 10:59:30.019  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-01 10:59:30.019  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-01 10:59:30.019  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
09-01 10:59:30.019  1015  1045 D WifiDisplayController:  secondary type: null
09-01 10:59:30.019  1015  1045 D WifiDisplayController:  wps: 0
09-01 10:59:30.019  1015  1045 D WifiDisplayController:  grpcapab: 0
09-01 10:59:30.019  1015  1045 D WifiDisplayController:  devcapab: 0
09-01 10:59:30.019  1015  1045 D WifiDisplayController:  status: 3
09-01 10:59:30.019  1015  1045 D WifiDisplayController:  wfdInfo: null
09-01 10:59:30.019  1015  1045 D WifiDisplayController:  groupownerAddress: null
09-01 10:59:30.019  1015  1045 D WifiDisplayController:  GOdeviceName: null
09-01 10:59:30.019  1015  1045 D WifiDisplayController:  interfaceAddress: 
09-01 10:59:30.019  1015  1045 D WifiDisplayController:  SConnectInfo : null
,09-01 10:59:30.019  6990  6990 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 10:59:30.019  6990  6990 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-01 10:59:30.019  6990  6990 D FileShare-Client: Outbound.stopDelayTimer - 
,09-01 10:59:30.029  1015  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-01 10:59:30.029  1015  1123 D WifiP2pService: InactiveState
09-01 10:59:30.029  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
,09-01 10:59:30.029  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-01 10:59:30.029  7005  7005 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-01 10:59:30.029  7261  7261 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-01 10:59:30.029  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
09-01 10:59:30.029  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-01 10:59:31.049   288   288 E SMD     : DCD OFF
,09-01 10:59:31.199  7261  7261 I wpa_supplicant: nl80211: Received scan results (25 BSSes),
09-01 10:59:31.199  7261  7261 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-01 10:59:31.199  7261  7261 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-01 10:59:31.199  7261  7261 I wpa_supplicant: Trying to associate with  'G700'
09-01 10:59:31.199  7261  7261 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-01 10:59:31.199  7261  7261 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-01 10:59:31.199  1015  7320 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-01 10:59:31.219  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-01 10:59:31.219  1015  1124 D SecContentProvider2: mCursor = null
,09-01 10:59:31.319  7261  7261 E wpa_supplicant: Cmd 35605 not handled
,09-01 10:59:31.319  7261  7261 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-01 10:59:31.319  7261  7261 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
09-01 10:59:31.319  7261  7261 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-01 10:59:31.319  7261  7261 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-01 10:59:31.319  7261  7261 I wpa_supplicant: Associated with F4.99.3E
,09-01 10:59:31.319  7261  7261 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-01 10:59:31.319  7261  7261 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-01 10:59:31.319  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:31.319  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:31.319  7261  7261 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-01 10:59:31.319  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:31.329  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 10:59:31.329  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:31.329  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:31.329  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 10:59:31.329  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:31.329  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:31.329  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true,
09-01 10:59:31.329  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-01 10:59:31.329  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,09-01 10:59:31.329  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:31.329  1015  1124 D SecContentProvider2: mCursor = null
,09-01 10:59:31.329  7261  7261 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-01 10:59:31.339  7261  7261 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-01 10:59:31.339  1015  1129 E Tethering: No numeric data
,09-01 10:59:31.339  7261  7261 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-01 10:59:31.339  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:31.339  1015  1124 D SecContentProvider2: mCursor = null
,09-01 10:59:31.339  7261  7261 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-01 10:59:31.339  7261  7261 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 10:59:31.339  7261  7261 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,09-01 10:59:31.339  7261  7261 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=],
,09-01 10:59:31.339  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
,09-01 10:59:31.349  1015  1121 V NetworkStats: performPollLocked(flags=0x1),
09-01 10:59:31.339  1015  1129 D Tethering: clearTetheredNotification()
09-01 10:59:31.349  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-01 10:59:31.349  7261  7261 I wpa_supplicant: Blacklist: Clear (temp) 
09-01 10:59:31.349  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 10:59:31.349  7261  7261 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-01 10:59:31.349  1176  1176 D HotspotTile: updateTetherState():false, false
09-01 10:59:31.349  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:31.349  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-01 10:59:31.349  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
09-01 10:59:31.349  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:31.349  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-01 10:59:31.349  1015  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
09-01 10:59:31.359  1015  1121 V NetworkStats: performPollLocked() took 10ms
09-01 10:59:31.359  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:31.359  1015  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,09-01 10:59:31.359  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 10:59:31.359  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:31.359  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.359  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.359  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.359  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:31.369  1015  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-01 10:59:31.369  1015  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-01 10:59:31.369  1015  1126 E ConnectivityService: updateNetworkInfo()
09-01 10:59:31.369  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-01 10:59:31.369  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 10:59:31.369  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:31.369  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:31.369  1015  1481 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 10:59:31.369  1015  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:31.369  1015  1481 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:31.369  1015  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:31.369  1015  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:31.369  1627  1627 I Hs20UtilService: Starting #14
09-01 10:59:31.369  1627  1701 I Hs20UtilService: Message received 5007
,09-01 10:59:31.379  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-01 10:59:31.379  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-01 10:59:31.379  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:31.379  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 10:59:31.379  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-01 10:59:31.379  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 10:59:31.379  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-01 10:59:31.379  1300  2241 V NearbySettings: MountReceiver.mPrefHandler - 7002,
,09-01 10:59:31.389   278  1014 D CommandListener: Setting iface cfg
,09-01 10:59:31.389  1015  1124 E WifiStateMachine: Start Dhcp Watchdog 2
,09-01 10:59:31.399  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:31.399  1015  1124 D SecContentProvider2: mCursor = null
,09-01 10:59:31.409  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 10:59:31.409  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-01 10:59:31.409  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.409  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.409  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:31.409  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:31.419  1015  1124 E WifiNative-wlan0: do suspend false
,09-01 10:59:31.419  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
09-01 10:59:31.419  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:31.419  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
09-01 10:59:31.419  1015  1124 D SecContentProvider2: mCursor = null
,09-01 10:59:31.449  1015  1467 I ActivityManager: Killing 7021:com.sec.pcw.device/1000 (adj 15): empty #21
,09-01 10:59:31.499  1015  1028 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-01 10:59:31.499  1015  1028 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-01 10:59:31.499  1015  1028 D SecContentProvider2: mCursor = null
,09-01 10:59:31.499  1015  1028 D WifiService: setWifiEnabled: false pid=6726, uid=10171
,09-01 10:59:31.499  1015  1028 D SettingsProvider: name = wifi_on
,09-01 10:59:31.509  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 10:59:31.519  1015  1124 E WifiNative-wlan0: do suspend true
,09-01 10:59:31.539  1015  1123 D WifiP2pService: InactiveState{ what=143375 },
09-01 10:59:31.539  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:31.539  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
09-01 10:59:31.539  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:31.539  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.539  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.539  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.539  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.549   278  1014 D CommandListener: Clearing all IP addresses on wlan0
,09-01 10:59:31.549  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-01 10:59:31.549  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-01 10:59:31.549   278  1014 E Netd    : no such netId 503
09-01 10:59:31.549  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0,
09-01 10:59:31.549  1015  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-01 10:59:31.549  1015  1123 D WifiP2pService: InactiveState{ what=131204 }
09-01 10:59:31.549  1015  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-01 10:59:31.549  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-01 10:59:31.559  1015  1126 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '78 network destroy 503' failed with '400 78 destroyNetwork() failed (Machine is not on the network)'
,09-01 10:59:31.559  1015  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-01 10:59:31.559  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-01 10:59:31.559  1015  1126 V NetworkStats: updateIfacesLocked()
09-01 10:59:31.559  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
09-01 10:59:31.559  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:31.559  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:31.559  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 10:59:31.559  1015  1126 V NetworkStats: performPollLocked() took 4ms
,09-01 10:59:31.559  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:31.569  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 10:59:31.569  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-01 10:59:31.569  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.569  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.569  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.569  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:31.569  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
,09-01 10:59:31.569  1015  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 10:59:31.569  1015  1015 D RttService: SCAN_AVAILABLE : 1
,09-01 10:59:31.579  1015  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 10:59:31.579  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-01 10:59:31.579  1015  1045 D WifiDisplayAdapter: onP2pDisconnected,
09-01 10:59:31.579  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:31.579  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-01 10:59:31.579  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-01 10:59:31.579  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-01 10:59:31.579  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:31.579  1015  1462 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-01 10:59:31.579  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-01 10:59:31.589  1015  7324 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:31.589  1015  7324 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-01 10:59:31.589  1015  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,09-01 10:59:31.589  1015  1126 D ConnectivityService: nai.networkMonitor.doQuit()
09-01 10:59:31.589  1015  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-01 10:59:31.589  1015  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-01 10:59:31.589  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
09-01 10:59:31.589  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:31.589  1015  1126 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-01 10:59:31.589  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:31.589  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-01 10:59:31.589  1015  1126 E ConnectivityService: updateNetworkInfo()
09-01 10:59:31.589  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-01 10:59:31.589  1015  1126 E ConnectivityService: updateNetworkInfo()
09-01 10:59:31.589  1015  1045 D WifiDisplayController: disconnect
09-01 10:59:31.589  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-01 10:59:31.589  1015  1045 D WifiDisplayController: updateConnection
09-01 10:59:31.589  1627  1627 I Hs20UtilService: Starting #15
,09-01 10:59:31.589  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 10:59:31.589  1627  1701 I Hs20UtilService: Message received 5007
09-01 10:59:31.589  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-01 10:59:31.589  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-01 10:59:31.589  1015  1467 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-01 10:59:31.589  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-01 10:59:31.599  1015  1123 D WifiP2pService: P2pDisablingState,
,09-01 10:59:31.599  1015  1124 E WifiNative-wlan0: do suspend true
09-01 10:59:31.599  1015  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
09-01 10:59:31.599  1015  1123 D WifiP2pService: p2p socket connection lost
09-01 10:59:31.599  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-01 10:59:31.599  1015  1123 D WifiP2pService: P2pDisabledState
,09-01 10:59:31.599  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:31.599  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 10:59:31.599  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-01 10:59:31.599  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
,09-01 10:59:31.599  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-01 10:59:31.599  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-01 10:59:31.609  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-01 10:59:31.609  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 10:59:31.609  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-01 10:59:31.609  1300  2241 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 10:59:31.619  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-01 10:59:31.619  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:31.619  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 10:59:31.619  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-01 10:59:31.619  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 10:59:31.619  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-01 10:59:31.619  1300  2241 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 10:59:31.619  6990  6990 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 10:59:31.619  6990  6990 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-01 10:59:31.619  6990  6990 D FileShare-Client: Outbound.stopDelayTimer - 
,09-01 10:59:31.629  1015  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-01 10:59:31.629  1015  1123 D WifiP2pService: DefaultState{ what=143375 }
,09-01 10:59:31.629   278  1014 D CommandListener: Clearing all IP addresses on wlan0
,09-01 10:59:31.639  7329  7329 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-01 10:59:31.639  7261  7261 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-01 10:59:31.639  7329  7329 I dhcpcd  : version 5.5.6 starting
,09-01 10:59:31.639  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 10:59:31.639  7329  7329 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
09-01 10:59:31.639  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-01 10:59:31.639  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-01 10:59:31.639  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.639  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.639  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.639  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:31.649  7005  7005 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 10:59:31.649  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:31.649  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:31.649  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.649  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.649  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.649  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:31.659  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:31.659  1015  1124 D SecContentProvider2: mCursor = null
,09-01 10:59:31.659  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:31.659  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 10:59:31.659  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-01 10:59:31.659  1176  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-01 10:59:31.659  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.659  1176  1176 D HotspotTile: onReceive : 0, 0
09-01 10:59:31.659  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:31.659  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.659  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:31.659  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 10:59:31.659  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-01 10:59:31.659  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
09-01 10:59:31.659  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:31.659  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:31.659  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:31.659  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:31.659  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:31.659  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:31.659  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
09-01 10:59:31.659  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:31.659  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:31.659  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:31.659  6726  6726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:31.669  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:31.669  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:31.669  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:31.669  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:31.669  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:31.669  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:31.669  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:31.669  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,09-01 10:59:31.669  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:31.669  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:31.669  6726  6726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:31.679  1015  1319 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-01 10:59:31.679  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-01 10:59:31.679  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:31.679  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:31.679  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 10:59:31.679  1627  1627 I Hs20UtilService: Starting #16
,09-01 10:59:31.679  1627  1701 I Hs20UtilService: Message received 5007
,09-01 10:59:31.689  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-01 10:59:31.689  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:31.689  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 10:59:31.689  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 10:59:31.689  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 10:59:31.689  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-01 10:59:31.689  1300  2241 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 10:59:31.689  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-01 10:59:31.689  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-01 10:59:31.699  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:31.699  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:31.699  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 10:59:31.699  1627  1627 I Hs20UtilService: Starting #17
09-01 10:59:31.699  1627  1701 I Hs20UtilService: Message received 5011
,09-01 10:59:31.699  6553  6553 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-01 10:59:31.699  6553  6553 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-01 10:59:31.699  6553  6553 D SecurityLogAgent: StateMachine : Current State = 1
09-01 10:59:31.699  6553  6553 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 10:59:31.719  7329  7329 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-01 10:59:31.719  7329  7329 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-01 10:59:31.719  7329  7329 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-01 10:59:31.719  7329  7329 I dhcpcd  : bssid match,
09-01 10:59:31.719  7329  7329 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,09-01 10:59:31.769  7261  7261 I wpa_supplicant: Blacklist: Clear (all) ,
,09-01 10:59:31.779  7329  7329 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,09-01 10:59:31.809  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
09-01 10:59:31.809  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 10:59:31.809  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
09-01 10:59:31.809  7261  7261 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,09-01 10:59:31.839  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-01 10:59:31.839  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:31.839  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-01 10:59:31.839  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:31.839  1015  1129 D Tethering: InitialState.processMessage what=4,
,09-01 10:59:31.839  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:31.849  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-01 10:59:31.839  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-01 10:59:31.849  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 10:59:31.839  1015  1129 E Tethering: No numeric data
09-01 10:59:31.849  1176  1176 D HotspotTile: updateTetherState():false, false
,09-01 10:59:31.839  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-01 10:59:31.849  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:31.839  1015  1129 D Tethering: clearTetheredNotification()
09-01 10:59:31.839  7261  7261 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-01 10:59:31.839  7261  7261 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-01 10:59:31.839  7261  7261 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,09-01 10:59:31.849  7261  7261 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-01 10:59:31.849  7261  7261 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-01 10:59:31.849  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:31.849  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:31.849  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-01 10:59:31.849  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:31.849  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:31.859  1015  1121 V NetworkStats: performPollLocked() took 8ms
,09-01 10:59:31.859  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:31.859  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:31.859  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:31.899  7329  7329 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,09-01 10:59:32.019  7261  7261 I wpa_supplicant: Blacklist: Clear (all) 
,09-01 10:59:32.139  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 10:59:32.139  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:32.139  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-01 10:59:32.139  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:32.139  7261  7261 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-01 10:59:32.139  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:32.139  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:32.149  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
09-01 10:59:32.149  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-01 10:59:32.149  6952  6952 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 10:59:32.159  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 10:59:32.159  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-01 10:59:32.159  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:32.159  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:32.159  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:32.159  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:32.159  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:32.159  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-01 10:59:32.159  1176  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-01 10:59:32.169  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
09-01 10:59:32.169  1176  1176 D HotspotTile: onReceive : 1, 0
,09-01 10:59:32.169  1937  2165 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 10:59:32.169  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-01 10:59:32.169  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:32.179  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:32.179  1015  1467 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-01 10:59:32.179  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:32.179  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:32.179  1015  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:32.179  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:32.189  6553  6553 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-01 10:59:32.189  1627  1627 I Hs20UtilService: Starting #18
,09-01 10:59:32.189  1627  1701 I Hs20UtilService: Message received 5011
,09-01 10:59:32.189  6553  6553 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-01 10:59:32.189  6553  6553 D SecurityLogAgent: StateMachine : Current State = 1
,09-01 10:59:32.189  6553  6553 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 10:59:32.859   278  1008 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-01 10:59:32.859  1015  1042 D Tethering: interfaceRemoved wlan0
,09-01 10:59:32.859  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-01 10:59:33.059  1015  1042 D Tethering: interfaceRemoved p2p0
,09-01 10:59:33.059  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-01 10:59:33.689  1015  3326 D SSRM:n  : SIOP:: AP = 340
,09-01 10:59:33.919  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
,09-01 10:59:34.049   288   288 E SMD     : DCD OFF
,09-01 10:59:34.509  6726  6780 D BluetoothAdapter: enable(),
,09-01 10:59:34.509  1015  1322 W ActivityManager: Permission Denial: getCurrentUser() from pid=6726, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,09-01 10:59:34.519  1015  1322 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
09-01 10:59:34.519  1015  1322 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6726, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-01 10:59:34.519  1015  1322 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-01 10:59:34.519  1015  1322 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
,09-01 10:59:34.519  1015  1322 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-01 10:59:34.519  1015  1322 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-01 10:59:34.519  1015  1322 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446),
,09-01 10:59:34.519  1015  1322 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-01 10:59:34.519  1015  1322 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 10:59:34.519  1015  1322 D SettingsProvider: name = bluetooth_on,
,09-01 10:59:34.529  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-01 10:59:34.529  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 10:59:34.529  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
09-01 10:59:34.529  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-01 10:59:34.529  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-01 10:59:34.529  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:34.529  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:34.529  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:34.549  7358  7358 E Zygote  : MountEmulatedStorage(),
09-01 10:59:34.549  1015  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7358 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-01 10:59:34.549  7358  7358 E Zygote  : v2
09-01 10:59:34.549  7358  7358 I libpersona: KNOX_SDCARD checking this for 1002
,09-01 10:59:34.549  7358  7358 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:34.559  7358  7358 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:34.559  7358  7358 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-01 10:59:34.559  7358  7358 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:34.589  7358  7358 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 10:59:34.589  7358  7358 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:34.609  7358  7358 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-01 10:59:34.609  7358  7358 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-01 10:59:34.649  7358  7358 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-01 10:59:34.679  7358  7358 D BtSettings.ProfileConfig: Adding GattService
,09-01 10:59:34.689  7358  7358 D BtSettings.ProfileConfig: Adding HeadsetService
09-01 10:59:34.689  7358  7358 D BtSettings.ProfileConfig: Adding A2dpService
,09-01 10:59:34.689  7358  7358 D BtSettings.ProfileConfig: Adding HidService
09-01 10:59:34.689  7358  7358 D BtSettings.ProfileConfig: Adding HealthService
09-01 10:59:34.689  7358  7358 D BtSettings.ProfileConfig: Adding PanService
,09-01 10:59:34.689  7358  7358 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-01 10:59:34.689  7358  7358 D BtSettings.ProfileConfig: Adding SapService
09-01 10:59:34.689  7358  7358 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-01 10:59:34.689  7358  7358 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-01 10:59:34.689  7358  7358 D BtSettings.ProfileConfig: Adding SapClientService
,09-01 10:59:34.689  7358  7358 D BtSettings.ProfileConfig: Adding HidDevService
09-01 10:59:34.689  7358  7358 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-01 10:59:34.689  1015  1472 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService,
09-01 10:59:34.689  1015  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:34.689  1015  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:34.689  1015  1472 D SettingsProvider: selectionArgs: false
,09-01 10:59:34.689  1015  1472 D SettingsProvider: selectionArgs: 1002
09-01 10:59:34.689  1015  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:34.689  1015  1472 D SettingsProvider: ret = -1
09-01 10:59:34.689  1015  1319 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-01 10:59:34.689  1015  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:34.689  1015  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-01 10:59:34.689  1015  1319 D SettingsProvider: selectionArgs: false
09-01 10:59:34.689  1015  1319 D SettingsProvider: selectionArgs: 1002
09-01 10:59:34.689  1015  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:34.689  1015  1319 D SettingsProvider: ret = -1
09-01 10:59:34.689  1015  1134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-01 10:59:34.689  1015  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:34.689  1015  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-01 10:59:34.689  1015  1134 D SettingsProvider: selectionArgs: false
09-01 10:59:34.689  1015  1134 D SettingsProvider: selectionArgs: 1002
09-01 10:59:34.689  1015  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:34.689  1015  1134 D SettingsProvider: ret = -1
,09-01 10:59:34.689  1015  1462 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,09-01 10:59:34.689  1015  1462 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:34.689  1015  1462 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:34.689  1015  1462 D SettingsProvider: selectionArgs: false
09-01 10:59:34.689  1015  1462 D SettingsProvider: selectionArgs: 1002
09-01 10:59:34.689  1015  1462 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:34.689  1015  1462 D SettingsProvider: ret = -1
,09-01 10:59:34.699  1015  1473 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-01 10:59:34.699  1015  1473 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:34.699  1015  1473 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:34.699  1015  1473 D SettingsProvider: selectionArgs: false
09-01 10:59:34.699  1015  1473 D SettingsProvider: selectionArgs: 1002
,09-01 10:59:34.699  1015  1473 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:34.699  1015  1473 D SettingsProvider: ret = -1
09-01 10:59:34.699  1015  1322 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-01 10:59:34.699  1015  1322 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:34.699  1015  1322 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-01 10:59:34.699  1015  1322 D SettingsProvider: selectionArgs: false
09-01 10:59:34.699  1015  1322 D SettingsProvider: selectionArgs: 1002
09-01 10:59:34.699  1015  1322 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:34.699  1015  1322 D SettingsProvider: ret = -1
09-01 10:59:34.699  1015  1467 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-01 10:59:34.699  1015  1467 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-01 10:59:34.699  1015  1467 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:34.699  1015  1467 D SettingsProvider: selectionArgs: false
,09-01 10:59:34.699  1015  1467 D SettingsProvider: selectionArgs: 1002,
09-01 10:59:34.699  1015  1467 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
09-01 10:59:34.699  1015  1467 D SettingsProvider: ret = -1,
09-01 10:59:34.699  1015  1028 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-01 10:59:34.699  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:34.699  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:34.699  1015  1028 D SettingsProvider: selectionArgs: false
09-01 10:59:34.699  1015  1028 D SettingsProvider: selectionArgs: 1002
,09-01 10:59:34.699  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:34.699  1015  1028 D SettingsProvider: ret = -1
09-01 10:59:34.699  1015  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:34.699  1015  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:34.699  1015  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:34.699  1015  1481 D SettingsProvider: selectionArgs: false,
,09-01 10:59:34.699  1015  1481 D SettingsProvider: selectionArgs: 1002
09-01 10:59:34.699  1015  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:34.699  1015  1481 D SettingsProvider: ret = -1
09-01 10:59:34.699  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:34.699  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-01 10:59:34.699  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:34.699  1015  1027 D SettingsProvider: selectionArgs: false
09-01 10:59:34.699  1015  1027 D SettingsProvider: selectionArgs: 1002
09-01 10:59:34.699  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:34.699  1015  1027 D SettingsProvider: ret = -1
09-01 10:59:34.699  1015  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-01 10:59:34.699  1015  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-01 10:59:34.699  1015  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:34.699  1015  1495 D SettingsProvider: selectionArgs: false,
09-01 10:59:34.699  1015  1495 D SettingsProvider: selectionArgs: 1002
09-01 10:59:34.699  1015  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:34.699  1015  1495 D SettingsProvider: ret = -1,
09-01 10:59:34.699  1015  1472 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-01 10:59:34.699  1015  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:34.699  1015  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-01 10:59:34.699  1015  1472 D SettingsProvider: selectionArgs: false
09-01 10:59:34.699  1015  1472 D SettingsProvider: selectionArgs: 1002
09-01 10:59:34.699  1015  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:34.699  1015  1472 D SettingsProvider: ret = -1
,09-01 10:59:34.719  7358  7358 D BluetoothAdapterState: make
,09-01 10:59:34.729  7358  7358 I bluedroid: init
,09-01 10:59:34.729  7358  7373 I BluetoothAdapterState: Entering OffState
,09-01 10:59:34.729  7358  7358 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
,09-01 10:59:34.729  7358  7358 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-01 10:59:34.729  7358  7358 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-01 10:59:34.729  7358  7358 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-01 10:59:34.739  7358  7358 E bt-btif : btif_fetch_local_ble_random_bdaddr,
09-01 10:59:34.739  7358  7358 I bluedroid: get_profile_interface socket
09-01 10:59:34.739  7358  7358 I bluedroid: get_profile_interface map_client
09-01 10:59:34.739  7358  7376 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-01 10:59:34.739  7358  7358 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,09-01 10:59:34.739  7358  7376 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-01 10:59:34.739  7358  7376 E BluetoothServiceJni: populateRssiValuesNative
09-01 10:59:34.739  7358  7376 I bluedroid: getModelRssiValues
,09-01 10:59:34.739  7358  7376 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-01 10:59:34.739  7358  7376 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-01 10:59:34.749  1015  1015 D SettingsProvider: name = bluetooth_name
,09-01 10:59:34.749  7358  7376 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-01 10:59:34.749  7358  7358 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:34.749  1015  1319 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-01 10:59:34.749  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 10:59:34.749  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:34.749  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:34.749  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:34.759  7358  7366 I bluedroid: config_hci_snoop_log
,09-01 10:59:34.759  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-01 10:59:34.759  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,09-01 10:59:34.759  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-01 10:59:34.759  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-01 10:59:34.759  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-01 10:59:34.769  7358  7358 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-01 10:59:34.769  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 10:59:34.769  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 10:59:34.779  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-01 10:59:34.779  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-01 10:59:34.779  7358  7373 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-01 10:59:34.779  7358  7373 D BluetoothAdapterProperties: Setting state to 11
,09-01 10:59:34.779  7358  7373 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-01 10:59:34.779  7358  7373 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 10:59:34.779  7358  7373 D BluetoothAdapterService: updateAdapterState state is 11
,09-01 10:59:34.779  7358  7373 D BluetoothAdapterService: Autoconnection is available 
09-01 10:59:34.779  7358  7373 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-01 10:59:34.789  7358  7373 D BluetoothSecureManager: getInstant: null
09-01 10:59:34.789  7358  7373 D BluetoothSecureManager: calling getMethod for getService
,09-01 10:59:34.789  7358  7373 D BluetoothSecureManager: calling getService
,09-01 10:59:34.789  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:34.789  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,09-01 10:59:34.799  7358  7373 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3cec7b46
,09-01 10:59:34.799  1015  1481 D BluetoothSecureManagerService: isSecureModeEnabled
,09-01 10:59:34.799  1015  1481 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
09-01 10:59:34.799  7358  7373 D BtConfig.SecureMode: isSecureModeOn:false
09-01 10:59:34.799  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-01 10:59:34.799  7358  7373 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-01 10:59:34.799  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-01 10:59:34.809  7358  7373 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-01 10:59:34.809  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-01 10:59:34.809  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-01 10:59:34.809  7358  7373 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-01 10:59:34.809  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:34.809  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-01 10:59:34.809  1176  1176 D BluetoothTile:  getBluetoothState : 11
09-01 10:59:34.809  7358  7373 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-01 10:59:34.809  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-01 10:59:34.809  7358  7373 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-01 10:59:34.809  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-01 10:59:34.809  7358  7373 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-01 10:59:34.809  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-01 10:59:34.809  7358  7373 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-01 10:59:34.809  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-01 10:59:34.809  7358  7373 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-01 10:59:34.809  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-01 10:59:34.809  7358  7373 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:34.809  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-01 10:59:34.809  7358  7373 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:34.809  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-01 10:59:34.819  1874  1874 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-01 10:59:34.819  7358  7373 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-01 10:59:34.819  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-01 10:59:34.819  1176  1729 D BluetoothTile:  handleUpdatestate:false name:null
09-01 10:59:34.819  1176  1729 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-01 10:59:34.819  7358  7373 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-01 10:59:34.829  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:34.829  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:34.829  1015  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:34.829  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-01 10:59:34.829  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:34.829  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:34.829  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:34.839  1015  1481 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 10:59:34.839  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:34.839  1015  1472 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-01 10:59:34.849  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-01 10:59:34.849  7358  7373 D BluetoothBondStateMachine: make
,09-01 10:59:34.849  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 10:59:34.859  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
09-01 10:59:34.859  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-01 10:59:34.859  7358  7373 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService,
09-01 10:59:34.859  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:34.859  1015  1473 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:34.859  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
09-01 10:59:34.859  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-01 10:59:34.859  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:34.859  1015  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:34.859  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:34.859  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-01 10:59:34.859  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-01 10:59:34.859  7358  7373 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-01 10:59:34.859  7358  7358 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 10:59:34.859  7358  7358 D BtGatt.GattService: Received start request. Starting profile...,
09-01 10:59:34.859  7358  7358 D BtGatt.GattService: start(),
09-01 10:59:34.859  7358  7358 D BtGatt.GattService: start()
,09-01 10:59:34.859  7358  7358 I bluedroid: get_profile_interface gatt
09-01 10:59:34.859  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:34.859  7358  7358 D BtGatt.AdvertiseManager: advertise manager created
,09-01 10:59:34.869  7358  7379 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-01 10:59:34.869  1015  1462 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-01 10:59:34.869  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:34.869  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:34.869  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:34.869  1015  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:34.889  7381  7381 E Zygote  : MountEmulatedStorage()
,09-01 10:59:34.889  7381  7381 E Zygote  : v2
09-01 10:59:34.889  7381  7381 I libpersona: KNOX_SDCARD checking this for 10055
09-01 10:59:34.889  7381  7381 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:34.889  1015  1462 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7381 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-01 10:59:34.889  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:34.889  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-01 10:59:34.889  1015  1028 W ActivityManager: userId = 0, bbcId = -10000,
09-01 10:59:34.889  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:34.889  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
09-01 10:59:34.889  7381  7381 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 10:59:34.889  7381  7381 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:34.889  7381  7381 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:34.899  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-01 10:59:34.899  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-01 10:59:34.899  7358  7373 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-01 10:59:34.899  1015  1322 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:34.899  1015  1322 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 10:59:34.899  1015  1322 W ActivityManager: userId = 0, bbcId = -10000,
09-01 10:59:34.899  1015  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:34.899  1015  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:34.899  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-01 10:59:34.899  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-01 10:59:34.899  7358  7373 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-01 10:59:34.899  1015  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:34.899  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-01 10:59:34.909  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:34.909  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:34.909  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:34.909  7358  7358 D BtGatt.GattService: mStartError = false
09-01 10:59:34.909  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:34.909  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-01 10:59:34.909  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-01 10:59:34.909  7358  7373 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-01 10:59:34.909  1015  1322 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-01 10:59:34.909  7358  7358 D HeadsetService: Received start request. Starting profile...
09-01 10:59:34.909  1015  1322 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-01 10:59:34.909  7358  7358 D HeadsetService: start()
,09-01 10:59:34.909  1015  1322 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:34.909  1015  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:34.909  1015  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:34.909  7358  7358 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 10:59:34.909  7358  7358 D HeadsetStateMachine: make
,09-01 10:59:34.919  7358  7358 E HeadsetStateMachine: # of Max HF connection is 2
,09-01 10:59:34.919  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-01 10:59:34.919  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-01 10:59:34.919  7358  7373 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-01 10:59:34.919  1015  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:34.919  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-01 10:59:34.919  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:34.919  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:34.919  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:34.929  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-01 10:59:34.929  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:34.929  7358  7373 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-01 10:59:34.929  1015  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:34.929  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-01 10:59:34.929  1015  1319 W ActivityManager: userId = 0, bbcId = -10000,
09-01 10:59:34.929  1015  1472 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-01 10:59:34.929  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-01 10:59:34.929  1015  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
09-01 10:59:34.929  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:34.929  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:34.929  1015  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:34.929  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-01 10:59:34.929  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-01 10:59:34.929  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-01 10:59:34.929  7358  7373 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-01 10:59:34.939  1015  1472 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:34.939  1015  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-01 10:59:34.939  7381  7381 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:34.939  7381  7381 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:34.939  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:34.939  1015  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:34.939  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:34.939  1015  1473 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-01 10:59:34.939  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-01 10:59:34.939  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:34.939  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:34.939  7358  7373 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:34.939  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:34.939  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:34.939  7358  7373 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:34.939  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-01 10:59:34.939  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-01 10:59:34.939  7358  7373 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-01 10:59:34.939  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-01 10:59:34.939  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-01 10:59:34.939  7358  7373 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-01 10:59:34.939  7358  7373 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-01 10:59:34.949  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:34.949  1015  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:34.949  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-01 10:59:34.949  7358  7358 I bluedroid: get_profile_interface handsfree
,09-01 10:59:34.969  7358  7358 I DualScoManager: Instantiating Dual Sco Manager
,09-01 10:59:34.969  7358  7358 I DualScoManager: Set HeadsetServiceHelper
,09-01 10:59:34.969  7358  7358 D BluetoothAtMessage: createCMTIContentObservers
,09-01 10:59:34.969  1015  1473 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-01 10:59:34.969  1015  1473 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:34.969  1015  1473 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:34.969  1015  1473 D SettingsProvider: selectionArgs: false
,09-01 10:59:34.969  1015  1473 D SettingsProvider: selectionArgs: 1002
09-01 10:59:34.969  1015  1473 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:34.969  1015  1473 D SettingsProvider: ret = -1
,09-01 10:59:34.969  7358  7391 D HeadsetStateMachine: Enter Disconnected: -2
,09-01 10:59:34.969  7358  7358 D HeadsetService: mStartError = false
,09-01 10:59:34.969  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:34.979  7381  7381 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-01 10:59:34.979  7358  7358 D A2dpService: Received start request. Starting profile...
09-01 10:59:34.979  7358  7358 D A2dpService: start()
,09-01 10:59:34.979  7358  7391 D HeadsetStateMachine: Clear mHeadsetBrsf
09-01 10:59:34.979  7358  7391 D HeadsetStateMachine: map size, before remove : 0
,09-01 10:59:34.979  7358  7391 D HeadsetStateMachine: map size, after remove: 0
09-01 10:59:34.979  7358  7358 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-01 10:59:34.979  7358  7358 I bluedroid: get_profile_interface avrcp
,09-01 10:59:34.989  7358  7358 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-01 10:59:34.989  7358  7358 D Avrcp   : Initialize Media Controller
09-01 10:59:34.989  7358  7358 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-01 10:59:34.989  7358  7358 E Avrcp   : getActiveSessions
,09-01 10:59:34.989  7358  7358 D Avrcp   : pick active media Controller
,09-01 10:59:34.989  7358  7358 D Avrcp   : Get the active Media Controller 
,09-01 10:59:34.999  7358  7358 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-01 10:59:34.999  7358  7401 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-01 10:59:35.009  7381  7381 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
09-01 10:59:35.009  7358  7358 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 10:59:35.009  7358  7358 D A2dpStateMachine: make
,09-01 10:59:35.009  7381  7381 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-01 10:59:35.009  7381  7381 D UserAnalysis: Create SecureDbHelper
,09-01 10:59:35.009  7358  7358 I bluedroid: get_profile_interface a2dp
,09-01 10:59:35.009  7358  7403 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-01 10:59:35.009  7358  7358 E bt-btif : warning : media task started media_task_refcnt 1 
,09-01 10:59:35.019  7358  7358 D A2dpService: mStartError = false
,09-01 10:59:35.019  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:35.019  7358  7358 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
09-01 10:59:35.019  7358  7402 D A2dpStateMachine: Enter Disconnected: -2
,09-01 10:59:35.019  7358  7358 I BluetoothHidServiceJni: classInitNative: succeeds
,09-01 10:59:35.019  7381  7381 D IntelligenceServiceApplication: onCreate()
,09-01 10:59:35.019  7358  7358 D HidService: Received start request. Starting profile...
09-01 10:59:35.019  7358  7358 D HidService: start()
09-01 10:59:35.019  7358  7358 I bluedroid: get_profile_interface hidhost
09-01 10:59:35.019  7358  7358 D HidService: setHidService(): set to: null
09-01 10:59:35.019  7358  7358 D HidService: mStartError = false
09-01 10:59:35.019  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:35.019  7358  7358 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-01 10:59:35.019  7358  7358 D HealthService: Received start request. Starting profile...
09-01 10:59:35.019  1015  1319 I ActivityManager: Killing 7038:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
09-01 10:59:35.019  7358  7358 D HealthService: start()
09-01 10:59:35.019  7358  7358 I bluedroid: get_profile_interface health
09-01 10:59:35.019  7358  7358 D HealthService: mStartError = false
09-01 10:59:35.019  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
09-01 10:59:35.019  7358  7358 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-01 10:59:35.029  7358  7358 D PanService: Received start request. Starting profile...
09-01 10:59:35.029  7358  7358 D PanService: start()
09-01 10:59:35.029  7358  7358 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 10:59:35.029  7358  7358 I bluedroid: get_profile_interface pan
,09-01 10:59:35.029  7358  7358 D PanService: mStartError = false
09-01 10:59:35.029  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:35.029  7381  7381 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-01 10:59:35.029  7358  7358 D BluetoothMapService: Received start request. Starting profile...
09-01 10:59:35.029  7358  7358 D BluetoothMapService: start()
,09-01 10:59:35.029  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-01 10:59:35.029  7358  7401 D BluetoothMediaBrowser: no now playing list
09-01 10:59:35.029  7358  7401 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-01 10:59:35.029  7358  7358 D BluetoothMapService: mStartError = false
09-01 10:59:35.029  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
09-01 10:59:35.039  7358  7358 D HeadsetStateMachine: Try to query the phonestate on bind
,09-01 10:59:35.039  7381  7381 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-01 10:59:35.039  1422  6918 I Telecom : BluetoothPhoneService: queryPhoneState
,09-01 10:59:35.039  1422  1422 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-01 10:59:35.039  1422  1422 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-01 10:59:35.039  1422  6918 I Telecom : BluetoothPhoneService: Result of Message : true
,09-01 10:59:35.039  7358  7358 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-01 10:59:35.039  7358  7358 D SapService: Received start request. Starting profile...
09-01 10:59:35.039  7358  7358 D SapService: start()
09-01 10:59:35.039  7358  7358 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-01 10:59:35.039  7358  7358 I bluedroid: get_profile_interface sap
09-01 10:59:35.039  7358  7358 D SapService: mStartError = false
09-01 10:59:35.039  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
09-01 10:59:35.039  7358  7358 D HeadsetStateMachine: Proxy object connected
,09-01 10:59:35.039  7358  7358 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-01 10:59:35.039  7358  7358 D HeadsetPhoneState: sendDeviceDataStateChanged
09-01 10:59:35.039  7358  7358 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-01 10:59:35.039  7358  7358 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-01 10:59:35.039  7358  7358 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-01 10:59:35.039  7358  7358 D BluetoothA2dp: Proxy object connected
09-01 10:59:35.039  7358  7358 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-01 10:59:35.039  7358  7358 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-01 10:59:35.039  7358  7358 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-01 10:59:35.039  7358  7358 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,09-01 10:59:35.039  7358  7391 D HeadsetStateMachine: Disconnected process message: 11
,09-01 10:59:35.039  7358  7391 D HeadsetStateMachine: Disconnected process message: 18
09-01 10:59:35.039  7358  7358 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
09-01 10:59:35.039  7381  7381 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
09-01 10:59:35.039  7358  7391 D HeadsetStateMachine: Disconnected process message: 10
,09-01 10:59:35.049  7358  7391 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-01 10:59:35.049  7358  7391 D HeadsetStateMachine: Disconnected process message: 11
,09-01 10:59:35.049  1015  1467 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-01 10:59:35.049  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:35.049  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:35.049  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:35.049  1015  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:35.059  7408  7408 E Zygote  : MountEmulatedStorage()
,09-01 10:59:35.059  7408  7408 E Zygote  : v2
09-01 10:59:35.059  7408  7408 I libpersona: KNOX_SDCARD checking this for 10105
09-01 10:59:35.059  7408  7408 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:35.059  1015  1467 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7408 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-01 10:59:35.069  7408  7408 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:35.069  7408  7408 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-01 10:59:35.069  7408  7408 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-01 10:59:35.089   307   307 I art     : Explicit concurrent mark sweep GC freed 8674(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 25.634ms
,09-01 10:59:35.089  7358  7358 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-01 10:59:35.089  7358  7358 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-01 10:59:35.099  7358  7373 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-01 10:59:35.099  7358  7373 I bluedroid: enable
,09-01 10:59:35.099  7358  7373 I bt_hci_bdroid: init
,09-01 10:59:35.099  7358  7420 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-01 10:59:35.099  7358  7373 I bt_vendor: bt-vendor : init
09-01 10:59:35.099  7358  7373 I bt_vendor: bt-vendor : get_bt_soc_type
09-01 10:59:35.099  7358  7373 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-01 10:59:35.099  7358  7373 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
09-01 10:59:35.099  7358  7373 D bt_userial_mct: userial_init
,09-01 10:59:35.099  7358  7373 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-01 10:59:35.099  7358  7373 I bt_vendor: Starting hciattach daemon
09-01 10:59:35.099  7358  7373 I bt_vendor: try to set false
,09-01 10:59:35.099  7358  7373 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-01 10:59:35.099  7358  7373 I bt_vendor: Starting hciattach daemon
09-01 10:59:35.099  7358  7373 I bt_vendor: try to set true
,09-01 10:59:35.109   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 660us total 16.446ms
,09-01 10:59:35.119  7426  7426 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
09-01 10:59:35.119   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.423ms
,09-01 10:59:35.129  7408  7408 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:35.129  7408  7408 D ActivityThread: Added TimaKeyStore provider,
,09-01 10:59:35.169  7434  7434 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-01 10:59:35.179  7435  7435 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-01 10:59:35.199  7437  7437 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-01 10:59:35.209  7438  7438 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-01 10:59:35.219  7439  7439 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-01 10:59:35.229  7440  7440 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-01 10:59:35.299   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-01 10:59:35.299   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:35.299  7408  7446 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-01 10:59:35.299   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/,
09-01 10:59:35.299   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:35.309  7408  7446 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-01 10:59:35.469  7408  7408 D StrictMode: StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.io.File.exists(File.java:363)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-01 10:59:35.469  7408  7408 D StrictMode: StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:35.469  7408  7408 D StrictMode: StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:35.469  7408  7408 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.q.e.b(PG:170)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09,-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:35.469  7408  7408 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.q.k.d(PG:583)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.q.e.b(PG:170)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:35.469  7408  7408 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.io.File.exists(File.java:363)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:35.469  7408  7408 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.io.File.exists(File.java:363)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:35.469  7408  7408 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:35.469  7408  7408 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:35.469  1015  1027 I ActivityManager: Killing 7052:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
09-01 10:59:35.479  1937  1937 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-01 10:59:35.479  1937  1937 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-01 10:59:35.489  7457  7457 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
09-01 10:59:35.499  7458  7458 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-01 10:59:35.509  7358  7373 I bt_vendor: bluetooth satus is on
09-01 10:59:35.509  7358  7423 D bt_userial_mct: userial_open(port:0)
09-01 10:59:35.509  7358  7423 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-01 10:59:35.509  7358  7423 I bt_vendor: Done intiailizing UART
09-01 10:59:35.519  7358  7423 I bt_vendor: Done intiailizing UART
09-01 10:59:35.519  7358  7423 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
09-01 10:59:35.519  7358  7423 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-01 10:59:35.519  7358  7460 D bt_userial_mct: Entering userial_read_thread()
09-01 10:59:35.519  7358  7420 I         : BTE_InitTraceLevels -- TRC_HCI
09-01 10:59:35.519  7358  7420 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-01 10:59:35.519  7358  7420 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-01 10:59:35.519  7358  7420 I         : BTE_InitTraceLevels -- TRC_AVDT
09-01 10:59:35.519  7358  7420 I         : BTE_InitTraceLevels -- TRC_AVRC
09-01 10:59:35.519  7358  7420 I         : BTE_InitTraceLevels -- TRC_A2D
09-01 10:59:35.519  7358  7420 I         : BTE_InitTraceLevels -- TRC_BNEP
09-01 10:59:35.519  7358  7420 I         : BTE_InitTraceLevels -- TRC_BTM
09-01 10:59:35.519  7358  7420 I         : BTE_InitTraceLevels -- TRC_GAP
09-01 10:59:35.519  7358  7420 I         : BTE_InitTraceLevels -- TRC_PAN
09-01 10:59:35.519  7358  7420 I         : BTE_InitTraceLevels -- TRC_SAP
09-01 10:59:35.519  7358  7420 I         : BTE_InitTraceLevels -- TRC_SDP
09-01 10:59:35.519  7358  7420 I         : BTE_InitTraceLevels -- TRC_GATT
09-01 10:59:35.519  7358  7420 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 10:59:35.519  7358  7420 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-01 10:59:35.519  7358  7420 I         : BTE_InitTraceLevels -- TRC_BTIF
09-01 10:59:35.519  7358  7420 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
09-01 10:59:35.539  7408  7450 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-01 10:59:35.609  7358  7420 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-01 10:59:35.619  7358  7420 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4304ed1 
,09-01 10:59:35.619  7358  7420 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4304ed1 
,09-01 10:59:35.629  7358  7376 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-01 10:59:35.629  7358  7376 E bt-btif : Calling BTA_HhEnable
,09-01 10:59:35.629  7358  7376 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-01 10:59:35.639  7358  7376 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-01 10:59:35.639  7358  7376 E BluetoothServiceJni: populateRssiValuesNative
,09-01 10:59:35.639  7358  7376 I bluedroid: getModelRssiValues
09-01 10:59:35.639  7358  7376 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-01 10:59:35.639  7358  7376 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-01 10:59:35.709  1015  1322 I art     : Explicit concurrent mark sweep GC freed 100208(5MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 24MB/36MB, paused 2.435ms total 155.148ms
,09-01 10:59:35.709  1015  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:35.709  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:35.709  1015  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:35.709  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-01 10:59:35.709  7358  7376 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-01 10:59:35.719  1015  1015 D SettingsProvider: name = bluetooth_name
,09-01 10:59:35.719  7358  7376 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-01 10:59:35.719  7358  7376 D BluetoothAdapterProperties: Scan Mode:20
09-01 10:59:35.719  7358  7376 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 10:59:35.719  7358  7376 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
09-01 10:59:35.719  7358  7376 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-01 10:59:35.719  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:35.719  7358  7376 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-01 10:59:35.719  7358  7376 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-01 10:59:35.719  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:35.719  7358  7460 E bt_mct  : hci lib postload completed
09-01 10:59:35.719  7358  7376 E bt-btif : btif_sock_init: !vhci_init
,09-01 10:59:35.719  7358  7376 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-01 10:59:35.719  7358  7376 D IOP_DB_BT: db_open: db_open : handle 3028615184l, read 13894 bytes onto local cache
09-01 10:59:35.719  7358  7376 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-01 10:59:35.719  7358  7376 D IOP_DB_BT: db_query: result 1
09-01 10:59:35.719  7358  7376 I         : iop_db_open: iop_db_open status 0
,09-01 10:59:35.729  7358  7376 D bte_conf: Device ID record 1 : primary
09-01 10:59:35.729  7358  7376 D bte_conf:   vendorId            = 0075
09-01 10:59:35.729  7358  7376 D bte_conf:   vendorIdSource      = 0001
09-01 10:59:35.729  7358  7376 D bte_conf:   product             = 0100
09-01 10:59:35.729  7358  7376 D bte_conf:   version             = 0200
09-01 10:59:35.729  7358  7376 D bte_conf:   clientExecutableURL = 
09-01 10:59:35.729  7358  7376 D bte_conf:   serviceDescription  = 
09-01 10:59:35.729  7358  7376 D bte_conf:   documentationURL    = 
09-01 10:59:35.729  7358  7376 D bte_conf: bte_load_did_conf no section named DID2.
09-01 10:59:35.729  7358  7376 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-01 10:59:35.729  7358  7373 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-01 10:59:35.729  7358  7373 D BluetoothAdapterProperties: ScanMode =  20
09-01 10:59:35.729  7358  7373 D BluetoothAdapterProperties: State =  11
,09-01 10:59:35.729  1015  1134 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-01 10:59:35.729  7358  7373 D BluetoothAdapterProperties: Setting state to 12
,09-01 10:59:35.729  7358  7373 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-01 10:59:35.729  7358  7376 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-01 10:59:35.729  7358  7376 D BluetoothAdapterProperties: Scan Mode:21
09-01 10:59:35.729  7358  7376 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 10:59:35.739  1015  1028 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-01 10:59:35.739  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:35.739  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:35.739  1015  1028 D SettingsProvider: selectionArgs: false
09-01 10:59:35.739  1015  1028 D SettingsProvider: selectionArgs: 1002
09-01 10:59:35.739  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:35.739  1015  1028 D SettingsProvider: ret = -1
,09-01 10:59:35.739  7358  7373 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 10:59:35.739  7358  7373 D BluetoothAdapterService: updateAdapterState state is 12
,09-01 10:59:35.739  1015  1322 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:35.739  1015  1322 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-01 10:59:35.739  1015  1322 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:35.739  1015  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:35.739  1015  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:35.739  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:35.739  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:35.749  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:35.749  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:35.749  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:35.749  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:35.749  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:35.749  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:35.749  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:35.749  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:35.749  7358  7373 D BluetoothAdapterService: Autoconnection is available 
,09-01 10:59:35.749  7358  7373 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-01 10:59:35.749  7358  7373 D BluetoothAdapterService: starting service from this receiver
,09-01 10:59:35.749  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:35.749  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-01 10:59:35.749  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:35.749  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:35.749  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:35.749  1422  6918 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:35.749  7358  7373 I BluetoothAdapterState: Entering On State from state = 11
,09-01 10:59:35.749  6726  6726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:35.759  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:35.759  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:35.759  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:35.759  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:35.759  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:35.759  1422  6918 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:35.759  1300  1313 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 10:59:35.759  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:35.759  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:35.759  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:35.759  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:35.759  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:35.759  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:35.759  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:35.759  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:35.759  7358  7358 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
09-01 10:59:35.759  6726  6726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:35.759  1300  1313 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:35.759  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-01 10:59:35.759  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 10:59:35.769  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:35.769  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:35.769  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-01 10:59:35.769  6726  6736 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:35.769  6726  6736 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 10:59:35.769  7358  7366 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:35.769  7358  7366 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:35.769  1451  2463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:35.769  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:35.769  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:35.769  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:35.769  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:35.769  1300  1300 D BluetoothA2dp: Proxy object connected
,09-01 10:59:35.769  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
09-01 10:59:35.769  1451  2463 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:35.769  1300  1300 D A2dpProfile: Bluetooth service connected
,09-01 10:59:35.779  7358  7358 I BluetoothPbapService: Handler(): got msg=1
09-01 10:59:35.779  1439  6185 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:35.779  1439  6185 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:35.779  1176  1792 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 10:59:35.779  1176  1792 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:35.779  1015  1462 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-01 10:59:35.779  1300  1313 D Bluetoothsap: onBluetoothStateChange: up=true
,09-01 10:59:35.779  1300  1313 D Bluetoothsap: Binding service...
,09-01 10:59:35.779  1300  1313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
09-01 10:59:35.779  7358  7467 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-01 10:59:35.779  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-01 10:59:35.779  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-01 10:59:35.779  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:35.779  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:35.779  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-01 10:59:35.779  1300  1313 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-01 10:59:35.789  1300  1300 D Bluetoothsap: BluetoothSAP Proxy object connected
09-01 10:59:35.789  1300  1300 D SapProfile: Bluetooth service connected
,09-01 10:59:35.789  1300  1300 D Bluetoothsap: getConnectedDevices()
09-01 10:59:35.789  1422  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:35.789  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-01 10:59:35.789  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-01 10:59:35.789  7358  7467 D BluetoothSocket: bindListen(): myUserId = 0
,09-01 10:59:35.789  7358  7467 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 10:59:35.789  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:35.789  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:35.789  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:35.789  1422  1445 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:35.789  1300  1313 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:35.789  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-01 10:59:35.789  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:35.789  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:35.789  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:35.789  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:35.789  7358  7467 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-01 10:59:35.789  7358  7467 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 10:59:35.789  7358  7467 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 10:59:35.799  7358  7467 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e9e6efb
09-01 10:59:35.799  7358  7467 D BluetoothSocket: channel: 19
,09-01 10:59:35.799  7358  7467 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-01 10:59:35.799  1300  1300 D HeadsetProfile: Bluetooth service connected
,09-01 10:59:35.799  1300  1313 E BluetoothHeadset: BluetoothHeadset service is binded
09-01 10:59:35.799  1422  1438 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 10:59:35.799  1422  1438 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:35.799  1300  7466 D BluetoothMap: onBluetoothStateChange: up=true
,09-01 10:59:35.799  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-01 10:59:35.799  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-01 10:59:35.799  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:35.799  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:35.799  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:35.799  1300  1300 D BluetoothMap: Proxy object connected
,09-01 10:59:35.799  1300  1300 D MapProfile: Bluetooth service connected
09-01 10:59:35.799  1300  1300 D BluetoothMap: getConnectedDevices()
09-01 10:59:35.799  1300  1313 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-01 10:59:35.809  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-01 10:59:35.809  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-01 10:59:35.809  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:35.809  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:35.809  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:35.809  1300  1300 D BluetoothInputDevice: Proxy object connected
,09-01 10:59:35.809  1451  1867 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:35.809  1451  1867 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 10:59:35.809  1300  1300 D HidProfile: Bluetooth service connected
09-01 10:59:35.809  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-01 10:59:35.809  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:35.809  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:35.809  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
09-01 10:59:35.809  1300  7466 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:35.809  1300  7466 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 10:59:35.809  7408  7424 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:35.809  7408  7424 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:35.809  1422  6918 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:35.809  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:35.809  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:35.819  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:35.819  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:35.819  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-01 10:59:35.819  1422  6918 E BluetoothHeadset: BluetoothHeadset service is binded
09-01 10:59:35.819  1015  1044 D BluetoothPan: Binding service...
,09-01 10:59:35.819  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-01 10:59:35.819  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-01 10:59:35.819  1937  1956 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:35.819  1937  1956 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:35.819  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,09-01 10:59:35.819  1300  1309 D BluetoothPan: Binding service...
,09-01 10:59:35.819  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-01 10:59:35.819  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 10:59:35.819  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:35.819  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:35.819  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:35.819  1300  1300 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 10:59:35.819  1300  1300 D PanProfile: Bluetooth service connected
,09-01 10:59:35.819  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 10:59:35.819  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:35.819  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-01 10:59:35.819  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-01 10:59:35.819  1015  1015 D BluetoothA2dp: Proxy object connected
09-01 10:59:35.819  1300  7466 D BluetoothPbap: onBluetoothStateChange: up=true
,09-01 10:59:35.829  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-01 10:59:35.829  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-01 10:59:35.829  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:35.829  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:35.829  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:35.829  7358  7377 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 10:59:35.829  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-01 10:59:35.829  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
09-01 10:59:35.829  1300  1300 D BluetoothPbap: Proxy object connected
,09-01 10:59:35.829  1300  1300 D PbapServerProfile: Bluetooth service connected
,09-01 10:59:35.829  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:35.829  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
09-01 10:59:35.829  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-01 10:59:35.839  1422  1422 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3ee68ee7, true
,09-01 10:59:35.839  1422  1422 D BluetoothHeadset: registerMessageListener
,09-01 10:59:35.839  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,09-01 10:59:35.839  1874  1874 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0,
09-01 10:59:35.839  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:35.849  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:35.849  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:35.849  1015  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:35.849  7358  7367 D HeadsetService: registerMessageListener
,09-01 10:59:35.849  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-01 10:59:35.849  7358  7367 D HeadsetService: registerMessageListener
09-01 10:59:35.849  7358  7391 D HeadsetStateMachine: Disconnected process message: 70
09-01 10:59:35.849  7358  7391 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2067eb18
,09-01 10:59:35.849  1422  1422 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-01 10:59:35.849  1422  1422 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-01 10:59:35.859  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:35.859  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-01 10:59:35.859  1176  1176 D BluetoothTile:  getBluetoothState : 12
09-01 10:59:35.859  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:35.859  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:35.859  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:35.859  7358  7470 D BluetoothMapMasInstance: set MAP SDP message type : 1,
09-01 10:59:35.859  1422  1422 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-01 10:59:35.859  1300  1300 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-01 10:59:35.859  1422  1422 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-01 10:59:35.859  1300  1300 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-01 10:59:35.859  1300  1300 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-01 10:59:35.859  1422  1422 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-01 10:59:35.859  1300  1300 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-01 10:59:35.859  7358  7470 D BluetoothSocket: bindListen(): myUserId = 0
09-01 10:59:35.859  1015  1495 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-01 10:59:35.859  7358  7470 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 10:59:35.869  7358  7470 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-01 10:59:35.869  7358  7470 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 10:59:35.869  7358  7470 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 10:59:35.869  7358  7470 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22709971
09-01 10:59:35.869  7358  7470 D BluetoothSocket: channel: 5
,09-01 10:59:35.869  1015  1467 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-01 10:59:35.869  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-01 10:59:35.869  7358  7391 D HeadsetStateMachine: Disconnected process message: 9
,09-01 10:59:35.869  7358  7391 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-01 10:59:35.879   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-01 10:59:35.879   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-01 10:59:35.879   283   283 V voice   : voice_set_parameters: exit with code(-2)
09-01 10:59:35.879  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 10:59:35.879   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-01 10:59:35.879   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-01 10:59:35.879   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-01 10:59:35.879   283   283 V audio_hw_primary: adev_set_parameters: exit
09-01 10:59:35.879  7358  7391 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-01 10:59:35.879  1015  1473 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-01 10:59:35.879  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-01 10:59:35.879  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:35.879  1015  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:35.879  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-01 10:59:35.889  1176  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:35.889  1176  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:35.889  1300  1300 D DockEventReceiver: finishStartingService: stopping service
,09-01 10:59:35.889  1176  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:35.889  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 10:59:35.899  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:35.899  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-01 10:59:35.899  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:35.899  7358  7358 D BtConfig.SecureMode: isSecureModeOn:false
,09-01 10:59:35.909  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:35.909  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-01 10:59:35.909  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:35.909  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:35.909  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:35.929  1937  1937 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-01 10:59:35.929  1015  1462 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:35.929  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-01 10:59:35.929  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:35.929  1015  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:35.929  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:35.939  1937  7476 D EasyUnlockInitService: Handling intent for initializer IntentService.
09-01 10:59:35.939  1937  1937 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-01 10:59:35.939  1015  1473 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:35.939  1015  1467 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-01 10:59:35.939  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:35.939  1015  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:35.939  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:35.959  7358  7480 D BluetoothSocket: bindListen(): myUserId = 0
09-01 10:59:35.959  7358  7480 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 10:59:35.959  7358  7480 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-01 10:59:35.959  7358  7480 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 10:59:35.959  7358  7480 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 10:59:35.959  7358  7480 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@5e5c273
09-01 10:59:35.959  7358  7480 D BluetoothSocket: channel: 12
09-01 10:59:35.959  7358  7480 I BtOppRfcommListener: Accept thread started.
,09-01 10:59:36.039  4760  5529 I art     : Explicit concurrent mark sweep GC freed 25507(1569KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 12MB/21MB, paused 1.510ms total 83.281ms
,09-01 10:59:36.039  1015  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:36.039  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:36.049  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:36.049  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:36.059  1937  7476 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-01 10:59:36.579  1015  1467 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-01 10:59:36.579  1015  1467 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-01 10:59:36.579  1015  1467 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-01 10:59:36.579  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-01 10:59:36.579  1015  1467 D BatteryService: stay LED for fully charged
,09-01 10:59:36.579  1015  1015 I MotionRecognitionService: Plugged
,09-01 10:59:36.579  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-01 10:59:36.589  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-01 10:59:36.589  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-01 10:59:36.599  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-01 10:59:36.599  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-01 10:59:36.619  7358  7358 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-01 10:59:36.619  7358  7391 D HeadsetStateMachine: Disconnected process message: 10
,09-01 10:59:36.619  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-01 10:59:36.619  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-01 10:59:36.629  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-01 10:59:37.049   288   288 E SMD     : DCD OFF,
,09-01 10:59:37.529  6726  6780 D BluetoothAdapter: disable()
,09-01 10:59:37.529  1015  1495 D SettingsProvider: name = bluetooth_on
,09-01 10:59:37.539  7358  7373 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-01 10:59:37.539  7358  7373 D BluetoothAdapterProperties: Setting state to 13
09-01 10:59:37.539  7358  7373 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-01 10:59:37.539  7358  7373 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 10:59:37.539  7358  7373 D BluetoothAdapterService: updateAdapterState state is 13
,09-01 10:59:37.539  1015  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:37.539  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-01 10:59:37.549  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:37.549  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:37.549  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:37.549  7358  7358 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-01 10:59:37.549  7358  7373 D BluetoothAdapterService: Autoconnection is available 
09-01 10:59:37.549  7358  7373 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,09-01 10:59:37.549  7358  7373 D BluetoothAdapterService: terminating service from this receiver
,09-01 10:59:37.549  7358  7358 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1c050530, channel: 19, state: LISTENING
09-01 10:59:37.549  7358  7358 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1c050530, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e9e6efb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@28d805a9mSocket: android.net.LocalSocket@3f6a172e impl:android.net.LocalSocketImpl@2ed012cf fd:FileDescriptor[74]
09-01 10:59:37.549  7358  7358 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3f6a172e impl:android.net.LocalSocketImpl@2ed012cf fd:FileDescriptor[74]
,09-01 10:59:37.549  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:37.549  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,09-01 10:59:37.559  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,09-01 10:59:37.559  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
09-01 10:59:37.559  1176  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:37.559  1176  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:37.559  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:37.569  1176  1176 D BluetoothTile:  getBluetoothState : 13
,09-01 10:59:37.569  1874  1874 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
09-01 10:59:37.569  1176  1729 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-01 10:59:37.569  1015  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 10:59:37.569  1015  1473 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-01 10:59:37.569  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:37.579  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-01 10:59:37.579  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-01 10:59:37.579  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:37.579  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:37.579  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:37.589  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 10:59:37.589  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:37.589  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:37.589  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:37.589  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:37.589  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:37.589  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:37.589  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:37.589  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:37.589  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:37.589  1015  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:37.589  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-01 10:59:37.589  7358  7373 D BluetoothAdapterProperties: onBluetoothDisable()
09-01 10:59:37.589  7358  7373 D BluetoothAdapterProperties: mDiscovering is false
,09-01 10:59:37.589  1015  1027 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-01 10:59:37.589  7358  7373 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-01 10:59:37.599  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:37.599  6726  6726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:37.599  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:37.599  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:37.599  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:37.599  1015  1462 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-01 10:59:37.599  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-01 10:59:37.609  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:37.609  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:37.609  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-01 10:59:37.609  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:37.609  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:37.609  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:37.609  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:37.609  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:37.609  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:37.609  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:37.609  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:37.609  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:37.609  6726  6726 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:37.609  6726  6726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:37.609  7358  7376 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-01 10:59:37.609  7358  7376 D BluetoothAdapterProperties: Scan Mode:20
,09-01 10:59:37.609  1300  1300 D BluetoothPbap: Proxy object disconnected
09-01 10:59:37.609  1300  1300 D PbapServerProfile: Bluetooth service disconnected
,09-01 10:59:37.619  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:37.619  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:37.629  7358  7358 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2f6d445c, channel: 5, state: LISTENING
,09-01 10:59:37.629  7358  7358 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2f6d445c, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22709971, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37825365mSocket: android.net.LocalSocket@3d04783a impl:android.net.LocalSocketImpl@e650ceb fd:FileDescriptor[76]
09-01 10:59:37.629  7358  7358 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3d04783a impl:android.net.LocalSocketImpl@e650ceb fd:FileDescriptor[76]
,09-01 10:59:37.629  7358  7358 I BtOppRfcommListener: stopping Accept Thread
,09-01 10:59:37.629  7358  7373 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-01 10:59:37.629  7358  7373 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-01 10:59:37.629  7358  7358 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@13b84a48, channel: 12, state: LISTENING
09-01 10:59:37.629  7358  7358 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@13b84a48, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@5e5c273, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@7c9c0e1mSocket: android.net.LocalSocket@18b1de06 impl:android.net.LocalSocketImpl@34058cc7 fd:FileDescriptor[80]
09-01 10:59:37.629  7358  7358 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@18b1de06 impl:android.net.LocalSocketImpl@34058cc7 fd:FileDescriptor[80]
,09-01 10:59:37.629  7358  7480 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 10:59:37.629  7358  7373 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-01 10:59:37.629  7358  7373 E bt-btif : BTA got event 0x1a1c
,09-01 10:59:37.629  7358  7373 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-01 10:59:37.629  7358  7420 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-01 10:59:37.629  7358  7420 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-01 10:59:37.629  7358  7420 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 10:59:37.629  7358  7420 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 10:59:37.629  7358  7420 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 10:59:37.629  7358  7480 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-01 10:59:37.629  1300  1300 D DockEventReceiver: finishStartingService: stopping service
,09-01 10:59:37.639  7358  7358 V BluetoothOppManager: cleanUp...
,09-01 10:59:37.639  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 10:59:37.639  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:37.639  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-01 10:59:37.669  1937  1937 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-01 10:59:37.669  1937  1937 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-01 10:59:37.829  7358  7420 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-01 10:59:37.829  7358  7420 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 10:59:37.829  7358  7420 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-01 10:59:37.829  7358  7420 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 10:59:37.829  7358  7420 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-01 10:59:37.829  7358  7420 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 10:59:37.829  7358  7420 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-01 10:59:37.829  7358  7420 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 10:59:37.839  7358  7460 I bt_userial_mct: exiting userial_read_thread
09-01 10:59:37.839  7358  7460 D bt_userial_mct: Leaving userial_evt_read_thread()
09-01 10:59:37.839  7358  7376 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-01 10:59:37.839  7358  7423 I bt_vendor: hw_epilog_process
,09-01 10:59:37.839  7358  7376 D bt_userial_mct: userial_close
09-01 10:59:37.839  7358  7376 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-01 10:59:37.839  7358  7420 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-01 10:59:37.839  7358  7420 W bt-btif : ag scb idx 1 not allocated
09-01 10:59:37.839  7358  7420 W bt-btif : ag scb idx 2 not allocated
,09-01 10:59:37.839  7358  7420 E bt-btif : BTA AG is already disabled, ignoring ...
,09-01 10:59:38.099  1015  1323 E Watchdog: !@Sync 4
,09-01 10:59:38.219  7358  7376 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-01 10:59:38.219  7358  7376 I bt_vendor: bluetooth satus is on
09-01 10:59:38.219  7358  7376 I bt_vendor: bt-vendor : resetting BT status
,09-01 10:59:38.219  7358  7376 I bt_vendor: Starting hciattach daemon
09-01 10:59:38.219  7358  7376 I bt_vendor: try to set false
09-01 10:59:38.219  7358  7376 I bt_vendor: Starting hciattach daemon
,09-01 10:59:38.219  7358  7376 I bt_vendor: try to set false
09-01 10:59:38.219  7358  7376 I bt_vendor: cleanup
,09-01 10:59:38.219  7358  7420 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-01 10:59:38.219  7358  7376 I GKI_LINUX: GKI_exit_task 0 done
09-01 10:59:38.219  7358  7376 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-01 10:59:38.219  7358  7373 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
09-01 10:59:38.219  7358  7373 D BtConfig.SecureMode: isSecureModeOn:false
09-01 10:59:38.219  7358  7373 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-01 10:59:38.219  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
09-01 10:59:38.219  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService,
09-01 10:59:38.219  1015  1322 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:38.219  7358  7373 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-01 10:59:38.219  1015  1322 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0,
,09-01 10:59:38.219  1015  1322 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:38.219  1015  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.219  1015  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:38.229  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService,
,09-01 10:59:38.229  1015  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-01 10:59:38.229  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-01 10:59:38.229  1015  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0,
09-01 10:59:38.229  7358  7373 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-01 10:59:38.229  7358  7358 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-01 10:59:38.229  7358  7358 D BtGatt.GattService: Received stop request...Stopping profile...,
09-01 10:59:38.229  7358  7358 D BtGatt.GattService: stop()
09-01 10:59:38.229  1015  1467 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:38.229  7358  7358 D BtGatt.AdvertiseManager: advertise clients cleared
,09-01 10:59:38.229  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-01 10:59:38.229  1015  1481 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:38.229  1015  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.229  1015  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:38.229  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-01 10:59:38.229  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-01 10:59:38.229  7358  7373 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-01 10:59:38.229  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
09-01 10:59:38.239  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:38.239  1015  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.239  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:38.239  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-01 10:59:38.239  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-01 10:59:38.239  7358  7373 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-01 10:59:38.239  1015  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-01 10:59:38.239  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-01 10:59:38.239  7358  7358 D HeadsetService: Received stop request...Stopping profile...
,09-01 10:59:38.239  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:38.239  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.239  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:38.239  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
09-01 10:59:38.239  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-01 10:59:38.239  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-01 10:59:38.239  7358  7373 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-01 10:59:38.249  1015  1462 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:38.249  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-01 10:59:38.249  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-01 10:59:38.249  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:38.249  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.249  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:38.249  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-01 10:59:38.249  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-01 10:59:38.249  7358  7373 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-01 10:59:38.249  1015  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:38.249  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.249  1300  1300 D HeadsetProfile: Bluetooth service disconnected
,09-01 10:59:38.249  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:38.249  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.249  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:38.259  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-01 10:59:38.259  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:38.259  7358  7373 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-01 10:59:38.259  1015  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:38.259  1015  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.259  1015  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:38.259  1015  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.259  1015  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:38.259  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-01 10:59:38.259  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-01 10:59:38.259  7358  7373 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-01 10:59:38.259  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:38.259  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.259  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:38.259  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.259  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:38.259  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:38.259  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:38.259  7358  7373 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:38.259  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:38.259  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:38.259  7358  7373 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:38.259  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-01 10:59:38.259  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-01 10:59:38.259  7358  7373 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-01 10:59:38.259  7358  7373 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-01 10:59:38.259  7358  7373 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-01 10:59:38.259  7358  7373 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-01 10:59:38.259  7358  7373 D BluetoothAdapterState: Stopping profile services that were post enabled
09-01 10:59:38.259  7358  7358 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-01 10:59:38.259  7358  7358 D A2dpService: Received stop request...Stopping profile...
,09-01 10:59:38.269  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:38.269  1015  1015 D BluetoothA2dp: Proxy object disconnected
09-01 10:59:38.269  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-01 10:59:38.269  7358  7402 D A2dpStateMachine: Exit Disconnected: -1
,09-01 10:59:38.269  7358  7358 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-01 10:59:38.269  7358  7358 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-01 10:59:38.269  7358  7358 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-01 10:59:38.269  7358  7358 D HidService: Received stop request...Stopping profile...
,09-01 10:59:38.269  7358  7358 D HidService: Stopping Bluetooth HidService
09-01 10:59:38.269  7358  7358 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 10:59:38.269  7358  7358 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-01 10:59:38.269  7358  7358 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 10:59:38.269  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:38.269  1300  1300 D BluetoothA2dp: Proxy object disconnected
,09-01 10:59:38.269  7358  7358 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-01 10:59:38.269  7358  7358 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-01 10:59:38.269  1300  1300 D A2dpProfile: Bluetooth service disconnected
09-01 10:59:38.269  1300  1300 D BluetoothInputDevice: Proxy object disconnected
09-01 10:59:38.269  1300  1300 D HidProfile: Bluetooth service disconnected
09-01 10:59:38.269  7358  7358 D HealthService: Received stop request...Stopping profile...
,09-01 10:59:38.279  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:38.279  7358  7358 D PanService: Received stop request...Stopping profile...
09-01 10:59:38.279  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:38.279  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-01 10:59:38.279  1300  1300 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 10:59:38.279  1300  1300 D PanProfile: Bluetooth service disconnected
,09-01 10:59:38.279  7358  7358 D BluetoothMapService: Received stop request...Stopping profile...
,09-01 10:59:38.279  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:38.289  7358  7358 D SapService: Received stop request...Stopping profile...
09-01 10:59:38.289  7358  7358 D SapService: Stopping Bluetooth SapService
09-01 10:59:38.289  1300  1300 D BluetoothMap: Proxy object disconnected
09-01 10:59:38.289  7358  7358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
09-01 10:59:38.289  1300  1300 D MapProfile: Bluetooth service disconnected
,09-01 10:59:38.289  1300  1300 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-01 10:59:38.289  1300  1300 D SapProfile: Bluetooth service disconnected
,09-01 10:59:38.289  7358  7358 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-01 10:59:38.289  7358  7358 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-01 10:59:38.289  7358  7358 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-01 10:59:38.289  7358  7358 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-01 10:59:38.289  7358  7358 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:38.289  7358  7358 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:38.289  7358  7358 D BluetoothA2dp: Proxy object disconnected
09-01 10:59:38.289  7358  7358 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-01 10:59:38.289  7358  7403 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-01 10:59:38.289  7358  7358 I GKI_LINUX: GKI_exit_task 2 done
09-01 10:59:38.289  7358  7358 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-01 10:59:38.289  7358  7358 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-01 10:59:38.289  7358  7358 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:38.289  7358  7358 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:38.289  7358  7358 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-01 10:59:38.289  7358  7358 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-01 10:59:38.289  7358  7358 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-01 10:59:38.289  7358  7358 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:38.289  7358  7358 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:38.289  7358  7358 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 10:59:38.289  7358  7358 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-01 10:59:38.289  7358  7358 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-01 10:59:38.289  7358  7358 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-01 10:59:38.289  7358  7358 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-01 10:59:38.289  7358  7358 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-01 10:59:38.289  7358  7358 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-01 10:59:38.289  7358  7358 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-01 10:59:38.289  7358  7373 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-01 10:59:38.299  7358  7373 D BluetoothAdapterProperties: Setting state to 10
09-01 10:59:38.299  7358  7373 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-01 10:59:38.299  7358  7373 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 10:59:38.299  7358  7373 D BluetoothAdapterService: updateAdapterState state is 10
,09-01 10:59:38.299  7358  7373 D BluetoothAdapterService: Autoconnection is available 
09-01 10:59:38.299  7358  7373 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,09-01 10:59:38.299  7358  7373 I BluetoothAdapterState: Entering OffState
09-01 10:59:38.299  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 10:59:38.299  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:38.299  1300  1309 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 10:59:38.299  6726  6736 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 10:59:38.299  6726  6736 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:38.299  6726  6736 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-01 10:59:38.299  6726  6736 D BluetoothLeAdvertiser: Exit stop advertising
,09-01 10:59:38.299  6726  6736 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-01 10:59:38.299  6726  6736 D BluetoothLeScanner: Exiting stopAllScan
,09-01 10:59:38.299  7358  7366 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:38.299  7358  7366 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:38.299  1439  6185 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 10:59:38.309  1439  6185 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:38.309  1176  1792 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:38.309  1176  1792 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:38.309  1300  7466 D Bluetoothsap: onBluetoothStateChange: up=false
09-01 10:59:38.309  1300  7466 D Bluetoothsap: Unbinding service...
,09-01 10:59:38.309  1422  1445 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 10:59:38.309  1422  1445 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:38.309  1300  1309 D BluetoothMap: onBluetoothStateChange: up=false
,09-01 10:59:38.309  1300  7466 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-01 10:59:38.309  1451  2463 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 10:59:38.309  1451  2463 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:38.309  1300  1313 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:38.309  1300  1313 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:38.309  7408  7418 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 10:59:38.309  7408  7418 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:38.319  1937  1956 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 10:59:38.319  1937  1956 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:38.319  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 10:59:38.319  1300  7466 D BluetoothPbap: onBluetoothStateChange: up=false
,09-01 10:59:38.319  7358  7469 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 10:59:38.319  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-01 10:59:38.319  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-01 10:59:38.329  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:38.329  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
,09-01 10:59:38.329  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-01 10:59:38.329  7358  7376 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-01 10:59:38.329  7358  7358 I GKI_LINUX: GKI_exit_task 1 done
09-01 10:59:38.329  7358  7358 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-01 10:59:38.329  7358  7358 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-01 10:59:38.339  7358  7358 I art     : System.exit called, status: 0
09-01 10:59:38.339  7358  7358 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-01 10:59:38.339  1015  1047 I PowerManagerService: [PWL] Off : 75s ago
09-01 10:59:38.339  1015  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-01 10:59:38.339  1015  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-01 10:59:38.339  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=11956)
09-01 10:59:38.339  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2464)
09-01 10:59:38.339  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2462)
,09-01 10:59:38.339  1176  1176 D BluetoothAdapter: 171507465: getState() :  mService = null. Returning STATE_OFF
,09-01 10:59:38.339  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-01 10:59:38.339  1176  1729 D BluetoothAdapter: 171507465: getState() :  mService = null. Returning STATE_OFF
,09-01 10:59:38.339  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:38.339  1176  1176 D BluetoothTile:  getBluetoothState : 10
,09-01 10:59:38.339  1176  1729 D BluetoothAdapter: 171507465: getState() :  mService = null. Returning STATE_OFF
,09-01 10:59:38.339  1176  1176 D BluetoothAdapter: 171507465: getState() :  mService = null. Returning STATE_OFF
09-01 10:59:38.339  1176  1176 D BluetoothAdapter: 171507465: getState() :  mService = null. Returning STATE_OFF
09-01 10:59:38.339  1015  1467 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 10:59:38.339  1015  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-01 10:59:38.339  1874  1874 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-01 10:59:38.349  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-01 10:59:38.349  1937  2165 D BluetoothAdapter: 600275001: getState() :  mService = null. Returning STATE_OFF
09-01 10:59:38.349  1937  2165 D BluetoothAdapter: 600275001: getState() :  mService = null. Returning STATE_OFF
,09-01 10:59:38.349  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:38.349  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:38.349  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:38.349  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:38.349  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.349  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:38.349  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:38.349  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:38.359  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 10:59:38.359  1015  1027 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-01 10:59:38.359  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.359  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:38.359  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.359  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-01 10:59:38.359  1300  1300 D DockEventReceiver: finishStartingService: stopping service
,09-01 10:59:38.359  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 10:59:38.369  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:38.369  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-01 10:59:38.459  1015  1319 I ActivityManager: Process com.android.bluetooth (pid 7358)(adj 0) has died(33,713)
,09-01 10:59:38.469  1937  1937 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-01 10:59:38.469  1015  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:38.469  1015  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.479  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:38.479  1015  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:38.479  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:38.479  1937  7498 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-01 10:59:38.489  1937  1937 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-01 10:59:38.499  1015  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:38.499  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:38.499  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:38.499  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:38.509  1937  7498 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-01 10:59:39.049   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-01 10:59:40.049   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-01 10:59:40.049   288   288 E SMD     : DCD OFF
,09-01 10:59:40.549  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 10:59:40.549  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:41.049   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:42.049   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-01 10:59:42.169  1015  2012 V SAMP_SPCM_test: CSC File load.. ,
,09-01 10:59:42.179  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-01 10:59:42.179  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
,09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
,09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall,
09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-01 10:59:42.189  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
,09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
,09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
,09-01 10:59:42.229  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-01 10:59:42.239  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,09-01 10:59:42.239  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage,
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
,09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory,
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
,09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
,09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn,
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-01 10:59:42.249  1015  2012 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
,09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall,
09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-01 10:59:42.249  1015  2012 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:42.249  1015  2012 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
09-01 10:59:42.249  1015  2012 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:42.249  1015  2012 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:42.249  1015  2012 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:42.269  1015  2012 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7501 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-01 10:59:42.269  7501  7501 E Zygote  : MountEmulatedStorage(),
09-01 10:59:42.269  7501  7501 E Zygote  : v2
09-01 10:59:42.269  7501  7501 I libpersona: KNOX_SDCARD checking this for 1000
09-01 10:59:42.269  7501  7501 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:42.279  7501  7501 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-01 10:59:42.279  7501  7501 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:42.279  7501  7501 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:42.309  7501  7501 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:42.309  7501  7501 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:42.319  7501  7501 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-01 10:59:42.359  1015  2012 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-01 10:59:42.389  1015  3358 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-01 10:59:43.049   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:43.049   288   288 E SMD     : DCD OFF
,09-01 10:59:43.519  1015  1319 I ActivityManager: Killing 7068:com.sec.android.soagent/u0a31 (adj 15): empty #21
,09-01 10:59:43.549  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 10:59:43.549  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b7923d7 added. We now have 6 listener(s)
09-01 10:59:43.549  6726  6780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:43.549  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 10:59:43.549  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ac9f4c4 added. We now have 7 listener(s)
09-01 10:59:43.549  6726  6780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:43.549  6726  6780 I System.out: IsBluetoothEnabled
,09-01 10:59:43.549  6726  6780 D BluetoothAdapter: disable()
,09-01 10:59:43.559  1015  1481 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-01 10:59:43.559  6726  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:43.559  6726  6780 D BluetoothAdapter: enable()
,09-01 10:59:43.559  1015  1473 W ActivityManager: Permission Denial: getCurrentUser() from pid=6726, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-01 10:59:43.559  1015  1473 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-01 10:59:43.559  1015  1473 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6726, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-01 10:59:43.559  1015  1473 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-01 10:59:43.559  1015  1473 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-01 10:59:43.559  1015  1473 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-01 10:59:43.559  1015  1473 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-01 10:59:43.559  1015  1473 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-01 10:59:43.559  1015  1473 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 10:59:43.569  1015  1473 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 10:59:43.569  1015  1473 D SettingsProvider: name = bluetooth_on
,09-01 10:59:43.579  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-01 10:59:43.579  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 10:59:43.579  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-01 10:59:43.579  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-01 10:59:43.579  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:43.579  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:43.579  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:43.579  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:43.599  7520  7520 E Zygote  : MountEmulatedStorage()
,09-01 10:59:43.599  7520  7520 E Zygote  : v2
09-01 10:59:43.599  7520  7520 I libpersona: KNOX_SDCARD checking this for 1002
09-01 10:59:43.599  7520  7520 I libpersona: KNOX_SDCARD not a persona,
09-01 10:59:43.599  7520  7520 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:43.599  1015  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7520 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-01 10:59:43.599  7520  7520 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:43.609  7520  7520 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-01 10:59:43.639  7520  7520 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:43.639  7520  7520 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:43.669  7520  7520 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-01 10:59:43.669  7520  7520 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-01 10:59:43.709  7520  7520 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-01 10:59:43.729  1015  3326 D SSRM:n  : SIOP:: AP = 320
,09-01 10:59:43.739  7520  7520 D BtSettings.ProfileConfig: Adding GattService
,09-01 10:59:43.749  7520  7520 D BtSettings.ProfileConfig: Adding HeadsetService
09-01 10:59:43.749  7520  7520 D BtSettings.ProfileConfig: Adding A2dpService
,09-01 10:59:43.749  7520  7520 D BtSettings.ProfileConfig: Adding HidService
09-01 10:59:43.749  7520  7520 D BtSettings.ProfileConfig: Adding HealthService
09-01 10:59:43.749  7520  7520 D BtSettings.ProfileConfig: Adding PanService
,09-01 10:59:43.749  7520  7520 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-01 10:59:43.749  7520  7520 D BtSettings.ProfileConfig: Adding SapService
09-01 10:59:43.749  7520  7520 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-01 10:59:43.749  7520  7520 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-01 10:59:43.749  7520  7520 D BtSettings.ProfileConfig: Adding SapClientService
09-01 10:59:43.749  7520  7520 D BtSettings.ProfileConfig: Adding HidDevService
,09-01 10:59:43.749  7520  7520 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-01 10:59:43.749  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-01 10:59:43.749  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.749  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.749  1015  1028 D SettingsProvider: selectionArgs: false,
09-01 10:59:43.749  1015  1028 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.749  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.749  1015  1028 D SettingsProvider: ret = -1
,09-01 10:59:43.749  1015  1322 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-01 10:59:43.749  1015  1322 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.749  1015  1322 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.749  1015  1322 D SettingsProvider: selectionArgs: false
09-01 10:59:43.749  1015  1322 D SettingsProvider: selectionArgs: 1002
,09-01 10:59:43.749  1015  1322 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.749  1015  1322 D SettingsProvider: ret = -1
,09-01 10:59:43.759  1015  1473 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-01 10:59:43.759  1015  1473 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.759  1015  1473 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-01 10:59:43.759  1015  1473 D SettingsProvider: selectionArgs: false
09-01 10:59:43.759  1015  1473 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.759  1015  1473 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.759  1015  1473 D SettingsProvider: ret = -1
09-01 10:59:43.759  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-01 10:59:43.759  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.759  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.759  1015  1027 D SettingsProvider: selectionArgs: false
09-01 10:59:43.759  1015  1027 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.759  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-01 10:59:43.759  1015  1027 D SettingsProvider: ret = -1
09-01 10:59:43.759  1015  1319 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-01 10:59:43.759  1015  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.759  1015  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.759  1015  1319 D SettingsProvider: selectionArgs: false
09-01 10:59:43.759  1015  1319 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.759  1015  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.759  1015  1319 D SettingsProvider: ret = -1
09-01 10:59:43.759  1015  1467 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-01 10:59:43.759  1015  1467 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.759  1015  1467 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-01 10:59:43.759  1015  1467 D SettingsProvider: selectionArgs: false
09-01 10:59:43.759  1015  1467 D SettingsProvider: selectionArgs: 1002
,09-01 10:59:43.759  1015  1467 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.759  1015  1467 D SettingsProvider: ret = -1
,09-01 10:59:43.759  1015  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-01 10:59:43.759  1015  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
09-01 10:59:43.759  1015  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
09-01 10:59:43.759  1015  1495 D SettingsProvider: selectionArgs: false,
09-01 10:59:43.759  1015  1495 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.759  1015  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.759  1015  1495 D SettingsProvider: ret = -1
,09-01 10:59:43.759  1015  1134 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-01 10:59:43.759  1015  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.759  1015  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.759  1015  1134 D SettingsProvider: selectionArgs: false
09-01 10:59:43.759  1015  1134 D SettingsProvider: selectionArgs: 1002
,09-01 10:59:43.759  1015  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.759  1015  1134 D SettingsProvider: ret = -1
09-01 10:59:43.759  1015  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:43.759  1015  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.759  1015  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-01 10:59:43.759  1015  1481 D SettingsProvider: selectionArgs: false
09-01 10:59:43.759  1015  1481 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.759  1015  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.759  1015  1481 D SettingsProvider: ret = -1
09-01 10:59:43.759  1015  1472 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:43.759  1015  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.759  1015  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-01 10:59:43.759  1015  1472 D SettingsProvider: selectionArgs: false
09-01 10:59:43.759  1015  1472 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.759  1015  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.759  1015  1472 D SettingsProvider: ret = -1
09-01 10:59:43.759  1015  1462 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-01 10:59:43.759  1015  1462 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-01 10:59:43.759  1015  1462 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.759  1015  1462 D SettingsProvider: selectionArgs: false
09-01 10:59:43.759  1015  1462 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.759  1015  1462 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.759  1015  1462 D SettingsProvider: ret = -1
,09-01 10:59:43.759  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-01 10:59:43.759  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.759  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.759  1015  1028 D SettingsProvider: selectionArgs: false
09-01 10:59:43.759  1015  1028 D SettingsProvider: selectionArgs: 1002
,09-01 10:59:43.759  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.759  1015  1028 D SettingsProvider: ret = -1
,09-01 10:59:43.779  7520  7520 D BluetoothAdapterState: make,
,09-01 10:59:43.789  7520  7520 I bluedroid: init,
,09-01 10:59:43.789  7520  7535 I BluetoothAdapterState: Entering OffState,
09-01 10:59:43.789  7520  7520 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-01 10:59:43.789  7520  7520 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-01 10:59:43.789  7520  7520 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-01 10:59:43.789  7520  7520 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-01 10:59:43.789  7520  7520 E bt-btif : btif_fetch_local_ble_random_bdaddr,
09-01 10:59:43.789  7520  7520 I bluedroid: get_profile_interface socket
09-01 10:59:43.789  7520  7520 I bluedroid: get_profile_interface map_client
09-01 10:59:43.789  7520  7538 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-01 10:59:43.799  7520  7520 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-01 10:59:43.799  7520  7538 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-01 10:59:43.799  7520  7538 E BluetoothServiceJni: populateRssiValuesNative
,09-01 10:59:43.799  7520  7538 I bluedroid: getModelRssiValues
09-01 10:59:43.799  7520  7538 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-01 10:59:43.799  7520  7538 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-01 10:59:43.799  7520  7538 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-01 10:59:43.799  1015  1015 D SettingsProvider: name = bluetooth_name
,09-01 10:59:43.809  7520  7520 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:43.809  1015  1473 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-01 10:59:43.809  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 10:59:43.809  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:43.809  1015  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:43.809  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:43.809  7520  7528 I bluedroid: config_hci_snoop_log
,09-01 10:59:43.809  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-01 10:59:43.819  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,09-01 10:59:43.819  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-01 10:59:43.819  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-01 10:59:43.819  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-01 10:59:43.819  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 10:59:43.819  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 10:59:43.819  7520  7520 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-01 10:59:43.829  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-01 10:59:43.829  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-01 10:59:43.829  7520  7535 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-01 10:59:43.829  7520  7535 D BluetoothAdapterProperties: Setting state to 11
09-01 10:59:43.829  7520  7535 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-01 10:59:43.829  7520  7535 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 10:59:43.829  7520  7535 D BluetoothAdapterService: updateAdapterState state is 11
,09-01 10:59:43.829  7520  7535 D BluetoothAdapterService: Autoconnection is available 
,09-01 10:59:43.829  7520  7535 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-01 10:59:43.829  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:43.839  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,09-01 10:59:43.839  7520  7535 D BluetoothSecureManager: getInstant: null
,09-01 10:59:43.839  7520  7535 D BluetoothSecureManager: calling getMethod for getService
09-01 10:59:43.839  7520  7535 D BluetoothSecureManager: calling getService
,09-01 10:59:43.839  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-01 10:59:43.839  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:43.849  1874  1874 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0,
09-01 10:59:43.849  1176  1176 D BluetoothTile:  getBluetoothState : 11
09-01 10:59:43.849  7520  7535 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1c640107
09-01 10:59:43.849  1176  1729 D BluetoothTile:  handleUpdatestate:false name:null
09-01 10:59:43.849  1015  1027 D BluetoothSecureManagerService: isSecureModeEnabled
,09-01 10:59:43.849  1176  1729 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-01 10:59:43.849  1015  1027 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
09-01 10:59:43.849  7520  7535 D BtConfig.SecureMode: isSecureModeOn:false
,09-01 10:59:43.849  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-01 10:59:43.849  7520  7535 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-01 10:59:43.849  1015  1462 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-01 10:59:43.849  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-01 10:59:43.849  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:43.849  7520  7535 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-01 10:59:43.849  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-01 10:59:43.849  7520  7535 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-01 10:59:43.849  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-01 10:59:43.859  1015  1467 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false,
09-01 10:59:43.859  1015  1495 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:43.859  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 10:59:43.859  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-01 10:59:43.859  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:43.859  7520  7535 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-01 10:59:43.859  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-01 10:59:43.859  7520  7535 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-01 10:59:43.859  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-01 10:59:43.859  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:43.859  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:43.859  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:43.859  7520  7535 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-01 10:59:43.859  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-01 10:59:43.859  7520  7535 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-01 10:59:43.859  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-01 10:59:43.859  7520  7535 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-01 10:59:43.859  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:43.859  7520  7535 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:43.859  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:43.859  7520  7535 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService,
,09-01 10:59:43.859  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-01 10:59:43.869  7520  7535 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-01 10:59:43.869  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-01 10:59:43.869  7520  7535 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-01 10:59:43.869  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 10:59:43.879  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ),
,09-01 10:59:43.879  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:43.879  7520  7535 D BluetoothBondStateMachine: make
09-01 10:59:43.879  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-01 10:59:43.879  7520  7541 I BluetoothBondStateMachine: StableState(): Entering Off State
09-01 10:59:43.879  7520  7535 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-01 10:59:43.879  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-01 10:59:43.879  7520  7535 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-01 10:59:43.889  1015  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:43.889  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-01 10:59:43.889  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:43.889  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:43.889  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:43.889  7520  7535 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-01 10:59:43.889  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-01 10:59:43.889  7520  7535 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-01 10:59:43.889  7520  7520 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-01 10:59:43.889  7520  7520 D BtGatt.GattService: Received start request. Starting profile...
09-01 10:59:43.889  7520  7520 D BtGatt.GattService: start()
09-01 10:59:43.889  7520  7520 D BtGatt.GattService: start()
09-01 10:59:43.889  7520  7520 I bluedroid: get_profile_interface gatt
,09-01 10:59:43.889  7520  7520 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
09-01 10:59:43.889  7520  7520 D BtGatt.AdvertiseManager: advertise manager created
,09-01 10:59:43.899  1015  1462 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:43.899  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-01 10:59:43.899  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:43.899  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:43.899  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:43.909  7520  7520 D BtGatt.GattService: mStartError = false
09-01 10:59:43.909  7520  7535 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-01 10:59:43.909  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-01 10:59:43.909  7520  7520 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
09-01 10:59:43.909  7520  7535 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-01 10:59:43.909  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:43.909  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 10:59:43.909  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:43.909  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:43.909  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:43.909  7520  7520 D HeadsetService: Received start request. Starting profile...
,09-01 10:59:43.909  7520  7520 D HeadsetService: start()
,09-01 10:59:43.909  7520  7535 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-01 10:59:43.909  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-01 10:59:43.909  7520  7520 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-01 10:59:43.909  7520  7535 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-01 10:59:43.909  7520  7520 D HeadsetStateMachine: make
,09-01 10:59:43.919  7520  7520 E HeadsetStateMachine: # of Max HF connection is 2
,09-01 10:59:43.929  1015  1462 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:43.929  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-01 10:59:43.929  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:43.929  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:43.929  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:43.929  7520  7535 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-01 10:59:43.929  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-01 10:59:43.929  7520  7535 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-01 10:59:43.929  1015  1134 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-01 10:59:43.929  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
09-01 10:59:43.929  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:43.929  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:43.929  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-01 10:59:43.929  1015  1481 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-01 10:59:43.929  1015  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-01 10:59:43.939  1015  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:43.939  1015  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:43.939  1015  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-01 10:59:43.939  7520  7520 I bluedroid: get_profile_interface handsfree
,09-01 10:59:43.939  1937  1937 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-01 10:59:43.939  1015  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:43.939  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-01 10:59:43.939  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:43.939  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:43.939  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:43.949  7520  7535 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-01 10:59:43.949  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-01 10:59:43.949  7520  7535 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-01 10:59:43.949  1015  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:43.949  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 10:59:43.949  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:43.949  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:43.949  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:43.949  7520  7535 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-01 10:59:43.949  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:43.949  7520  7535 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-01 10:59:43.949  1015  1322 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:43.949  1015  1322 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-01 10:59:43.959  1015  1322 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:43.959  1015  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,09-01 10:59:43.959  1015  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:43.959  7520  7535 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-01 10:59:43.969  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-01 10:59:43.969  7520  7535 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-01 10:59:43.969  1937  1937 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-01 10:59:43.979  1015  1462 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:43.979  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-01 10:59:43.979  1015  1462 W ActivityManager: userId = 0, bbcId = -10000,
09-01 10:59:43.979  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:43.979  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:43.979  7520  7520 I DualScoManager: Instantiating Dual Sco Manager
09-01 10:59:43.979  7520  7520 I DualScoManager: Set HeadsetServiceHelper
,09-01 10:59:43.979  7520  7520 D BluetoothAtMessage: createCMTIContentObservers
,09-01 10:59:43.979  7520  7535 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:43.979  1015  1472 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-01 10:59:43.979  1015  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.979  1015  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.979  1015  1472 D SettingsProvider: selectionArgs: false
09-01 10:59:43.979  1015  1472 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.979  1015  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.979  1015  1472 D SettingsProvider: ret = -1
,09-01 10:59:43.979  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:43.979  7520  7535 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-01 10:59:43.979  7520  7535 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:43.989  7520  7544 D HeadsetStateMachine: Enter Disconnected: -2
09-01 10:59:43.989  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:43.989  7520  7535 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:43.989  7520  7535 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-01 10:59:43.989  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-01 10:59:43.989  7520  7535 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-01 10:59:43.989  7520  7535 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-01 10:59:43.989  7520  7535 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-01 10:59:43.989  7520  7535 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-01 10:59:43.989  7520  7535 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-01 10:59:43.989  7520  7520 D HeadsetService: mStartError = false,
09-01 10:59:43.989  7520  7520 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
09-01 10:59:43.989  7520  7520 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-01 10:59:43.989  7520  7544 D HeadsetStateMachine: Clear mHeadsetBrsf
09-01 10:59:43.989  7520  7544 D HeadsetStateMachine: map size, before remove : 0
09-01 10:59:43.989  7520  7544 D HeadsetStateMachine: map size, after remove: 0
,09-01 10:59:43.989  7520  7520 D A2dpService: Received start request. Starting profile...
,09-01 10:59:43.989  7520  7520 D A2dpService: start()
,09-01 10:59:43.989  7520  7520 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-01 10:59:43.999  7520  7520 I bluedroid: get_profile_interface avrcp
,09-01 10:59:43.999  7520  7520 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-01 10:59:43.999  7520  7520 D Avrcp   : Initialize Media Controller
,09-01 10:59:43.999  7520  7520 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-01 10:59:44.009  7520  7520 E Avrcp   : getActiveSessions
,09-01 10:59:44.009  7520  7520 D Avrcp   : pick active media Controller
09-01 10:59:44.009  7520  7520 D Avrcp   : Get the active Media Controller 
,09-01 10:59:44.019  7520  7520 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-01 10:59:44.019  7520  7548 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-01 10:59:44.019  7520  7520 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 10:59:44.019  7520  7520 D A2dpStateMachine: make
,09-01 10:59:44.029  7520  7520 I bluedroid: get_profile_interface a2dp
,09-01 10:59:44.029  7520  7550 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-01 10:59:44.029  7520  7520 E bt-btif : warning : media task started media_task_refcnt 1 
,09-01 10:59:44.029  7520  7520 D A2dpService: mStartError = false
09-01 10:59:44.029  7520  7520 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:44.029  7520  7549 D A2dpStateMachine: Enter Disconnected: -2
,09-01 10:59:44.029  7520  7520 I BluetoothHidServiceJni: classInitNative: succeeds
,09-01 10:59:44.029  7520  7520 D HidService: Received start request. Starting profile...
09-01 10:59:44.029  7520  7520 D HidService: start()
09-01 10:59:44.029  7520  7520 I bluedroid: get_profile_interface hidhost
09-01 10:59:44.029  7520  7520 D HidService: setHidService(): set to: null
09-01 10:59:44.029  7520  7520 D HidService: mStartError = false
09-01 10:59:44.029  7520  7520 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:44.029  7520  7520 D HeadsetStateMachine: Try to query the phonestate on bind
,09-01 10:59:44.039  1422  1445 I Telecom : BluetoothPhoneService: queryPhoneState
,09-01 10:59:44.039  1422  1422 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-01 10:59:44.039  1422  1422 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-01 10:59:44.039  1422  1445 I Telecom : BluetoothPhoneService: Result of Message : true
,09-01 10:59:44.039  7520  7520 D HeadsetStateMachine: Proxy object connected
09-01 10:59:44.039  7520  7520 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-01 10:59:44.039  7520  7520 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-01 10:59:44.039  7520  7544 D HeadsetStateMachine: Disconnected process message: 11
,09-01 10:59:44.039  7520  7520 D HealthService: Received start request. Starting profile...
09-01 10:59:44.039  7520  7520 D HealthService: start()
,09-01 10:59:44.039  7520  7520 I bluedroid: get_profile_interface health
,09-01 10:59:44.039  7520  7520 D HealthService: mStartError = false
09-01 10:59:44.039  7520  7520 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:44.039  7520  7520 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-01 10:59:44.039  7520  7520 D PanService: Received start request. Starting profile...
09-01 10:59:44.039  7520  7520 D PanService: start()
09-01 10:59:44.049  7520  7520 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 10:59:44.049  7520  7520 I bluedroid: get_profile_interface pan
,09-01 10:59:44.049  7520  7520 D PanService: mStartError = false
09-01 10:59:44.049  7520  7520 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:44.049  7520  7520 D HeadsetPhoneState: sendDeviceDataStateChanged
09-01 10:59:44.049  7520  7520 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-01 10:59:44.049   319   319 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-01 10:59:44.049  7520  7544 D HeadsetStateMachine: Disconnected process message: 18
,09-01 10:59:44.049  7520  7548 D BluetoothMediaBrowser: no now playing list
09-01 10:59:44.049  7520  7548 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-01 10:59:44.049  7520  7520 D BluetoothMapService: Received start request. Starting profile...
09-01 10:59:44.049  7520  7520 D BluetoothMapService: start()
,09-01 10:59:44.049  7520  7520 D BluetoothMapService: mStartError = false
09-01 10:59:44.049  7520  7520 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:44.049  7520  7520 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-01 10:59:44.049  7520  7520 D SapService: Received start request. Starting profile...
,09-01 10:59:44.049  7520  7520 D SapService: start()
09-01 10:59:44.049  7520  7520 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-01 10:59:44.049  7520  7520 I bluedroid: get_profile_interface sap
09-01 10:59:44.049  7520  7520 D SapService: mStartError = false
09-01 10:59:44.049  7520  7520 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
09-01 10:59:44.049  7520  7520 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,09-01 10:59:44.049  7520  7520 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-01 10:59:44.049  7520  7520 D BluetoothA2dp: Proxy object connected
09-01 10:59:44.049  7520  7520 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-01 10:59:44.049  7520  7520 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-01 10:59:44.049  7520  7520 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-01 10:59:44.049  7520  7520 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-01 10:59:44.049  7520  7520 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
09-01 10:59:44.059  7520  7544 D HeadsetStateMachine: Disconnected process message: 10
,09-01 10:59:44.059  7520  7544 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-01 10:59:44.059  7520  7544 D HeadsetStateMachine: Disconnected process message: 11
,09-01 10:59:44.079  7520  7520 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-01 10:59:44.079  7520  7520 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-01 10:59:44.079  7520  7535 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-01 10:59:44.079  7520  7535 I bluedroid: enable
,09-01 10:59:44.079  7520  7535 I bt_hci_bdroid: init
09-01 10:59:44.079  7520  7554 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-01 10:59:44.079  7520  7535 I bt_vendor: bt-vendor : init
,09-01 10:59:44.079  7520  7535 I bt_vendor: bt-vendor : get_bt_soc_type
09-01 10:59:44.079  7520  7535 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-01 10:59:44.079  7520  7535 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
,09-01 10:59:44.089  7520  7535 D bt_userial_mct: userial_init
09-01 10:59:44.089  7520  7535 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-01 10:59:44.089  7520  7535 I bt_vendor: Starting hciattach daemon
09-01 10:59:44.089  7520  7535 I bt_vendor: try to set false
,09-01 10:59:44.089  7520  7535 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,09-01 10:59:44.089  7520  7535 I bt_vendor: Starting hciattach daemon
09-01 10:59:44.089  7520  7535 I bt_vendor: try to set true
,09-01 10:59:44.099  7558  7558 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-01 10:59:44.149  7564  7564 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-01 10:59:44.159  7565  7565 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-01 10:59:44.169  7567  7567 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-01 10:59:44.179  7568  7568 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-01 10:59:44.189  7569  7569 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-01 10:59:44.199  7570  7570 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-01 10:59:44.429  7573  7573 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,09-01 10:59:44.439  7574  7574 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-01 10:59:44.499  7520  7535 I bt_vendor: bluetooth satus is on
,09-01 10:59:44.499  7520  7556 D bt_userial_mct: userial_open(port:0)
09-01 10:59:44.499  7520  7556 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-01 10:59:44.499  7520  7556 I bt_vendor: Done intiailizing UART,
,09-01 10:59:44.499  7520  7556 I bt_vendor: Done intiailizing UART
09-01 10:59:44.499  7520  7556 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
09-01 10:59:44.499  7520  7556 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-01 10:59:44.509  7520  7576 D bt_userial_mct: Entering userial_read_thread()
,09-01 10:59:44.509  7520  7554 I         : BTE_InitTraceLevels -- TRC_HCI
,09-01 10:59:44.509  7520  7554 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-01 10:59:44.509  7520  7554 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-01 10:59:44.509  7520  7554 I         : BTE_InitTraceLevels -- TRC_AVDT
09-01 10:59:44.509  7520  7554 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-01 10:59:44.509  7520  7554 I         : BTE_InitTraceLevels -- TRC_A2D
09-01 10:59:44.509  7520  7554 I         : BTE_InitTraceLevels -- TRC_BNEP
09-01 10:59:44.509  7520  7554 I         : BTE_InitTraceLevels -- TRC_BTM
09-01 10:59:44.509  7520  7554 I         : BTE_InitTraceLevels -- TRC_GAP
09-01 10:59:44.509  7520  7554 I         : BTE_InitTraceLevels -- TRC_PAN,
09-01 10:59:44.509  7520  7554 I         : BTE_InitTraceLevels -- TRC_SAP
09-01 10:59:44.509  7520  7554 I         : BTE_InitTraceLevels -- TRC_SDP
09-01 10:59:44.509  7520  7554 I         : BTE_InitTraceLevels -- TRC_GATT,
09-01 10:59:44.509  7520  7554 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 10:59:44.509  7520  7554 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-01 10:59:44.509  7520  7554 I         : BTE_InitTraceLevels -- TRC_BTIF,
09-01 10:59:44.509  7520  7554 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-01 10:59:44.599  7520  7554 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-01 10:59:44.609  7520  7554 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4304ed1 
,09-01 10:59:44.609  7520  7554 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4304ed1 
,09-01 10:59:44.619  7520  7538 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-01 10:59:44.629  7520  7538 E bt-btif : Calling BTA_HhEnable
,09-01 10:59:44.629  7520  7538 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-01 10:59:44.629  7520  7538 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-01 10:59:44.629  7520  7538 E BluetoothServiceJni: populateRssiValuesNative
09-01 10:59:44.629  7520  7538 I bluedroid: getModelRssiValues
,09-01 10:59:44.629  7520  7538 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-01 10:59:44.629  7520  7538 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-01 10:59:44.629  1015  1015 D SettingsProvider: name = bluetooth_name
,09-01 10:59:44.629  7520  7538 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-01 10:59:44.639  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:44.639  7520  7538 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-01 10:59:44.639  7520  7538 D BluetoothAdapterProperties: Scan Mode:20
,09-01 10:59:44.639  7520  7538 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 10:59:44.639  7520  7538 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,09-01 10:59:44.639  7520  7538 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,09-01 10:59:44.649  7520  7538 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-01 10:59:44.649  7520  7538 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-01 10:59:44.649  7520  7538 E bt-btif : btif_sock_init: !vhci_init
09-01 10:59:44.649  7520  7538 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-01 10:59:44.649  7520  7538 D IOP_DB_BT: db_open: db_open : handle 3024138256l, read 13894 bytes onto local cache
09-01 10:59:44.649  7520  7538 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
09-01 10:59:44.649  7520  7538 D IOP_DB_BT: db_query: result 1
09-01 10:59:44.649  7520  7538 I         : iop_db_open: iop_db_open status 0
,09-01 10:59:44.649  7520  7538 D bte_conf: Device ID record 1 : primary
09-01 10:59:44.649  7520  7538 D bte_conf:   vendorId            = 0075
09-01 10:59:44.649  7520  7538 D bte_conf:   vendorIdSource      = 0001
09-01 10:59:44.649  7520  7538 D bte_conf:   product             = 0100
09-01 10:59:44.649  7520  7538 D bte_conf:   version             = 0200
09-01 10:59:44.649  7520  7538 D bte_conf:   clientExecutableURL = 
09-01 10:59:44.649  7520  7538 D bte_conf:   serviceDescription  = 
09-01 10:59:44.649  7520  7538 D bte_conf:   documentationURL    = 
09-01 10:59:44.649  7520  7538 D bte_conf: bte_load_did_conf no section named DID2.
,09-01 10:59:44.649  7520  7576 E bt_mct  : hci lib postload completed
,09-01 10:59:44.649  7520  7538 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-01 10:59:44.649  7520  7535 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-01 10:59:44.649  7520  7535 D BluetoothAdapterProperties: ScanMode =  20
,09-01 10:59:44.649  7520  7535 D BluetoothAdapterProperties: State =  11
,09-01 10:59:44.649  1015  1462 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-01 10:59:44.649  7520  7535 D BluetoothAdapterProperties: Setting state to 12
,09-01 10:59:44.649  7520  7535 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-01 10:59:44.659  7520  7538 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-01 10:59:44.659  7520  7538 D BluetoothAdapterProperties: Scan Mode:21
,09-01 10:59:44.659  7520  7538 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 10:59:44.659  1015  1319 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-01 10:59:44.659  1015  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-01 10:59:44.659  1015  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:44.659  1015  1319 D SettingsProvider: selectionArgs: false
09-01 10:59:44.659  1015  1319 D SettingsProvider: selectionArgs: 1002
09-01 10:59:44.659  1015  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:44.659  1015  1319 D SettingsProvider: ret = -1
,09-01 10:59:44.659  7520  7535 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 10:59:44.659  7520  7535 D BluetoothAdapterService: updateAdapterState state is 12
,09-01 10:59:44.659  1015  1472 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:44.659  1015  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-01 10:59:44.669  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:44.669  1015  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:44.669  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:44.669  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:44.669  7520  7535 D BluetoothAdapterService: Autoconnection is available 
09-01 10:59:44.669  7520  7535 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-01 10:59:44.669  7520  7535 D BluetoothAdapterService: starting service from this receiver
,09-01 10:59:44.669  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:44.669  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:44.669  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-01 10:59:44.679  1422  6918 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:44.689  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:44.689  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:44.689  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:44.689  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:44.689  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:44.689  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:44.689  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:44.689  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:44.689  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:44.689  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:44.689  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:44.689  7520  7535 I BluetoothAdapterState: Entering On State from state = 11
,09-01 10:59:44.689  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-01 10:59:44.689  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:44.689  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:44.689  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:44.689  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:44.699  1422  6918 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:44.699  6726  6726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:44.699  1300  7466 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 10:59:44.699  1300  7466 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:44.699  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-01 10:59:44.699  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 10:59:44.699  7520  7520 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-01 10:59:44.699  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:44.699  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:44.699  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:44.709  1300  1300 D BluetoothA2dp: Proxy object connected
09-01 10:59:44.709  1300  1300 D A2dpProfile: Bluetooth service connected
09-01 10:59:44.709  6726  6734 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 10:59:44.709  6726  6734 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 10:59:44.709  1451  2463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:44.709  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:44.709  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:44.709  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:44.709  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:44.709  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:44.709  1451  2463 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:44.709  1439  6185 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 10:59:44.709  1439  6185 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:44.719  1176  1792 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 10:59:44.719  1176  1792 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:44.719  1300  1309 D Bluetoothsap: onBluetoothStateChange: up=true
09-01 10:59:44.719  1300  1309 D Bluetoothsap: Binding service...
,09-01 10:59:44.719  1300  1309 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-01 10:59:44.719  7520  7520 I BluetoothPbapService: Handler(): got msg=1
,09-01 10:59:44.719  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-01 10:59:44.719  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-01 10:59:44.719  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:44.719  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:44.719  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-01 10:59:44.719  1015  1495 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-01 10:59:44.719  1300  1309 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-01 10:59:44.729  7520  7528 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 10:59:44.729  1422  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:44.729  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:44.729  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:44.729  7520  7580 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-01 10:59:44.729  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:44.729  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:44.729  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:44.729  1422  1445 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:44.729  1300  1300 D Bluetoothsap: BluetoothSAP Proxy object connected
09-01 10:59:44.729  1300  1300 D SapProfile: Bluetooth service connected
09-01 10:59:44.729  1300  1300 D Bluetoothsap: getConnectedDevices()
,09-01 10:59:44.729  1300  1309 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:44.739  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:44.739  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:44.739  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:44.739  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:44.739  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:44.739  1300  1309 E BluetoothHeadset: BluetoothHeadset service is binded
09-01 10:59:44.739  1300  1300 D HeadsetProfile: Bluetooth service connected
09-01 10:59:44.739  1422  1438 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:44.739  1422  1438 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:44.739  7520  7528 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:44.739  7520  7528 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 10:59:44.739  7520  7580 D BluetoothSocket: bindListen(): myUserId = 0
09-01 10:59:44.739  1300  7466 D BluetoothMap: onBluetoothStateChange: up=true
09-01 10:59:44.739  7520  7580 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 10:59:44.739  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-01 10:59:44.739  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-01 10:59:44.739  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:44.739  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:44.739  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:44.739  1300  1313 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-01 10:59:44.739  1300  1300 D BluetoothMap: Proxy object connected,
,09-01 10:59:44.739  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-01 10:59:44.739  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-01 10:59:44.749  7520  7580 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-01 10:59:44.749  7520  7580 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 10:59:44.749  7520  7580 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 10:59:44.749  7520  7580 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e9e6efb
09-01 10:59:44.749  1300  1300 D MapProfile: Bluetooth service connected
09-01 10:59:44.749  1300  1300 D BluetoothMap: getConnectedDevices()
,09-01 10:59:44.749  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:44.749  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:44.749  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:44.749  1451  1867 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 10:59:44.749  1451  1867 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 10:59:44.749  7520  7580 D BluetoothSocket: channel: 19
09-01 10:59:44.749  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:44.749  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:44.749  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-01 10:59:44.749  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
09-01 10:59:44.749  7520  7580 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-01 10:59:44.749  1300  7466 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:44.749  1300  7466 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:44.749  7408  7424 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:44.749  7408  7424 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:44.749  1422  6918 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:44.749  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:44.749  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:44.749  1300  1300 D BluetoothInputDevice: Proxy object connected
09-01 10:59:44.749  1300  1300 D HidProfile: Bluetooth service connected
09-01 10:59:44.749  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:44.759  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:44.759  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:44.759  1422  6918 E BluetoothHeadset: BluetoothHeadset service is binded
09-01 10:59:44.759  1015  1044 D BluetoothPan: Binding service...
,09-01 10:59:44.759  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-01 10:59:44.759  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-01 10:59:44.759  1937  2159 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 10:59:44.759  1937  2159 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 10:59:44.759  1300  1313 D BluetoothPan: Binding service...
,09-01 10:59:44.759  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,09-01 10:59:44.899  1015  1044 I art     : Explicit concurrent mark sweep GC freed 29401(1696KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.350ms total 142.574ms
09-01 10:59:44.899  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-01 10:59:44.899  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 10:59:44.909  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:44.909  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:44.909  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:44.909  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 10:59:44.909  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-01 10:59:44.909  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp,
09-01 10:59:44.909  1300  1300 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 10:59:44.909  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-01 10:59:44.909  1300  1300 D PanProfile: Bluetooth service connected
09-01 10:59:44.909  1015  1015 D BluetoothA2dp: Proxy object connected
09-01 10:59:44.909  1300  1309 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 10:59:44.909  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-01 10:59:44.909  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-01 10:59:44.909  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:44.909  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:44.909  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:44.919  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-01 10:59:44.919  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-01 10:59:44.919  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:44.919  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
09-01 10:59:44.919  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
09-01 10:59:44.919  1300  1300 D BluetoothPbap: Proxy object connected
09-01 10:59:44.919  1300  1300 D PbapServerProfile: Bluetooth service connected
,09-01 10:59:44.919  1422  1422 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@355f6a94, true
,09-01 10:59:44.919  1422  1422 D BluetoothHeadset: registerMessageListener
,09-01 10:59:44.919  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,09-01 10:59:44.929  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-01 10:59:44.929  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:44.929  1176  1176 D BluetoothTile:  getBluetoothState : 12
,09-01 10:59:44.929  1874  1874 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-01 10:59:44.939  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:44.939  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:44.939  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:44.939  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-01 10:59:44.939  1015  1134 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-01 10:59:44.939  7520  7539 D HeadsetService: registerMessageListener
,09-01 10:59:44.939  7520  7539 D HeadsetService: registerMessageListener
,09-01 10:59:44.939  7520  7544 D HeadsetStateMachine: Disconnected process message: 70
09-01 10:59:44.939  7520  7544 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2067eb18
09-01 10:59:44.939  1015  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-01 10:59:44.939  1422  1422 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-01 10:59:44.939  1422  1422 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-01 10:59:44.939  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 10:59:44.939  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:44.939  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:44.939  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:44.939  1176  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:44.949  7520  7584 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-01 10:59:44.949  1176  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:44.949  1422  1422 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-01 10:59:44.949  1300  1300 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-01 10:59:44.949  1422  1422 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-01 10:59:44.949  1300  1300 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-01 10:59:44.949  1422  1422 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-01 10:59:44.949  1300  1300 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-01 10:59:44.949  1300  1300 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-01 10:59:44.959  1176  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:44.959  7520  7584 D BluetoothSocket: bindListen(): myUserId = 0
09-01 10:59:44.959  7520  7584 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 10:59:44.959  7520  7544 D HeadsetStateMachine: Disconnected process message: 9
,09-01 10:59:44.959  7520  7544 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-01 10:59:44.959  7520  7584 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-01 10:59:44.959  7520  7584 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 10:59:44.959  7520  7584 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 10:59:44.959  7520  7584 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22709971
09-01 10:59:44.959  7520  7584 D BluetoothSocket: channel: 5
,09-01 10:59:44.959  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 10:59:44.969  1015  1495 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-01 10:59:44.969  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-01 10:59:44.969  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:44.969  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:44.969  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-01 10:59:44.969   283   698 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-01 10:59:44.969   283   698 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-01 10:59:44.969   283   698 V voice   : voice_set_parameters: exit with code(-2)
09-01 10:59:44.969   283   698 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-01 10:59:44.969   283   698 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-01 10:59:44.969   283   698 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-01 10:59:44.969   283   698 V audio_hw_primary: adev_set_parameters: exit
09-01 10:59:44.969  7520  7544 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
09-01 10:59:44.989  1300  1300 D DockEventReceiver: finishStartingService: stopping service
09-01 10:59:44.989  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
09-01 10:59:44.989  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:44.999  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
09-01 10:59:44.999  7520  7520 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
09-01 10:59:44.999  7520  7520 D BtConfig.SecureMode: isSecureModeOn:false
09-01 10:59:45.009  1015  1462 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:45.009  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
09-01 10:59:45.009  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:45.009  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:45.009  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:45.019  1937  1937 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-01 10:59:45.019  1015  1467 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:45.019  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-01 10:59:45.029  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:45.029  1015  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:45.029  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:45.039  1937  1937 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-01 10:59:45.039  1015  1495 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-01 10:59:45.049  1937  7591 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-01 10:59:45.049  1015  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:45.049  1015  1319 W ActivityManager: userId = 0, bbcId = -10000,
09-01 10:59:45.049  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:45.049  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:45.059  7520  7594 D BluetoothSocket: bindListen(): myUserId = 0
,09-01 10:59:45.059  7520  7594 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 10:59:45.059  7520  7594 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
09-01 10:59:45.059  7520  7594 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 10:59:45.059  7520  7594 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 10:59:45.059  7520  7594 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@5e5c273
,09-01 10:59:45.069  7520  7594 D BluetoothSocket: channel: 12
09-01 10:59:45.069  7520  7594 I BtOppRfcommListener: Accept thread started.
,09-01 10:59:45.069  1015  1134 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:45.069  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:45.069  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:45.069  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:45.079  1937  7591 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-01 10:59:45.589  6726  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:45.589  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:45.589  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:45.589  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:45.589  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:45.589  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:45.589  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:45.589  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:45.589  6726  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:45.589  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 10:59:45.589  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24291fad added. We now have 8 listener(s)
,09-01 10:59:45.589  6726  6780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:45.599  1015  1462 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-01 10:59:45.599  1015  1462 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-01 10:59:45.599  1015  1462 D SecContentProvider2: mCursor = null
,09-01 10:59:45.599  1015  1462 D WifiService: setWifiEnabled: false pid=6726, uid=10171
,09-01 10:59:45.599  1015  1462 D SettingsProvider: name = wifi_on
,09-01 10:59:45.609  6726  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:45.609  1015  1481 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-01 10:59:45.609  1015  1481 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-01 10:59:45.609  1015  1481 D SecContentProvider2: mCursor = null
,09-01 10:59:45.609  1015  1481 D WifiService: setWifiEnabled: true pid=6726, uid=10171
,09-01 10:59:45.609  1015  1481 W ActivityManager: Permission Denial: getCurrentUser() from pid=6726, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-01 10:59:45.609  1015  1481 W WifiService: Failed getting userId using ActivityManagerNative
09-01 10:59:45.609  1015  1481 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6726, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-01 10:59:45.609  1015  1481 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-01 10:59:45.609  1015  1481 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-01 10:59:45.609  1015  1481 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-01 10:59:45.609  1015  1481 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-01 10:59:45.609  1015  1481 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-01 10:59:45.609  1015  1481 D SettingsProvider: name = wifi_on
,09-01 10:59:45.619  1015  1124 E WifiHW  : ##################### set firmware type 0 #####################
,09-01 10:59:45.959  1015  1042 D Tethering: interfaceAdded wlan0
,09-01 10:59:45.959  1015  1129 E Tethering: No numeric data
,09-01 10:59:45.969  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-01 10:59:45.969  1015  1129 D Tethering: clearTetheredNotification()
,09-01 10:59:45.969  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,09-01 10:59:45.969  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:45.969  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-01 10:59:45.969  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 10:59:45.979  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 10:59:45.979  1176  1176 D HotspotTile: updateTetherState():false, false
,09-01 10:59:45.979  1015  1121 V NetworkStats: performPollLocked() took 10ms
09-01 10:59:45.979  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:45.979  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:45.979  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:45.989  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 10:59:45.989  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:45.989  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:45.989  1015  1129 D Tethering: InitialState.processMessage what=4
,09-01 10:59:45.989  1015  1129 E Tethering: No numeric data
,09-01 10:59:45.989  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-01 10:59:45.999  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-01 10:59:45.999  1176  1176 D HotspotTile: updateTetherState():false, false,
09-01 10:59:45.999  1015  1129 D Tethering: clearTetheredNotification()
09-01 10:59:45.999  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-01 10:59:45.999  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit,
09-01 10:59:45.999  1015  1042 D Tethering: interfaceAdded p2p0
09-01 10:59:45.999  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:45.999  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
09-01 10:59:45.999  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 10:59:45.999  1015  1121 V NetworkStats: performPollLocked() took 8ms
,09-01 10:59:46.009  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:46.009  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 10:59:46.009  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-01 10:59:46.009  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-01 10:59:46.009  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:46.009  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:46.009   278  1014 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-01 10:59:46.009   278  1014 D SoftapController: Softap fwReload - Ok
,09-01 10:59:46.009   278  1014 D CommandListener: Setting iface cfg
09-01 10:59:46.009   278  1014 D CommandListener: Trying to bring down wlan0
,09-01 10:59:46.009   278  1014 D CommandListener: Clearing all IP addresses on wlan0
,09-01 10:59:46.019  1015  1124 E WifiHW  : supplicant_name : p2p_supplicant
,09-01 10:59:46.029  1015  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,09-01 10:59:46.029  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 10:59:46.029  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-01 10:59:46.029  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:46.029  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:46.029  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:46.029  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:46.039  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:46.039  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-01 10:59:46.039  1176  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-01 10:59:46.039  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:46.039  1176  1176 D HotspotTile: onReceive : 2, 0
,09-01 10:59:46.039  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:46.049  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:46.049  1015  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-01 10:59:46.049  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-01 10:59:46.049   288   288 E SMD     : DCD OFF
,09-01 10:59:46.049  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:46.049  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:46.049  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 10:59:46.049  1627  1627 I Hs20UtilService: Starting #19,
09-01 10:59:46.059  1627  1701 I Hs20UtilService: Message received 5011
,09-01 10:59:46.059  6553  6553 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
09-01 10:59:46.059  6553  6553 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 10:59:46.059  6553  6553 D SecurityLogAgent: StateMachine : Current State = 1
09-01 10:59:46.059  6553  6553 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 10:59:46.059  7605  7605 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-01 10:59:46.059  7605  7605 I wpa_supplicant: Successfully initialized wpa_supplicant
09-01 10:59:46.059  7605  7605 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-01 10:59:46.079  7605  7605 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-01 10:59:46.079   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7605
09-01 10:59:46.079   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-01 10:59:46.079  7605  7605 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-01 10:59:46.079  7605  7605 I wpa_supplicant: ssSupport state is = 1
09-01 10:59:46.079  7605  7605 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-01 10:59:46.079  7605  7605 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-01 10:59:46.079   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7605
,09-01 10:59:46.079   405   405 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-01 10:59:46.239   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-01 10:59:46.239  7605  7605 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-01 10:59:46.279  7605  7605 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-01 10:59:46.289  7605  7605 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-01 10:59:46.289  7605  7605 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-01 10:59:46.289   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7605
09-01 10:59:46.289   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-01 10:59:46.289  7605  7605 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-01 10:59:46.289  7605  7605 I wpa_supplicant: ssSupport state is = 1
09-01 10:59:46.299  7605  7605 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:46.299  7605  7605 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 10:59:46.299  7605  7605 E wpa_supplicant: SIM READ ERROR
09-01 10:59:46.299  7605  7605 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-01 10:59:46.299  7605  7605 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 10:59:46.299  7605  7605 E wpa_supplicant: SIM READ ERROR
09-01 10:59:46.299  7605  7605 I wpa_supplicant: Blacklist: Clear (all) 
09-01 10:59:46.299  7605  7605 I wpa_supplicant: wpa_default_ap_write_once
09-01 10:59:46.299  7605  7605 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,09-01 10:59:46.299  7605  7605 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:46.299  7605  7605 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-01 10:59:46.299  7605  7605 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:46.299  7605  7605 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-01 10:59:46.299  7605  7605 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-01 10:59:46.299  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-01 10:59:46.299  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 10:59:46.299  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:46.399  7605  7605 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-01 10:59:46.549  7605  7605 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-01 10:59:46.549  7605  7605 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-01 10:59:46.559  7605  7605 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-01 10:59:46.559   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7605
09-01 10:59:46.559   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-01 10:59:46.569  7605  7605 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-01 10:59:46.569  7605  7605 I wpa_supplicant: ssSupport state is = 1,
09-01 10:59:46.569  7605  7605 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-01 10:59:46.569  7605  7605 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-01 10:59:46.579  7605  7605 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-01 10:59:46.579   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7605
09-01 10:59:46.579   405   405 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-01 10:59:46.579  7605  7605 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-01 10:59:46.579  7605  7605 I wpa_supplicant: ssSupport state is = 1
09-01 10:59:46.579  7605  7605 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:46.579  7605  7605 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 10:59:46.579  7605  7605 E wpa_supplicant: SIM READ ERROR
09-01 10:59:46.579  7605  7605 I wpa_supplicant: wpa_default_ap_write_once
09-01 10:59:46.579  7605  7605 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-01 10:59:46.579  7605  7605 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-01 10:59:46.589  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
09-01 10:59:46.589  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 10:59:46.589  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-01 10:59:46.589  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 10:59:46.589  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-01 10:59:46.589  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-01 10:59:46.639  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-01 10:59:46.639  1015  1134 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-01 10:59:46.639  1015  1134 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-01 10:59:46.639  1015  1134 D BatteryService: stay LED for fully charged
09-01 10:59:46.639  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-01 10:59:46.639  1015  1015 I MotionRecognitionService: Plugged
09-01 10:59:46.649  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-01 10:59:46.649  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-01 10:59:46.649  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate,
,09-01 10:59:46.649  1408  1408 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-01 10:59:46.649  1408  1408 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-01 10:59:46.659  7605  7605 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-01 10:59:46.659  7605  7605 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-01 10:59:46.669  7520  7520 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-01 10:59:46.669  7520  7544 D HeadsetStateMachine: Disconnected process message: 10
,09-01 10:59:46.679  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-01 10:59:46.679  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-01 10:59:46.679  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-01 10:59:46.739  7605  7605 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-01 10:59:46.739  7605  7605 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
,09-01 10:59:46.739  7605  7605 I wpa_supplicant: Skip scan - bUseNetwork false
,09-01 10:59:46.749  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,09-01 10:59:46.749  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-01 10:59:46.749  7605  7605 I wpa_supplicant: HOTSPOT20_ENABLE called
09-01 10:59:46.749  7605  7605 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:46.749  7605  7605 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 10:59:46.749  7605  7605 E wpa_supplicant: SIM READ ERROR
09-01 10:59:46.749  7605  7605 I wpa_supplicant: Blacklist: Clear (all) 
,09-01 10:59:46.769  7605  7605 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-01 10:59:46.779  7605  7605 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-01 10:59:46.779  1015  1124 D WifiConfigStore: Loading config and enabling all networks 
,09-01 10:59:46.779  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-01 10:59:46.779  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:46.779  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:46.779  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:46.779  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:46.779  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:46.779  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 10:59:46.779  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-01 10:59:46.779  1176  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-01 10:59:46.789  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
,09-01 10:59:46.789  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:46.789  1176  1176 D HotspotTile: onReceive : 3, 0
,09-01 10:59:46.789  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:46.789  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:46.789  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:46.789  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:46.789  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:46.789  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:46.789  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:46.789  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:46.789  1015  1319 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 10:59:46.789  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:46.799  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:46.799  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:46.799  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:46.799  1015  1124 E WifiConfigStore: Not a HS20
,09-01 10:59:46.799  6726  6726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:46.799  1015  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-01 10:59:46.799  1627  1627 I Hs20UtilService: Starting #20
,09-01 10:59:46.799  1627  1701 I Hs20UtilService: Message received 5011
,09-01 10:59:46.809  6553  6553 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-01 10:59:46.809  6553  6553 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 10:59:46.809  6553  6553 D SecurityLogAgent: StateMachine : Current State = 1
09-01 10:59:46.809  6553  6553 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 10:59:46.809  1015  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-01 10:59:46.809  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-01 10:59:46.809  7605  7605 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-01 10:59:46.809  7605  7605 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-01 10:59:46.809  7605  7605 I wpa_supplicant: reset timer : RESET_TIMER 0
09-01 10:59:46.809  7605  7605 I wpa_supplicant: P2P: Current p2p state = IDLE
09-01 10:59:46.809  7605  7605 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-01 10:59:46.809  7605  7605 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-01 10:59:46.809  7605  7605 I wpa_supplicant: First Scan Start
,09-01 10:59:46.809  7605  7605 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-01 10:59:46.809  1015  1124 D WifiNative-wlan0: Setting external_sim to 1
,09-01 10:59:46.809  1015  1124 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 10:59:46.809  1015  1124 I WifiNative-HAL: startHal
09-01 10:59:46.809  1015  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9eef688c
09-01 10:59:46.809  1015  1124 I WifiNative-HAL: Could not start hal
,09-01 10:59:46.819  6952  6952 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 10:59:46.819  1015  1124 E WifiNative-wlan0: do suspend true
,09-01 10:59:46.819  1015  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-01 10:59:46.819  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-01 10:59:46.819   278  1014 D CommandListener: Setting iface cfg
09-01 10:59:46.819   278  1014 D CommandListener: Trying to bring up p2p0
,09-01 10:59:46.819  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
09-01 10:59:46.819  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:46.819  1015  1148 I WifiNative-HAL: startHal
,09-01 10:59:46.819  1015  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-01 10:59:46.819  1015  1148 E wifi    : getStaticLongField sWifiHalHandle 0x993e09bc
09-01 10:59:46.819  1015  1123 D WifiP2pService: P2pEnablingState
09-01 10:59:46.819  1015  1148 I WifiNative-HAL: Could not start hal
09-01 10:59:46.819  1015  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-01 10:59:46.819  1015  1015 D RttService: SCAN_AVAILABLE : 3
,09-01 10:59:46.819  1015  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:46.819  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-01 10:59:46.819  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-01 10:59:46.819  1015  1124 E WifiNative-wlan0: invaild command id : 215
,09-01 10:59:46.819  1015  1148 E WifiScanningService: could not start HAL
,09-01 10:59:46.819  1015  1123 D WifiP2pService: P2p socket connection successful
09-01 10:59:46.819  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-01 10:59:46.819  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-01 10:59:46.819  1015  1124 E WifiNative-wlan0: invaild command id : 215
09-01 10:59:46.819  1015  1123 D WifiP2pService: P2pEnabledState
,09-01 10:59:46.829  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-01 10:59:46.829  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-01 10:59:46.829  7605  7605 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-01 10:59:46.829  7605  7605 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-01 10:59:46.829  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-01 10:59:46.829  7605  7605 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-01 10:59:46.829  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-01 10:59:46.829  1015  1124 E WifiStateMachine: Failed to set frequency band 0
,09-01 10:59:46.829  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 10:59:46.829  1015  1045 D WifiDisplayController: disconnect
09-01 10:59:46.829  1015  1045 D WifiDisplayController: updateConnection,
,09-01 10:59:46.829  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:46.829  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 10:59:46.829  1015  1124 D SecContentProvider2: mCursor = null,
09-01 10:59:46.829  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-01 10:59:46.829  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-01 10:59:46.829  1015  1495 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
09-01 10:59:46.829  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0,
,09-01 10:59:46.839  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 10:59:46.839  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-01 10:59:46.839  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:46.839  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer,
09-01 10:59:46.839  1015  1124 D SecContentProvider2: mCursor = null
09-01 10:59:46.839  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-01 10:59:46.839  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress
09-01 10:59:46.839  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,09-01 10:59:46.839  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-01 10:59:46.839  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-01 10:59:46.839  1015  1123 D WifiP2pService: DeviceAddress: 0a:76:28
,09-01 10:59:46.839  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 10:59:46.839  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-01 10:59:46.839  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-01 10:59:46.839  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
09-01 10:59:46.839  1015  1045 D WifiDisplayController:  secondary type: null
09-01 10:59:46.839  1015  1045 D WifiDisplayController:  wps: 0
09-01 10:59:46.839  1015  1045 D WifiDisplayController:  grpcapab: 0
09-01 10:59:46.839  1015  1045 D WifiDisplayController:  devcapab: 0
09-01 10:59:46.839  1015  1045 D WifiDisplayController:  status: 3
09-01 10:59:46.839  1015  1045 D WifiDisplayController:  wfdInfo: null
09-01 10:59:46.839  1015  1045 D WifiDisplayController:  groupownerAddress: null
09-01 10:59:46.839  1015  1045 D WifiDisplayController:  GOdeviceName: null
09-01 10:59:46.839  1015  1045 D WifiDisplayController:  interfaceAddress: 
09-01 10:59:46.839  1015  1045 D WifiDisplayController:  SConnectInfo : null
,09-01 10:59:46.839  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-01 10:59:46.839  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 10:59:46.839  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-01 10:59:46.839  1300  2241 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 10:59:46.849  6990  6990 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 10:59:46.849  6990  6990 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-01 10:59:46.849  6990  6990 D FileShare-Client: Outbound.stopDelayTimer - 
,09-01 10:59:46.849  7005  7005 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 10:59:46.859  1015  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-01 10:59:46.859  1015  1123 D WifiP2pService: InactiveState
,09-01 10:59:46.859  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
,09-01 10:59:46.859  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-01 10:59:46.859  7605  7605 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-01 10:59:46.859  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
,09-01 10:59:46.859  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-01 10:59:46.989  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-01 10:59:46.989  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,09-01 10:59:46.989  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-01 10:59:47.629  6726  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-01 10:59:47.629  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:47.629  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:47.629  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:47.629  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:47.629  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:47.629  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:47.629  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:47.639  6726  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:47.639  6726  6780 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-01 10:59:47.639  6726  6780 D io.jxcore.node.LifeCycleMonitor: onActivityResumed,
,09-01 10:59:47.649  6726  6780 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1ef209ff Bundle[{}],
09-01 10:59:47.649  6726  6780 I io.jxcore.node.LifeCycleMonitor: start: OK
09-01 10:59:47.649  6726  6780 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-01 10:59:47.649  6726  6780 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-01 10:59:47.649  6726  6780 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-01 10:59:47.649  6726  6780 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-01 10:59:47.649  6726  6780 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-01 10:59:47.649  6726  6780 I System.out: Running OutgoingSocketThread
,09-01 10:59:47.659  6726  7615 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1325)
,09-01 10:59:47.659  6726  7615 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 53114
,09-01 10:59:47.659  6726  7615 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-01 10:59:48.029  7605  7605 I wpa_supplicant: nl80211: Received scan results (25 BSSes),
,09-01 10:59:48.039  7605  7605 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-01 10:59:48.039  1015  7611 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,09-01 10:59:48.039  7605  7605 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-01 10:59:48.039  7605  7605 I wpa_supplicant: Trying to associate with  'G700'
,09-01 10:59:48.039  7605  7605 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-01 10:59:48.039  7605  7605 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,09-01 10:59:48.059  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:48.059  1015  1124 D SecContentProvider2: mCursor = null
,09-01 10:59:48.149  7605  7605 E wpa_supplicant: Cmd 35605 not handled
,09-01 10:59:48.149  7605  7605 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-01 10:59:48.149  7605  7605 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
09-01 10:59:48.149  7605  7605 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-01 10:59:48.149  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:48.149  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:48.149  7605  7605 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-01 10:59:48.149  7605  7605 I wpa_supplicant: Associated with F4.99.3E
09-01 10:59:48.149  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-01 10:59:48.149  7605  7605 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-01 10:59:48.149  7605  7605 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-01 10:59:48.149  7605  7605 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-01 10:59:48.149  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:48.149  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:48.149  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:48.149  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:48.149  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:48.149  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:48.159  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-01 10:59:48.159  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
,09-01 10:59:48.159  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,09-01 10:59:48.159  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:48.159  1015  1124 D SecContentProvider2: mCursor = null
,09-01 10:59:48.159  1015  1129 E Tethering: No numeric data
,09-01 10:59:48.159  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-01 10:59:48.159  1015  1124 D SecContentProvider2: mCursor = null
,09-01 10:59:48.169  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-01 10:59:48.169  1015  1129 D Tethering: clearTetheredNotification()
,09-01 10:59:48.169  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-01 10:59:48.169  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:48.169  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:48.169  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 10:59:48.169  7605  7605 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-01 10:59:48.169  7605  7605 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-01 10:59:48.169  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 10:59:48.169  1176  1176 D HotspotTile: updateTetherState():false, false
09-01 10:59:48.179  7605  7605 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-01 10:59:48.179  7605  7605 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030,
,09-01 10:59:48.179  7605  7605 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-01 10:59:48.179  1015  1121 V NetworkStats: performPollLocked() took 10ms
,09-01 10:59:48.179  7605  7605 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-01 10:59:48.179  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-01 10:59:48.179  7605  7605 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-01 10:59:48.179  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-01 10:59:48.179  7605  7605 I wpa_supplicant: Blacklist: Clear (temp) 
,09-01 10:59:48.179  7605  7605 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-01 10:59:48.179  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-01 10:59:48.179  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
09-01 10:59:48.179  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:48.179  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:48.189  1015  1124 D WifiNative-wlan0: callSECApiVoid - ID [50],
,09-01 10:59:48.189  1015  1124 E WifiConfigStore: setLastSelectedConfiguration -1,
,09-01 10:59:48.199  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 10:59:48.199  1015  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-01 10:59:48.199  1015  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-01 10:59:48.199  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:48.199  1015  1126 E ConnectivityService: updateNetworkInfo()
09-01 10:59:48.199  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:48.199  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 10:59:48.199  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:48.199  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:48.199  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:48.199  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-01 10:59:48.209  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 10:59:48.209  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:48.209  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:48.209  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:48.209  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:48.209  1627  1627 I Hs20UtilService: Starting #21
09-01 10:59:48.209  1627  1701 I Hs20UtilService: Message received 5007
09-01 10:59:48.209  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-01 10:59:48.209  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:48.209  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 10:59:48.219  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-01 10:59:48.219  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-01 10:59:48.219  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-01 10:59:48.219  1300  2241 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 10:59:48.229  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 10:59:48.239   278  1014 D CommandListener: Setting iface cfg
,09-01 10:59:48.239  1015  1124 E WifiStateMachine: Start Dhcp Watchdog 3
,09-01 10:59:48.239  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-01 10:59:48.239  1015  1124 D SecContentProvider2: mCursor = null
,09-01 10:59:48.249  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 10:59:48.249  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-01 10:59:48.249  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:48.249  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:48.249  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:48.249  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:48.259  1015  1124 E WifiNative-wlan0: do suspend false
,09-01 10:59:48.259  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,09-01 10:59:48.259  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:48.259  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
09-01 10:59:48.259  1015  1124 D SecContentProvider2: mCursor = null
,09-01 10:59:48.479  7618  7618 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-01 10:59:48.479  7618  7618 I dhcpcd  : version 5.5.6 starting
,09-01 10:59:48.479  7618  7618 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-01 10:59:48.539  7618  7618 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-01 10:59:48.539  7618  7618 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-01 10:59:48.539  7618  7618 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-01 10:59:48.539  7618  7618 I dhcpcd  : bssid match
09-01 10:59:48.539  7618  7618 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,09-01 10:59:48.609  7618  7618 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,09-01 10:59:48.659  6726  6780 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1326),
09-01 10:59:48.659  6726  6780 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1326)
09-01 10:59:48.659  6726  6780 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1331)
09-01 10:59:48.659  6726  6780 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-01 10:59:48.659  6726  6780 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1332)
09-01 10:59:48.659  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:48.659  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19f762e2 added. We now have 2 listener(s)
,09-01 10:59:48.669  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-01 10:59:48.669  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:48.669  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 10:59:48.669  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:48.669  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b422673 added. We now have 9 listener(s)
09-01 10:59:48.669  6726  6780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:48.669  7618  7618 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,09-01 10:59:48.669  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 10:59:48.679  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-01 10:59:48.689  6726  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:48.689  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:48.689  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:48.689  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:48.689  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:48.689  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:48.689  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,09-01 10:59:48.689  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:48.689  6726  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 10:59:48.689  6726  6780 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:48.689  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:48.689  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37e509a9 added. We now have 3 listener(s)
09-01 10:59:48.689  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:48.689  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:48.689  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-01 10:59:48.689  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:48.689  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:48.689  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:48.689  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@372ccb2e added. We now have 10 listener(s),
09-01 10:59:48.689  6726  6780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:48.689  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:48.689  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:48.689  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:48.689  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:48.689  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:48.689  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:48.689  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:48.689  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19f762e2 removed from the list
09-01 10:59:48.689  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:48.689  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b422673 removed from the list
09-01 10:59:48.689  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:48.689  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:48.699  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:48.699  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:48.699  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:48.699  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:48.699  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:48.699  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b422673 not in the list
09-01 10:59:48.699  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:48.699  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:48.699  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:48.699  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:48.699  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:48.699  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@372ccb2e removed from the list
09-01 10:59:48.699  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:48.699  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:48.699  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:48.699  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:48.699  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37e509a9 removed from the list
09-01 10:59:48.699  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:48.699  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@378eb6cf added. We now have 2 listener(s)
09-01 10:59:48.699  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-01 10:59:48.699  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:48.699  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:48.699  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:48.699  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1691185c added. We now have 9 listener(s)
09-01 10:59:48.699  6726  6780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:48.699  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 10:59:48.709  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:48.719  6726  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-01 10:59:48.719  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:48.719  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:48.719  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:48.719  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:48.719  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:48.719  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:48.719  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:48.719  6726  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 10:59:48.719  6726  6780 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:48.719  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:48.719  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e6c3a added. We now have 3 listener(s)
09-01 10:59:48.719  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:48.719  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:48.719  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-01 10:59:48.719  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:48.719  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:48.719  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:48.719  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e69f0eb added. We now have 10 listener(s)
09-01 10:59:48.719  6726  6780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:48.719  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 10:59:48.719  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 10:59:48.719  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-01 10:59:48.719  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:48.719  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 10:59:48.729  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,09-01 10:59:48.739  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
09-01 10:59:48.739  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 10:59:48.739  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 10:59:48.739  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-01 10:59:48.739  6726  6780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 10:59:48.749  7520  7583 D BtGatt.GattService: registerClient() - UUID=555b6f8a-62ca-4d7f-b82f-dc35b83f6e88
,09-01 10:59:48.789  7520  7538 D BtGatt.GattService: onClientRegistered() - UUID=555b6f8a-62ca-4d7f-b82f-dc35b83f6e88, clientIf=6
09-01 10:59:48.789  6726  6736 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-01 10:59:48.789  7520  7531 D BtGatt.GattService: start scan with filters
,09-01 10:59:48.799  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 10:59:48.799  7520  7543 D BtGatt.ScanManager: handling starting scan,
09-01 10:59:48.799  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 10:59:48.799  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
09-01 10:59:48.799  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 10:59:48.799  7520  7543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:48.799  7520  7538 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-01 10:59:48.799  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:48.799  7520  7543 D BtGatt.ScanManager: allow scan with filters
09-01 10:59:48.799  7520  7543 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-01 10:59:48.799  7520  7543 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-01 10:59:48.799  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 10:59:48.799  7520  7538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-01 10:59:48.799  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:48.799  7520  7543 D BtGatt.ScanManager: Starting BLE batch scan
09-01 10:59:48.799  7520  7543 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-01 10:59:48.799  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-01 10:59:48.799  6726  6726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 10:59:48.809  7520  7538 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-01 10:59:48.809  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:48.809  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 10:59:48.809  7520  7538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-01 10:59:48.809  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:48.819  6726  6780 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-01 10:59:48.819  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:48.819  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 10:59:48.819  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:48.819  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 10:59:48.819  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 10:59:48.819  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:48.819  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
09-01 10:59:48.819  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:48.819  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 10:59:48.819  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 10:59:48.819  7520  7531 D BtGatt.GattService: stopScan() - queue size =1,
09-01 10:59:48.819  7520  7543 D BtGatt.ScanManager: filter size is 1,
09-01 10:59:48.819  7520  7543 D BtGatt.ScanManager: delete FilterIndex - 3
,09-01 10:59:48.829  7520  7528 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-01 10:59:48.829  7520  7538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-01 10:59:48.829  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:48.829  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 10:59:48.829  7520  7543 D BtGatt.ScanManager: stopping BLe Batch
,09-01 10:59:48.829  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 10:59:48.829  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 10:59:48.829  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 10:59:48.829  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 10:59:48.829  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:48.829  7520  7538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-01 10:59:48.829  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:48.829  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 10:59:48.829  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 10:59:48.829  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 10:59:48.829  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:48.829  7520  7543 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-01 10:59:48.839  7520  7538 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
09-01 10:59:48.839  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:48.839  6726  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:48.839  6726  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:48.839  6726  6726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:48.839  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:48.839  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:48.839  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:48.839  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:48.839  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:48.839  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:48.839  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:48.849  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@378eb6cf removed from the list
,09-01 10:59:48.849  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:48.849  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1691185c removed from the list
09-01 10:59:48.849  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:48.849  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:48.849  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:48.849  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:48.849  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:48.849  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:48.849  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:48.849  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1691185c not in the list
09-01 10:59:48.849  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:48.849  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:48.869  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:48.869  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:48.869  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:48.869  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e69f0eb removed from the list
09-01 10:59:48.869  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:48.869  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:48.869  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:48.869  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:48.869  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e6c3a removed from the list
,09-01 10:59:48.869  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:48.869  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3974b0c7 added. We now have 2 listener(s)
,09-01 10:59:48.869  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
09-01 10:59:48.869  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:48.869  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:48.869  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:48.869  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57616f4 added. We now have 9 listener(s)
09-01 10:59:48.869  6726  6780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:48.869  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 10:59:48.869  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:48.879  6726  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:48.879  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:48.879  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:48.879  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:48.879  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:48.879  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:48.879  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:48.879  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:48.879  6726  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-01 10:59:48.879  6726  6780 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:48.879  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:48.879  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9824892 added. We now have 3 listener(s)
,09-01 10:59:48.879  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-01 10:59:48.879  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:48.879  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:48.879  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:48.879  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31819263 added. We now have 10 listener(s)
09-01 10:59:48.879  6726  6780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:48.879  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:48.879  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:48.879  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 10:59:48.879  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 10:59:48.879  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-01 10:59:48.879  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 10:59:48.889  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 10:59:48.899  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 10:59:48.909  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 10:59:48.909  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 10:59:48.919  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 10:59:48.919  6726  6780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 10:59:48.919  1015  1040 W ProcessCpuTracker: Skipping unknown process pid 7640
,09-01 10:59:48.919  7520  7531 D BtGatt.GattService: registerClient() - UUID=100760f8-aee5-48a6-85f2-b3d2854e2951
,09-01 10:59:48.919  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:48.929  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:48.969  7520  7538 D BtGatt.GattService: onClientRegistered() - UUID=100760f8-aee5-48a6-85f2-b3d2854e2951, clientIf=6
,09-01 10:59:48.969  6726  6734 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-01 10:59:48.969  7520  7583 D BtGatt.GattService: start scan with filters
,09-01 10:59:48.969  7520  7543 D BtGatt.ScanManager: handling starting scan
09-01 10:59:48.969  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 10:59:48.969  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 10:59:48.969  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 10:59:48.969  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-01 10:59:48.969  7520  7538 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-01 10:59:48.969  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:48.969  7520  7543 D BtGatt.ScanManager: allow scan with filters
09-01 10:59:48.969  7520  7543 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-01 10:59:48.969  7520  7543 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-01 10:59:48.969  7520  7538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-01 10:59:48.969  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:48.969  7520  7543 D BtGatt.ScanManager: Starting BLE batch scan
09-01 10:59:48.969  7520  7543 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-01 10:59:48.969  7520  7538 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-01 10:59:48.969  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:48.969  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 10:59:48.969  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 10:59:48.969  6726  6726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:48.979  7520  7538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-01 10:59:48.979  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:48.979  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 10:59:48.979  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 10:59:48.989  6726  6780 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-01 10:59:48.989  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:48.989  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:48.989  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 10:59:48.989  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 10:59:48.989  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:48.989  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 10:59:48.989  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 10:59:48.989  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3974b0c7 removed from the list
09-01 10:59:48.989  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:48.989  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57616f4 removed from the list
09-01 10:59:48.989  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:48.989  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 10:59:48.989  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:48.989  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left,
09-01 10:59:48.989  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:48.989  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 10:59:48.989  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:48.989  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 10:59:48.989  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:48.989  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57616f4 not in the list
,09-01 10:59:48.989  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:48.999  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-01 10:59:48.999  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:48.999  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 10:59:48.999  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 10:59:48.999  7520  7583 D BtGatt.GattService: stopScan() - queue size =1
09-01 10:59:48.999  7520  7543 D BtGatt.ScanManager: filter size is 1
09-01 10:59:48.999  7520  7543 D BtGatt.ScanManager: delete FilterIndex - 4
09-01 10:59:48.999  7520  7528 D BtGatt.GattService: unregisterClient() - clientIf=6
09-01 10:59:48.999  7520  7538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-01 10:59:48.999  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:48.999  7520  7543 D BtGatt.ScanManager: stopping BLe Batch
09-01 10:59:48.999  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 10:59:48.999  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 10:59:48.999  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 10:59:48.999  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 10:59:48.999  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-01 10:59:49.009  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:49.009  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 10:59:49.009  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 10:59:49.009  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 10:59:49.009  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:49.009  6726  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:49.009  7520  7538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-01 10:59:49.009  6726  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:49.009  6726  6726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:49.009  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:49.009  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:49.009  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:49.009  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31819263 removed from the list
09-01 10:59:49.009  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:49.009  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:49.009  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:49.009  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:49.009  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9824892 removed from the list
09-01 10:59:49.009  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:49.009  7520  7543 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-01 10:59:49.009  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:49.009  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ff0f1bf added. We now have 2 listener(s)
,09-01 10:59:49.009  7520  7538 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-01 10:59:49.009  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:49.019  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-01 10:59:49.019  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 10:59:49.019  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:49.019  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 10:59:49.019  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bf9508c added. We now have 9 listener(s)
09-01 10:59:49.019  6726  6780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:49.019  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 10:59:49.019  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:49.029  6726  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:49.029  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:49.029  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:49.029  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:49.029  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:49.029  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:49.029  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:49.029  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:49.029  6726  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:49.029  6726  6780 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:49.029  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:49.029  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382a57ea added. We now have 3 listener(s)
,09-01 10:59:49.029  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:49.029  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-01 10:59:49.029  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-01 10:59:49.029  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 10:59:49.029  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:49.029  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-01 10:59:49.029  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39cceadb added. We now have 10 listener(s)
09-01 10:59:49.029  6726  6780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:49.029  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:49.029  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 10:59:49.029  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 10:59:49.029  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:49.029  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 10:59:49.039  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 10:59:49.039  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 10:59:49.039  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 10:59:49.039  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-01 10:59:49.039  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 10:59:49.039  6726  6780 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 10:59:49.049  7520  7583 D BtGatt.GattService: registerClient() - UUID=6bd1c100-ba05-4699-bdd2-69f642cd13d8
,09-01 10:59:49.049   288   288 E SMD     : DCD OFF,
,09-01 10:59:49.069  1015  1124 E WifiNative-wlan0: do suspend true
,09-01 10:59:49.089  7520  7538 D BtGatt.GattService: onClientRegistered() - UUID=6bd1c100-ba05-4699-bdd2-69f642cd13d8, clientIf=6
,09-01 10:59:49.089  6726  6736 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-01 10:59:49.089  7520  7531 D BtGatt.GattService: start scan with filters
,09-01 10:59:49.089  7520  7543 D BtGatt.ScanManager: handling starting scan
,09-01 10:59:49.089  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 10:59:49.089  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 10:59:49.089  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 10:59:49.089  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 10:59:49.089  7520  7538 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-01 10:59:49.099  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:49.099  7520  7543 D BtGatt.ScanManager: allow scan with filters
09-01 10:59:49.099  7520  7543 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-01 10:59:49.099  7520  7543 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-01 10:59:49.099  7520  7538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-01 10:59:49.099  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:49.099  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:49.099  7520  7543 D BtGatt.ScanManager: Starting BLE batch scan
,09-01 10:59:49.099  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,09-01 10:59:49.099  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-01 10:59:49.099  7520  7543 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-01 10:59:49.099  1015  1124 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-01 10:59:49.099  1015  1124 E WifiStateMachine: VerifyingLinkState enter
,09-01 10:59:49.109  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 10:59:49.109  6726  6726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:49.109  1015  1126 E ConnectivityService: updateNetworkInfo()
09-01 10:59:49.109  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:49.109  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:49.109  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.109  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.109  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.109  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:49.109  7520  7538 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-01 10:59:49.109  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:49.119  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-01 10:59:49.119  1015  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-01 10:59:49.119  1015  1126 D ConnectivityService: Adding iface wlan0 to network 504
,09-01 10:59:49.119  7520  7538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-01 10:59:49.119  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:49.119  1015  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,09-01 10:59:49.119  1015  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-01 10:59:49.129  1015  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
09-01 10:59:49.129  1015  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-01 10:59:49.129  1015  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-01 10:59:49.129  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-01 10:59:49.129  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:49.129  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.129  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.129  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.129  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.129  1015  1124 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-01 10:59:49.139  1015  1467 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-01 10:59:49.139  1015  1467 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-01 10:59:49.139  1015  1467 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:49.139  1015  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:49.139  1015  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:49.139  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:49.139  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:49.139  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:49.139  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:49.139  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:49.139  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 10:59:49.139  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:49.139  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ff0f1bf removed from the list
09-01 10:59:49.139  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:49.139  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bf9508c removed from the list
09-01 10:59:49.139  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:49.139  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 10:59:49.139  1627  1627 I Hs20UtilService: Starting #22
,09-01 10:59:49.139  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-01 10:59:49.139  1627  1701 I Hs20UtilService: Message received 5007
,09-01 10:59:49.149  1015  1126 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504,
,09-01 10:59:49.149  1015  1126 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,09-01 10:59:49.149  1015  1126 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
09-01 10:59:49.149  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-01 10:59:49.149  1015  1126 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-01 10:59:49.149  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-01 10:59:49.149  1015  1126 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-01 10:59:49.149  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-01 10:59:49.149  1015  1126 D ConnectivityService: LTETest block dns file not exists
09-01 10:59:49.149  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
09-01 10:59:49.149  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
09-01 10:59:49.149  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:49.149  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:49.149  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.149  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.149  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.149  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:49.159  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-01 10:59:49.159  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-01 10:59:49.159  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.159  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-01 10:59:49.159  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.159  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:49.159  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-01 10:59:49.159  1300  1300 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-01 10:59:49.169  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:49.169  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-01 10:59:49.169  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:49.169  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:49.169  1015  1126 V NetworkStats: updateIfacesLocked()
09-01 10:59:49.169  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:49.169  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
09-01 10:59:49.169  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:49.169  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 10:59:49.169  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:49.169  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:49.169  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:49.169  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bf9508c not in the list
09-01 10:59:49.169  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:49.169  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 10:59:49.169  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:49.169  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 10:59:49.169  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 10:59:49.169  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:49.169  1015  1126 V NetworkStats: performPollLocked() took 6ms
,09-01 10:59:49.179  7520  7539 D BtGatt.GattService: stopScan() - queue size =1
,09-01 10:59:49.179  7520  7543 D BtGatt.ScanManager: filter size is 1
,09-01 10:59:49.179  7520  7539 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-01 10:59:49.179  7520  7543 D BtGatt.ScanManager: delete FilterIndex - 5
09-01 10:59:49.179  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 10:59:49.179  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 10:59:49.179  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 10:59:49.179  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 10:59:49.179  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 10:59:49.179  7520  7538 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-01 10:59:49.179  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:49.179  7520  7543 D BtGatt.ScanManager: stopping BLe Batch
,09-01 10:59:49.179  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:49.189  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-01 10:59:49.189  6726  6780 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 10:59:49.189  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 10:59:49.189  1015  1126 E ConnectivityService: updateNetworkInfo()
09-01 10:59:49.189  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-01 10:59:49.189  1015  1126 E ConnectivityService: updateNetworkInfo()
09-01 10:59:49.189  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 10:59:49.189  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:49.189  1015  1126 V NetworkStats: updateIfacesLocked()
09-01 10:59:49.189  7520  7538 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-01 10:59:49.189  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
,09-01 10:59:49.189  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:49.189  7520  7543 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-01 10:59:49.189  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:49.189  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:49.189  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:49.189  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-01 10:59:49.189  7520  7538 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-01 10:59:49.189  7520  7538 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:49.189  1015  1126 V NetworkStats: performPollLocked() took 5ms
,09-01 10:59:49.189  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:49.189  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:49.189  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:49.189  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:49.189  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:49.189  1015  1462 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 10:59:49.189  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:49.189  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-01 10:59:49.189  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:49.189  1015  1126 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-01 10:59:49.189  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39cceadb removed from the list
09-01 10:59:49.189  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:49.189  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:49.189  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:49.189  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:49.199  6726  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:49.199  1015  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-01 10:59:49.199  6726  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:49.199  6726  6726 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:49.199  1015  7616 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:49.199  1015  7616 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-01 10:59:49.199  1015  7616 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:49.199  1015  7616 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-01 10:59:49.199  1015  7616 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:49.199  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:49.199   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-01 10:59:49.199   278  1010 D Netd    : getNetworkForDns: using netid 504 for uid 1000
09-01 10:59:49.199  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382a57ea removed from the list
,09-01 10:59:49.199  1015  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:49.199  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:49.199  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-01 10:59:49.199  1015  1126 D ConnectivityService:    accepting network in place of null
09-01 10:59:49.199  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-01 10:59:49.199  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:49.199  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30a559b7 added. We now have 2 listener(s)
09-01 10:59:49.199  1451  1451 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-01 10:59:49.199  1451  1451 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-01 10:59:49.199  1627  1627 I Hs20UtilService: Starting #23
09-01 10:59:49.199  1015  1126 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-01 10:59:49.199  1015  1126 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-01 10:59:49.199  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-01 10:59:49.199  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 10:59:49.199  1627  1701 I Hs20UtilService: Message received 5007
09-01 10:59:49.199  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:49.209  1015  1126 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-01 10:59:49.209  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-01 10:59:49.209  1015  1129 D Tethering: MasterInitialState.processMessage what=3
,09-01 10:59:49.209  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
09-01 10:59:49.209  1015  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-01 10:59:49.209  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:49.209  1015  1121 V NetworkStats: updateIfacesLocked()
09-01 10:59:49.209  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-01 10:59:49.209  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-01 10:59:49.209  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 10:59:49.209  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:49.209  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:49.209  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32472524 added. We now have 9 listener(s)
09-01 10:59:49.209  6726  6780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:49.209  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:49.209  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 10:59:49.209  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-01 10:59:49.209  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-01 10:59:49.209  1300  1300 I NearbySettings: MountReceiver.onReceive - Keep current state
09-01 10:59:49.209  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-01 10:59:49.209  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
09-01 10:59:49.209  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-01 10:59:49.209  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-01 10:59:49.209  1176  1176 D StatusBar.NetworkController: updateDataNetType()
09-01 10:59:49.209  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-01 10:59:49.209  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-01 10:59:49.209  1176  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-01 10:59:49.209  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 10:59:49.209  4760  6790 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-01 10:59:49.219  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:49.219  1015  1121 V NetworkStats: performPollLocked() took 8ms
,09-01 10:59:49.219  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:49.219  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:49.219  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:49.219  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:49.219  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,09-01 10:59:49.219  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-01 10:59:49.219  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-01 10:59:49.219  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-01 10:59:49.219  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:49.219  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-01 10:59:49.219  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.219  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.219  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.219  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:49.219  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:49.219  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:49.219  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:49.229  1015  1322 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-01 10:59:49.229  1015  1322 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:49.229  1015  1322 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:49.229  1015  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:49.229  1015  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 10:59:49.229  6726  6780 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-01 10:59:49.229  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:49.229  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:49.229  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:49.229  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:49.229  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:49.229  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:49.229  6726  6780 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:49.229  1627  1627 I Hs20UtilService: Starting #24
,09-01 10:59:49.229  1627  1701 I Hs20UtilService: Message received 5007
,09-01 10:59:49.229  6726  6780 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:49.229  6726  6780 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:49.229  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:49.229  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@829fa42 added. We now have 3 listener(s)
,09-01 10:59:49.229  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:49.239  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-01 10:59:49.239  1300  1300 I NearbySettings: MountReceiver.onReceive - Keep current state
09-01 10:59:49.239  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-01 10:59:49.239  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:49.239  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:49.239  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:49.239  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@152bda53 added. We now have 10 listener(s)
09-01 10:59:49.239  6726  6780 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:49.239  6726  6780 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:49.239  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:49.239  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:49.239  6726  6780 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:49.239  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:49.239  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:49.239  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:49.239  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:49.239  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30a559b7 removed from the list
09-01 10:59:49.239  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:49.239  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32472524 removed from the list
09-01 10:59:49.239  6726  6780 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:49.239  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:49.239  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:49.239  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:49.239  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:49.239  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 10:59:49.239  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:49.239  6726  6780 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32472524 not in the list
09-01 10:59:49.239  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:49.239  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:49.239  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 10:59:49.239  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:49.239  6726  6780 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:49.239  6726  6780 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@152bda53 removed from the list
09-01 10:59:49.239  6726  6780 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:49.239  6726  6780 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:49.239  6726  6780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:49.239  6726  6780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:49.239  6726  6780 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@829fa42 removed from the list
,09-01 10:59:49.249  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-01 10:59:49.249  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything,
09-01 10:59:49.249  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-01 10:59:49.249  1015  1322 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-01 10:59:49.249  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:49.249  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-01 10:59:49.249  6726  6780 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:49.249  1015  1473 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-01 10:59:49.249  1015  1473 D SecContentProvider2: mCursor = null
,09-01 10:59:49.249  1015  1472 D SecContentProvider2: uri = 15 selection = getToastGravity
09-01 10:59:49.249  1015  1472 D SecContentProvider2: mCursor = null
09-01 10:59:49.249  1015  1319 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,09-01 10:59:49.249  1015  1319 D SecContentProvider2: mCursor = null
09-01 10:59:49.249  1015  1028 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-01 10:59:49.249  1015  1028 D SecContentProvider2: mCursor = null
,09-01 10:59:49.249  6726  7654 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1339, name: My test thread name)
09-01 10:59:49.249  6726  7654 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1339, thread name: My test thread name)
09-01 10:59:49.249  6726  7654 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1339, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-01 10:59:49.259  1015  1481 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-01 10:59:49.259  1015  1481 D SecContentProvider2: mCursor = null
09-01 10:59:49.259  6726  7655 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1341, name: My test thread name)
,09-01 10:59:49.259  6726  7655 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1341, thread name: My test thread name)
09-01 10:59:49.259  6726  7655 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1341, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-01 10:59:49.259  1015  1467 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-01 10:59:49.259  1015  1467 D SecContentProvider2: mCursor = null
09-01 10:59:49.259  6726  6780 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-01 10:59:49.259  6726  6780 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-01 10:59:49.259  6726  6780 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-01 10:59:49.259  6726  6780 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-01 10:59:49.259  6726  6780 D com.test.thalitest.ThaliTestRunner: Total duration: 24347 ms
09-01 10:59:49.259  6726  6780 I jxcore-log: *Native tests were executed*
09-01 10:59:49.259  6726  6780 I jxcore-log: 
09-01 10:59:49.259  6726  6780 I jxcore-log: Total number of executed tests:  80
09-01 10:59:49.259  6726  6780 I jxcore-log: 
09-01 10:59:49.259  6726  6780 I jxcore-log: Number of passed tests:  80
09-01 10:59:49.259  6726  6780 I jxcore-log: 
09-01 10:59:49.259  6726  6780 I jxcore-log: Number of failed tests:  0
09-01 10:59:49.259  6726  6780 I jxcore-log: 
09-01 10:59:49.259  6726  6780 I jxcore-log: Number of ignored tests:  0
09-01 10:59:49.259  6726  6780 I jxcore-log: 
09-01 10:59:49.259  6726  6780 I jxcore-log: Total duration:  24347
09-01 10:59:49.259  6726  6780 I jxcore-log: 
09-01 10:59:49.259  6726  6780 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-01 10:59:49.259  6726  6780 I jxcore-log: 
09-01 10:59:49.259  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:49.259  6726  6780 I jxcore-log: 
,09-01 10:59:49.269  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:49.269  6726  6780 I jxcore-log: 
09-01 10:59:49.269  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:49.269  6726  6780 I jxcore-log: 
09-01 10:59:49.269  6726  6726 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-01 10:59:49.269  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:49.269  6726  6780 I jxcore-log: 
09-01 10:59:49.269  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:49.269  6726  6780 I jxcore-log: 
09-01 10:59:49.269  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:49.269  6726  6780 I jxcore-log: 
09-01 10:59:49.279  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:49.279  6726  6780 I jxcore-log: 
09-01 10:59:49.279  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 10:59:49.279  6726  6780 I jxcore-log: 
09-01 10:59:49.279  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:49.279  6726  6780 I jxcore-log: 
09-01 10:59:49.279  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:49.279  6726  6780 I jxcore-log: 
09-01 10:59:49.279  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 10:59:49.279  6726  6780 I jxcore-log: 
09-01 10:59:49.279  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 10:59:49.279  6726  6780 I jxcore-log: 
09-01 10:59:49.279  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:49.279  6726  6780 I jxcore-log: 
,09-01 10:59:49.279  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:49.279  6726  6780 I jxcore-log: 
09-01 10:59:49.279  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 10:59:49.279  6726  6780 I jxcore-log: 
,09-01 10:59:49.279  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 10:59:49.279  6726  6780 I jxcore-log: 
09-01 10:59:49.279   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-01 10:59:49.289  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:49.289  6726  6780 I jxcore-log: 
,09-01 10:59:49.289  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:49.289  6726  6780 I jxcore-log: 
,09-01 10:59:49.289  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 10:59:49.289  6726  6780 I jxcore-log: 
09-01 10:59:49.289  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 10:59:49.289  6726  6780 I jxcore-log: 
,09-01 10:59:49.289  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 10:59:49.289  6726  6780 I jxcore-log: 
,09-01 10:59:49.289  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-01 10:59:49.289  6726  6780 I jxcore-log: 
09-01 10:59:49.289  1015  7616 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-01 10:59:49.289  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 10:59:49.289  6726  6780 I jxcore-log: 
,09-01 10:59:49.289  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 10:59:49.289  6726  6780 I jxcore-log: 
,09-01 10:59:49.289  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 10:59:49.289  6726  6780 I jxcore-log: 
,09-01 10:59:49.289  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 10:59:49.289  6726  6780 I jxcore-log: 
09-01 10:59:49.289  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:49.289  6726  6780 I jxcore-log: 
,09-01 10:59:49.289  1015  1319 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,09-01 10:59:49.299  1176  1176 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-01 10:59:49.309  1015  7616 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 08:59:49 GMT], X-Android-Received-Millis=[1472720389314], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472720389304]}
,09-01 10:59:49.309  1015  7616 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,09-01 10:59:49.309  1015  7616 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-01 10:59:49.309  1015  1126 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-01 10:59:49.309  1015  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-01 10:59:49.309  1015  1126 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-01 10:59:49.309  1015  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-01 10:59:49.309  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-01 10:59:49.309  1176  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-01 10:59:49.309  4760  6790 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-01 10:59:49.329  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
,09-01 10:59:49.329  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-01 10:59:49.329  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-01 10:59:49.329  1176  1176 D StatusBar.NetworkController: updateDataNetType()
09-01 10:59:49.329  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-01 10:59:49.329  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-01 10:59:49.329  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-01 10:59:49.329  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-01 10:59:49.339  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-01 10:59:49.339  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:49.339  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-01 10:59:49.339  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:49.339  6726  6726 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 10:59:49.339  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:49.339  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.339  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.339  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 10:59:49.339  6726  6780 I jxcore-log: 
,09-01 10:59:49.509  6726  6726 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 10:59:49.509  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 10:59:49.509  6726  6780 I jxcore-log: 
,09-01 10:59:49.559  7657  7657 D AndroidRuntime: 
09-01 10:59:49.559  7657  7657 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-01 10:59:49.559  7657  7657 D AndroidRuntime: CheckJNI is OFF,
09-01 10:59:49.559  7657  7657 D AndroidRuntime: readGMSProperty: start
09-01 10:59:49.559  7657  7657 D AndroidRuntime: readGMSProperty: already setted!!
09-01 10:59:49.559  7657  7657 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-01 10:59:49.559  7657  7657 D AndroidRuntime: readGMSProperty: could not set the property(default)!!,
09-01 10:59:49.559  7657  7657 D AndroidRuntime: readGMSProperty: end
09-01 10:59:49.559  7657  7657 D AndroidRuntime: addProductProperty: start
,09-01 10:59:49.699  6726  6726 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-01 10:59:49.699  7657  7657 E AffinityControl: AffinityControl: registerfunction enter
09-01 10:59:49.699  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 10:59:49.699  6726  6780 I jxcore-log: 
,09-01 10:59:49.699  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:49.719  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:49.729  7657  7657 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,09-01 10:59:49.729  6726  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:49.729  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:49.729  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:49.729  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:49.729  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:49.729  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:49.729  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:49.729  6726  6726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 10:59:49.729  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-01 10:59:49.739  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:49.739  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:49.739  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:49.739  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:49.739  6726  6726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:49.739  6726  6780 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:49.739  6726  6780 I jxcore-log: 
09-01 10:59:49.749  1015  1462 D PackageManager: START PACKAGE DELETE: observer{471486021}
09-01 10:59:49.749  1015  1462 D PackageManager: pkg{<packageName>}
09-01 10:59:49.749  1015  1462 D PackageManager: user{0}
09-01 10:59:49.749  1015  1462 D PackageManager: caller{2000}
09-01 10:59:49.749  1015  1462 D PackageManager: flags{2}
09-01 10:59:49.749  1015  1462 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-01 10:59:49.749  1015  1462 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,09-01 10:59:49.749  1015  1462 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-01 10:59:49.749  1015  1462 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-01 10:59:49.749  1015  1462 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-01 10:59:49.749  7667  7667 E Zygote  : MountEmulatedStorage()
09-01 10:59:49.749  7667  7667 E Zygote  : v2
09-01 10:59:49.749  7667  7667 I libpersona: KNOX_SDCARD checking this for 1000
09-01 10:59:49.749  7667  7667 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:49.759  7667  7667 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 10:59:49.759  1015  1040 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7667 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-01 10:59:49.759  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,09-01 10:59:49.759  1015  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-01 10:59:49.759  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-01 10:59:49.759  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
09-01 10:59:49.759  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-01 10:59:49.759  7667  7667 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:49.759  7667  7667 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:49.769  1015  1055 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,09-01 10:59:49.769  1015  1040 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,09-01 10:59:49.769  1015  1040 I ActivityManager: Killing 6726:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg,
,09-01 10:59:49.779  1015  1028 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin,
09-01 10:59:49.779  1015  1028 D SecContentProvider2: mCursor = null
,09-01 10:59:49.779  1015  1040 I ActivityManager:   Force finishing activity ActivityRecord{3a27daf5 u0 com.test.thalitest/.MainActivity t2}
,09-01 10:59:49.789  1015  1040 D InputDispatcher: Focus left window: 6726
,09-01 10:59:49.789   258   453 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
09-01 10:59:49.789   258  1095 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,09-01 10:59:49.809  7667  7667 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:49.809  7667  7667 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:49.819  1015  1040 D InputDispatcher: Focused application released
,09-01 10:59:49.819  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-01 10:59:49.819  1015  1040 D FocusedStackFrame: Set to : 0
09-01 10:59:49.819  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-01 10:59:49.829  1015  1040 W ActivityManager: mDVFSHelper.acquire()
,09-01 10:59:49.859  1015  1055 W PackageSettings: Skipping PackageSetting{20079ff2 com.example.hello/10168} due to missing metadata,
,09-01 10:59:49.889  1015  1040 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,09-01 10:59:49.909  1015  1055 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-01 10:59:49.919  1015  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-01 10:59:49.939  1479  1479 D Launcher: onRestart, Launcher: 719845797
,09-01 10:59:49.979  2646  2646 I art     : Explicit concurrent mark sweep GC freed 19549(1115KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 823us total 36.581ms
,09-01 10:59:49.979  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-01 10:59:49.989  4760  4760 I art     : Explicit concurrent mark sweep GC freed 6702(284KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/21MB, paused 1.315ms total 70.389ms
09-01 10:59:49.989  1874  1874 E SamsungIME: mOCRHelper is null
,09-01 10:59:49.999  4760  4769 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,09-01 10:59:49.999  7667  7667 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-01 10:59:49.999  7667  7667 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-01 10:59:49.999  7667  7667 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-01 10:59:50.009  1937  2157 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-01 10:59:50.009  1479  1479 D Launcher: onStart, Launcher: 719845797
,09-01 10:59:50.009  1479  1479 D Launcher.HomeView: onStart
,09-01 10:59:50.019  1479  1479 D Launcher: onResume, Launcher: 719845797
,09-01 10:59:50.019  1015  1472 D SettingsProvider: name = kids_home_mode
09-01 10:59:50.019  1015  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:50.019  1015  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:50.019  1015  1472 D SettingsProvider: selectionArgs: false
09-01 10:59:50.019  1015  1472 D SettingsProvider: selectionArgs: 10006
09-01 10:59:50.019  1015  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:50.019  1015  1472 D SettingsProvider: ret = -1
,09-01 10:59:50.019  1479  1479 D Launcher.HomeView: onResume
,09-01 10:59:50.039  1439  1439 D PersonaManager: isKioskContainerExistOnDevice,
,09-01 10:59:50.039  7667  7667 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-01 10:59:50.039  7667  7667 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-01 10:59:50.039  7667  7667 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-01 10:59:50.039  1479  1479 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
09-01 10:59:50.039  7667  7667 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:50.049  1015  1121 V NetworkStats: removeUidsLocked() for UIDs [10171]
09-01 10:59:50.049  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:50.049  1015  1121 V NetworkStats: performPollLocked(flags=0x3)
,09-01 10:59:50.049  1439  1439 D RegisteredServicesCache: empty dynamic service
09-01 10:59:50.049  1479  1479 D MenuAppsGridFragment: onResume
,09-01 10:59:50.049  1479  1479 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-01 10:59:50.059  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-01 10:59:50.059  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 10:59:50.059  1479  1479 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-01 10:59:50.069  1015  1028 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,09-01 10:59:50.069  1015  1028 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-01 10:59:50.069  1015  1121 V NetworkStats: performPollLocked() took 17ms
,09-01 10:59:50.069  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:50.089  1015  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
09-01 10:59:50.089  1015  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-01 10:59:50.089  1015  1039 W TextServicesManagerService: no available spell checker services found
,09-01 10:59:50.089  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-01 10:59:50.089  1777  1777 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-01 10:59:50.089  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:50.089  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:50.089  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:50.089  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:50.099  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:50.109  7685  7685 E Zygote  : MountEmulatedStorage(),
09-01 10:59:50.109  7685  7685 I libpersona: KNOX_SDCARD checking this for 10121
09-01 10:59:50.109  7685  7685 E Zygote  : v2
09-01 10:59:50.109  7685  7685 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:50.109  7685  7685 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:50.109  7685  7685 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:50.109  7685  7685 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:50.109  1015  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7685 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-01 10:59:50.109  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:50.109  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:50.109  1015  1473 D ActivityManager: handle home activity for 0
09-01 10:59:50.109  1015  1473 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
09-01 10:59:50.109  1015  1473 D KnoxTimeoutHandler: post home show event for user 0
09-01 10:59:50.109  1015  1473 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-01 10:59:50.109  1015  1473 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-01 10:59:50.109  1015  1473 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-01 10:59:50.109  1479  1479 D Launcher.HomeView: onPause
,09-01 10:59:50.119  1479  1479 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-01 10:59:50.129  1015  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-01 10:59:50.129  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:50.129  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:50.129  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:50.129  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:50.129  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:50.149  7685  7685 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:50.149  7685  7685 D ActivityThread: Added TimaKeyStore provider,
,09-01 10:59:50.149  7700  7700 E Zygote  : MountEmulatedStorage(),
09-01 10:59:50.149  7700  7700 I libpersona: KNOX_SDCARD checking this for 10031
09-01 10:59:50.149  7700  7700 E Zygote  : v2
09-01 10:59:50.149  7700  7700 I libpersona: KNOX_SDCARD not a persona
09-01 10:59:50.149  1015  1015 I art     : Explicit concurrent mark sweep GC freed 67955(4MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 25MB/37MB, paused 5.786ms total 229.500ms
,09-01 10:59:50.149  1015  1495 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7700 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
09-01 10:59:50.149  7700  7700 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 10:59:50.149  1015  1055 I art     : WaitForGcToComplete blocked for 125.647ms for cause Explicit
09-01 10:59:50.159  7700  7700 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-01 10:59:50.159  7700  7700 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:50.159  1015  1495 I ActivityManager: Killing 6804:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,09-01 10:59:50.159  1439  1439 D RegisteredComponentCache: Collect Tech packages for Knox
,09-01 10:59:50.169  1015  1472 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-01 10:59:50.169  1015  1472 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,09-01 10:59:50.169  1015  1472 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:50.169  1015  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:50.169  1015  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-01 10:59:50.169  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,09-01 10:59:50.179  2609  2620 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,09-01 10:59:50.189  7700  7700 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:50.189  7700  7700 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:50.189  1015  1028 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-01 10:59:50.189  1015  1028 D SecContentProvider2: mCursor = null
,09-01 10:59:50.189  1777  1777 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-01 10:59:50.189  1777  1777 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-01 10:59:50.199  1777  1777 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-01 10:59:50.199  1777  1777 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-01 10:59:50.209  1015  1126 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-01 10:59:50.209   258   258 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,09-01 10:59:50.209  7685  7685 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 10:59:50.209  7685  7685 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-01 10:59:50.209  7685  7685 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-01 10:59:50.209  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-01 10:59:50.209  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-01 10:59:50.219  1777  1777 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-01 10:59:50.219  1777  1777 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-01 10:59:50.219  1015  1322 D InputDispatcher: Focus entered window: 1479
,09-01 10:59:50.219  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-01 10:59:50.219  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-01 10:59:50.229  1479  1479 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-01 10:59:50.229  7685  7685 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:50.239  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{98c3e56 token=android.os.BinderProxy@1d04f3e0 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
09-01 10:59:50.239  1479  1479 D Launcher.HomeView: onStop
,09-01 10:59:50.249  1015  1467 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-01 10:59:50.249  1015  7716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-01 10:59:50.249  1015  1467 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6726 uid 10171
,09-01 10:59:50.249  7685  7685 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-01 10:59:50.259  1015  1473 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
09-01 10:59:50.259  1015  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,09-01 10:59:50.259  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,09-01 10:59:50.259  1015  1473 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:50.259  1015  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:50.259  1015  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
09-01 10:59:50.259  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
09-01 10:59:50.259  1874  1874 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-01 10:59:50.269  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:50.269  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-01 10:59:50.269  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-01 10:59:50.269  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,09-01 10:59:50.269  7685  7685 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-01 10:59:50.279  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,09-01 10:59:50.289  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-01 10:59:50.289  1015  1462 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 10:59:50.299  1015  1322 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 10:59:50.309  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:50.329  7190  7190 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-01 10:59:50.339  1015  1027 D PersonaManager: isKioskContainerExistOnDevice
,09-01 10:59:50.349  1015  1040 W ActivityManager: mDVFSHelper.release()
,09-01 10:59:50.359  1015  1462 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-01 10:59:50.359  1015  1462 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-01 10:59:50.359  1015  1462 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:50.359  1015  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:50.359  1015  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-01 10:59:50.359  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{27384c4c u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:150135
,09-01 10:59:50.399  1015  1055 I art     : Explicit concurrent mark sweep GC freed 12579(995KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.192ms total 247.914ms
,09-01 10:59:50.409  7116  7116 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,09-01 10:59:50.419  6952  7723 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-01 10:59:50.419  6952  7723 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-01 10:59:50.419  6952  7723 I System.out: (HTTPLog)-Static: isShipBuild true
09-01 10:59:50.419  6952  7723 I System.out: (HTTPLog)-Thread-1241-252877824: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-01 10:59:50.419  6952  7723 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:50.419  2779  7724 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-01 10:59:50.419   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-01 10:59:50.419   278  1010 D Netd    : getNetworkForDns: using netid 504 for uid 10102
09-01 10:59:50.419  2779  7724 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
09-01 10:59:50.419  2779  7724 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-01 10:59:50.429  7154  7154 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
09-01 10:59:50.429  7154  7154 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
09-01 10:59:50.429  7154  7154 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-01 10:59:50.429  7154  7154 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-01 10:59:50.429  7154  7154 I SA      : [OR] == isSIMCardReady false ==
,09-01 10:59:50.429  7154  7154 I SA      : [SCU] == networkStateCheck == true
,09-01 10:59:50.439  7154  7154 I SA      : [DM] getCountryCodeFromCSC : PL
,09-01 10:59:50.439  7154  7154 I SA      : isChinaCountryCode : false
09-01 10:59:50.439  7154  7154 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-01 10:59:50.439  7154  7154 I SA      : [OR] == networkStateCheck true ==
,09-01 10:59:50.459  7154  7154 I SA      : [OR] GetMyCountryZoneTask
,09-01 10:59:50.459  7154  7154 I SA      : [OR] onReceive END
,09-01 10:59:50.459  1226  1226 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:50.459  1015  1481 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
09-01 10:59:50.459  1015  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,09-01 10:59:50.469  6952  7723 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-01 10:59:50.469  1015  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-01 10:59:50.469  1015  1481 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:50.469  1015  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:50.469  1015  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,09-01 10:59:50.479  2779  7724 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,09-01 10:59:50.479  2779  7724 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,09-01 10:59:50.479  2779  7724 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,09-01 10:59:50.479  2779  7724 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,09-01 10:59:50.479  2779  7724 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,09-01 10:59:50.489  7154  7727 I SA      : [SRS] prepareGetMyCountryZone
,09-01 10:59:50.489  2779  7724 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,09-01 10:59:50.489  1015  1319 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
09-01 10:59:50.489  1015  1319 D SecContentProvider2: mCursor = null
09-01 10:59:50.489  2779  7724 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,09-01 10:59:50.489  2779  7724 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,09-01 10:59:50.489  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:50.499  2779  7724 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,09-01 10:59:50.509  6952  7723 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-01 10:59:50.509  1015  1028 I ActivityManager: Killing 7131:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,09-01 10:59:50.529  7154  7727 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-01 10:59:50.529  7154  7727 I SA      : [SSP] query invoked
,09-01 10:59:50.529  2779  7724 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-01 10:59:50.539  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:50.539  7154  7727 I SA      : [TPMU] GetMccFromDB : null
,09-01 10:59:50.539  7154  7727 I SA      : [SCU] getMccFromPreferece mcc = 260
09-01 10:59:50.539  7154  7727 I SA      : [LBE] isSupportCheckDomainRegion : false
09-01 10:59:50.539  7154  7727 I SA      : [TPM] isNoProxy(default) : true
,09-01 10:59:50.549  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:50.549  1015  1055 D PackageManager: delete codoeFile: 
,09-01 10:59:50.549  1015  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-01 10:59:50.549  1015  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 10:59:50.549  1015  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-01 10:59:50.559  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:50.559  1015  1055 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,09-01 10:59:50.559  1015  1055 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,09-01 10:59:50.569  1015  1055 D PackageManager: result of delete: 1{471486021}
,09-01 10:59:50.569  7154  7727 E File    : fail readDirectory() errno=2
,09-01 10:59:50.569  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-01 10:59:50.569  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-01 10:59:50.579  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,09-01 10:59:50.579  7657  7657 D AndroidRuntime: Shutting down VM
09-01 10:59:50.579  1015  1015 V EnterpriseBillingPolicy: uID is 10171
09-01 10:59:50.579  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-01 10:59:50.579  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-01 10:59:50.579  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-01 10:59:50.579  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-01 10:59:50.579  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-01 10:59:50.579  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-01 10:59:50.579  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-01 10:59:50.579  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-01 10:59:50.579  1015  1159 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,09-01 10:59:50.579  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:50.579  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
09-01 10:59:50.579  1015  3326 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-01 10:59:50.579  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,09-01 10:59:50.589  1015  1015 V EnterpriseBillingPolicy: uID is 10171
,09-01 10:59:50.589  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
,09-01 10:59:50.589  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-01 10:59:50.589  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:50.589  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,09-01 10:59:50.589  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,09-01 10:59:50.589  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-01 10:59:50.589  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-01 10:59:50.589  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:50.589  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-01 10:59:50.589  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-01 10:59:50.609  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
09-01 10:59:50.609  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
09-01 10:59:50.609  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
09-01 10:59:50.609  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-01 10:59:50.609  1015  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-01 10:59:50.609  1015  1055 D PackageManager: userId{-1}
09-01 10:59:50.609  1015  1055 D PackageManager: andCode{true}
,09-01 10:59:50.609  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:50.609  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,09-01 10:59:50.609  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
09-01 10:59:50.619  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-01 10:59:50.619  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-01 10:59:50.619  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:50.619  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:50.619  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:50.619  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:50.619  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-01 10:59:50.619  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-01 10:59:50.619  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-01 10:59:50.639  1176  1176 I StatusBar: Icon Only
09-01 10:59:50.639  1176  1176 D PanelView: There is/are notification(s) 
,09-01 10:59:50.639  7731  7731 E Zygote  : MountEmulatedStorage()
09-01 10:59:50.639  7731  7731 E Zygote  : v2
09-01 10:59:50.639  7731  7731 I libpersona: KNOX_SDCARD checking this for 10003
09-01 10:59:50.639  7731  7731 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:50.639  7731  7731 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:50.639  7731  7731 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:50.649  7731  7731 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:50.649  1015  1055 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7731 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-01 10:59:50.649  1015  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest,
,09-01 10:59:50.659  7520  7536 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-01 10:59:50.659  1015  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
09-01 10:59:50.659  7731  7731 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 10:59:50.659  7731  7731 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:50.699  1015  1319 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
09-01 10:59:50.699  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,09-01 10:59:50.699  1015  1319 W ActivityManager: userId = 0, bbcId = -10000,
09-01 10:59:50.699  1015  1319 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-01 10:59:50.699  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-01 10:59:50.709  1015  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:50.709  1015  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-01 10:59:50.709  1015  1481 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:50.709  1015  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:50.709  1015  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:50.719  7190  7190 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,09-01 10:59:50.719   278  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-01 10:59:50.719   278  1010 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,09-01 10:59:50.719  7190  7190 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,09-01 10:59:50.719  7190  7190 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,09-01 10:59:50.719  7190  7190 D InitializeManagerStateMachine: exit::IDLE
09-01 10:59:50.719  7190  7190 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,09-01 10:59:50.729  7190  7190 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
,09-01 10:59:50.729  7190  7190 D InitializeManagerStateMachine: exit::NETWORK_CHECK
,09-01 10:59:50.729  7190  7190 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
,09-01 10:59:50.729  7190  7190 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,09-01 10:59:50.729  7190  7190 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
,09-01 10:59:50.729  7190  7190 D InitializeManagerStateMachine: entry::SUCCESS
,09-01 10:59:50.729  7190  7190 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-01 10:59:50.739  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-01 10:59:50.739  4760  4760 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-01 10:59:50.739  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:50.739  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:50.739  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:50.739  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:50.749  1479  1479 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1d04f3e0 time:150523
,09-01 10:59:50.749  7750  7750 E Zygote  : MountEmulatedStorage(),
09-01 10:59:50.749  7750  7750 I libpersona: KNOX_SDCARD checking this for 10001
,09-01 10:59:50.749  7750  7750 E Zygote  : v2
09-01 10:59:50.749  7750  7750 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:50.749  4760  7243 I iu.UploadsManager: num queued entries: 0
09-01 10:59:50.749  7750  7750 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-01 10:59:50.749  4760  7243 I iu.UploadsManager: num updated entries: 0
,09-01 10:59:50.749  4760  7243 I iu.SyncManager: NEXT; no task
,09-01 10:59:50.749  7750  7750 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-01 10:59:50.759  7750  7750 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-01 10:59:50.759  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7750 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 10:59:50.759  7190  7190 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-01 10:59:50.759  7190  7190 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,09-01 10:59:50.759  7190  7190 D InitializeManagerStateMachine: exit::SUCCESS
09-01 10:59:50.759  7190  7190 D InitializeManagerStateMachine: entry::IDLE
,09-01 10:59:50.769  1015  1027 I ActivityManager: Killing 7173:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-01 10:59:50.769  7750  7750 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:50.779  7750  7750 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:50.789  7657  7657 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-01 10:59:50.799  1015  1472 I ActivityManager: Killing 7207:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-01 10:59:50.839  1015  1472 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-01 10:59:50.839  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:50.839  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:50.839  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:50.839  1015  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:50.859  7768  7768 E Zygote  : MountEmulatedStorage(),
09-01 10:59:50.859  7768  7768 E Zygote  : v2
09-01 10:59:50.859  7768  7768 I libpersona: KNOX_SDCARD checking this for 1000
09-01 10:59:50.859  7768  7768 I libpersona: KNOX_SDCARD not a persona
09-01 10:59:50.859  7768  7768 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-01 10:59:50.859  1015  1472 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7768 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-01 10:59:50.859  7768  7768 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-01 10:59:50.859  7768  7768 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-01 10:59:50.859  1015  1472 I ActivityManager: Killing 7501:com.samsung.android.sm/1000 (adj 15): empty #21
,09-01 10:59:50.869  1937  7748 I qtaguid : Tagging socket 49 with tag 1000040700000000{268436487,0} for uid -1, pid: 1937, getuid(): 10011
,09-01 10:59:50.899  7768  7768 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:50.899  7768  7768 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:50.959  7768  7768 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-01 10:59:50.959  7768  7768 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,09-01 10:59:50.959  7768  7768 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:50.959  7768  7768 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-01 10:59:50.969  7768  7768 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,09-01 10:59:50.969  7768  7768 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,09-01 10:59:50.969  7768  7768 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.,
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
,09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282),
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
,09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102),
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399),
09-01 10:59:50.969  7768  7768 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178),
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
,09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: ,	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:50.969  7768  7768 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-01 10:59:50.969  7768  7768 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
09-01 10:59:50.969  7768  7768 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,09-01 10:59:50.979  7768  7768 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:50.979  7768  7768 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:50.979  7768  7768 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-01 10:59:50.979  7768  7768 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,09-01 10:59:50.979  7768  7768 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,09-01 10:59:50.979  7768  7768 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
```
