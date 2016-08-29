#### Test 81418577b213184_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
08-29 11:25:11.723   288   288 E SMD     : DCD OFF
,08-29 11:25:12.433  6735  6735 D AndroidRuntime: 
08-29 11:25:12.433  6735  6735 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 11:25:12.433  6735  6735 D AndroidRuntime: CheckJNI is OFF
08-29 11:25:12.433  6735  6735 D AndroidRuntime: readGMSProperty: start
08-29 11:25:12.433  6735  6735 D AndroidRuntime: readGMSProperty: already setted!!
08-29 11:25:12.433  6735  6735 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-29 11:25:12.433  6735  6735 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-29 11:25:12.433  6735  6735 D AndroidRuntime: readGMSProperty: end
08-29 11:25:12.433  6735  6735 D AndroidRuntime: addProductProperty: start
08-29 11:25:12.563  6735  6735 E AffinityControl: AffinityControl: registerfunction enter
08-29 11:25:12.583  6735  6735 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 11:25:12.593  1016  1497 E PersonaManagerService: inState():  stateMachine is null !!
08-29 11:25:12.603  1016  1497 I PersonaManagerService: PersonaId don't exist
08-29 11:25:12.603  1016  1497 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-29 11:25:12.603  1016  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-29 11:25:12.623  1016  1497 W ActivityManager: mDVFSHelper.acquire()
08-29 11:25:12.623   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-29 11:25:12.623   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-29 11:25:12.633  1016  1497 D FocusedStackFrame: Set to : 0
08-29 11:25:12.633  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:12.633  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:12.633  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:12.633  1016  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:12.643  1016  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-29 11:25:12.643  1016  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-29 11:25:12.653  6746  6746 E Zygote  : MountEmulatedStorage()
08-29 11:25:12.653  6746  6746 E Zygote  : v2
08-29 11:25:12.653  6746  6746 I libpersona: KNOX_SDCARD checking this for 10171
08-29 11:25:12.653  6746  6746 I libpersona: KNOX_SDCARD not a persona
08-29 11:25:12.653  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-29 11:25:12.653  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-29 11:25:12.653  6746  6746 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 11:25:12.653   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-29 11:25:12.653  1016  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-29 11:25:12.653  1016  1497 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6746 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 11:25:12.653  1016  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 11:25:12.663  1016  1497 D InputDispatcher: Focused application set to: xxxx
08-29 11:25:12.663  1016  1497 D InputDispatcher: Focus left window: 1481
08-29 11:25:12.663  6746  6746 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 11:25:12.663  6735  6735 D AndroidRuntime: Shutting down VM
08-29 11:25:12.663  6746  6746 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-29 11:25:12.663  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 11:25:12.663  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-29 11:25:12.683  6746  6746 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 11:25:12.683  6746  6746 D ActivityThread: Added TimaKeyStore provider
08-29 11:25:12.683  1016  1329 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-29 11:25:12.683  1016  1016 V ActivityManager: Display changed displayId=0
08-29 11:25:12.703  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-29 11:25:12.713  1016  1329 D PersonaManager: isKioskContainerExistOnDevice
08-29 11:25:12.723  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-29 11:25:12.743   258   445 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-29 11:25:12.753   258  1987 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-29 11:25:12.753  1481  1481 D Launcher: onTrimMemory. Level: 20
08-29 11:25:12.753  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{2e790631 token=android.os.BinderProxy@16889cf6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-29 11:25:12.773  1016  1320 E Watchdog: !@Sync 3
08-29 11:25:12.833  6746  6746 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-29 11:25:12.873  6735  6735 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-29 11:25:12.873  6746  6746 I cr.library_loader: Time to load native libraries: 17 ms (timestamps 8128-8145)
08-29 11:25:12.873  6746  6746 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-29 11:25:12.893  6746  6746 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {30359dbf}
,08-29 11:25:12.893  6746  6746 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-29 11:25:12.903  6746  6746 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 11:25:12.943  6746  6746 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-29 11:25:12.943  6746  6746 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 11:25:12.953  6746  6746 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 11:25:12.983  6746  6746 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 11:25:12.983  6746  6746 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 11:25:12.983  6746  6746 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 11:25:12.983  6746  6746 I Adreno-EGL: Local Branch: 
08-29 11:25:12.983  6746  6746 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 11:25:12.983  6746  6746 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 11:25:12.983  6746  6746 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 11:25:13.053  6746  6746 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 11:25:13.103  6746  6746 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-29 11:25:13.103  6746  6746 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-29 11:25:13.113  6746  6746 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-29 11:25:13.113  6746  6746 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-29 11:25:13.213  1016  1041 W ActivityManager: Activity pause timeout for ActivityRecord{21605354 u0 com.test.thalitest/.MainActivity t2}
,08-29 11:25:13.223  6746  6746 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 11:25:13.243  6746  6746 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 11:25:13.253  6746  6746 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-29 11:25:13.253  6746  6746 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-29 11:25:13.253  6746  6746 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-29 11:25:13.263  6746  6746 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 11:25:13.263  6746  6746 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 11:25:13.333  6746  6786 D OpenGLRenderer: Render dirty regions requested: true
,08-29 11:25:13.333  1016  1134 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-29 11:25:13.333  1016  1134 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-29 11:25:13.333  1016  1134 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-29 11:25:13.333  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-29 11:25:13.333  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-29 11:25:13.343  6746  6773 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-29 11:25:13.343  6746  6746 V ActivityThread: updateVisibility : ActivityRecord{2cd4e79f token=android.os.BinderProxy@103158c0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-29 11:25:13.353  6746  6746 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-29 11:25:13.353  6746  6746 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-29 11:25:13.363   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-29 11:25:13.383  1016  1480 D InputDispatcher: Focus entered window: 6746
,08-29 11:25:13.383  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-29 11:25:13.383  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 11:25:13.393  6746  6746 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-29 11:25:13.393  6746  6786 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 11:25:13.393  6746  6786 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-29 11:25:13.393  6746  6786 D OpenGLRenderer: Enabling debug mode 0
,08-29 11:25:13.413  1016  1028 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-29 11:25:13.413  1016  6790 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 11:25:13.413  1177  1177 I StatusBar: Icon Only
,08-29 11:25:13.413  1177  1177 D PanelView: There is/are notification(s) 
,08-29 11:25:13.433  1016  1046 I ActivityManager: Displayed Component not be shown by security: +715ms (total +795ms)
,08-29 11:25:13.433  1016  1046 W ActivityManager: mDVFSHelper.release()
,08-29 11:25:13.433  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{21605354 u0 com.test.thalitest/.MainActivity t2} time:108704
,08-29 11:25:13.433  6746  6746 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-29 11:25:13.433  6746  6746 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@103158c0 time:108705
,08-29 11:25:13.433   258  1153 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-29 11:25:13.443   258   445 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-29 11:25:13.483  1872  1872 I SamsungIME: getCurrentCandidateView,
,08-29 11:25:13.553  6746  6746 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6746
,08-29 11:25:13.573  1872  1872 D SamsungIME: Dismiss ExpandCandiate
,08-29 11:25:13.723  1872  1872 I SamsungIME: getDebugLevel  : 0x4f4c
,08-29 11:25:13.743  6746  6746 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 11:25:13.773   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-29 11:25:13.773   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 11:25:13.773  1872  1872 I SamsungIME: getDebugLevel  : 0x4f4c
,08-29 11:25:13.783  1872  1872 I SamsungIME: KeybaordView init() : load resources
,08-29 11:25:13.813  1872  1872 I SamsungIME: getCurrentKeyboard
,08-29 11:25:13.813  1872  1872 I SamsungIME: getTextKeyboard
,08-29 11:25:13.833  1872  1872 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-29 11:25:13.833  6746  6793 D jxcore_app_log: JniHelper::setJavaVM(0xb86812b0), pthread_self() = -1195311232
,08-29 11:25:13.843  6746  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 11:25:13.843  6746  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 11:25:13.843  6746  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 11:25:13.843  6746  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 11:25:13.843  6746  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 11:25:13.843  6746  6793 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@123acd6d added. We now have 1 listener(s)
,08-29 11:25:13.853  6746  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-29 11:25:13.853  6746  6793 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 11:25:13.853  6746  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:25:13.853  6746  6793 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 11:25:13.863  6746  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 11:25:13.863  6746  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 11:25:13.863  6746  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 11:25:13.863  6746  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-29 11:25:13.863  6746  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 11:25:13.863  6746  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 11:25:13.863  6746  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 11:25:13.863  6746  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 11:25:13.863  6746  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 11:25:13.863  6746  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 11:25:13.863  6746  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 11:25:13.863  6746  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 11:25:13.863  6746  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 11:25:13.863  6746  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 11:25:13.863  6746  6793 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ac71f0 added. We now have 1 listener(s)
,08-29 11:25:13.863  6746  6793 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:25:13.873  6746  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:25:13.873  6746  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 11:25:13.873  6746  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 11:25:13.873  6746  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-29 11:25:13.873  6746  6793 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 11:25:13.873  6746  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:25:13.873  6746  6793 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27,
,08-29 11:25:13.883  6746  6793 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 11:25:13.883  6746  6793 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:13.883  6746  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:13.883  6746  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:13.883  6746  6793 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:13.883  6746  6793 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:13.883  6746  6793 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:13.883  6746  6793 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:25:13.883  6746  6793 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:25:13.883  6746  6793 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 11:25:13.883  6746  6793 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:25:13.883  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:13.883  6746  6793 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 11:25:13.883  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:13.923  6746  6746 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 11:25:14.393  6746  6800 W jxcore-log: Initializing JXcore engine,
08-29 11:25:14.393  6746  6800 W jxcore-log: JXcore engine is ready
,08-29 11:25:14.453  2029  2029 E audit   : type=1400 msg=audit(1472462714.453:205): avc:  denied  { ioctl } for  pid=6800 comm="Thread-1256" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2066 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 11:25:14.453  2029  2029 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-29 11:25:14.453  2029  2029 E audit   : type=1300 msg=audit(1472462714.453:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f3fb8f8 items=0 ppid=306 ppcomm=main pid=6800 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1256" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-29 11:25:14.453  2029  2029 E audit   : type=1320 msg=audit(1472462714.453:205): 
,08-29 11:25:14.463  6746  6800 W jxcore-log: Starting JXcore engine
,08-29 11:25:14.573  6746  6800 W jxcore-log: Platform android
08-29 11:25:14.573  6746  6800 W jxcore-log: 
08-29 11:25:14.573  6746  6800 W jxcore-log: Process ARCH arm
08-29 11:25:14.573  6746  6800 W jxcore-log: 
,08-29 11:25:14.723   288   288 E SMD     : DCD OFF,
,08-29 11:25:14.783  6746  6800 I jxcore-log: JXcore Cordova bridge is ready!
08-29 11:25:14.783  6746  6800 I jxcore-log: 
,08-29 11:25:14.783  6746  6800 W jxcore-log: JXcore engine is started
,08-29 11:25:14.783  6746  6793 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 11:25:14.793  6746  6746 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 11:25:17.733   288   288 E SMD     : DCD OFF
,08-29 11:25:17.913  1016  1048 I PowerManagerService: [PWL] Off : 50s ago
,08-29 11:25:17.993  1016  3365 D SSRM:n  : SIOP:: AP = 340
,08-29 11:25:18.773   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 11:25:19.773   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 11:25:20.463  5642  5642 D FactoryTest: Not factory mode
,08-29 11:25:20.463  5642  5642 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-29 11:25:20.473  5642  5642 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-29 11:25:20.473  5642  5642 D MTPRx   : still no open session command from host, so toast
,08-29 11:25:20.473  5642  5642 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-29 11:25:20.473  5642  5642 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-29 11:25:20.473  5642  5642 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115749
,08-29 11:25:20.483  1016  1479 E PersonaManagerService: inState():  stateMachine is null !!
,08-29 11:25:20.483  1016  1479 I PersonaManagerService: PersonaId don't exist
08-29 11:25:20.483  1016  1479 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-29 11:25:20.483  1016  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 11:25:20.483  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:20.483  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:20.483  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-29 11:25:20.493  1016  1479 W ActivityManager: mDVFSHelper.acquire()
,08-29 11:25:20.503  1016  1479 D PersonaManager: isKioskContainerExistOnDevice
,08-29 11:25:20.533  1016  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 11:25:20.533  1016  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 11:25:20.533  1016  1479 D InputDispatcher: Focused application set to: xxxx
08-29 11:25:20.533  1016  1479 D InputDispatcher: Focus left window: 6746
,08-29 11:25:20.533  5642  5642 E MTPRx   : started activity for popup,
,08-29 11:25:20.533  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 11:25:20.533  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 11:25:20.553  5642  5642 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-29 11:25:20.553  5642  5642 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-29 11:25:20.553  5642  5642 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-29 11:25:20.553  5642  5642 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 11:25:20.563  5642  5642 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 11:25:20.563  5642  5642 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 11:25:20.583  5642  5642 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-29 11:25:20.583  1016  1224 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 11:25:20.583  1016  1224 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-29 11:25:20.583  1016  1224 D InputDispatcher: Focused application set to: xxxx
,08-29 11:25:20.583  1016  1224 D InputDispatcher: Focus entered window: 6746
,08-29 11:25:20.593  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-29 11:25:20.593  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 11:25:20.593  1016  1329 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-29 11:25:20.593  1016  1329 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@9029977 attribute=null, token = android.os.BinderProxy@18de8087
,08-29 11:25:20.633  5642  5642 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-29 11:25:20.643  5642  5642 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-29 11:25:20.643  5642  5642 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-29 11:25:20.663  6746  6746 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 11:25:20.663  6746  6746 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-29 11:25:20.663  6746  6746 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 11:25:20.663  6746  6746 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-29 11:25:20.673  1016  1497 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-29 11:25:20.673  1016  1497 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-29 11:25:20.673  1016  1497 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-29 11:25:20.673  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-29 11:25:20.673  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-29 11:25:20.683  6746  6746 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 11:25:20.683  6746  6746 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 11:25:20.683  6746  6746 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@112430bc Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3d92c88d, 16908290=android.view.AbsSavedState$1@3d92c88d}, android:focusedViewId=100}]}]
,08-29 11:25:20.693  6746  6746 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-29 11:25:20.693  6746  6746 V ActivityThread: updateVisibility : ActivityRecord{2cd4e79f token=android.os.BinderProxy@103158c0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-29 11:25:20.693  6746  6746 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 11:25:20.693  6746  6746 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 11:25:20.693  6746  6746 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@103158c0 time:115960
,08-29 11:25:20.703  1016  1329 D PersonaManager: isKioskContainerExistOnDevice
,08-29 11:25:20.733   288   288 E SMD     : DCD OFF
,08-29 11:25:20.773   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 11:25:20.933  1016  1553 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 11:25:20.933  1016  1553 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 11:25:20.933  1016  1553 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 11:25:20.933  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 11:25:20.943  1016  1016 I MotionRecognitionService: Plugged
,08-29 11:25:20.943  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 11:25:20.943  1016  1553 D BatteryService: stay LED for fully charged
,08-29 11:25:20.943  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 11:25:20.943  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 11:25:20.953  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 11:25:20.953  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 11:25:20.963  3158  3158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 11:25:20.963  3158  3265 D HeadsetStateMachine: Disconnected process message: 10
,08-29 11:25:20.983  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 11:25:20.983  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-29 11:25:20.983  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 11:25:20.983  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 11:25:20.983  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 11:25:21.773   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 11:25:22.683  1016  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-29 11:25:22.773   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 11:25:23.493  1016  1041 W ActivityManager: mDVFSHelper.release(),
,08-29 11:25:23.733   288   288 E SMD     : DCD OFF,
,08-29 11:25:23.773   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-29 11:25:24.733  1016  1094 V AlarmManager: waitForAlarm result :4
,08-29 11:25:24.733  1016  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-29 11:25:24.773  2001  2001 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-29 11:25:24.813  1016  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 11:25:24.813  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-29 11:25:24.813  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:24.813  1016  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:24.813  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:24.863  4767  4767 D ConnectivityManager: CallingUid : 10011, CallingPid : 4767
,08-29 11:25:24.863  1016  1551 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-29 11:25:24.863  1016  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-29 11:25:24.863  1016  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-29 11:25:24.863  1016  1126 D ConnectivityService: apparently satisfied.  currentScore=60
,08-29 11:25:24.863  4767  6808 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 11:25:24.913  4767  6809 W DriveInitializer: Background init thread started
,08-29 11:25:24.953   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-29 11:25:24.953   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 11:25:24.953  4767  6809 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-29 11:25:25.003  2001  2001 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-29 11:25:25.043  1016  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 11:25:25.043  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-29 11:25:25.043  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:25.043  1016  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:25.043  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:25.073  1016  1553 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-29 11:25:25.073  1016  1553 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-29 11:25:25.083  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 11:25:25.083  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-29 11:25:25.083  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:25.083  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:25.083  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:25.123  1016  1551 I art     : Explicit concurrent mark sweep GC freed 36307(2006KB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 24MB/36MB, paused 2.609ms total 158.870ms
,08-29 11:25:25.133  2001  2001 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.,
,08-29 11:25:25.143  4767  6812 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-29 11:25:25.143  4767  6812 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-29 11:25:25.183  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:25.183  1016  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:25.183  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:25.213  4767  6809 W DriveInitializer: Background init thread ended
,08-29 11:25:25.303  1016  1224 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 11:25:25.303  1016  1224 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-29 11:25:25.303  1016  1224 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:25.303  1016  1224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:25.303  1016  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:25.343  1016  1224 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 11:25:25.343  1016  1224 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-29 11:25:25.343  1016  1224 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:25.343  1016  1224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:25.343  1016  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:25.393  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:25.393  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:25.393  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:25.393  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:25.423  1016  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:25.423  1016  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:25.423  1016  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:25.423  1016  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:25.483  1016  1553 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:25.483  1016  1553 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:25.483  1016  1553 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:25.483  1016  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:25.483  1016  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:25.483  1016  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:25.483  1016  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:25.493  1016  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:25.503  6822  6822 E Zygote  : MountEmulatedStorage()
,08-29 11:25:25.503  6822  6822 E Zygote  : v2
08-29 11:25:25.503  6822  6822 I libpersona: KNOX_SDCARD checking this for 10011
08-29 11:25:25.503  6822  6822 I libpersona: KNOX_SDCARD not a persona
,08-29 11:25:25.503  1016  1553 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6822 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-29 11:25:25.513  6822  6822 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:25.513  6822  6822 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 11:25:25.523  6822  6822 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 11:25:25.553  6822  6822 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:25.553  6822  6822 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:25.573  6822  6822 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-29 11:25:25.573  6822  6822 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-29 11:25:25.613  6822  6822 I MultiDex: VM with version 2.1.0 has multidex support
,08-29 11:25:25.613  6822  6822 I MultiDex: install
08-29 11:25:25.613  6822  6822 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-29 11:25:25.633  2001  2157 I art     : Explicit concurrent mark sweep GC freed 73772(4MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 10MB/17MB, paused 1.557ms total 89.625ms,
,08-29 11:25:25.643  6822  6822 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-29 11:25:25.703  6822  6822 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-29 11:25:25.713  6822  6822 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@34ac6cab: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
,08-29 11:25:25.713  6822  6822 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-29 11:25:25.733  6822  6822 D ChimeraCfgMgr: Reading stored module config
,08-29 11:25:25.813  6822  6836 I art     : Background sticky concurrent mark sweep GC freed 22940(1100KB) AllocSpace objects, 2(32KB) LOS objects, 1% free, 7MB/7MB, paused 8.817ms total 65.807ms
,08-29 11:25:25.833  6822  6839 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-29 11:25:25.843  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-29 11:25:25.853  6822  6836 W art     : Suspending all threads took: 10.159ms
,08-29 11:25:25.863  1016  1471 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:25.863  1016  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:25.863  1016  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:25.863  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:25.873  6822  6822 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-29 11:25:25.873  6822  6822 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
08-29 11:25:25.873  1016  1551 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:25.873  1016  1551 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:25.873  1016  1551 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:25.873  1016  1551 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 11:25:25.873  6822  6836 I art     : Background partial concurrent mark sweep GC freed 1035(190KB) AllocSpace objects, 1(101KB) LOS objects, 39% free, 7MB/12MB, paused 28.809ms total 58.306ms
08-29 11:25:25.903  2001  2001 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=0fa8b55d-b5c8-45e5-843c-decd1f8c92c7
,08-29 11:25:25.903  1016  1224 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-29 11:25:25.903  1016  1224 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-29 11:25:25.903  1016  1224 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:25.913  1016  1224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:25.913  1016  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:25.913  2001  2001 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-29 11:25:25.913  2001  2001 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-29 11:25:25.923  1016  1134 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:25.933  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:25.933  1016  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:25.933  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:25.993   283   694 D WVCdm   : Instantiating CDM.
,08-29 11:25:25.993   283   722 I WVCdm   : CdmEngine::OpenSession
,08-29 11:25:25.993   283   722 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-29 11:25:26.023   283   722 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory,
,08-29 11:25:26.033  4298  4391 I art     : Explicit concurrent mark sweep GC freed 1421(48KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 695us total 28.075ms
,08-29 11:25:26.043   283   722 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-29 11:25:26.103   283   722 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-29 11:25:26.103   283   283 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-29 11:25:26.103   283   283 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-29 11:25:26.103   283   283 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-29 11:25:26.113   283   283 D WVCdm   : PrepareKeyRequest: nonce=1212680991
,08-29 11:25:26.123  6822  6830 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-29 11:25:26.123  6822  6830 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 11:25:26.123  6822  6830 I System.out: (HTTPLog)-Static: isShipBuild true
08-29 11:25:26.123  6822  6830 I System.out: (HTTPLog)-Thread-1229-108635468: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-29 11:25:26.123  6822  6830 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 11:25:26.123   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 11:25:26.123   278  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-29 11:25:26.153  2001  2149 W GCoreFlp: No location to return for getLastLocation()
,08-29 11:25:26.173  6822  6830 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 11:25:26.183  6822  6830 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6822, getuid(): 10011
,08-29 11:25:26.193  1016  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:26.193  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:26.193  1016  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:26.193  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:26.193  1016  1134 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:26.203  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:26.203  1016  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:26.203  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:26.203  1016  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:26.203  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:26.203  1016  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 11:25:26.203  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:26.223  4767  6818 D UdcContextInitService: registered all accounts: true
,08-29 11:25:26.233  2001  2152 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 11:25:26.243  2001  2171 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-29 11:25:26.423  1016  1550 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-29 11:25:26.423  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-29 11:25:26.433  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:26.433  1016  1550 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 11:25:26.433  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:26.453  6822  6830 I qtaguid : Untagging socket 30
,08-29 11:25:26.733   288   288 E SMD     : DCD OFF
,08-29 11:25:26.953  1016  3399 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 11:25:27.143  6851  6851 I dex2oat : ----------------------------------------------------
08-29 11:25:27.143  6851  6851 I dex2oat : <SS>: S T A R T I N G . . .
08-29 11:25:27.143  6851  6851 I dex2oat : <SS>: Zip is absent. Canceled.
,08-29 11:25:27.143  6851  6851 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-29 11:25:27.203  6851  6851 I dex2oat : dex2oat took 57.741ms (threads: 4)
,08-29 11:25:27.213  6822  6830 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 11:25:27.213  6822  6830 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 11:25:27.213  6822  6830 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 11:25:27.213  6822  6830 I Adreno-EGL: Local Branch: 
08-29 11:25:27.213  6822  6830 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 11:25:27.213  6822  6830 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 11:25:27.213  6822  6830 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 11:25:27.303  6822  6830 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 11:25:27.303  6822  6830 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 11:25:27.303  6822  6830 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 11:25:27.303  6822  6830 I Adreno-EGL: Local Branch: 
08-29 11:25:27.303  6822  6830 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 11:25:27.303  6822  6830 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 11:25:27.303  6822  6830 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 11:25:27.343  6822  6830 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-29 11:25:27.343  6822  6830 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 11:25:27.343  6822  6830 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 11:25:27.343  6822  6830 I Adreno-EGL: Local Branch: 
08-29 11:25:27.343  6822  6830 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 11:25:27.343  6822  6830 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 11:25:27.343  6822  6830 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 11:25:27.413  1016  1134 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-29 11:25:27.413  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-29 11:25:27.413  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:27.413  1016  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:27.413  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:27.423  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 11:25:27.423  6746  6800 I jxcore-log: 
,08-29 11:25:27.423  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 11:25:27.423  6746  6800 I jxcore-log: 
,08-29 11:25:27.433  6746  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:27.433  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:27.433  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:27.433  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:27.433  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:27.433  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:27.433  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:25:27.433  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:25:27.433  6746  6800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:25:27.443  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 11:25:27.443  6746  6800 I jxcore-log: 
,08-29 11:25:27.443  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 11:25:27.443  6746  6800 I jxcore-log: 
,08-29 11:25:27.443  2001  6820 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-29 11:25:27.453  2001  6820 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 11:25:27.453  2001  6820 I System.out: (HTTPLog)-Static: isShipBuild true
08-29 11:25:27.453  2001  6820 I System.out: (HTTPLog)-Thread-267-156031230: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-29 11:25:27.453  2001  6820 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 11:25:27.453   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 11:25:27.453   278  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-29 11:25:27.453  2001  6820 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 11:25:27.453  2001  6820 I qtaguid : Tagging socket 61 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2001, getuid(): 10011
,08-29 11:25:27.503  2001  6820 I qtaguid : Tagging socket 64 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2001, getuid(): 10011
,08-29 11:25:27.673   283   694 I WVCdm   : CdmEngine::CloseSession
,08-29 11:25:27.683   283   694 I WVCdm   : L3 Terminate.
,08-29 11:25:27.723  2001  2171 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-29 11:25:27.733  2001  2171 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-29 11:25:27.743  2001  2171 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-29 11:25:26.349+0200, stopTime=2016-08-29 11:25:27.743+0200, duration=1394ms
,08-29 11:25:27.743  2001  6863 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 11:25:27.753   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 11:25:27.753   278  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-29 11:25:27.753  2001  6863 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 11:25:27.753  2001  6863 I qtaguid : Tagging socket 65 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2001, getuid(): 10011
,08-29 11:25:27.773  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-29 11:25:27.793  2001  6863 I qtaguid : Tagging socket 68 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2001, getuid(): 10011
,08-29 11:25:28.003  1016  3365 D SSRM:n  : SIOP:: AP = 380
,08-29 11:25:28.033  2001  6863 I qtaguid : Untagging socket 65
,08-29 11:25:28.063  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 11:25:28.063  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-29 11:25:28.063  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:28.063  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:28.063  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:28.093  2001  2171 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-29 11:25:28.153  1016  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:28.153  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:28.153  1016  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:28.153  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:28.173  1016  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:28.183  6746  6800 D executeNativeTests: Running unit tests
08-29 11:25:28.183  1016  1480 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:28.183  1016  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:28.183  1016  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:28.233  1016  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:28.233  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:28.233  1016  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:28.233  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:28.233  2001  6869 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-29 11:25:28.233  2001  6867 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-29 11:25:28.233  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:28.233  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:28.233  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:28.233  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:28.263  1016  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:28.263  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:28.263  1016  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:28.263  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:28.263  2001  6869 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-29 11:25:28.263  2001  6867 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-29 11:25:28.263  1016  1550 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:28.263  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:28.263  1016  1550 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:28.263  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:28.283  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:28.283  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 added. We now have 2 listener(s)
,08-29 11:25:28.283  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 11:25:28.283  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:25:28.283  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:28.283  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:28.283  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 added. We now have 2 listener(s)
08-29 11:25:28.283  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:25:28.283  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:25:28.293  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:28.293  1016  1497 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-29 11:25:28.293  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:28.293  1016  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:28.293  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 11:25:28.293  2001  6869 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-29 11:25:28.293  2001  6867 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-29 11:25:28.293  2001  6867 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
08-29 11:25:28.293  6746  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:28.293  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:28.293  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:28.293  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:28.293  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:28.293  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:28.293  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:25:28.293  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:25:28.293  6746  6800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:28.293  6746  6800 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:25:28.303  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:28.303  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 11:25:28.303  6746  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 11:25:28.303  6746  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 11:25:28.303  6746  6800 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 11:25:28.303  6746  6800 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 11:25:28.303  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 11:25:28.303  6746  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 11:25:28.303  6746  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 11:25:28.303  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.303  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.303  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:28.303  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:28.303  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.303  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.303  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:28.303  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:28.303  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 removed from the list
08-29 11:25:28.303  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.303  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 removed from the list
08-29 11:25:28.303  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.303  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.303  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.303  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.303  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:28.303  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:28.303  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.303  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.313  6746  6800 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 11:25:28.313  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.313  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.313  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:28.313  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.313  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.313  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.313  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.313  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.313  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.313  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.313  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.313  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.313  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.313  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.313  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:28.313  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:28.313  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.313  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
,08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 11:25:28.323  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.323  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.323  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:28.323  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.323  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.323  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.323  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.323  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.323  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.323  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.323  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.323  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.323  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.323  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.323  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:28.323  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:28.323  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.323  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.323  6746  6800 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 11:25:28.323  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:28.323  6746  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:28.323  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:28.323  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:28.323  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:28.323  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:28.323  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:28.323  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:25:28.323  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:25:28.333  2001  6867 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-29 11:25:28.333  6746  6800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:28.333  6746  6800 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:25:28.333  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:25:28.333  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:28.333  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:25:28.333  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:25:28.333  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:28.333  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 11:25:28.333  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:28.333  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 11:25:28.343  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 11:25:28.353  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 11:25:28.353  6746  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-29 11:25:28.353  6746  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 11:25:28.353  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 11:25:28.353  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 11:25:28.353  6746  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 11:25:28.373  3158  3167 D BtGatt.GattService: registerClient() - UUID=19e2cfcd-4820-4fde-a447-31c79baae214
,08-29 11:25:28.413  2001  6867 I art     : Explicit concurrent mark sweep GC freed 54741(2MB) AllocSpace objects, 18(596KB) LOS objects, 39% free, 11MB/19MB, paused 1.366ms total 76.315ms
,08-29 11:25:28.413  3158  3255 D BtGatt.GattService: onClientRegistered() - UUID=19e2cfcd-4820-4fde-a447-31c79baae214, clientIf=6
,08-29 11:25:28.423  6746  6791 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 11:25:28.423  3158  3358 D BtGatt.GattService: start scan with filters
,08-29 11:25:28.423  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 11:25:28.423  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 11:25:28.423  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 11:25:28.423  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 11:25:28.423  3158  3261 D BtGatt.ScanManager: handling starting scan
,08-29 11:25:28.423  3158  3261 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:28.433  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:25:28.433  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 11:25:28.433  6746  6746 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:25:28.433  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 11:25:28.433  3158  3255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-29 11:25:28.433  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:28.433  3158  3261 D BtGatt.ScanManager: allow scan with filters
08-29 11:25:28.433  3158  3261 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-29 11:25:28.433  3158  3261 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-29 11:25:28.443  6746  6800 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 11:25:28.443  3158  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 11:25:28.443  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:28.443  3158  3261 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 11:25:28.443  3158  3261 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 11:25:28.443  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.443  6746  6800 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 11:25:28.443  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.443  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 11:25:28.443  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.443  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 11:25:28.443  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 11:25:28.443  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:25:28.443  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:25:28.443  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 11:25:28.443  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 11:25:28.443  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 11:25:28.453  3158  3167 D BtGatt.GattService: stopScan() - queue size =1
,08-29 11:25:28.453  3158  3358 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 11:25:28.453  3158  3255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 11:25:28.453  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:28.453  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:28.453  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 11:25:28.453  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 11:25:28.453  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 11:25:28.453  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 11:25:28.453  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:25:28.453  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 11:25:28.453  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 11:25:28.453  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:25:28.453  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:28.453  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.453  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:25:28.463  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:28.463  6746  6746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:25:28.463  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.463  6746  6746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:25:28.463  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.463  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.463  6746  6746 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:25:28.463  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.463  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:28.463  3158  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-29 11:25:28.463  6746  6800 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 11:25:28.463  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:28.463  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:25:28.463  3158  3261 D BtGatt.ScanManager: filter size is 1
,08-29 11:25:28.463  3158  3261 D BtGatt.ScanManager: delete FilterIndex - 3
,08-29 11:25:28.473  6746  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:28.473  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:28.473  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:28.473  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:28.473  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:28.473  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:28.473  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:25:28.473  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:25:28.473  6746  6800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:25:28.473  6746  6800 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:25:28.473  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:25:28.473  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:25:28.473  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:25:28.473  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:28.473  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 11:25:28.473  3158  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 11:25:28.473  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:28.473  3158  3261 D BtGatt.ScanManager: stopping BLe Batch
,08-29 11:25:28.473  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:28.473  3158  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 11:25:28.473  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:28.483  3158  3261 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 11:25:28.483  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 11:25:28.483  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:28.483  1016  1553 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-29 11:25:28.483  3158  3255 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 11:25:28.483  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:28.483  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 11:25:28.493  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 11:25:28.493  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 11:25:28.493  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 11:25:28.493  6746  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 11:25:28.493  3158  3167 D BtGatt.GattService: registerClient() - UUID=d912ced9-6db8-42ef-a246-a5f99ebe3512
,08-29 11:25:28.523  2001  6867 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 11:25:28.523   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 11:25:28.523   278  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-29 11:25:28.523  2001  6867 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 11:25:28.523  2001  6867 I qtaguid : Tagging socket 77 with tag 11065fff00000000{285630463,0} for uid -1, pid: 2001, getuid(): 10011
,08-29 11:25:28.543  3158  3255 D BtGatt.GattService: onClientRegistered() - UUID=d912ced9-6db8-42ef-a246-a5f99ebe3512, clientIf=6
,08-29 11:25:28.543  6746  6754 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 11:25:28.543  3158  3166 D BtGatt.GattService: start scan with filters
,08-29 11:25:28.543  3158  3261 D BtGatt.ScanManager: handling starting scan
,08-29 11:25:28.543  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 11:25:28.543  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 11:25:28.543  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 11:25:28.543  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 11:25:28.543  3158  3255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 11:25:28.543  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:28.543  3158  3261 D BtGatt.ScanManager: allow scan with filters
,08-29 11:25:28.543  3158  3261 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 11:25:28.543  3158  3261 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-29 11:25:28.553  3158  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-29 11:25:28.553  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:28.553  3158  3261 D BtGatt.ScanManager: Starting BLE batch scan
08-29 11:25:28.553  3158  3261 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 11:25:28.553  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:25:28.553  6746  6746 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:25:28.553  3158  3255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-29 11:25:28.553  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:28.553  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 11:25:28.553  3158  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 11:25:28.553  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:28.563  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 11:25:28.563  6746  6800 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 11:25:28.563  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:25:28.563  6746  6800 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 11:25:28.563  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.563  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 11:25:28.563  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.563  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 11:25:28.563  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 11:25:28.563  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:25:28.563  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:25:28.563  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 11:25:28.563  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 11:25:28.573  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 11:25:28.573  3158  3358 D BtGatt.GattService: stopScan() - queue size =1
,08-29 11:25:28.573  3158  3261 D BtGatt.ScanManager: filter size is 1
08-29 11:25:28.573  3158  3261 D BtGatt.ScanManager: delete FilterIndex - 4
,08-29 11:25:28.573  2001  6867 I qtaguid : Tagging socket 80 with tag 11065fff00000000{285630463,0} for uid -1, pid: 2001, getuid(): 10011
08-29 11:25:28.573  3158  3167 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 11:25:28.573  3158  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 11:25:28.573  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:28.573  3158  3261 D BtGatt.ScanManager: stopping BLe Batch
,08-29 11:25:28.573  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:28.573  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 11:25:28.573  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 11:25:28.573  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 11:25:28.573  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 11:25:28.573  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:25:28.573  3158  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-29 11:25:28.573  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:28.573  3158  3261 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 11:25:28.573  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 11:25:28.573  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 11:25:28.573  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 11:25:28.583  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:25:28.583  3158  3255 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 11:25:28.583  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:28.583  6746  6746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:25:28.583  6746  6746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:25:28.583  6746  6746 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:25:28.583  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.583  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.583  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:28.583  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.583  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.583  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.583  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.583  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:28.583  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:25:28.583  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:28.583  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:25:28.583  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:28.583  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:25:28.583  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
,08-29 11:25:28.583  6746  6800 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 11:25:28.593  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:25:28.593  6746  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:28.593  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:28.593  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:28.593  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:28.593  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:28.593  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:28.593  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:25:28.593  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:25:28.593  6746  6800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:25:28.593  6746  6800 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:25:28.603  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:25:28.603  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:25:28.603  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:25:28.603  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:28.603  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 11:25:28.603  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:28.603  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:28.603  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 11:25:28.613  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 11:25:28.613  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 11:25:28.613  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 11:25:28.613  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 11:25:28.613  6746  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 11:25:28.613  3158  3166 D BtGatt.GattService: registerClient() - UUID=40d4f338-f102-4bd2-8ab1-618593adedbf
,08-29 11:25:28.653  3158  3255 D BtGatt.GattService: onClientRegistered() - UUID=40d4f338-f102-4bd2-8ab1-618593adedbf, clientIf=6
,08-29 11:25:28.653  6746  6791 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 11:25:28.663  3158  3357 D BtGatt.GattService: start scan with filters
,08-29 11:25:28.663  3158  3261 D BtGatt.ScanManager: handling starting scan
,08-29 11:25:28.663  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 11:25:28.663  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 11:25:28.663  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 11:25:28.663  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 11:25:28.663  3158  3255 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 11:25:28.663  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:28.663  3158  3261 D BtGatt.ScanManager: allow scan with filters
08-29 11:25:28.663  3158  3261 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 11:25:28.663  3158  3261 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-29 11:25:28.673  3158  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-29 11:25:28.673  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:28.673  3158  3261 D BtGatt.ScanManager: Starting BLE batch scan
08-29 11:25:28.673  3158  3261 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-29 11:25:28.673  3158  3255 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-29 11:25:28.673  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:28.673  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:25:28.673  3158  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 11:25:28.673  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:28.683  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 11:25:28.683  6746  6746 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:25:28.683  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 11:25:28.683  6746  6800 I io.jxcore.node.ConnectionHelper: start: OK
08-29 11:25:28.683  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.683  6746  6800 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 11:25:28.683  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.683  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 11:25:28.683  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.683  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 11:25:28.683  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 11:25:28.683  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:25:28.683  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:25:28.683  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 11:25:28.683  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 11:25:28.683  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 11:25:28.693  3158  3166 D BtGatt.GattService: stopScan() - queue size =1
08-29 11:25:28.693  3158  3261 D BtGatt.ScanManager: filter size is 1
08-29 11:25:28.693  3158  3261 D BtGatt.ScanManager: delete FilterIndex - 5
,08-29 11:25:28.693  3158  3255 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-29 11:25:28.693  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:28.693  3158  3357 D BtGatt.GattService: unregisterClient() - clientIf=6
08-29 11:25:28.693  3158  3261 D BtGatt.ScanManager: stopping BLe Batch,
,08-29 11:25:28.693  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:28.693  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 11:25:28.693  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 11:25:28.693  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 11:25:28.693  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 11:25:28.693  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:25:28.693  3158  3255 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 11:25:28.693  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:28.693  3158  3261 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 11:25:28.693  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 11:25:28.693  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 11:25:28.693  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:25:28.693  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:25:28.703  3158  3255 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-29 11:25:28.703  6746  6746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:25:28.703  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.703  6746  6800 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 11:25:28.703  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.703  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:28.703  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.703  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.703  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:28.703  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.703  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.703  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.703  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.703  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:28.703  3158  3255 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:28.703  6746  6746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:25:28.703  6746  6746 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:25:28.703  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.703  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:28.703  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:28.703  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:28.703  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.703  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
,08-29 11:25:28.703  6746  6800 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-29 11:25:28.703  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.703  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.703  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:28.703  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.703  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.703  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.703  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.703  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.703  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.703  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.703  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.703  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.703  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.703  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:28.703  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:28.703  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:25:28.703  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.703  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
,08-29 11:25:28.703  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 11:25:28.703  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.703  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.703  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:25:28.703  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.703  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.703  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.703  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
,08-29 11:25:28.703  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.703  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list,
08-29 11:25:28.703  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:25:28.703  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 11:25:28.703  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.703  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.703  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.703  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:28.703  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:28.703  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.703  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.713  6746  6800 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 11:25:28.713  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.713  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.713  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:28.713  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.713  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.713  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.713  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.713  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.713  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.713  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.713  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.713  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.713  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.713  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.713  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:28.713  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 11:25:28.713  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.713  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.713  6746  6800 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 11:25:28.713  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.713  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.713  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:25:28.713  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.713  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:25:28.713  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:28.713  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.713  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:25:28.713  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.713  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.713  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.713  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:28.713  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.713  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.713  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:28.713  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:28.713  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.713  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.713  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 11:25:28.713  6746  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 11:25:28.713  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 11:25:28.713  6746  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 11:25:28.713  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 11:25:28.713  6746  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 11:25:28.713  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.713  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.713  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:28.713  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.713  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.713  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.713  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.713  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.713  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.713  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.713  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.713  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.713  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.713  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.713  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:28.713  6746  6800 I org.thal,iproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:28.713  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.713  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.723  6746  6800 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:25:28.723  6746  6800 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 11:25:28.723  6746  6800 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:25:28.723  6746  6800 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410],
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 11:25:28.723  6746  6800 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 11:25:28.723  6746  6800 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered p,eers, but trying anyway...
08-29 11:25:28.723  6746  6800 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 11:25:28.723  6746  6800 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:25:28.723  6746  6800 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 11:25:28.723  6746  6800 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 11:25:28.723  6746  6800 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:25:28.723  6746  6800 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 11:25:28.723  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 11:25:28.723  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 11:25:28.723  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 11:25:28.723  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 11:25:28.723  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 11:25:28.723  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 11:25:28.723  6746  6800 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 11:25:28.723  6746  6800 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 11:25:28.723  6746  6800 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 11:25:28.723  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.723  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.723  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:28.723  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.723  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.723  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.723  6746  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1320)
08-29 11:25:28.723  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 11:25:28.723  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
,08-29 11:25:28.723  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.723  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.723  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.723  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.723  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-29 11:25:28.723  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.723  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.733  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.733  6746  6875 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1320
08-29 11:25:28.733  6746  6800 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 11:25:28.733  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.733  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.733  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.733  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.733  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.733  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.733  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.733  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.733  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.733  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.733  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.733  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.733  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
,08-29 11:25:28.733  6746  6800 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 11:25:28.733  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.733  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.733  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.733  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.733  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.733  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.733  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.733  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.733  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.733  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.733  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.733  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.733  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
,08-29 11:25:28.733  6746  6800 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 11:25:28.733  6746  6800 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 11:25:28.733  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 11:25:28.733  6746  6800 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 11:25:28.733  6746  6800 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 11:25:28.733  6746  6800 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 11:25:28.733  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 11:25:28.733  6746  6800 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 11:25:28.733  6746  6874 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-29 11:25:28.733  6746  6800 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 11:25:28.733  6746  6800 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 11:25:28.733  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 11:25:28.733  6746  6800 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 11:25:28.733  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.733  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.733  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.733  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.733  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.733  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.733  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.733  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.733  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.733  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.733  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:,28.733  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.733  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
,08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.733  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.733  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.733  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.733  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.733  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.733  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.733  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:25:28.733  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.733  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.733  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.733  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.733  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.733  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.733  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.733  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:25:28.733  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.733  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.733  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.733  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.733  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.733  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.733  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.733  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.733  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.743  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:25:28.743  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:28.743  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.743  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.743  6746  6800 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-29 11:25:28.743  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:25:28.743  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 11:25:28.743  6746  6800 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 11:25:28.743  6746  6800 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-29 11:25:28.743  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 11:25:28.743  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 11:25:28.743  6746  6746 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 11:25:28.743  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.743  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 11:25:28.743  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 11:25:28.743  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 11:25:28.743  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.743  6746  6800 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 11:25:28.743  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.743  6746  6746 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 11:25:28.743  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.743  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:25:28.743  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:25:28.743  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 11:25:28.743  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.743  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.743  6746  6874 D BluetoothSocket: connect(): myUserId = 0
08-29 11:25:28.743  6746  6874 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:25:28.743  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:25:28.743  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.743  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.743  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.743  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:28.743  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.743  6746  6746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:25:28.743  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.743  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.743  6746  6746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:25:28.743  6746  6800 E org.t,haliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.743  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.743  6746  6746 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:25:28.743  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.743  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.743  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.743  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.743  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.743  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:28.743  6746  6876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 11:25:28.743  6746  6876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 11:25:28.743  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:28.743  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:28.743  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.743  6746  6746 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 11:25:28.743  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.743  3158  3167 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:25:28.753  6746  6800 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 11:25:28.753  6746  6800 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 11:25:28.753  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 11:25:28.753  6746  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 11:25:28.753  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.753  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.753  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:28.753  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.753  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.753  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.753  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.753  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.753  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.753  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.753  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.753  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.753  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.753  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:28.753  6746  6874 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-29 11:25:28.753  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:28.753  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:28.753  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.753  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
,08-29 11:25:28.753  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.753  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.753  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:25:28.753  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.753  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.753  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.753  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.753  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.753  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.753  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.753  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.753  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.753  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.753  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:28.753  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:28.753  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:28.753  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.753  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
,08-29 11:25:28.753  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:28.753  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:28.753  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:28.753  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:28.753  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.753  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.753  6746  6800 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc07f2 not in the list
08-29 11:25:28.753  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.753  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
08-29 11:25:28.753  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:28.753  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.753  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:28.753  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:28.753  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:28.763  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:28.763  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:28.763  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:28.763  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e74e43 not in the list
,08-29 11:25:28.763  6746  6800 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing,
08-29 11:25:28.763  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 11:25:28.763  6746  6800 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 11:25:28.763  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 11:25:28.763  6746  6800 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 11:25:28.763  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-29 11:25:28.763  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
08-29 11:25:28.763  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-29 11:25:28.763  6746  6800 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 11:25:28.763  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 11:25:28.763  6746  6800 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 11:25:28.763  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 11:25:28.763  6746  6800 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-29 11:25:28.763  6746  6800 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 11:25:28.763  6746  6800 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 11:25:28.763  6746  6800 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-29 11:25:28.763  6746  6800 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 11:25:28.763  6746  6800 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 11:25:28.763  6746  6800 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 11:25:28.763  6746  6800 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-29 11:25:28.763  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-29 11:25:28.763  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b23916d added. We now have 2 listener(s)
08-29 11:25:28.763  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:25:28.763  6746  6800 D BluetoothAdapter: enable()
,08-29 11:25:28.773  6746  6800 D BluetoothAdapter: enable(): BT is already enabled..!
,08-29 11:25:28.773  1016  1224 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-29 11:25:28.773  1016  1224 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 11:25:28.773  1016  1224 D SecContentProvider2: mCursor = null
,08-29 11:25:28.773  1016  1224 D WifiService: setWifiEnabled: true pid=6746, uid=10171
,08-29 11:25:28.773   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 11:25:28.783  1016  1224 W ActivityManager: Permission Denial: getCurrentUser() from pid=6746, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,08-29 11:25:28.783  1016  1224 W WifiService: Failed getting userId using ActivityManagerNative,
08-29 11:25:28.783  1016  1224 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6746, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 11:25:28.783  1016  1224 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 11:25:28.783  1016  1224 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 11:25:28.783  1016  1224 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 11:25:28.783  1016  1224 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
,08-29 11:25:28.783  1016  1224 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-29 11:25:28.783  1016  1224 D SettingsProvider: name = wifi_on
08-29 11:25:28.783  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:28.783  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2bc251a2 added. We now have 3 listener(s)
08-29 11:25:28.783  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:25:28.793  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:25:28.793  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1be84e33 added. We now have 4 listener(s)
08-29 11:25:28.793  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:25:28.793  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:25:28.793  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@182f05f0 added. We now have 5 listener(s)
08-29 11:25:28.793  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:25:28.793  1016  1029 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 11:25:28.793  1016  1029 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 11:25:28.793  1016  1029 D SecContentProvider2: mCursor = null
,08-29 11:25:28.793  1016  1029 D WifiService: setWifiEnabled: false pid=6746, uid=10171
,08-29 11:25:28.793  1016  1029 D SettingsProvider: name = wifi_on
,08-29 11:25:28.803  1016  1124 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 11:25:28.803  1387  1387 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 11:25:28.803  1387  1387 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-29 11:25:28.803  1387  1387 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 11:25:28.813  1387  1387 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-29 11:25:28.813  6746  6800 D BluetoothAdapter: disable()
,08-29 11:25:28.813  1016  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-29 11:25:28.813  1016  1479 D SettingsProvider: name = bluetooth_on
,08-29 11:25:28.823  3158  3252 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-29 11:25:28.823  3158  3252 D BluetoothAdapterProperties: Setting state to 13
08-29 11:25:28.823  3158  3252 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 11:25:28.823  3158  3252 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-29 11:25:28.823  3158  3252 D BluetoothAdapterService: updateAdapterState state is 13
08-29 11:25:28.823  1016  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:28.823  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:28.823  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-29 11:25:28.823  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:28.823  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 11:25:28.823  3158  3158 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-29 11:25:28.833  3158  3252 D BluetoothAdapterService: Autoconnection is available 
08-29 11:25:28.833  3158  3252 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-29 11:25:28.833  3158  3252 D BluetoothAdapterService: terminating service from this receiver
08-29 11:25:28.833  3158  3158 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@28bb68d9, channel: 19, state: LISTENING
08-29 11:25:28.833  3158  3158 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@28bb68d9, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22986a1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2293f29emSocket: android.net.LocalSocket@111ea17f impl:android.net.LocalSocketImpl@679a54c fd:FileDescriptor[74]
08-29 11:25:28.833  3158  3158 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@111ea17f impl:android.net.LocalSocketImpl@679a54c fd:FileDescriptor[74],
,08-29 11:25:28.833  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-29 11:25:28.833  1016  1124 E WifiNative-wlan0: do suspend true
,08-29 11:25:28.833  1016  1224 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 11:25:28.833  1016  1224 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:28.833  1016  1224 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:28.833  1016  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:28.833  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:28.833  6746  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:28.833  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:28.833  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:28.833  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:28.833  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:28.833  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:28.833  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:25:28.833  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:25:28.833  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:28.833  6746  6800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:28.833  6746  6800 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:25:28.843  3158  3252 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 11:25:28.843  3158  3252 D BluetoothAdapterProperties: mDiscovering is false
08-29 11:25:28.843  1016  1329 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-29 11:25:28.843  3158  3252 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-29 11:25:28.843  3306  3306 D BluetoothPbap: Proxy object disconnected
08-29 11:25:28.843  3306  3306 D PbapServerProfile: Bluetooth service disconnected
,08-29 11:25:28.843  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:28.843  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
,08-29 11:25:28.843  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:28.843  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:28.853  1872  1872 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 11:25:28.853  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-29 11:25:28.863  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 11:25:28.863  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:28.863  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-29 11:25:28.863  1177  1765 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 11:25:28.863  3306  3306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:28.863  1177  1765 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 11:25:28.863  1177  1765 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 11:25:28.863  1016  1497 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 11:25:28.863  1016  1224 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 11:25:28.863  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:25:28.863  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:28.863  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:28.863  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:28.863  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:28.863  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:28.863  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:28.863  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:25:28.863  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:25:28.863  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 11:25:28.873  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:25:28.873  6746  6746 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:28.873  1016  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 11:25:28.873  1016  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 11:25:28.873  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-29 11:25:28.873  1016  1472 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:28.873  1016  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 11:25:28.873  1016  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 11:25:28.873  3158  3255 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-29 11:25:28.873  3158  3255 D BluetoothAdapterProperties: Scan Mode:20
,08-29 11:25:28.883  3158  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-29 11:25:28.883  3158  3252 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-29 11:25:28.883  3158  3252 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-29 11:25:28.883  3158  3252 E bt-btif : cmd socket is not created
,08-29 11:25:28.883  3158  5204 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 11:25:28.883  3158  3276 E bt-btm  : btm_ble_start_auto_conn start : 0, 0,
08-29 11:25:28.883  3158  3276 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 11:25:28.883  3158  3276 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:25:28.883  3158  3276 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:25:28.883  3158  3276 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration,
08-29 11:25:28.883  3158  3252 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 11:25:28.883  6746  6874 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2a97e5ee, channel: -1, state: INIT
08-29 11:25:28.883  6746  6874 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2a97e5ee, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ecf9a8f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@916911cmSocket: android.net.LocalSocket@167a8125 impl:android.net.LocalSocketImpl@2d2072fa fd:FileDescriptor[106]
08-29 11:25:28.883  6746  6874 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@167a8125 impl:android.net.LocalSocketImpl@2d2072fa fd:FileDescriptor[106]
08-29 11:25:28.883  6746  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1320)
,08-29 11:25:28.893  3306  3306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 11:25:28.893  1016  1134 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-29 11:25:28.893  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 11:25:28.893  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:28.893  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:28.893  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:28.893  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 11:25:28.893  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:28.903  3158  3158 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b489aaa, channel: 5, state: LISTENING
,08-29 11:25:28.903  3158  3158 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1b489aaa, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@143990c6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@685d69bmSocket: android.net.LocalSocket@2541ca38 impl:android.net.LocalSocketImpl@7f05a11 fd:FileDescriptor[76]
08-29 11:25:28.903  3158  3158 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2541ca38 impl:android.net.LocalSocketImpl@7f05a11 fd:FileDescriptor[76]
08-29 11:25:28.903  3158  3158 I BtOppRfcommListener: stopping Accept Thread
08-29 11:25:28.903  3158  3158 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@16edb776, channel: 12, state: LISTENING
08-29 11:25:28.903  3158  3158 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@16edb776, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a783720, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@c614177mSocket: android.net.LocalSocket@6551e4 impl:android.net.LocalSocketImpl@46f864d fd:FileDescriptor[80]
08-29 11:25:28.903  3158  3158 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@6551e4 impl:android.net.LocalSocketImpl@46f864d fd:FileDescriptor[80]
,08-29 11:25:28.903  3158  5204 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 11:25:28.903  3306  3306 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:25:28.903  3158  3158 V BluetoothOppManager: cleanUp...
,08-29 11:25:28.903  3306  3306 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 11:25:28.913  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:28.913  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-29 11:25:28.913  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-29 11:25:28.913  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:28.913  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:28.913  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:28.913  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:28.933  6882  6882 E Zygote  : MountEmulatedStorage()
,08-29 11:25:28.933  6882  6882 E Zygote  : v2
08-29 11:25:28.933  6882  6882 I libpersona: KNOX_SDCARD checking this for 10055
08-29 11:25:28.933  6882  6882 I libpersona: KNOX_SDCARD not a persona
,08-29 11:25:28.933  6882  6882 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:28.933  1016  1028 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6882 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-29 11:25:28.933  6882  6882 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 11:25:28.933  6882  6882 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 11:25:28.963  6882  6882 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:28.963  6882  6882 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:28.983  6882  6882 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-29 11:25:29.023  6882  6882 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-29 11:25:29.023  6882  6882 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-29 11:25:29.023  6882  6882 D UserAnalysis: Create SecureDbHelper
,08-29 11:25:29.033  6882  6882 D IntelligenceServiceApplication: onCreate()
,08-29 11:25:29.033  1016  1480 I ActivityManager: Killing 6447:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-29 11:25:29.033  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-29 11:25:29.043  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:29.043  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:29.043  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:29.043  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:29.043  6882  6882 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-29 11:25:29.053  6900  6900 E Zygote  : MountEmulatedStorage()
,08-29 11:25:29.053  6900  6900 E Zygote  : v2
08-29 11:25:29.053  6900  6900 I libpersona: KNOX_SDCARD checking this for 10105
08-29 11:25:29.053  6900  6900 I libpersona: KNOX_SDCARD not a persona
,08-29 11:25:29.053  6900  6900 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:29.053  6900  6900 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 11:25:29.053  6900  6900 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
08-29 11:25:29.053  1016  1028 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6900 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-29 11:25:29.063  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0,
,08-29 11:25:29.063  6882  6882 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-29 11:25:29.063  6882  6882 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-29 11:25:29.073  6900  6900 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:29.073  6900  6900 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:29.083  3158  3276 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 11:25:29.083  3158  3276 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:25:29.083  3158  3276 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:25:29.083  3158  3276 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:25:29.083  3158  3276 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 11:25:29.083  3158  3276 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:25:29.083  3158  3276 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:25:29.083  3158  3276 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:25:29.083  3158  3276 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:25:29.083  3158  3276 W bt-btif : ag scb idx 1 not allocated
,08-29 11:25:29.083  3158  3276 W bt-btif : ag scb idx 2 not allocated
08-29 11:25:29.083  3158  3276 E bt-btif : BTA AG is already disabled, ignoring ...
,08-29 11:25:29.083  3158  3328 I bt_userial_mct: exiting userial_read_thread
08-29 11:25:29.083  3158  3328 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 11:25:29.083  3158  3255 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 11:25:29.083  3158  3279 I bt_vendor: hw_epilog_process
,08-29 11:25:29.093  3158  3255 D bt_userial_mct: userial_close
08-29 11:25:29.093  3158  3255 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-29 11:25:29.183   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 11:25:29.183   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 11:25:29.183  6900  6921 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 11:25:29.183   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 11:25:29.183   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 11:25:29.183  6900  6921 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 11:25:29.243  6746  6746 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 11:25:29.303  3158  3255 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-29 11:25:29.303  3158  3255 I bt_vendor: bluetooth satus is on
08-29 11:25:29.303  3158  3255 I bt_vendor: bt-vendor : resetting BT status
08-29 11:25:29.303  3158  3255 I bt_vendor: Starting hciattach daemon
08-29 11:25:29.303  3158  3255 I bt_vendor: try to set false
,08-29 11:25:29.303  3158  3255 I bt_vendor: Starting hciattach daemon
,08-29 11:25:29.303  3158  3255 I bt_vendor: try to set false
,08-29 11:25:29.303  3158  3255 I bt_vendor: cleanup
,08-29 11:25:29.303  3158  3276 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 11:25:29.303  3158  3255 I GKI_LINUX: GKI_exit_task 0 done
08-29 11:25:29.303  3158  3255 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-29 11:25:29.303  3158  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 11:25:29.303  3158  3252 D BtConfig.SecureMode: isSecureModeOn:false
08-29 11:25:29.303  3158  3252 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-29 11:25:29.303  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-29 11:25:29.303  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-29 11:25:29.303  3158  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-29 11:25:29.303  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:29.313  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-29 11:25:29.313  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:29.313  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:29.313  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:29.313  3158  3158 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 11:25:29.313  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 11:25:29.313  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 11:25:29.313  3158  3158 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 11:25:29.313  3158  3158 D BtGatt.GattService: stop()
08-29 11:25:29.313  3158  3158 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 11:25:29.313  3158  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-29 11:25:29.313  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
08-29 11:25:29.313  1016  1551 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:29.313  1016  1551 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 11:25:29.313  1016  1551 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:29.313  1016  1551 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:29.313  1016  1551 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:29.313  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 11:25:29.313  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 11:25:29.323  3158  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 11:25:29.323  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:29.323  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 11:25:29.323  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:29.323  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:29.323  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:29.323  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-29 11:25:29.323  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 11:25:29.323  3158  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-29 11:25:29.323  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:29.323  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:29.323  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-29 11:25:29.323  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:29.323  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 11:25:29.323  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-29 11:25:29.323  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 11:25:29.323  3158  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 11:25:29.323  1016  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:29.323  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-29 11:25:29.333  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:29.333  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:29.333  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:29.333  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-29 11:25:29.333  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-29 11:25:29.333  3158  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 11:25:29.333  1016  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:29.333  1016  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 11:25:29.333  1016  1471 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:29.333  1016  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:29.333  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:29.333  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 11:25:29.333  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 11:25:29.333  3158  3252 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-29 11:25:29.333  1016  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:29.333  1016  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 11:25:29.333  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:29.333  1016  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:29.333  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:29.343  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-29 11:25:29.343  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 11:25:29.343  3158  3252 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 11:25:29.343  1016  1224 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:29.343  1016  1224 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 11:25:29.343  1016  1224 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:29.343  1016  1224 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:29.343  1016  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:29.343  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 11:25:29.343  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 11:25:29.343  3158  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-29 11:25:29.343  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 11:25:29.343  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-29 11:25:29.343  3158  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-29 11:25:29.343  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 11:25:29.343  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-29 11:25:29.343  3158  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 11:25:29.343  3158  3252 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-29 11:25:29.353  3158  3252 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-29 11:25:29.353  3158  3252 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 11:25:29.353  3158  3252 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 11:25:29.353  3158  3158 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-29 11:25:29.353  3158  3158 D HeadsetService: Received stop request...Stopping profile...
,08-29 11:25:29.353  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:29.353  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-29 11:25:29.353  3158  3158 D A2dpService: Received stop request...Stopping profile...
08-29 11:25:29.353  3158  3268 D A2dpStateMachine: Exit Disconnected: -1
,08-29 11:25:29.353  3306  3306 D HeadsetProfile: Bluetooth service disconnected
,08-29 11:25:29.363  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:29.363  1016  1016 D BluetoothA2dp: Proxy object disconnected
,08-29 11:25:29.363  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-29 11:25:29.363  3158  3158 D HidService: Received stop request...Stopping profile...
08-29 11:25:29.363  3158  3158 D HidService: Stopping Bluetooth HidService
08-29 11:25:29.363  3158  3158 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-29 11:25:29.363  3158  3158 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-29 11:25:29.363  3306  3306 D BluetoothA2dp: Proxy object disconnected
08-29 11:25:29.363  3158  3158 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 11:25:29.363  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:29.363  3306  3306 D A2dpProfile: Bluetooth service disconnected
,08-29 11:25:29.363  3158  3158 D HealthService: Received stop request...Stopping profile...
,08-29 11:25:29.363  3306  3306 D BluetoothInputDevice: Proxy object disconnected
08-29 11:25:29.363  3306  3306 D HidProfile: Bluetooth service disconnected
,08-29 11:25:29.363  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:29.373  3158  3158 D PanService: Received stop request...Stopping profile...
,08-29 11:25:29.373  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:29.373  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected,
08-29 11:25:29.373  3306  3306 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 11:25:29.373  3306  3306 D PanProfile: Bluetooth service disconnected
,08-29 11:25:29.373  3158  3158 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 11:25:29.373  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:29.383  3306  3306 D BluetoothMap: Proxy object disconnected
08-29 11:25:29.383  3306  3306 D MapProfile: Bluetooth service disconnected
,08-29 11:25:29.383  3158  3158 D SapService: Received stop request...Stopping profile...
08-29 11:25:29.383  3158  3158 D SapService: Stopping Bluetooth SapService
08-29 11:25:29.383  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:29.383  3158  3158 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-29 11:25:29.383  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 11:25:29.383  3158  3158 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-29 11:25:29.383  3306  3306 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-29 11:25:29.383  3306  3306 D SapProfile: Bluetooth service disconnected
,08-29 11:25:29.383  3158  3158 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 11:25:29.383  3158  3158 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 11:25:29.383  3158  3158 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-29 11:25:29.383  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 11:25:29.383  3158  3158 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-29 11:25:29.383  3158  3158 D BluetoothA2dp: Proxy object disconnected
08-29 11:25:29.383  6900  6900 D StrictMode: StrictMode policy violation; ~duration=193 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 11:25:29.383  3158  3158 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-29 11:25:29.383  6900  6900 D StrictMode: StrictMode policy violation; ~duration=193 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1,332)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 11:25:29.383  6900  6900 D StrictMode: StrictMode policy violation; ~duration=192 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThrea,d.java:5256)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 11:25:29.383  6900  6900 D StrictMode: StrictMode policy violation; ~duration=191 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 11:25:29.383  3158  3158 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-29 11:25:29.393  1016  1551 I ActivityManager: Killing 6345:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
08-29 11:25:29.383  6900  6900 D StrictMode: StrictMode policy violation; ~duration=188 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.q.k.d(PG:583)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 11:25:29.383  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 11:25:29.383  3158  3158 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 11:25:29.383  6900  6900 D StrictMode: StrictMode policy violation; ~duration=168 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 11:25:29.383  6900  6900 D StrictMode: StrictMode policy violation; ~duration=167 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 11:25:29.383  6900  6900 D StrictMode: StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 11:25:29.383  6900  6900 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 11:25:29.393  3158  3270 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 11:25:29.393  3158  3158 I GKI_LINUX: GKI_exit_task 2 done
08-29 11:25:29.393  3158  3158 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 11:25:29.393  3158  3158 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-29 11:25:29.393  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 11:25:29.393  3158  3158 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 11:25:29.393  3158  3158 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 11:25:29.393  3158  3158 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 11:25:29.393  3158  3158 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-29 11:25:29.393  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 11:25:29.393  3158  3158 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 11:25:29.393  3158  3158 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 11:25:29.393  3158  3158 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 11:25:29.393  3158  3158 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-29 11:25:29.393  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 11:25:29.393  3158  3158 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-29 11:25:29.393  3158  3158 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-29 11:25:29.393  3158  3158 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-29 11:25:29.393  3158  3158 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-29 11:25:29.393  3158  3252 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-29 11:25:29.393  3158  3252 D BluetoothAdapterProperties: Setting state to 10
08-29 11:25:29.393  3158  3252 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 11:25:29.393  3158  3252 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 11:25:29.393  3158  3252 D BluetoothAdapterService: updateAdapterState state is 10
08-29 11:25:29.393  3158  3252 D BluetoothAdapterService: Autoconnection is available 
08-29 11:25:29.393  3158  3252 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-29 11:25:29.393  3158  3252 I BluetoothAdapterState: Entering OffState
08-29 11:25:29.393  3158  3358 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 11:25:29.393  3306  3322 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 11:25:29.393  2001  2001 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-29 11:25:29.403  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 11:25:29.403  1177  1900 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 11:25:29.403  1177  1900 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 11:25:29.403  2001  2001 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-29 11:25:29.403  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 11:25:29.403  1016  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 11:25:29.403  3158  3166 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 11:25:29.403  3158  3166 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 11:25:29.413  3306  3319 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 11:25:29.413  2001  3079 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 11:25:29.413  2001  3079 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 11:25:29.413  3306  3322 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 11:25:29.413  3306  3322 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 11:25:29.413  3306  3322 D BluetoothMap: onBluetoothStateChange: up=false
08-29 11:25:29.413  3306  3322 D Bluetoothsap: onBluetoothStateChange: up=false
08-29 11:25:29.413  3306  3322 D Bluetoothsap: Unbinding service...
08-29 11:25:29.413  6746  6791 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 11:25:29.413  6746  6791 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 11:25:29.413  6746  6791 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-29 11:25:29.413  6746  6791 D BluetoothLeAdvertiser: Exit stop advertising
08-29 11:25:29.413  6746  6791 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-29 11:25:29.413  6746  6791 D BluetoothLeScanner: Exiting stopAllScan
08-29 11:25:29.413  3306  3319 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 11:25:29.413  1432  1440 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 11:25:29.413  1432  1440 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 11:25:29.413  1456  1473 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 11:25:29.413  1456  1473 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 11:25:29.413  1441  1462 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 11:25:29.413  1441  1462 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 11:25:29.423  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 11:25:29.423  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-29 11:25:29.423  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:29.433  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
08-29 11:25:29.433  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-29 11:25:29.433  1177  1177 D BluetoothAdapter: 1060206718: getState() :  mService = null. Returning STATE_OFF
08-29 11:25:29.433  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 11:25:29.433  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:29.433  1177  1765 D BluetoothAdapter: 1060206718: getState() :  mService = null. Returning STATE_OFF
08-29 11:25:29.433  1177  1177 D BluetoothTile:  getBluetoothState : 10
08-29 11:25:29.433  1177  1765 D BluetoothAdapter: 1060206718: getState() :  mService = null. Returning STATE_OFF
08-29 11:25:29.433  1872  1872 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-29 11:25:29.443  1016  1029 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 11:25:29.433  1177  1177 D BluetoothAdapter: 1060206718: getState() :  mService = null. Returning STATE_OFF
08-29 11:25:29.433  1177  1177 D BluetoothAdapter: 1060206718: getState() :  mService = null. Returning STATE_OFF
08-29 11:25:29.443  2001  2161 D BluetoothAdapter: 991978917: getState() :  mService = null. Returning STATE_OFF
08-29 11:25:29.443  2001  2161 D BluetoothAdapter: 991978917: getState() :  mService = null. Returning STATE_OFF
08-29 11:25:29.443  1016  1497 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-29 11:25:29.443  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 11:25:29.443  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-29 11:25:29.443  3306  3306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:29.443  1016  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 11:25:29.443  1016  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-29 11:25:29.453  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:29.453  1016  1480 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:29.453  1016  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:29.453  1016  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 11:25:29.453  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:29.453  3306  3306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 11:25:29.453  3158  3255 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-29 11:25:29.453  3158  3158 I GKI_LINUX: GKI_exit_task 1 done
08-29 11:25:29.453  3158  3158 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 11:25:29.463  3158  3158 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 11:25:29.463  1016  1550 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-29 11:25:29.463  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 11:25:29.463  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:29.463  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:29.463  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 11:25:29.463  3158  3158 I art     : System.exit called, status: 0
08-29 11:25:29.463  3158  3158 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 11:25:29.473  6900  6931 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 11:25:29.473  3306  3306 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:25:29.473  3306  3306 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 11:25:29.483  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:29.483  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-29 11:25:29.493  1016  1471 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:29.493  1016  1471 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:29.493  1016  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:29.493  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-29 11:25:29.573  1387  1387 I wpa_supplicant: nl80211: Received scan results (9 BSSes),
,08-29 11:25:29.573  1016  1123 D WifiP2pService: InactiveState{ what=147461 }
,08-29 11:25:29.573  1016  1123 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-29 11:25:29.573  1016  1497 I ActivityManager: Process com.android.bluetooth (pid 3158)(adj 0) has died(34,701)
,08-29 11:25:29.583  1016  1123 D WifiP2pService: DefaultState{ what=147461 }
,08-29 11:25:29.583  1016  1123 D WifiP2pService: InactiveState{ what=143375 },
08-29 11:25:29.583  1016  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 11:25:29.583  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 11:25:29.583  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-29 11:25:29.583  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:29.583  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:29.583  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:29.583  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:29.593   278  1015 D CommandListener: Clearing all IP addresses on wlan0
08-29 11:25:29.593  1016  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:25:29.593  2001  3075 V NativeCrypto: Read error: ssl=0xb8b81dd0: I/O error during system call, Connection timed out
08-29 11:25:29.593  1016  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-29 11:25:29.593  2001  3075 V NativeCrypto: SSL shutdown failed: ssl=0xb8b81dd0: I/O error during system call, Broken pipe
08-29 11:25:29.593  1016  1126 E ConnectivityService: updateNetworkInfo()
08-29 11:25:29.593  1016  1126 E ConnectivityService: updateNetworkInfo()
08-29 11:25:29.603  2001  3075 E GCM     : Wifi connection closed with errorCode 20
,08-29 11:25:29.603  1016  1123 D WifiP2pService: InactiveState{ what=131204 }
08-29 11:25:29.603  1016  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
08-29 11:25:29.603  1016  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-29 11:25:29.603  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 11:25:29.603  2001  2001 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 11:25:29.613  1016  1497 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-29 11:25:29.613  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 11:25:29.613  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1
,08-29 11:25:29.613  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 11:25:29.613  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:29.613  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:29.613  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:29.613  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:29.613  1016  1148 D WifiScanningService: DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 11:25:29.623  1016  1016 D RttService: SCAN_AVAILABLE : 1
08-29 11:25:29.623  1016  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 11:25:29.623  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 11:25:29.623  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-29 11:25:29.623  1016  1329 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 11:25:29.623  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-29 11:25:29.623  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:29.623  1016  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:29.623  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:29.633  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-29 11:25:29.633  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 11:25:29.643  1016  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-24ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 11:25:29.643  1016  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-25ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:29.643  1016  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-29 11:25:29.643  1016  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:29.643  1016  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-29 11:25:29.643  1016  1741 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 11:25:29.643  2001  6942 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-29 11:25:29.643  2001  2001 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 11:25:29.643  1016  1741 I qtaguid : Tagging socket 347 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1016, getuid(): 1000
,08-29 11:25:29.653  1016  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 11:25:29.653  1016  1329 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-29 11:25:29.653  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:29.653  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 11:25:29.663  1016  1741 I qtaguid : Untagging socket 347,
08-29 11:25:29.663  1016  1741 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 11:25:29.663  1016  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:29.663  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
08-29 11:25:29.663  1016  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-29 11:25:29.663  1598  1598 I Hs20UtilService: Starting #8
,08-29 11:25:29.663  1016  1480 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:29.663  1016  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:29.663  1016  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 11:25:29.663  1598  1647 I Hs20UtilService: Message received 5007
,08-29 11:25:29.673  3306  3306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 11:25:29.683  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-29 11:25:29.683  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-29 11:25:29.683  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 11:25:29.683  1016  1046 D WifiDisplayController: disconnect
08-29 11:25:29.683  1016  1046 D WifiDisplayController: updateConnection
08-29 11:25:29.683  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 11:25:29.683  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 11:25:29.683  1016  1471 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:29.683  1016  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-29 11:25:29.683  3306  3306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 11:25:29.693   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 11:25:29.693   278  1011 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-29 11:25:29.693  1016  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:29.693  1016  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:29.693  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:29.693  1016  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-29 11:25:29.693  1016  1126 V NetworkStats: updateIfacesLocked()
08-29 11:25:29.693  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:29.693  1016  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-29 11:25:29.693  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 11:25:29.693  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 11:25:29.693  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-29 11:25:29.693  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 11:25:29.693  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-29 11:25:29.693  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 11:25:29.693  3306  3306 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 11:25:29.693  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-29 11:25:29.693  1016  1123 D WifiP2pService: P2pDisablingState
,08-29 11:25:29.693  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-29 11:25:29.693  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 11:25:29.693  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 11:25:29.703  1016  1126 V NetworkStats: performPollLocked() took 9ms
08-29 11:25:29.703  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:29.703  3306  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 11:25:29.703  1016  1029 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 11:25:29.703  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-29 11:25:29.703  2001  6942 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-29 11:25:29.713  1016  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,08-29 11:25:29.713  1016  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-29 11:25:29.723  1016  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-29 11:25:29.723  1177  1723 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292,
08-29 11:25:29.723  1016  1126 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:29.723  1016  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 11:25:29.723  1016  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-29 11:25:29.723  1016  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:29.723  1016  1123 D WifiP2pService: p2p socket connection lost
08-29 11:25:29.723  1016  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 11:25:29.723  1016  1123 D WifiP2pService: P2pDisabledState
08-29 11:25:29.723  1016  1124 E WifiNative-wlan0: do suspend true
08-29 11:25:29.723  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:29.723  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:29.733  1016  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-29 11:25:29.733  4767  6808 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 11:25:29.733  1456  1456 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 11:25:29.733  1456  1456 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:29.733  1016  1126 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-29 11:25:29.733  1016  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-29 11:25:29.733  1016  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-29 11:25:29.733   288   288 E SMD     : DCD OFF
,08-29 11:25:29.733  3306  3306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 11:25:29.743  3306  3306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 11:25:29.753  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 11:25:29.763   278  1015 D CommandListener: Clearing all IP addresses on wlan0
,08-29 11:25:29.763  1016  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-29 11:25:29.763  1016  1472 I art     : Explicit concurrent mark sweep GC freed 35685(1987KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 24MB/36MB, paused 11.040ms total 207.699ms
,08-29 11:25:29.763  1016  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-29 11:25:29.763  1016  1126 D ConnectivityService: nai.networkMonitor.doQuit()
08-29 11:25:29.763  1016  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-29 11:25:29.763  1016  1126 E ConnectivityService: updateNetworkInfo()
08-29 11:25:29.763  1016  1126 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:25:29.763  1016  1126 E ConnectivityService: updateNetworkInfo()
,08-29 11:25:29.763  1016  1123 D WifiP2pService: DefaultState{ what=143375 }
,08-29 11:25:29.763  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-29 11:25:29.763  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 11:25:29.763  3306  3306 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 11:25:29.763  3306  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 11:25:29.773  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-29 11:25:29.773  1387  1387 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-29 11:25:29.773  1016  1129 D Tethering: MasterInitialState.processMessage what=3
,08-29 11:25:29.773   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 11:25:29.773  1016  1121 V NetworkStats: updateIfacesLocked()
,08-29 11:25:29.773  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-29 11:25:29.773  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:29.783  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:29.783  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:29.783  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:29.783  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:29.783  1016  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-29 11:25:29.783  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-29 11:25:29.783  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 11:25:29.783  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 11:25:29.783  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-29 11:25:29.783  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-29 11:25:29.783  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-29 11:25:29.783  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 11:25:29.783  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 11:25:29.793  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-29 11:25:29.793  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-29 11:25:29.793  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-29 11:25:29.793  1016  1121 V NetworkStats: performPollLocked() took 13ms
08-29 11:25:29.793  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 11:25:29.793  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 11:25:29.793  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 11:25:29.793  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:29.793  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:29.793  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:29.793  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:29.793  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:29.793  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 11:25:29.793  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 11:25:29.793  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:29.793  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:29.793  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:29.793  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:29.793  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-29 11:25:29.793  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:29.793  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:29.793  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:29.793  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:29.803  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 11:25:29.803  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 11:25:29.803  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:29.803  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:29.803  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:29.803  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:29.813  6948  6948 E Zygote  : MountEmulatedStorage(),
,08-29 11:25:29.813  6948  6948 E Zygote  : v2
08-29 11:25:29.813  6948  6948 I libpersona: KNOX_SDCARD checking this for 10064
,08-29 11:25:29.813  6948  6948 I libpersona: KNOX_SDCARD not a persona
08-29 11:25:29.813  1016  1029 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6948 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 11:25:29.813  6948  6948 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:29.823  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-29 11:25:29.823  1016  1124 D SecContentProvider2: mCursor = null
,08-29 11:25:29.823  6948  6948 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 11:25:29.823  6948  6948 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 11:25:29.833  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 11:25:29.833  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 11:25:29.833  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:29.833  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:29.833  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:29.833  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:29.833  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:29.833  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-29 11:25:29.833  1177  1765 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 11:25:29.833  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:29.833  1177  1177 D HotspotTile: onReceive : 0, 0
,08-29 11:25:29.843  3306  3306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:29.843  1387  1387 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 11:25:29.843  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:29.843  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:29.843  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:25:29.843  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:29.843  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:29.843  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:29.843  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:29.843  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:29.843  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:29.843  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:29.843  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:29.843  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:29.843  6746  6746 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:25:29.843  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:29.843  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:29.843  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:29.843  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:29.843  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:29.843  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:29.843  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:29.843  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:29.843  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:29.843  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:29.843  6746  6746 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:25:29.853  6948  6948 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:29.853  6948  6948 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:29.863  2001  2171 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-29 11:25:29.863  6948  6948 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-29 11:25:29.863  2001  2171 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-29 11:25:29.883  6948  6948 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 11:25:29.893  1387  1387 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-29 11:25:29.893  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-29 11:25:29.893  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 11:25:29.893  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
08-29 11:25:29.893  6948  6948 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-29 11:25:29.893  1016  1497 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-29 11:25:29.913  2001  6867 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 11:25:29.913  2001  6867 I qtaguid : Tagging socket 77 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2001, getuid(): 10011
,08-29 11:25:29.913  1387  1387 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-29 11:25:29.913  2001  6867 I qtaguid : Untagging socket 77
08-29 11:25:29.913  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 11:25:29.913  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 11:25:29.913  2001  6867 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-29 11:25:29.913  1387  1387 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-29 11:25:29.913  1387  1387 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-29 11:25:29.913  2001  6867 I qtaguid : Tagging socket 47 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2001, getuid(): 10011
08-29 11:25:29.913  1387  1387 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-29 11:25:29.913  1387  1387 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-29 11:25:29.913  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 11:25:29.923  1016  1129 D Tethering: InitialState.processMessage what=4
,08-29 11:25:29.923  1016  1129 E Tethering: No numeric data
,08-29 11:25:29.923  2001  6867 I qtaguid : Untagging socket 47
08-29 11:25:29.923  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 11:25:29.923  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 11:25:29.923  2001  6867 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 11:25:29.923  2001  6867 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 11:25:29.923  2001  6867 I qtaguid : Tagging socket 47 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2001, getuid(): 10011
08-29 11:25:29.923  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 11:25:29.923  1016  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 11:25:29.923  1016  1129 D Tethering: clearTetheredNotification()
,08-29 11:25:29.923  2001  6867 I qtaguid : Untagging socket 47
,08-29 11:25:29.923  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 11:25:29.923  2001  6867 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 11:25:29.923  2001  6867 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-29 11:25:29.923  2001  6867 I qtaguid : Tagging socket 47 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2001, getuid(): 10011
,08-29 11:25:29.923  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 11:25:29.923  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:29.923  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-29 11:25:29.923  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 11:25:29.923  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 11:25:29.923  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 11:25:29.923  1177  1177 D HotspotTile: updateTetherState():false, false
,08-29 11:25:29.923  2001  6867 I qtaguid : Untagging socket 47
08-29 11:25:29.923  2001  6867 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 11:25:29.923  2001  6867 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-29 11:25:29.923  2001  6867 I qtaguid : Tagging socket 47 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2001, getuid(): 10011
,08-29 11:25:29.933  2001  6867 I qtaguid : Untagging socket 47
08-29 11:25:29.933  1016  1121 V NetworkStats: performPollLocked() took 4ms
,08-29 11:25:29.933  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:29.933  2001  6867 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 11:25:29.933  2001  6867 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-29 11:25:29.933  2001  6867 I qtaguid : Tagging socket 47 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2001, getuid(): 10011
,08-29 11:25:29.933  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 11:25:29.933  2001  6867 I qtaguid : Untagging socket 47
08-29 11:25:29.933  2001  6867 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 11:25:29.933  2001  6867 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-29 11:25:29.933  2001  6867 I qtaguid : Tagging socket 47 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2001, getuid(): 10011
,08-29 11:25:29.933  2001  6867 I qtaguid : Untagging socket 47
,08-29 11:25:29.933  2001  6867 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 11:25:29.933  2001  6867 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-29 11:25:29.933  2001  6867 I qtaguid : Tagging socket 47 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2001, getuid(): 10011
,08-29 11:25:29.933  2001  6867 I qtaguid : Untagging socket 47
,08-29 11:25:29.933  2001  6867 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 11:25:29.933  2001  6867 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-29 11:25:29.933  2001  6867 I qtaguid : Tagging socket 47 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2001, getuid(): 10011
08-29 11:25:29.933  2001  6867 I qtaguid : Untagging socket 47
08-29 11:25:29.933  2001  6867 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 11:25:29.933  2001  6867 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-29 11:25:29.933  2001  6867 I qtaguid : Tagging socket 47 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2001, getuid(): 10011
,08-29 11:25:29.943  2001  6867 I qtaguid : Untagging socket 47
,08-29 11:25:29.943  2001  6867 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 11:25:29.943  2001  6867 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-29 11:25:29.943  2001  6867 I qtaguid : Tagging socket 47 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2001, getuid(): 10011
,08-29 11:25:29.943  2001  6867 I qtaguid : Untagging socket 47
08-29 11:25:29.943  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:29.943  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:29.943  2001  6867 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 11:25:29.943  2001  6867 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-29 11:25:29.943  2001  6867 I qtaguid : Tagging socket 47 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2001, getuid(): 10011
,08-29 11:25:29.943  2001  6867 I qtaguid : Untagging socket 47
,08-29 11:25:29.943  2001  6867 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/216.58.214.74 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
,08-29 11:25:29.963  6948  6948 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 11:25:29.963  1016  1224 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-29 11:25:29.963  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:29.963  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:29.963  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:29.963  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:29.973   268   268 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7e907c8,
08-29 11:25:29.973  1016  1224 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6967 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 11:25:29.973   268   268 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,08-29 11:25:29.973   268   268 I rmt_storage: wakelock acquired: 1, error no: 42
08-29 11:25:29.973   268   368 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1209464696)
,08-29 11:25:29.983  6967  6967 E Zygote  : MountEmulatedStorage()
,08-29 11:25:29.983  6967  6967 I libpersona: KNOX_SDCARD checking this for 10065
08-29 11:25:29.983  6967  6967 E Zygote  : v2
08-29 11:25:29.983  6967  6967 I libpersona: KNOX_SDCARD not a persona
08-29 11:25:29.983  6967  6967 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 11:25:29.983  6967  6967 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 11:25:29.983  6967  6967 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 11:25:29.993  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,08-29 11:25:29.993  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 11:25:30.003  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,08-29 11:25:30.003  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 11:25:30.003  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 11:25:30.003  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 11:25:30.003  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 11:25:30.013  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 11:25:30.013  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 11:25:30.013  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 11:25:30.013  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 11:25:30.013  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 11:25:30.013  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 11:25:30.013  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 11:25:30.023  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 11:25:30.023  6967  6967 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:30.023  6967  6967 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:30.023  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 11:25:30.023  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 11:25:30.023  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 11:25:30.023  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 11:25:30.023  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 11:25:30.033  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 11:25:30.033  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 11:25:30.033  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
08-29 11:25:30.033  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 11:25:30.033  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 11:25:30.033   268   368 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-29 11:25:30.033   268   368 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-29 11:25:30.033   268   368 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1209464696) wakelock released: 1, error no: 0
08-29 11:25:30.033   268   368 I rmt_storage: 
,08-29 11:25:30.033  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 11:25:30.033  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 11:25:30.033   268   268 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7e907c8
,08-29 11:25:30.043  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-29 11:25:30.043  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 11:25:30.043  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
,08-29 11:25:30.043  6967  6967 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 11:25:30.063  1016  1471 I ActivityManager: Killing 6478:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-29 11:25:30.073  1016  1471 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:30.073  1016  1471 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-29 11:25:30.073  1016  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:30.073  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-29 11:25:30.073  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:30.073  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:30.073  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:30.073  1016  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:30.083  6997  6997 E Zygote  : MountEmulatedStorage(),
,08-29 11:25:30.083  6997  6997 E Zygote  : v2
,08-29 11:25:30.083  1016  1471 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6997 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-29 11:25:30.093  6997  6997 I libpersona: KNOX_SDCARD checking this for 10102,
08-29 11:25:30.093  6997  6997 I libpersona: KNOX_SDCARD not a persona
08-29 11:25:30.093  6997  6997 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:30.093  6997  6997 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 11:25:30.093  6997  6997 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 11:25:30.113  1387  1387 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 11:25:30.113  6997  6997 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:30.113  6997  6997 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:30.123  6997  6997 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 11:25:30.243  1387  1387 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
08-29 11:25:30.253  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 11:25:30.253  1016  1043 D Tethering: interfaceStatusChanged wlan0, false,
,08-29 11:25:30.253  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 11:25:30.253  1016  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:25:30.263  1016  1016 I ApplicationPolicy: updateDataUsageMap,
,08-29 11:25:30.263  1016  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:25:30.283  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:30.283  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:30.353  1016  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-29 11:25:30.353  1016  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 11:25:30.353  6997  7017 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-29 11:25:30.353  6997  7017 I Babel_SMS: MmsConfig.loadMmsSettings
,08-29 11:25:30.353  6997  7017 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-29 11:25:30.353  6997  7017 I Babel_SMS: MmsConfig.loadFromDatabase
,08-29 11:25:30.353  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 11:25:30.363  2001  2161 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 11:25:30.363  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-29 11:25:30.363  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:30.363  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:30.363  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:30.363  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:30.363  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:25:30.363  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-29 11:25:30.363  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:30.363  3306  3306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:30.363  1177  1765 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 11:25:30.363  1177  1177 D HotspotTile: onReceive : 1, 0
,08-29 11:25:30.373  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:30.373  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:30.383  6997  7017 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-29 11:25:30.383  6997  7017 I Babel_SMS: MmsConfig.loadFromResources
,08-29 11:25:30.383  6997  7017 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-29 11:25:30.383  6997  7017 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-29 11:25:30.413  1016  1224 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-29 11:25:30.413  1016  1224 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-29 11:25:30.413  1016  1224 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:30.413  1016  1224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:30.413  1016  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 11:25:30.433  6997  6997 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 11:25:30.433  6997  6997 I Babel_Crash: startup - clean
,08-29 11:25:30.463  1016  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:30.463  1016  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:30.463  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 11:25:30.473  6997  6997 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 11:25:30.473  6997  6997 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 11:25:30.483  6997  6997 W AudioCapabilities: Unsupported mime audio/qcelp
,08-29 11:25:30.483  6997  6997 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-29 11:25:30.483  6997  6997 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-29 11:25:30.483  6997  6997 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-29 11:25:30.483  6997  6997 W AudioCapabilities: Unsupported mime audio/x-ima
,08-29 11:25:30.493  6997  6997 W AudioCapabilities: Unsupported mime audio/qcelp
,08-29 11:25:30.493  6997  6997 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 11:25:30.503  6997  6997 W VideoCapabilities: Unsupported mime video/wvc1
,08-29 11:25:30.503  6997  6997 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 11:25:30.513  6997  6997 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-29 11:25:30.513  6997  6997 W VideoCapabilities: Unsupported mime video/wvc1
,08-29 11:25:30.513  6997  6997 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 11:25:30.513  6997  6997 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-29 11:25:30.513  6997  6997 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-29 11:25:30.513  6997  6997 W VideoCapabilities: Unsupported mime video/mp43
,08-29 11:25:30.523  6997  6997 W VideoCapabilities: Unsupported mime video/sorenson
,08-29 11:25:30.523  6997  6997 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-29 11:25:30.543  6997  6997 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-29 11:25:30.563  6997  6997 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 11:25:30.563  6997  6997 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 11:25:30.563  6997  6997 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 11:25:30.573  6997  6997 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 11:25:30.573  1016  1472 I ActivityManager: Killing 6504:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-29 11:25:30.573  6997  6997 I vclib   : onServiceConnected
,08-29 11:25:30.653  1016  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 11:25:30.653  1016  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 11:25:30.653  1016  1480 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:30.653  1016  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:30.653  1016  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 11:25:30.653  1598  1598 I Hs20UtilService: Starting #9
08-29 11:25:30.653  1598  1647 I Hs20UtilService: Message received 5007
,08-29 11:25:30.663  3306  3306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 11:25:30.663  3306  3306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 11:25:30.663  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 11:25:30.663  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 11:25:30.663  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 11:25:30.663  3306  3306 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 11:25:30.663  3306  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 11:25:30.673  1016  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:30.673  1016  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:30.673  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 11:25:30.683  1016  1550 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 11:25:30.683  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 11:25:30.683  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:30.683  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:30.683  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 11:25:30.693  1598  1598 I Hs20UtilService: Starting #10
,08-29 11:25:30.693  1598  1647 I Hs20UtilService: Message received 5011
,08-29 11:25:30.693  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 11:25:30.693  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 11:25:30.693  6555  6555 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 11:25:30.693  6555  6555 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 11:25:30.703  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:30.703  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:30.703  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 11:25:30.703  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:30.703  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:30.703  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 11:25:30.703  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:30.703  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:30.703  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 11:25:30.713  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:30.713  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:30.713  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 11:25:30.713  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:30.713  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:30.713  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 11:25:30.713  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:30.713  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:30.713  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 11:25:30.723  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:30.723  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:30.723  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 11:25:30.723  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:30.723  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:30.723  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 11:25:30.723  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:30.723  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:30.723  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 11:25:30.733  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:30.733  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:30.733  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 11:25:30.733  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:30.733  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:30.733  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 11:25:30.733  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:30.733  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:30.733  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 11:25:30.733  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:30.733  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:30.733  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 11:25:30.743  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-29 11:25:30.743  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:30.743  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:30.743  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:30.743  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:30.753  1016  1016 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7020 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-29 11:25:30.753  7020  7020 E Zygote  : MountEmulatedStorage()
08-29 11:25:30.753  7020  7020 I libpersona: KNOX_SDCARD checking this for 1000
,08-29 11:25:30.753  7020  7020 E Zygote  : v2
08-29 11:25:30.753  7020  7020 I libpersona: KNOX_SDCARD not a persona
08-29 11:25:30.753  7020  7020 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:30.753  7020  7020 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 11:25:30.763  7020  7020 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 11:25:30.773   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 11:25:30.783  7020  7020 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:30.783  7020  7020 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:30.803  7020  7020 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-29 11:25:30.803  7020  7020 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-29 11:25:30.803  7020  7020 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-29 11:25:30.813  7020  7020 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-29 11:25:30.813  7020  7020 I PCWCLIENTTRACE_PushUtil: sales region : global
08-29 11:25:30.813  7020  7020 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-29 11:25:30.813  7020  7020 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:25:30.823  1016  1028 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
08-29 11:25:30.823  1016  1028 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-29 11:25:30.823  7020  7035 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-29 11:25:30.823  1016  1028 I ActivityManager: Killing 6527:com.samsung.android.sm/1000 (adj 15): empty #21
,08-29 11:25:30.833  1016  1480 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-29 11:25:30.833  1016  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:30.833  1016  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:30.833  1016  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:30.833  1016  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:30.843  7037  7037 E Zygote  : MountEmulatedStorage(),
08-29 11:25:30.843  7037  7037 E Zygote  : v2
08-29 11:25:30.843  7037  7037 I libpersona: KNOX_SDCARD checking this for 10031,
08-29 11:25:30.843  7037  7037 I libpersona: KNOX_SDCARD not a persona
,08-29 11:25:30.853  7037  7037 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 11:25:30.853  1016  1480 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7037 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-29 11:25:30.853  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-29 11:25:30.853  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:30.853  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:30.853  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:30.853  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:30.853  7037  7037 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 11:25:30.853  7037  7037 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 11:25:30.853  1781  1781 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 11:25:30.873  7037  7037 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-29 11:25:30.873   306   306 I art     : Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 26.897ms
08-29 11:25:30.873  7037  7037 D ActivityThread: Added TimaKeyStore provider,
,08-29 11:25:30.893   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 620us total 16.455ms
,08-29 11:25:30.903   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 571us total 16.111ms
,08-29 11:25:30.923  7052  7052 E Zygote  : MountEmulatedStorage(),
08-29 11:25:30.923  7052  7052 I libpersona: KNOX_SDCARD checking this for 10121
08-29 11:25:30.923  7052  7052 E Zygote  : v2
08-29 11:25:30.923  7052  7052 I libpersona: KNOX_SDCARD not a persona
08-29 11:25:30.923  7052  7052 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 11:25:30.923  1016  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7052 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-29 11:25:30.923  7052  7052 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 11:25:30.923  7052  7052 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 11:25:30.933  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast,
08-29 11:25:30.933  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:30.933  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:30.933  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:30.933  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:30.943  2477  2486 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,08-29 11:25:30.953  7052  7052 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:30.953  7052  7052 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:30.963  7067  7067 E Zygote  : MountEmulatedStorage()
08-29 11:25:30.963  7067  7067 I libpersona: KNOX_SDCARD checking this for 10001
08-29 11:25:30.963  7067  7067 E Zygote  : v2
08-29 11:25:30.963  7067  7067 I libpersona: KNOX_SDCARD not a persona
,08-29 11:25:30.963  7067  7067 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:30.973  1016  1043 D Tethering: interfaceRemoved wlan0
08-29 11:25:30.973  1016  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-29 11:25:30.973  7067  7067 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 11:25:30.973  1016  1016 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7067 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 11:25:30.973  7067  7067 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 11:25:30.973  1781  1781 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-29 11:25:30.973  1781  1781 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-29 11:25:30.973  1781  1781 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-29 11:25:30.973  1781  1781 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-29 11:25:30.983  7037  7037 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-29 11:25:30.993  1781  1781 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 11:25:30.993  1781  1781 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-29 11:25:30.993  1016  1329 I ActivityManager: Killing 6576:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-29 11:25:31.013  7052  7052 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 11:25:31.013  7052  7052 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 11:25:31.013  7052  7052 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 11:25:31.013  1016  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 11:25:31.013  1016  1329 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-29 11:25:31.013  1016  1134 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 11:25:31.013  1016  1134 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 11:25:31.013  1016  1134 D BatteryService: stay LED for fully charged
08-29 11:25:31.013  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-29 11:25:31.013  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.013  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.013  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.013  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:31.023  7067  7067 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:31.023  7067  7067 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:31.023  7052  7052 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:25:31.023  7082  7082 E Zygote  : MountEmulatedStorage()
,08-29 11:25:31.033  7082  7082 E Zygote  : v2,
08-29 11:25:31.033  7082  7082 I libpersona: KNOX_SDCARD checking this for 10077
08-29 11:25:31.033  1016  1329 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7082 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-29 11:25:31.033  7082  7082 I libpersona: KNOX_SDCARD not a persona
,08-29 11:25:31.033  7082  7082 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 11:25:31.033  7052  7052 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-29 11:25:31.033  1016  1479 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
08-29 11:25:31.043  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.043  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.043  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.043  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:31.043  7082  7082 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 11:25:31.043  2801  7088 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-29 11:25:31.043  7082  7082 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-29 11:25:31.043  2801  7088 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-29 11:25:31.043  2801  7088 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-29 11:25:31.053  2801  7088 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-29 11:25:31.053  2801  7088 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-29 11:25:31.053  7092  7092 E Zygote  : MountEmulatedStorage()
,08-29 11:25:31.053  7092  7092 E Zygote  : v2
08-29 11:25:31.053  7092  7092 I libpersona: KNOX_SDCARD checking this for 10032
08-29 11:25:31.053  7092  7092 I libpersona: KNOX_SDCARD not a persona
08-29 11:25:31.053  7092  7092 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:31.063  7092  7092 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 11:25:31.063  1016  1479 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7092 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 11:25:31.063  7092  7092 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-29 11:25:31.063  1016  1016 I MotionRecognitionService: Plugged
08-29 11:25:31.063  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 11:25:31.063  7082  7082 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 11:25:31.073  7082  7082 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:31.073  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 11:25:31.073  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 11:25:31.073  1016  1043 D Tethering: interfaceRemoved p2p0
08-29 11:25:31.073  1016  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-29 11:25:31.073  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 11:25:31.073  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 11:25:31.093  7052  7052 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-29 11:25:31.093  1016  1329 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-29 11:25:31.093  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.093  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.093  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.093  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.103  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-29 11:25:31.103  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-29 11:25:31.103  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 11:25:31.103  7092  7092 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:31.103  7092  7092 D ActivityThread: Added TimaKeyStore provider
08-29 11:25:31.103  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 11:25:31.103  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 11:25:31.113  7113  7113 E Zygote  : MountEmulatedStorage()
,08-29 11:25:31.113  7113  7113 E Zygote  : v2
08-29 11:25:31.113  7113  7113 I libpersona: KNOX_SDCARD checking this for 10141
08-29 11:25:31.113  7113  7113 I libpersona: KNOX_SDCARD not a persona
08-29 11:25:31.113  7113  7113 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 11:25:31.113  1016  1329 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7113 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-29 11:25:31.113  7113  7113 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 11:25:31.123  7113  7113 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 11:25:31.123  1016  1329 I ActivityManager: Killing 6593:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-29 11:25:31.133  7113  7113 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:31.143  7113  7113 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:31.153  7113  7113 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-29 11:25:31.153  7113  7113 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 11:25:31.153  7113  7113 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 11:25:31.153  7113  7113 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-29 11:25:31.163  1016  1553 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-29 11:25:31.173  1016  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:31.173  1016  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:31.173  1016  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.173  1016  1553 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:31.183  7092  7130 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-29 11:25:31.183  7092  7130 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-29 11:25:31.183  7131  7131 E Zygote  : MountEmulatedStorage()
,08-29 11:25:31.183  7131  7131 E Zygote  : v2
08-29 11:25:31.183  7131  7131 I libpersona: KNOX_SDCARD checking this for 1000
08-29 11:25:31.183  7131  7131 I libpersona: KNOX_SDCARD not a persona
08-29 11:25:31.183  7131  7131 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:31.193  1016  1553 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7131 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 11:25:31.193  1016  1553 I ActivityManager: Killing 6610:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-29 11:25:31.193  7092  7130 D SPPClientService: PushLog.txt file is not deleted.
,08-29 11:25:31.193  7092  7130 D SPPClientService: PushLog.txt file is not deleted.
08-29 11:25:31.193  7092  7130 D SPPClientService: ============PushLog. stop!
,08-29 11:25:31.203  7131  7131 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 11:25:31.203  7131  7131 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-29 11:25:31.213  1016  1550 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 11:25:31.223  1016  1497 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 11:25:31.243  7131  7131 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:31.243  7131  7131 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:31.243  7092  7092 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-29 11:25:31.243  1016  1329 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-29 11:25:31.253  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.253  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.253  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.253  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:31.283  1016  1134 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 11:25:31.293  1016  1329 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7155 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 11:25:31.293  1016  1329 I ActivityManager: Killing 6630:com.qualcomm.timeservice/1000 (adj 15): empty #21
08-29 11:25:31.293  1016  1479 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-29 11:25:31.293  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-29 11:25:31.303  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:31.303  1016  1479 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-29 11:25:31.303  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-29 11:25:31.303  7155  7155 E Zygote  : MountEmulatedStorage()
,08-29 11:25:31.303  7155  7155 E Zygote  : v2
08-29 11:25:31.303  7155  7155 I libpersona: KNOX_SDCARD checking this for 10036,
08-29 11:25:31.303  7155  7155 I libpersona: KNOX_SDCARD not a persona
,08-29 11:25:31.303  7155  7155 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-29 11:25:31.313  7155  7155 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 11:25:31.313  7155  7155 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-29 11:25:31.323  1016  1480 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 11:25:31.343  7155  7155 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:31.343  7155  7155 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:31.353  7131  7131 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-29 11:25:31.383  7092  7161 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-29 11:25:31.403  1016  1550 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-29 11:25:31.403  1016  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:31.413  1016  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.413  1016  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.413  1016  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:31.413  7155  7155 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@20ffdcc7
,08-29 11:25:31.423  7174  7174 E Zygote  : MountEmulatedStorage()
08-29 11:25:31.423  1016  1550 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7174 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-29 11:25:31.423  7174  7174 E Zygote  : v2
08-29 11:25:31.423  7174  7174 I libpersona: KNOX_SDCARD checking this for 10068
08-29 11:25:31.423  7155  7155 I SA      : [SSP] onCreated
08-29 11:25:31.423  7174  7174 I libpersona: KNOX_SDCARD not a persona
,08-29 11:25:31.433  7174  7174 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 11:25:31.433  7174  7174 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 11:25:31.443  7174  7174 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 11:25:31.443  1016  1029 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 11:25:31.453  1016  1329 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 11:25:31.463  7155  7155 I SA      : [TPM] There is no property file
,08-29 11:25:31.463  7174  7174 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:31.463  7174  7174 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:31.463  7155  7155 I SA      : [SCU] isHaveSA() - false
,08-29 11:25:31.473  7155  7155 I SA      : [TPM] getModelProperty : null
,08-29 11:25:31.473  7155  7155 I SA      : [TPM] getCSCProperty : null
,08-29 11:25:31.473  7155  7155 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-29 11:25:31.473  7155  7155 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-29 11:25:31.473  7155  7155 I SA      : [DM] TFT FEATURE: false
,08-29 11:25:31.483  7155  7155 I SA      : [DM] init START
,08-29 11:25:31.483  7155  7155 I SA      : [DM] This device is not a Vodafone
,08-29 11:25:31.483  1016  1471 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 11:25:31.493  7155  7155 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-29 11:25:31.493  7155  7155 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-29 11:25:31.493  7155  7155 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-29 11:25:31.493  7155  7155 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-29 11:25:31.493  7155  7155 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-29 11:25:31.493  7155  7155 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-29 11:25:31.493  7155  7155 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-29 11:25:31.503  7174  7174 D BadgeProvider: onCreate
08-29 11:25:31.503  1016  1497 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 11:25:31.503  7174  7174 D BadgeProvider: DatabaseHelper
,08-29 11:25:31.503  7155  7155 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 11:25:31.503  7155  7155 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-29 11:25:31.503  7155  7155 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-29 11:25:31.503  7155  7155 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-29 11:25:31.503  1016  1224 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-29 11:25:31.503  7155  7155 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-29 11:25:31.503  7155  7155 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-29 11:25:31.503  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.503  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.503  7155  7155 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-29 11:25:31.503  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.503  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:31.503  7155  7155 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-29 11:25:31.503  7155  7155 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-29 11:25:31.503  7155  7155 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-29 11:25:31.503  7155  7155 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-29 11:25:31.503  7155  7155 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-29 11:25:31.513  7155  7155 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-29 11:25:31.513  7155  7155 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-29 11:25:31.513  7155  7155 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-29 11:25:31.513  7155  7155 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-29 11:25:31.523  7195  7195 I libpersona: KNOX_SDCARD checking this for 10009
08-29 11:25:31.513  7155  7155 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-29 11:25:31.523  7195  7195 I libpersona: KNOX_SDCARD not a persona
08-29 11:25:31.513  7155  7155 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-29 11:25:31.513  7155  7155 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-29 11:25:31.513  7155  7155 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-29 11:25:31.513  7155  7155 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
08-29 11:25:31.513  7155  7155 I SA      : [SCU] isHaveSA() - false
08-29 11:25:31.513  7155  7155 I SA      : support phone number id : false
08-29 11:25:31.513  7155  7155 I SA      : [DM] Supports Ref Jpn : true
08-29 11:25:31.513  7155  7155 I SA      : [DM] init END
08-29 11:25:31.513  7155  7155 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
08-29 11:25:31.523  7195  7195 E Zygote  : MountEmulatedStorage()
08-29 11:25:31.523  7195  7195 E Zygote  : v2
08-29 11:25:31.523  7195  7195 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 11:25:31.523  7155  7155 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-29 11:25:31.523  7155  7155 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-29 11:25:31.523  7195  7195 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 11:25:31.523  7195  7195 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-29 11:25:31.523  7174  7191 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-29 11:25:31.533  1016  1224 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7195 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-29 11:25:31.533  1016  1224 I ActivityManager: Killing 6061:com.android.mms/u0a41 (adj 15): empty #21
08-29 11:25:31.533  1016  1224 I ActivityManager: Killing 6546:com.android.providers.calendar/u0a37 (adj 15): empty #22
,08-29 11:25:31.543  7155  7155 I SA      : [SLFUCHKMGR] constructor called
,08-29 11:25:31.553  7195  7195 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:31.553  7195  7195 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:31.553  7174  7202 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-29 11:25:31.553  7174  7202 D BadgeProvider: sendNotify, [notify] : null
08-29 11:25:31.553  7174  7202 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-29 11:25:31.553  7174  7202 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-29 11:25:31.553  7174  7202 D BadgeProvider: update, [UpdateCount] : 1
08-29 11:25:31.553  1481  1481 D Launcher.Model: reloadBadges entered.
,08-29 11:25:31.563  1016  1471 D CountryDetector: No listener is left
,08-29 11:25:31.573  7155  7155 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-29 11:25:31.583  7155  7155 I SA      : [OR] == isSIMCardReady false ==
,08-29 11:25:31.593  7155  7155 I SA      : [SCU] == networkStateCheck == false
08-29 11:25:31.593  7155  7155 I SA      : [OR] onReceive END
,08-29 11:25:31.593  1016  1329 I ActivityManager: Killing 6654:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-29 11:25:31.603  1231  1231 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:25:31.613  1016  1553 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-29 11:25:31.613  1016  1553 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-29 11:25:31.613  7131  7131 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-29 11:25:31.613  1016  1553 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:31.613  1016  1553 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 11:25:31.613  1016  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 11:25:31.623  1016  1224 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-29 11:25:31.623  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:31.623  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.623  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:31.623  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:31.623  7131  7131 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,08-29 11:25:31.633  7131  7131 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:25:31.633  7131  7131 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-29 11:25:31.633  7131  7131 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-29 11:25:31.633  7131  7131 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-29 11:25:31.653  7217  7217 E Zygote  : MountEmulatedStorage(),
08-29 11:25:31.653  7217  7217 E Zygote  : v2
08-29 11:25:31.653  7217  7217 I libpersona: KNOX_SDCARD checking this for 10110
08-29 11:25:31.653  7217  7217 I libpersona: KNOX_SDCARD not a persona
08-29 11:25:31.653  7217  7217 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:31.653  7217  7217 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 11:25:31.653  1016  1224 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7217 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 11:25:31.653  7217  7217 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-29 11:25:31.653  1016  1224 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-29 11:25:31.663  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.663  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.663  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:31.663  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:31.673  7232  7232 E Zygote  : MountEmulatedStorage()
,08-29 11:25:31.673  7232  7232 E Zygote  : v2
08-29 11:25:31.673  7232  7232 I libpersona: KNOX_SDCARD checking this for 10008
08-29 11:25:31.673  7232  7232 I libpersona: KNOX_SDCARD not a persona
,08-29 11:25:31.673  7232  7232 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 11:25:31.673  7217  7217 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:31.683  7217  7217 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:31.683  7232  7232 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 11:25:31.683  1016  1224 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7232 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 11:25:31.693  1016  1224 I ActivityManager: Killing 6671:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-29 11:25:31.693  7232  7232 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-29 11:25:31.693  1016  1551 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-29 11:25:31.693  1016  1551 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-29 11:25:31.693  1016  1551 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:31.693  1016  1551 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:31.693  1016  1551 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 11:25:31.703  6997  7215 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-29 11:25:31.703   306   306 I art     : Explicit concurrent mark sweep GC freed 8690(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 649us total 24.399ms
,08-29 11:25:31.713  1016  1224 I ActivityManager: Killing 6487:com.android.calendar/u0a131 (adj 15): empty #21
,08-29 11:25:31.713  1016  1551 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 11:25:31.713  1016  1551 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-29 11:25:31.713  1016  1551 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:31.713  1016  1551 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:31.713  1016  1551 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:31.723  1016  1553 I ActivityManager: Killing 6686:com.google.android.gms:car/u0a11 (adj 15): empty #21,
,08-29 11:25:31.733   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 24.891ms
,08-29 11:25:31.733  4767  7245 I iu.SyncManager: SYNC; picasa accounts
,08-29 11:25:31.743  7232  7232 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:31.753   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 16.888ms,
08-29 11:25:31.753  7232  7232 D ActivityThread: Added TimaKeyStore provider
08-29 11:25:31.753  4767  4767 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-29 11:25:31.763  1016  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-29 11:25:31.773  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-29 11:25:31.773  1016  1479 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-29 11:25:31.773  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-29 11:25:31.773  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-29 11:25:31.773   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 11:25:31.823  1016  1029 I ActivityManager: Killing 6007:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-29 11:25:31.833  2897  2897 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 29 11:25:31 GMT+02:00 2016
,08-29 11:25:31.833  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-29 11:25:31.833  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-29 11:25:31.833  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:31.833  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:31.833  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-29 11:25:31.833  2897  2897 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-29 11:25:31.843  1016  1472 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 11:25:31.843  1016  1472 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 11:25:31.843  1016  1472 D SecContentProvider2: mCursor = null
,08-29 11:25:31.843  1016  1472 D WifiService: setWifiEnabled: true pid=6746, uid=10171
08-29 11:25:31.843  1016  1472 W ActivityManager: Permission Denial: getCurrentUser() from pid=6746, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 11:25:31.843  1016  1472 W WifiService: Failed getting userId using ActivityManagerNative
08-29 11:25:31.843  1016  1472 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6746, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 11:25:31.843  1016  1472 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 11:25:31.843  1016  1472 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 11:25:31.843  1016  1472 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 11:25:31.843  1016  1472 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 11:25:31.843  1016  1472 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 11:25:31.843  1016  1472 D SettingsProvider: name = wifi_on
,08-29 11:25:31.843  2897  2897 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-29 11:25:31.843  2897  2897 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-29 11:25:31.843  2897  2897 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-29 11:25:31.853  2897  7249 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-29 11:25:31.853  2897  7249 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-29 11:25:31.853  2897  7249 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-29 11:25:31.853  2897  7249 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-29 11:25:31.863  2897  2897 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
08-29 11:25:31.863  1016  1124 E WifiHW  : ##################### set firmware type 0 #####################
,08-29 11:25:31.933  1016  1553 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 11:25:32.033   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-29 11:25:32.033   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 11:25:32.043  7217  7254 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-29 11:25:32.043   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-29 11:25:32.043   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 11:25:32.043  7217  7254 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-29 11:25:32.053   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-29 11:25:32.053   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 11:25:32.053  7217  7255 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-29 11:25:32.063   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/,
08-29 11:25:32.063   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 11:25:32.073  7217  7255 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-29 11:25:32.073  7217  7217 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 11:25:32.073  7217  7217 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 11:25:32.073  7217  7217 I GAv4    :   adb logcat -s GAv4
,08-29 11:25:32.093  7217  7217 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 11:25:32.093  1016  1028 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 11:25:32.103  7217  7217 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 11:25:32.113  7217  7263 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 11:25:32.223  1016  1043 D Tethering: interfaceAdded wlan0
,08-29 11:25:32.233  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 11:25:32.233  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 11:25:32.233  1016  1129 E Tethering: No numeric data
08-29 11:25:32.233  1016  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 11:25:32.233  1016  1129 D Tethering: clearTetheredNotification()
,08-29 11:25:32.233  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 11:25:32.233  1016  1129 D Tethering: InitialState.processMessage what=4
,08-29 11:25:32.243  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 11:25:32.243  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:32.243  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated,
,08-29 11:25:32.243  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 11:25:32.243  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 11:25:32.243  1016  1043 D Tethering: interfaceAdded p2p0
08-29 11:25:32.243  1177  1177 D HotspotTile: updateTetherState():false, false
08-29 11:25:32.243  1016  1129 E Tethering: No numeric data
08-29 11:25:32.243  1016  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
08-29 11:25:32.243  1016  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
08-29 11:25:32.243  1016  1129 D Tethering: clearTetheredNotification()
,08-29 11:25:32.243   278  1015 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-29 11:25:32.243   278  1015 D SoftapController: Softap fwReload - Ok,
08-29 11:25:32.243  1016  1121 V NetworkStats: performPollLocked() took 7ms
08-29 11:25:32.243  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:32.243  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-29 11:25:32.243  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 11:25:32.243  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 11:25:32.253   278  1015 D CommandListener: Setting iface cfg,
08-29 11:25:32.253  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 11:25:32.253   278  1015 D CommandListener: Trying to bring down wlan0
08-29 11:25:32.253  1177  1177 D HotspotTile: updateTetherState():false, false
,08-29 11:25:32.253   278  1015 D CommandListener: Clearing all IP addresses on wlan0
08-29 11:25:32.253  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 11:25:32.253  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:32.253  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 11:25:32.253  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 11:25:32.253  1016  1121 V NetworkStats: performPollLocked() took 3ms
08-29 11:25:32.253  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:32.253  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:32.253  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:32.253  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:32.253  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:32.253  1016  1124 E WifiHW  : supplicant_name : p2p_supplicant
,08-29 11:25:32.253  1016  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 11:25:32.263  1016  1124 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-29 11:25:32.263  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 11:25:32.263  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 11:25:32.263  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:32.263  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:32.263  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:32.263  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:32.263  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:32.263  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-29 11:25:32.263  1177  1765 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 11:25:32.263  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:25:32.263  1177  1177 D HotspotTile: onReceive : 2, 0
,08-29 11:25:32.263  3306  3306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:25:32.273  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:32.273  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:32.323  7278  7278 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-29 11:25:32.323  7278  7278 I wpa_supplicant: Successfully initialized wpa_supplicant
08-29 11:25:32.323  7278  7278 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-29 11:25:32.343  7278  7278 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-29 11:25:32.343   348   348 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7278
08-29 11:25:32.343   348   348 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,08-29 11:25:32.343  7278  7278 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-29 11:25:32.343  7278  7278 I wpa_supplicant: ssSupport state is = 1
08-29 11:25:32.343  7278  7278 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-29 11:25:32.343  7278  7278 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-29 11:25:32.343   348   348 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7278
08-29 11:25:32.343   348   348 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-29 11:25:32.383  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:32.383  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:32.383  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:32.383  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-29 11:25:32.433  7217  7217 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-29 11:25:32.453  7217  7217 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 7720-7723),
08-29 11:25:32.453  7217  7217 I cr.library_loader: Expected native library version number "", actual native library version number "",
,08-29 11:25:32.453  7217  7217 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2293f29e}
08-29 11:25:32.453  7217  7217 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-29 11:25:32.453  7217  7217 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 11:25:32.483  7217  7217 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-29 11:25:32.483  7217  7217 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 11:25:32.483  7217  7217 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 11:25:32.503  7217  7217 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 11:25:32.503  7217  7217 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 11:25:32.503  7217  7217 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 11:25:32.503  7217  7217 I Adreno-EGL: Local Branch: 
08-29 11:25:32.503  7217  7217 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 11:25:32.503  7217  7217 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 11:25:32.503  7217  7217 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 11:25:32.563   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,08-29 11:25:32.573  7278  7278 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,08-29 11:25:32.603  7217  7217 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 11:25:32.603  7217  7294 W cr.media: Requires BLUETOOTH permission
,08-29 11:25:32.613  7217  7217 I NSApplication: Starting up...
,08-29 11:25:32.613  1016  1472 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output,
,08-29 11:25:32.623  1016  1553 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 11:25:32.623  7278  7278 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-29 11:25:32.623  7278  7278 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
08-29 11:25:32.623  1016  1329 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-29 11:25:32.623  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:32.623  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:32.623  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:32.623  1016  1329 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:32.643  7278  7278 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-29 11:25:32.643   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7278
08-29 11:25:32.643   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 11:25:32.643  7278  7278 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-29 11:25:32.643  7278  7278 I wpa_supplicant: ssSupport state is = 1
08-29 11:25:32.643  7278  7278 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-29 11:25:32.643  7278  7278 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-29 11:25:32.643  7278  7278 E wpa_supplicant: SIM READ ERROR
08-29 11:25:32.643  7278  7278 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 11:25:32.643  7278  7278 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 11:25:32.643  7278  7278 E wpa_supplicant: SIM READ ERROR
08-29 11:25:32.643  7278  7278 I wpa_supplicant: Blacklist: Clear (all) 
08-29 11:25:32.643  7278  7278 I wpa_supplicant: wpa_default_ap_write_once
,08-29 11:25:32.643  7278  7278 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 11:25:32.643  7278  7278 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 11:25:32.643  7278  7278 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-29 11:25:32.643  7278  7278 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 11:25:32.643  7278  7278 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 11:25:32.643  7300  7300 I libpersona: KNOX_SDCARD checking this for 10117
08-29 11:25:32.643  7300  7300 E Zygote  : MountEmulatedStorage()
08-29 11:25:32.643  7300  7300 I libpersona: KNOX_SDCARD not a persona,
08-29 11:25:32.643  7300  7300 E Zygote  : v2
,08-29 11:25:32.643  7278  7278 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 11:25:32.643  7300  7300 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:32.643  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 11:25:32.643  1016  1329 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7300 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-29 11:25:32.643  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 11:25:32.643  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 11:25:32.653  1016  1329 I ActivityManager: Killing 6882:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
08-29 11:25:32.653  1016  1329 I ActivityManager: Killing 5807:com.android.vending/u0a26 (adj 15): empty #22
08-29 11:25:32.653  7300  7300 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 11:25:32.653  7300  7300 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 11:25:32.673  7300  7300 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:32.673  7300  7300 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:32.693  7300  7300 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 11:25:32.703  7278  7278 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-29 11:25:32.733   288   288 E SMD     : DCD OFF
,08-29 11:25:32.783   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 11:25:32.873  7278  7278 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
08-29 11:25:32.873  7278  7278 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-29 11:25:32.883  7278  7278 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-29 11:25:32.893   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7278
08-29 11:25:32.893   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 11:25:32.893  7278  7278 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-29 11:25:32.893  7278  7278 I wpa_supplicant: ssSupport state is = 1
,08-29 11:25:32.893  7278  7278 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-29 11:25:32.893  7278  7278 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-29 11:25:32.903  7278  7278 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-29 11:25:32.903   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7278
08-29 11:25:32.903   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-29 11:25:32.903  7278  7278 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-29 11:25:32.903  7278  7278 I wpa_supplicant: ssSupport state is = 1
08-29 11:25:32.903  7278  7278 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-29 11:25:32.903  7278  7278 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 11:25:32.903  7278  7278 E wpa_supplicant: SIM READ ERROR
08-29 11:25:32.903  7278  7278 I wpa_supplicant: wpa_default_ap_write_once
08-29 11:25:32.903  7278  7278 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 11:25:32.903  7278  7278 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 11:25:32.903  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-29 11:25:32.903  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 11:25:32.903  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
08-29 11:25:32.903  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-29 11:25:32.903  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 11:25:32.913  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 11:25:33.003  7278  7278 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-29 11:25:33.003  7278  7278 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-29 11:25:33.033  1016  1224 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-29 11:25:33.033  1016  1224 I ActivityManager: Killing 6900:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-29 11:25:33.043  1016  1550 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 11:25:33.043  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 11:25:33.043  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:33.043  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:33.043  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 11:25:33.043  1598  1598 I Hs20UtilService: Starting #11
08-29 11:25:33.043  1598  1647 I Hs20UtilService: Message received 5011
,08-29 11:25:33.053  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 11:25:33.053  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 11:25:33.053  6555  6555 D SecurityLogAgent: StateMachine : Current State = 1
08-29 11:25:33.053  6555  6555 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 11:25:33.063  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 11:25:33.063  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 11:25:33.063  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:33.063  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:33.063  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 11:25:33.063  1598  1598 I Hs20UtilService: Starting #12
08-29 11:25:33.063  1598  1647 I Hs20UtilService: Message received 5011
,08-29 11:25:33.073  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 11:25:33.073  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 11:25:33.073  6555  6555 D SecurityLogAgent: StateMachine : Current State = 1
08-29 11:25:33.073  6555  6555 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 11:25:33.093  7278  7278 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-29 11:25:33.093  7278  7278 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-29 11:25:33.093  7278  7278 I wpa_supplicant: Skip scan - bUseNetwork false
,08-29 11:25:33.233  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-29 11:25:33.233  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 11:25:33.233  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 11:25:33.263  1016  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-29 11:25:33.263  1016  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 11:25:33.263  7278  7278 I wpa_supplicant: HOTSPOT20_ENABLE called
08-29 11:25:33.263  7278  7278 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-29 11:25:33.263  7278  7278 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 11:25:33.263  7278  7278 E wpa_supplicant: SIM READ ERROR
08-29 11:25:33.263  7278  7278 I wpa_supplicant: Blacklist: Clear (all) ,
,08-29 11:25:33.293  7278  7278 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-29 11:25:33.303  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-29 11:25:33.303  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 11:25:33.303  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:33.303  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 11:25:33.303  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 11:25:33.303  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:33.313  1177  1765 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
,08-29 11:25:33.313  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:33.313  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:33.313  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-29 11:25:33.313  1177  1177 D HotspotTile: onReceive : 3, 0
08-29 11:25:33.313  7278  7278 I wpa_supplicant: Skip scan - bUseNetwork false
,08-29 11:25:33.313  1016  1124 D WifiConfigStore: Loading config and enabling all networks 
08-29 11:25:33.313  3306  3306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:25:33.313  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:33.313  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:33.313  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:33.313  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:33.313  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:33.313  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:33.313  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:33.313  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:33.313  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:33.313  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:33.313  6746  6746 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:25:33.313  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:33.313  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:33.313  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:33.313  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:33.313  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:33.313  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:33.313  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:33.313  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:33.313  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:33.313  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:33.313  6746  6746 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:25:33.323  1016  1479 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 11:25:33.323  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 11:25:33.323  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:33.323  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:33.323  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 11:25:33.323  1598  1598 I Hs20UtilService: Starting #13
08-29 11:25:33.323  1598  1647 I Hs20UtilService: Message received 5011
08-29 11:25:33.323  1016  1124 E WifiConfigStore: Not a HS20
08-29 11:25:33.333  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 11:25:33.333  1016  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 11:25:33.333  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 11:25:33.333  6555  6555 D SecurityLogAgent: StateMachine : Current State = 1
08-29 11:25:33.333  6555  6555 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-29 11:25:33.333  1016  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
08-29 11:25:33.333  1016  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-29 11:25:33.333  7278  7278 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-29 11:25:33.333  7278  7278 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 11:25:33.333  7278  7278 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 11:25:33.333  7278  7278 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 11:25:33.333  7278  7278 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-29 11:25:33.333  7278  7278 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-29 11:25:33.333  7278  7278 I wpa_supplicant: First Scan Start
08-29 11:25:33.333  7278  7278 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-29 11:25:33.343  1016  1124 D WifiNative-wlan0: Setting external_sim to 1
08-29 11:25:33.343  1016  1124 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 11:25:33.343  1016  1124 I WifiNative-HAL: startHal
08-29 11:25:33.343  1016  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9d3f888c
08-29 11:25:33.343  1016  1124 I WifiNative-HAL: Could not start hal
08-29 11:25:33.343  6997  6997 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:33.343  1016  1124 E WifiNative-wlan0: do suspend true
08-29 11:25:33.343  1016  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-29 11:25:33.343  1016  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
08-29 11:25:33.343  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 11:25:33.343  1016  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:33.343  1016  1148 I WifiNative-HAL: startHal
08-29 11:25:33.343  1016  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9e3a29bc
08-29 11:25:33.343  1016  1148 I WifiNative-HAL: Could not start hal
08-29 11:25:33.343  1016  1148 E WifiScanningService: could not start HAL
08-29 11:25:33.343  1016  1016 D RttService: SCAN_AVAILABLE : 3
08-29 11:25:33.343  1016  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:33.343   278  1015 D CommandListener: Setting iface cfg
08-29 11:25:33.343   278  1015 D CommandListener: Trying to bring up p2p0
08-29 11:25:33.353  1016  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 11:25:33.353  1016  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 11:25:33.353  1016  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 11:25:33.353  1016  1124 E WifiNative-wlan0: invaild command id : 215
08-29 11:25:33.353  1016  1123 D WifiP2pService: P2pEnablingState
08-29 11:25:33.353  1016  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
08-29 11:25:33.353  1016  1123 D WifiP2pService: P2p socket connection successful
08-29 11:25:33.353  1016  1123 D WifiP2pService: P2pEnabledState
,08-29 11:25:33.353  1016  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 11:25:33.353  1016  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 11:25:33.353  1016  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-29 11:25:33.353  1016  1124 E WifiNative-wlan0: invaild command id : 215
08-29 11:25:33.353  1016  1126 E ConnectivityService: updateNetworkInfo()
08-29 11:25:33.353  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-29 11:25:33.353  7278  7278 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-29 11:25:33.353  7278  7278 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-29 11:25:33.353  7278  7278 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-29 11:25:33.353  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-29 11:25:33.353  1016  1124 E WifiStateMachine: Failed to set frequency band 0
08-29 11:25:33.353  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 11:25:33.353  1016  1046 D WifiDisplayController: disconnect
08-29 11:25:33.353  1016  1046 D WifiDisplayController: updateConnection
08-29 11:25:33.353  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 11:25:33.353  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 11:25:33.353  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 11:25:33.353  1016  1124 D SecContentProvider2: mCursor = null
08-29 11:25:33.363  1016  1123 D WifiNative-p2p0: p2pGetDeviceAddress
08-29 11:25:33.363  1016  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-29 11:25:33.363  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 11:25:33.363  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-29 11:25:33.363  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 11:25:33.363  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-29 11:25:33.363  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-29 11:25:33.363  1016  1134 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 11:25:33.363  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-29 11:25:33.373  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 11:25:33.373  1016  1123 D WifiP2pService: DeviceAddress: 0a:76:28
08-29 11:25:33.373  1016  1124 D SecContentProvider2: mCursor = null
08-29 11:25:33.373  1016  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-29 11:25:33.373  1016  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-29 11:25:33.373  1016  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-29 11:25:33.373  1016  1046 D WifiDisplayController:  secondary type: null
08-29 11:25:33.373  1016  1046 D WifiDisplayController:  wps: 0
08-29 11:25:33.373  1016  1046 D WifiDisplayController:  grpcapab: 0
08-29 11:25:33.373  1016  1046 D WifiDisplayController:  devcapab: 0
08-29 11:25:33.373  1016  1046 D WifiDisplayController:  status: 3
08-29 11:25:33.373  1016  1046 D WifiDisplayController:  wfdInfo: null
08-29 11:25:33.373  1016  1046 D WifiDisplayController:  groupownerAddress: null
08-29 11:25:33.373  1016  1046 D WifiDisplayController:  GOdeviceName: null
08-29 11:25:33.373  1016  1046 D WifiDisplayController:  interfaceAddress: 
08-29 11:25:33.373  1016  1046 D WifiDisplayController:  SConnectInfo : null
08-29 11:25:33.373  3306  3306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 11:25:33.373  3306  3306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 11:25:33.373  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 11:25:33.373  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 11:25:33.373  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 11:25:33.373  3306  3306 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 11:25:33.373  3306  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-29 11:25:33.383  6948  6948 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-29 11:25:33.383  6948  6948 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-29 11:25:33.383  6948  6948 D FileShare-Client: Outbound.stopDelayTimer - 
08-29 11:25:33.383  6967  6967 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-29 11:25:33.393  1016  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-29 11:25:33.393  1016  1123 D WifiP2pService: InactiveState
08-29 11:25:33.393  1016  1123 D WifiP2pService: InactiveState{ what=143376 }
08-29 11:25:33.393  7278  7278 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-29 11:25:33.393  1016  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
08-29 11:25:33.393  1016  1123 D WifiP2pService: InactiveState{ what=143376 }
08-29 11:25:33.393  1016  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 11:25:33.783   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-29 11:25:34.583  7278  7278 I wpa_supplicant: nl80211: Received scan results (25 BSSes),
,08-29 11:25:34.583  7278  7278 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-29 11:25:34.583  1016  7325 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
08-29 11:25:34.593  7278  7278 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-29 11:25:34.593  7278  7278 I wpa_supplicant: Trying to associate with  'G700'
,08-29 11:25:34.593  7278  7278 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-29 11:25:34.593  7278  7278 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,08-29 11:25:34.613  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 11:25:34.613  1016  1124 D SecContentProvider2: mCursor = null
,08-29 11:25:34.703  7278  7278 E wpa_supplicant: Cmd 35605 not handled
,08-29 11:25:34.703  7278  7278 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 11:25:34.703  7278  7278 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-29 11:25:34.703  7278  7278 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-29 11:25:34.703  7278  7278 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-29 11:25:34.703  7278  7278 I wpa_supplicant: Associated with F4.99.3E
08-29 11:25:34.703  7278  7278 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-29 11:25:34.703  7278  7278 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-29 11:25:34.703  7278  7278 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-29 11:25:34.713  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 11:25:34.713  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 11:25:34.713  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 11:25:34.713  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 11:25:34.713  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 11:25:34.713  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 11:25:34.713  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 11:25:34.713  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 11:25:34.713  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 11:25:34.713  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 11:25:34.713  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-29 11:25:34.723  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-29 11:25:34.723  1016  1129 E Tethering: No numeric data
,08-29 11:25:34.723  7278  7278 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-29 11:25:34.723  7278  7278 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-29 11:25:34.723  1016  1029 I ActivityManager: Killing 7020:com.sec.pcw.device/1000 (adj 15): empty #21
08-29 11:25:34.723  7278  7278 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-29 11:25:34.723  7278  7278 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-29 11:25:34.723  7278  7278 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 11:25:34.723  7278  7278 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-29 11:25:34.723  7278  7278 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-29 11:25:34.723  7278  7278 I wpa_supplicant: Blacklist: Clear (temp) 
08-29 11:25:34.723  7278  7278 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-29 11:25:34.733  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
,08-29 11:25:34.733  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
08-29 11:25:34.733  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-29 11:25:34.733  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 11:25:34.733  1016  1124 D SecContentProvider2: mCursor = null
,08-29 11:25:34.733  1016  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 11:25:34.733  1016  1129 D Tethering: clearTetheredNotification()
,08-29 11:25:34.733  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 11:25:34.733  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:34.733  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 11:25:34.733  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 11:25:34.733  1177  1177 D HotspotTile: updateTetherState():false, false
08-29 11:25:34.733  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 11:25:34.743  1016  1121 V NetworkStats: performPollLocked() took 7ms
08-29 11:25:34.743  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:34.743  1016  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-29 11:25:34.753  1016  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,08-29 11:25:34.753  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:34.753  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:34.753  1016  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-29 11:25:34.753  1016  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-29 11:25:34.753  1016  1126 E ConnectivityService: updateNetworkInfo()
08-29 11:25:34.753  1016  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-29 11:25:34.763  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 11:25:34.763  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 11:25:34.763  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:34.763  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:34.763  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:34.763  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:34.763  1016  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:25:34.763  1016  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 11:25:34.763  1016  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 11:25:34.763  1016  1480 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:34.763  1016  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:34.763  1016  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 11:25:34.773  1598  1598 I Hs20UtilService: Starting #14
,08-29 11:25:34.773  1598  1647 I Hs20UtilService: Message received 5007
,08-29 11:25:34.773  3306  3306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 11:25:34.773  3306  3306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 11:25:34.773  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 11:25:34.773  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 11:25:34.773  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 11:25:34.773  3306  3306 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 11:25:34.773  3306  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 11:25:34.783  1016  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:25:34.793   278  1015 D CommandListener: Setting iface cfg
,08-29 11:25:34.793  1016  1124 E WifiStateMachine: Start Dhcp Watchdog 2
,08-29 11:25:34.793  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 11:25:34.793  1016  1124 D SecContentProvider2: mCursor = null
,08-29 11:25:34.803  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 11:25:34.803  1016  1124 D SecContentProvider2: mCursor = null
,08-29 11:25:34.813  1016  1124 E WifiNative-wlan0: do suspend false
,08-29 11:25:34.813  1016  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-29 11:25:34.823  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 11:25:34.823  1016  1124 D SecContentProvider2: mCursor = null
,08-29 11:25:34.823  1016  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 11:25:34.843  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 11:25:34.853  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 11:25:34.853  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:34.853  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:34.853  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:34.853  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:34.863  1016  1029 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-29 11:25:34.863  1016  1029 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 11:25:34.863  1016  1029 D SecContentProvider2: mCursor = null
,08-29 11:25:34.863  1016  1029 D WifiService: setWifiEnabled: false pid=6746, uid=10171
,08-29 11:25:34.863  1016  1029 D SettingsProvider: name = wifi_on
,08-29 11:25:34.873  1016  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:25:34.883  1016  1124 E WifiNative-wlan0: do suspend true
,08-29 11:25:34.903  1016  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-29 11:25:34.903  1016  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 11:25:34.913   278  1015 D CommandListener: Clearing all IP addresses on wlan0
,08-29 11:25:34.913  1016  1126 E ConnectivityService: updateNetworkInfo()
08-29 11:25:34.913  1016  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:25:34.913  1016  1126 E ConnectivityService: updateNetworkInfo()
08-29 11:25:34.913  1016  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,08-29 11:25:34.913   278  1015 E Netd    : no such netId 503
,08-29 11:25:34.913  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 11:25:34.913  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 11:25:34.913  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:34.913  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:34.913  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:34.913  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:34.913  1016  1126 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-29 11:25:34.913  1016  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-29 11:25:34.913  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 11:25:34.913  1016  1126 V NetworkStats: updateIfacesLocked()
08-29 11:25:34.913  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:34.913  1016  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-29 11:25:34.923  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 11:25:34.923  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 11:25:34.923  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 11:25:34.923  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 11:25:34.923  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:34.923  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:34.923  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:34.923  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:34.923  1016  1126 V NetworkStats: performPollLocked() took 10ms
08-29 11:25:34.923  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:34.933  1016  1123 D WifiP2pService: InactiveState{ what=131204 }
,08-29 11:25:34.933  1016  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 11:25:34.933  1016  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-29 11:25:34.933  1016  7329 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 11:25:34.933  1016  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-29 11:25:34.933  1016  7329 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting,
08-29 11:25:34.933  1016  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-29 11:25:34.933  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 11:25:34.933  1016  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-29 11:25:34.933  1016  1126 D ConnectivityService: nai.networkMonitor.doQuit()
08-29 11:25:34.933  1016  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-29 11:25:34.933  1016  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:34.933  1016  1016 D RttService: SCAN_AVAILABLE : 1
08-29 11:25:34.933  1016  1126 E ConnectivityService: updateNetworkInfo()
08-29 11:25:34.933  1016  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:34.933  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:34.933  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:34.943  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 11:25:34.943  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-29 11:25:34.943  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 11:25:34.943  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 11:25:34.943  1016  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-29 11:25:34.943  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-29 11:25:34.943  1016  1126 E ConnectivityService: updateNetworkInfo()
,08-29 11:25:34.943  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-29 11:25:34.943  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 11:25:34.943  1016  1471 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 11:25:34.943  1016  1471 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 11:25:34.943  1016  1123 D WifiP2pService: P2pDisablingState
08-29 11:25:34.943  1016  1046 D WifiDisplayController: disconnect
08-29 11:25:34.943  1016  1046 D WifiDisplayController: updateConnection
08-29 11:25:34.943  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 11:25:34.943  1016  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
08-29 11:25:34.943  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 11:25:34.943  1016  1123 D WifiP2pService: p2p socket connection lost
08-29 11:25:34.943  1016  1123 D WifiP2pService: P2pDisabledState
,08-29 11:25:34.943  1016  1471 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:34.943  1016  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:34.943  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 11:25:34.943  1016  1124 E WifiNative-wlan0: do suspend true
,08-29 11:25:34.943  1598  1598 I Hs20UtilService: Starting #15
,08-29 11:25:34.953  1598  1647 I Hs20UtilService: Message received 5007
,08-29 11:25:34.953  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false],
08-29 11:25:34.953  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-29 11:25:34.953  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 11:25:34.953  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 11:25:34.953  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-29 11:25:34.953  1016  1134 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 11:25:34.953  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-29 11:25:34.953  3306  3306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 11:25:34.953  3306  3306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 11:25:34.953  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 11:25:34.963  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 11:25:34.963  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 11:25:34.963  3306  3306 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 11:25:34.963  3306  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 11:25:34.973  3306  3306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 11:25:34.973  3306  3306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 11:25:34.973  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 11:25:34.973  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 11:25:34.973  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 11:25:34.973  3306  3306 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 11:25:34.973  3306  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 11:25:34.983  1016  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-29 11:25:34.983  1016  1123 D WifiP2pService: DefaultState{ what=143375 }
,08-29 11:25:34.983  6948  6948 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 11:25:34.983  6948  6948 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-29 11:25:34.983  6948  6948 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 11:25:34.983   278  1015 D CommandListener: Clearing all IP addresses on wlan0
,08-29 11:25:34.983  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 11:25:34.983  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 11:25:34.993  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:34.993  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:34.993  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:34.993  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:34.993  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 11:25:34.993  7278  7278 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-29 11:25:35.003  6967  6967 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 11:25:35.003  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 11:25:35.003  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 11:25:35.003  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:35.003  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:35.003  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:35.003  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:35.003  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 11:25:35.003  1016  1124 D SecContentProvider2: mCursor = null
,08-29 11:25:35.013  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 11:25:35.013  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 11:25:35.013  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:35.013  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:35.013  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:35.013  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:35.013  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:35.013  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-29 11:25:35.013  1177  1765 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 11:25:35.013  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:35.013  1177  1177 D HotspotTile: onReceive : 0, 0
,08-29 11:25:35.013  3306  3306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:25:35.013  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:35.013  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:35.013  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:35.013  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:35.013  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:35.013  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:35.013  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:35.013  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:35.013  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:25:35.013  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:35.013  6746  6746 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:25:35.023  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:25:35.023  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:35.023  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:35.023  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:35.023  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:35.023  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:35.023  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:35.023  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:35.023  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:35.023  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:35.023  6746  6746 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:25:35.023  1016  1472 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 11:25:35.023  1016  1472 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 11:25:35.023  1016  1472 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:35.023  1016  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:35.023  1016  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 11:25:35.023  1598  1598 I Hs20UtilService: Starting #16
,08-29 11:25:35.023  1598  1647 I Hs20UtilService: Message received 5007
,08-29 11:25:35.033  3306  3306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 11:25:35.033  3306  3306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 11:25:35.033  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 11:25:35.033  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-29 11:25:35.033  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 11:25:35.033  3306  3306 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 11:25:35.033  7335  7335 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 11:25:35.043  7335  7335 I dhcpcd  : version 5.5.6 starting
,08-29 11:25:35.043  7335  7335 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-29 11:25:35.043  3306  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 11:25:35.053  1016  1550 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 11:25:35.053  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
,08-29 11:25:35.053  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:35.053  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:35.053  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 11:25:35.063  1598  1598 I Hs20UtilService: Starting #17
08-29 11:25:35.063  1598  1647 I Hs20UtilService: Message received 5011
,08-29 11:25:35.063  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 11:25:35.063  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 11:25:35.063  6555  6555 D SecurityLogAgent: StateMachine : Current State = 1
08-29 11:25:35.063  6555  6555 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 11:25:35.093  7335  7335 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-29 11:25:35.093  7335  7335 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-29 11:25:35.093  7335  7335 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-29 11:25:35.093  7335  7335 I dhcpcd  : bssid match
,08-29 11:25:35.093  7335  7335 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-29 11:25:35.153  7335  7335 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-29 11:25:35.193  7278  7278 I wpa_supplicant: Blacklist: Clear (all) ,
,08-29 11:25:35.243  7335  7335 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,08-29 11:25:35.283  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-29 11:25:35.283  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 11:25:35.283  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 11:25:35.283  7278  7278 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-29 11:25:35.313  7278  7278 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-29 11:25:35.313  7278  7278 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,08-29 11:25:35.313  7278  7278 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-29 11:25:35.313  7278  7278 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-29 11:25:35.313  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 11:25:35.313  7278  7278 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-29 11:25:35.313  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-29 11:25:35.313  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 11:25:35.313  1016  1129 D Tethering: InitialState.processMessage what=4
08-29 11:25:35.313  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 11:25:35.313  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 11:25:35.313  1016  1129 E Tethering: No numeric data
08-29 11:25:35.313  1016  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 11:25:35.313  1016  1129 D Tethering: clearTetheredNotification()
,08-29 11:25:35.323  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-29 11:25:35.323  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 11:25:35.323  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 11:25:35.323  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 11:25:35.323  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-29 11:25:35.323  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 11:25:35.323  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:35.323  1177  1177 D HotspotTile: updateTetherState():false, false
08-29 11:25:35.323  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:35.323  1016  1121 V NetworkStats: performPollLocked() took 4ms
08-29 11:25:35.323  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:35.323  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 11:25:35.323  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 11:25:35.323  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 11:25:35.633  7278  7278 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 11:25:35.673  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 11:25:35.673  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 11:25:35.673  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 11:25:35.673  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 11:25:35.673  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 11:25:35.673  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 11:25:35.683  7278  7278 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-29 11:25:35.743   288   288 E SMD     : DCD OFF,
,08-29 11:25:35.793  1016  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-29 11:25:35.793  1016  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 11:25:35.793  6997  6997 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 11:25:35.793  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 11:25:35.803  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-29 11:25:35.803  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:35.803  2001  2161 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 11:25:35.803  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:35.803  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:35.803  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:35.803  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:25:35.813  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-29 11:25:35.813  3306  3306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:25:35.813  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:35.813  1177  1765 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-29 11:25:35.813  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:35.813  1177  1177 D HotspotTile: onReceive : 1, 0
08-29 11:25:35.813  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:35.813  1016  1329 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 11:25:35.813  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 11:25:35.823  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:35.823  1016  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:35.823  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 11:25:35.823  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 11:25:35.823  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-29 11:25:35.823  6555  6555 D SecurityLogAgent: StateMachine : Current State = 1
08-29 11:25:35.823  6555  6555 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 11:25:35.833  1598  1598 I Hs20UtilService: Starting #18
,08-29 11:25:35.833  1598  1647 I Hs20UtilService: Message received 5011
,08-29 11:25:36.343   278  1009 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-29 11:25:36.353  1016  1043 D Tethering: interfaceRemoved wlan0
,08-29 11:25:36.353  1016  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-29 11:25:36.513  1016  1043 D Tethering: interfaceRemoved p2p0
,08-29 11:25:36.513  1016  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-29 11:25:37.303  1016  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-29 11:25:37.873  6746  6800 D BluetoothAdapter: enable()
,08-29 11:25:37.873  1016  1480 W ActivityManager: Permission Denial: getCurrentUser() from pid=6746, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,08-29 11:25:37.873  1016  1480 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-29 11:25:37.873  1016  1480 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6746, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 11:25:37.873  1016  1480 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 11:25:37.873  1016  1480 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-29 11:25:37.873  1016  1480 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688),
08-29 11:25:37.873  1016  1480 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-29 11:25:37.873  1016  1480 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-29 11:25:37.873  1016  1480 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-29 11:25:37.873  1016  1480 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 11:25:37.883  1016  1480 D SettingsProvider: name = bluetooth_on,
,08-29 11:25:37.883  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-29 11:25:37.883  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 11:25:37.893  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-29 11:25:37.893  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-29 11:25:37.893  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:37.893  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:37.893  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:37.893  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:37.913  7366  7366 E Zygote  : MountEmulatedStorage()
08-29 11:25:37.913  7366  7366 E Zygote  : v2
,08-29 11:25:37.913  7366  7366 I libpersona: KNOX_SDCARD checking this for 1002
08-29 11:25:37.913  7366  7366 I libpersona: KNOX_SDCARD not a persona
,08-29 11:25:37.913  7366  7366 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-29 11:25:37.913  1016  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7366 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-29 11:25:37.913  7366  7366 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 11:25:37.923  7366  7366 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 11:25:37.943  7366  7366 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:37.943  7366  7366 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:37.963  7366  7366 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-29 11:25:37.963  7366  7366 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 11:25:37.993  7366  7366 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-29 11:25:38.033  1016  3365 D SSRM:n  : SIOP:: AP = 370
,08-29 11:25:38.033  7366  7366 D BtSettings.ProfileConfig: Adding GattService
,08-29 11:25:38.033  7366  7366 D BtSettings.ProfileConfig: Adding HeadsetService
,08-29 11:25:38.033  7366  7366 D BtSettings.ProfileConfig: Adding A2dpService
,08-29 11:25:38.033  7366  7366 D BtSettings.ProfileConfig: Adding HidService
,08-29 11:25:38.033  7366  7366 D BtSettings.ProfileConfig: Adding HealthService
,08-29 11:25:38.033  7366  7366 D BtSettings.ProfileConfig: Adding PanService
,08-29 11:25:38.043  7366  7366 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-29 11:25:38.043  7366  7366 D BtSettings.ProfileConfig: Adding SapService
,08-29 11:25:38.043  7366  7366 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-29 11:25:38.043  7366  7366 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-29 11:25:38.043  7366  7366 D BtSettings.ProfileConfig: Adding SapClientService
,08-29 11:25:38.043  7366  7366 D BtSettings.ProfileConfig: Adding HidDevService
,08-29 11:25:38.043  7366  7366 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-29 11:25:38.043  1016  1497 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-29 11:25:38.043  1016  1497 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:38.043  1016  1497 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:38.043  1016  1497 D SettingsProvider: selectionArgs: false
08-29 11:25:38.043  1016  1497 D SettingsProvider: selectionArgs: 1002
08-29 11:25:38.043  1016  1497 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:38.043  1016  1497 D SettingsProvider: ret = -1
,08-29 11:25:38.043  1016  1471 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-29 11:25:38.043  1016  1471 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:38.043  1016  1471 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:38.043  1016  1471 D SettingsProvider: selectionArgs: false
,08-29 11:25:38.043  1016  1471 D SettingsProvider: selectionArgs: 1002
08-29 11:25:38.043  1016  1471 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:38.043  1016  1471 D SettingsProvider: ret = -1
08-29 11:25:38.043  1016  1329 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-29 11:25:38.043  1016  1329 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:38.043  1016  1329 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:38.043  1016  1329 D SettingsProvider: selectionArgs: false
08-29 11:25:38.043  1016  1329 D SettingsProvider: selectionArgs: 1002
08-29 11:25:38.043  1016  1329 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:38.043  1016  1329 D SettingsProvider: ret = -1
08-29 11:25:38.053  1016  1134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-29 11:25:38.053  1016  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:38.053  1016  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:38.053  1016  1134 D SettingsProvider: selectionArgs: false
08-29 11:25:38.053  1016  1134 D SettingsProvider: selectionArgs: 1002
08-29 11:25:38.053  1016  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:38.053  1016  1134 D SettingsProvider: ret = -1
08-29 11:25:38.053  1016  1550 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-29 11:25:38.053  1016  1550 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:38.053  1016  1550 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 11:25:38.053  1016  1550 D SettingsProvider: selectionArgs: false
08-29 11:25:38.053  1016  1550 D SettingsProvider: selectionArgs: 1002
08-29 11:25:38.053  1016  1550 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:38.053  1016  1550 D SettingsProvider: ret = -1
,08-29 11:25:38.053  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-29 11:25:38.053  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:38.053  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:38.053  1016  1028 D SettingsProvider: selectionArgs: false
08-29 11:25:38.053  1016  1028 D SettingsProvider: selectionArgs: 1002
08-29 11:25:38.053  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:38.053  1016  1028 D SettingsProvider: ret = -1
08-29 11:25:38.053  1016  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-29 11:25:38.053  1016  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:38.053  1016  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:38.053  1016  1029 D SettingsProvider: selectionArgs: false
08-29 11:25:38.053  1016  1029 D SettingsProvider: selectionArgs: 1002
08-29 11:25:38.053  1016  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 11:25:38.053  1016  1029 D SettingsProvider: ret = -1
08-29 11:25:38.053  1016  1479 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService,
08-29 11:25:38.053  1016  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:38.053  1016  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:38.053  1016  1479 D SettingsProvider: selectionArgs: false
08-29 11:25:38.053  1016  1479 D SettingsProvider: selectionArgs: 1002
08-29 11:25:38.053  1016  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:38.053  1016  1479 D SettingsProvider: ret = -1
08-29 11:25:38.053  1016  1553 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-29 11:25:38.053  1016  1553 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:38.053  1016  1553 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:38.053  1016  1553 D SettingsProvider: selectionArgs: false
08-29 11:25:38.053  1016  1553 D SettingsProvider: selectionArgs: 1002
08-29 11:25:38.053  1016  1553 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:38.053  1016  1553 D SettingsProvider: ret = -1
08-29 11:25:38.053  1016  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-29 11:25:38.053  1016  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:38.053  1016  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:38.053  1016  1480 D SettingsProvider: selectionArgs: false
08-29 11:25:38.053  1016  1480 D SettingsProvider: selectionArgs: 1002
08-29 11:25:38.053  1016  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:38.053  1016  1480 D SettingsProvider: ret = -1
08-29 11:25:38.053  1016  1224 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-29 11:25:38.053  1016  1224 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:38.053  1016  1224 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:38.053  1016  1224 D SettingsProvider: selectionArgs: false
08-29 11:25:38.053  1016  1224 D SettingsProvider: selectionArgs: 1002
08-29 11:25:38.053  1016  1224 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:38.053  1016  1224 D SettingsProvider: ret = -1
08-29 11:25:38.053  1016  1472 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-29 11:25:38.053  1016  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:38.053  1016  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:38.053  1016  1472 D SettingsProvider: selectionArgs: false
08-29 11:25:38.053  1016  1472 D SettingsProvider: selectionArgs: 1002
08-29 11:25:38.053  1016  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:38.053  1016  1472 D SettingsProvider: ret = -1
,08-29 11:25:38.073  7366  7366 D BluetoothAdapterState: make
,08-29 11:25:38.073  7366  7366 I bluedroid: init
,08-29 11:25:38.073  7366  7381 I BluetoothAdapterState: Entering OffState
,08-29 11:25:38.073  7366  7366 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 11:25:38.083  7366  7366 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 11:25:38.083  7366  7366 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 11:25:38.083  7366  7366 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 11:25:38.083  7366  7366 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-29 11:25:38.083  7366  7366 I bluedroid: get_profile_interface socket
08-29 11:25:38.083  7366  7366 I bluedroid: get_profile_interface map_client
,08-29 11:25:38.083  7366  7384 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 11:25:38.083  7366  7366 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-29 11:25:38.083  7366  7384 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-29 11:25:38.083  7366  7384 E BluetoothServiceJni: populateRssiValuesNative
08-29 11:25:38.083  7366  7384 I bluedroid: getModelRssiValues
08-29 11:25:38.083  7366  7384 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-29 11:25:38.083  7366  7384 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 11:25:38.093  7366  7384 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-29 11:25:38.093  1016  1016 D SettingsProvider: name = bluetooth_name
,08-29 11:25:38.093  7366  7366 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 11:25:38.093  1016  1480 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 11:25:38.093  1016  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 11:25:38.093  1016  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:38.093  1016  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:38.093  1016  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:38.093  7366  7380 I bluedroid: config_hci_snoop_log
,08-29 11:25:38.093  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-29 11:25:38.103  1016  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-29 11:25:38.103  1016  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-29 11:25:38.103  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-29 11:25:38.103  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 11:25:38.103  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 11:25:38.103  7366  7366 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
08-29 11:25:38.103  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 11:25:38.113  1016  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-29 11:25:38.113  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-29 11:25:38.113  7366  7381 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-29 11:25:38.113  7366  7381 D BluetoothAdapterProperties: Setting state to 11
08-29 11:25:38.113  7366  7381 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-29 11:25:38.113  7366  7381 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 11:25:38.113  7366  7381 D BluetoothAdapterService: updateAdapterState state is 11
,08-29 11:25:38.113  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:38.113  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
08-29 11:25:38.113  7366  7381 D BluetoothAdapterService: Autoconnection is available 
08-29 11:25:38.113  7366  7381 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-29 11:25:38.123  7366  7381 D BluetoothSecureManager: getInstant: null
08-29 11:25:38.123  7366  7381 D BluetoothSecureManager: calling getMethod for getService
08-29 11:25:38.123  7366  7381 D BluetoothSecureManager: calling getService
08-29 11:25:38.123  7366  7381 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@175385b7
,08-29 11:25:38.123  1016  1550 D BluetoothSecureManagerService: isSecureModeEnabled
08-29 11:25:38.123  1016  1550 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-29 11:25:38.123  7366  7381 D BtConfig.SecureMode: isSecureModeOn:false
08-29 11:25:38.123  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-29 11:25:38.123  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 11:25:38.123  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:38.123  1177  1177 D BluetoothTile:  getBluetoothState : 11
,08-29 11:25:38.123  7366  7381 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-29 11:25:38.123  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-29 11:25:38.123  7366  7381 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-29 11:25:38.123  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 11:25:38.123  7366  7381 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-29 11:25:38.123  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 11:25:38.133  7366  7381 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,08-29 11:25:38.133  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 11:25:38.133  7366  7381 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-29 11:25:38.133  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-29 11:25:38.133  7366  7381 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-29 11:25:38.133  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 11:25:38.133  1872  1872 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-29 11:25:38.133  7366  7381 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-29 11:25:38.133  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 11:25:38.143  7366  7381 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-29 11:25:38.143  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 11:25:38.143  7366  7381 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 11:25:38.143  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-29 11:25:38.143  7366  7381 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-29 11:25:38.143  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 11:25:38.143  1016  1553 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 11:25:38.143  7366  7381 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-29 11:25:38.143  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 11:25:38.143  1177  1765 D BluetoothTile:  handleUpdatestate:false name:null
08-29 11:25:38.143  1177  1765 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-29 11:25:38.143  7366  7381 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-29 11:25:38.143  1016  1134 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-29 11:25:38.143  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-29 11:25:38.143  3306  3306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:38.143  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:38.143  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:38.153  7366  7381 D BluetoothBondStateMachine: make
,08-29 11:25:38.153  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-29 11:25:38.153  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-29 11:25:38.153  7366  7381 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-29 11:25:38.153  7366  7386 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 11:25:38.293  1016  1497 I art     : Explicit concurrent mark sweep GC freed 81967(4MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 24MB/36MB, paused 2.362ms total 158.741ms
,08-29 11:25:38.293  1016  1553 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:38.293  1016  1553 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-29 11:25:38.293  1016  1553 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:38.293  1016  1553 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:38.293  1016  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:38.293  1016  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 11:25:38.293  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-29 11:25:38.293  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 11:25:38.293  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 11:25:38.293  7366  7381 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-29 11:25:38.293  7366  7366 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 11:25:38.293  3306  3306 D BluetoothNotiBroadcastReceiver: onReceive
08-29 11:25:38.293  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:38.293  1016  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:38.293  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 11:25:38.293  7366  7366 D BtGatt.GattService: Received start request. Starting profile...
08-29 11:25:38.293  7366  7366 D BtGatt.GattService: start()
08-29 11:25:38.293  7366  7366 D BtGatt.GattService: start()
08-29 11:25:38.293  7366  7366 I bluedroid: get_profile_interface gatt
,08-29 11:25:38.293  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:38.303  7366  7366 D BtGatt.AdvertiseManager: advertise manager created
,08-29 11:25:38.303  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:38.303  1016  1550 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:38.303  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 11:25:38.303  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-29 11:25:38.303  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:38.303  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:38.303  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:38.313  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 11:25:38.313  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 11:25:38.313  7366  7381 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 11:25:38.313  1016  1134 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-29 11:25:38.313  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:38.313  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:38.313  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:38.313  1016  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:38.323  7390  7390 E Zygote  : MountEmulatedStorage(),
08-29 11:25:38.323  7390  7390 E Zygote  : v2
08-29 11:25:38.323  7390  7390 I libpersona: KNOX_SDCARD checking this for 10055
08-29 11:25:38.323  7390  7390 I libpersona: KNOX_SDCARD not a persona
,08-29 11:25:38.333  7390  7390 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:38.333  1016  1134 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7390 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
,08-29 11:25:38.333  7390  7390 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 11:25:38.333  1016  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:38.333  1016  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:38.333  1016  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:38.333  1016  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-29 11:25:38.333  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:38.333  7390  7390 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 11:25:38.333  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-29 11:25:38.343  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 11:25:38.343  7366  7381 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-29 11:25:38.343  7366  7366 D BtGatt.GattService: mStartError = false
08-29 11:25:38.343  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:38.343  1016  1551 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:38.343  1016  1551 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 11:25:38.343  1016  1551 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:38.343  1016  1551 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:38.343  1016  1551 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:38.353  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-29 11:25:38.353  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 11:25:38.353  7366  7381 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-29 11:25:38.353  1016  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:38.353  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-29 11:25:38.353  7366  7366 D HeadsetService: Received start request. Starting profile...
08-29 11:25:38.353  7366  7366 D HeadsetService: start()
,08-29 11:25:38.353  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:38.353  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:38.353  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:38.353  7366  7366 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 11:25:38.353  7366  7366 D HeadsetStateMachine: make
,08-29 11:25:38.353  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-29 11:25:38.353  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 11:25:38.353  7366  7381 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 11:25:38.353  1016  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:38.353  1016  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-29 11:25:38.353  1016  1480 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:38.353  1016  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:38.353  1016  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:38.363  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 11:25:38.363  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 11:25:38.363  7366  7381 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 11:25:38.363  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:38.363  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-29 11:25:38.363  7366  7366 E HeadsetStateMachine: # of Max HF connection is 2
,08-29 11:25:38.363  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:38.363  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:38.363  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:38.373  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-29 11:25:38.373  1016  1329 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-29 11:25:38.373  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-29 11:25:38.373  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 11:25:38.373  7366  7381 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 11:25:38.373  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:38.373  1016  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:38.373  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 11:25:38.373  1016  1472 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:38.373  1016  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 11:25:38.373  1016  1472 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:38.373  1016  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:38.373  1016  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:38.373  1016  1479 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-29 11:25:38.373  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-29 11:25:38.373  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-29 11:25:38.373  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 11:25:38.373  7366  7381 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 11:25:38.373  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 11:25:38.373  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 11:25:38.373  7366  7381 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 11:25:38.373  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 11:25:38.373  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 11:25:38.373  7366  7381 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 11:25:38.373  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-29 11:25:38.373  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 11:25:38.373  7366  7381 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 11:25:38.373  7366  7381 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 11:25:38.373  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:38.373  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:38.373  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-29 11:25:38.373  7366  7366 I bluedroid: get_profile_interface handsfree
,08-29 11:25:38.383  7390  7390 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 11:25:38.383  7390  7390 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:38.393  7366  7366 I DualScoManager: Instantiating Dual Sco Manager
08-29 11:25:38.393  7366  7366 I DualScoManager: Set HeadsetServiceHelper
,08-29 11:25:38.403  7366  7366 D BluetoothAtMessage: createCMTIContentObservers
,08-29 11:25:38.403  1016  1329 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-29 11:25:38.403  1016  1329 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:38.403  1016  1329 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 11:25:38.403  1016  1329 D SettingsProvider: selectionArgs: false
08-29 11:25:38.403  1016  1329 D SettingsProvider: selectionArgs: 1002
08-29 11:25:38.403  1016  1329 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:38.403  1016  1329 D SettingsProvider: ret = -1
08-29 11:25:38.403  7366  7400 D HeadsetStateMachine: Enter Disconnected: -2
,08-29 11:25:38.403  7366  7366 D HeadsetService: mStartError = false
08-29 11:25:38.403  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:38.403  7366  7400 D HeadsetStateMachine: Clear mHeadsetBrsf
08-29 11:25:38.403  7366  7366 D A2dpService: Received start request. Starting profile...
08-29 11:25:38.403  7366  7366 D A2dpService: start()
,08-29 11:25:38.403  7366  7400 D HeadsetStateMachine: map size, before remove : 0
08-29 11:25:38.403  7366  7400 D HeadsetStateMachine: map size, after remove: 0
,08-29 11:25:38.413  7366  7366 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 11:25:38.413  7366  7366 I bluedroid: get_profile_interface avrcp
,08-29 11:25:38.413  7366  7366 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 11:25:38.413  7366  7366 D Avrcp   : Initialize Media Controller
,08-29 11:25:38.413  7366  7366 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-29 11:25:38.423  7366  7366 E Avrcp   : getActiveSessions,
08-29 11:25:38.423  7366  7366 D Avrcp   : pick active media Controller
08-29 11:25:38.423  7366  7366 D Avrcp   : Get the active Media Controller 
,08-29 11:25:38.423  7390  7390 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-29 11:25:38.433  7366  7366 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-29 11:25:38.433  7366  7410 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-29 11:25:38.443  7366  7366 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 11:25:38.443  7366  7366 D A2dpStateMachine: make
,08-29 11:25:38.443  7366  7366 I bluedroid: get_profile_interface a2dp
08-29 11:25:38.443  7366  7412 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 11:25:38.443  7366  7366 E bt-btif : warning : media task started media_task_refcnt 1 
,08-29 11:25:38.443  7366  7366 D A2dpService: mStartError = false
08-29 11:25:38.443  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
08-29 11:25:38.443  7366  7366 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-29 11:25:38.443  7366  7366 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 11:25:38.453  7366  7411 D A2dpStateMachine: Enter Disconnected: -2
08-29 11:25:38.453  7366  7410 D BluetoothMediaBrowser: no now playing list
08-29 11:25:38.453  7366  7410 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-29 11:25:38.453  7366  7366 D HidService: Received start request. Starting profile...
08-29 11:25:38.453  7366  7366 D HidService: start()
08-29 11:25:38.453  7366  7366 I bluedroid: get_profile_interface hidhost
08-29 11:25:38.453  7366  7366 D HidService: setHidService(): set to: null
08-29 11:25:38.453  7366  7366 D HidService: mStartError = false
08-29 11:25:38.453  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:38.453  7366  7366 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 11:25:38.453  7366  7366 D HealthService: Received start request. Starting profile...,
08-29 11:25:38.453  7366  7366 D HealthService: start()
,08-29 11:25:38.453  7366  7366 I bluedroid: get_profile_interface health,
08-29 11:25:38.453  7366  7366 D HealthService: mStartError = false
08-29 11:25:38.453  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
08-29 11:25:38.453  7366  7366 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 11:25:38.453  7366  7366 D PanService: Received start request. Starting profile...
08-29 11:25:38.453  7366  7366 D PanService: start()
08-29 11:25:38.453  7366  7366 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 11:25:38.453  7366  7366 I bluedroid: get_profile_interface pan
08-29 11:25:38.453  7366  7366 D PanService: mStartError = false
08-29 11:25:38.453  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
08-29 11:25:38.453  7390  7390 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-29 11:25:38.453  7390  7390 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-29 11:25:38.453  7390  7390 D UserAnalysis: Create SecureDbHelper
,08-29 11:25:38.463  7366  7366 D BluetoothMapService: Received start request. Starting profile...
08-29 11:25:38.463  7366  7366 D BluetoothMapService: start()
,08-29 11:25:38.463  7366  7366 D BluetoothMapService: mStartError = false
08-29 11:25:38.463  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
08-29 11:25:38.463  7366  7366 D HeadsetStateMachine: Try to query the phonestate on bind
,08-29 11:25:38.463  1432  1440 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 11:25:38.463  1432  1432 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-29 11:25:38.463  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-29 11:25:38.463  1432  1440 I Telecom : BluetoothPhoneService: Result of Message : true
,08-29 11:25:38.463  7390  7390 D IntelligenceServiceApplication: onCreate()
08-29 11:25:38.463  7366  7366 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-29 11:25:38.473  7366  7366 D SapService: Received start request. Starting profile...
08-29 11:25:38.473  7366  7366 D SapService: start()
08-29 11:25:38.473  7366  7366 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-29 11:25:38.473  7366  7366 I bluedroid: get_profile_interface sap
08-29 11:25:38.473  7366  7366 D SapService: mStartError = false
08-29 11:25:38.473  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
08-29 11:25:38.473  7366  7366 D HeadsetStateMachine: Proxy object connected
08-29 11:25:38.473  7366  7366 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-29 11:25:38.473  7366  7366 D HeadsetPhoneState: sendDeviceDataStateChanged
08-29 11:25:38.473  7366  7400 D HeadsetStateMachine: Disconnected process message: 11
08-29 11:25:38.473  7366  7366 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-29 11:25:38.473  7366  7366 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-29 11:25:38.473  7366  7366 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 11:25:38.473  7366  7366 D BluetoothA2dp: Proxy object connected
08-29 11:25:38.473  7366  7366 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-29 11:25:38.473  7366  7366 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-29 11:25:38.473  7366  7400 D HeadsetStateMachine: Disconnected process message: 18
08-29 11:25:38.473  7366  7400 D HeadsetStateMachine: Disconnected process message: 10
,08-29 11:25:38.473  7366  7400 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 11:25:38.473  7366  7400 D HeadsetStateMachine: Disconnected process message: 11
,08-29 11:25:38.473  1016  1551 I ActivityManager: Killing 7037:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-29 11:25:38.473  7366  7366 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-29 11:25:38.473  7366  7366 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-29 11:25:38.473  7366  7366 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-29 11:25:38.483  7390  7390 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-29 11:25:38.483  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-29 11:25:38.483  7390  7390 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-29 11:25:38.493  7390  7390 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-29 11:25:38.503  7366  7366 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true,
08-29 11:25:38.503  7366  7366 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
08-29 11:25:38.503  1016  1551 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-29 11:25:38.503  1016  1551 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:38.503  1016  1551 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:38.503  1016  1551 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:38.503  1016  1551 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:38.513  7417  7417 E Zygote  : MountEmulatedStorage()
08-29 11:25:38.513  7417  7417 E Zygote  : v2
08-29 11:25:38.513  7417  7417 I libpersona: KNOX_SDCARD checking this for 10105
08-29 11:25:38.513  7417  7417 I libpersona: KNOX_SDCARD not a persona
,08-29 11:25:38.513  1016  1551 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7417 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-29 11:25:38.513  7417  7417 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:38.523  7417  7417 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 11:25:38.523  7417  7417 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-29 11:25:38.523  7366  7381 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-29 11:25:38.523  7366  7381 I bluedroid: enable
,08-29 11:25:38.533  7366  7426 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-29 11:25:38.533  7366  7381 I bt_hci_bdroid: init
,08-29 11:25:38.533  7366  7381 I bt_vendor: bt-vendor : init
08-29 11:25:38.533  7366  7381 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 11:25:38.533  7366  7381 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 11:25:38.533  7366  7381 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-29 11:25:38.533  7366  7381 D bt_userial_mct: userial_init
,08-29 11:25:38.533  7366  7381 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 11:25:38.533  7366  7381 I bt_vendor: Starting hciattach daemon
08-29 11:25:38.533  7366  7381 I bt_vendor: try to set false
,08-29 11:25:38.533  7366  7381 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 11:25:38.533  7366  7381 I bt_vendor: Starting hciattach daemon
08-29 11:25:38.533  7366  7381 I bt_vendor: try to set true
,08-29 11:25:38.543  7417  7417 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 11:25:38.543  7417  7417 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:38.563  7437  7437 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 11:25:38.613  7443  7443 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-29 11:25:38.623  7446  7446 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 11:25:38.643  7448  7448 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-29 11:25:38.653  7449  7449 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-29 11:25:38.653  7453  7453 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-29 11:25:38.663  7454  7454 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-29 11:25:38.683   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 11:25:38.683   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 11:25:38.683  7417  7451 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 11:25:38.683   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 11:25:38.683   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 11:25:38.693  7417  7451 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 11:25:38.743   288   288 E SMD     : DCD OFF,
,08-29 11:25:38.833  7417  7417 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 11:25:38.833  7417  7417 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 11:25:38.833  7417  7417 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 11:25:38.833  7417  7417 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 11:25:38.833  7417  7417 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.q.k.d(PG:583)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 11:25:38.833  7417  7417 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 11:25:38.833  7417  7417 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 11:25:38.833  7417  7417 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 11:25:38.833  7417  7417 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 11:25:38.833  1016  1479 I ActivityManager: Killing 7052:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
08-29 11:25:38.843  2001  2001 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-29 11:25:38.843  2001  2001 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 11:25:38.883  7417  7450 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-29 11:25:38.913  1016  1471 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:38.913  1016  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:38.913  1016  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:38.913  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-29 11:25:38.973  7468  7468 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-29 11:25:38.983  7469  7469 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-29 11:25:39.043  7366  7381 I bt_vendor: bluetooth satus is on
,08-29 11:25:39.043  7366  7428 D bt_userial_mct: userial_open(port:0)
08-29 11:25:39.043  7366  7428 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-29 11:25:39.043  7366  7428 I bt_vendor: Done intiailizing UART,
08-29 11:25:39.043  7366  7428 I bt_vendor: Done intiailizing UART
08-29 11:25:39.043  7366  7428 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-29 11:25:39.043  7366  7428 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-29 11:25:39.043  7366  7471 D bt_userial_mct: Entering userial_read_thread()
,08-29 11:25:39.053  7366  7426 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 11:25:39.063  7366  7426 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 11:25:39.063  7366  7426 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 11:25:39.063  7366  7426 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 11:25:39.063  7366  7426 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 11:25:39.063  7366  7426 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 11:25:39.063  7366  7426 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 11:25:39.063  7366  7426 I         : BTE_InitTraceLevels -- TRC_BTM
,08-29 11:25:39.063  7366  7426 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 11:25:39.063  7366  7426 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 11:25:39.063  7366  7426 I         : BTE_InitTraceLevels -- TRC_SAP
,08-29 11:25:39.063  7366  7426 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 11:25:39.063  7366  7426 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 11:25:39.063  7366  7426 I         : BTE_InitTraceLevels -- TRC_SMP
,08-29 11:25:39.063  7366  7426 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 11:25:39.063  7366  7426 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 11:25:39.063  7366  7426 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-29 11:25:39.153  7366  7426 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-29 11:25:39.163  7366  7426 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4307ed1 
,08-29 11:25:39.163  7366  7426 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4307ed1 
,08-29 11:25:39.173  7366  7384 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-29 11:25:39.183  7366  7384 E bt-btif : Calling BTA_HhEnable
,08-29 11:25:39.183  7366  7384 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-29 11:25:39.183  7366  7384 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-29 11:25:39.183  7366  7384 E BluetoothServiceJni: populateRssiValuesNative
08-29 11:25:39.183  7366  7384 I bluedroid: getModelRssiValues
,08-29 11:25:39.183  7366  7384 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-29 11:25:39.183  7366  7384 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 11:25:39.183  1016  1016 D SettingsProvider: name = bluetooth_name
,08-29 11:25:39.183  7366  7384 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-29 11:25:39.193  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-29 11:25:39.193  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:39.193  7366  7384 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 11:25:39.193  7366  7384 D BluetoothAdapterProperties: Scan Mode:20
08-29 11:25:39.193  7366  7384 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 11:25:39.193  7366  7384 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-29 11:25:39.193  7366  7384 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-29 11:25:39.193  7366  7384 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-29 11:25:39.193  7366  7384 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-29 11:25:39.193  7366  7384 E bt-btif : btif_sock_init: !vhci_init
,08-29 11:25:39.203  7366  7384 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-29 11:25:39.203  7366  7384 D IOP_DB_BT: db_open: db_open : handle 2966163472l, read 13894 bytes onto local cache
,08-29 11:25:39.203  7366  7384 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-29 11:25:39.203  7366  7384 D IOP_DB_BT: db_query: result 1
,08-29 11:25:39.203  7366  7471 E bt_mct  : hci lib postload completed
,08-29 11:25:39.203  7366  7384 I         : iop_db_open: iop_db_open status 0
,08-29 11:25:39.203  7366  7384 D bte_conf: Device ID record 1 : primary
08-29 11:25:39.203  7366  7384 D bte_conf:   vendorId            = 0075
08-29 11:25:39.203  7366  7384 D bte_conf:   vendorIdSource      = 0001
08-29 11:25:39.203  7366  7384 D bte_conf:   product             = 0100
08-29 11:25:39.203  7366  7384 D bte_conf:   version             = 0200
08-29 11:25:39.203  7366  7384 D bte_conf:   clientExecutableURL = 
08-29 11:25:39.203  7366  7384 D bte_conf:   serviceDescription  = 
08-29 11:25:39.203  7366  7384 D bte_conf:   documentationURL    = 
08-29 11:25:39.203  7366  7384 D bte_conf: bte_load_did_conf no section named DID2.
,08-29 11:25:39.203  7366  7384 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 11:25:39.203  7366  7381 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-29 11:25:39.203  7366  7381 D BluetoothAdapterProperties: ScanMode =  20
08-29 11:25:39.203  7366  7381 D BluetoothAdapterProperties: State =  11
,08-29 11:25:39.213  1016  1329 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 11:25:39.213  7366  7381 D BluetoothAdapterProperties: Setting state to 12
08-29 11:25:39.213  7366  7381 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 11:25:39.213  7366  7384 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 11:25:39.213  7366  7384 D BluetoothAdapterProperties: Scan Mode:21
,08-29 11:25:39.213  7366  7384 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 11:25:39.213  1016  1551 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-29 11:25:39.213  1016  1551 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:39.213  1016  1551 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:39.213  1016  1551 D SettingsProvider: selectionArgs: false
08-29 11:25:39.213  1016  1551 D SettingsProvider: selectionArgs: 1002
08-29 11:25:39.213  1016  1551 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:39.213  1016  1551 D SettingsProvider: ret = -1
,08-29 11:25:39.213  7366  7381 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 11:25:39.213  7366  7381 D BluetoothAdapterService: updateAdapterState state is 12
,08-29 11:25:39.213  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:39.223  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 11:25:39.223  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:39.223  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:39.223  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:39.223  7366  7381 D BluetoothAdapterService: Autoconnection is available 
,08-29 11:25:39.223  7366  7381 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,08-29 11:25:39.223  7366  7381 D BluetoothAdapterService: starting service from this receiver
,08-29 11:25:39.223  1016  1329 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:39.223  1016  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-29 11:25:39.223  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 11:25:39.233  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:39.233  1016  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:39.233  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 11:25:39.233  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 11:25:39.233  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-29 11:25:39.233  1016  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 11:25:39.233  7366  7381 I BluetoothAdapterState: Entering On State from state = 11
,08-29 11:25:39.233  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:39.233  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:39.233  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:39.233  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:39.233  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:39.233  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:39.233  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:39.233  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:25:39.243  3306  3322 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 11:25:39.243  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-29 11:25:39.243  6746  6746 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:25:39.243  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 11:25:39.253  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:39.253  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:39.253  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:39.253  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:39.253  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:39.253  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:39.253  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:39.253  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:39.253  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:39.253  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:39.253  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:25:39.253  1432  1447 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 11:25:39.263  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 11:25:39.263  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 11:25:39.263  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:39.263  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:39.263  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-29 11:25:39.263  7366  7366 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-29 11:25:39.263  1432  1447 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 11:25:39.263  6746  6746 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:25:39.263  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 11:25:39.263  1016  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 11:25:39.263  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 11:25:39.263  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 11:25:39.263  1016  1016 D BluetoothA2dp: Proxy object connected
,08-29 11:25:39.263  1177  1842 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 11:25:39.263  1177  1842 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:39.263  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 11:25:39.263  1016  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:39.273  1432  3263 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 11:25:39.273  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 11:25:39.273  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 11:25:39.273  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:39.273  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:39.273  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:39.273  1432  3263 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 11:25:39.273  7417  7434 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 11:25:39.273  7417  7434 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:39.273  1432  3264 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 11:25:39.283  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 11:25:39.283  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 11:25:39.283  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:39.283  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:39.283  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:39.283  7366  7366 I BluetoothPbapService: Handler(): got msg=1
,08-29 11:25:39.283  1432  3264 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 11:25:39.283  3306  3306 D BluetoothPbap: Proxy object connected
08-29 11:25:39.283  3306  3306 D PbapServerProfile: Bluetooth service connected
,08-29 11:25:39.283  1016  1029 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 11:25:39.283  7366  7374 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 11:25:39.283  7366  7374 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:39.283  7366  7380 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 11:25:39.283  3306  3319 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 11:25:39.293  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-29 11:25:39.293  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 11:25:39.293  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:39.293  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:39.293  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:39.293  3306  3306 D BluetoothInputDevice: Proxy object connected
,08-29 11:25:39.293  2001  2157 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 11:25:39.293  2001  2157 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:39.293  7366  7475 V BluetoothPbapService: PBAP Service initSocket try: 0
08-29 11:25:39.293  3306  3306 D HidProfile: Bluetooth service connected
,08-29 11:25:39.293  3306  6947 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 11:25:39.293  3306  6947 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:39.303  3306  3319 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 11:25:39.303  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 11:25:39.303  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 11:25:39.303  7366  7475 D BluetoothSocket: bindListen(): myUserId = 0
08-29 11:25:39.303  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:39.303  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:39.303  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-29 11:25:39.303  3306  3319 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 11:25:39.303  7366  7475 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:25:39.303  3306  6947 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 11:25:39.303  3306  3306 D HeadsetProfile: Bluetooth service connected
,08-29 11:25:39.303  7366  7475 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-29 11:25:39.303  7366  7475 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 11:25:39.303  7366  7475 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 11:25:39.303  7366  7475 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2dc88f08
,08-29 11:25:39.303  7366  7475 D BluetoothSocket: channel: 19
08-29 11:25:39.303  7366  7475 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-29 11:25:39.303  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-29 11:25:39.303  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 11:25:39.303  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:39.303  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:39.303  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:39.303  3306  3322 D BluetoothPan: Binding service...
,08-29 11:25:39.313  3306  3306 D BluetoothMap: Proxy object connected
,08-29 11:25:39.313  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 11:25:39.313  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 11:25:39.313  3306  3306 D MapProfile: Bluetooth service connected
08-29 11:25:39.313  3306  3306 D BluetoothMap: getConnectedDevices()
08-29 11:25:39.313  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:39.313  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:39.313  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:39.313  3306  6947 D Bluetoothsap: onBluetoothStateChange: up=true
,08-29 11:25:39.313  3306  6947 D Bluetoothsap: Binding service...
,08-29 11:25:39.313  3306  3306 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 11:25:39.313  3306  3306 D PanProfile: Bluetooth service connected
,08-29 11:25:39.323  3306  6947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-29 11:25:39.323  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-29 11:25:39.323  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 11:25:39.323  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:39.323  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:39.323  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:39.323  3306  3306 D Bluetoothsap: BluetoothSAP Proxy object connected
08-29 11:25:39.323  3306  6947 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-29 11:25:39.323  3306  3306 D SapProfile: Bluetooth service connected
08-29 11:25:39.323  3306  3306 D Bluetoothsap: getConnectedDevices()
,08-29 11:25:39.323  1456  1991 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 11:25:39.333  1016  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 11:25:39.333  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 11:25:39.333  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:39.333  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:39.333  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:39.333  1456  1991 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 11:25:39.333  1016  1045 D BluetoothPan: Binding service...
,08-29 11:25:39.333  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-29 11:25:39.333  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 11:25:39.333  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 11:25:39.333  6746  6791 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 11:25:39.333  6746  6791 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:39.333  3306  3319 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 11:25:39.333  3306  3319 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 11:25:39.343  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-29 11:25:39.343  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 11:25:39.343  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:39.343  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:39.343  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:39.343  3306  3306 D BluetoothA2dp: Proxy object connected
,08-29 11:25:39.343  3306  3306 D A2dpProfile: Bluetooth service connected
08-29 11:25:39.343  1432  1447 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 11:25:39.343  1432  1447 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 11:25:39.343  1456  1473 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 11:25:39.343  1456  1473 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:39.343  1441  1462 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 11:25:39.343  1441  1462 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:39.343  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-29 11:25:39.343  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 11:25:39.353  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:39.353  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
08-29 11:25:39.353  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 11:25:39.353  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-29 11:25:39.363  1432  1432 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3202c184, true
,08-29 11:25:39.363  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:39.363  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 11:25:39.363  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-29 11:25:39.363  1872  1872 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 11:25:39.363  1177  1765 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 11:25:39.363  1177  1765 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 11:25:39.363  1432  1432 D BluetoothHeadset: registerMessageListener
,08-29 11:25:39.363  1177  1765 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 11:25:39.373  3306  3306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:39.373  1016  1329 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 11:25:39.373  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:39.373  1016  1551 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-29 11:25:39.373  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 11:25:39.373  1016  1224 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 11:25:39.373  1016  1224 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 11:25:39.373  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:39.383  7366  7380 D HeadsetService: registerMessageListener
,08-29 11:25:39.383  3306  3306 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-29 11:25:39.383  3306  3306 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-29 11:25:39.383  1016  1224 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:39.383  1016  1224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:39.383  1016  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:39.383  7366  7380 D HeadsetService: registerMessageListener
,08-29 11:25:39.383  7366  7400 D HeadsetStateMachine: Disconnected process message: 70
,08-29 11:25:39.383  7366  7400 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@22986a1
08-29 11:25:39.383  1432  1432 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-29 11:25:39.383  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 11:25:39.383  3306  3306 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-29 11:25:39.383  3306  3306 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-29 11:25:39.383  1432  1432 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-29 11:25:39.383  1432  1432 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-29 11:25:39.383  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-29 11:25:39.393  7366  7477 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-29 11:25:39.393  7366  7400 D HeadsetStateMachine: Disconnected process message: 9
08-29 11:25:39.393  7366  7400 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-29 11:25:39.403   283   694 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-29 11:25:39.403   283   694 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-29 11:25:39.403   283   694 V voice   : voice_set_parameters: exit with code(-2)
08-29 11:25:39.403   283   694 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-29 11:25:39.403   283   694 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-29 11:25:39.403   283   694 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-29 11:25:39.403   283   694 V audio_hw_primary: adev_set_parameters: exit
,08-29 11:25:39.403  7366  7400 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-29 11:25:39.403  3306  3306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 11:25:39.403  1016  1134 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 11:25:39.403  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-29 11:25:39.403  7366  7477 D BluetoothSocket: bindListen(): myUserId = 0
08-29 11:25:39.403  7366  7477 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:25:39.403  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:39.403  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:39.403  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 11:25:39.413  7366  7477 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-29 11:25:39.413  7366  7477 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 11:25:39.413  7366  7477 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 11:25:39.413  7366  7477 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@143990c6
,08-29 11:25:39.413  7366  7477 D BluetoothSocket: channel: 5
,08-29 11:25:39.413  3306  3306 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:25:39.413  3306  3306 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 11:25:39.423  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:39.423  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-29 11:25:39.433  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
08-29 11:25:39.433  7366  7366 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 11:25:39.433  1016  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:39.433  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-29 11:25:39.433  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:39.433  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:39.433  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:39.453  2001  2001 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 11:25:39.453  1016  1329 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 11:25:39.453  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-29 11:25:39.453  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:39.453  1016  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 11:25:39.463  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:39.473  1016  1471 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 11:25:39.473  2001  7485 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-29 11:25:39.473  2001  2001 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 11:25:39.473  1016  1550 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:39.483  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:39.483  1016  1550 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:39.483  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:39.493  7366  7488 D BluetoothSocket: bindListen(): myUserId = 0
08-29 11:25:39.493  7366  7488 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:25:39.493  7366  7488 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-29 11:25:39.493  7366  7488 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 11:25:39.493  7366  7488 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 11:25:39.493  7366  7488 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a783720
,08-29 11:25:39.493  7366  7488 D BluetoothSocket: channel: 12
08-29 11:25:39.493  7366  7488 I BtOppRfcommListener: Accept thread started.
,08-29 11:25:39.493  1016  1134 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:39.503  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:39.503  1016  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:39.503  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:39.513  2001  7485 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-29 11:25:40.883  6746  6800 D BluetoothAdapter: disable()
,08-29 11:25:40.893  1016  1329 D SettingsProvider: name = bluetooth_on
,08-29 11:25:40.923  7366  7381 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-29 11:25:40.923  7366  7381 D BluetoothAdapterProperties: Setting state to 13
08-29 11:25:40.923  7366  7381 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 11:25:40.923  7366  7381 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 11:25:40.923  7366  7381 D BluetoothAdapterService: updateAdapterState state is 13
,08-29 11:25:40.923  1016  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:40.923  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 11:25:40.923  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:40.923  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:40.923  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:40.923  7366  7366 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-29 11:25:40.923  7366  7381 D BluetoothAdapterService: Autoconnection is available 
,08-29 11:25:40.923  7366  7381 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-29 11:25:40.923  7366  7381 D BluetoothAdapterService: terminating service from this receiver
,08-29 11:25:40.923  7366  7366 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@28bb68d9, channel: 19, state: LISTENING
,08-29 11:25:40.933  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:40.933  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
08-29 11:25:40.933  7366  7366 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@28bb68d9, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2dc88f08, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2293f29emSocket: android.net.LocalSocket@111ea17f impl:android.net.LocalSocketImpl@679a54c fd:FileDescriptor[74]
08-29 11:25:40.933  7366  7366 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@111ea17f impl:android.net.LocalSocketImpl@679a54c fd:FileDescriptor[74]
,08-29 11:25:40.933  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-29 11:25:40.933  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 11:25:40.943  1177  1765 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 11:25:40.943  1177  1765 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 11:25:40.943  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:40.943  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-29 11:25:40.943  1872  1872 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 11:25:40.953  1016  1224 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 11:25:40.953  1177  1765 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 11:25:40.953  3306  3306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:40.953  1016  1472 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-29 11:25:40.953  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 11:25:40.963  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:25:40.963  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:40.963  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:40.963  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:40.963  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:40.963  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:40.963  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:40.963  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:40.963  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:25:40.963  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 11:25:40.963  6746  6746 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:40.963  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 11:25:40.963  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:40.963  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:40.963  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:40.963  7366  7381 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 11:25:40.963  7366  7381 D BluetoothAdapterProperties: mDiscovering is false
08-29 11:25:40.963  7366  7366 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@36f0b995, channel: 5, state: LISTENING
08-29 11:25:40.963  7366  7366 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@36f0b995, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@143990c6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1b489aaamSocket: android.net.LocalSocket@685d69b impl:android.net.LocalSocketImpl@2541ca38 fd:FileDescriptor[76]
08-29 11:25:40.963  7366  7366 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@685d69b impl:android.net.LocalSocketImpl@2541ca38 fd:FileDescriptor[76]
,08-29 11:25:40.973  7366  7366 I BtOppRfcommListener: stopping Accept Thread
08-29 11:25:40.973  7366  7366 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@7f05a11, channel: 12, state: LISTENING
08-29 11:25:40.973  7366  7366 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@7f05a11, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a783720, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@16edb776mSocket: android.net.LocalSocket@c614177 impl:android.net.LocalSocketImpl@6551e4 fd:FileDescriptor[80]
08-29 11:25:40.973  7366  7366 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@c614177 impl:android.net.LocalSocketImpl@6551e4 fd:FileDescriptor[80]
,08-29 11:25:40.973  7366  7488 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 11:25:40.973  7366  7488 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 11:25:40.973  1016  1471 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-29 11:25:40.973  7366  7381 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-29 11:25:40.973  1016  1551 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 11:25:40.973  1016  1551 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 11:25:40.973  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:40.973  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:40.973  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:40.973  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:40.973  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:40.973  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 11:25:40.973  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:40.973  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:40.973  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 11:25:40.973  1016  1551 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:40.973  1016  1551 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:40.973  1016  1551 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:40.973  6746  6746 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 11:25:40.973  3306  3306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 11:25:40.973  6746  6746 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:25:40.973  1016  1028 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 11:25:40.973  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 11:25:40.983  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:40.983  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:40.983  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 11:25:40.993  7366  7384 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 11:25:40.993  7366  7384 D BluetoothAdapterProperties: Scan Mode:20
,08-29 11:25:40.993  3306  3306 D BluetoothPbap: Proxy object disconnected
08-29 11:25:40.993  3306  3306 D PbapServerProfile: Bluetooth service disconnected
,08-29 11:25:40.993  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:41.003  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:41.003  3306  3306 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:25:41.003  7366  7381 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 11:25:41.003  7366  7381 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-29 11:25:41.003  7366  7381 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-29 11:25:41.003  7366  7381 E bt-btif : cmd socket is not created
,08-29 11:25:41.003  7366  7426 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-29 11:25:41.003  7366  7426 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-29 11:25:41.003  7366  7426 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:25:41.003  7366  7426 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:25:41.003  7366  7426 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:25:41.003  3306  3306 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 11:25:41.013  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:41.013  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
08-29 11:25:41.013  7366  7381 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-29 11:25:41.013  7366  7366 V BluetoothOppManager: cleanUp...
,08-29 11:25:41.033  2001  2001 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 11:25:41.043  2001  2001 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 11:25:41.073  1016  1551 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 11:25:41.073  1016  1551 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 11:25:41.073  1016  1551 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-29 11:25:41.073  1016  1551 D BatteryService: stay LED for fully charged
08-29 11:25:41.073  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 11:25:41.073  1016  1016 I MotionRecognitionService: Plugged
,08-29 11:25:41.073  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 11:25:41.083  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 11:25:41.083  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 11:25:41.083  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 11:25:41.083  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 11:25:41.093  7366  7366 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 11:25:41.093  7366  7400 D HeadsetStateMachine: Disconnected process message: 10
,08-29 11:25:41.103  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 11:25:41.103  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-29 11:25:41.103  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 11:25:41.103  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 11:25:41.103  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 11:25:41.203  7366  7426 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 11:25:41.203  7366  7426 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:25:41.203  7366  7426 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:25:41.203  7366  7426 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:25:41.203  7366  7426 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:25:41.203  7366  7426 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:25:41.203  7366  7426 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 11:25:41.203  7366  7426 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 11:25:41.203  7366  7426 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 11:25:41.203  7366  7426 W bt-btif : ag scb idx 1 not allocated
08-29 11:25:41.203  7366  7426 W bt-btif : ag scb idx 2 not allocated
08-29 11:25:41.203  7366  7426 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 11:25:41.203  7366  7471 I bt_userial_mct: exiting userial_read_thread
08-29 11:25:41.203  7366  7471 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 11:25:41.203  7366  7384 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 11:25:41.203  7366  7428 I bt_vendor: hw_epilog_process
08-29 11:25:41.203  7366  7384 D bt_userial_mct: userial_close
08-29 11:25:41.203  7366  7384 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-29 11:25:41.643  7366  7384 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-29 11:25:41.643  7366  7384 I bt_vendor: bluetooth satus is on
08-29 11:25:41.643  7366  7384 I bt_vendor: bt-vendor : resetting BT status
08-29 11:25:41.643  7366  7384 I bt_vendor: Starting hciattach daemon
08-29 11:25:41.643  7366  7384 I bt_vendor: try to set false
,08-29 11:25:41.643  7366  7384 I bt_vendor: Starting hciattach daemon
08-29 11:25:41.643  7366  7384 I bt_vendor: try to set false
,08-29 11:25:41.643  7366  7384 I bt_vendor: cleanup
,08-29 11:25:41.643  7366  7426 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-29 11:25:41.643  7366  7384 I GKI_LINUX: GKI_exit_task 0 done
,08-29 11:25:41.643  7366  7384 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-29 11:25:41.643  7366  7381 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-29 11:25:41.643  7366  7381 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 11:25:41.643  7366  7381 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-29 11:25:41.643  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-29 11:25:41.643  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-29 11:25:41.643  7366  7381 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-29 11:25:41.643  1016  1329 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:41.643  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-29 11:25:41.643  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:41.653  1016  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:41.653  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:41.653  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 11:25:41.653  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 11:25:41.653  7366  7381 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-29 11:25:41.653  1016  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:41.653  1016  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-29 11:25:41.653  7366  7366 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 11:25:41.653  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:41.653  1016  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:41.653  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:41.653  7366  7366 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 11:25:41.653  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 11:25:41.653  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 11:25:41.653  7366  7381 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 11:25:41.653  7366  7366 D BtGatt.GattService: stop()
08-29 11:25:41.653  7366  7366 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 11:25:41.653  1016  1551 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:41.653  1016  1551 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 11:25:41.653  1016  1551 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:41.653  1016  1551 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:41.653  1016  1551 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:41.653  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-29 11:25:41.653  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 11:25:41.653  7366  7381 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 11:25:41.653  1016  1550 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:41.653  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
08-29 11:25:41.663  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-29 11:25:41.663  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:41.663  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:41.663  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:41.663  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-29 11:25:41.663  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 11:25:41.663  7366  7381 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 11:25:41.663  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:41.663  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 11:25:41.663  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:41.663  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:41.663  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:41.663  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-29 11:25:41.663  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 11:25:41.663  7366  7381 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 11:25:41.673  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:41.673  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 11:25:41.673  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:41.673  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:41.673  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:41.673  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-29 11:25:41.673  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 11:25:41.673  7366  7381 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 11:25:41.673  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:41.673  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 11:25:41.673  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:41.673  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:41.673  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:41.683  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-29 11:25:41.683  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 11:25:41.683  7366  7381 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 11:25:41.683  1016  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:41.683  1016  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 11:25:41.683  1016  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:41.683  1016  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:41.683  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:41.683  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 11:25:41.683  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 11:25:41.683  7366  7381 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 11:25:41.683  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 11:25:41.683  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-29 11:25:41.683  7366  7381 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-29 11:25:41.683  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 11:25:41.693  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-29 11:25:41.693  7366  7381 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-29 11:25:41.693  7366  7381 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,08-29 11:25:41.693  7366  7381 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-29 11:25:41.693  7366  7381 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-29 11:25:41.693  7366  7366 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-29 11:25:41.693  7366  7381 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-29 11:25:41.693  7366  7366 D HeadsetService: Received stop request...Stopping profile...
,08-29 11:25:41.693  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:41.693  7366  7366 D A2dpService: Received stop request...Stopping profile...
08-29 11:25:41.703  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-29 11:25:41.703  3306  3306 D HeadsetProfile: Bluetooth service disconnected
,08-29 11:25:41.703  7366  7411 D A2dpStateMachine: Exit Disconnected: -1
,08-29 11:25:41.703  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:41.703  1016  1016 D BluetoothA2dp: Proxy object disconnected
,08-29 11:25:41.703  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-29 11:25:41.703  7366  7366 D HidService: Received stop request...Stopping profile...
,08-29 11:25:41.713  3306  3306 D BluetoothA2dp: Proxy object disconnected
08-29 11:25:41.713  7366  7366 D HidService: Stopping Bluetooth HidService
08-29 11:25:41.713  7366  7366 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 11:25:41.713  7366  7366 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-29 11:25:41.713  7366  7366 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 11:25:41.713  3306  3306 D A2dpProfile: Bluetooth service disconnected
08-29 11:25:41.713  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:41.713  7366  7366 D HealthService: Received stop request...Stopping profile...
,08-29 11:25:41.713  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:41.713  7366  7366 D PanService: Received stop request...Stopping profile...
,08-29 11:25:41.713  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:41.713  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 11:25:41.713  7366  7366 D BluetoothMapService: Received stop request...Stopping profile...
08-29 11:25:41.713  3306  3306 D BluetoothInputDevice: Proxy object disconnected
08-29 11:25:41.713  3306  3306 D HidProfile: Bluetooth service disconnected
08-29 11:25:41.723  3306  3306 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 11:25:41.723  3306  3306 D PanProfile: Bluetooth service disconnected
,08-29 11:25:41.723  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:41.723  3306  3306 D BluetoothMap: Proxy object disconnected
,08-29 11:25:41.723  7366  7366 D SapService: Received stop request...Stopping profile...
08-29 11:25:41.723  7366  7366 D SapService: Stopping Bluetooth SapService
08-29 11:25:41.723  7366  7366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a7437de
,08-29 11:25:41.723  3306  3306 D MapProfile: Bluetooth service disconnected
,08-29 11:25:41.723  7366  7366 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-29 11:25:41.723  7366  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 11:25:41.723  7366  7366 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-29 11:25:41.723  3306  3306 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-29 11:25:41.723  3306  3306 D SapProfile: Bluetooth service disconnected
,08-29 11:25:41.723  7366  7366 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 11:25:41.723  7366  7366 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 11:25:41.723  7366  7366 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-29 11:25:41.723  7366  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 11:25:41.723  7366  7366 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-29 11:25:41.723  7366  7366 D BluetoothA2dp: Proxy object disconnected
08-29 11:25:41.723  7366  7366 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-29 11:25:41.733  7366  7412 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 11:25:41.733  7366  7366 I GKI_LINUX: GKI_exit_task 2 done
08-29 11:25:41.733  7366  7366 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-29 11:25:41.733  7366  7366 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,08-29 11:25:41.733  7366  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 11:25:41.733  7366  7366 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-29 11:25:41.733  7366  7366 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-29 11:25:41.733  7366  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 11:25:41.733  7366  7366 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-29 11:25:41.733  7366  7366 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 11:25:41.733  7366  7366 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 11:25:41.733  7366  7366 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-29 11:25:41.733  7366  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 11:25:41.733  7366  7366 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 11:25:41.733  7366  7366 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 11:25:41.733  7366  7366 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 11:25:41.733  7366  7366 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-29 11:25:41.733  7366  7366 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 11:25:41.733  7366  7366 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-29 11:25:41.733  7366  7366 E BluetoothAdapterService(175388638): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-29 11:25:41.733  7366  7366 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-29 11:25:41.733  7366  7366 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-29 11:25:41.733  7366  7381 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-29 11:25:41.733  7366  7381 D BluetoothAdapterProperties: Setting state to 10
08-29 11:25:41.733  7366  7381 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 11:25:41.733  7366  7381 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 11:25:41.733  7366  7381 D BluetoothAdapterService: updateAdapterState state is 10
,08-29 11:25:41.733  3306  3319 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 11:25:41.733  7366  7381 D BluetoothAdapterService: Autoconnection is available 
08-29 11:25:41.733  7366  7381 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-29 11:25:41.733  7366  7381 I BluetoothAdapterState: Entering OffState
,08-29 11:25:41.743  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 11:25:41.743  1177  1187 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 11:25:41.743  1177  1187 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 11:25:41.743  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 11:25:41.743  1016  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 11:25:41.743  7417  7434 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 11:25:41.743  7417  7434 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 11:25:41.743   288   288 E SMD     : DCD OFF
,08-29 11:25:41.743  7366  7385 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 11:25:41.743  7366  7385 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 11:25:41.743  7366  7478 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 11:25:41.743  3306  6947 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 11:25:41.743  2001  2157 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 11:25:41.743  2001  2157 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 11:25:41.753  3306  3322 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 11:25:41.753  3306  3322 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 11:25:41.753  3306  6947 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 11:25:41.753  3306  3319 D Bluetoothsap: onBluetoothStateChange: up=false
,08-29 11:25:41.753  3306  3319 D Bluetoothsap: Unbinding service...
,08-29 11:25:41.753  6746  6754 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 11:25:41.753  6746  6754 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 11:25:41.753  6746  6754 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-29 11:25:41.753  6746  6754 D BluetoothLeAdvertiser: Exit stop advertising
,08-29 11:25:41.753  6746  6754 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-29 11:25:41.753  6746  6754 D BluetoothLeScanner: Exiting stopAllScan
,08-29 11:25:41.753  3306  6947 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 11:25:41.753  1432  1447 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 11:25:41.753  1432  1447 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 11:25:41.763  1456  1473 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 11:25:41.763  1456  1473 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 11:25:41.763  1441  1462 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 11:25:41.763  1441  1462 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 11:25:41.763  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 11:25:41.763  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-29 11:25:41.773  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:41.773  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
08-29 11:25:41.773  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 11:25:41.773  1177  1177 D BluetoothAdapter: 1060206718: getState() :  mService = null. Returning STATE_OFF
,08-29 11:25:41.773  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 11:25:41.773  1177  1765 D BluetoothAdapter: 1060206718: getState() :  mService = null. Returning STATE_OFF
08-29 11:25:41.773  7366  7384 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-29 11:25:41.773  7366  7366 I GKI_LINUX: GKI_exit_task 1 done
08-29 11:25:41.773  7366  7366 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-29 11:25:41.773  7366  7366 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 11:25:41.773  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:41.773  1177  1765 D BluetoothAdapter: 1060206718: getState() :  mService = null. Returning STATE_OFF
08-29 11:25:41.773  1177  1177 D BluetoothTile:  getBluetoothState : 10
,08-29 11:25:41.773  1177  1177 D BluetoothAdapter: 1060206718: getState() :  mService = null. Returning STATE_OFF
08-29 11:25:41.773  1177  1177 D BluetoothAdapter: 1060206718: getState() :  mService = null. Returning STATE_OFF
,08-29 11:25:41.773  1016  1479 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 11:25:41.783  1872  1872 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 11:25:41.783  1016  1472 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 11:25:41.783  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 11:25:41.783  2001  2161 D BluetoothAdapter: 991978917: getState() :  mService = null. Returning STATE_OFF
08-29 11:25:41.783  2001  2161 D BluetoothAdapter: 991978917: getState() :  mService = null. Returning STATE_OFF
,08-29 11:25:41.783  3306  3306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:41.783  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:41.783  7366  7366 I art     : System.exit called, status: 0
08-29 11:25:41.783  7366  7366 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 11:25:41.783  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:41.783  1016  1224 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 11:25:41.783  1016  1224 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 11:25:41.783  1016  1224 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:41.783  1016  1224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 11:25:41.783  1016  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:41.793  3306  3306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 11:25:41.793  1016  1472 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-29 11:25:41.793  1016  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 11:25:41.793  1016  1472 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:41.793  1016  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:41.793  1016  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 11:25:41.803  3306  3306 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:25:41.803  3306  3306 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 11:25:41.813  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:41.813  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-29 11:25:41.813  1016  1550 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-29 11:25:41.823  1016  1550 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-29 11:25:41.823  1016  1550 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-29 11:25:41.823  1016  1550 W BroadcastQueue: android.os.TransactionTooLargeException
08-29 11:25:41.823  1016  1550 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 11:25:41.823  1016  1550 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 11:25:41.823  1016  1550 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-29 11:25:41.823  1016  1550 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-29 11:25:41.823  1016  1550 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-29 11:25:41.823  1016  1550 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-29 11:25:41.823  1016  1550 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-29 11:25:41.823  1016  1550 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-29 11:25:41.823  1016  1550 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 11:25:41.823  1016  1550 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-29 11:25:41.823  1016  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:41.833  1016  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:41.833  1016  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:41.833  1016  1550 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:41.843  7505  7505 E Zygote  : MountEmulatedStorage()
,08-29 11:25:41.843  7505  7505 E Zygote  : v2
08-29 11:25:41.843  7505  7505 I libpersona: KNOX_SDCARD checking this for 1002
08-29 11:25:41.843  7505  7505 I libpersona: KNOX_SDCARD not a persona
,08-29 11:25:41.843  7505  7505 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 11:25:41.843  1016  1550 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7505 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
08-29 11:25:41.843  7505  7505 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 11:25:41.853  7505  7505 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-29 11:25:41.863  7505  7505 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:41.863  7505  7505 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:41.873  7505  7505 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-29 11:25:41.883  7505  7505 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 11:25:41.903  7505  7505 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-29 11:25:41.943  7505  7505 D BtSettings.ProfileConfig: Adding GattService
,08-29 11:25:41.943  7505  7505 D BtSettings.ProfileConfig: Adding HeadsetService
,08-29 11:25:41.943  7505  7505 D BtSettings.ProfileConfig: Adding A2dpService
,08-29 11:25:41.943  7505  7505 D BtSettings.ProfileConfig: Adding HidService
,08-29 11:25:41.943  7505  7505 D BtSettings.ProfileConfig: Adding HealthService
,08-29 11:25:41.943  7505  7505 D BtSettings.ProfileConfig: Adding PanService
,08-29 11:25:41.943  7505  7505 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-29 11:25:41.943  7505  7505 D BtSettings.ProfileConfig: Adding SapService
,08-29 11:25:41.943  7505  7505 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-29 11:25:41.943  7505  7505 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-29 11:25:41.943  7505  7505 D BtSettings.ProfileConfig: Adding SapClientService
,08-29 11:25:41.943  7505  7505 D BtSettings.ProfileConfig: Adding HidDevService
,08-29 11:25:41.943  7505  7505 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-29 11:25:41.953  1016  1550 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-29 11:25:41.953  1016  1550 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 11:25:41.953  1016  1550 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:41.953  1016  1550 D SettingsProvider: selectionArgs: false
08-29 11:25:41.953  1016  1550 D SettingsProvider: selectionArgs: 1002
,08-29 11:25:41.953  1016  1550 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:41.953  1016  1550 D SettingsProvider: ret = -1
,08-29 11:25:41.953  1016  1471 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-29 11:25:41.953  1016  1471 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:41.953  1016  1471 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:41.953  1016  1471 D SettingsProvider: selectionArgs: false
08-29 11:25:41.953  1016  1471 D SettingsProvider: selectionArgs: 1002
08-29 11:25:41.953  1016  1471 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:41.953  1016  1471 D SettingsProvider: ret = -1
,08-29 11:25:41.953  1016  1329 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-29 11:25:41.953  1016  1329 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:41.953  1016  1329 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:41.953  1016  1329 D SettingsProvider: selectionArgs: false
08-29 11:25:41.953  1016  1329 D SettingsProvider: selectionArgs: 1002
08-29 11:25:41.953  1016  1329 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:41.953  1016  1329 D SettingsProvider: ret = -1
,08-29 11:25:41.953  1016  1134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-29 11:25:41.953  1016  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 11:25:41.953  1016  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:41.953  1016  1134 D SettingsProvider: selectionArgs: false
,08-29 11:25:41.953  1016  1134 D SettingsProvider: selectionArgs: 1002
08-29 11:25:41.953  1016  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 11:25:41.953  1016  1134 D SettingsProvider: ret = -1
,08-29 11:25:41.953  1016  1472 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-29 11:25:41.963  1016  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:41.963  1016  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:41.963  1016  1472 D SettingsProvider: selectionArgs: false
08-29 11:25:41.963  1016  1472 D SettingsProvider: selectionArgs: 1002
,08-29 11:25:41.963  1016  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:41.963  1016  1472 D SettingsProvider: ret = -1
,08-29 11:25:41.963  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-29 11:25:41.963  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:41.963  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:41.963  1016  1028 D SettingsProvider: selectionArgs: false
08-29 11:25:41.963  1016  1028 D SettingsProvider: selectionArgs: 1002
,08-29 11:25:41.963  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:41.963  1016  1028 D SettingsProvider: ret = -1
,08-29 11:25:41.963  1016  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-29 11:25:41.963  1016  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:41.963  1016  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:41.963  1016  1480 D SettingsProvider: selectionArgs: false
,08-29 11:25:41.963  1016  1480 D SettingsProvider: selectionArgs: 1002
08-29 11:25:41.963  1016  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:41.963  1016  1480 D SettingsProvider: ret = -1
,08-29 11:25:41.963  1016  1551 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,08-29 11:25:41.963  1016  1551 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:41.963  1016  1551 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:41.963  1016  1551 D SettingsProvider: selectionArgs: false
,08-29 11:25:41.963  1016  1551 D SettingsProvider: selectionArgs: 1002
08-29 11:25:41.963  1016  1551 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 11:25:41.963  1016  1551 D SettingsProvider: ret = -1
,08-29 11:25:41.963  1016  1224 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 11:25:41.963  1016  1224 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:41.963  1016  1224 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 11:25:41.973  1016  1224 D SettingsProvider: selectionArgs: false
08-29 11:25:41.973  1016  1224 D SettingsProvider: selectionArgs: 1002
08-29 11:25:41.973  1016  1224 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 11:25:41.973  1016  1224 D SettingsProvider: ret = -1
,08-29 11:25:41.973  1016  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-29 11:25:41.973  1016  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:41.973  1016  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 11:25:41.973  1016  1029 D SettingsProvider: selectionArgs: false
08-29 11:25:41.973  1016  1029 D SettingsProvider: selectionArgs: 1002
08-29 11:25:41.973  1016  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:41.973  1016  1029 D SettingsProvider: ret = -1
,08-29 11:25:41.973  1016  1479 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-29 11:25:41.973  1016  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:41.973  1016  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:41.973  1016  1479 D SettingsProvider: selectionArgs: false
,08-29 11:25:41.973  1016  1479 D SettingsProvider: selectionArgs: 1002
08-29 11:25:41.973  1016  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 11:25:41.973  1016  1479 D SettingsProvider: ret = -1
,08-29 11:25:41.973  1016  1497 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-29 11:25:41.973  1016  1497 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:41.973  1016  1497 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:41.973  1016  1497 D SettingsProvider: selectionArgs: false
,08-29 11:25:41.973  1016  1497 D SettingsProvider: selectionArgs: 1002
,08-29 11:25:41.973  1016  1497 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:41.973  1016  1497 D SettingsProvider: ret = -1
,08-29 11:25:41.993  2001  2001 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 11:25:41.993  1016  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 11:25:41.993  1016  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-29 11:25:41.993  1016  1472 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:41.993  1016  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:41.993  1016  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:42.003  2001  7521 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-29 11:25:42.003  2001  2001 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 11:25:42.013  1016  1471 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:42.013  1016  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:42.013  1016  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:42.013  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:42.023  2001  7521 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-29 11:25:42.773  1016  1320 E Watchdog: !@Sync 4
,08-29 11:25:42.913  1016  1048 I PowerManagerService: [PWL] Off : 75s ago
,08-29 11:25:42.913  1016  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,08-29 11:25:42.913  1016  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-29 11:25:42.913  1016  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1016, ws=null) (elapsedTime=13152)
,08-29 11:25:43.783   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 11:25:43.913  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 11:25:43.913  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:44.743   288   288 E SMD     : DCD OFF
,08-29 11:25:44.783   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 11:25:45.783   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 11:25:46.783   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 11:25:46.913  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:46.913  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13550ab added. We now have 6 listener(s)
08-29 11:25:46.913  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:46.913  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:46.913  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1189a308 added. We now have 7 listener(s)
08-29 11:25:46.913  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:46.913  6746  6800 I System.out: IsBluetoothEnabled
,08-29 11:25:46.913  6746  6800 D BluetoothAdapter: disable()
08-29 11:25:46.913  1016  1329 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-29 11:25:46.923  6746  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:46.923  6746  6800 D BluetoothAdapter: enable()
,08-29 11:25:46.923  1016  1550 W ActivityManager: Permission Denial: getCurrentUser() from pid=6746, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-29 11:25:46.923  1016  1550 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-29 11:25:46.923  1016  1550 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6746, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 11:25:46.923  1016  1550 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 11:25:46.923  1016  1550 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-29 11:25:46.923  1016  1550 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-29 11:25:46.923  1016  1550 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-29 11:25:46.923  1016  1550 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 11:25:46.923  1016  1550 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 11:25:46.923  1016  1550 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 11:25:46.933  1016  1550 D SettingsProvider: name = bluetooth_on,
,08-29 11:25:46.943  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-29 11:25:46.943  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 11:25:46.943  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-29 11:25:46.943  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-29 11:25:46.953  1016  3399 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 11:25:46.963  7505  7505 D BluetoothAdapterState: make
,08-29 11:25:46.973  7505  7505 I bluedroid: init
,08-29 11:25:46.973  7505  7505 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 11:25:46.973  7505  7505 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 11:25:46.973  7505  7505 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 11:25:46.973  7505  7505 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 11:25:46.973  7505  7505 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-29 11:25:46.973  7505  7505 I bluedroid: get_profile_interface socket
08-29 11:25:46.973  7505  7505 I bluedroid: get_profile_interface map_client
,08-29 11:25:46.973  7505  7505 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-29 11:25:46.983  7505  7530 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-29 11:25:46.983  7505  7527 I BluetoothAdapterState: Entering OffState
,08-29 11:25:46.983  7505  7530 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-29 11:25:46.983  7505  7530 E BluetoothServiceJni: populateRssiValuesNative
08-29 11:25:46.983  7505  7530 I bluedroid: getModelRssiValues
,08-29 11:25:46.983  7505  7530 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-29 11:25:46.983  7505  7530 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 11:25:46.983  7505  7530 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-29 11:25:46.983  1016  1016 D SettingsProvider: name = bluetooth_name
,08-29 11:25:46.993  7505  7505 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 11:25:46.993  1016  1028 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-29 11:25:46.993  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 11:25:46.993  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:46.993  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:46.993  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:46.993  7505  7513 I bluedroid: config_hci_snoop_log
,08-29 11:25:46.993  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 11:25:47.003  1016  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-29 11:25:47.003  1016  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-29 11:25:47.003  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-29 11:25:47.003  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 11:25:47.013  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 11:25:47.013  7505  7505 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
08-29 11:25:47.013  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 11:25:47.013  1016  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-29 11:25:47.023  7505  7527 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-29 11:25:47.023  7505  7527 D BluetoothAdapterProperties: Setting state to 11
08-29 11:25:47.023  7505  7527 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-29 11:25:47.023  7505  7527 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 11:25:47.023  7505  7527 D BluetoothAdapterService: updateAdapterState state is 11
,08-29 11:25:47.023  7505  7527 D BluetoothAdapterService: Autoconnection is available 
,08-29 11:25:47.023  7505  7527 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-29 11:25:47.023  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-29 11:25:47.023  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:47.023  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
,08-29 11:25:47.023  7505  7527 D BluetoothSecureManager: getInstant: null
08-29 11:25:47.023  7505  7527 D BluetoothSecureManager: calling getMethod for getService
08-29 11:25:47.023  7505  7527 D BluetoothSecureManager: calling getService
,08-29 11:25:47.023  7505  7527 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@2f5c048d
,08-29 11:25:47.033  1016  1029 D BluetoothSecureManagerService: isSecureModeEnabled
08-29 11:25:47.033  1016  1029 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-29 11:25:47.033  7505  7527 D BtConfig.SecureMode: isSecureModeOn:false
08-29 11:25:47.033  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-29 11:25:47.033  7505  7527 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-29 11:25:47.033  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-29 11:25:47.033  7505  7527 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-29 11:25:47.033  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 11:25:47.033  7505  7527 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-29 11:25:47.033  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 11:25:47.033  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 11:25:47.033  7505  7527 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-29 11:25:47.033  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 11:25:47.033  7505  7527 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-29 11:25:47.033  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 11:25:47.033  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:47.033  1177  1177 D BluetoothTile:  getBluetoothState : 11
,08-29 11:25:47.033  7505  7527 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-29 11:25:47.033  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 11:25:47.033  7505  7527 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-29 11:25:47.033  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 11:25:47.033  7505  7527 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-29 11:25:47.033  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 11:25:47.033  7505  7527 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 11:25:47.033  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-29 11:25:47.033  1872  1872 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-29 11:25:47.033  7505  7527 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-29 11:25:47.033  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-29 11:25:47.033  7505  7527 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-29 11:25:47.033  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-29 11:25:47.033  7505  7527 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-29 11:25:47.043  1016  1550 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 11:25:47.043  1016  1472 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 11:25:47.043  7505  7527 D BluetoothBondStateMachine: make
08-29 11:25:47.043  3306  3306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:47.043  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 11:25:47.043  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 11:25:47.043  1177  1765 D BluetoothTile:  handleUpdatestate:false name:null
08-29 11:25:47.043  1177  1765 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 11:25:47.043  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:47.043  7505  7527 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-29 11:25:47.043  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-29 11:25:47.043  7505  7527 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-29 11:25:47.043  7505  7532 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 11:25:47.053  1016  1550 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:47.053  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-29 11:25:47.053  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:47.053  3306  3306 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 11:25:47.053  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:47.053  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:47.053  7505  7527 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 11:25:47.053  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 11:25:47.053  7505  7527 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-29 11:25:47.053  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:47.053  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 11:25:47.053  7505  7505 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 11:25:47.053  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:47.053  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:47.053  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:47.053  7505  7505 D BtGatt.GattService: Received start request. Starting profile...
08-29 11:25:47.053  7505  7505 D BtGatt.GattService: start()
08-29 11:25:47.053  7505  7505 D BtGatt.GattService: start()
08-29 11:25:47.053  7505  7505 I bluedroid: get_profile_interface gatt
,08-29 11:25:47.053  7505  7505 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d9e8c8c
08-29 11:25:47.053  7505  7505 D BtGatt.AdvertiseManager: advertise manager created
,08-29 11:25:47.063  1016  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 11:25:47.063  1016  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 11:25:47.063  7505  7527 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-29 11:25:47.063  1016  1480 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:47.063  1016  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:47.063  1016  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:47.063  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 11:25:47.063  7505  7527 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 11:25:47.073  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:47.073  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-29 11:25:47.073  1016  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:47.073  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 11:25:47.073  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:47.073  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:47.073  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:47.073  7505  7527 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-29 11:25:47.073  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 11:25:47.073  7505  7527 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 11:25:47.083  7505  7505 D BtGatt.GattService: mStartError = false
08-29 11:25:47.083  7505  7505 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d9e8c8c
,08-29 11:25:47.083  1016  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:47.083  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 11:25:47.083  7505  7505 D HeadsetService: Received start request. Starting profile...
08-29 11:25:47.083  7505  7505 D HeadsetService: start()
,08-29 11:25:47.083  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:47.083  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:47.083  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:47.083  7505  7505 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 11:25:47.083  7505  7505 D HeadsetStateMachine: make
,08-29 11:25:47.083  7505  7505 E HeadsetStateMachine: # of Max HF connection is 2
,08-29 11:25:47.093  7505  7527 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-29 11:25:47.093  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 11:25:47.093  7505  7527 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 11:25:47.093  1016  1329 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:47.093  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 11:25:47.093  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:47.093  1016  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:47.093  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:47.103  1016  1480 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-29 11:25:47.103  1016  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-29 11:25:47.103  7505  7527 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-29 11:25:47.103  1016  1480 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:47.103  1016  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:47.103  1016  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 11:25:47.103  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 11:25:47.103  7505  7527 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 11:25:47.103  1016  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:47.103  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 11:25:47.103  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:47.103  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:47.103  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:47.103  1016  1029 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-29 11:25:47.103  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-29 11:25:47.103  7505  7527 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 11:25:47.103  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 11:25:47.113  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:47.113  7505  7527 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-29 11:25:47.113  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:47.113  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 11:25:47.113  7505  7505 I bluedroid: get_profile_interface handsfree
08-29 11:25:47.113  1016  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:47.113  1016  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 11:25:47.113  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:47.113  1016  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:47.113  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:47.113  7505  7527 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-29 11:25:47.113  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 11:25:47.113  7505  7527 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 11:25:47.113  1016  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:47.113  1016  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 11:25:47.113  1016  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:47.113  1016  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:47.113  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:47.123  7505  7527 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-29 11:25:47.123  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 11:25:47.123  7505  7527 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-29 11:25:47.123  7505  7527 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 11:25:47.123  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 11:25:47.123  7505  7527 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 11:25:47.123  7505  7527 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 11:25:47.123  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 11:25:47.123  7505  7527 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 11:25:47.123  7505  7527 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-29 11:25:47.123  7505  7527 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 11:25:47.123  7505  7527 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 11:25:47.123  7505  7527 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-29 11:25:47.123  7505  7505 I DualScoManager: Instantiating Dual Sco Manager
08-29 11:25:47.123  7505  7505 I DualScoManager: Set HeadsetServiceHelper
,08-29 11:25:47.133  7505  7505 D BluetoothAtMessage: createCMTIContentObservers
,08-29 11:25:47.133  1016  1224 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-29 11:25:47.133  1016  1224 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:47.133  1016  1224 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 11:25:47.133  1016  1224 D SettingsProvider: selectionArgs: false
,08-29 11:25:47.133  1016  1224 D SettingsProvider: selectionArgs: 1002
08-29 11:25:47.133  1016  1224 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:47.133  1016  1224 D SettingsProvider: ret = -1
,08-29 11:25:47.133  7505  7536 D HeadsetStateMachine: Enter Disconnected: -2
,08-29 11:25:47.133  7505  7505 D HeadsetService: mStartError = false
,08-29 11:25:47.133  7505  7505 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d9e8c8c
,08-29 11:25:47.133  7505  7505 D A2dpService: Received start request. Starting profile...
,08-29 11:25:47.143  7505  7505 D A2dpService: start()
,08-29 11:25:47.143  7505  7536 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-29 11:25:47.143  7505  7505 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 11:25:47.143  7505  7536 D HeadsetStateMachine: map size, before remove : 0
08-29 11:25:47.143  7505  7536 D HeadsetStateMachine: map size, after remove: 0
,08-29 11:25:47.143  7505  7505 I bluedroid: get_profile_interface avrcp
,08-29 11:25:47.143  7505  7505 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 11:25:47.143  7505  7505 D Avrcp   : Initialize Media Controller
,08-29 11:25:47.153  7505  7505 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-29 11:25:47.153  7505  7505 E Avrcp   : getActiveSessions
,08-29 11:25:47.153  7505  7505 D Avrcp   : pick active media Controller
08-29 11:25:47.153  7505  7505 D Avrcp   : Get the active Media Controller 
,08-29 11:25:47.163  7505  7505 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-29 11:25:47.163  7505  7540 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-29 11:25:47.173  7505  7505 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-29 11:25:47.173  7505  7505 D A2dpStateMachine: make
,08-29 11:25:47.173  7505  7505 I bluedroid: get_profile_interface a2dp
,08-29 11:25:47.173  7505  7542 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 11:25:47.173  7505  7505 E bt-btif : warning : media task started media_task_refcnt 1 
,08-29 11:25:47.173  7505  7505 D A2dpService: mStartError = false
08-29 11:25:47.173  7505  7505 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d9e8c8c
,08-29 11:25:47.173  7505  7541 D A2dpStateMachine: Enter Disconnected: -2
08-29 11:25:47.173  7505  7505 E BluetoothAdapterService(496929932): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-29 11:25:47.173  7505  7505 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 11:25:47.173  7505  7505 D HidService: Received start request. Starting profile...
08-29 11:25:47.173  7505  7505 D HidService: start()
08-29 11:25:47.173  7505  7505 I bluedroid: get_profile_interface hidhost
08-29 11:25:47.173  7505  7505 D HidService: setHidService(): set to: null
08-29 11:25:47.173  7505  7505 D HidService: mStartError = false
08-29 11:25:47.173  7505  7505 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d9e8c8c
,08-29 11:25:47.173  7505  7505 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 11:25:47.183  7505  7505 D HealthService: Received start request. Starting profile...
08-29 11:25:47.183  7505  7505 D HealthService: start()
,08-29 11:25:47.183  7505  7540 D BluetoothMediaBrowser: no now playing list
,08-29 11:25:47.183  7505  7505 I bluedroid: get_profile_interface health
08-29 11:25:47.183  7505  7505 D HealthService: mStartError = false
08-29 11:25:47.183  7505  7505 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d9e8c8c
08-29 11:25:47.183  7505  7505 D HeadsetStateMachine: Try to query the phonestate on bind
,08-29 11:25:47.183  7505  7540 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-29 11:25:47.183  1432  1447 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 11:25:47.183  1432  1432 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-29 11:25:47.183  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 11:25:47.183  1432  1447 I Telecom : BluetoothPhoneService: Result of Message : true
,08-29 11:25:47.193  7505  7505 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 11:25:47.193  7505  7505 D PanService: Received start request. Starting profile...
08-29 11:25:47.193  7505  7505 D PanService: start()
08-29 11:25:47.193  7505  7505 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 11:25:47.193  7505  7505 I bluedroid: get_profile_interface pan
,08-29 11:25:47.193  7505  7505 D PanService: mStartError = false
08-29 11:25:47.193  7505  7505 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d9e8c8c
,08-29 11:25:47.193  7505  7505 D BluetoothMapService: Received start request. Starting profile...
08-29 11:25:47.193  7505  7505 D BluetoothMapService: start()
,08-29 11:25:47.193  2001  2001 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 11:25:47.203  7505  7505 D BluetoothMapService: mStartError = false
08-29 11:25:47.203  7505  7505 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d9e8c8c
,08-29 11:25:47.203  7505  7505 D HeadsetStateMachine: Proxy object connected
08-29 11:25:47.203  7505  7505 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-29 11:25:47.203  7505  7536 D HeadsetStateMachine: Disconnected process message: 11
08-29 11:25:47.203  7505  7505 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-29 11:25:47.203  7505  7505 D SapService: Received start request. Starting profile...
08-29 11:25:47.203  7505  7505 D SapService: start()
08-29 11:25:47.203  7505  7505 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-29 11:25:47.203  7505  7505 I bluedroid: get_profile_interface sap
08-29 11:25:47.203  7505  7505 D SapService: mStartError = false
08-29 11:25:47.203  7505  7505 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d9e8c8c
08-29 11:25:47.203  7505  7505 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-29 11:25:47.203  7505  7505 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-29 11:25:47.203  7505  7505 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 11:25:47.203  7505  7505 E BluetoothAdapterService(496929932): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-29 11:25:47.203  7505  7505 D BluetoothA2dp: Proxy object connected
08-29 11:25:47.203  7505  7536 D HeadsetStateMachine: Disconnected process message: 18
08-29 11:25:47.203  7505  7505 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-29 11:25:47.203  7505  7536 D HeadsetStateMachine: Disconnected process message: 10
08-29 11:25:47.203  7505  7505 E BluetoothAdapterService(496929932): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-29 11:25:47.203  7505  7505 E BluetoothAdapterService(496929932): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-29 11:25:47.203  7505  7536 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 11:25:47.203  7505  7536 D HeadsetStateMachine: Disconnected process message: 11
,08-29 11:25:47.203  2001  2001 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 11:25:47.213  7505  7505 E BluetoothAdapterService(496929932): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-29 11:25:47.213  7505  7505 E BluetoothAdapterService(496929932): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-29 11:25:47.233  7505  7505 E BluetoothAdapterService(496929932): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-29 11:25:47.233  7505  7505 E BluetoothAdapterService(496929932): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-29 11:25:47.233  7505  7527 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-29 11:25:47.243  7505  7527 I bluedroid: enable
,08-29 11:25:47.243  7505  7527 I bt_hci_bdroid: init
08-29 11:25:47.243  7505  7527 I bt_vendor: bt-vendor : init
08-29 11:25:47.243  7505  7527 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 11:25:47.243  7505  7527 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 11:25:47.243  7505  7527 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-29 11:25:47.243  7505  7527 D bt_userial_mct: userial_init
08-29 11:25:47.243  7505  7546 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-29 11:25:47.243  7505  7527 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 11:25:47.243  7505  7527 I bt_vendor: Starting hciattach daemon
08-29 11:25:47.243  7505  7527 I bt_vendor: try to set false
,08-29 11:25:47.243  7505  7527 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-29 11:25:47.243  7505  7527 I bt_vendor: Starting hciattach daemon
08-29 11:25:47.243  7505  7527 I bt_vendor: try to set true
,08-29 11:25:47.253  7550  7550 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-29 11:25:47.303  7556  7556 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-29 11:25:47.313  1016  2067 V SAMP_SPCM_test: CSC File load.. 
,08-29 11:25:47.313  7557  7557 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 11:25:47.323  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application,
,08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-29 11:25:47.333  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-29 11:25:47.333  7559  7559 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-29 11:25:47.343  7560  7560 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-29 11:25:47.343  7561  7561 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-29 11:25:47.353  7562  7562 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application,
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account,
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering,
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings,
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming,
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
,08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth,
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
,08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
,08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
,08-29 11:25:47.383  1016  2067 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
,08-29 11:25:47.383  1016  2067 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-29 11:25:47.383  1016  2067 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-29 11:25:47.383  1016  2067 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
,08-29 11:25:47.383  1016  2067 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
,08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-29 11:25:47.373  1016  2067 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-29 11:25:47.393  7565  7565 E Zygote  : MountEmulatedStorage()
,08-29 11:25:47.393  7565  7565 E Zygote  : v2
08-29 11:25:47.393  7565  7565 I libpersona: KNOX_SDCARD checking this for 1000
08-29 11:25:47.393  7565  7565 I libpersona: KNOX_SDCARD not a persona
08-29 11:25:47.393  7565  7565 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:47.393  1016  2067 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7565 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 11:25:47.393  7565  7565 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 11:25:47.403  7565  7565 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 11:25:47.423  7565  7565 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:47.423  7565  7565 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:47.443  7565  7565 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 11:25:47.483  1016  2067 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-29 11:25:47.483  1016  1016 I ActivityManager: Killing 7067:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-29 11:25:47.593  7581  7581 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,08-29 11:25:47.603  7582  7582 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 11:25:47.643  7505  7527 I bt_vendor: bluetooth satus is on
,08-29 11:25:47.643  7505  7548 D bt_userial_mct: userial_open(port:0)
08-29 11:25:47.643  7505  7548 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN,
,08-29 11:25:47.643  7505  7548 I bt_vendor: Done intiailizing UART
,08-29 11:25:47.653  7505  7548 I bt_vendor: Done intiailizing UART
08-29 11:25:47.653  7505  7548 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-29 11:25:47.653  7505  7548 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-29 11:25:47.653  7505  7546 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 11:25:47.653  7505  7546 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 11:25:47.653  7505  7546 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 11:25:47.653  7505  7546 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 11:25:47.653  7505  7546 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 11:25:47.653  7505  7546 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 11:25:47.653  7505  7546 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 11:25:47.653  7505  7546 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 11:25:47.653  7505  7546 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 11:25:47.653  7505  7546 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 11:25:47.653  7505  7546 I         : BTE_InitTraceLevels -- TRC_SAP
08-29 11:25:47.653  7505  7546 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 11:25:47.653  7505  7546 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 11:25:47.653  7505  7546 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 11:25:47.653  7505  7546 I         : BTE_InitTraceLevels -- TRC_BTAPP,
08-29 11:25:47.653  7505  7546 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 11:25:47.663  7505  7584 D bt_userial_mct: Entering userial_read_thread()
08-29 11:25:47.663  7505  7546 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-29 11:25:47.743   288   288 E SMD     : DCD OFF
,08-29 11:25:47.753  7505  7546 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-29 11:25:47.753  7505  7546 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4203ed1 
,08-29 11:25:47.753  7505  7546 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4203ed1 
,08-29 11:25:47.763  7505  7530 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-29 11:25:47.773  7505  7530 E bt-btif : Calling BTA_HhEnable
,08-29 11:25:47.773  7505  7530 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-29 11:25:47.773  7505  7530 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-29 11:25:47.773  7505  7530 E BluetoothServiceJni: populateRssiValuesNative
08-29 11:25:47.773  7505  7530 I bluedroid: getModelRssiValues
08-29 11:25:47.773  7505  7530 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-29 11:25:47.773  7505  7530 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 11:25:47.773  7505  7530 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-29 11:25:47.773  1016  1016 D SettingsProvider: name = bluetooth_name
,08-29 11:25:47.783  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:47.783  7505  7530 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
08-29 11:25:47.783  7505  7530 D BluetoothAdapterProperties: Scan Mode:20
08-29 11:25:47.783  7505  7530 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 11:25:47.783  7505  7530 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-29 11:25:47.783  7505  7530 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-29 11:25:47.783  7505  7530 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-29 11:25:47.783  7505  7530 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-29 11:25:47.783  7505  7530 E bt-btif : btif_sock_init: !vhci_init
08-29 11:25:47.783  7505  7530 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-29 11:25:47.783   315   315 I ServiceManager: Waiting for service AtCmdFwd...
08-29 11:25:47.783  7505  7530 D IOP_DB_BT: db_open: db_open : handle 3026419728l, read 13894 bytes onto local cache
08-29 11:25:47.783  7505  7530 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-29 11:25:47.783  7505  7530 D IOP_DB_BT: db_query: result 1
08-29 11:25:47.783  7505  7530 I         : iop_db_open: iop_db_open status 0
08-29 11:25:47.783  7505  7530 D bte_conf: Device ID record 1 : primary
08-29 11:25:47.783  7505  7530 D bte_conf:   vendorId            = 0075
08-29 11:25:47.783  7505  7530 D bte_conf:   vendorIdSource      = 0001
08-29 11:25:47.783  7505  7530 D bte_conf:   product             = 0100
08-29 11:25:47.783  7505  7530 D bte_conf:   version             = 0200
08-29 11:25:47.783  7505  7530 D bte_conf:   clientExecutableURL = 
08-29 11:25:47.783  7505  7530 D bte_conf:   serviceDescription  = 
08-29 11:25:47.783  7505  7530 D bte_conf:   documentationURL    = 
08-29 11:25:47.783  7505  7530 D bte_conf: bte_load_did_conf no section named DID2.
08-29 11:25:47.783  7505  7530 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 11:25:47.783  7505  7527 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-29 11:25:47.783  7505  7527 D BluetoothAdapterProperties: ScanMode =  20
08-29 11:25:47.793  7505  7527 D BluetoothAdapterProperties: State =  11
,08-29 11:25:47.793  7505  7584 E bt_mct  : hci lib postload completed,
,08-29 11:25:47.793  1016  1029 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 11:25:47.793  7505  7527 D BluetoothAdapterProperties: Setting state to 12
,08-29 11:25:47.793  7505  7527 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 11:25:47.803  7505  7530 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 11:25:47.803  7505  7530 D BluetoothAdapterProperties: Scan Mode:21
08-29 11:25:47.803  7505  7530 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 11:25:47.803  1016  1028 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-29 11:25:47.803  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:47.803  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:47.803  1016  1028 D SettingsProvider: selectionArgs: false
08-29 11:25:47.803  1016  1028 D SettingsProvider: selectionArgs: 1002
08-29 11:25:47.803  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:47.803  1016  1028 D SettingsProvider: ret = -1
,08-29 11:25:47.803  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:47.803  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:47.803  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:47.803  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:47.803  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:47.803  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:47.803  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:47.803  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:25:47.803  7505  7527 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 11:25:47.803  7505  7527 D BluetoothAdapterService: updateAdapterState state is 12
,08-29 11:25:47.803  1016  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:47.803  1016  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 11:25:47.813  1016  1480 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:47.813  6746  6746 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 11:25:47.813  1016  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:47.813  1016  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:47.813  1016  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-29 11:25:47.813  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 11:25:47.813  7505  7527 D BluetoothAdapterService: Autoconnection is available 
08-29 11:25:47.813  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-29 11:25:47.813  7505  7527 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-29 11:25:47.813  7505  7527 D BluetoothAdapterService: starting service from this receiver
08-29 11:25:47.813  1016  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 11:25:47.813  3306  3319 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 11:25:47.813  1016  1329 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 11:25:47.813  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 11:25:47.813  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:47.813  1016  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:47.813  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:47.823  7505  7527 I BluetoothAdapterState: Entering On State from state = 11
,08-29 11:25:47.833  7505  7505 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-29 11:25:47.943  6746  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:47.943  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:47.943  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:47.943  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 11:25:47.943  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:47.943  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:47.943  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:47.943  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:25:47.943  6746  6800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:25:47.953  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 11:25:47.953  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7770aa1 added. We now have 8 listener(s)
08-29 11:25:47.953  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:25:47.953  1016  1472 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 11:25:47.953  1016  1472 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-29 11:25:47.953  1016  1472 D SecContentProvider2: mCursor = null
,08-29 11:25:47.953  1016  1472 D WifiService: setWifiEnabled: false pid=6746, uid=10171
,08-29 11:25:47.963  1016  1472 D SettingsProvider: name = wifi_on
,08-29 11:25:47.963  6746  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:47.963  1016  1471 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 11:25:47.963  1016  1471 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 11:25:47.963  1016  1471 D SecContentProvider2: mCursor = null
,08-29 11:25:47.973  1016  1471 D WifiService: setWifiEnabled: true pid=6746, uid=10171
08-29 11:25:47.973  1016  1471 W ActivityManager: Permission Denial: getCurrentUser() from pid=6746, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-29 11:25:47.973  1016  1471 W WifiService: Failed getting userId using ActivityManagerNative
08-29 11:25:47.973  1016  1471 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6746, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 11:25:47.973  1016  1471 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 11:25:47.973  1016  1471 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 11:25:47.973  1016  1471 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 11:25:47.973  1016  1471 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 11:25:47.973  1016  1471 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-29 11:25:47.973  1016  1471 D SettingsProvider: name = wifi_on
,08-29 11:25:47.973  1016  1124 E WifiHW  : ##################### set firmware type 0 #####################
,08-29 11:25:47.983  1016  1045 I art     : Explicit concurrent mark sweep GC freed 31086(1771KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.536ms total 166.092ms
08-29 11:25:47.983  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-29 11:25:47.983  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 11:25:47.983  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:47.983  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:47.983  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:48.003  1432  3263 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 11:25:48.003  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 11:25:48.003  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 11:25:48.013  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:48.013  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:48.013  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:48.023  1432  3263 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 11:25:48.023  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 11:25:48.023  1016  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-29 11:25:48.023  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-29 11:25:48.023  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 11:25:48.023  1016  1016 D BluetoothA2dp: Proxy object connected
,08-29 11:25:48.033  1177  3896 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 11:25:48.033  1177  3896 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:48.033  7505  7505 I BluetoothPbapService: Handler(): got msg=1
,08-29 11:25:48.033  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 11:25:48.033  1016  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:48.033  1016  1471 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 11:25:48.033  1432  1440 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 11:25:48.033  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 11:25:48.033  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 11:25:48.033  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:48.033  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:48.033  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:48.033  1432  1440 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 11:25:48.043  3306  3306 D BluetoothPbap: Proxy object connected
08-29 11:25:48.043  3306  3306 D PbapServerProfile: Bluetooth service connected
,08-29 11:25:48.043  7417  7429 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 11:25:48.043  7417  7429 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:48.043  7505  7591 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-29 11:25:48.043  1432  3264 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 11:25:48.043  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 11:25:48.043  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 11:25:48.043  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:48.043  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:48.043  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:48.043  1432  3264 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 11:25:48.043  3306  6947 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 11:25:48.043  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-29 11:25:48.043  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 11:25:48.043  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:48.043  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:48.043  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:48.053  2001  7332 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 11:25:48.053  2001  7332 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:48.053  3306  3322 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 11:25:48.053  3306  3322 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:48.053  7505  7514 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 11:25:48.053  7505  7591 D BluetoothSocket: bindListen(): myUserId = 0
,08-29 11:25:48.053  7505  7591 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 11:25:48.053  3306  3319 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 11:25:48.053  3306  3306 D BluetoothInputDevice: Proxy object connected
08-29 11:25:48.053  3306  3306 D HidProfile: Bluetooth service connected
,08-29 11:25:48.053  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 11:25:48.053  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 11:25:48.053  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:48.053  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:48.053  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:48.063  7505  7591 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-29 11:25:48.063  7505  7591 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 11:25:48.063  7505  7591 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 11:25:48.063  7505  7591 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@143990c6
08-29 11:25:48.063  7505  7591 D BluetoothSocket: channel: 19
08-29 11:25:48.063  7505  7591 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-29 11:25:48.063  3306  3319 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 11:25:48.063  3306  3306 D HeadsetProfile: Bluetooth service connected
08-29 11:25:48.063  3306  6947 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 11:25:48.063  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-29 11:25:48.063  1016  3365 D SSRM:n  : SIOP:: AP = 340
,08-29 11:25:48.063  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 11:25:48.063  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:48.063  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:48.063  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:48.083  3306  3319 D BluetoothPan: Binding service...
,08-29 11:25:48.083  3306  3306 D BluetoothMap: Proxy object connected
08-29 11:25:48.083  3306  3306 D MapProfile: Bluetooth service connected
08-29 11:25:48.083  3306  3306 D BluetoothMap: getConnectedDevices()
,08-29 11:25:48.083  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 11:25:48.083  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 11:25:48.083  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:48.083  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:48.083  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:48.083  3306  3322 D Bluetoothsap: onBluetoothStateChange: up=true
,08-29 11:25:48.083  3306  3322 D Bluetoothsap: Binding service...
,08-29 11:25:48.083  3306  3306 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 11:25:48.083  3306  3322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-29 11:25:48.083  3306  3306 D PanProfile: Bluetooth service connected
08-29 11:25:48.083  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-29 11:25:48.083  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 11:25:48.083  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:48.083  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:48.083  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:48.083  3306  3322 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-29 11:25:48.083  7505  7531 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 11:25:48.083  7505  7531 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:48.093  1456  1991 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 11:25:48.093  1016  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 11:25:48.093  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 11:25:48.093  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:48.093  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:48.093  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:48.093  3306  3306 D Bluetoothsap: BluetoothSAP Proxy object connected
08-29 11:25:48.093  1456  1991 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 11:25:48.093  3306  3306 D SapProfile: Bluetooth service connected
08-29 11:25:48.093  1016  1045 D BluetoothPan: Binding service...
08-29 11:25:48.093  3306  3306 D Bluetoothsap: getConnectedDevices()
08-29 11:25:48.093  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 11:25:48.093  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 11:25:48.093  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 11:25:48.093  6746  6756 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 11:25:48.093  6746  6756 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:48.093  3306  6947 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 11:25:48.093  3306  6947 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 11:25:48.093  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 11:25:48.093  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 11:25:48.103  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:48.103  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:48.103  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:48.103  3306  3306 D BluetoothA2dp: Proxy object connected
,08-29 11:25:48.103  3306  3306 D A2dpProfile: Bluetooth service connected
08-29 11:25:48.103  1432  1447 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 11:25:48.103  1432  1447 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:48.103  1456  1929 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 11:25:48.103  1456  1929 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:48.103  1441  1462 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 11:25:48.103  1441  1462 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 11:25:48.103  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-29 11:25:48.103  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 11:25:48.103  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:48.103  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
08-29 11:25:48.103  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 11:25:48.113  1432  1432 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@123acd6d, true
,08-29 11:25:48.113  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-29 11:25:48.113  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 11:25:48.113  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 11:25:48.113  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-29 11:25:48.113  1432  1432 D BluetoothHeadset: registerMessageListener
,08-29 11:25:48.113  1872  1872 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 11:25:48.123  3306  3306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:48.123  1016  1551 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 11:25:48.123  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:48.123  1016  1329 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-29 11:25:48.123  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 11:25:48.123  1177  1765 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 11:25:48.123  1016  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 11:25:48.123  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 11:25:48.123  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:48.123  1177  1765 D BluetoothTile:  handleUpdatestate:false name:null
08-29 11:25:48.123  1016  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:48.123  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:48.133  7505  7514 D HeadsetService: registerMessageListener
,08-29 11:25:48.133  3306  3306 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-29 11:25:48.133  3306  3306 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-29 11:25:48.133  3306  3306 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-29 11:25:48.133  3306  3306 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-29 11:25:48.133  7505  7514 D HeadsetService: registerMessageListener
,08-29 11:25:48.133  7505  7536 D HeadsetStateMachine: Disconnected process message: 70
08-29 11:25:48.133  7505  7536 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@25c32887
,08-29 11:25:48.133  1432  1432 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-29 11:25:48.133  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-29 11:25:48.133  1177  1765 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 11:25:48.133  1432  1432 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-29 11:25:48.133  1432  1432 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-29 11:25:48.143  7505  7593 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-29 11:25:48.143  1432  1432 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-29 11:25:48.143  7505  7593 D BluetoothSocket: bindListen(): myUserId = 0
08-29 11:25:48.143  7505  7593 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:25:48.143  7505  7593 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-29 11:25:48.143  7505  7593 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 11:25:48.143  7505  7593 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 11:25:48.143  7505  7593 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29db93b4
,08-29 11:25:48.143  7505  7593 D BluetoothSocket: channel: 5
,08-29 11:25:48.143  7505  7536 D HeadsetStateMachine: Disconnected process message: 9
,08-29 11:25:48.143  7505  7536 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-29 11:25:48.153   283   723 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-29 11:25:48.153   283   723 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-29 11:25:48.153   283   723 V voice   : voice_set_parameters: exit with code(-2)
08-29 11:25:48.153   283   723 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-29 11:25:48.153   283   723 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-29 11:25:48.153   283   723 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-29 11:25:48.153   283   723 V audio_hw_primary: adev_set_parameters: exit
,08-29 11:25:48.153  3306  3306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 11:25:48.153  1016  1550 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 11:25:48.153  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-29 11:25:48.153  7505  7536 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-29 11:25:48.153  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:48.153  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:48.153  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 11:25:48.173  3306  3306 D DockEventReceiver: finishStartingService: stopping service
,08-29 11:25:48.173  3306  3306 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 11:25:48.183  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 11:25:48.183  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-29 11:25:48.183  7505  7505 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d9e8c8c
08-29 11:25:48.183  7505  7505 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 11:25:48.193  1016  1329 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 11:25:48.193  1016  1329 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-29 11:25:48.193  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:48.193  1016  1329 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:48.193  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 11:25:48.203  2001  2001 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 11:25:48.203  1016  1551 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 11:25:48.213  1016  1551 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-29 11:25:48.213  1016  1551 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:48.213  1016  1551 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 11:25:48.213  1016  1551 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:48.223  2001  2001 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 11:25:48.223  2001  7600 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-29 11:25:48.223  1016  1551 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-29 11:25:48.223  1016  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-29 11:25:48.233  1016  1472 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:48.233  1016  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:48.233  1016  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:48.233  7505  7609 D BluetoothSocket: bindListen(): myUserId = 0
,08-29 11:25:48.233  7505  7609 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 11:25:48.243  7505  7609 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-29 11:25:48.243  7505  7609 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 11:25:48.243  7505  7609 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 11:25:48.243  7505  7609 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a783720
,08-29 11:25:48.243  7505  7609 D BluetoothSocket: channel: 12
08-29 11:25:48.243  7505  7609 I BtOppRfcommListener: Accept thread started.
,08-29 11:25:48.243  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 11:25:48.243  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:48.243  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:48.243  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:48.253  2001  7600 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-29 11:25:48.353  1016  1043 D Tethering: interfaceAdded wlan0
,08-29 11:25:48.363  1016  1129 E Tethering: No numeric data
,08-29 11:25:48.363  1016  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 11:25:48.363  1016  1129 D Tethering: clearTetheredNotification()
,08-29 11:25:48.363  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:48.363  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 11:25:48.373  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 11:25:48.373  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 11:25:48.373  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 11:25:48.373  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 11:25:48.373  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 11:25:48.373  1177  1177 D HotspotTile: updateTetherState():false, false
08-29 11:25:48.373  1016  1129 D Tethering: InitialState.processMessage what=4
08-29 11:25:48.373  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 11:25:48.383  1016  1121 V NetworkStats: performPollLocked() took 11ms
08-29 11:25:48.383  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:48.383  1016  1129 E Tethering: No numeric data
,08-29 11:25:48.383  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:48.383  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:48.383  1016  1043 D Tethering: interfaceAdded p2p0
,08-29 11:25:48.383  1016  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-29 11:25:48.383  1016  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
08-29 11:25:48.383  1016  1129 D Tethering: clearTetheredNotification()
08-29 11:25:48.393  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
08-29 11:25:48.393  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:48.393  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 11:25:48.393  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 11:25:48.393  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 11:25:48.393  1177  1177 D HotspotTile: updateTetherState():false, false
,08-29 11:25:48.393  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 11:25:48.393  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 11:25:48.393  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 11:25:48.403  1016  1121 V NetworkStats: performPollLocked() took 10ms
08-29 11:25:48.403  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:48.403   278  1015 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-29 11:25:48.403   278  1015 D SoftapController: Softap fwReload - Ok
,08-29 11:25:48.403  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:48.403  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:48.403   278  1015 D CommandListener: Setting iface cfg,
08-29 11:25:48.403   278  1015 D CommandListener: Trying to bring down wlan0
08-29 11:25:48.403   278  1015 D CommandListener: Clearing all IP addresses on wlan0
,08-29 11:25:48.413  1016  1124 E WifiHW  : supplicant_name : p2p_supplicant
,08-29 11:25:48.453  7611  7611 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-29 11:25:48.453  7611  7611 I wpa_supplicant: Successfully initialized wpa_supplicant
08-29 11:25:48.453  7611  7611 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-29 11:25:48.463  7611  7611 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-29 11:25:48.463   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7611,
08-29 11:25:48.463   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 11:25:48.473  7611  7611 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-29 11:25:48.473  7611  7611 I wpa_supplicant: ssSupport state is = 1
08-29 11:25:48.473  7611  7611 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,08-29 11:25:48.473  7611  7611 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-29 11:25:48.473   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7611,
08-29 11:25:48.473   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-29 11:25:48.513  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-29 11:25:48.513  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 11:25:48.513  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:48.513  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:48.513  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:48.513  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:48.523  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:48.523  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:48.523  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2),
08-29 11:25:48.523  1177  1177 D HotspotTile: onReceive : 2, 0,
08-29 11:25:48.523  1016  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 11:25:48.523  1177  1765 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 11:25:48.523  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:48.523  3306  3306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:25:48.533  1016  1479 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 11:25:48.533  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 11:25:48.533  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:48.533  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:48.533  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 11:25:48.533  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 11:25:48.533  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 11:25:48.533  6555  6555 D SecurityLogAgent: StateMachine : Current State = 1
08-29 11:25:48.533  6555  6555 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-29 11:25:48.533  1598  1598 I Hs20UtilService: Starting #19
08-29 11:25:48.533  1598  1647 I Hs20UtilService: Message received 5011
,08-29 11:25:48.633   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-29 11:25:48.633  7611  7611 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-29 11:25:48.673  7611  7611 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-29 11:25:48.673  7611  7611 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-29 11:25:48.683  7611  7611 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-29 11:25:48.683   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7611
08-29 11:25:48.683   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-29 11:25:48.683  7611  7611 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 11:25:48.683  7611  7611 I wpa_supplicant: ssSupport state is = 1
08-29 11:25:48.693  7611  7611 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 11:25:48.693  7611  7611 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-29 11:25:48.693  7611  7611 E wpa_supplicant: SIM READ ERROR
08-29 11:25:48.693  7611  7611 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 11:25:48.693  7611  7611 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 11:25:48.693  7611  7611 E wpa_supplicant: SIM READ ERROR
08-29 11:25:48.693  7611  7611 I wpa_supplicant: Blacklist: Clear (all) 
08-29 11:25:48.693  7611  7611 I wpa_supplicant: wpa_default_ap_write_once,
08-29 11:25:48.693  7611  7611 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 11:25:48.693  7611  7611 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 11:25:48.693  7611  7611 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-29 11:25:48.693  7611  7611 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 11:25:48.693  7611  7611 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,08-29 11:25:48.693  7611  7611 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 11:25:48.693  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 11:25:48.693  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 11:25:48.693  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 11:25:48.783  7611  7611 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-29 11:25:48.783   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-29 11:25:48.973  7611  7611 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-29 11:25:48.973  7611  7611 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-29 11:25:48.983  7611  7611 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-29 11:25:48.983   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7611
08-29 11:25:48.983   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-29 11:25:48.983  7611  7611 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 11:25:48.983  7611  7611 I wpa_supplicant: ssSupport state is = 1
08-29 11:25:48.993  7611  7611 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-29 11:25:48.993  7611  7611 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-29 11:25:49.003  7611  7611 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-29 11:25:49.003   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7611
08-29 11:25:49.003   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-29 11:25:49.003  7611  7611 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 11:25:49.003  7611  7611 I wpa_supplicant: ssSupport state is = 1,
08-29 11:25:49.003  7611  7611 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 11:25:49.003  7611  7611 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 11:25:49.003  7611  7611 E wpa_supplicant: SIM READ ERROR
08-29 11:25:49.003  7611  7611 I wpa_supplicant: wpa_default_ap_write_once
08-29 11:25:49.003  7611  7611 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-29 11:25:49.003  7611  7611 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 11:25:49.003  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-29 11:25:49.003  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 11:25:49.003  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
08-29 11:25:49.013  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 11:25:49.013  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-29 11:25:49.013  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 11:25:49.053  7611  7611 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-29 11:25:49.053  7611  7611 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-29 11:25:49.153  7611  7611 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-29 11:25:49.153  7611  7611 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-29 11:25:49.153  7611  7611 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-29 11:25:49.163  1016  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-29 11:25:49.173  1016  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 11:25:49.173  7611  7611 I wpa_supplicant: HOTSPOT20_ENABLE called
08-29 11:25:49.173  7611  7611 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 11:25:49.173  7611  7611 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 11:25:49.173  7611  7611 E wpa_supplicant: SIM READ ERROR,
08-29 11:25:49.173  7611  7611 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 11:25:49.183  7611  7611 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-29 11:25:49.193  7611  7611 I wpa_supplicant: Skip scan - bUseNetwork false
08-29 11:25:49.193  1016  1124 D WifiConfigStore: Loading config and enabling all networks 
08-29 11:25:49.193  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 11:25:49.193  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 11:25:49.193  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:49.193  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:49.193  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:49.193  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:49.193  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 11:25:49.193  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-29 11:25:49.193  1177  1765 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 11:25:49.203  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:25:49.203  1177  1177 D HotspotTile: onReceive : 3, 0
,08-29 11:25:49.203  3306  3306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 11:25:49.213  1016  1472 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 11:25:49.213  1016  1472 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 11:25:49.213  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:49.213  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:49.213  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:49.213  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:49.213  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:49.213  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:49.213  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:49.213  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:25:49.213  1016  1124 E WifiConfigStore: Not a HS20
,08-29 11:25:49.213  1016  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 11:25:49.213  1016  1472 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:49.213  1016  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:49.213  1016  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 11:25:49.213  6746  6746 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:25:49.223  1598  1598 I Hs20UtilService: Starting #20
,08-29 11:25:49.223  1016  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
08-29 11:25:49.223  1598  1647 I Hs20UtilService: Message received 5011
,08-29 11:25:49.223  1016  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-29 11:25:49.223  7611  7611 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-29 11:25:49.223  7611  7611 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-29 11:25:49.223  7611  7611 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 11:25:49.223  7611  7611 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 11:25:49.223  7611  7611 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-29 11:25:49.223  7611  7611 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-29 11:25:49.223  7611  7611 I wpa_supplicant: First Scan Start
,08-29 11:25:49.223  7611  7611 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-29 11:25:49.223  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 11:25:49.223  6555  6555 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-29 11:25:49.223  6555  6555 D SecurityLogAgent: StateMachine : Current State = 1
08-29 11:25:49.223  1016  1124 D WifiNative-wlan0: Setting external_sim to 1
08-29 11:25:49.223  1016  1124 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 11:25:49.223  1016  1124 I WifiNative-HAL: startHal
08-29 11:25:49.223  1016  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9d3f888c
,08-29 11:25:49.223  1016  1124 I WifiNative-HAL: Could not start hal
08-29 11:25:49.223  6997  6997 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 11:25:49.233  6555  6555 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 11:25:49.233  1016  1124 E WifiNative-wlan0: do suspend true
,08-29 11:25:49.233  1016  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-29 11:25:49.233  1016  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-29 11:25:49.233   278  1015 D CommandListener: Setting iface cfg
08-29 11:25:49.233   278  1015 D CommandListener: Trying to bring up p2p0
,08-29 11:25:49.233  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 11:25:49.243  1016  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:49.243  1016  1148 I WifiNative-HAL: startHal
08-29 11:25:49.243  1016  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9e3a29bc
08-29 11:25:49.243  1016  1148 I WifiNative-HAL: Could not start hal
08-29 11:25:49.243  1016  1148 E WifiScanningService: could not start HAL
08-29 11:25:49.243  1016  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 11:25:49.243  1016  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 11:25:49.243  1016  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 11:25:49.243  1016  1124 E WifiNative-wlan0: invaild command id : 215
,08-29 11:25:49.243  1016  1123 D WifiP2pService: P2pEnablingState
08-29 11:25:49.243  1016  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
08-29 11:25:49.243  1016  1016 D RttService: SCAN_AVAILABLE : 3
08-29 11:25:49.243  1016  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 11:25:49.243  1016  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 11:25:49.243  1016  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,08-29 11:25:49.243  1016  1124 E WifiNative-wlan0: invaild command id : 215
,08-29 11:25:49.243  1016  1123 D WifiP2pService: P2p socket connection successful
,08-29 11:25:49.243  7611  7611 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-29 11:25:49.243  1016  1123 D WifiP2pService: P2pEnabledState
,08-29 11:25:49.243  1016  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-29 11:25:49.243  7611  7611 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 11:25:49.243  7611  7611 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-29 11:25:49.243  1016  1126 E ConnectivityService: updateNetworkInfo()
08-29 11:25:49.243  1016  1124 E WifiStateMachine: Failed to set frequency band 0
,08-29 11:25:49.253  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 11:25:49.253  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-29 11:25:49.253  1016  1124 D SecContentProvider2: mCursor = null
08-29 11:25:49.253  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-29 11:25:49.253  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 11:25:49.253  1016  1046 D WifiDisplayController: disconnect
08-29 11:25:49.253  1016  1046 D WifiDisplayController: updateConnection
08-29 11:25:49.253  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 11:25:49.253  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 11:25:49.253  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 11:25:49.253  1016  1124 D SecContentProvider2: mCursor = null
,08-29 11:25:49.253  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
08-29 11:25:49.253  1016  1029 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 11:25:49.253  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-29 11:25:49.253  1016  1123 D WifiNative-p2p0: p2pGetDeviceAddress
08-29 11:25:49.253  1016  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-29 11:25:49.263  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 11:25:49.263  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-29 11:25:49.263  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 11:25:49.263  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 11:25:49.263  1016  1123 D WifiP2pService: DeviceAddress: 0a:76:28,
08-29 11:25:49.263  3306  3306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 11:25:49.263  3306  3306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 11:25:49.263  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 11:25:49.263  1016  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-29 11:25:49.263  1016  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-29 11:25:49.263  1016  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-29 11:25:49.263  1016  1046 D WifiDisplayController:  secondary type: null
08-29 11:25:49.263  1016  1046 D WifiDisplayController:  wps: 0
08-29 11:25:49.263  1016  1046 D WifiDisplayController:  grpcapab: 0
08-29 11:25:49.263  1016  1046 D WifiDisplayController:  devcapab: 0
08-29 11:25:49.263  1016  1046 D WifiDisplayController:  status: 3
08-29 11:25:49.263  1016  1046 D WifiDisplayController:  wfdInfo: null
08-29 11:25:49.263  1016  1046 D WifiDisplayController:  groupownerAddress: null
08-29 11:25:49.263  1016  1046 D WifiDisplayController:  GOdeviceName: null
08-29 11:25:49.263  1016  1046 D WifiDisplayController:  interfaceAddress: ,
08-29 11:25:49.263  1016  1046 D WifiDisplayController:  SConnectInfo : null
,08-29 11:25:49.263  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 11:25:49.273  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 11:25:49.273  3306  3306 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 11:25:49.273  3306  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 11:25:49.273  6948  6948 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 11:25:49.273  6948  6948 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-29 11:25:49.273  6948  6948 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 11:25:49.273  6967  6967 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 11:25:49.283  1016  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-29 11:25:49.283  1016  1123 D WifiP2pService: InactiveState
,08-29 11:25:49.283  1016  1123 D WifiP2pService: InactiveState{ what=143376 }
,08-29 11:25:49.283  1016  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 11:25:49.283  7611  7611 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-29 11:25:49.293  1016  1123 D WifiP2pService: InactiveState{ what=143376 },
08-29 11:25:49.293  1016  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 11:25:49.373  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 11:25:49.373  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
08-29 11:25:49.373  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 11:25:49.983  6746  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-29 11:25:49.983  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:49.983  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:49.983  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:49.983  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:49.983  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:49.983  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:49.983  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:25:49.983  6746  6800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:25:49.993  6746  6800 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 11:25:49.993  6746  6800 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 11:25:49.993  6746  6800 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@112430bc Bundle[{}]
,08-29 11:25:49.993  6746  6800 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 11:25:49.993  6746  6800 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-29 11:25:49.993  6746  6800 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 11:25:50.003  6746  6800 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 11:25:50.003  6746  6800 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 11:25:50.003  6746  6800 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 11:25:50.003  6746  6800 I System.out: Running OutgoingSocketThread
,08-29 11:25:50.013  6746  7619 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1350)
,08-29 11:25:50.013  6746  7619 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57042
,08-29 11:25:50.013  6746  7619 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 11:25:50.403  7611  7611 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
08-29 11:25:50.403  7611  7611 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 11:25:50.403  7611  7611 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-29 11:25:50.403  7611  7611 I wpa_supplicant: Trying to associate with  'G700'
08-29 11:25:50.403  7611  7611 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-29 11:25:50.403  7611  7611 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-29 11:25:50.403  1016  7616 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-29 11:25:50.423  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 11:25:50.433  1016  1124 D SecContentProvider2: mCursor = null
,08-29 11:25:50.533  7611  7611 E wpa_supplicant: Cmd 35605 not handled
,08-29 11:25:50.533  7611  7611 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 11:25:50.533  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 11:25:50.533  7611  7611 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-29 11:25:50.533  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 11:25:50.533  7611  7611 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-29 11:25:50.533  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 11:25:50.533  7611  7611 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-29 11:25:50.533  7611  7611 I wpa_supplicant: Associated with F4.99.3E
08-29 11:25:50.533  7611  7611 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-29 11:25:50.533  7611  7611 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-29 11:25:50.533  7611  7611 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-29 11:25:50.533  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 11:25:50.543  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 11:25:50.533  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 11:25:50.543  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true,
08-29 11:25:50.543  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
08-29 11:25:50.543  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-29 11:25:50.543  1016  1129 E Tethering: No numeric data
08-29 11:25:50.543  1016  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 11:25:50.543  1016  1129 D Tethering: clearTetheredNotification()
,08-29 11:25:50.543  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:50.543  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-29 11:25:50.543  7611  7611 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-29 11:25:50.543  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 11:25:50.543  7611  7611 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-29 11:25:50.543  1016  1124 D SecContentProvider2: mCursor = null,
08-29 11:25:50.553  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 11:25:50.553  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 11:25:50.553  1177  1177 D HotspotTile: updateTetherState():false, false
,08-29 11:25:50.553  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,08-29 11:25:50.553  7611  7611 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-29 11:25:50.553  7611  7611 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-29 11:25:50.553  7611  7611 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 11:25:50.553  7611  7611 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-29 11:25:50.553  7611  7611 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=],
08-29 11:25:50.563  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 11:25:50.553  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 11:25:50.553  1016  1124 D SecContentProvider2: mCursor = null
08-29 11:25:50.553  7611  7611 I wpa_supplicant: Blacklist: Clear (temp) 
08-29 11:25:50.553  7611  7611 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-29 11:25:50.563  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 11:25:50.563  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
08-29 11:25:50.563  1016  1121 V NetworkStats: performPollLocked() took 18ms
08-29 11:25:50.563  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:50.563  1016  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-29 11:25:50.563  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:50.563  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:50.563  1016  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,08-29 11:25:50.573  1016  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-29 11:25:50.573  1016  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-29 11:25:50.573  1016  1126 E ConnectivityService: updateNetworkInfo()
08-29 11:25:50.573  1016  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-29 11:25:50.573  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 11:25:50.573  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 11:25:50.573  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:50.573  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:50.583  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:50.583  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:50.583  1016  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:25:50.583  1016  1471 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 11:25:50.583  1016  1471 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 11:25:50.583  1016  1471 W ActivityManager: userId = 0, bbcId = -10000,
08-29 11:25:50.583  1016  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-29 11:25:50.583  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 11:25:50.593  1598  1598 I Hs20UtilService: Starting #21,
,08-29 11:25:50.593  1598  1647 I Hs20UtilService: Message received 5007
,08-29 11:25:50.593  1016  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 11:25:50.593  3306  3306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 11:25:50.603  3306  3306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 11:25:50.603  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 11:25:50.603  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 11:25:50.603  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 11:25:50.603  3306  3306 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 11:25:50.603  3306  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 11:25:50.613   278  1015 D CommandListener: Setting iface cfg
,08-29 11:25:50.613  1016  1124 E WifiStateMachine: Start Dhcp Watchdog 3,
,08-29 11:25:50.613  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 11:25:50.623  1016  1124 D SecContentProvider2: mCursor = null
,08-29 11:25:50.623  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 11:25:50.623  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 11:25:50.623  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:50.623  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:50.623  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:50.633  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:50.633  1016  1124 E WifiNative-wlan0: do suspend false
,08-29 11:25:50.633  1016  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-29 11:25:50.633  1016  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 11:25:50.643  1016  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 11:25:50.643  1016  1124 D SecContentProvider2: mCursor = null
,08-29 11:25:50.743   288   288 E SMD     : DCD OFF,
,08-29 11:25:50.863  7624  7624 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 11:25:50.873  7624  7624 I dhcpcd  : version 5.5.6 starting,
,08-29 11:25:50.873  7624  7624 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 11:25:50.933  7624  7624 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-29 11:25:50.933  7624  7624 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-29 11:25:50.933  7624  7624 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-29 11:25:50.933  7624  7624 I dhcpcd  : bssid match
,08-29 11:25:50.933  7624  7624 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-29 11:25:50.993  7624  7624 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-29 11:25:51.013  6746  6800 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1351),
08-29 11:25:51.013  6746  6800 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1351)
08-29 11:25:51.013  6746  6800 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1356)
08-29 11:25:51.013  6746  6800 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...,
08-29 11:25:51.013  6746  6800 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1357)
08-29 11:25:51.013  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:51.013  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c72c4c6 added. We now have 2 listener(s)
,08-29 11:25:51.023  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 11:25:51.023  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:25:51.023  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:51.023  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:51.023  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bf64c87 added. We now have 9 listener(s)
08-29 11:25:51.023  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:25:51.023  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 11:25:51.033  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:25:51.033  6746  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:51.033  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:51.033  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:51.033  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:51.033  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:51.033  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:51.033  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:51.033  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:25:51.033  6746  6800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:25:51.043  6746  6800 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:25:51.043  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:51.043  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1158afdd added. We now have 3 listener(s)
,08-29 11:25:51.043  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:51.043  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:51.043  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 11:25:51.043  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:25:51.043  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 11:25:51.043  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:51.043  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a466752 added. We now have 10 listener(s)
,08-29 11:25:51.053  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:51.053  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:51.053  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:51.053  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:51.053  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:51.053  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:51.053  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:51.053  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:51.053  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c72c4c6 removed from the list
08-29 11:25:51.053  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:51.053  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bf64c87 removed from the list
08-29 11:25:51.053  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:51.053  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:51.053  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:51.053  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:51.053  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:51.053  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:51.053  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:51.053  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bf64c87 not in the list
08-29 11:25:51.053  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:25:51.053  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:51.053  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:51.053  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:51.053  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:51.053  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a466752 removed from the list
08-29 11:25:51.053  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:51.053  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:25:51.053  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:51.053  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:51.053  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1158afdd removed from the list
08-29 11:25:51.053  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:51.053  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee12a23 added. We now have 2 listener(s)
,08-29 11:25:51.053  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 11:25:51.053  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:25:51.053  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:51.053  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:51.053  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ac7cb20 added. We now have 9 listener(s)
08-29 11:25:51.053  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:51.063  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 11:25:51.063  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-29 11:25:51.063  6746  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:51.063  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:51.063  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:51.063  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:51.063  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:51.063  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:51.063  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:51.063  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:25:51.073  6746  6800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:25:51.083  6746  6800 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:25:51.083  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:51.083  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a3fa69e added. We now have 3 listener(s)
,08-29 11:25:51.083  7624  7624 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-29 11:25:51.083  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 11:25:51.083  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:25:51.083  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:51.083  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:51.083  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e12457f added. We now have 10 listener(s)
08-29 11:25:51.083  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:51.083  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:25:51.083  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:25:51.083  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:25:51.083  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:51.083  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 11:25:51.093  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:51.093  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:51.093  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 11:25:51.103  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 11:25:51.103  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 11:25:51.113  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 11:25:51.113  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 11:25:51.113  6746  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 11:25:51.113  7505  7514 D BtGatt.GattService: registerClient() - UUID=c7828612-9f06-4d4a-b60f-6cf9408c3038
,08-29 11:25:51.153  1016  1329 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 11:25:51.153  1016  1329 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 11:25:51.153  1016  1329 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 11:25:51.153  1016  1329 D BatteryService: stay LED for fully charged
08-29 11:25:51.153  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 11:25:51.153  1016  1016 I MotionRecognitionService: Plugged
,08-29 11:25:51.153  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 11:25:51.163  7505  7530 D BtGatt.GattService: onClientRegistered() - UUID=c7828612-9f06-4d4a-b60f-6cf9408c3038, clientIf=6
,08-29 11:25:51.163  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 11:25:51.163  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 11:25:51.163  6746  6756 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 11:25:51.163  7505  7513 D BtGatt.GattService: start scan with filters
,08-29 11:25:51.163  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 11:25:51.163  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 11:25:51.163  7505  7535 D BtGatt.ScanManager: handling starting scan,
08-29 11:25:51.173  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 11:25:51.173  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 11:25:51.173  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 11:25:51.173  7505  7535 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d9e8c8c
,08-29 11:25:51.173  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 11:25:51.183  7505  7530 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-29 11:25:51.183  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:51.183  7505  7535 D BtGatt.ScanManager: allow scan with filters
08-29 11:25:51.183  7505  7535 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-29 11:25:51.183  7505  7535 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-29 11:25:51.183  7505  7530 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-29 11:25:51.183  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:51.193  7505  7505 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 11:25:51.193  7505  7535 D BtGatt.ScanManager: Starting BLE batch scan
08-29 11:25:51.193  7505  7535 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 11:25:51.193  7505  7536 D HeadsetStateMachine: Disconnected process message: 10
,08-29 11:25:51.193  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 11:25:51.193  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 11:25:51.193  6746  6746 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:25:51.193  7505  7530 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-29 11:25:51.193  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,08-29 11:25:51.193  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-29 11:25:51.193  1177  1177 D SViewCoverView: level :100 plugged : 2
,08-29 11:25:51.203  7505  7530 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 11:25:51.203  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:51.203  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 11:25:51.203  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 11:25:51.203  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 11:25:51.203  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 11:25:51.213  6746  6800 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 11:25:51.213  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:51.213  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 11:25:51.213  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:51.213  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 11:25:51.213  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 11:25:51.213  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:25:51.213  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 11:25:51.213  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 11:25:51.213  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 11:25:51.213  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 11:25:51.213  7505  7531 D BtGatt.GattService: stopScan() - queue size =1
,08-29 11:25:51.213  7505  7535 D BtGatt.ScanManager: filter size is 1
,08-29 11:25:51.213  7505  7592 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 11:25:51.213  7505  7535 D BtGatt.ScanManager: delete FilterIndex - 3
,08-29 11:25:51.213  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:51.213  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 11:25:51.213  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 11:25:51.213  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 11:25:51.213  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 11:25:51.223  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:25:51.223  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-29 11:25:51.223  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 11:25:51.223  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:25:51.223  7505  7530 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 11:25:51.223  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:51.223  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:25:51.223  6746  6746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 11:25:51.223  6746  6746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:25:51.223  6746  6746 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:25:51.223  7505  7535 D BtGatt.ScanManager: stopping BLe Batch
,08-29 11:25:51.233  7505  7530 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-29 11:25:51.233  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:51.233  7505  7535 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 11:25:51.233  7505  7530 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 11:25:51.233  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:51.233  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:51.233  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:51.233  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:51.233  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:51.233  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:51.233  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:51.233  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee12a23 removed from the list
08-29 11:25:51.233  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:51.233  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ac7cb20 removed from the list
08-29 11:25:51.233  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:51.233  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:51.233  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:51.233  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:51.233  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:51.233  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-29 11:25:51.233  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:51.233  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:51.233  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ac7cb20 not in the list
,08-29 11:25:51.233  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:51.233  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:51.233  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:51.233  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:51.233  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-29 11:25:51.233  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e12457f removed from the list
08-29 11:25:51.233  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:51.233  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:51.233  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:51.233  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 11:25:51.233  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a3fa69e removed from the list
08-29 11:25:51.233  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:51.233  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90fba9b added. We now have 2 listener(s)
,08-29 11:25:51.243  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-29 11:25:51.243  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:25:51.243  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:51.243  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:51.243  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@156fde38 added. We now have 9 listener(s)
08-29 11:25:51.243  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:51.243  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 11:25:51.253  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:25:51.263  6746  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-29 11:25:51.263  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:51.263  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:51.263  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:51.263  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:51.263  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:51.263  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:51.263  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:25:51.273  6746  6800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-29 11:25:51.273  6746  6800 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 11:25:51.273  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:51.273  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39dbeb76 added. We now have 3 listener(s)
,08-29 11:25:51.273  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 11:25:51.273  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:25:51.273  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:51.273  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:51.273  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37a56577 added. We now have 10 listener(s)
08-29 11:25:51.273  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:51.273  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:25:51.273  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:25:51.273  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:25:51.273  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:25:51.273  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:51.273  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 11:25:51.273  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-29 11:25:51.273  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:51.283  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:51.293  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,08-29 11:25:51.293  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-29 11:25:51.303  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 11:25:51.303  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 11:25:51.303  6746  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 11:25:51.303  7505  7592 D BtGatt.GattService: registerClient() - UUID=cb528515-b614-4b72-9b35-f9c5b39ffa94
,08-29 11:25:51.343  7505  7530 D BtGatt.GattService: onClientRegistered() - UUID=cb528515-b614-4b72-9b35-f9c5b39ffa94, clientIf=6
,08-29 11:25:51.343  6746  6754 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 11:25:51.343  7505  7514 D BtGatt.GattService: start scan with filters
,08-29 11:25:51.343  7505  7535 D BtGatt.ScanManager: handling starting scan
,08-29 11:25:51.343  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 11:25:51.343  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 11:25:51.343  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 11:25:51.343  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 11:25:51.353  7505  7530 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 11:25:51.353  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:51.353  7505  7535 D BtGatt.ScanManager: allow scan with filters
,08-29 11:25:51.353  7505  7535 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 11:25:51.353  7505  7535 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-29 11:25:51.353  7505  7530 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 11:25:51.353  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:51.353  7505  7535 D BtGatt.ScanManager: Starting BLE batch scan
08-29 11:25:51.353  7505  7535 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 11:25:51.363  7505  7530 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 11:25:51.363  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:51.363  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 11:25:51.363  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 11:25:51.363  6746  6746 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 11:25:51.363  7505  7530 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 11:25:51.363  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:51.363  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 11:25:51.373  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 11:25:51.373  6746  6800 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 11:25:51.373  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:25:51.373  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:51.373  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 11:25:51.373  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 11:25:51.373  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:51.373  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 11:25:51.373  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:51.373  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90fba9b removed from the list
,08-29 11:25:51.373  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:51.373  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@156fde38 removed from the list
,08-29 11:25:51.373  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:51.373  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:25:51.373  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:25:51.373  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 11:25:51.373  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:25:51.383  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:25:51.383  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 11:25:51.383  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:51.383  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 11:25:51.383  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@156fde38 not in the list
08-29 11:25:51.383  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 11:25:51.383  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:25:51.383  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 11:25:51.383  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 11:25:51.383  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 11:25:51.383  7505  7514 D BtGatt.GattService: stopScan() - queue size =1
,08-29 11:25:51.383  7505  7535 D BtGatt.ScanManager: filter size is 1
08-29 11:25:51.383  7505  7535 D BtGatt.ScanManager: delete FilterIndex - 4
,08-29 11:25:51.383  7505  7513 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 11:25:51.383  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:51.383  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 11:25:51.383  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 11:25:51.383  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 11:25:51.383  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 11:25:51.383  7505  7530 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 11:25:51.383  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:51.383  7505  7535 D BtGatt.ScanManager: stopping BLe Batch
,08-29 11:25:51.393  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:25:51.393  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 11:25:51.393  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 11:25:51.393  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 11:25:51.393  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:51.393  7505  7530 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 11:25:51.393  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:51.393  7505  7535 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 11:25:51.393  6746  6746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:25:51.393  6746  6746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:25:51.393  6746  6746 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 11:25:51.393  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:51.393  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:51.393  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:51.393  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37a56577 removed from the list
08-29 11:25:51.393  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:51.393  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:51.393  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:51.393  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:51.393  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39dbeb76 removed from the list
08-29 11:25:51.393  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:51.393  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1880e213 added. We now have 2 listener(s)
,08-29 11:25:51.393  7505  7530 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 11:25:51.393  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:51.403  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 11:25:51.403  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:25:51.403  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 11:25:51.403  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:51.403  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21743c50 added. We now have 9 listener(s)
08-29 11:25:51.403  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:51.403  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 11:25:51.403  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 11:25:51.403  6746  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:51.403  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:51.403  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:51.403  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:51.403  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:51.403  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 11:25:51.403  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 11:25:51.403  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 11:25:51.413  6746  6800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 11:25:51.413  6746  6800 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:25:51.413  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:51.413  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:51.413  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:51.413  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@370f34e added. We now have 3 listener(s)
,08-29 11:25:51.413  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 11:25:51.413  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 11:25:51.413  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:51.423  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:51.423  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d8d8c6f added. We now have 10 listener(s)
08-29 11:25:51.423  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 11:25:51.423  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:25:51.423  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 11:25:51.423  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 11:25:51.423  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:51.423  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 11:25:51.423  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 11:25:51.423  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 11:25:51.423  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 11:25:51.433  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 11:25:51.433  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 11:25:51.433  6746  6800 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 11:25:51.433  7505  7514 D BtGatt.GattService: registerClient() - UUID=37544ba4-ab16-44e6-bd9e-37643179603a
,08-29 11:25:51.463  1016  1124 E WifiNative-wlan0: do suspend true
,08-29 11:25:51.473  7505  7530 D BtGatt.GattService: onClientRegistered() - UUID=37544ba4-ab16-44e6-bd9e-37643179603a, clientIf=6
,08-29 11:25:51.473  6746  6791 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 11:25:51.473  7505  7513 D BtGatt.GattService: start scan with filters
,08-29 11:25:51.473  7505  7535 D BtGatt.ScanManager: handling starting scan
,08-29 11:25:51.483  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 11:25:51.483  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 11:25:51.483  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 11:25:51.483  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 11:25:51.483  7505  7530 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 11:25:51.483  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:51.483  7505  7535 D BtGatt.ScanManager: allow scan with filters
08-29 11:25:51.483  7505  7535 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 11:25:51.483  7505  7535 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-29 11:25:51.483  7505  7530 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 11:25:51.483  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:51.483  7505  7535 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 11:25:51.483  7505  7535 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 11:25:51.493  1016  1123 D WifiP2pService: InactiveState{ what=143375 }
,08-29 11:25:51.493  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 11:25:51.493  1016  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 11:25:51.493  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 11:25:51.493  1016  1124 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 11:25:51.493  6746  6746 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 11:25:51.493  1016  1124 E WifiStateMachine: VerifyingLinkState enter
,08-29 11:25:51.493  7505  7530 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-29 11:25:51.493  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:51.493  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 11:25:51.493  7505  7530 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-29 11:25:51.503  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 11:25:51.503  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 11:25:51.503  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:51.503  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:51.503  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:51.503  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:51.503  1016  1126 E ConnectivityService: updateNetworkInfo()
,08-29 11:25:51.503  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 11:25:51.503  1016  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-29 11:25:51.503  1016  1126 D ConnectivityService: Adding iface wlan0 to network 504
,08-29 11:25:51.513  1016  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-29 11:25:51.513  1016  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-29 11:25:51.513  1016  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-29 11:25:51.513  1016  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-29 11:25:51.513  1016  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-29 11:25:51.523  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 11:25:51.523  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 11:25:51.523  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:51.523  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 11:25:51.523  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:51.523  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:51.533  1016  1124 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-29 11:25:51.543  1016  1471 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 11:25:51.543  1016  1471 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 11:25:51.543  1016  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:51.543  1016  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:51.543  1016  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 11:25:51.543  1598  1598 I Hs20UtilService: Starting #22
,08-29 11:25:51.553  1598  1647 I Hs20UtilService: Message received 5007
,08-29 11:25:51.553  1016  1126 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-29 11:25:51.553  1016  1126 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-29 11:25:51.563  3306  3306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 11:25:51.563  1016  1126 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-29 11:25:51.563  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 11:25:51.563  1016  1126 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 11:25:51.563  1016  1126 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-29 11:25:51.563  1016  1126 D ConnectivityService: LTETest block dns file not exists
,08-29 11:25:51.563  3306  3306 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-29 11:25:51.573  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 11:25:51.573  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:51.573  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:51.573  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:51.573  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:51.573  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 11:25:51.573  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:51.573  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1880e213 removed from the list
08-29 11:25:51.573  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:51.573  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21743c50 removed from the list
08-29 11:25:51.573  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:51.573  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:25:51.573  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 11:25:51.573  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 11:25:51.573  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:51.573  1016  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 11:25:51.573  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:51.573  1016  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 11:25:51.573  1016  1126 V NetworkStats: updateIfacesLocked()
08-29 11:25:51.573  1016  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-29 11:25:51.573  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:51.573  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:51.573  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 11:25:51.573  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 11:25:51.573  1016  1016 I WifiTrafficPoller: mBoosterFLAG : 0
08-29 11:25:51.573  1016  1016 I WifiTrafficPoller: current booster mode : FullMode
08-29 11:25:51.573  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 11:25:51.573  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:51.583  1016  1126 V NetworkStats: performPollLocked() took 6ms
08-29 11:25:51.583  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:51.583  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 11:25:51.583  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-29 11:25:51.583  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:51.593  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:51.593  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:51.593  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:51.593  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-29 11:25:51.593  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 11:25:51.593  1016  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-29 11:25:51.593  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:51.593  1016  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 11:25:51.593  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 11:25:51.593  1016  1126 E ConnectivityService: updateNetworkInfo()
08-29 11:25:51.593  1016  1126 E ConnectivityService: updateNetworkInfo()
08-29 11:25:51.593  1016  1126 V NetworkStats: updateIfacesLocked()
08-29 11:25:51.593  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:51.593  1016  1126 V NetworkStats: performPollLocked(flags=0x1)
,08-29 11:25:51.593  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 11:25:51.593  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 11:25:51.603  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 11:25:51.603  1016  1126 V NetworkStats: performPollLocked() took 6ms
,08-29 11:25:51.603  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:51.603  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:51.613  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:51.613  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:51.613  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:51.613  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21743c50 not in the list
08-29 11:25:51.613  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 11:25:51.613  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 11:25:51.613  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 11:25:51.613  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 11:25:51.613  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 11:25:51.613  7505  7514 D BtGatt.GattService: stopScan() - queue size =1
08-29 11:25:51.613  7505  7535 D BtGatt.ScanManager: filter size is 1
08-29 11:25:51.613  7505  7535 D BtGatt.ScanManager: delete FilterIndex - 5
,08-29 11:25:51.613  7505  7531 D BtGatt.GattService: unregisterClient() - clientIf=6,
08-29 11:25:51.613  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 11:25:51.613  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 11:25:51.613  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
08-29 11:25:51.613  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 11:25:51.613  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 11:25:51.613  7505  7530 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 11:25:51.613  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:51.613  7505  7535 D BtGatt.ScanManager: stopping BLe Batch
,08-29 11:25:51.613  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:25:51.613  1016  1126 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-29 11:25:51.613  1016  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-29 11:25:51.613  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:51.613  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:51.613  1016  7620 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:51.613  1016  7620 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-29 11:25:51.613  1016  7620 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 11:25:51.613  1016  7620 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-29 11:25:51.613  1016  1472 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 11:25:51.613  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 11:25:51.623  1016  7620 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 11:25:51.623  6746  6800 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 11:25:51.623  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 11:25:51.623  7505  7530 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 11:25:51.623  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:51.623  7505  7535 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-29 11:25:51.623   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 11:25:51.623   278  1011 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-29 11:25:51.623  1016  1472 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 11:25:51.623  1016  1126 D ConnectivityService:    accepting network in place of null
08-29 11:25:51.623  1016  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-29 11:25:51.623  7505  7530 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 11:25:51.623  7505  7530 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 11:25:51.623  1456  1456 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-29 11:25:51.623  1456  1456 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 11:25:51.623  1016  1472 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:51.623  1016  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:51.623  1016  1126 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-29 11:25:51.623  1016  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 11:25:51.623  1016  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 11:25:51.623  1016  1126 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 11:25:51.623  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:51.623  1016  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-29 11:25:51.623  1598  1598 I Hs20UtilService: Starting #23
,08-29 11:25:51.623  1598  1647 I Hs20UtilService: Message received 5007
,08-29 11:25:51.623  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:51.623  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:51.623  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:51.623  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d8d8c6f removed from the list
08-29 11:25:51.623  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:51.623  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:51.623  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:51.623  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:51.623  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@370f34e removed from the list
08-29 11:25:51.623  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:51.623  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@210808b added. We now have 2 listener(s)
08-29 11:25:51.623  6746  6746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:25:51.623  6746  6746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 11:25:51.623  6746  6746 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 11:25:51.623  3306  3306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 11:25:51.633  3306  3306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 11:25:51.633  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-29 11:25:51.633  1016  1126 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-29 11:25:51.633  1016  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-29 11:25:51.633  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-29 11:25:51.633  1177  1723 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 11:25:51.633  1016  1129 D Tethering: MasterInitialState.processMessage what=3
08-29 11:25:51.633  4767  6808 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 11:25:51.633  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 11:25:51.633  3306  3306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-29 11:25:51.633  3306  3306 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-29 11:25:51.633  1016  1121 V NetworkStats: updateIfacesLocked()
08-29 11:25:51.633  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:51.633  1016  1121 V NetworkStats: performPollLocked(flags=0x1)
,08-29 11:25:51.633  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 11:25:51.633  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 11:25:51.633  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 11:25:51.633  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-29 11:25:51.633  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:51.633  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:51.633  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-29 11:25:51.633  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-29 11:25:51.633  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb34568 added. We now have 9 listener(s)
08-29 11:25:51.633  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 11:25:51.633  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:51.633  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-29 11:25:51.633  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-29 11:25:51.633  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-29 11:25:51.643  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 11:25:51.643  1016  1121 V NetworkStats: performPollLocked() took 5ms
08-29 11:25:51.643  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:51.643  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 11:25:51.643  1016  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-29 11:25:51.643  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:51.643  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:51.643  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:51.643  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-29 11:25:51.643  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-29 11:25:51.643  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-29 11:25:51.643  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 11:25:51.643  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 11:25:51.643  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:51.643  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:51.643  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 11:25:51.643  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 11:25:51.643  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 11:25:51.643  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:51.653  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:51.653  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-29 11:25:51.653  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 11:25:51.653  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:51.653  6746  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 11:25:51.653  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:51.653  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:51.653  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:51.653  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:51.653  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:51.653  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:25:51.653  6746  6800 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 11:25:51.653  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 11:25:51.653  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 11:25:51.653  1598  1598 I Hs20UtilService: Starting #24
,08-29 11:25:51.653  1598  1647 I Hs20UtilService: Message received 5007
08-29 11:25:51.653  6746  6800 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:51.653  6746  6800 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 11:25:51.663  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 11:25:51.663  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ef41e26 added. We now have 3 listener(s)
,08-29 11:25:51.663  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 11:25:51.663  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 11:25:51.663  3306  3306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 11:25:51.663  3306  3306 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-29 11:25:51.663  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-29 11:25:51.663  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 11:25:51.663  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 11:25:51.663  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 11:25:51.663  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26849a67 added. We now have 10 listener(s)
08-29 11:25:51.663  6746  6800 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 11:25:51.663  6746  6800 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 11:25:51.663  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:51.663  6746  6800 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 11:25:51.663  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:51.663  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:51.663  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 11:25:51.663  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:51.663  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@210808b removed from the list
08-29 11:25:51.663  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:51.663  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb34568 removed from the list
,08-29 11:25:51.663  6746  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-29 11:25:51.663  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:51.673  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 11:25:51.673  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:51.673  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:51.673  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:51.673  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:51.673  6746  6800 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb34568 not in the list
08-29 11:25:51.673  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:51.673  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 11:25:51.673  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 11:25:51.673  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 11:25:51.673  6746  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 11:25:51.673  6746  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26849a67 removed from the list
08-29 11:25:51.673  6746  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 11:25:51.673  6746  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 11:25:51.673  6746  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 11:25:51.673  6746  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 11:25:51.673  6746  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ef41e26 removed from the list
08-29 11:25:51.673  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 11:25:51.673  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 11:25:51.673  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 11:25:51.673  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 11:25:51.673  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 11:25:51.673  6746  6800 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 11:25:51.673  1016  1480 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
08-29 11:25:51.673  1016  1553 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-29 11:25:51.673  1016  1553 D SecContentProvider2: mCursor = null
,08-29 11:25:51.673  1016  1029 D SecContentProvider2: uri = 15 selection = getToastGravity
08-29 11:25:51.673  1016  1029 D SecContentProvider2: mCursor = null
08-29 11:25:51.683  6746  7660 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1364, name: My test thread name)
08-29 11:25:51.683  6746  7660 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1364, thread name: My test thread name)
08-29 11:25:51.683  6746  7660 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1364, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 11:25:51.683  1016  1028 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-29 11:25:51.683  1016  1028 D SecContentProvider2: mCursor = null
,08-29 11:25:51.683  1016  1550 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-29 11:25:51.683  1016  1550 D SecContentProvider2: mCursor = null
08-29 11:25:51.683  6746  7661 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1366, name: My test thread name)
08-29 11:25:51.683  6746  7661 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1366, thread name: My test thread name)
08-29 11:25:51.683  6746  7661 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1366, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 11:25:51.683  6746  6800 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 11:25:51.683  6746  6800 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 11:25:51.683  6746  6800 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 11:25:51.683  6746  6800 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 11:25:51.683  6746  6800 D com.test.thalitest.ThaliTestRunner: Total duration: 23404 ms
08-29 11:25:51.683  6746  6800 I jxcore-log: Total number of executed tests:  80
08-29 11:25:51.683  6746  6800 I jxcore-log: 
08-29 11:25:51.683  6746  6800 I jxcore-log: Number of passed tests:  80
08-29 11:25:51.683  6746  6800 I jxcore-log: 
08-29 11:25:51.683  6746  6800 I jxcore-log: Number of failed tests:  0
08-29 11:25:51.683  6746  6800 I jxcore-log: 
08-29 11:25:51.683  6746  6800 I jxcore-log: Number of ignored tests:  0
08-29 11:25:51.683  6746  6800 I jxcore-log: 
08-29 11:25:51.683  6746  6800 I jxcore-log: Total duration:  23404
08-29 11:25:51.683  6746  6800 I jxcore-log: 
08-29 11:25:51.683  6746  6800 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 11:25:51.683  6746  6800 I jxcore-log: 
,08-29 11:25:51.693  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:25:51.693  6746  6800 I jxcore-log: 
08-29 11:25:51.693  1016  1497 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-29 11:25:51.693  1016  1497 D SecContentProvider2: mCursor = null
08-29 11:25:51.693  1016  1479 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-29 11:25:51.693  1016  1479 D SecContentProvider2: mCursor = null
08-29 11:25:51.693  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:25:51.693  6746  6800 I jxcore-log: 
08-29 11:25:51.693  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:25:51.693  6746  6800 I jxcore-log: 
08-29 11:25:51.693  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:25:51.693  6746  6800 I jxcore-log: 
08-29 11:25:51.693  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:25:51.693  6746  6800 I jxcore-log: 
08-29 11:25:51.703  6746  6746 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 11:25:51.703  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:25:51.703  6746  6800 I jxcore-log: 
08-29 11:25:51.703  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:25:51.703  6746  6800 I jxcore-log: 
08-29 11:25:51.703  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 11:25:51.703  6746  6800 I jxcore-log: 
08-29 11:25:51.703  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:25:51.703  6746  6800 I jxcore-log: 
08-29 11:25:51.703  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:25:51.703  6746  6800 I jxcore-log: 
08-29 11:25:51.703  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 11:25:51.703  6746  6800 I jxcore-log: 
08-29 11:25:51.703  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 11:25:51.703  6746  6800 I jxcore-log: 
08-29 11:25:51.703  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:25:51.703  6746  6800 I jxcore-log: 
08-29 11:25:51.713  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:25:51.713  6746  6800 I jxcore-log: 
08-29 11:25:51.713  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:25:51.713  6746  6800 I jxcore-log: 
08-29 11:25:51.713  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:25:51.713  6746  6800 I jxcore-log: 
08-29 11:25:51.713  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:25:51.713  6746  6800 I jxcore-log: 
08-29 11:25:51.713  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 11:25:51.713  6746  6800 I jxcore-log: 
08-29 11:25:51.713  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:25:51.713  6746  6800 I jxcore-log: 
08-29 11:25:51.713  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 11:25:51.713  6746  6800 I jxcore-log: 
08-29 11:25:51.713  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:25:51.713  6746  6800 I jxcore-log: 
08-29 11:25:51.713  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:25:51.713  6746  6800 I jxcore-log: 
08-29 11:25:51.713  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:25:51.713  6746  6800 I jxcore-log: 
08-29 11:25:51.713  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:25:51.713  6746  6800 I jxcore-log: 
08-29 11:25:51.713  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:25:51.713  6746  6800 I jxcore-log: 
08-29 11:25:51.713  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 11:25:51.713  6746  6800 I jxcore-log: 
08-29 11:25:51.713  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:25:51.713  6746  6800 I jxcore-log: 
,08-29 11:25:51.723   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast,
,08-29 11:25:51.723  6746  6746 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-29 11:25:51.723  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 11:25:51.723  6746  6800 I jxcore-log: 
,08-29 11:25:51.733  1016  1553 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,08-29 11:25:51.743  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-29 11:25:51.893  6746  6746 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-29 11:25:51.893  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 11:25:51.893  6746  6800 I jxcore-log: 
,08-29 11:25:51.963  7663  7663 D AndroidRuntime: ,
08-29 11:25:51.963  7663  7663 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-29 11:25:51.963  7663  7663 D AndroidRuntime: CheckJNI is OFF,
08-29 11:25:51.973  7663  7663 D AndroidRuntime: readGMSProperty: start
08-29 11:25:51.973  7663  7663 D AndroidRuntime: readGMSProperty: already setted!!
08-29 11:25:51.973  7663  7663 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-29 11:25:51.973  7663  7663 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-29 11:25:51.973  7663  7663 D AndroidRuntime: readGMSProperty: end
08-29 11:25:51.973  7663  7663 D AndroidRuntime: addProductProperty: start,
,08-29 11:25:51.983  1016  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-29 11:25:51.983  1016  1126 V NetworkStats: updateIfacesLocked()
08-29 11:25:51.983  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:51.983  1016  1126 V NetworkStats: performPollLocked(flags=0x1),
08-29 11:25:51.983  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 11:25:51.983  1016  1126 V NetworkStats: performPollLocked() took 3ms
,08-29 11:25:51.983  1016  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 11:25:51.993  1016  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-29 11:25:51.983  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:51.993  1016  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-29 11:25:51.983  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:51.983  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:51.993  1177  1723 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-29 11:25:51.993  4767  6808 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-29 11:25:51.993  1177  1723 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-29 11:25:51.993  4767  6808 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-29 11:25:52.093  7663  7663 E AffinityControl: AffinityControl: registerfunction enter,
,08-29 11:25:52.123  7663  7663 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-29 11:25:52.133  6746  6746 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 11:25:52.133  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
08-29 11:25:52.133  6746  6800 I jxcore-log: 
08-29 11:25:52.133  1016  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:25:52.143  1016  1134 D PackageManager: START PACKAGE DELETE: observer{320537974}
08-29 11:25:52.143  1016  1134 D PackageManager: pkg{<packageName>}
08-29 11:25:52.143  1016  1134 D PackageManager: user{0}
08-29 11:25:52.143  1016  1134 D PackageManager: caller{2000}
08-29 11:25:52.143  1016  1134 D PackageManager: flags{2}
,08-29 11:25:52.143  1016  1134 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,08-29 11:25:52.143  1016  1134 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-29 11:25:52.143  1016  1134 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-29 11:25:52.143  1016  1134 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-29 11:25:52.143  1016  1134 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-29 11:25:52.153  1016  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-29 11:25:52.153  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-29 11:25:52.153  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-29 11:25:52.153  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled,
08-29 11:25:52.153  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-29 11:25:52.153  1016  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:25:52.163  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-29 11:25:52.163  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:52.163  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:52.163  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:52.163  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:52.173  6746  6746 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 11:25:52.173  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 11:25:52.173  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 11:25:52.173  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 11:25:52.173  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 11:25:52.173  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 11:25:52.173  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 11:25:52.173  6746  6746 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 11:25:52.173  1016  1056 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-29 11:25:52.183  7673  7673 E Zygote  : MountEmulatedStorage(),
,08-29 11:25:52.183  7673  7673 I libpersona: KNOX_SDCARD checking this for 1000
08-29 11:25:52.183  7673  7673 E Zygote  : v2
08-29 11:25:52.183  7673  7673 I libpersona: KNOX_SDCARD not a persona
08-29 11:25:52.183  6746  6746 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 11:25:52.183  7673  7673 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:52.183  6746  6800 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 11:25:52.183  6746  6800 I jxcore-log: 
,08-29 11:25:52.183  7673  7673 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 11:25:52.183  7673  7673 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 11:25:52.193  1016  1041 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7673 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 11:25:52.193  1016  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg,
08-29 11:25:52.193  1016  1041 I ActivityManager: Killing 6746:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg,
,08-29 11:25:52.223  7673  7673 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:52.223  7673  7673 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:52.293  1016  1056 W PackageSettings: Skipping PackageSetting{2703764f com.example.hello/10168} due to missing metadata
,08-29 11:25:52.313  1016  1041 I ActivityManager:   Force finishing activity ActivityRecord{21605354 u0 com.test.thalitest/.MainActivity t2}
,08-29 11:25:52.313  1016  1041 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-29 11:25:52.333  1016  1041 D InputDispatcher: Focus left window: 6746
,08-29 11:25:52.333   258   445 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-29 11:25:52.333   258   447 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-29 11:25:52.343  1016  1472 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-29 11:25:52.343  1016  1472 D SecContentProvider2: mCursor = null
,08-29 11:25:52.343  1016  1041 D InputDispatcher: Focused application released
,08-29 11:25:52.353  1016  1046 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-29 11:25:52.353  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 11:25:52.353  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-29 11:25:52.353  1016  1041 D FocusedStackFrame: Set to : 0
,08-29 11:25:52.363  1016  1041 W ActivityManager: mDVFSHelper.acquire()
,08-29 11:25:52.363  1016  1041 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-29 11:25:52.373  1016  1056 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-29 11:25:52.383  1016  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-29 11:25:52.423  1481  1481 D Launcher: onRestart, Launcher: 587723754
,08-29 11:25:52.433  2679  2679 I art     : Explicit concurrent mark sweep GC freed 21153(1184KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 1.164ms total 36.331ms
,08-29 11:25:52.443  2001  2152 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 11:25:52.443  1872  1872 E SamsungIME: mOCRHelper is null
,08-29 11:25:52.443  1016  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 11:25:52.463  7673  7673 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-29 11:25:52.463  7673  7673 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,08-29 11:25:52.463  7673  7673 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-29 11:25:52.473  1016  1121 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-29 11:25:52.473  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:52.473  1016  1121 V NetworkStats: performPollLocked(flags=0x3)
,08-29 11:25:52.473  1456  1456 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 11:25:52.483  4767  4767 I art     : Explicit concurrent mark sweep GC freed 23207(1398KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 12MB/21MB, paused 1.336ms total 92.231ms
,08-29 11:25:52.483  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 11:25:52.483  1016  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 11:25:52.493  1481  1481 D Launcher: onStart, Launcher: 587723754
08-29 11:25:52.493  1481  1481 D Launcher.HomeView: onStart
,08-29 11:25:52.493  1481  1481 D Launcher: onResume, Launcher: 587723754
,08-29 11:25:52.493  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,08-29 11:25:52.493  1016  1121 V NetworkStats: performPollLocked() took 24ms
08-29 11:25:52.493  1016  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:52.493  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
08-29 11:25:52.493  1016  1472 D SettingsProvider: name = kids_home_mode
08-29 11:25:52.493  1016  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 11:25:52.493  1016  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 11:25:52.493  1016  1472 D SettingsProvider: selectionArgs: false
08-29 11:25:52.493  1016  1472 D SettingsProvider: selectionArgs: 10006
08-29 11:25:52.493  1016  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 11:25:52.493  1016  1472 D SettingsProvider: ret = -1
,08-29 11:25:52.493  1481  1481 D Launcher.HomeView: onResume
,08-29 11:25:52.503  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-29 11:25:52.503  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-29 11:25:52.503  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-29 11:25:52.513  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,08-29 11:25:52.513  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-29 11:25:52.513  1441  1441 D RegisteredServicesCache: empty dynamic service
,08-29 11:25:52.513  7673  7673 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-29 11:25:52.513  7673  7673 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-29 11:25:52.513  7673  7673 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-29 11:25:52.513  7673  7673 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:25:52.523  1016  1479 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
08-29 11:25:52.523  1016  1479 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
08-29 11:25:52.523  1481  1481 D MenuAppsGridFragment: onResume
,08-29 11:25:52.523  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,08-29 11:25:52.523  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-29 11:25:52.533  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-29 11:25:52.533  1781  1781 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 11:25:52.533  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-29 11:25:52.533  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-29 11:25:52.543  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:52.543  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:52.543  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:52.543  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:52.553  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 11:25:52.553  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 11:25:52.553  7692  7692 E Zygote  : MountEmulatedStorage()
,08-29 11:25:52.553  7692  7692 E Zygote  : v2
,08-29 11:25:52.553  7692  7692 I libpersona: KNOX_SDCARD checking this for 10121
,08-29 11:25:52.553  7692  7692 I libpersona: KNOX_SDCARD not a persona
08-29 11:25:52.563  1016  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7692 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-29 11:25:52.563  7692  7692 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:52.563  1016  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-29 11:25:52.563  1016  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-29 11:25:52.563  1016  1040 W TextServicesManagerService: no available spell checker services found
,08-29 11:25:52.563  7692  7692 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 11:25:52.563  7692  7692 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 11:25:52.573  1016  1479 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-29 11:25:52.573  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:52.573  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:52.573  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:52.573  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:52.593  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 11:25:52.593  1016  1479 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7702 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-29 11:25:52.593  7702  7702 E Zygote  : MountEmulatedStorage()
08-29 11:25:52.593  7702  7702 I libpersona: KNOX_SDCARD checking this for 10031
08-29 11:25:52.593  7702  7702 E Zygote  : v2
08-29 11:25:52.593  7702  7702 I libpersona: KNOX_SDCARD not a persona
,08-29 11:25:52.603  7702  7702 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 11:25:52.603  7692  7692 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:52.603  7692  7692 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:52.603  7702  7702 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 11:25:52.603  1016  1550 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-29 11:25:52.603  7702  7702 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-29 11:25:52.603  1016  1550 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
08-29 11:25:52.603  1016  1550 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:52.603  1016  1550 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:52.603  1016  1550 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
08-29 11:25:52.603  1016  1134 D ActivityManager: handle home activity for 0
08-29 11:25:52.603  1016  1134 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,08-29 11:25:52.603  1016  1134 D KnoxTimeoutHandler: post home show event for user 0
08-29 11:25:52.603  1016  1134 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-29 11:25:52.603  1016  1134 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-29 11:25:52.603  1016  1134 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-29 11:25:52.603  1481  1481 D Launcher.HomeView: onPause
,08-29 11:25:52.613  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) },
,08-29 11:25:52.613  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0,
08-29 11:25:52.613  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 11:25:52.613  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,08-29 11:25:52.613  1016  1016 V EnterpriseBillingPolicy: uID is 10171,
08-29 11:25:52.613  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
,08-29 11:25:52.613  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter,
08-29 11:25:52.613  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-29 11:25:52.613  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-29 11:25:52.613  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-29 11:25:52.613  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-29 11:25:52.613  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-29 11:25:52.623  2477  2486 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
08-29 11:25:52.623  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-29 11:25:52.623  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-29 11:25:52.623  1016  1160 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
08-29 11:25:52.623  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-29 11:25:52.623  1016  3365 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-29 11:25:52.623  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-29 11:25:52.623  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-29 11:25:52.623  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-29 11:25:52.623  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-29 11:25:52.623  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-29 11:25:52.623  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-29 11:25:52.623  1441  1441 D RegisteredComponentCache: Collect Tech packages for Knox
,08-29 11:25:52.633  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-29 11:25:52.633  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-29 11:25:52.633  1016  1016 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
08-29 11:25:52.633  1016  1126 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-29 11:25:52.633  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 11:25:52.633   258   258 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-29 11:25:52.643  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
08-29 11:25:52.643  1781  1781 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-29 11:25:52.643  1781  1781 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-29 11:25:52.643  1781  1781 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-29 11:25:52.643  1781  1781 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-29 11:25:52.643  7702  7702 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:52.643  7702  7702 D ActivityThread: Added TimaKeyStore provider
08-29 11:25:52.643  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 11:25:52.653  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 11:25:52.653  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-29 11:25:52.663  7692  7692 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 11:25:52.663  7692  7692 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-29 11:25:52.663  7692  7692 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 11:25:52.663  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-29 11:25:52.663  1016  1497 D InputDispatcher: Focus entered window: 1481
,08-29 11:25:52.673  1781  1781 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 11:25:52.673  1481  1481 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-29 11:25:52.673  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-29 11:25:52.673  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-29 11:25:52.673  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-29 11:25:52.673  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-29 11:25:52.683  7692  7692 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:25:52.683  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 11:25:52.683  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 11:25:52.693  1481  1481 D Launcher.HomeView: onStop
08-29 11:25:52.693  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{2e790631 token=android.os.BinderProxy@16889cf6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-29 11:25:52.693  1781  1781 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-29 11:25:52.723  7692  7692 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-29 11:25:52.733  7692  7692 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-29 11:25:52.743  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-29 11:25:52.743  1016  1551 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-29 11:25:52.753  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:52.753  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:52.753  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:52.753  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:52.753  1016  1056 I art     : Explicit concurrent mark sweep GC freed 82416(5MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 24MB/36MB, paused 14.102ms total 350.254ms
,08-29 11:25:52.763  1016  1551 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6746 uid 10171
,08-29 11:25:52.763  1016  1029 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-29 11:25:52.763  1016  1029 D SecContentProvider2: mCursor = null,
,08-29 11:25:52.763  1016  7723 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 11:25:52.773  7724  7724 E Zygote  : MountEmulatedStorage()
08-29 11:25:52.773  7724  7724 E Zygote  : v2
08-29 11:25:52.773  7724  7724 I libpersona: KNOX_SDCARD checking this for 10001
08-29 11:25:52.773  7724  7724 I libpersona: KNOX_SDCARD not a persona
08-29 11:25:52.773  7724  7724 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 11:25:52.773  7724  7724 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 11:25:52.773  1016  1016 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7724 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 11:25:52.773  7724  7724 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 11:25:52.783  1016  1480 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
08-29 11:25:52.783  1016  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-29 11:25:52.783  1016  1480 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:52.783  1016  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:52.783  1016  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-29 11:25:52.793  1872  1872 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-29 11:25:52.793  1016  1046 W ActivityManager: mDVFSHelper.release()
,08-29 11:25:52.793  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3d523617 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:148065
,08-29 11:25:52.803  1016  1497 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 11:25:52.803  1177  1177 I StatusBar: Icon Only
08-29 11:25:52.803  1177  1177 D PanelView: There is/are notification(s) 
,08-29 11:25:52.813  1016  1224 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-29 11:25:52.813  1016  1224 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-29 11:25:52.813  1016  1224 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:52.813  1016  1224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:52.813  1016  1224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-29 11:25:52.813  1016  1471 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 11:25:52.833  1016  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-29 11:25:52.833  7195  7195 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-29 11:25:52.843  7724  7724 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:52.843  6997  7737 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-29 11:25:52.843  6997  7737 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 11:25:52.843  6997  7737 I System.out: (HTTPLog)-Static: isShipBuild true
08-29 11:25:52.843  6997  7737 I System.out: (HTTPLog)-Thread-1270-516150121: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-29 11:25:52.843  6997  7737 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 11:25:52.843  7724  7724 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:52.843   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 11:25:52.843   278  1011 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,08-29 11:25:52.863  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 11:25:52.863  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 11:25:52.873  7092  7092 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-29 11:25:52.883  7155  7155 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-29 11:25:52.883  7155  7155 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-29 11:25:52.883  7155  7155 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-29 11:25:52.883  7155  7155 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-29 11:25:52.883  7155  7155 I SA      : [OR] == isSIMCardReady false ==
,08-29 11:25:52.893  7155  7155 I SA      : [SCU] == networkStateCheck == true
,08-29 11:25:52.893  2801  7746 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-29 11:25:52.893  2801  7746 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-29 11:25:52.893  7155  7155 I SA      : [DM] getCountryCodeFromCSC : PL
,08-29 11:25:52.893  7155  7155 I SA      : isChinaCountryCode : false
,08-29 11:25:52.893  2801  7746 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-29 11:25:52.893  7155  7155 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-29 11:25:52.893  7155  7155 I SA      : [OR] == networkStateCheck true ==
,08-29 11:25:52.903  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 11:25:52.913  7155  7155 I SA      : [OR] GetMyCountryZoneTask
,08-29 11:25:52.913  7155  7155 I SA      : [OR] onReceive END
,08-29 11:25:52.913  1016  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-29 11:25:52.913  1016  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 11:25:52.913  1016  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 11:25:52.913  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 11:25:52.913  1231  1231 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:25:52.923  1016  1479 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
08-29 11:25:52.923  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-29 11:25:52.923  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:52.923  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:52.923  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-29 11:25:52.933  7155  7751 I SA      : [SRS] prepareGetMyCountryZone
,08-29 11:25:52.933  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 11:25:52.943  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 11:25:52.943  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 11:25:52.943  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-29 11:25:52.943  7155  7751 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-29 11:25:52.943  1016  1479 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-29 11:25:52.943  1016  1479 D SecContentProvider2: mCursor = null
,08-29 11:25:52.953  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 11:25:52.953  1016  1056 D PackageManager: delete codoeFile: 
,08-29 11:25:52.953  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 11:25:52.953  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-29 11:25:52.953  7131  7131 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-29 11:25:52.953  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 11:25:52.953  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-29 11:25:52.963  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 11:25:52.963  1016  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-29 11:25:52.963  7131  7131 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-29 11:25:52.963  7131  7131 I DIAGMON_AGENT: ./extraInfo: "NG700"
08-29 11:25:52.963  7131  7131 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
08-29 11:25:52.963  1016  1056 I AASA_removePackage: UID=10171 Target=com.test.thalitest
08-29 11:25:52.963  1016  1056 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,08-29 11:25:52.963  1016  1056 D PackageManager: result of delete: 1{320537974}
,08-29 11:25:52.973  1016  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-29 11:25:52.973  7155  7751 I SA      : [SSP] query invoked
,08-29 11:25:52.973  7663  7663 D AndroidRuntime: Shutting down VM
,08-29 11:25:52.983  7155  7751 I SA      : [TPMU] GetMccFromDB : null
08-29 11:25:52.983  7155  7751 I SA      : [SCU] getMccFromPreferece mcc = 260
08-29 11:25:52.983  7155  7751 I SA      : [LBE] isSupportCheckDomainRegion : false
08-29 11:25:52.983  7155  7751 I SA      : [TPM] isNoProxy(default) : true
,08-29 11:25:52.993  7155  7751 E File    : fail readDirectory() errno=2
,08-29 11:25:53.013  2801  7746 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-29 11:25:53.013  2801  7746 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-29 11:25:53.013  2801  7746 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-29 11:25:53.013  2801  7746 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-29 11:25:53.013  2801  7746 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-29 11:25:53.013  2801  7746 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-29 11:25:53.023  2801  7746 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-29 11:25:53.023  2801  7746 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-29 11:25:53.043  2801  7746 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-29 11:25:53.063  2801  7746 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-29 11:25:53.123  7232  7232 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-29 11:25:53.123  1481  1481 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@16889cf6 time:148397
,08-29 11:25:53.133  7232  7232 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-29 11:25:53.133  7232  7232 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-29 11:25:53.133  7232  7232 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-29 11:25:53.133  1016  1550 I ActivityManager: Killing 7174:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-29 11:25:53.143  2897  2897 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 29 11:25:53 GMT+02:00 2016
,08-29 11:25:53.143  1016  1029 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-29 11:25:53.143  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-29 11:25:53.143  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-29 11:25:53.143  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:53.143  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-29 11:25:53.143  2897  2897 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-29 11:25:53.153  2897  2897 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-29 11:25:53.153  2897  2897 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-29 11:25:53.153  2897  2897 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-29 11:25:53.163  2897  7758 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-29 11:25:53.163  2897  7758 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-29 11:25:53.163  2897  7758 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,08-29 11:25:53.173  2897  7758 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,08-29 11:25:53.173  2897  7758 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,08-29 11:25:53.183  2897  7758 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
08-29 11:25:53.183  2897  7758 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-29 11:25:53.183  2897  2897 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-29 11:25:53.193  7663  7663 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-29 11:25:53.203  1016  1497 D PersonaManager: isKioskContainerExistOnDevice
,08-29 11:25:53.213  1016  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-29 11:25:53.213  1016  1056 D PackageManager: userId{-1}
08-29 11:25:53.213  1016  1056 D PackageManager: andCode{true}
,08-29 11:25:53.213  1016  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-29 11:25:53.213  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:53.213  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:53.213  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:53.213  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:53.233  7759  7759 E Zygote  : MountEmulatedStorage(),
08-29 11:25:53.233  7759  7759 E Zygote  : v2
08-29 11:25:53.233  7759  7759 I libpersona: KNOX_SDCARD checking this for 10003
08-29 11:25:53.233  7759  7759 I libpersona: KNOX_SDCARD not a persona,
08-29 11:25:53.233  7759  7759 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 11:25:53.233  1016  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7759 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a,
08-29 11:25:53.233  1016  1551 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:53.233  1016  1551 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
08-29 11:25:53.233  1016  1551 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-29 11:25:53.233  1016  1551 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
08-29 11:25:53.233  1016  1551 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-29 11:25:53.243  7759  7759 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 11:25:53.243  7759  7759 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 11:25:53.243  1016  1553 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 11:25:53.243  1016  1553 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0,
08-29 11:25:53.243  1016  1553 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:53.243  1016  1553 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 11:25:53.243  1016  1553 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 11:25:53.253  4767  4767 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-29 11:25:53.253   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 11:25:53.253   278  1011 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,08-29 11:25:53.263   306   306 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 26.224ms
,08-29 11:25:53.263  7195  7195 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-29 11:25:53.273  7195  7195 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,08-29 11:25:53.273  4767  7245 I iu.UploadsManager: num queued entries: 0
,08-29 11:25:53.273  7759  7759 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:53.273  7195  7195 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
08-29 11:25:53.273  7195  7195 D InitializeManagerStateMachine: exit::IDLE
08-29 11:25:53.273  7195  7195 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-29 11:25:53.273  7759  7759 D ActivityThread: Added TimaKeyStore provider
08-29 11:25:53.273  4767  7245 I iu.UploadsManager: num updated entries: 0
,08-29 11:25:53.273  7195  7195 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-29 11:25:53.273  7195  7195 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-29 11:25:53.273  7195  7195 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-29 11:25:53.273  7195  7195 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-29 11:25:53.273  7195  7195 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-29 11:25:53.273  7195  7195 D InitializeManagerStateMachine: entry::SUCCESS
08-29 11:25:53.273  7195  7195 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-29 11:25:53.283   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 704us total 18.450ms
,08-29 11:25:53.283  4767  7245 I iu.SyncManager: NEXT; no task
,08-29 11:25:53.293  7195  7195 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-29 11:25:53.293  7195  7195 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-29 11:25:53.293  7195  7195 D InitializeManagerStateMachine: exit::SUCCESS
08-29 11:25:53.293  7195  7195 D InitializeManagerStateMachine: entry::IDLE
,08-29 11:25:53.303   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 18.773ms
,08-29 11:25:53.313  1016  1551 I ActivityManager: Killing 6822:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,08-29 11:25:53.313  1016  1041 I splitIntent: Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-29 11:25:53.313  1016  1041 I ActivityManager: Killing 7565:com.samsung.android.sm/1000 (adj 15): empty #21
,08-29 11:25:53.323  1016  1329 I ActivityManager: Killing 7390:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-29 11:25:53.333  2897  2897 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 29 11:25:53 GMT+02:00 2016
,08-29 11:25:53.333  1016  1134 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-29 11:25:53.333  1016  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-29 11:25:53.333  1016  1134 W ActivityManager: userId = 0, bbcId = -10000
08-29 11:25:53.333  1016  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 11:25:53.333  1016  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-29 11:25:53.333  2897  2897 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-29 11:25:53.343  1016  1551 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
,08-29 11:25:53.343  1016  1551 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-29 11:25:53.343  1016  1551 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
08-29 11:25:53.343  1016  1551 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:53.343  1016  1551 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:53.343  1016  1551 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:53.343  1016  1551 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:53.343  2897  2897 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-29 11:25:53.343  2897  2897 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-29 11:25:53.353  2897  2897 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-29 11:25:53.353  7779  7779 E Zygote  : MountEmulatedStorage()
08-29 11:25:53.353  7779  7779 E Zygote  : v2
08-29 11:25:53.353  7779  7779 I libpersona: KNOX_SDCARD checking this for 10090
08-29 11:25:53.353  7779  7779 I libpersona: KNOX_SDCARD not a persona
,08-29 11:25:53.353  1016  1551 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7779 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-29 11:25:53.353  7779  7779 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:53.363  7779  7779 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 11:25:53.363  7779  7779 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 11:25:53.363  2897  7778 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-29 11:25:53.363  2897  7778 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-29 11:25:53.373  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-29 11:25:53.373  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:53.373  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:53.373  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:53.373  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:53.373  2897  7778 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-29 11:25:53.373  2897  7778 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-29 11:25:53.373  1016  1471 I TactileAssist: enable value -1
08-29 11:25:53.373  1016  1471 I TactileAssist: internal enable value -1
08-29 11:25:53.373  1016  1471 I TactileAssist: intensity value -1
08-29 11:25:53.373  1016  1471 I TactileAssist: saveAppList value true
,08-29 11:25:53.383  7791  7791 E Zygote  : MountEmulatedStorage()
,08-29 11:25:53.383  7791  7791 E Zygote  : v2
,08-29 11:25:53.383  7791  7791 I libpersona: KNOX_SDCARD checking this for 1000
08-29 11:25:53.383  7791  7791 I libpersona: KNOX_SDCARD not a persona
08-29 11:25:53.393  7779  7779 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 11:25:53.393  7779  7779 D ActivityThread: Added TimaKeyStore provider
08-29 11:25:53.393  1016  1471 I TactileAssist: List of disabled apps :
,08-29 11:25:53.393  1016  1041 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7791 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 11:25:53.393  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,08-29 11:25:53.403  7791  7791 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 11:25:53.403  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:53.403  7791  7791 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 11:25:53.403  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:53.403  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:53.403  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 11:25:53.403  7791  7791 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 11:25:53.413  7804  7804 E Zygote  : MountEmulatedStorage(),
08-29 11:25:53.413  7804  7804 E Zygote  : v2
08-29 11:25:53.413  7804  7804 I libpersona: KNOX_SDCARD checking this for 1000
,08-29 11:25:53.413  1016  1041 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7804 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-29 11:25:53.413  7804  7804 I libpersona: KNOX_SDCARD not a persona,
08-29 11:25:53.423  7804  7804 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 11:25:53.423  7804  7804 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 11:25:53.423  7804  7804 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 11:25:53.443  7791  7791 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 11:25:53.443  7791  7791 D ActivityThread: Added TimaKeyStore provider
,08-29 11:25:53.453  1016  1224 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-29 11:25:53.453  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:53.453  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:53.453  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 11:25:53.453  1016  1224 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
