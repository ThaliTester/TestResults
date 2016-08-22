#### Test 82147046d1155fd_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
,08-22 11:14:46.619   288   288 E SMD     : DCD OFF
08-22 11:14:46.899  6763  6763 D AndroidRuntime: 
08-22 11:14:46.899  6763  6763 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-22 11:14:46.899  6763  6763 D AndroidRuntime: CheckJNI is OFF
08-22 11:14:46.899  6763  6763 D AndroidRuntime: readGMSProperty: start
08-22 11:14:46.899  6763  6763 D AndroidRuntime: readGMSProperty: already setted!!
08-22 11:14:46.899  6763  6763 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-22 11:14:46.899  6763  6763 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-22 11:14:46.899  6763  6763 D AndroidRuntime: readGMSProperty: end
08-22 11:14:46.899  6763  6763 D AndroidRuntime: addProductProperty: start
08-22 11:14:47.039  6763  6763 E AffinityControl: AffinityControl: registerfunction enter
08-22 11:14:47.059  6763  6763 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-22 11:14:47.079  1016  3764 E PersonaManagerService: inState():  stateMachine is null !!
08-22 11:14:47.079  1016  3764 I PersonaManagerService: PersonaId don't exist
08-22 11:14:47.079  1016  3764 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-22 11:14:47.079  1016  3764 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-22 11:14:47.099  1016  3764 W ActivityManager: mDVFSHelper.acquire()
08-22 11:14:47.109   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-22 11:14:47.109   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-22 11:14:47.129  1016  3764 D FocusedStackFrame: Set to : 0
08-22 11:14:47.139  1016  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-22 11:14:47.139  1016  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-22 11:14:47.149  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-22 11:14:47.149  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-22 11:14:47.149   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-22 11:14:47.169  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:47.169  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:47.169  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:47.169  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:14:47.179  6774  6774 E Zygote  : MountEmulatedStorage()
08-22 11:14:47.179  6774  6774 I libpersona: KNOX_SDCARD checking this for 10171
08-22 11:14:47.179  6774  6774 E Zygote  : v2
08-22 11:14:47.179  6774  6774 I libpersona: KNOX_SDCARD not a persona
08-22 11:14:47.179  6774  6774 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:14:47.179  6774  6774 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:47.189  1016  3764 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6774 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-22 11:14:47.189  1016  3764 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-22 11:14:47.189  1016  3764 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 11:14:47.189  6774  6774 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-22 11:14:47.189  1016  3764 D InputDispatcher: Focused application set to: xxxx
08-22 11:14:47.189  1016  3764 D InputDispatcher: Focus left window: 1498
08-22 11:14:47.189  6763  6763 D AndroidRuntime: Shutting down VM
08-22 11:14:47.199  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 11:14:47.199  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-22 11:14:47.209  6774  6774 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:14:47.209  6774  6774 D ActivityThread: Added TimaKeyStore provider
08-22 11:14:47.209  1016  1214 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-22 11:14:47.219  1016  1016 V ActivityManager: Display changed displayId=0
08-22 11:14:47.219  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-22 11:14:47.229  1016  1214 D PersonaManager: isKioskContainerExistOnDevice
08-22 11:14:47.239  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-22 11:14:47.279   258   456 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
08-22 11:14:47.279   258  1054 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
08-22 11:14:47.289  1498  1498 V ActivityThread: updateVisibility : ActivityRecord{1fcb1ad8 token=android.os.BinderProxy@1a84fb64 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-22 11:14:47.289  1498  1498 D Launcher: onTrimMemory. Level: 20
08-22 11:14:47.379  6774  6774 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-22 11:14:47.399  6763  6763 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-22 11:14:47.429  6774  6774 I cr.library_loader: Time to load native libraries: 6 ms (timestamps 4960-4966)
08-22 11:14:47.429  6774  6774 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-22 11:14:47.449  6774  6774 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1fbe7fde}
08-22 11:14:47.449  6774  6774 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-22 11:14:47.459  6774  6774 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-22 11:14:47.499  6774  6774 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-22 11:14:47.499  6774  6774 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 11:14:47.509  6774  6774 E SysUtils: ApplicationContext is null in ApplicationStatus
08-22 11:14:47.539  6774  6774 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-22 11:14:47.539  6774  6774 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-22 11:14:47.539  6774  6774 I Adreno-EGL: Build Date: 04/06/15 Mon
08-22 11:14:47.539  6774  6774 I Adreno-EGL: Local Branch: 
08-22 11:14:47.539  6774  6774 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-22 11:14:47.539  6774  6774 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-22 11:14:47.539  6774  6774 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-22 11:14:47.629  6774  6774 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-22 11:14:47.649  6774  6774 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-22 11:14:47.649  6774  6774 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-22 11:14:47.659  6774  6774 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-22 11:14:47.659  6774  6774 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-22 11:14:47.739  1016  1041 W ActivityManager: Activity pause timeout for ActivityRecord{3cd38f08 u0 com.test.thalitest/.MainActivity t2}
08-22 11:14:47.789  6774  6774 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 11:14:47.799  6774  6774 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-22 11:14:47.809  6774  6774 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-22 11:14:47.809  6774  6774 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-22 11:14:47.819  6774  6774 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-22 11:14:47.829  6774  6774 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 11:14:47.829  6774  6774 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 11:14:47.869  6774  6812 D OpenGLRenderer: Render dirty regions requested: true
08-22 11:14:47.869  1016  1536 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-22 11:14:47.869  1016  1536 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-22 11:14:47.869  1016  1536 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-22 11:14:47.869  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-22 11:14:47.869  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-22 11:14:47.879  6774  6801 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-22 11:14:47.879  6774  6774 V ActivityThread: updateVisibility : ActivityRecord{90b453e token=android.os.BinderProxy@24b21243 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-22 11:14:47.879  6774  6774 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-22 11:14:47.879  6774  6774 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-22 11:14:47.899   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-22 11:14:47.909  1016  1514 D InputDispatcher: Focus entered window: 6774
08-22 11:14:47.909  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 11:14:47.909  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-22 11:14:47.919  6774  6774 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-22 11:14:47.919  6774  6812 I OpenGLRenderer: Initialized EGL, version 1.4
08-22 11:14:47.919  6774  6812 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-22 11:14:47.919  6774  6812 D OpenGLRenderer: Enabling debug mode 0
08-22 11:14:47.939  1016  1214 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-22 11:14:47.939  1174  1174 I StatusBar: Icon Only
08-22 11:14:47.949  1174  1174 D PanelView: There is/are notification(s) 
08-22 11:14:47.959  1016  6818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-22 11:14:47.959  1016  1046 I ActivityManager: Displayed Component not be shown by security: +722ms (total +795ms)
08-22 11:14:47.959  1016  1046 W ActivityManager: mDVFSHelper.release()
08-22 11:14:47.959  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3cd38f08 u0 com.test.thalitest/.MainActivity t2} time:105495
08-22 11:14:47.969  6774  6774 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-22 11:14:47.969  6774  6774 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@24b21243 time:105500
08-22 11:14:47.969   258  1055 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-22 11:14:47.969   258  1054 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-22 11:14:47.979  1919  1919 I SamsungIME: getCurrentCandidateView
08-22 11:14:48.129  6774  6774 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6774
08-22 11:14:48.149  1919  1919 D SamsungIME: Dismiss ExpandCandiate
,08-22 11:14:48.299  1919  1919 I SamsungIME: getDebugLevel  : 0x4f4c
,08-22 11:14:48.339  1919  1919 I SamsungIME: getDebugLevel  : 0x4f4c
,08-22 11:14:48.349  1919  1919 I SamsungIME: KeybaordView init() : load resources
,08-22 11:14:48.379  1919  1919 I SamsungIME: getCurrentKeyboard
08-22 11:14:48.379  1919  1919 I SamsungIME: getTextKeyboard
,08-22 11:14:48.399  1919  1919 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-22 11:14:48.419  6774  6774 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-22 11:14:48.499  6774  6820 D jxcore_app_log: JniHelper::setJavaVM(0xb8b762b0), pthread_self() = -1190126160
,08-22 11:14:48.509  6774  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-22 11:14:48.509  6774  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-22 11:14:48.509  6774  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-22 11:14:48.509  6774  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-22 11:14:48.509  6774  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-22 11:14:48.509  6774  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10174984 added. We now have 1 listener(s)
,08-22 11:14:48.509  6774  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-22 11:14:48.509  6774  6820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-22 11:14:48.509  6774  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 11:14:48.519  6774  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 11:14:48.519  6774  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-22 11:14:48.519  6774  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-22 11:14:48.519  6774  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-22 11:14:48.519  6774  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-22 11:14:48.519  6774  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-22 11:14:48.519  6774  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-22 11:14:48.519  6774  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-22 11:14:48.519  6774  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-22 11:14:48.519  6774  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-22 11:14:48.519  6774  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-22 11:14:48.519  6774  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-22 11:14:48.519  6774  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-22 11:14:48.519  6774  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-22 11:14:48.519  6774  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-22 11:14:48.519  6774  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ec1233 added. We now have 1 listener(s)
08-22 11:14:48.519  6774  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:14:48.529  6774  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 11:14:48.529  6774  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-22 11:14:48.529  6774  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-22 11:14:48.529  6774  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-22 11:14:48.529  6774  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-22 11:14:48.529  6774  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:14:48.529  6774  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-22 11:14:48.539  6774  6820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-22 11:14:48.539  6774  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:14:48.539  6774  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:14:48.539  6774  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:14:48.539  6774  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:14:48.539  6774  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:14:48.539  6774  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:14:48.539  6774  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:14:48.539  6774  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 11:14:48.539  6774  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-22 11:14:48.549  6774  6820 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:14:48.549  6774  6820 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 11:14:48.549  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:14:48.549  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:14:48.589  6774  6774 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-22 11:14:48.619  1016  3765 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-22 11:14:48.619  1016  3765 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-22 11:14:48.619  1016  3765 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-22 11:14:48.619  1016  3765 D BatteryService: stay LED for fully charged
,08-22 11:14:48.619  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 11:14:48.619  1016  1016 I MotionRecognitionService: Plugged
08-22 11:14:48.619  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 11:14:48.619  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-22 11:14:48.619  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 11:14:48.629  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-22 11:14:48.629  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-22 11:14:48.639  3174  3174 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-22 11:14:48.639  3174  3298 D HeadsetStateMachine: Disconnected process message: 10
,08-22 11:14:48.649  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-22 11:14:48.649  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-22 11:14:48.649  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-22 11:14:48.649  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-22 11:14:48.649  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-22 11:14:49.139  6774  6827 W jxcore-log: Initializing JXcore engine
08-22 11:14:49.139  6774  6827 W jxcore-log: JXcore engine is ready
,08-22 11:14:49.189  1955  1955 E audit   : type=1400 msg=audit(1471857289.189:205): avc:  denied  { ioctl } for  pid=6827 comm="Thread-1250" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2069 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-22 11:14:49.199  1955  1955 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:14:49.199  1955  1955 E audit   : type=1300 msg=audit(1471857289.189:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9cd028f8 items=0 ppid=313 ppcomm=main pid=6827 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1250" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-22 11:14:49.199  1955  1955 E audit   : type=1320 msg=audit(1471857289.189:205): 
,08-22 11:14:49.209  6774  6827 W jxcore-log: Starting JXcore engine
,08-22 11:14:49.309  6774  6827 W jxcore-log: Platform android
08-22 11:14:49.309  6774  6827 W jxcore-log: 
08-22 11:14:49.309  6774  6827 W jxcore-log: Process ARCH arm
08-22 11:14:49.309  6774  6827 W jxcore-log: 
,08-22 11:14:49.519  6774  6827 I jxcore-log: JXcore Cordova bridge is ready!
08-22 11:14:49.519  6774  6827 I jxcore-log: 
,08-22 11:14:49.519  6774  6827 W jxcore-log: JXcore engine is started
,08-22 11:14:49.529  6774  6820 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-22 11:14:49.529  6774  6774 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-22 11:14:49.619   288   288 E SMD     : DCD OFF
,08-22 11:14:50.529  1016  1322 E Watchdog: !@Sync 3,
,08-22 11:14:51.629   331   331 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-22 11:14:51.629   331   331 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-22 11:14:52.619   288   288 E SMD     : DCD OFF
,08-22 11:14:54.169  1016  1048 I PowerManagerService: [PWL] Off : 50s ago,
,08-22 11:14:54.379  1016  3371 D SSRM:n  : SIOP:: AP = 330,
,08-22 11:14:55.619   288   288 E SMD     : DCD OFF
,08-22 11:14:56.629   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 11:14:57.089  5647  5647 D FactoryTest: Not factory mode
08-22 11:14:57.089  5647  5647 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-22 11:14:57.089  5647  5647 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-22 11:14:57.089  5647  5647 D MTPRx   : still no open session command from host, so toast
,08-22 11:14:57.099  5647  5647 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-22 11:14:57.099  5647  5647 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-22 11:14:57.099  5647  5647 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114635,
08-22 11:14:57.099  1016  1504 E PersonaManagerService: inState():  stateMachine is null !!
08-22 11:14:57.099  1016  1504 I PersonaManagerService: PersonaId don't exist
08-22 11:14:57.099  1016  1504 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-22 11:14:57.109  1016  1504 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-22 11:14:57.109  1016  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:14:57.109  1016  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:14:57.109  1016  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-22 11:14:57.109  1016  1504 W ActivityManager: mDVFSHelper.acquire()
,08-22 11:14:57.129  1016  1504 D PersonaManager: isKioskContainerExistOnDevice
,08-22 11:14:57.129  1016  1504 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 11:14:57.129  1016  1504 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-22 11:14:57.129  1016  1504 D InputDispatcher: Focused application set to: xxxx
08-22 11:14:57.129  1016  1504 D InputDispatcher: Focus left window: 6774
,08-22 11:14:57.139  5647  5647 E MTPRx   : started activity for popup
,08-22 11:14:57.139  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 11:14:57.139  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 11:14:57.159  5647  5647 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-22 11:14:57.159  5647  5647 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-22 11:14:57.159  5647  5647 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-22 11:14:57.159  5647  5647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-22 11:14:57.169  5647  5647 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:14:57.169  5647  5647 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-22 11:14:57.189  5647  5647 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-22 11:14:57.189  1016  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-22 11:14:57.199  1016  1214 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-22 11:14:57.199  1016  1214 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 11:14:57.199  1016  1214 D InputDispatcher: Focused application set to: xxxx
,08-22 11:14:57.199  1016  1214 D InputDispatcher: Focus entered window: 6774
,08-22 11:14:57.199  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 11:14:57.199  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 11:14:57.209  1016  1262 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-22 11:14:57.209  1016  1262 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3ed1be7b attribute=null, token = android.os.BinderProxy@71c9c8b
,08-22 11:14:57.249  5647  5647 D SettingsReceiverActivity: dev.kiessupport is : TRUE,
,08-22 11:14:57.259  5647  5647 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-22 11:14:57.259  5647  5647 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-22 11:14:57.279  6774  6774 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-22 11:14:57.279  6774  6774 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-22 11:14:57.279  6774  6774 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-22 11:14:57.279  6774  6774 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-22 11:14:57.279  1016  1029 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-22 11:14:57.289  1016  1029 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-22 11:14:57.289  1016  1029 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-22 11:14:57.289  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-22 11:14:57.289  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-22 11:14:57.299  6774  6774 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-22 11:14:57.299  6774  6774 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-22 11:14:57.309  6774  6774 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@14621caf Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3c0fbd24, 16908290=android.view.AbsSavedState$1@3c0fbd24}, android:focusedViewId=100}]}]
08-22 11:14:57.309  6774  6774 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-22 11:14:57.309  6774  6774 V ActivityThread: updateVisibility : ActivityRecord{90b453e token=android.os.BinderProxy@24b21243 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-22 11:14:57.309  6774  6774 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-22 11:14:57.309  6774  6774 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-22 11:14:57.309  6774  6774 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@24b21243 time:114841
,08-22 11:14:57.309  1016  1492 D PersonaManager: isKioskContainerExistOnDevice
,08-22 11:14:57.629   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 11:14:58.619   288   288 E SMD     : DCD OFF,
,08-22 11:14:58.639   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 11:14:58.679  1016  3765 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-22 11:14:59.639   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 11:14:59.989  1016  1096 V AlarmManager: waitForAlarm result :8,
,08-22 11:15:00.119  1016  1041 W ActivityManager: mDVFSHelper.release()
,08-22 11:15:00.639   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 11:15:01.619   288   288 E SMD     : DCD OFF,
,08-22 11:15:01.639   331   331 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-22 11:15:01.749  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-22 11:15:01.749  6774  6827 I jxcore-log: 
,08-22 11:15:01.749  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-22 11:15:01.749  6774  6827 I jxcore-log: 
,08-22 11:15:01.759  6774  6827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:01.759  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:01.759  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:01.759  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:01.759  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:01.759  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:01.759  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:01.759  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:01.759  6774  6827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:01.759  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-22 11:15:01.759  6774  6827 I jxcore-log: 
,08-22 11:15:01.759  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-22 11:15:01.759  6774  6827 I jxcore-log: 
,08-22 11:15:02.409  6774  6827 D ExecuteNativeTests: Running unit tests
,08-22 11:15:02.469  1016  1096 V AlarmManager: waitForAlarm result :4
,08-22 11:15:02.479  1016  1096 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-22 11:15:02.479  1016  1016 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-22 11:15:02.489  1016  1016 V AlarmManagerEXT: <AppSync3 Whitelist>
08-22 11:15:02.489  1016  1016 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-22 11:15:02.489  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-22 11:15:02.489  1174  1174 D KeyguardUpdateMonitor: handleTimeUpdate
,08-22 11:15:02.499  1174  1174 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-22 11:15:02.499  1174  1174 D SecKeyguardClockView: HomeTimezone(): 1
,08-22 11:15:02.509  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-22 11:15:02.509  1174  1174 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-22 11:15:02.509  1174  1174 I KeyguardEffectViewController: *** don't update sliding image ***
,08-22 11:15:02.519  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:02.519  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd added. We now have 2 listener(s)
,08-22 11:15:02.519  1981  1981 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-22 11:15:02.529  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-22 11:15:02.529  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:02.529  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:02.529  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:02.529  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 added. We now have 2 listener(s)
08-22 11:15:02.529  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:02.529  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 11:15:02.529  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:02.539  6774  6827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:02.539  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:02.539  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:02.539  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:02.539  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:02.539  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:02.539  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:02.539  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:02.539  6774  6827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:02.539  6774  6827 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:15:02.549  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-22 11:15:02.549  6774  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 11:15:02.549  6774  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-22 11:15:02.549  6774  6827 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-22 11:15:02.549  6774  6827 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-22 11:15:02.549  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 11:15:02.549  6774  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 11:15:02.549  6774  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 11:15:02.549  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:02.549  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:02.549  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:02.549  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:02.549  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:02.549  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:02.549  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:02.549  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:02.549  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd removed from the list
,08-22 11:15:02.549  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:02.549  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 removed from the list
,08-22 11:15:02.549  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:02.559  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:02.559  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:02.559  1016  3768 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:15:02.559  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:02.559  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:02.559  1016  3768 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-22 11:15:02.559  1016  3768 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:02.559  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:02.559  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:02.559  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:02.559  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
,08-22 11:15:02.559  1016  3768 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:02.559  1016  3768 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:02.559  6774  6827 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-22 11:15:02.559  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:02.559  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:02.559  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:02.559  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:02.559  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:02.559  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:02.559  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:02.559  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:02.559  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:02.559  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:02.559  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:02.559  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:02.559  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:02.559  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:02.569  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-22 11:15:02.569  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:02.569  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:02.569  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:02.569  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-22 11:15:02.569  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:02.569  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:02.569  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:02.569  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:02.569  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:02.569  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:02.569  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:02.569  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:02.569  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:02.569  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:02.569  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:02.569  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:02.569  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:02.569  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:02.569  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:02.569  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:02.569  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:02.569  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:02.569  6774  6827 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-22 11:15:02.579  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:02.579  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-22 11:15:02.579  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-22 11:15:02.579  6774  6827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:02.579  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:02.579  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:02.579  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:02.579  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:02.579  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:02.579  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:02.579  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 11:15:02.589  6774  6827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:02.589  6774  6827 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 11:15:02.589  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:02.589  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 11:15:02.589  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 11:15:02.589  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:02.589  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 11:15:02.589  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:02.589  1174  1174 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
08-22 11:15:02.589  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:02.599  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 11:15:02.599  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-22 11:15:02.619  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-22 11:15:02.629  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-22 11:15:02.629  6774  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-22 11:15:02.639  6774  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-22 11:15:02.639  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 11:15:02.639  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 11:15:02.639  6774  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-22 11:15:02.639  4824  4824 D ConnectivityManager: CallingUid : 10011, CallingPid : 4824
08-22 11:15:02.639  1016  3765 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-22 11:15:02.639  1016  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501],
08-22 11:15:02.639  1016  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-22 11:15:02.639  1016  1128 D ConnectivityService: apparently satisfied.  currentScore=60
08-22 11:15:02.649  4824  6838 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-22 11:15:02.659  3174  3197 D BtGatt.GattService: registerClient() - UUID=8206c5fa-95b5-4062-8f9f-6992ea836186
,08-22 11:15:02.699  3174  3285 D BtGatt.GattService: onClientRegistered() - UUID=8206c5fa-95b5-4062-8f9f-6992ea836186, clientIf=6
,08-22 11:15:02.709  6774  6784 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-22 11:15:02.709  3174  5213 D BtGatt.GattService: start scan with filters
,08-22 11:15:02.709  3174  3295 D BtGatt.ScanManager: handling starting scan
,08-22 11:15:02.709  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 11:15:02.709  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 11:15:02.709  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 11:15:02.709  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 11:15:02.709  3174  3295 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:02.709  4824  6840 W DriveInitializer: Background init thread started
,08-22 11:15:02.719  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:02.719  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:02.719  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 11:15:02.719  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 11:15:02.719  3174  3285 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-22 11:15:02.719  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:02.719  3174  3295 D BtGatt.ScanManager: allow scan with filters
08-22 11:15:02.719  3174  3295 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-22 11:15:02.729  3174  3295 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-22 11:15:02.729  6774  6827 I io.jxcore.node.ConnectionHelper: start: OK
,08-22 11:15:02.729  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:02.729  3174  3285 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-22 11:15:02.729  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:02.729  6774  6827 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 11:15:02.729  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:02.729  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 11:15:02.729  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:02.729  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 11:15:02.729  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 11:15:02.729  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 11:15:02.729  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:02.729  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-22 11:15:02.729  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 11:15:02.729  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 11:15:02.729  3174  3295 D BtGatt.ScanManager: Starting BLE batch scan
,08-22 11:15:02.729  3174  3295 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-22 11:15:02.729  3174  3197 D BtGatt.GattService: stopScan() - queue size =1
,08-22 11:15:02.739  3174  5213 D BtGatt.GattService: unregisterClient() - clientIf=6
08-22 11:15:02.739  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 11:15:02.739  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 11:15:02.739  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 11:15:02.739  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 11:15:02.739  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 11:15:02.739  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:02.739  3174  3285 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-22 11:15:02.739  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:02.739  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 11:15:02.739  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 11:15:02.739  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 11:15:02.739  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:02.739  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:02.739  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:02.739  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:02.739  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:02.739  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:02.739  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:02.739  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:02.739  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:02.739  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:02.739  6774  6827 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-22 11:15:02.739  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:02.739  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:02.749  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:02.749  3174  3285 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-22 11:15:02.749  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:02.749   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-22 11:15:02.749   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 11:15:02.749  3174  3295 D BtGatt.ScanManager: filter size is 1
08-22 11:15:02.749  3174  3295 D BtGatt.ScanManager: delete FilterIndex - 3
,08-22 11:15:02.759  6774  6827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:02.759  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:02.759  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:02.759  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:02.759  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:02.759  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:02.759  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:02.759  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 11:15:02.759  4824  6840 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
08-22 11:15:02.759  6774  6827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:02.759  6774  6827 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 11:15:02.759  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:02.759  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 11:15:02.759  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 11:15:02.759  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:02.759  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 11:15:02.759  3174  3285 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-22 11:15:02.759  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:02.759  3174  3295 D BtGatt.ScanManager: stopping BLe Batch
08-22 11:15:02.759  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-22 11:15:02.769  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:02.769  3174  3285 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-22 11:15:02.769  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:02.769  3174  3295 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-22 11:15:02.769  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:02.769  3174  3285 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-22 11:15:02.779  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:02.779  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-22 11:15:02.779  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-22 11:15:02.789  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 11:15:02.789  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 11:15:02.789  6774  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-22 11:15:02.789  3174  5213 D BtGatt.GattService: registerClient() - UUID=ad75f105-74f3-49c6-a215-b5367824275e
08-22 11:15:02.799  1981  1981 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-22 11:15:02.829  3174  3285 D BtGatt.GattService: onClientRegistered() - UUID=ad75f105-74f3-49c6-a215-b5367824275e, clientIf=6
,08-22 11:15:02.829  6774  6784 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-22 11:15:02.829  3174  3290 D BtGatt.GattService: start scan with filters
,08-22 11:15:02.829  3174  3295 D BtGatt.ScanManager: handling starting scan
,08-22 11:15:02.839  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 11:15:02.839  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 11:15:02.839  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 11:15:02.839  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 11:15:02.839  1016  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 11:15:02.839  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:02.839  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.net.NetworkReportService; callingUser = 0; userId(target) = 0
,08-22 11:15:02.839  3174  3285 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-22 11:15:02.839  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:02.839  3174  3295 D BtGatt.ScanManager: allow scan with filters
,08-22 11:15:02.839  3174  3295 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-22 11:15:02.839  3174  3295 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
08-22 11:15:02.839  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 11:15:02.839  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-22 11:15:02.839  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:02.839  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:02.839  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:02.849  3174  3285 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-22 11:15:02.849  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:02.849  3174  3295 D BtGatt.ScanManager: Starting BLE batch scan
08-22 11:15:02.849  3174  3295 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 11:15:02.849  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 11:15:02.859  3174  3285 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-22 11:15:02.859  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,08-22 11:15:02.869  3174  3285 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-22 11:15:02.869  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:02.869  6774  6827 I io.jxcore.node.ConnectionHelper: start: OK
,08-22 11:15:02.879  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:02.879  6774  6827 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 11:15:02.879  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:02.879  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 11:15:02.879  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:02.879  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 11:15:02.879  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 11:15:02.879  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 11:15:02.879  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:02.879  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 11:15:02.879  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 11:15:02.879  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 11:15:02.879  3174  3197 D BtGatt.GattService: stopScan() - queue size =1
,08-22 11:15:02.879  3174  5213 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 11:15:02.889  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 11:15:02.889  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 11:15:02.889  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 11:15:02.889  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 11:15:02.889  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 11:15:02.889  3174  3295 D BtGatt.ScanManager: filter size is 1
08-22 11:15:02.889  3174  3295 D BtGatt.ScanManager: delete FilterIndex - 4
,08-22 11:15:02.889  4824  5168 D NetworkUsageDbReporter: Started reporting usage
,08-22 11:15:02.889  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:02.889  1016  1492 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-22 11:15:02.889  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 11:15:02.889  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 11:15:02.889  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 11:15:02.889  1016  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,08-22 11:15:02.889  1016  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:02.889  1016  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:02.889  1016  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:02.889  3174  3285 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-22 11:15:02.889  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:02.889  3174  3295 D BtGatt.ScanManager: stopping BLe Batch
,08-22 11:15:02.899  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:02.899  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:02.899  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:02.899  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:02.899  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:02.899  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:02.899  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:02.899  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:02.899  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:02.899  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:02.899  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:02.899  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:02.899  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:02.899  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:02.899  3174  3285 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-22 11:15:02.899  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:02.899  3174  3295 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-22 11:15:02.899  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:02.899  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:02.899  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:02.899  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
,08-22 11:15:02.899  3174  3285 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-22 11:15:02.899  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:02.899  6774  6827 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-22 11:15:02.899  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:02.909  1016  1487 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:15:02.909  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-22 11:15:02.909  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:02.909  1016  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:02.909  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:02.919  6774  6827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:02.919  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:02.919  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:02.919  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:02.919  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:02.919  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:02.919  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:02.919  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:02.919  6774  6827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:02.919  6774  6827 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:15:02.919  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:02.919  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:02.919  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-22 11:15:02.919  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 11:15:02.919  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 11:15:02.919  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:02.919  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 11:15:02.929  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 11:15:02.929  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 11:15:02.929  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 11:15:02.939  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 11:15:02.939  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 11:15:02.939  6774  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 11:15:02.939  4824  6840 W DriveInitializer: Background init thread ended
,08-22 11:15:02.949  1016  1029 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-22 11:15:02.949  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-22 11:15:02.949  3174  5213 D BtGatt.GattService: registerClient() - UUID=965a5cfc-0314-49cb-89ee-e45bed03bdb4
,08-22 11:15:02.989  3174  3285 D BtGatt.GattService: onClientRegistered() - UUID=965a5cfc-0314-49cb-89ee-e45bed03bdb4, clientIf=6
08-22 11:15:02.989  6774  6784 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-22 11:15:02.989  3174  3197 D BtGatt.GattService: start scan with filters
08-22 11:15:02.989  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 11:15:02.989  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 11:15:02.989  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 11:15:02.989  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-22 11:15:02.989  3174  3295 D BtGatt.ScanManager: handling starting scan
,08-22 11:15:02.999  3174  3285 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-22 11:15:02.999  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:02.999  3174  3295 D BtGatt.ScanManager: allow scan with filters
08-22 11:15:02.999  3174  3295 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-22 11:15:02.999  3174  3295 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-22 11:15:02.999  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 11:15:02.999  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 11:15:02.999  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 11:15:02.999  1981  1981 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-22 11:15:03.009  3174  3285 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-22 11:15:03.009  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:03.009  3174  3295 D BtGatt.ScanManager: Starting BLE batch scan
08-22 11:15:03.009  3174  3295 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 11:15:03.009  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 11:15:03.009  4824  5168 D NetworkUsageDbReporter: Finished reporting usage.
,08-22 11:15:03.009  3174  3285 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-22 11:15:03.009  6774  6827 I io.jxcore.node.ConnectionHelper: start: OK
08-22 11:15:03.009  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:03.009  6774  6827 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 11:15:03.009  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:03.009  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 11:15:03.009  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.009  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 11:15:03.009  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 11:15:03.009  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 11:15:03.009  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:03.009  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 11:15:03.009  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 11:15:03.009  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 11:15:03.009  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:03.019  3174  3191 D BtGatt.GattService: stopScan() - queue size =1
,08-22 11:15:03.019  3174  5213 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 11:15:03.019  3174  3285 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-22 11:15:03.019  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:03.019  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 11:15:03.019  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 11:15:03.019  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 11:15:03.019  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 11:15:03.019  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 11:15:03.029  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:03.029  3174  3295 D BtGatt.ScanManager: filter size is 1
08-22 11:15:03.029  3174  3295 D BtGatt.ScanManager: delete FilterIndex - 5
,08-22 11:15:03.029  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 11:15:03.029  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 11:15:03.029  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 11:15:03.029  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:03.029  3174  3285 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-22 11:15:03.029  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:03.029  3174  3295 D BtGatt.ScanManager: stopping BLe Batch
,08-22 11:15:03.029  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:03.029  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:03.029  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:03.029  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:03.029  6774  6827 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 11:15:03.029  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:03.029  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:03.029  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.029  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.029  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:03.029  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.029  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.029  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.029  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:03.029  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:03.029  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.029  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:03.039  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:03.039  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:03.039  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.039  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
,08-22 11:15:03.039  3174  3285 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-22 11:15:03.039  6774  6827 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-22 11:15:03.039  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:03.039  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:03.039  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:03.039  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:03.039  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.039  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.039  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.039  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.039  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.039  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.039  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:03.039  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.039  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.039  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.039  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:03.039  3174  3295 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-22 11:15:03.039  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:03.039  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:03.039  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.039  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
,08-22 11:15:03.039  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-22 11:15:03.039  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:03.039  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:03.039  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:03.039  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.039  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.039  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.039  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.039  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.039  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.039  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:03.039  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.039  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.039  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.039  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:03.039  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 11:15:03.039  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:03.039  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.039  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
,08-22 11:15:03.039  6774  6827 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-22 11:15:03.039  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:03.039  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:03.039  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:03.039  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.039  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.039  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.039  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.039  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.039  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.039  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:03.049  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.049  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.049  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.049  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:03.049  3174  3285 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-22 11:15:03.049  3174  3285 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:03.049  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:03.049  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:03.049  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.049  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
,08-22 11:15:03.049  6774  6827 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-22 11:15:03.049  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:03.049  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:03.049  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:03.049  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.049  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.049  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.049  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.049  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.049  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.049  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:03.049  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.049  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.049  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.049  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:03.049  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:03.049  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:03.049  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.049  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.049  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.049  1016  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.049  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.049  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 11:15:03.049  6774  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 11:15:03.049  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 11:15:03.049  6774  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 11:15:03.049  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 11:15:03.049  6774  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 11:15:03.049  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:03.049  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:03.049  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:03.049  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.049  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.049  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.049  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.049  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.049  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.049  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:03.049  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.049  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.049  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.049  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:03.049  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:03.049  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:03.049  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.049  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
,08-22 11:15:03.059  6774  6827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 11:15:03.059  6774  6827 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-22 11:15:03.059  6774  6827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 11:15:03.059  6774  6827 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 11:15:03.059  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-22 11:15:03.059  6774  6827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-22 11:15:03.059  6774  6827 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 11:15:03.059  6774  6827 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-22 11:15:03.059  6774  6827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 11:15:03.059  6774  6827 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 11:15:03.059  6774  6827 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-22 11:15:03.059  6774  6827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 11:15:03.059  6774  6827 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 11:15:03.059  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-22 11:15:03.059  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-22 11:15:03.059  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-22 11:15:03.059  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-22 11:15:03.069  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55,
08-22 11:15:03.069  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-22 11:15:03.069  6774  6827 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-22 11:15:03.069  6774  6827 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 11:15:03.069  6774  6827 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-22 11:15:03.069  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:03.069  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:03.069  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 11:15:03.069  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.069  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.069  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.069  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-22 11:15:03.069  6774  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1314)
,08-22 11:15:03.069  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.069  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.069  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.069  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:03.069  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.069  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.069  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.069  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:03.069  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:03.069  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:03.069  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.069  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
,08-22 11:15:03.069  6774  6827 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-22 11:15:03.069  6774  6854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1314
,08-22 11:15:03.069  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:03.069  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:03.069  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:03.069  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.069  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.069  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.069  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.069  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.069  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.069  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:03.069  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:03.069  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.069  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.069  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:03.079  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:03.079  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:03.079  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.079  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
,08-22 11:15:03.079  6774  6827 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-22 11:15:03.079  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:03.079  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:03.079  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:03.079  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.079  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.079  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.079  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.079  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.079  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.079  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:03.079  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.079  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.079  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.079  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:03.079  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:03.079  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:03.079  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.079  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
,08-22 11:15:03.079  6774  6827 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-22 11:15:03.079  6774  6827 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-22 11:15:03.079  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 11:15:03.079  6774  6827 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-22 11:15:03.079  6774  6827 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-22 11:15:03.079  6774  6827 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-22 11:15:03.079  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 11:15:03.079  6774  6827 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-22 11:15:03.079  6774  6827 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-22 11:15:03.079  6774  6827 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-22 11:15:03.079  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 11:15:03.079  6774  6827 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-22 11:15:03.079  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:03.079  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:03.079  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:03.079  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.079  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.079  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.079  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.079  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.079  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.079  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:03.079  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.079  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.079  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.079  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1, listener(s) left
08-22 11:15:03.079  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:03.079  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:03.079  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:03.089  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.089  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.089  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.089  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.089  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.089  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:03.089  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.089  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.089  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.089  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.089  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.089  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.089  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:03.089  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:03.089  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.089  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.089  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.089  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.089  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.089  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:03.089  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not e,xist in the list - probably already removed
08-22 11:15:03.089  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.089  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.089  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.089  6774  6853 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.089  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
,08-22 11:15:03.089  6774  6853 D BluetoothSocket: connect(): myUserId = 0
08-22 11:15:03.089  6774  6853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 11:15:03.089  6774  6827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-22 11:15:03.089  6774  6827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-22 11:15:03.089  3174  3197 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:03.089  6774  6827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-22 11:15:03.089  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-22 11:15:03.089  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.089  6774  6827 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-22 11:15:03.089  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.089  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 11:15:03.089  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:03.089  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 11:15:03.089  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.089  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.089  6774  6774 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-22 11:15:03.089  6774  6774 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-22 11:15:03.089  6774  6853 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
,08-22 11:15:03.099  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:03.099  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.099  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:03.099  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:03.099  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:03.099  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:03.099  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:03.099  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.099  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.099  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:03.099  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.099  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.099  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.099  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.099  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:03.099  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.099  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.099  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.099  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:03.099  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:03.099  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:03.099  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.099  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
,08-22 11:15:03.099  6774  6855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-22 11:15:03.099  6774  6827 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-22 11:15:03.099  6774  6827 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-22 11:15:03.099  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-22 11:15:03.099  6774  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 11:15:03.099  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:03.099  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:03.099  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:03.099  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.099  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.099  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.099  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.099  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.099  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.099  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:03.099  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.099  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.099  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.099  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:03.099  6774  6855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-22 11:15:03.099  6774  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-22 11:15:03.099  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:03.099  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:03.099  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.099  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
,08-22 11:15:03.109  1016  3768 I art     : Explicit concurrent mark sweep GC freed 40503(2MB) AllocSpace objects, 18(288KB) LOS objects, 33% free, 24MB/36MB, paused 2.879ms total 164.366ms
,08-22 11:15:03.109  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:03.109  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:03.109  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:03.109  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.109  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.109  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.109  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.109  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.109  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.109  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:03.109  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.109  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.109  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.109  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:03.109  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:03.109  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:03.109  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.109  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
,08-22 11:15:03.119  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:03.119  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:03.119  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:03.119  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:03.119  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.119  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.119  6774  6827 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7d6fd not in the list
08-22 11:15:03.119  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.119  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
08-22 11:15:03.119  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:03.119  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.119  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:03.119  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:03.119  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:03.119  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:03.119  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:03.119  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:03.119  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31b5cff2 not in the list
,08-22 11:15:03.119  6774  6827 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-22 11:15:03.119  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 11:15:03.119  6774  6827 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-22 11:15:03.119  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 11:15:03.119  6774  6827 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-22 11:15:03.119  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-22 11:15:03.119  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-22 11:15:03.119  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-22 11:15:03.119  6774  6827 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-22 11:15:03.119  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-22 11:15:03.119  6774  6827 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-22 11:15:03.119  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-22 11:15:03.119  6774  6827 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-22 11:15:03.119  6774  6827 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-22 11:15:03.119  6774  6827 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-22 11:15:03.119  6774  6827 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-22 11:15:03.119  6774  6827 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-22 11:15:03.119  6774  6827 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-22 11:15:03.119  6774  6827 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-22 11:15:03.119  6774  6827 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-22 11:15:03.129  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:03.129  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b589d84 added. We now have 2 listener(s)
08-22 11:15:03.129  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:03.129  6774  6827 D BluetoothAdapter: enable()
,08-22 11:15:03.129  6774  6827 D BluetoothAdapter: enable(): BT is already enabled..!
,08-22 11:15:03.129  1016  1536 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-22 11:15:03.129  1016  1536 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-22 11:15:03.129  1016  1536 D SecContentProvider2: mCursor = null
,08-22 11:15:03.139  1016  1536 D WifiService: setWifiEnabled: true pid=6774, uid=10171
,08-22 11:15:03.139  1016  1536 W ActivityManager: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-22 11:15:03.149  1016  1536 W WifiService: Failed getting userId using ActivityManagerNative
08-22 11:15:03.149  1016  1536 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-22 11:15:03.149  1016  1536 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 11:15:03.149  1016  1536 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-22 11:15:03.149  1016  1536 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-22 11:15:03.149  1016  1536 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-22 11:15:03.149  1016  1536 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-22 11:15:03.149  1016  1536 D SettingsProvider: name = wifi_on
,08-22 11:15:03.149  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:03.149  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd1796d added. We now have 3 listener(s)
08-22 11:15:03.149  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:03.159  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:03.159  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f7e19a2 added. We now have 4 listener(s)
08-22 11:15:03.159  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:03.159  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:03.159  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9cc7633 added. We now have 5 listener(s)
08-22 11:15:03.159  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:03.159  1016  1487 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-22 11:15:03.159  1016  1487 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed,
08-22 11:15:03.159  1016  1487 D SecContentProvider2: mCursor = null
08-22 11:15:03.169  1016  1487 D WifiService: setWifiEnabled: false pid=6774, uid=10171
08-22 11:15:03.169  1016  1487 D SettingsProvider: name = wifi_on
,08-22 11:15:03.179  6774  6827 D BluetoothAdapter: disable()
,08-22 11:15:03.179  1016  1126 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-22 11:15:03.179  1346  1346 I wpa_supplicant: reset timer : RESET_TIMER 0
08-22 11:15:03.179  1346  1346 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-22 11:15:03.179  1346  1346 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-22 11:15:03.189  1346  1346 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-22 11:15:03.189  1016  1428 D SettingsProvider: name = bluetooth_on
,08-22 11:15:03.189  1016  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 11:15:03.199  3174  3282 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-22 11:15:03.199  3174  3282 D BluetoothAdapterProperties: Setting state to 13
08-22 11:15:03.199  3174  3282 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-22 11:15:03.199  3174  3282 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 11:15:03.199  3174  3282 D BluetoothAdapterService: updateAdapterState state is 13
08-22 11:15:03.209  1016  3767 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:03.209  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:03.209  1016  3767 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 11:15:03.209  1016  3767 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.209  1016  3767 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:03.209  1016  3767 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:03.209  3174  3174 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-22 11:15:03.209  3174  3282 D BluetoothAdapterService: Autoconnection is available 
,08-22 11:15:03.209  3174  3282 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-22 11:15:03.209  3174  3282 D BluetoothAdapterService: terminating service from this receiver
,08-22 11:15:03.209  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-22 11:15:03.209  3174  3174 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c9f3f20, channel: 19, state: LISTENING
,08-22 11:15:03.209  3174  3174 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3c9f3f20, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e72eea1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@7c9d0d9mSocket: android.net.LocalSocket@2f663a9e impl:android.net.LocalSocketImpl@897497f fd:FileDescriptor[76]
,08-22 11:15:03.209  3174  3174 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2f663a9e impl:android.net.LocalSocketImpl@897497f fd:FileDescriptor[76]
,08-22 11:15:03.209  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.209  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:03.209  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:03.219  1346  1346 I wpa_supplicant: nl80211: Received scan results (19 BSSes)
,08-22 11:15:03.219  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:03.219  6774  6827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:03.219  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:03.219  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:03.219  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:03.219  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:03.219  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:03.219  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:03.219  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:03.219  3174  3282 D BluetoothAdapterProperties: onBluetoothDisable()
08-22 11:15:03.219  3174  3282 D BluetoothAdapterProperties: mDiscovering is false
,08-22 11:15:03.219  1016  1125 D WifiP2pService: InactiveState{ what=147461 }
08-22 11:15:03.219  1016  3764 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-22 11:15:03.219  1016  1125 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-22 11:15:03.219  3174  3282 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-22 11:15:03.219  1016  1125 D WifiP2pService: DefaultState{ what=147461 }
,08-22 11:15:03.219  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:03.219  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
,08-22 11:15:03.219  1016  1126 E WifiNative-wlan0: do suspend true
,08-22 11:15:03.229  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:03.229  6774  6827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:03.229  6774  6827 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:15:03.229  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-22 11:15:03.229  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-22 11:15:03.229  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:03.229  1174  1174 D BluetoothTile:  getBluetoothState : 13
,08-22 11:15:03.229  1919  1919 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 11:15:03.229  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:03.239  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:03.239  1174  1671 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:03.239  1016  1492 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-22 11:15:03.239  1981  2185 I art     : Explicit concurrent mark sweep GC freed 64597(3MB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 10MB/17MB, paused 1.186ms total 85.701ms
,08-22 11:15:03.249  1174  1671 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:03.249  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-22 11:15:03.249  1016  3767 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-22 11:15:03.249  1174  1671 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-22 11:15:03.249  3060  3060 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:03.249  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-22 11:15:03.259  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:03.259  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:03.259  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:03.259  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:03.259  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:03.259  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:03.259  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:03.259  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:03.259  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:03.259  3174  3285 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 11:15:03.259  3174  3285 D BluetoothAdapterProperties: Scan Mode:20
,08-22 11:15:03.259  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:03.259  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:03.259  3174  3282 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-22 11:15:03.259  3174  3282 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-22 11:15:03.259  3174  3282 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-22 11:15:03.259  3174  3282 E bt-btif : cmd socket is not created
,08-22 11:15:03.259  3174  5219 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 11:15:03.259  3174  3317 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,08-22 11:15:03.259  3174  3317 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-22 11:15:03.269  3174  3317 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 11:15:03.269  3174  3317 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 11:15:03.269  3174  3317 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-22 11:15:03.269  6774  6853 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@a193f69, channel: -1, state: INIT
08-22 11:15:03.269  6774  6853 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@a193f69, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@32482dee, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ace428fmSocket: android.net.LocalSocket@bb4191c impl:android.net.LocalSocketImpl@22fd6925 fd:FileDescriptor[105]
08-22 11:15:03.269  6774  6853 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@bb4191c impl:android.net.LocalSocketImpl@22fd6925 fd:FileDescriptor[105]
08-22 11:15:03.269  3174  3282 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-22 11:15:03.269  6774  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1314)
,08-22 11:15:03.269  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:03.269  3060  3060 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 11:15:03.279  1016  1214 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-22 11:15:03.279  1016  1214 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 11:15:03.279  1016  1214 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.279  1016  1214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:03.279  1016  1214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 11:15:03.279  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:03.279  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:03.279  3060  3060 D BluetoothPbap: Proxy object disconnected
08-22 11:15:03.279  3060  3060 D PbapServerProfile: Bluetooth service disconnected
,08-22 11:15:03.279  3174  3174 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@18092d4c, channel: 5, state: LISTENING
08-22 11:15:03.279  3174  3174 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@18092d4c, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21369708, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c7da195mSocket: android.net.LocalSocket@36f762aa impl:android.net.LocalSocketImpl@e0fe9b fd:FileDescriptor[74]
08-22 11:15:03.279  3174  3174 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@36f762aa impl:android.net.LocalSocketImpl@e0fe9b fd:FileDescriptor[74]
,08-22 11:15:03.279  3174  3174 I BtOppRfcommListener: stopping Accept Thread
08-22 11:15:03.279  3174  3174 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3441d238, channel: 12, state: LISTENING
08-22 11:15:03.279  3174  3174 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3441d238, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@345dee23, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1d63c211mSocket: android.net.LocalSocket@12c0ff76 impl:android.net.LocalSocketImpl@1546e977 fd:FileDescriptor[80]
08-22 11:15:03.279  3174  3174 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@12c0ff76 impl:android.net.LocalSocketImpl@1546e977 fd:FileDescriptor[80]
,08-22 11:15:03.279  3174  5219 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-22 11:15:03.289  3174  3174 V BluetoothOppManager: cleanUp...
,08-22 11:15:03.289  3060  3060 D DockEventReceiver: finishStartingService: stopping service
,08-22 11:15:03.289  3060  3060 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 11:15:03.299  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:03.299  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-22 11:15:03.299  1016  1428 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-22 11:15:03.299  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:03.299  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:03.299  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:03.299  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:03.319  6860  6860 E Zygote  : MountEmulatedStorage(),
08-22 11:15:03.319  6860  6860 E Zygote  : v2
08-22 11:15:03.319  6860  6860 I libpersona: KNOX_SDCARD checking this for 10055
08-22 11:15:03.319  6860  6860 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:03.319  1016  1428 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6860 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-22 11:15:03.329  6860  6860 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:03.329  6860  6860 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:03.329  6860  6860 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:03.359  1016  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 11:15:03.359  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-22 11:15:03.359  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.359  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.359  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.359  1016  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-22 11:15:03.359  1016  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-22 11:15:03.369   278  1015 D CommandListener: Clearing all IP addresses on wlan0
,08-22 11:15:03.369  1981  3014 V NativeCrypto: Read error: ssl=0xb906bc80: I/O error during system call, Connection timed out
,08-22 11:15:03.369  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:03.369  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-22 11:15:03.369  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:03.369  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:03.369  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:03.369  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:03.369  6860  6860 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:03.379  6860  6860 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:03.379  1016  1128 E ConnectivityService: updateNetworkInfo()
,08-22 11:15:03.379  1981  3014 V NativeCrypto: SSL shutdown failed: ssl=0xb906bc80: I/O error during system call, Broken pipe
,08-22 11:15:03.379  1016  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 11:15:03.379  1016  1128 E ConnectivityService: updateNetworkInfo()
,08-22 11:15:03.379  1016  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-22 11:15:03.379  1981  3014 E GCM     : Wifi connection closed with errorCode 20
,08-22 11:15:03.389  1016  1214 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-22 11:15:03.389  1016  1687 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 11:15:03.389  1016  1687 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 11:15:03.389  1016  1687 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-22 11:15:03.389  1016  1687 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:03.389  1016  1125 D WifiP2pService: InactiveState{ what=131204 }
08-22 11:15:03.389  1016  1687 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-22 11:15:03.389  1016  1687 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 11:15:03.389  1016  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-22 11:15:03.399  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-22 11:15:03.399  1016  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-22 11:15:03.399  1016  1687 I qtaguid : Tagging socket 329 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1016, getuid(): 1000
,08-22 11:15:03.399  1016  1687 I qtaguid : Untagging socket 329
,08-22 11:15:03.399  1016  1687 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 11:15:03.409  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1
,08-22 11:15:03.409  1016  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 11:15:03.409  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:03.409  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:03.409  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:03.419  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:03.419  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:03.419  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:03.419  1016  1016 D RttService: SCAN_AVAILABLE : 1
,08-22 11:15:03.419  1016  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 11:15:03.419  1016  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost,
08-22 11:15:03.419  1016  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-22 11:15:03.419  6860  6860 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
08-22 11:15:03.419  1016  1125 D WifiP2pService: P2pDisablingState,
08-22 11:15:03.419  1016  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
08-22 11:15:03.419  1016  1125 D WifiP2pService: p2p socket connection lost
08-22 11:15:03.419  1016  1125 D WifiP2pService: P2pDisabledState,
,08-22 11:15:03.429  1016  1126 E WifiNative-wlan0: do suspend true
,08-22 11:15:03.429  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-22 11:15:03.429  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-22 11:15:03.429  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-22 11:15:03.439  1016  1537 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 11:15:03.439  1016  1537 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
08-22 11:15:03.439  1016  1537 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.439  1016  1537 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.439  1016  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.439  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 11:15:03.439  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-22 11:15:03.439  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-22 11:15:03.439  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 11:15:03.439  1016  1046 D WifiDisplayController: disconnect
08-22 11:15:03.439  1016  1046 D WifiDisplayController: updateConnection
08-22 11:15:03.439  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 11:15:03.439  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 11:15:03.439  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-22 11:15:03.439  4824  6874 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-22 11:15:03.439  4824  6874 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-22 11:15:03.449  1016  3765 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-22 11:15:03.449  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-22 11:15:03.449  6860  6860 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-22 11:15:03.459  6860  6860 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-22 11:15:03.459  6860  6860 D UserAnalysis: Create SecureDbHelper
,08-22 11:15:03.459  6860  6860 D IntelligenceServiceApplication: onCreate()
08-22 11:15:03.469  3174  3369 I bt_userial_mct: exiting userial_read_thread
08-22 11:15:03.469  3174  3369 D bt_userial_mct: Leaving userial_evt_read_thread()
08-22 11:15:03.469  3174  3285 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-22 11:15:03.469  3174  3319 I bt_vendor: hw_epilog_process
08-22 11:15:03.469  3174  3317 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 11:15:03.469  3174  3317 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
08-22 11:15:03.469  3174  3317 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 11:15:03.469  3174  3317 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 11:15:03.469  3174  3317 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 11:15:03.469  3174  3317 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-22 11:15:03.469  3174  3317 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 11:15:03.469  1016  1428 I ActivityManager: Killing 6372:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
08-22 11:15:03.469  3174  3317 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 11:15:03.469  3174  3317 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration,
08-22 11:15:03.469  3174  3317 W bt-btif : ag scb idx 1 not allocated
08-22 11:15:03.469  3174  3317 W bt-btif : ag scb idx 2 not allocated
08-22 11:15:03.469  3174  3317 E bt-btif : BTA AG is already disabled, ignoring ...
08-22 11:15:03.469  3174  3285 D bt_userial_mct: userial_close
08-22 11:15:03.469  3174  3285 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-22 11:15:03.469  1016  1428 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-22 11:15:03.469  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:03.469  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:03.469  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:03.469  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:03.479  6860  6860 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-22 11:15:03.489  6881  6881 E Zygote  : MountEmulatedStorage()
08-22 11:15:03.489  6881  6881 E Zygote  : v2
08-22 11:15:03.489  6881  6881 I libpersona: KNOX_SDCARD checking this for 10105
08-22 11:15:03.489  6881  6881 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:03.489  6881  6881 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 11:15:03.489  1016  1428 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6881 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-22 11:15:03.489  6881  6881 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-22 11:15:03.489  1016  1214 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-22 11:15:03.489  6860  6860 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-22 11:15:03.499  6881  6881 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 11:15:03.499  6860  6860 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-22 11:15:03.499  1016  3767 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:15:03.499  1016  3767 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-22 11:15:03.499  1016  3767 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.499  1016  3767 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.499  1016  3767 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.519  6881  6881 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:03.519  6881  6881 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:03.549  1016  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-22 11:15:03.549  1016  1125 D WifiP2pService: DefaultState{ what=143375 }
,08-22 11:15:03.559  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 11:15:03.559  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:03.559  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:03.559  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:03.559  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:03.559  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:03.569  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:03.569   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 11:15:03.569   278  1011 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-22 11:15:03.569   278  1015 D CommandListener: Clearing all IP addresses on wlan0
,08-22 11:15:03.569  1016  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-22 11:15:03.569  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:03.569  1016  1128 V NetworkStats: updateIfacesLocked()
08-22 11:15:03.569  1016  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-22 11:15:03.569  1016  1687 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-22 11:15:03.569  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:03.569  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 11:15:03.569  1016  1687 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-22 11:15:03.569  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.569  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.569  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.579  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-22 11:15:03.579  1016  1128 V NetworkStats: performPollLocked() took 11ms
08-22 11:15:03.579  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:03.579  1346  1346 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-22 11:15:03.589  1016  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-22 11:15:03.589  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:03.589  1016  1128 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 11:15:03.589  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:03.589  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:03.589  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:03.589  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:03.589  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:03.589  1174  1652 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-22 11:15:03.589  1016  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-22 11:15:03.589  1481  1481 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-22 11:15:03.589  1481  1481 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 11:15:03.589  1016  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-22 11:15:03.589  1016  1687 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:03.589  1016  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-22 11:15:03.589  1016  1128 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,08-22 11:15:03.589  1016  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-22 11:15:03.589  4824  6838 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-22 11:15:03.589  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:03.589  1016  1126 D SecContentProvider2: mCursor = null
,08-22 11:15:03.599  6774  6774 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 11:15:03.599  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:03.599  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 11:15:03.599  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:03.599  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:03.599  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:03.599  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:03.599  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:03.599  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0),
,08-22 11:15:03.609  1174  1671 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-22 11:15:03.609  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:03.609  3060  3060 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:03.609  1174  1174 D HotspotTile: onReceive : 0, 0,
08-22 11:15:03.609  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:03.609  1016  1128 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 11:15:03.609  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:03.609  1016  1128 D ConnectivityService: nai.networkMonitor.doQuit()
08-22 11:15:03.609  1016  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-22 11:15:03.609  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-22 11:15:03.609  1016  1128 E ConnectivityService: updateNetworkInfo()
08-22 11:15:03.609  1016  1128 E ConnectivityService: updateNetworkInfo()
08-22 11:15:03.609  1016  1130 D Tethering: MasterInitialState.processMessage what=3
,08-22 11:15:03.609  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:03.609  1016  1123 V NetworkStats: updateIfacesLocked()
08-22 11:15:03.609  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-22 11:15:03.609  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:03.609  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:03.609  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:03.609  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:03.609  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:03.609  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:03.609  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:03.609  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:03.609  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 11:15:03.609  1016  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-22 11:15:03.619  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:03.619  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:03.619  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:03.619  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 11:15:03.619  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
08-22 11:15:03.619  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-22 11:15:03.619  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-22 11:15:03.619  1174  1174 D StatusBar.NetworkController: updateDataNetType()
08-22 11:15:03.619  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-22 11:15:03.619  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-22 11:15:03.619  1016  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-22 11:15:03.619  1016  1123 V NetworkStats: performPollLocked() took 8ms
08-22 11:15:03.619  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:03.619  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:03.619  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:03.619  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:03.619  1016  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-22 11:15:03.619  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:03.619  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-22 11:15:03.619  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-22 11:15:03.619  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-22 11:15:03.619  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:03.619  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 11:15:03.619  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:03.619  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:03.619  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:03.619  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:03.619  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:03.619  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:03.619  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:03.619  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:03.619  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:03.619  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:03.619  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:03.619  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:03.619  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:03.629  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:03.629  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:03.629  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:03.629  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:03.679  3174  3285 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-22 11:15:03.679  3174  3285 I bt_vendor: bluetooth satus is on
08-22 11:15:03.679  3174  3285 I bt_vendor: bt-vendor : resetting BT status
08-22 11:15:03.679  3174  3285 I bt_vendor: Starting hciattach daemon
08-22 11:15:03.679  3174  3285 I bt_vendor: try to set false
,08-22 11:15:03.679  3174  3285 I bt_vendor: Starting hciattach daemon
,08-22 11:15:03.679  3174  3285 I bt_vendor: try to set false
08-22 11:15:03.679  3174  3285 I bt_vendor: cleanup
,08-22 11:15:03.679  3174  3317 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-22 11:15:03.679  3174  3285 I GKI_LINUX: GKI_exit_task 0 done
08-22 11:15:03.679  3174  3285 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-22 11:15:03.679  3174  3282 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-22 11:15:03.679  3174  3282 D BtConfig.SecureMode: isSecureModeOn:false
08-22 11:15:03.679  3174  3282 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-22 11:15:03.679  3174  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-22 11:15:03.679  3174  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-22 11:15:03.679  3174  3282 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-22 11:15:03.679  1346  1346 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 11:15:03.689  1016  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:03.689  1016  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-22 11:15:03.689  1016  1492 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.689  1016  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:03.689  1016  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:03.689  3174  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-22 11:15:03.689  3174  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-22 11:15:03.689  3174  3174 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 11:15:03.689  3174  3282 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-22 11:15:03.689   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-22 11:15:03.689   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 11:15:03.689  6881  6905 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-22 11:15:03.699  3174  3174 D BtGatt.GattService: Received stop request...Stopping profile...
08-22 11:15:03.699  3174  3174 D BtGatt.GattService: stop()
08-22 11:15:03.699  3174  3174 D BtGatt.AdvertiseManager: advertise clients cleared
,08-22 11:15:03.699  1016  3768 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:03.699  1016  3768 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-22 11:15:03.699  1016  3768 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.699  1016  3768 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:03.699  1016  3768 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:03.699  3174  3174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
08-22 11:15:03.699   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-22 11:15:03.699   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 11:15:03.699  3174  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-22 11:15:03.699  3174  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-22 11:15:03.699  6881  6905 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-22 11:15:03.699  3174  3282 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-22 11:15:03.699  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:03.699  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 11:15:03.699  1481  1481 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:03.699  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.699  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:03.699  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:03.709  3174  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-22 11:15:03.709  3174  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-22 11:15:03.709  3174  3174 D HeadsetService: Received stop request...Stopping profile...
,08-22 11:15:03.709  3174  3282 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-22 11:15:03.709  1016  1428 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:03.709  1016  1428 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-22 11:15:03.709  1346  1346 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-22 11:15:03.709  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 11:15:03.709  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 11:15:03.709  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
08-22 11:15:03.709  1016  1428 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.709  1016  1428 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:03.709  1016  1428 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:03.709  3174  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-22 11:15:03.709  3174  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-22 11:15:03.719  3174  3174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:03.719  3174  3282 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-22 11:15:03.719  1481  1481 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 11:15:03.719  3060  3060 D HeadsetProfile: Bluetooth service disconnected
08-22 11:15:03.719  1016  3765 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:03.719  1016  3765 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.719  1016  3765 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-22 11:15:03.719  1016  3765 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:03.719  1016  3765 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 11:15:03.719  3174  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-22 11:15:03.719  3174  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-22 11:15:03.719  3174  3282 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-22 11:15:03.719  1016  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:03.719  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 11:15:03.719  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-22 11:15:03.719  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.719  1016  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:03.719  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:03.719  3174  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-22 11:15:03.719  3174  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-22 11:15:03.719  1481  1481 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-22 11:15:03.719  3174  3282 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-22 11:15:03.729  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:03.729  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-22 11:15:03.729  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:03.729  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:03.729  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:03.729  3174  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-22 11:15:03.729  3174  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 11:15:03.729  1481  1481 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:03.729  3174  3282 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-22 11:15:03.729  1016  1537 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:03.729  1016  1537 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-22 11:15:03.729  1016  1537 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.729  1016  1537 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:03.729  1016  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:03.729  3174  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:03.729  3174  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 11:15:03.729  3174  3282 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:03.739  3174  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-22 11:15:03.739  3174  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-22 11:15:03.739  3174  3282 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:03.739  3174  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-22 11:15:03.739  3174  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-22 11:15:03.739  3174  3282 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-22 11:15:03.739  3174  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-22 11:15:03.739  3174  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-22 11:15:03.739  3174  3282 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-22 11:15:03.739  3174  3174 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-22 11:15:03.739  1481  1481 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:03.739  1346  1346 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-22 11:15:03.739  1346  1346 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-22 11:15:03.739  1346  1346 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-22 11:15:03.739  1346  1346 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-22 11:15:03.739  1346  1346 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-22 11:15:03.739  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:03.739  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:03.739  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:03.739  3174  3282 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-22 11:15:03.739  3174  3174 D A2dpService: Received stop request...Stopping profile...,
08-22 11:15:03.749  1016  1130 D Tethering: InitialState.processMessage what=4
,08-22 11:15:03.749  3174  3304 D A2dpStateMachine: Exit Disconnected: -1
,08-22 11:15:03.749  1016  1130 E Tethering: No numeric data
08-22 11:15:03.749  1016  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 11:15:03.749  1016  1130 D Tethering: clearTetheredNotification()
,08-22 11:15:03.749  1481  1481 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:03.749  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 11:15:03.749  1481  1481 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:03.749  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-22 11:15:03.749  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:03.749  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:03.749  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:03.749  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:03.749  1481  1481 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:03.759  1481  1481 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:03.759  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 11:15:03.759  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:03.759  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 11:15:03.759  1174  1174 D HotspotTile: updateTetherState():false, false
,08-22 11:15:03.759  1481  1481 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:03.759  3174  3174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:03.759  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:03.759  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:03.759  1481  1481 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:03.769  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:03.769  1016  1123 V NetworkStats: performPollLocked() took 12ms
,08-22 11:15:03.769  1016  1016 D BluetoothA2dp: Proxy object disconnected
08-22 11:15:03.769  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-22 11:15:03.769  3174  3174 D HidService: Received stop request...Stopping profile...
08-22 11:15:03.769  3174  3174 D HidService: Stopping Bluetooth HidService
08-22 11:15:03.769  3174  3174 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-22 11:15:03.769  3174  3174 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-22 11:15:03.769  3174  3174 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-22 11:15:03.769  3174  3174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:03.769  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:03.769  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:03.769  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 11:15:03.769  1481  1481 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:03.769  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:03.769  3174  3174 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-22 11:15:03.769  3174  3174 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 11:15:03.769  3174  3174 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-22 11:15:03.779  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 11:15:03.779  1481  1481 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:03.779  1481  1481 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:03.779  3060  3060 D BluetoothA2dp: Proxy object disconnected
,08-22 11:15:03.779  3060  3060 D A2dpProfile: Bluetooth service disconnected
08-22 11:15:03.779  3060  3060 D BluetoothInputDevice: Proxy object disconnected
08-22 11:15:03.779  3060  3060 D HidProfile: Bluetooth service disconnected
,08-22 11:15:03.779  3174  3174 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-22 11:15:03.779  3174  3174 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-22 11:15:03.779  1481  1481 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:03.779  3174  3174 D HealthService: Received stop request...Stopping profile...
08-22 11:15:03.779  1481  1481 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 11:15:03.779  3174  3174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:03.789  3174  3174 D PanService: Received stop request...Stopping profile...
08-22 11:15:03.789  3174  3174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:03.789  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-22 11:15:03.789  3174  3174 D BluetoothMapService: Received stop request...Stopping profile...
,08-22 11:15:03.789  3060  3060 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-22 11:15:03.789  3060  3060 D PanProfile: Bluetooth service disconnected
,08-22 11:15:03.789  3174  3174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:03.789  1481  1481 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:03.799  3174  3174 D SapService: Received stop request...Stopping profile...
,08-22 11:15:03.799  3174  3174 D SapService: Stopping Bluetooth SapService
08-22 11:15:03.799  3174  3174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
08-22 11:15:03.799  1481  1481 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:03.799  3060  3060 D BluetoothMap: Proxy object disconnected
08-22 11:15:03.799  3060  3060 D MapProfile: Bluetooth service disconnected
08-22 11:15:03.799  1481  1481 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-22 11:15:03.799  3060  3060 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-22 11:15:03.799  3060  3060 D SapProfile: Bluetooth service disconnected
,08-22 11:15:03.799  3174  3174 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-22 11:15:03.799  3174  3174 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 11:15:03.799  3174  3174 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-22 11:15:03.799  3174  3174 D BluetoothA2dp: Proxy object disconnected
08-22 11:15:03.799  3174  3174 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-22 11:15:03.799  3174  3174 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-22 11:15:03.799  3174  3174 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:03.799  3174  3174 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:03.799   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7dda7c8
08-22 11:15:03.799   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-22 11:15:03.799  1481  1481 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 11:15:03.799   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-22 11:15:03.799  1481  1481 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-22 11:15:03.799   273   340 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1210211016)
08-22 11:15:03.799  3174  3305 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-22 11:15:03.799  3174  3174 I GKI_LINUX: GKI_exit_task 2 done
08-22 11:15:03.799  3174  3174 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-22 11:15:03.799  3174  3174 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-22 11:15:03.799  3174  3174 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:03.799  3174  3174 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:03.799  3174  3174 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-22 11:15:03.799  3174  3174 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-22 11:15:03.799  3174  3174 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-22 11:15:03.799  3174  3174 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:03.799  3174  3174 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:03.809  3174  3174 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 11:15:03.809  1481  1481 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 11:15:03.809  3174  3174 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-22 11:15:03.809  1481  1481 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-22 11:15:03.809  3174  3174 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-22 11:15:03.809  1481  1481 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 11:15:03.809  3174  3174 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 11:15:03.809  3174  3174 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-22 11:15:03.809  3174  3174 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-22 11:15:03.809  3174  3174 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-22 11:15:03.809  3174  3174 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-22 11:15:03.809  3174  3282 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-22 11:15:03.809  3174  3282 D BluetoothAdapterProperties: Setting state to 10
08-22 11:15:03.809  3174  3282 I BluetoothAdapterState: Blu,etooth adapter state changed: 13-> 10
08-22 11:15:03.809  3174  3282 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 11:15:03.809  3174  3282 D BluetoothAdapterService: updateAdapterState state is 10
08-22 11:15:03.809  3174  3282 D BluetoothAdapterService: Autoconnection is available 
08-22 11:15:03.809  3174  3282 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-22 11:15:03.809  3174  3282 I BluetoothAdapterState: Entering OffState
08-22 11:15:03.819  1456  1473 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:03.819  1456  1473 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:03.819  3060  3073 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-22 11:15:03.819  3060  3070 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:03.819  3060  3070 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:03.819  6774  6784 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:03.819  6774  6784 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 11:15:03.819  6774  6784 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-22 11:15:03.819  6774  6784 D BluetoothLeAdvertiser: Exit stop advertising
08-22 11:15:03.819  6774  6784 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-22 11:15:03.819  6774  6784 D BluetoothLeScanner: Exiting stopAllScan
,08-22 11:15:03.819  3060  3073 D BluetoothPbap: onBluetoothStateChange: up=false
,08-22 11:15:03.819  1481  1481 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:03.819  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 11:15:03.829  1481  1481 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 11:15:03.829  1481  1481 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:03.829  3060  3070 D BluetoothMap: onBluetoothStateChange: up=false
08-22 11:15:03.829  1481  1481 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 11:15:03.829  1481  1481 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 11:15:03.829  1481  1481 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 11:15:03.849  1446  1459 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:03.849  1446  1459 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:03.849  3060  3073 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 11:15:03.849  1174  1903 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:03.849  1174  1903 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 11:15:03.849  3060  3070 D Bluetoothsap: onBluetoothStateChange: up=false
08-22 11:15:03.849  3060  3070 D Bluetoothsap: Unbinding service...
08-22 11:15:03.849  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:03.849  1016  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 11:15:03.849  1481  1493 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:03.849  1481  1493 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 11:15:03.849  1981  2185 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:03.849  1981  2185 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:03.859  3174  3290 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 11:15:03.859  3174  3191 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 11:15:03.859  3174  3191 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:03.859  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-22 11:15:03.869  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-22 11:15:03.869   273   340 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-22 11:15:03.869   273   340 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-22 11:15:03.869   273   340 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1210211016) wakelock released: 1, error no: 0
08-22 11:15:03.869   273   340 I rmt_storage: 
,08-22 11:15:03.869   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7dda7c8
,08-22 11:15:03.869  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:03.879  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
,08-22 11:15:03.879  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-22 11:15:03.879  1346  1346 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 11:15:03.879  1174  1174 D BluetoothAdapter: 358947328: getState() :  mService = null. Returning STATE_OFF
08-22 11:15:03.879  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-22 11:15:03.879  1174  1671 D BluetoothAdapter: 358947328: getState() :  mService = null. Returning STATE_OFF
08-22 11:15:03.879  1174  1174 D BluetoothTile:  getBluetoothState : 10
08-22 11:15:03.879  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:03.879  1174  1671 D BluetoothAdapter: 358947328: getState() :  mService = null. Returning STATE_OFF
,08-22 11:15:03.879  1174  1174 D BluetoothAdapter: 358947328: getState() :  mService = null. Returning STATE_OFF
08-22 11:15:03.879  1174  1174 D BluetoothAdapter: 358947328: getState() :  mService = null. Returning STATE_OFF
08-22 11:15:03.879  1016  3767 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:03.879  1919  1919 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 11:15:03.889  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-22 11:15:03.889  1016  1537 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-22 11:15:03.889  1981  2215 D BluetoothAdapter: 542772662: getState() :  mService = null. Returning STATE_OFF
08-22 11:15:03.889  1981  2215 D BluetoothAdapter: 542772662: getState() :  mService = null. Returning STATE_OFF
,08-22 11:15:03.889  3060  3060 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:03.889  3174  3285 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-22 11:15:03.889  1016  1214 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:15:03.889  1016  1214 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-22 11:15:03.889  3174  3174 I GKI_LINUX: GKI_exit_task 1 done
08-22 11:15:03.889  1016  1214 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.889  1016  1214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.889  1016  1214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 11:15:03.889  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:03.889  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:03.889  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:03.889  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:03.889  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:03.889  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:03.889  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:03.889  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:03.889  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:03.889  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:03.889  3174  3174 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-22 11:15:03.899  3174  3174 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-22 11:15:03.899  3174  3174 I art     : System.exit called, status: 0
08-22 11:15:03.899  3174  3174 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-22 11:15:03.909  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.909  1016  1487 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-22 11:15:03.909  1016  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:03.909  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:03.909  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:03.909  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:03.909  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:03.909  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:03.919  1346  1346 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-22 11:15:03.919  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:03.919  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:03.919  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:03.929  6941  6941 E Zygote  : MountEmulatedStorage()
08-22 11:15:03.929  6941  6941 E Zygote  : v2
08-22 11:15:03.929  6941  6941 I libpersona: KNOX_SDCARD checking this for 10011
08-22 11:15:03.929  6941  6941 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:03.929  6941  6941 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:03.929  6941  6941 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:03.929  1016  1487 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6941 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
08-22 11:15:03.929  6941  6941 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 11:15:03.969  1016  1028 I ActivityManager: Process com.android.bluetooth (pid 3174)(adj 0) has died(25,728)
,08-22 11:15:03.969  6941  6941 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:15:03.969  6941  6941 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:03.979  6881  6881 D StrictMode: StrictMode policy violation; ~duration=275 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:03.979  6881  6881 D StrictMode: StrictMode policy violation; ~duration=274 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:03.979  6881  6881 D StrictMode: StrictMode policy violation; ~duration=273 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:03.979  6881  6881 D StrictMode: StrictMode policy violation; ~duration=272 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.q.e.b(PG:170)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:03.979  6881  6881 D StrictMode: StrictMode policy violation; ~duration=262 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.q.k.d(PG:583)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.q.e.b(PG:170)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:03.979  6881  6881 D StrictMode: StrictMode policy violation; ~duration=236 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:03.979  1016  1492 I ActivityManager: Killing 6477:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
08-22 11:15:03.979  6881  6881 D StrictMode: StrictMode policy violation; ~duration=235 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:03.989  6941  6941 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-22 11:15:03.979  6881  6881 D StrictMode: StrictMode policy violation; ~duration=235 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:03.979  6881  6881 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:03.989  6941  6941 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-22 11:15:03.989  1981  1981 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-22 11:15:03.989  1981  1981 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-22 11:15:03.999  1016  1214 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:03.999  1016  1214 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-22 11:15:03.999  1016  1214 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:03.999  1016  1214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:03.999  1016  1214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 11:15:03.999  1620  1620 I Hs20UtilService: Starting #8
08-22 11:15:03.999  1620  1640 I Hs20UtilService: Message received 5007
08-22 11:15:03.999  3060  3060 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 11:15:04.009  3060  3060 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-22 11:15:04.009  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-22 11:15:04.009  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 11:15:04.009  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 11:15:04.009  3060  3060 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 11:15:04.009  3060  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-22 11:15:04.019  3060  3060 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-22 11:15:04.019  3060  3060 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-22 11:15:04.029  1016  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-22 11:15:04.029  1016  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-22 11:15:04.029  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-22 11:15:04.029  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 11:15:04.029  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 11:15:04.029  3060  3060 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 11:15:04.029  3060  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-22 11:15:04.039  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:04.039  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 11:15:04.039  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:04.039  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:04.039  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:04.039  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:04.039  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:04.039  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-22 11:15:04.039  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:04.039  1174  1671 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 11:15:04.039  6941  6941 I MultiDex: VM with version 2.1.0 has multidex support
08-22 11:15:04.039  6941  6941 I MultiDex: install
08-22 11:15:04.039  6941  6941 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-22 11:15:04.039  1981  2215 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 11:15:04.039  3060  3060 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:04.049  1174  1174 D HotspotTile: onReceive : 1, 0
08-22 11:15:04.049  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:04.049  1016  1262 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-22 11:15:04.049  6881  6923 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-22 11:15:04.049  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:04.049  1016  1262 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:04.049  1016  1262 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:04.049  1016  1262 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:04.049  1016  1262 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:04.059  6958  6958 E Zygote  : MountEmulatedStorage()
,08-22 11:15:04.059  6958  6958 E Zygote  : v2
08-22 11:15:04.069  6958  6958 I libpersona: KNOX_SDCARD checking this for 10064
08-22 11:15:04.069  6958  6958 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:04.069  6958  6958 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:04.069  1016  1262 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6958 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 11:15:04.069  6958  6958 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:04.069  6958  6958 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:04.089  1016  1536 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:04.089  1016  1536 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:04.089  1016  1536 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:04.089  1016  1536 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-22 11:15:04.089  6958  6958 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:04.089  6958  6958 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:04.089  6941  6941 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-22 11:15:04.109  6958  6958 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-22 11:15:04.109  1016  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:04.109  1016  1016 I ApplicationPolicy: updateDataUsageMap
,08-22 11:15:04.129  1016  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:04.129  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:04.129  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:04.139  6958  6958 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 11:15:04.139  6958  6958 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-22 11:15:04.159  6941  6941 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-22 11:15:04.159  6941  6941 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@10bf46fa: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-22 11:15:04.159  6941  6941 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-22 11:15:04.179  6958  6958 D FileShare-Client: Outbound.stopDelayTimer - 
,08-22 11:15:04.179  1016  1428 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-22 11:15:04.179  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:04.179  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:04.179  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:04.179  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:04.189  6941  6941 D ChimeraCfgMgr: Reading stored module config
,08-22 11:15:04.199  6976  6976 E Zygote  : MountEmulatedStorage()
08-22 11:15:04.199  6976  6976 I libpersona: KNOX_SDCARD checking this for 10065
08-22 11:15:04.199  6976  6976 E Zygote  : v2
08-22 11:15:04.199  6976  6976 I libpersona: KNOX_SDCARD not a persona
08-22 11:15:04.199  6976  6976 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:04.199  6976  6976 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:04.199  6976  6976 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:04.209  1016  1428 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6976 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 11:15:04.229  6976  6976 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:04.239  6976  6976 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:04.269  6941  6975 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-22 11:15:04.269  6976  6976 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 11:15:04.279  1016  1428 I ActivityManager: Killing 6526:com.samsung.android.sm/1000 (adj 15): empty #21
,08-22 11:15:04.289  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:04.289  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:04.289  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-22 11:15:04.289  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-22 11:15:04.289  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:04.289  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:04.289  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:04.289  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:04.299  6992  6992 E Zygote  : MountEmulatedStorage()
,08-22 11:15:04.299  6992  6992 E Zygote  : v2
08-22 11:15:04.299  6992  6992 I libpersona: KNOX_SDCARD checking this for 10102
08-22 11:15:04.299  6992  6992 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:04.299  6992  6992 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:04.299  1016  1028 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6992 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
08-22 11:15:04.309  6992  6992 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:04.309  6941  6941 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
08-22 11:15:04.309  6941  6941 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
08-22 11:15:04.309  6992  6992 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 11:15:04.319  6992  6992 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:04.319  6992  6992 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:04.329  6941  6953 W art     : Suspending all threads took: 16.111ms
,08-22 11:15:04.329  1016  1487 I ActivityManager: Killing 6487:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-22 11:15:04.339  6941  6953 I art     : Background partial concurrent mark sweep GC freed 905(156KB) AllocSpace objects, 1(101KB) LOS objects, 39% free, 7MB/12MB, paused 20.211ms total 66.807ms
,08-22 11:15:04.349  6992  6992 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-22 11:15:04.399   283   283 D WVCdm   : Instantiating CDM.
,08-22 11:15:04.399   283   699 I WVCdm   : CdmEngine::OpenSession
,08-22 11:15:04.399  1016  3371 D SSRM:n  : SIOP:: AP = 340
08-22 11:15:04.399   283   699 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-22 11:15:04.429   283   699 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-22 11:15:04.449   283   699 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-22 11:15:04.489  6941  6954 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-22 11:15:04.489  6941  6954 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-22 11:15:04.489  6941  6954 I System.out: (HTTPLog)-Static: isShipBuild true
,08-22 11:15:04.489  6941  6954 I System.out: (HTTPLog)-Thread-1239-144132479: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-22 11:15:04.489  6941  6954 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 11:15:04.489   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 11:15:04.489   278  1011 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-22 11:15:04.499   283   699 I WVCdm   : CdmEngine::QueryKeyControlInfo
08-22 11:15:04.509   283   283 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-22 11:15:04.509   283   283 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-22 11:15:04.509   283   283 I WVCdm   : CdmEngine::GenerateKeyRequest
08-22 11:15:04.509   283   283 D WVCdm   : PrepareKeyRequest: nonce=2364140620
,08-22 11:15:04.509  1016  3411 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-22 11:15:04.519  1016  1043 D Tethering: interfaceRemoved wlan0
08-22 11:15:04.519  1016  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-22 11:15:04.589  7013  7013 I dex2oat : ----------------------------------------------------
08-22 11:15:04.589  7013  7013 I dex2oat : <SS>: S T A R T I N G . . .
08-22 11:15:04.589  7013  7013 I dex2oat : <SS>: Zip is absent. Canceled.
,08-22 11:15:04.589  7013  7013 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-22 11:15:04.619   288   288 E SMD     : DCD OFF
,08-22 11:15:04.629  1016  1043 D Tethering: interfaceRemoved p2p0
,08-22 11:15:04.629  1016  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-22 11:15:04.639  6992  7022 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-22 11:15:04.639  6992  7022 I Babel_SMS: MmsConfig.loadMmsSettings
08-22 11:15:04.639  6992  7022 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-22 11:15:04.639  6992  7022 I Babel_SMS: MmsConfig.loadFromDatabase
,08-22 11:15:04.639  7013  7013 I dex2oat : dex2oat took 49.207ms (threads: 4)
,08-22 11:15:04.649  6941  6954 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-22 11:15:04.649  6941  6954 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-22 11:15:04.649  6941  6954 I Adreno-EGL: Build Date: 04/06/15 Mon
08-22 11:15:04.649  6941  6954 I Adreno-EGL: Local Branch: 
08-22 11:15:04.649  6941  6954 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-22 11:15:04.649  6941  6954 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-22 11:15:04.649  6941  6954 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-22 11:15:04.659  6992  7022 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-22 11:15:04.659  6992  7022 I Babel_SMS: MmsConfig.loadFromResources
,08-22 11:15:04.659  6992  7022 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-22 11:15:04.659  6992  7022 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-22 11:15:04.689  1016  3765 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
08-22 11:15:04.689  1016  3765 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
08-22 11:15:04.699  1016  3765 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:04.699  1016  3765 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:04.699  1016  3765 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-22 11:15:04.729  6992  6992 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 11:15:04.729  6992  6992 I Babel_Crash: startup - clean
,08-22 11:15:04.739   283   699 I WVCdm   : CdmEngine::OpenSession
,08-22 11:15:04.769  1016  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:04.769  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:04.769  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:04.769  1016  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:04.769  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:04.779  1620  1620 I Hs20UtilService: Starting #9
,08-22 11:15:04.779  1620  1640 I Hs20UtilService: Message received 5007
,08-22 11:15:04.789  3060  3060 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
08-22 11:15:04.789  3060  3060 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 11:15:04.789  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 11:15:04.789  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 11:15:04.789  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 11:15:04.789  3060  3060 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 11:15:04.799  3060  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002,
08-22 11:15:04.799  6992  6992 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,08-22 11:15:04.799  6992  6992 W AudioCapabilities: Unsupported mime audio/evrc
,08-22 11:15:04.799  1016  1537 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 11:15:04.799  6992  6992 W AudioCapabilities: Unsupported mime audio/qcelp
08-22 11:15:04.799  1016  1537 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:04.799  1016  1537 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:04.809  1016  1537 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:04.809  1016  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:04.809  6992  6992 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-22 11:15:04.809  1620  1620 I Hs20UtilService: Starting #10
,08-22 11:15:04.809  1620  1640 I Hs20UtilService: Message received 5011
,08-22 11:15:04.809  6992  6992 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-22 11:15:04.809  6545  6545 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-22 11:15:04.809  6545  6545 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-22 11:15:04.809  6545  6545 D SecurityLogAgent: StateMachine : Current State = 1
,08-22 11:15:04.809  6992  6992 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-22 11:15:04.819  6992  6992 W AudioCapabilities: Unsupported mime audio/x-ima
,08-22 11:15:04.819  6545  6545 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-22 11:15:04.819  6992  6992 W AudioCapabilities: Unsupported mime audio/qcelp
,08-22 11:15:04.819  6992  6992 W AudioCapabilities: Unsupported mime audio/evrc
,08-22 11:15:04.829  1016  3764 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:04.829  1016  3764 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:04.829  1016  3764 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:04.829  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:04.829  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:04.829  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:04.829  6992  6992 W VideoCapabilities: Unsupported mime video/wvc1
,08-22 11:15:04.829  6992  6992 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-22 11:15:04.829  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:04.829  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:04.839  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:04.839  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:04.839  6992  6992 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
08-22 11:15:04.839  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:04.839  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:04.839  6992  6992 W VideoCapabilities: Unsupported mime video/wvc1
,08-22 11:15:04.839  6992  6992 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-22 11:15:04.849  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:04.849  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:04.849  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
08-22 11:15:04.849  6992  6992 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-22 11:15:04.849  6992  6992 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-22 11:15:04.849  6992  6992 W VideoCapabilities: Unsupported mime video/mp43
,08-22 11:15:04.849  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:04.849  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:04.849  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:04.849  6992  6992 W VideoCapabilities: Unsupported mime video/sorenson
,08-22 11:15:04.859  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:04.859  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:04.859  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:04.859  6992  6992 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-22 11:15:04.859  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:04.859  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:04.859  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:04.859  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:04.859  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:04.859  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:04.869  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:04.869  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:04.869  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:04.869  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:04.869  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:04.869  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:04.869  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:04.869  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:04.869  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:04.869  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:04.869  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:04.869  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:04.879  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:04.879  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:04.879  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:04.879  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:04.879  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:04.879  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 11:15:04.879  6992  6992 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-22 11:15:04.889  3060  3060 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 11:15:04.889  1016  1029 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-22 11:15:04.889  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 11:15:04.889  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:04.889  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:04.889  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 11:15:04.889  3060  3060 D DockEventReceiver: finishStartingService: stopping service
,08-22 11:15:04.899  3060  3060 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 11:15:04.899  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:04.899  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-22 11:15:04.899  1016  3765 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-22 11:15:04.909  1016  3765 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:04.909  1016  3765 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:04.909  1016  3765 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:04.909  1016  3765 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:04.919  7030  7030 E Zygote  : MountEmulatedStorage()
08-22 11:15:04.919  7030  7030 I libpersona: KNOX_SDCARD checking this for 1002
08-22 11:15:04.919  7030  7030 E Zygote  : v2
08-22 11:15:04.919  7030  7030 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:04.919  7030  7030 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:04.919  7030  7030 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:04.929  7030  7030 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 11:15:04.929  1016  3765 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7030 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-22 11:15:04.929  6992  6992 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-22 11:15:04.929  6992  6992 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 11:15:04.929  6992  6992 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 11:15:04.939  6992  6992 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 11:15:04.939  1016  1029 I ActivityManager: Killing 6578:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-22 11:15:04.939  6992  6992 I vclib   : onServiceConnected
,08-22 11:15:04.949  7030  7030 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:04.949  7030  7030 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:04.959  7030  7030 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-22 11:15:04.959  7030  7030 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-22 11:15:04.989  7030  7030 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-22 11:15:05.029  7030  7030 D BtSettings.ProfileConfig: Adding GattService
,08-22 11:15:05.029  7030  7030 D BtSettings.ProfileConfig: Adding HeadsetService
,08-22 11:15:05.029  7030  7030 D BtSettings.ProfileConfig: Adding A2dpService
,08-22 11:15:05.029  7030  7030 D BtSettings.ProfileConfig: Adding HidService
08-22 11:15:05.029  7030  7030 D BtSettings.ProfileConfig: Adding HealthService
,08-22 11:15:05.029  7030  7030 D BtSettings.ProfileConfig: Adding PanService
,08-22 11:15:05.029  7030  7030 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-22 11:15:05.029  7030  7030 D BtSettings.ProfileConfig: Adding SapService
,08-22 11:15:05.029  7030  7030 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-22 11:15:05.029  7030  7030 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-22 11:15:05.029  7030  7030 D BtSettings.ProfileConfig: Adding SapClientService
,08-22 11:15:05.029  7030  7030 D BtSettings.ProfileConfig: Adding HidDevService
08-22 11:15:05.029  7030  7030 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-22 11:15:05.039  1016  1536 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-22 11:15:05.039  1016  1536 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:05.039  1016  1536 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:05.039  1016  1536 D SettingsProvider: selectionArgs: false
08-22 11:15:05.039  1016  1536 D SettingsProvider: selectionArgs: 1002
,08-22 11:15:05.039  1016  1536 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:05.039  1016  1536 D SettingsProvider: ret = -1
,08-22 11:15:05.039  1016  1514 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-22 11:15:05.039  1016  1514 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:05.039  1016  1514 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:05.039  1016  1514 D SettingsProvider: selectionArgs: false
08-22 11:15:05.039  1016  1514 D SettingsProvider: selectionArgs: 1002
,08-22 11:15:05.039  1016  1514 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:05.039  1016  1514 D SettingsProvider: ret = -1
,08-22 11:15:05.039  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-22 11:15:05.039  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:05.039  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:05.039  1016  1028 D SettingsProvider: selectionArgs: false
08-22 11:15:05.039  1016  1028 D SettingsProvider: selectionArgs: 1002
08-22 11:15:05.039  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:05.039  1016  1028 D SettingsProvider: ret = -1
,08-22 11:15:05.039  1016  1262 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-22 11:15:05.039  1016  1262 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:05.039  1016  1262 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:05.039  1016  1262 D SettingsProvider: selectionArgs: false
08-22 11:15:05.039  1016  1262 D SettingsProvider: selectionArgs: 1002
08-22 11:15:05.039  1016  1262 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:05.039  1016  1262 D SettingsProvider: ret = -1
,08-22 11:15:05.039  1016  1537 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService,
08-22 11:15:05.039  1016  1537 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:05.039  1016  1537 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 11:15:05.039  1016  1537 D SettingsProvider: selectionArgs: false
08-22 11:15:05.039  1016  1537 D SettingsProvider: selectionArgs: 1002
08-22 11:15:05.039  1016  1537 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:05.039  1016  1537 D SettingsProvider: ret = -1
08-22 11:15:05.039  1016  1214 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-22 11:15:05.039  1016  1214 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-22 11:15:05.039  1016  1214 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:05.039  1016  1214 D SettingsProvider: selectionArgs: false
08-22 11:15:05.039  1016  1214 D SettingsProvider: selectionArgs: 1002
08-22 11:15:05.039  1016  1214 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-22 11:15:05.039  1016  1214 D SettingsProvider: ret = -1
08-22 11:15:05.039  1016  3767 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-22 11:15:05.039  1016  3767 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:05.039  1016  3767 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:05.039  1016  3767 D SettingsProvider: selectionArgs: false
,08-22 11:15:05.039  1016  3767 D SettingsProvider: selectionArgs: 1002
08-22 11:15:05.039  1016  3767 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:05.039  1016  3767 D SettingsProvider: ret = -1
08-22 11:15:05.039  1016  1428 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-22 11:15:05.039  1016  1428 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:05.039  1016  1428 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 11:15:05.039  1016  1428 D SettingsProvider: selectionArgs: false
08-22 11:15:05.039  1016  1428 D SettingsProvider: selectionArgs: 1002
08-22 11:15:05.039  1016  1428 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-22 11:15:05.039  1016  1428 D SettingsProvider: ret = -1
08-22 11:15:05.039  1016  1492 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:05.039  1016  1492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:05.039  1016  1492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:05.039  1016  1492 D SettingsProvider: selectionArgs: false
08-22 11:15:05.039  1016  1492 D SettingsProvider: selectionArgs: 1002
08-22 11:15:05.039  1016  1492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-22 11:15:05.039  1016  1492 D SettingsProvider: ret = -1
08-22 11:15:05.049  1016  3765 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:05.049  1016  3765 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:05.049  1016  3765 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:05.049  1016  3765 D SettingsProvider: selectionArgs: false
08-22 11:15:05.049  1016  3765 D SettingsProvider: selectionArgs: 1002
08-22 11:15:05.049  1016  3765 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:05.049  1016  3765 D SettingsProvider: ret = -1
08-22 11:15:05.049  1016  1504 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService,
08-22 11:15:05.049  1016  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:05.049  1016  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:05.049  1016  1504 D SettingsProvider: selectionArgs: false
08-22 11:15:05.049  1016  1504 D SettingsProvider: selectionArgs: 1002
08-22 11:15:05.049  1016  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-22 11:15:05.049  1016  1504 D SettingsProvider: ret = -1
08-22 11:15:05.049  1016  3764 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-22 11:15:05.049  1016  3764 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:05.049  1016  3764 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:05.049  1016  3764 D SettingsProvider: selectionArgs: false
08-22 11:15:05.049  1016  3764 D SettingsProvider: selectionArgs: 1002
08-22 11:15:05.049  1016  3764 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-22 11:15:05.049  1016  3764 D SettingsProvider: ret = -1
08-22 11:15:05.059  1016  1029 I ActivityManager: Killing 6595:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-22 11:15:05.059  1981  1981 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-22 11:15:05.059  1016  3764 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:15:05.059  1016  3764 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
08-22 11:15:05.059  1016  3764 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:05.059  1016  3764 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:05.059  1016  3764 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:05.069  1981  7046 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-22 11:15:05.069  1981  1981 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-22 11:15:05.079  1016  3764 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:05.079  1016  3764 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:05.079  1016  3764 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:05.079  1016  3764 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:05.079  1016  1504 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 11:15:05.079  1016  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:05.089  1016  1504 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:05.089  1016  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:05.089  1016  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:05.089  1016  1262 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:05.089  6545  6545 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-22 11:15:05.089  6545  6545 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 11:15:05.089  6545  6545 D SecurityLogAgent: StateMachine : Current State = 1
08-22 11:15:05.089  6545  6545 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 11:15:05.089  1620  1620 I Hs20UtilService: Starting #11
,08-22 11:15:05.089  1620  1640 I Hs20UtilService: Message received 5011
08-22 11:15:05.089  1016  1262 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:05.089  1016  1262 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:05.089  1016  1262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:05.109  1016  3765 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-22 11:15:05.109  1016  3765 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:05.109  1016  3765 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.109  1016  3765 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.109  1016  3765 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:05.109  1981  7046 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-22 11:15:05.119  7047  7047 E Zygote  : MountEmulatedStorage(),
08-22 11:15:05.119  7047  7047 E Zygote  : v2
08-22 11:15:05.119  7047  7047 I libpersona: KNOX_SDCARD checking this for 1000
08-22 11:15:05.119  7047  7047 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:05.119  7047  7047 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 11:15:05.129  7047  7047 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 11:15:05.129  7047  7047 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-22 11:15:05.129  1016  3765 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7047 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-22 11:15:05.149  7047  7047 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:05.149  7047  7047 D ActivityThread: Added TimaKeyStore provider,
,08-22 11:15:05.169  7047  7047 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-22 11:15:05.169  7047  7047 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-22 11:15:05.169  7047  7047 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-22 11:15:05.189  7047  7047 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-22 11:15:05.189  7047  7047 I PCWCLIENTTRACE_PushUtil: sales region : global
08-22 11:15:05.189  7047  7047 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-22 11:15:05.189  7047  7047 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:05.189  1016  1514 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-22 11:15:05.189  7047  7062 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
08-22 11:15:05.189  1016  1514 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-22 11:15:05.199  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-22 11:15:05.199  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:05.199  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.199  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.199  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:05.209  7064  7064 E Zygote  : MountEmulatedStorage(),
08-22 11:15:05.209  7064  7064 E Zygote  : v2
08-22 11:15:05.209  7064  7064 I libpersona: KNOX_SDCARD checking this for 10001
08-22 11:15:05.209  7064  7064 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:05.209  7064  7064 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:05.219  7064  7064 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:05.219  1016  1016 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7064 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 11:15:05.219  1016  1514 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
08-22 11:15:05.219  7064  7064 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 11:15:05.219  1016  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.219  1016  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.219  1016  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.219  1016  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:05.239   313   313 I art     : Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 23.550ms
,08-22 11:15:05.239  7064  7064 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:05.239  7064  7064 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:05.249   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.562ms,
,08-22 11:15:05.269   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 570us total 16.149ms
,08-22 11:15:05.279  7079  7079 E Zygote  : MountEmulatedStorage(),
,08-22 11:15:05.279  7079  7079 E Zygote  : v2,
08-22 11:15:05.279  7079  7079 I libpersona: KNOX_SDCARD checking this for 10031
08-22 11:15:05.279  7079  7079 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:05.289  1016  1514 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7079 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
08-22 11:15:05.289  1016  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
08-22 11:15:05.289  7079  7079 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:05.289  7079  7079 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:05.289  7079  7079 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:05.289  1819  1819 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-22 11:15:05.299  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-22 11:15:05.299  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.299  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.299  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.299  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:05.309  7094  7094 E Zygote  : MountEmulatedStorage()
,08-22 11:15:05.309  7094  7094 E Zygote  : v2
08-22 11:15:05.309  7094  7094 I libpersona: KNOX_SDCARD checking this for 10121
08-22 11:15:05.309  7094  7094 I libpersona: KNOX_SDCARD not a persona,
,08-22 11:15:05.309  7094  7094 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:05.309  7079  7079 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:05.309  7079  7079 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:05.319  1016  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7094 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-22 11:15:05.319  7094  7094 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:05.319  7094  7094 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-22 11:15:05.319  2600  2608 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
08-22 11:15:05.329  1819  1819 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-22 11:15:05.329  1819  1819 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-22 11:15:05.329  1819  1819 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-22 11:15:05.329  1819  1819 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-22 11:15:05.339  7094  7094 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:05.339  7094  7094 D ActivityThread: Added TimaKeyStore provider
08-22 11:15:05.339  1819  1819 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-22 11:15:05.339  1819  1819 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-22 11:15:05.349  1016  1514 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-22 11:15:05.349  1016  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.349  1016  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.349  1016  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.349  1016  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:05.359  7094  7094 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-22 11:15:05.359  7094  7094 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-22 11:15:05.359  7079  7079 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-22 11:15:05.359  7094  7094 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-22 11:15:05.369  7109  7109 E Zygote  : MountEmulatedStorage(),
08-22 11:15:05.369  7109  7109 I libpersona: KNOX_SDCARD checking this for 10077
08-22 11:15:05.369  7109  7109 E Zygote  : v2
08-22 11:15:05.369  7109  7109 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:05.369  7109  7109 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:05.369  1016  1514 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7109 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 11:15:05.369  1016  1514 I ActivityManager: Killing 6610:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
08-22 11:15:05.379  7109  7109 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:05.379  7109  7109 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-22 11:15:05.379  7094  7094 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
08-22 11:15:05.389  1016  3764 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
08-22 11:15:05.389  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.389  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.389  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.389  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:05.419  7125  7125 E Zygote  : MountEmulatedStorage()
08-22 11:15:05.419  7125  7125 I libpersona: KNOX_SDCARD checking this for 10032
08-22 11:15:05.419  7125  7125 E Zygote  : v2
08-22 11:15:05.419  7125  7125 I libpersona: KNOX_SDCARD not a persona
08-22 11:15:05.419  7125  7125 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:05.419  1016  3764 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7125 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 11:15:05.419  7125  7125 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:05.429  7125  7125 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-22 11:15:05.439  7109  7109 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:15:05.439  7109  7109 D ActivityThread: Added TimaKeyStore provider
08-22 11:15:05.439  2756  7118 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-22 11:15:05.439  7094  7094 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-22 11:15:05.439  2756  7118 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
08-22 11:15:05.439  2756  7118 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-22 11:15:05.439  2756  7118 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-22 11:15:05.449  7094  7094 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-22 11:15:05.449  1016  3768 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
08-22 11:15:05.449  2756  7118 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-22 11:15:05.449  1016  3768 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.449  1016  3768 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.449  1016  3768 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.449  1016  3768 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:05.469  7125  7125 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:05.469  7125  7125 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:05.479  7143  7143 E Zygote  : MountEmulatedStorage(),
,08-22 11:15:05.479  7143  7143 E Zygote  : v2
08-22 11:15:05.479  7143  7143 I libpersona: KNOX_SDCARD checking this for 10141
08-22 11:15:05.479  7143  7143 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:05.479  7143  7143 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:05.479  1016  3768 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7143 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-22 11:15:05.479  1016  3768 I ActivityManager: Killing 6626:com.qualcomm.timeservice/1000 (adj 15): empty #21
08-22 11:15:05.479  7143  7143 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:05.479  7143  7143 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:05.499  1016  3764 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-22 11:15:05.499  7143  7143 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:05.499  7143  7143 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:05.499  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.499  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.499  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.499  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:05.519  7158  7158 E Zygote  : MountEmulatedStorage()
08-22 11:15:05.519  7158  7158 I libpersona: KNOX_SDCARD checking this for 1000
08-22 11:15:05.519  7158  7158 E Zygote  : v2
08-22 11:15:05.519  7158  7158 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:05.519  1016  3764 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7158 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 11:15:05.519  7158  7158 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:05.519  1016  3764 I ActivityManager: Killing 6561:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-22 11:15:05.519  7158  7158 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:05.519  7158  7158 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:05.539  7158  7158 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:05.539  7158  7158 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:05.559  7143  7143 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-22 11:15:05.559  7143  7143 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 11:15:05.559  7143  7143 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 11:15:05.559  7143  7143 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-22 11:15:05.589  7125  7173 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-22 11:15:05.599  7125  7173 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-22 11:15:05.599  7125  7173 D SPPClientService: PushLog.txt file is not deleted.
,08-22 11:15:05.599  7125  7173 D SPPClientService: PushLog.txt file is not deleted.
,08-22 11:15:05.599  7125  7173 D SPPClientService: ============PushLog. stop!
,08-22 11:15:05.609  7158  7158 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-22 11:15:05.619  7125  7125 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-22 11:15:05.619  1016  1029 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 11:15:05.619  1016  1487 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-22 11:15:05.629  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:05.629  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.629  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:05.629  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:05.639  7175  7175 E Zygote  : MountEmulatedStorage()
,08-22 11:15:05.639  7175  7175 E Zygote  : v2
08-22 11:15:05.639  7175  7175 I libpersona: KNOX_SDCARD checking this for 10036
08-22 11:15:05.639  7175  7175 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:05.639  7175  7175 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:05.649  1016  1487 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7175 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 11:15:05.649  1016  1487 I ActivityManager: Killing 6073:com.android.mms/u0a41 (adj 15): empty #21,
,08-22 11:15:05.649  1016  3767 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-22 11:15:05.649  1016  3767 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0,
08-22 11:15:05.649  1016  3767 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:05.649  1016  3767 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-22 11:15:05.649  1016  3767 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-22 11:15:05.649  7175  7175 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 11:15:05.649  7175  7175 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-22 11:15:05.659  1016  1537 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 11:15:05.669  7175  7175 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:15:05.669  7175  7175 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:05.709  1016  1537 D CountryDetector: No listener is left
,08-22 11:15:05.719  7175  7175 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@194cb606
,08-22 11:15:05.729  7175  7175 I SA      : [SSP] onCreated
,08-22 11:15:05.739  7125  7183 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-22 11:15:05.749  7175  7175 I SA      : [TPM] There is no property file
,08-22 11:15:05.749  7175  7175 I SA      : [SCU] isHaveSA() - false
,08-22 11:15:05.749  7175  7175 I SA      : [TPM] getModelProperty : null
08-22 11:15:05.749  7175  7175 I SA      : [TPM] getCSCProperty : null
,08-22 11:15:05.759  7175  7175 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-22 11:15:05.759  7175  7175 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-22 11:15:05.759  7175  7175 I SA      : [DM] TFT FEATURE: false
,08-22 11:15:05.759  7175  7175 I SA      : [DM] init START
,08-22 11:15:05.769  7175  7175 I SA      : [DM] This device is not a Vodafone
,08-22 11:15:05.779  7175  7175 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-22 11:15:05.779  7175  7175 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-22 11:15:05.779  7175  7175 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-22 11:15:05.779  7175  7175 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-22 11:15:05.779  7158  7158 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-22 11:15:05.779  7175  7175 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-22 11:15:05.779  7175  7175 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-22 11:15:05.779  7175  7175 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-22 11:15:05.779  7175  7175 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-22 11:15:05.789  7175  7175 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-22 11:15:05.789  7175  7175 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-22 11:15:05.789  7175  7175 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-22 11:15:05.789  7158  7158 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-22 11:15:05.789  7175  7175 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-22 11:15:05.789  7158  7158 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:05.789  7175  7175 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-22 11:15:05.789  7175  7175 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-22 11:15:05.789  7158  7158 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-22 11:15:05.789  7158  7158 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-22 11:15:05.789  7158  7158 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
08-22 11:15:05.789  7175  7175 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-22 11:15:05.789  1016  1537 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-22 11:15:05.799  1016  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.799  1016  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.799  1016  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.799  1016  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:05.799  7175  7175 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-22 11:15:05.799  7175  7175 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-22 11:15:05.799  7175  7175 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-22 11:15:05.799  7175  7175 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-22 11:15:05.799  7175  7175 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-22 11:15:05.799  7175  7175 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-22 11:15:05.799  7175  7175 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-22 11:15:05.809  7175  7175 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-22 11:15:05.809  7202  7202 I libpersona: KNOX_SDCARD checking this for 10008
08-22 11:15:05.809  7175  7175 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-22 11:15:05.809  7202  7202 I libpersona: KNOX_SDCARD not a persona
08-22 11:15:05.809  7175  7175 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-22 11:15:05.809  7175  7175 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-22 11:15:05.809  7175  7175 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-22 11:15:05.809  7175  7175 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
08-22 11:15:05.809  7202  7202 E Zygote  : MountEmulatedStorage()
08-22 11:15:05.809  7202  7202 E Zygote  : v2
08-22 11:15:05.809  1016  3764 D RCPManagerService: exchangeData() failure , invalid userId
08-22 11:15:05.809  7202  7202 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:05.819  7202  7202 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:05.819  7175  7175 I SA      : [SCU] isHaveSA() - false
08-22 11:15:05.819  7175  7175 I SA      : support phone number id : false
08-22 11:15:05.819  7175  7175 I SA      : [DM] Supports Ref Jpn : true
08-22 11:15:05.819  7175  7175 I SA      : [DM] init END
08-22 11:15:05.819  7175  7175 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
08-22 11:15:05.819  7202  7202 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-22 11:15:05.819  1016  1537 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7202 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 11:15:05.819  1016  1537 I ActivityManager: Killing 6653:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-22 11:15:05.829  7175  7175 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,08-22 11:15:05.829  7175  7175 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-22 11:15:05.839  1016  3765 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 11:15:05.839  7175  7175 I SA      : [SLFUCHKMGR] constructor called,
,08-22 11:15:05.839  7202  7202 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:05.849  7202  7202 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:05.859  1016  3765 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-22 11:15:05.859  1016  3765 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-22 11:15:05.869  1016  3765 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:05.869  1016  3765 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:05.869  1016  3765 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-22 11:15:05.869  1016  1492 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-22 11:15:05.869  7175  7175 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-22 11:15:05.869  7175  7175 I SA      : [OR] == isSIMCardReady false ==
,08-22 11:15:05.869  1016  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:05.869  1016  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.869  1016  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:05.869  7175  7175 I SA      : [SCU] == networkStateCheck == false
08-22 11:15:05.869  1016  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.869  7175  7175 I SA      : [OR] onReceive END
,08-22 11:15:05.889  7220  7220 E Zygote  : MountEmulatedStorage()
08-22 11:15:05.889  7220  7220 E Zygote  : v2
08-22 11:15:05.889  7220  7220 I libpersona: KNOX_SDCARD checking this for 10110
08-22 11:15:05.889  7220  7220 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:05.889  7220  7220 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:05.889  7220  7220 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:05.889  1016  1492 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7220 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 11:15:05.889  7220  7220 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 11:15:05.889  1016  1504 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-22 11:15:05.889  1016  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-22 11:15:05.889  1016  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:05.899  1016  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:05.899  1016  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-22 11:15:05.899  1016  1492 I ActivityManager: Killing 6670:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-22 11:15:05.909  6992  7219 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-22 11:15:05.909  7220  7220 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:05.909  7220  7220 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:05.919  1016  1514 I ActivityManager: Killing 6507:com.android.calendar/u0a131 (adj 15): empty #21
,08-22 11:15:05.939  1016  1262 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 11:15:05.939  1226  1226 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:05.949  1016  3764 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-22 11:15:05.949  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.949  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.949  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:05.949  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:05.949  1016  1514 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 11:15:05.959  7238  7238 E Zygote  : MountEmulatedStorage()
08-22 11:15:05.959  7238  7238 E Zygote  : v2
08-22 11:15:05.959  7238  7238 I libpersona: KNOX_SDCARD checking this for 10068
08-22 11:15:05.959  7238  7238 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:05.969  7238  7238 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:05.969  1016  3764 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7238 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-22 11:15:05.969  7238  7238 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:05.969  7238  7238 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-22 11:15:05.979  1016  3768 I ActivityManager: Killing 6686:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-22 11:15:05.999  7238  7238 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:05.999  7238  7238 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:05.999  1016  1040 W libprocessgroup: failed to kill pid 6507: No such process
,08-22 11:15:06.009  2852  2852 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 22 11:15:05 GMT+02:00 2016
,08-22 11:15:06.009  1016  1514 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-22 11:15:06.009  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-22 11:15:06.009  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:06.009  1016  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:06.009  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-22 11:15:06.019  2852  2852 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-22 11:15:06.029  2852  2852 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-22 11:15:06.029  2852  2852 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-22 11:15:06.029  2852  2852 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-22 11:15:06.029  2852  7253 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-22 11:15:06.039  2852  7253 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-22 11:15:06.039  7238  7238 D BadgeProvider: onCreate
,08-22 11:15:06.039  7238  7238 D BadgeProvider: DatabaseHelper
,08-22 11:15:06.049  2852  7253 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-22 11:15:06.049  2852  7253 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-22 11:15:06.049  2852  2852 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-22 11:15:06.059  1016  1428 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 11:15:06.059  7238  7247 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-22 11:15:06.079  1016  3768 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 11:15:06.079  1016  1428 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-22 11:15:06.079  1498  1498 D Launcher.Model: reloadBadges entered.
,08-22 11:15:06.079  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:06.079  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:06.079  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:06.079  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:06.079  7238  7247 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,08-22 11:15:06.079  7238  7247 D BadgeProvider: sendNotify, [notify] : null
,08-22 11:15:06.079  7238  7247 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,08-22 11:15:06.079  7238  7247 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-22 11:15:06.079  7238  7247 D BadgeProvider: update, [UpdateCount] : 1
,08-22 11:15:06.089  7254  7254 E Zygote  : MountEmulatedStorage()
,08-22 11:15:06.089  7254  7254 E Zygote  : v2
08-22 11:15:06.089  7254  7254 I libpersona: KNOX_SDCARD checking this for 10009
08-22 11:15:06.089  7254  7254 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:06.089  7254  7254 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 11:15:06.099  1016  1428 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7254 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-22 11:15:06.099  1016  1428 I ActivityManager: Killing 6721:com.google.android.apps.docs/u0a87 (adj 15): empty #21,
08-22 11:15:06.099  1016  1428 I ActivityManager: Killing 6036:com.android.defcontainer/u0a3 (adj 15): empty #22
,08-22 11:15:06.099  7254  7254 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 11:15:06.099  7254  7254 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,08-22 11:15:06.139   313   313 I art     : Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.682ms total 43.318ms
,08-22 11:15:06.139  7254  7254 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:06.139  7254  7254 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:06.159   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 16.640ms
,08-22 11:15:06.179   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 16.595ms
,08-22 11:15:06.179  1016  1028 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output,
,08-22 11:15:06.229  1016  3768 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 11:15:06.229  1016  3768 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-22 11:15:06.229  1016  3768 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:06.229  1016  3768 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:06.229  1016  3768 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:06.229  1016  1514 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-22 11:15:06.229  1016  1514 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-22 11:15:06.259  1016  1514 D SecContentProvider2: mCursor = null
,08-22 11:15:06.259  1016  1514 D WifiService: setWifiEnabled: true pid=6774, uid=10171,
,08-22 11:15:06.259  1016  1514 W ActivityManager: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-22 11:15:06.259  1016  1514 W WifiService: Failed getting userId using ActivityManagerNative
08-22 11:15:06.259  1016  1514 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-22 11:15:06.259  1016  1514 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 11:15:06.259  1016  1514 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-22 11:15:06.259  1016  1514 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-22 11:15:06.259  1016  1514 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-22 11:15:06.259  1016  1514 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-22 11:15:06.259  1016  1514 D SettingsProvider: name = wifi_on
,08-22 11:15:06.269   283   672 I WVCdm   : CdmEngine::CloseSession
,08-22 11:15:06.269  1016  1126 E WifiHW  : ##################### set firmware type 0 #####################
,08-22 11:15:06.279  4824  7271 I iu.SyncManager: SYNC; picasa accounts
,08-22 11:15:06.279  1016  1504 I art     : Explicit concurrent mark sweep GC freed 52783(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 23MB/35MB, paused 2.747ms total 177.663ms
,08-22 11:15:06.279  4824  4824 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-22 11:15:06.309  1016  1514 I ActivityManager: Killing 5832:com.android.vending/u0a26 (adj 15): empty #21
,08-22 11:15:06.319  1016  1214 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-22 11:15:06.319  1016  1214 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-22 11:15:06.319  1016  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-22 11:15:06.319  1016  1536 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-22 11:15:06.329   283   699 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-22 11:15:06.329   283   283 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-22 11:15:06.329   283   283 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-22 11:15:06.329   283   283 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-22 11:15:06.339   283   283 D WVCdm   : PrepareKeyRequest: nonce=3137529431
,08-22 11:15:06.409  7220  7220 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-22 11:15:06.409  7220  7220 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-22 11:15:06.409  7220  7220 I GAv4    :   adb logcat -s GAv4
,08-22 11:15:06.419   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-22 11:15:06.419   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 11:15:06.419  7220  7278 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-22 11:15:06.429   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-22 11:15:06.429   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 11:15:06.429  7220  7278 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-22 11:15:06.429  7220  7220 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-22 11:15:06.429  1016  1492 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-22 11:15:06.439   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-22 11:15:06.439   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 11:15:06.439  7220  7280 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-22 11:15:06.439   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-22 11:15:06.439   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 11:15:06.439  7220  7280 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-22 11:15:06.439  7220  7220 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-22 11:15:06.449  7220  7281 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-22 11:15:06.639   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 11:15:06.659  1016  1043 D Tethering: interfaceAdded wlan0
,08-22 11:15:06.669  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 11:15:06.669  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:06.669  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:06.669  1016  1130 E Tethering: No numeric data
,08-22 11:15:06.679  1016  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-22 11:15:06.679  1016  1130 D Tethering: clearTetheredNotification()
08-22 11:15:06.679  1016  1130 D Tethering: InitialState.processMessage what=4
,08-22 11:15:06.679  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:06.679  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:06.679  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:06.679  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:06.679  1016  1043 D Tethering: interfaceAdded p2p0
,08-22 11:15:06.679  1016  1130 E Tethering: No numeric data
,08-22 11:15:06.679  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 11:15:06.679  1174  1174 D HotspotTile: updateTetherState():false, false
,08-22 11:15:06.679  1016  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-22 11:15:06.689  1016  1123 V NetworkStats: performPollLocked() took 6ms
,08-22 11:15:06.689  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:06.689  1016  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 11:15:06.689  1016  1130 D Tethering: clearTetheredNotification()
,08-22 11:15:06.689  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-22 11:15:06.689  1174  1174 D HotspotTile: updateTetherState():false, false
,08-22 11:15:06.689  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:06.689  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-22 11:15:06.689  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:06.689  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:06.689  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:06.689  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:06.689  1016  1123 V NetworkStats: performPollLocked() took 3ms
08-22 11:15:06.689  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:06.699  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 11:15:06.699  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 11:15:06.699  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 11:15:06.699   278  1015 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-22 11:15:06.699   278  1015 D SoftapController: Softap fwReload - Ok
,08-22 11:15:06.709   278  1015 D CommandListener: Setting iface cfg
,08-22 11:15:06.709   278  1015 D CommandListener: Trying to bring down wlan0
08-22 11:15:06.709   278  1015 D CommandListener: Clearing all IP addresses on wlan0
,08-22 11:15:06.709  7220  7220 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-22 11:15:06.709  1016  1126 E WifiHW  : supplicant_name : p2p_supplicant
,08-22 11:15:06.709  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:06.709  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:06.719  1016  3765 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:06.719  1016  3765 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:06.719  1016  3765 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:06.719  1016  3765 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-22 11:15:06.749  7220  7220 I cr.library_loader: Time to load native libraries: 7 ms (timestamps 4269-4276)
,08-22 11:15:06.749  7220  7220 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-22 11:15:06.759  7303  7303 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-22 11:15:06.759  7303  7303 I wpa_supplicant: Successfully initialized wpa_supplicant
08-22 11:15:06.759  7303  7303 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-22 11:15:06.779  7220  7220 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7c9d0d9}
,08-22 11:15:06.779  7220  7220 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-22 11:15:06.779  7220  7220 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-22 11:15:06.799  7303  7303 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-22 11:15:06.799   382   382 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7303
,08-22 11:15:06.799   382   382 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-22 11:15:06.799  7303  7303 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-22 11:15:06.799  7303  7303 I wpa_supplicant: ssSupport state is = 1
08-22 11:15:06.799  7303  7303 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-22 11:15:06.799  7303  7303 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-22 11:15:06.799   382   382 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7303
08-22 11:15:06.799   382   382 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
08-22 11:15:06.799  7220  7220 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,08-22 11:15:06.799  7220  7220 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 11:15:06.809  7220  7220 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-22 11:15:06.809  1016  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-22 11:15:06.819  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 11:15:06.819  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 11:15:06.819  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:06.819  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:06.819  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:06.819  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:06.829  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:06.829  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-22 11:15:06.829  1174  1671 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 11:15:06.829  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:06.829  1174  1174 D HotspotTile: onReceive : 2, 0
,08-22 11:15:06.829  3060  3060 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:06.829  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:06.829  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:06.829  7220  7220 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-22 11:15:06.829  7220  7220 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-22 11:15:06.829  7220  7220 I Adreno-EGL: Build Date: 04/06/15 Mon
08-22 11:15:06.829  7220  7220 I Adreno-EGL: Local Branch: 
08-22 11:15:06.829  7220  7220 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-22 11:15:06.829  7220  7220 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-22 11:15:06.829  7220  7220 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-22 11:15:06.909  7220  7220 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-22 11:15:06.909  7220  7318 W cr.media: Requires BLUETOOTH permission
,08-22 11:15:06.919  7220  7220 I NSApplication: Starting up...
,08-22 11:15:06.919  1016  1487 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-22 11:15:06.919  1016  1028 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-22 11:15:06.929  1016  3765 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-22 11:15:06.929  1016  3765 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:06.929  1016  3765 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:06.929  1016  3765 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:06.929  1016  3765 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:06.949  1016  3765 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7323 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-22 11:15:06.949  1016  3765 I ActivityManager: Killing 6958:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-22 11:15:06.949  7323  7323 E Zygote  : MountEmulatedStorage(),
08-22 11:15:06.949  7323  7323 E Zygote  : v2
08-22 11:15:06.949  7323  7323 I libpersona: KNOX_SDCARD checking this for 10117
08-22 11:15:06.949  7323  7323 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:06.949  7323  7323 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:06.959  7323  7323 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:06.959  7323  7323 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 11:15:06.979  7323  7323 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:06.979  7323  7323 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:06.989  7323  7323 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-22 11:15:06.999   382   382 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-22 11:15:06.999  7303  7303 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,08-22 11:15:07.049  7303  7303 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-22 11:15:07.049  7303  7303 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-22 11:15:07.059  7303  7303 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
08-22 11:15:07.059   382   382 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7303
08-22 11:15:07.059   382   382 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-22 11:15:07.059  7303  7303 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-22 11:15:07.059  7303  7303 I wpa_supplicant: ssSupport state is = 1
,08-22 11:15:07.059  7303  7303 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-22 11:15:07.059  7303  7303 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 11:15:07.059  7303  7303 E wpa_supplicant: SIM READ ERROR
08-22 11:15:07.059  7303  7303 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:07.059  7303  7303 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-22 11:15:07.059  7303  7303 E wpa_supplicant: SIM READ ERROR
08-22 11:15:07.059  7303  7303 I wpa_supplicant: Blacklist: Clear (all) 
08-22 11:15:07.059  7303  7303 I wpa_supplicant: wpa_default_ap_write_once
08-22 11:15:07.059  7303  7303 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-22 11:15:07.059  7303  7303 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-22 11:15:07.059  7303  7303 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-22 11:15:07.059  7303  7303 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:07.059  7303  7303 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-22 11:15:07.059  7303  7303 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-22 11:15:07.069  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 11:15:07.069  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-22 11:15:07.069  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:07.129  7303  7303 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-22 11:15:07.309  7303  7303 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-22 11:15:07.309  7303  7303 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-22 11:15:07.319  7303  7303 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-22 11:15:07.319   382   382 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7303
08-22 11:15:07.319   382   382 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-22 11:15:07.319  7303  7303 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-22 11:15:07.319  7303  7303 I wpa_supplicant: ssSupport state is = 1
,08-22 11:15:07.319  7303  7303 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-22 11:15:07.319  7303  7303 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-22 11:15:07.329  7303  7303 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-22 11:15:07.329   382   382 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7303
08-22 11:15:07.329   382   382 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-22 11:15:07.329  7303  7303 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-22 11:15:07.329  7303  7303 I wpa_supplicant: ssSupport state is = 1
08-22 11:15:07.329  7303  7303 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:07.329  7303  7303 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 11:15:07.329  7303  7303 E wpa_supplicant: SIM READ ERROR
08-22 11:15:07.329  7303  7303 I wpa_supplicant: wpa_default_ap_write_once
08-22 11:15:07.329  7303  7303 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-22 11:15:07.329  7303  7303 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-22 11:15:07.339  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-22 11:15:07.339  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 11:15:07.339  1016  1043 D Tethering: interfaceStatusChanged p2p0, false,
,08-22 11:15:07.339  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-22 11:15:07.339  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 11:15:07.339  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 11:15:07.339  1016  1029 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-22 11:15:07.339  1016  1029 I ActivityManager: Killing 6976:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-22 11:15:07.349  1016  1214 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:07.349  1016  1214 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:07.349  1016  1214 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:07.349  1016  1214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:07.349  1016  1214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:07.349  1620  1620 I Hs20UtilService: Starting #12
,08-22 11:15:07.349  1620  1640 I Hs20UtilService: Message received 5011
,08-22 11:15:07.359  6545  6545 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-22 11:15:07.359  6545  6545 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 11:15:07.359  6545  6545 D SecurityLogAgent: StateMachine : Current State = 1
08-22 11:15:07.359  6545  6545 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 11:15:07.389  7303  7303 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-22 11:15:07.389  7303  7303 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-22 11:15:07.499  7303  7303 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-22 11:15:07.499  7303  7303 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-22 11:15:07.499  7303  7303 I wpa_supplicant: Skip scan - bUseNetwork false
,08-22 11:15:07.499  1016  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-22 11:15:07.509  1016  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-22 11:15:07.509  7303  7303 I wpa_supplicant: HOTSPOT20_ENABLE called
08-22 11:15:07.509  7303  7303 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:07.509  7303  7303 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 11:15:07.509  7303  7303 E wpa_supplicant: SIM READ ERROR
,08-22 11:15:07.509  7303  7303 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 11:15:07.529  7303  7303 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-22 11:15:07.539  7303  7303 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-22 11:15:07.539  1016  1126 D WifiConfigStore: Loading config and enabling all networks 
,08-22 11:15:07.539  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 11:15:07.539  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:07.539  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:07.539  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:07.539  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:07.539  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:07.539  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:07.539  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-22 11:15:07.539  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-22 11:15:07.539  1174  1671 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-22 11:15:07.539  1174  1174 D HotspotTile: onReceive : 3, 0
,08-22 11:15:07.549  3060  3060 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:07.549  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:07.549  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:07.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:07.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:07.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:07.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:07.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:07.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:07.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 11:15:07.549  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:07.549  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:07.549  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:07.549  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:07.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:07.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:07.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:07.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:07.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:07.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:07.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 11:15:07.549  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:07.549  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:07.549  1016  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 11:15:07.549  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-22 11:15:07.549  1016  1126 E WifiConfigStore: Not a HS20
08-22 11:15:07.549  1016  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-22 11:15:07.549  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:07.549  1016  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:07.549  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:07.559  1620  1620 I Hs20UtilService: Starting #13
08-22 11:15:07.559  1620  1640 I Hs20UtilService: Message received 5011
,08-22 11:15:07.559  1016  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-22 11:15:07.559  6545  6545 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-22 11:15:07.559  6545  6545 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-22 11:15:07.559  6545  6545 D SecurityLogAgent: StateMachine : Current State = 1
08-22 11:15:07.559  6545  6545 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 11:15:07.559  1016  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-22 11:15:07.559  7303  7303 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-22 11:15:07.559  7303  7303 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-22 11:15:07.559  7303  7303 I wpa_supplicant: reset timer : RESET_TIMER 0
08-22 11:15:07.559  7303  7303 I wpa_supplicant: P2P: Current p2p state = IDLE
08-22 11:15:07.559  7303  7303 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-22 11:15:07.559  7303  7303 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-22 11:15:07.559  7303  7303 I wpa_supplicant: First Scan Start
,08-22 11:15:07.559  7303  7303 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-22 11:15:07.569  1016  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-22 11:15:07.569  1016  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-22 11:15:07.569  1016  1126 I WifiNative-HAL: startHal
08-22 11:15:07.569  1016  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9d36888c
08-22 11:15:07.569  1016  1126 I WifiNative-HAL: Could not start hal
,08-22 11:15:07.569  6992  6992 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 11:15:07.569  1016  1126 E WifiNative-wlan0: do suspend true
,08-22 11:15:07.579  1016  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-22 11:15:07.579  1016  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-22 11:15:07.579   278  1015 D CommandListener: Setting iface cfg
08-22 11:15:07.579   278  1015 D CommandListener: Trying to bring up p2p0
08-22 11:15:07.579  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
08-22 11:15:07.579  1016  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:07.579  1016  1149 I WifiNative-HAL: startHal
08-22 11:15:07.579  1016  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9e4109bc
08-22 11:15:07.579  1016  1149 I WifiNative-HAL: Could not start hal
08-22 11:15:07.579  1016  1149 E WifiScanningService: could not start HAL
,08-22 11:15:07.579  1016  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-22 11:15:07.579  1016  1016 D RttService: SCAN_AVAILABLE : 3
08-22 11:15:07.579  1016  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-22 11:15:07.579  1016  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-22 11:15:07.579  1016  1126 E WifiNative-wlan0: invaild command id : 215
,08-22 11:15:07.579  1016  1150 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 11:15:07.579  1016  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-22 11:15:07.579  1016  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-22 11:15:07.579  1016  1126 E WifiNative-wlan0: invaild command id : 215
,08-22 11:15:07.579  1016  1125 D WifiP2pService: P2pEnablingState
,08-22 11:15:07.579  1016  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-22 11:15:07.579  1016  1125 D WifiP2pService: P2p socket connection successful
,08-22 11:15:07.579  1016  1125 D WifiP2pService: P2pEnabledState
,08-22 11:15:07.589  7303  7303 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-22 11:15:07.589  7303  7303 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-22 11:15:07.589  1016  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-22 11:15:07.589  7303  7303 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-22 11:15:07.589  1016  1126 E WifiStateMachine: Failed to set frequency band 0
,08-22 11:15:07.589  1016  1128 E ConnectivityService: updateNetworkInfo()
08-22 11:15:07.589  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:07.589  1016  1126 D SecContentProvider2: mCursor = null
,08-22 11:15:07.589  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-22 11:15:07.589  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-22 11:15:07.589  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 11:15:07.589  1016  1046 D WifiDisplayController: disconnect
,08-22 11:15:07.589  1016  1046 D WifiDisplayController: updateConnection
08-22 11:15:07.589  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 11:15:07.589  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 11:15:07.589  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-22 11:15:07.589  1016  1126 D SecContentProvider2: mCursor = null
,08-22 11:15:07.599  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 11:15:07.599  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-22 11:15:07.599  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-22 11:15:07.599  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-22 11:15:07.599  1016  1125 D WifiNative-p2p0: p2pGetDeviceAddress
08-22 11:15:07.599  1016  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-22 11:15:07.599  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
,08-22 11:15:07.599  1016  1537 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-22 11:15:07.599  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-22 11:15:07.599  3060  3060 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-22 11:15:07.599  1016  1125 D WifiP2pService: DeviceAddress: 0a:76:28
,08-22 11:15:07.599  3060  3060 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 11:15:07.599  1016  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-22 11:15:07.599  1016  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-22 11:15:07.599  1016  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-22 11:15:07.599  1016  1046 D WifiDisplayController:  secondary type: null
08-22 11:15:07.599  1016  1046 D WifiDisplayController:  wps: 0
08-22 11:15:07.599  1016  1046 D WifiDisplayController:  grpcapab: 0
08-22 11:15:07.599  1016  1046 D WifiDisplayController:  devcapab: 0
08-22 11:15:07.599  1016  1046 D WifiDisplayController:  status: 3
08-22 11:15:07.599  1016  1046 D WifiDisplayController:  wfdInfo: null
08-22 11:15:07.599  1016  1046 D WifiDisplayController:  groupownerAddress: null
08-22 11:15:07.599  1016  1046 D WifiDisplayController:  GOdeviceName: null
08-22 11:15:07.599  1016  1046 D WifiDisplayController:  interfaceAddress: 
08-22 11:15:07.599  1016  1046 D WifiDisplayController:  SConnectInfo : null
08-22 11:15:07.609  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 11:15:07.609  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-22 11:15:07.609  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 11:15:07.609  3060  3060 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 11:15:07.609  3060  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 11:15:07.609  1016  3764 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-22 11:15:07.609  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:07.609  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:07.609  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:07.609  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:07.619  7353  7353 E Zygote  : MountEmulatedStorage()
,08-22 11:15:07.619  7353  7353 E Zygote  : v2
08-22 11:15:07.619  7353  7353 I libpersona: KNOX_SDCARD checking this for 10064
08-22 11:15:07.619  7353  7353 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:07.629   288   288 E SMD     : DCD OFF
,08-22 11:15:07.629  1016  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
08-22 11:15:07.629  7353  7353 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:07.629  1016  3764 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7353 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 11:15:07.629  7353  7353 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:07.629  1016  1125 D WifiP2pService: InactiveState
08-22 11:15:07.629  1016  1125 D WifiP2pService: InactiveState{ what=143376 }
08-22 11:15:07.629  1016  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
08-22 11:15:07.629  7353  7353 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:07.629  7303  7303 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-22 11:15:07.629  1016  1125 D WifiP2pService: InactiveState{ what=143376 },
08-22 11:15:07.629  1016  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-22 11:15:07.639   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 11:15:07.649  7353  7353 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:07.649  7353  7353 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:07.659  1016  1096 V AlarmManager: waitForAlarm result :4
,08-22 11:15:07.659  7353  7353 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-22 11:15:07.669  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-22 11:15:07.669  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 11:15:07.669  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 11:15:07.669  7353  7353 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 11:15:07.679  7353  7353 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-22 11:15:07.699  7353  7353 D FileShare-Client: Outbound.stopDelayTimer - 
,08-22 11:15:07.699  1016  1428 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-22 11:15:07.699  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:07.699  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:07.699  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:07.699  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:07.719  7368  7368 E Zygote  : MountEmulatedStorage()
,08-22 11:15:07.719  7368  7368 E Zygote  : v2
08-22 11:15:07.719  7368  7368 I libpersona: KNOX_SDCARD checking this for 10065
08-22 11:15:07.719  7368  7368 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:07.719  7368  7368 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:07.719  1016  1428 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7368 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-22 11:15:07.719  1016  1428 I ActivityManager: Killing 6860:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-22 11:15:07.719  7368  7368 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:07.719  7368  7368 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:07.739  7368  7368 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:07.739  7368  7368 D ActivityThread: Added TimaKeyStore provider,
,08-22 11:15:07.759  7368  7368 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 11:15:07.769  1016  3767 I ActivityManager: Killing 7030:com.android.bluetooth/1002 (adj 15): empty #21
,08-22 11:15:07.919   283   672 I WVCdm   : CdmEngine::CloseSession
,08-22 11:15:07.929   283   672 I WVCdm   : L3 Terminate.
,08-22 11:15:07.969  4318  4330 I art     : Explicit concurrent mark sweep GC freed 1539(53KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 690us total 21.080ms
,08-22 11:15:07.989  1016  1029 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-22 11:15:07.989  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-22 11:15:07.989  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:07.989  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:07.989  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:08.019  1981  6898 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-22 11:15:08.029  1981  6898 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 11:15:08.029  1981  6898 I System.out: (HTTPLog)-Static: isShipBuild true
,08-22 11:15:08.029  1981  6898 I System.out: (HTTPLog)-Thread-267-392122470: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-22 11:15:08.029  1981  6898 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 11:15:08.029   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-22 11:15:08.029   278  1011 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-22 11:15:08.029  1981  6898 W GLSUser : [AppCertManager] IOException while requesting key: 
,08-22 11:15:08.119  1016  1492 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 11:15:08.119  1016  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-22 11:15:08.119  1016  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:08.119  1016  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:08.119  1016  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:08.169  1016  3765 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:08.169  1016  3765 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:08.169  1016  3765 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:08.169  1016  3765 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:08.409  1016  3764 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-22 11:15:08.429  1016  3768 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:08.429  1016  3768 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:08.429  1016  3768 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:08.429  1016  3768 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:08.439  1016  3765 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:08.439  1016  3765 W ActivityManager: userId = 0, bbcId = -10000,
08-22 11:15:08.439  1016  3765 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:08.439  1016  3765 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:08.469  1981  1981 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=a0c896ad-64cd-4fff-a5a6-aa779c7df0ae
,08-22 11:15:08.469  1016  1514 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-22 11:15:08.469  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-22 11:15:08.469  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:08.469  1016  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:08.479  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:08.479  1981  1981 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-22 11:15:08.479  1981  1981 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-22 11:15:08.499  1016  1262 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:08.499  1016  1262 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:08.499  1016  1262 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:08.499  1016  1262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:08.629  1981  2182 W GCoreFlp: No location to return for getLastLocation()
,08-22 11:15:08.639   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 11:15:08.659  1016  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:08.659  1016  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:08.659  1016  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:08.659  1016  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:08.659  1016  3768 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:08.659  1016  3768 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:08.659  1016  3768 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:08.659  1016  3768 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:08.669  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:08.669  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:08.669  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:08.669  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:08.699  1981  2205 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-22 11:15:08.709  4824  7388 D UdcContextInitService: registered all accounts: true
,08-22 11:15:08.709  1981  2220 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-22 11:15:08.739  1016  1428 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-22 11:15:08.739  1016  1428 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-22 11:15:08.739  1016  1428 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-22 11:15:08.739  1016  1428 D BatteryService: stay LED for fully charged
08-22 11:15:08.739  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 11:15:08.739  1016  1016 I MotionRecognitionService: Plugged
,08-22 11:15:08.739  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 11:15:08.749  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-22 11:15:08.749  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 11:15:08.749  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-22 11:15:08.749  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-22 11:15:08.779  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 11:15:08.779  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 11:15:08.779  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-22 11:15:08.779  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-22 11:15:08.779  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-22 11:15:08.789  7303  7303 I wpa_supplicant: nl80211: Received scan results (21 BSSes)
08-22 11:15:08.789  7303  7303 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-22 11:15:08.789  7303  7303 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-22 11:15:08.789  7303  7303 I wpa_supplicant: Trying to associate with  'G700'
08-22 11:15:08.789  1016  7349 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
08-22 11:15:08.789  7303  7303 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-22 11:15:08.789  7303  7303 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-22 11:15:08.809  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:08.809  1016  1126 D SecContentProvider2: mCursor = null
,08-22 11:15:08.819  1981  2220 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-22 11:15:08.869  1981  2220 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,08-22 11:15:08.869  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-22 11:15:08.909  7303  7303 E wpa_supplicant: Cmd 35605 not handled
,08-22 11:15:08.909  7303  7303 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-22 11:15:08.909  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:08.909  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:08.909  7303  7303 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-22 11:15:08.909  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 11:15:08.909  7303  7303 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-22 11:15:08.909  7303  7303 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-22 11:15:08.909  7303  7303 I wpa_supplicant: Associated with F4.99.3E
08-22 11:15:08.909  7303  7303 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-22 11:15:08.909  7303  7303 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-22 11:15:08.909  7303  7303 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-22 11:15:08.909  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:08.909  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 11:15:08.909  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 11:15:08.909  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:08.909  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:08.909  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:08.909  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-22 11:15:08.909  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-22 11:15:08.909  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-22 11:15:08.909  1016  1130 E Tethering: No numeric data
,08-22 11:15:08.909  1016  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-22 11:15:08.909  1016  1130 D Tethering: clearTetheredNotification()
,08-22 11:15:08.909  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:08.909  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-22 11:15:08.919  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-22 11:15:08.919  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 11:15:08.919  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 11:15:08.919  1174  1174 D HotspotTile: updateTetherState():false, false
08-22 11:15:08.919  1016  1126 D SecContentProvider2: mCursor = null
,08-22 11:15:08.919  1016  1123 V NetworkStats: performPollLocked() took 4ms
08-22 11:15:08.919  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 11:15:08.919  7303  7303 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-22 11:15:08.919  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:08.919  7303  7303 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-22 11:15:08.919  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:08.919  1016  1126 D SecContentProvider2: mCursor = null,
08-22 11:15:08.919  7303  7303 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-22 11:15:08.919  7303  7303 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030,
08-22 11:15:08.919  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-22 11:15:08.919  7303  7303 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-22 11:15:08.919  7303  7303 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-22 11:15:08.919  7303  7303 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-22 11:15:08.919  7303  7303 I wpa_supplicant: Blacklist: Clear (temp) 
08-22 11:15:08.919  7303  7303 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-22 11:15:08.919  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-22 11:15:08.919  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-22 11:15:08.919  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:08.919  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:08.929  1016  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-22 11:15:08.929  1016  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-22 11:15:08.929  1016  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-22 11:15:08.929  1016  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-22 11:15:08.929  1016  1128 E ConnectivityService: updateNetworkInfo()
08-22 11:15:08.929  1016  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-22 11:15:08.929  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 11:15:08.929  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:08.929  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:08.929  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:08.929  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:08.929  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:08.939  1016  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-22 11:15:08.939  1016  1492 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 11:15:08.939  1016  1492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:08.939  1016  1492 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:08.939  1016  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:08.939  1016  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-22 11:15:08.949  1016  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 11:15:08.949  1620  1620 I Hs20UtilService: Starting #14
,08-22 11:15:08.949  3060  3060 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-22 11:15:08.949  3060  3060 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-22 11:15:08.949  1620  1640 I Hs20UtilService: Message received 5007
,08-22 11:15:08.949  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 11:15:08.949  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-22 11:15:08.949  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 11:15:08.949  3060  3060 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 11:15:08.949  3060  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 11:15:08.959   278  1015 D CommandListener: Setting iface cfg
,08-22 11:15:08.969  1016  1126 E WifiStateMachine: Start Dhcp Watchdog 2
,08-22 11:15:08.969  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 11:15:08.969  1016  1126 D SecContentProvider2: mCursor = null
,08-22 11:15:08.979  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 11:15:08.979  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:08.979  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:08.979  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:08.979  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:08.979  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:08.979  1016  1126 E WifiNative-wlan0: do suspend false
,08-22 11:15:08.979  1016  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-22 11:15:08.989  1016  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-22 11:15:08.989  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:08.989  1016  1126 D SecContentProvider2: mCursor = null
,08-22 11:15:09.199  7397  7397 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-22 11:15:09.209  7397  7397 I dhcpcd  : version 5.5.6 starting,
,08-22 11:15:09.209  7397  7397 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-22 11:15:09.269  7397  7397 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-22 11:15:09.269  7397  7397 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-22 11:15:09.269  7397  7397 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-22 11:15:09.269  7397  7397 I dhcpcd  : bssid match
08-22 11:15:09.269  7397  7397 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-22 11:15:09.269  1016  3767 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-22 11:15:09.269  1016  3767 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-22 11:15:09.269  1016  3767 D SecContentProvider2: mCursor = null
,08-22 11:15:09.269  1016  3767 D WifiService: setWifiEnabled: false pid=6774, uid=10171
08-22 11:15:09.269  1016  3767 D SettingsProvider: name = wifi_on
,08-22 11:15:09.279  1016  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 11:15:09.299  1016  1126 E WifiNative-wlan0: do suspend true,
,08-22 11:15:09.329  1016  1125 D WifiP2pService: InactiveState{ what=143375 },
08-22 11:15:09.329  1016  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-22 11:15:09.329  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:09.329  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:09.329  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:09.329  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.329  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.329  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:09.329  1016  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 11:15:09.329   278  1015 D CommandListener: Clearing all IP addresses on wlan0
08-22 11:15:09.329  1016  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-22 11:15:09.329  1016  1128 E ConnectivityService: updateNetworkInfo()
08-22 11:15:09.329   278  1015 E Netd    : no such netId 503
08-22 11:15:09.329  1016  1128 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-22 11:15:09.329  1016  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-22 11:15:09.329  1016  1128 V NetworkStats: updateIfacesLocked()
,08-22 11:15:09.329  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-22 11:15:09.329  1016  1128 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:09.329  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:09.329  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:09.339  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:09.339  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 11:15:09.339  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:09.339  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.339  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.339  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.339  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:09.339  1016  1128 V NetworkStats: performPollLocked() took 8ms
08-22 11:15:09.339  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:09.339  1016  1537 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:09.339  1016  1537 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:09.339  1016  1537 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:09.339  1016  1537 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:09.339  1016  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 11:15:09.349  1016  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-22 11:15:09.349  1016  7395 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:09.349  1016  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-22 11:15:09.349  1016  7395 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-22 11:15:09.349  1016  1125 D WifiP2pService: InactiveState{ what=131204 }
08-22 11:15:09.349  1016  1128 D ConnectivityService: nai.networkMonitor.doQuit()
08-22 11:15:09.349  1016  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-22 11:15:09.349  1016  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-22 11:15:09.349  1620  1620 I Hs20UtilService: Starting #15
08-22 11:15:09.349  1016  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-22 11:15:09.349  1016  1128 E ConnectivityService: updateNetworkInfo()
08-22 11:15:09.349  1016  1128 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-22 11:15:09.349  1620  1640 I Hs20UtilService: Message received 5007
,08-22 11:15:09.359  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1
,08-22 11:15:09.359  1016  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:09.359  1016  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-22 11:15:09.359  1016  1016 D RttService: SCAN_AVAILABLE : 1
08-22 11:15:09.359  1016  1150 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:09.359  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:09.359  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:09.359  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 11:15:09.359  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-22 11:15:09.359  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 11:15:09.359  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-22 11:15:09.369  3060  3060 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 11:15:09.369  3060  3060 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 11:15:09.369  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-22 11:15:09.369  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - P2P: FAILED
,08-22 11:15:09.379  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-22 11:15:09.379  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-22 11:15:09.379  3060  3060 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 11:15:09.379  7397  7397 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
08-22 11:15:09.379  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-22 11:15:09.379  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 11:15:09.379  1016  1128 E ConnectivityService: updateNetworkInfo()
08-22 11:15:09.379  1016  1046 D WifiDisplayController: disconnect
08-22 11:15:09.379  3060  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-22 11:15:09.379  1016  1046 D WifiDisplayController: updateConnection
08-22 11:15:09.379  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 11:15:09.379  1016  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-22 11:15:09.379  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 11:15:09.389  1016  1125 D WifiP2pService: P2pDisablingState
,08-22 11:15:09.389  1016  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-22 11:15:09.389  1016  1125 D WifiP2pService: p2p socket connection lost
,08-22 11:15:09.389  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-22 11:15:09.389  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-22 11:15:09.389  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 11:15:09.389  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-22 11:15:09.389  1016  1126 E WifiNative-wlan0: do suspend true
08-22 11:15:09.389  1016  1125 D WifiP2pService: P2pDisabledState
,08-22 11:15:09.399  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-22 11:15:09.399  1016  3768 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-22 11:15:09.399  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-22 11:15:09.399  3060  3060 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE,
08-22 11:15:09.399  3060  3060 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 11:15:09.409  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-22 11:15:09.409  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 11:15:09.409  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 11:15:09.409  3060  3060 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 11:15:09.409  3060  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 11:15:09.419  7353  7353 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 11:15:09.419  1016  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
08-22 11:15:09.419  1016  1125 D WifiP2pService: DefaultState{ what=143375 }
,08-22 11:15:09.419  7353  7353 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-22 11:15:09.419  7353  7353 D FileShare-Client: Outbound.stopDelayTimer - 
,08-22 11:15:09.419  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 11:15:09.419  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-22 11:15:09.419  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:09.429  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:09.429  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:09.429  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:09.429   278  1015 D CommandListener: Clearing all IP addresses on wlan0
,08-22 11:15:09.429  7368  7368 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 11:15:09.429  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-22 11:15:09.429  7303  7303 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-22 11:15:09.439  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:09.439  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:09.439  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.439  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.439  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.439  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:09.439  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:09.439  1016  1126 D SecContentProvider2: mCursor = null
,08-22 11:15:09.449  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 11:15:09.449  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-22 11:15:09.449  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:09.449  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:09.449  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:09.449  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:09.449  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:09.449  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-22 11:15:09.449  3060  3060 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:09.459  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:09.459  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:09.459  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:09.459  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:09.459  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:09.459  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:09.459  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:09.459  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:09.459  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:09.459  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 11:15:09.459  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:09.459  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:09.459  1174  1671 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 11:15:09.459  1174  1174 D HotspotTile: onReceive : 0, 0
,08-22 11:15:09.459  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:09.459  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:09.459  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:09.459  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:09.459  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:09.459  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:09.459  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:09.459  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:09.459  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 11:15:09.459  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:09.459  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:09.459  1016  1537 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:09.459  1016  1537 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:09.459  1016  1537 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:09.459  1016  1537 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:09.459  1016  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:09.459  1620  1620 I Hs20UtilService: Starting #16
,08-22 11:15:09.459  1620  1640 I Hs20UtilService: Message received 5007
,08-22 11:15:09.469  3060  3060 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 11:15:09.469  3060  3060 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-22 11:15:09.469  7397  7397 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-22 11:15:09.469  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-22 11:15:09.469  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 11:15:09.469  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 11:15:09.469  3060  3060 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 11:15:09.469  3060  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 11:15:09.479  1016  3764 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-22 11:15:09.479  1016  3764 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-22 11:15:09.479  1016  3764 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:09.479  1016  3764 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:09.479  1016  3764 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:09.479  1620  1620 I Hs20UtilService: Starting #17
,08-22 11:15:09.479  1620  1640 I Hs20UtilService: Message received 5011
,08-22 11:15:09.479  6545  6545 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-22 11:15:09.479  6545  6545 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-22 11:15:09.479  6545  6545 D SecurityLogAgent: StateMachine : Current State = 1
08-22 11:15:09.479  6545  6545 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 11:15:09.549  7303  7303 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 11:15:09.609  7303  7303 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
08-22 11:15:09.609  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 11:15:09.609  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 11:15:09.609  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 11:15:09.629  7303  7303 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
08-22 11:15:09.629  7303  7303 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-22 11:15:09.629  7303  7303 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,08-22 11:15:09.629  7303  7303 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-22 11:15:09.629  7303  7303 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-22 11:15:09.629  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:09.629  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:09.629  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:09.629  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 11:15:09.639  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:09.629  1016  1130 D Tethering: InitialState.processMessage what=4
08-22 11:15:09.629  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:09.629  1016  1043 D Tethering: interfaceStatusChanged wlan0, false,
08-22 11:15:09.639  1016  1130 E Tethering: No numeric data
08-22 11:15:09.639  1016  1123 V NetworkStats: performPollLocked() took 4ms
08-22 11:15:09.639  1016  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 11:15:09.639  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 11:15:09.639  1016  1130 D Tethering: clearTetheredNotification()
08-22 11:15:09.639  1174  1174 D HotspotTile: updateTetherState():false, false
08-22 11:15:09.639  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:09.639  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:09.639  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:09.639  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 11:15:09.639  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:09.639   331   331 I ServiceManager: Waiting for service AtCmdFwd...
08-22 11:15:09.639  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:09.639  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 11:15:09.639  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:09.639  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:09.899  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 11:15:09.899  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:09.899  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:10.019  7303  7303 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 11:15:10.099  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-22 11:15:10.099  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:10.099  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:10.099  7303  7303 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-22 11:15:10.119  1016  3765 I ActivityManager: Killing 6881:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-22 11:15:10.209  1016  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-22 11:15:10.209  1016  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-22 11:15:10.219  6992  6992 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 11:15:10.219  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 11:15:10.219  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 11:15:10.219  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:10.219  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:10.219  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:10.219  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:10.219  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:10.219  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-22 11:15:10.219  1174  1671 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-22 11:15:10.219  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:10.219  1981  2215 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 11:15:10.219  1174  1174 D HotspotTile: onReceive : 1, 0
,08-22 11:15:10.229  3060  3060 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:10.229  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-22 11:15:10.229  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-22 11:15:10.239  1016  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 11:15:10.239  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:10.239  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:10.239  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:10.239  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:10.249  1620  1620 I Hs20UtilService: Starting #18
,08-22 11:15:10.249  6545  6545 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-22 11:15:10.249  6545  6545 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 11:15:10.249  6545  6545 D SecurityLogAgent: StateMachine : Current State = 1
08-22 11:15:10.249  6545  6545 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-22 11:15:10.249  1620  1640 I Hs20UtilService: Message received 5011
,08-22 11:15:10.639   288   288 E SMD     : DCD OFF,
,08-22 11:15:10.649   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 11:15:10.909   278  1009 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-22 11:15:10.909  1016  1043 D Tethering: interfaceRemoved wlan0
,08-22 11:15:10.909  1016  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-22 11:15:10.979  1981  2220 I art     : Explicit concurrent mark sweep GC freed 45888(2MB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 11MB/18MB, paused 1.704ms total 105.425ms
,08-22 11:15:10.999  1981  2220 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-22 11:15:10.999  1981  2220 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-22 11:15:11.169  1016  1043 D Tethering: interfaceRemoved p2p0
,08-22 11:15:11.169  1016  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-22 11:15:11.649   331   331 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-22 11:15:11.969  1016  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-22 11:15:12.289  6774  6827 D BluetoothAdapter: enable()
,08-22 11:15:12.289  1016  1029 W ActivityManager: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-22 11:15:12.289  1016  1029 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-22 11:15:12.289  1016  1029 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-22 11:15:12.289  1016  1029 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 11:15:12.289  1016  1029 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-22 11:15:12.289  1016  1029 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-22 11:15:12.289  1016  1029 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-22 11:15:12.289  1016  1029 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-22 11:15:12.289  1016  1029 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-22 11:15:12.289  1016  1029 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 11:15:12.289  1016  1029 D SettingsProvider: name = bluetooth_on
,08-22 11:15:12.299  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 11:15:12.299  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 11:15:12.299  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-22 11:15:12.299  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-22 11:15:12.299  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:12.299  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:12.299  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:12.299  1016  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:12.319  7428  7428 E Zygote  : MountEmulatedStorage()
,08-22 11:15:12.319  7428  7428 I libpersona: KNOX_SDCARD checking this for 1002
08-22 11:15:12.319  7428  7428 E Zygote  : v2
08-22 11:15:12.319  7428  7428 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:12.319  7428  7428 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 11:15:12.319  1016  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7428 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-22 11:15:12.319  7428  7428 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:12.329  7428  7428 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:12.349  7428  7428 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-22 11:15:12.349  7428  7428 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:12.369  7428  7428 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-22 11:15:12.369  7428  7428 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-22 11:15:12.399  7428  7428 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-22 11:15:12.429  7428  7428 D BtSettings.ProfileConfig: Adding GattService
,08-22 11:15:12.429  7428  7428 D BtSettings.ProfileConfig: Adding HeadsetService
,08-22 11:15:12.429  7428  7428 D BtSettings.ProfileConfig: Adding A2dpService
,08-22 11:15:12.429  7428  7428 D BtSettings.ProfileConfig: Adding HidService
08-22 11:15:12.439  7428  7428 D BtSettings.ProfileConfig: Adding HealthService
08-22 11:15:12.439  7428  7428 D BtSettings.ProfileConfig: Adding PanService,
08-22 11:15:12.439  7428  7428 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-22 11:15:12.439  7428  7428 D BtSettings.ProfileConfig: Adding SapService
08-22 11:15:12.439  7428  7428 D BtSettings.ProfileConfig: Adding HeadsetClientService,
08-22 11:15:12.439  7428  7428 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-22 11:15:12.439  7428  7428 D BtSettings.ProfileConfig: Adding SapClientService
08-22 11:15:12.439  7428  7428 D BtSettings.ProfileConfig: Adding HidDevService
08-22 11:15:12.439  7428  7428 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******,
,08-22 11:15:12.439  1016  1504 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService,
08-22 11:15:12.439  1016  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:12.439  1016  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 11:15:12.439  1016  1504 D SettingsProvider: selectionArgs: false
08-22 11:15:12.439  1016  1504 D SettingsProvider: selectionArgs: 1002
08-22 11:15:12.439  1016  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-22 11:15:12.439  1016  1504 D SettingsProvider: ret = -1
08-22 11:15:12.439  1016  1514 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-22 11:15:12.439  1016  1514 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-22 11:15:12.439  1016  1514 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:12.439  1016  1514 D SettingsProvider: selectionArgs: false
08-22 11:15:12.439  1016  1514 D SettingsProvider: selectionArgs: 1002
08-22 11:15:12.439  1016  1514 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:12.439  1016  1514 D SettingsProvider: ret = -1
,08-22 11:15:12.439  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-22 11:15:12.439  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:12.439  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:12.439  1016  1028 D SettingsProvider: selectionArgs: false
08-22 11:15:12.439  1016  1028 D SettingsProvider: selectionArgs: 1002,
08-22 11:15:12.439  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:12.439  1016  1028 D SettingsProvider: ret = -1
08-22 11:15:12.439  1016  3765 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-22 11:15:12.439  1016  3765 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-22 11:15:12.439  1016  3765 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:12.439  1016  3765 D SettingsProvider: selectionArgs: false
08-22 11:15:12.439  1016  3765 D SettingsProvider: selectionArgs: 1002
,08-22 11:15:12.439  1016  3765 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:12.439  1016  3765 D SettingsProvider: ret = -1
08-22 11:15:12.439  1016  3767 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-22 11:15:12.439  1016  3767 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-22 11:15:12.439  1016  3767 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:12.439  1016  3767 D SettingsProvider: selectionArgs: false
08-22 11:15:12.439  1016  3767 D SettingsProvider: selectionArgs: 1002
08-22 11:15:12.439  1016  3767 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-22 11:15:12.439  1016  3767 D SettingsProvider: ret = -1
08-22 11:15:12.439  1016  1214 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-22 11:15:12.439  1016  1214 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:12.439  1016  1214 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-22 11:15:12.439  1016  1214 D SettingsProvider: selectionArgs: false
08-22 11:15:12.439  1016  1214 D SettingsProvider: selectionArgs: 1002
08-22 11:15:12.439  1016  1214 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:12.439  1016  1214 D SettingsProvider: ret = -1
,08-22 11:15:12.449  1016  3768 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-22 11:15:12.449  1016  3768 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:12.449  1016  3768 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:12.449  1016  3768 D SettingsProvider: selectionArgs: false
,08-22 11:15:12.449  1016  3768 D SettingsProvider: selectionArgs: 1002
08-22 11:15:12.449  1016  3768 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:12.449  1016  3768 D SettingsProvider: ret = -1
,08-22 11:15:12.449  1016  1536 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-22 11:15:12.449  1016  1536 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:12.449  1016  1536 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:12.449  1016  1536 D SettingsProvider: selectionArgs: false
,08-22 11:15:12.449  1016  1536 D SettingsProvider: selectionArgs: 1002
08-22 11:15:12.449  1016  1536 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:12.449  1016  1536 D SettingsProvider: ret = -1
08-22 11:15:12.449  1016  1428 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:12.449  1016  1428 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-22 11:15:12.449  1016  1428 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:12.449  1016  1428 D SettingsProvider: selectionArgs: false
08-22 11:15:12.449  1016  1428 D SettingsProvider: selectionArgs: 1002
08-22 11:15:12.449  1016  1428 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-22 11:15:12.449  1016  1428 D SettingsProvider: ret = -1
08-22 11:15:12.449  1016  1492 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:12.449  1016  1492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-22 11:15:12.449  1016  1492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:12.449  1016  1492 D SettingsProvider: selectionArgs: false
,08-22 11:15:12.449  1016  1492 D SettingsProvider: selectionArgs: 1002
08-22 11:15:12.449  1016  1492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:12.449  1016  1492 D SettingsProvider: ret = -1
,08-22 11:15:12.449  1016  1537 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-22 11:15:12.449  1016  1537 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:12.449  1016  1537 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 11:15:12.449  1016  1537 D SettingsProvider: selectionArgs: false
,08-22 11:15:12.449  1016  1537 D SettingsProvider: selectionArgs: 1002
08-22 11:15:12.449  1016  1537 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-22 11:15:12.449  1016  1537 D SettingsProvider: ret = -1
08-22 11:15:12.449  1016  3764 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-22 11:15:12.449  1016  3764 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:12.449  1016  3764 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:12.449  1016  3764 D SettingsProvider: selectionArgs: false
,08-22 11:15:12.449  1016  3764 D SettingsProvider: selectionArgs: 1002
08-22 11:15:12.449  1016  3764 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:12.449  1016  3764 D SettingsProvider: ret = -1
,08-22 11:15:12.469  7428  7428 D BluetoothAdapterState: make
,08-22 11:15:12.469  7428  7443 I BluetoothAdapterState: Entering OffState
,08-22 11:15:12.469  7428  7428 I bluedroid: init
,08-22 11:15:12.479  7428  7428 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-22 11:15:12.479  7428  7428 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-22 11:15:12.479  7428  7428 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-22 11:15:12.479  7428  7428 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-22 11:15:12.479  7428  7428 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-22 11:15:12.479  7428  7428 I bluedroid: get_profile_interface socket
08-22 11:15:12.479  7428  7428 I bluedroid: get_profile_interface map_client
,08-22 11:15:12.489  7428  7428 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
08-22 11:15:12.489  7428  7446 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-22 11:15:12.489  7428  7446 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-22 11:15:12.489  7428  7446 E BluetoothServiceJni: populateRssiValuesNative
,08-22 11:15:12.489  7428  7446 I bluedroid: getModelRssiValues
,08-22 11:15:12.489  7428  7446 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-22 11:15:12.489  7428  7446 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-22 11:15:12.499  7428  7428 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:12.499  1016  1016 D SettingsProvider: name = bluetooth_name
08-22 11:15:12.499  7428  7446 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
08-22 11:15:12.499  1016  1428 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-22 11:15:12.499  1016  1428 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 11:15:12.499  1016  1428 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:12.499  1016  1428 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:12.499  1016  1428 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:12.499  7428  7439 I bluedroid: config_hci_snoop_log
,08-22 11:15:12.499  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-22 11:15:12.509  1016  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-22 11:15:12.509  1016  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-22 11:15:12.509  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-22 11:15:12.509  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-22 11:15:12.509  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 11:15:12.509  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 11:15:12.519  7428  7428 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-22 11:15:12.519  1016  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-22 11:15:12.529  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-22 11:15:12.529  7428  7443 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-22 11:15:12.529  7428  7443 D BluetoothAdapterProperties: Setting state to 11
,08-22 11:15:12.529  7428  7443 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-22 11:15:12.529  7428  7443 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-22 11:15:12.529  7428  7443 D BluetoothAdapterService: updateAdapterState state is 11
,08-22 11:15:12.529  7428  7443 D BluetoothAdapterService: Autoconnection is available 
,08-22 11:15:12.529  7428  7443 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-22 11:15:12.529  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:12.529  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
,08-22 11:15:12.529  7428  7443 D BluetoothSecureManager: getInstant: null
,08-22 11:15:12.529  7428  7443 D BluetoothSecureManager: calling getMethod for getService
08-22 11:15:12.529  7428  7443 D BluetoothSecureManager: calling getService
08-22 11:15:12.539  7428  7443 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3ab4acb6
08-22 11:15:12.539  1016  1504 D BluetoothSecureManagerService: isSecureModeEnabled
08-22 11:15:12.539  1016  1504 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-22 11:15:12.539  7428  7443 D BtConfig.SecureMode: isSecureModeOn:false
08-22 11:15:12.539  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-22 11:15:12.539  7428  7443 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-22 11:15:12.539  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-22 11:15:12.539  7428  7443 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,08-22 11:15:12.539  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-22 11:15:12.549  1919  1919 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 11:15:12.549  7428  7443 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-22 11:15:12.549  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-22 11:15:12.549  7428  7443 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-22 11:15:12.549  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-22 11:15:12.549  7428  7443 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-22 11:15:12.549  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-22 11:15:12.549  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 11:15:12.549  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:12.549  7428  7443 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-22 11:15:12.549  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-22 11:15:12.549  1174  1174 D BluetoothTile:  getBluetoothState : 11
,08-22 11:15:12.549  7428  7443 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-22 11:15:12.549  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 11:15:12.549  3060  3060 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:12.549  7428  7443 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-22 11:15:12.549  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 11:15:12.549  7428  7443 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:12.549  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-22 11:15:12.549  7428  7443 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:12.549  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-22 11:15:12.549  1016  1428 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:12.549  7428  7443 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-22 11:15:12.549  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-22 11:15:12.549  1016  3767 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 11:15:12.559  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-22 11:15:12.559  7428  7443 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-22 11:15:12.559  1174  1671 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:12.559  1016  1504 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:15:12.559  1016  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-22 11:15:12.559  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:12.559  1016  1504 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:12.559  1174  1671 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-22 11:15:12.559  1016  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:12.559  1016  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:12.569  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:12.569  3060  3060 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 11:15:12.569  7428  7443 D BluetoothBondStateMachine: make
,08-22 11:15:12.579  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-22 11:15:12.579  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-22 11:15:12.579  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-22 11:15:12.579  7428  7449 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-22 11:15:12.579  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:12.579  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-22 11:15:12.579  1016  1536 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:12.579  1016  1536 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-22 11:15:12.579  1016  1536 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:12.579  1016  1536 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:12.579  1016  1536 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:12.589  1016  1428 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-22 11:15:12.589  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-22 11:15:12.589  7428  7428 D BtGatt.DebugUtils: handleDebugAction() action=null
08-22 11:15:12.589  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 11:15:12.589  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-22 11:15:12.589  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:12.589  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:12.589  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:12.589  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:12.589  7428  7428 D BtGatt.GattService: Received start request. Starting profile...
,08-22 11:15:12.589  7428  7428 D BtGatt.GattService: start()
,08-22 11:15:12.589  7428  7428 D BtGatt.GattService: start()
08-22 11:15:12.589  7428  7428 I bluedroid: get_profile_interface gatt
08-22 11:15:12.589  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
08-22 11:15:12.589  7428  7428 D BtGatt.AdvertiseManager: advertise manager created
,08-22 11:15:12.609  7451  7451 E Zygote  : MountEmulatedStorage(),
08-22 11:15:12.609  7451  7451 I libpersona: KNOX_SDCARD checking this for 10055,
08-22 11:15:12.609  7451  7451 E Zygote  : v2,
08-22 11:15:12.609  7451  7451 I libpersona: KNOX_SDCARD not a persona
08-22 11:15:12.609  7451  7451 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:12.609  7451  7451 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:12.609  7451  7451 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:12.609  1016  1428 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7451 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-22 11:15:12.619  1016  3767 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:12.619  1016  3767 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-22 11:15:12.619  1016  3767 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:12.619  1016  3767 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:12.619  1016  3767 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:12.629  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-22 11:15:12.629  1016  3768 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:12.629  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-22 11:15:12.629  1016  3768 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-22 11:15:12.629  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-22 11:15:12.629  7428  7428 D BtGatt.GattService: mStartError = false
08-22 11:15:12.629  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
08-22 11:15:12.629  1016  3768 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:12.629  1016  3768 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:12.629  1016  3768 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 11:15:12.629  7428  7428 D HeadsetService: Received start request. Starting profile...
08-22 11:15:12.629  7428  7428 D HeadsetService: start()
,08-22 11:15:12.629  7428  7428 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-22 11:15:12.629  7428  7428 D HeadsetStateMachine: make
,08-22 11:15:12.629  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-22 11:15:12.629  1016  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:12.629  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 11:15:12.629  1016  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-22 11:15:12.629  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-22 11:15:12.639  1016  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:12.639  1016  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:12.639  1016  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:12.639  7428  7428 E HeadsetStateMachine: # of Max HF connection is 2
,08-22 11:15:12.649  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-22 11:15:12.649  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-22 11:15:12.649  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-22 11:15:12.649  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:12.649  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-22 11:15:12.649  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:12.649  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:12.649  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:12.649  1016  1504 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-22 11:15:12.649  1016  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-22 11:15:12.649  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-22 11:15:12.649  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-22 11:15:12.649  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-22 11:15:12.649  1016  1504 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:12.649  1016  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:12.649  1016  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-22 11:15:12.649  1016  1537 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:12.649  1016  1537 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 11:15:12.649  1016  1537 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:12.649  1016  1537 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:12.649  1016  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:12.659  1016  1514 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-22 11:15:12.659  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-22 11:15:12.659  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:12.659  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-22 11:15:12.659  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-22 11:15:12.659  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:12.659  1016  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:12.659  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-22 11:15:12.659  7428  7428 I bluedroid: get_profile_interface handsfree
,08-22 11:15:12.659  1016  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:12.659  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-22 11:15:12.669  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:12.669  1016  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:12.669  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:12.669  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-22 11:15:12.669  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 11:15:12.669  7428  7443 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-22 11:15:12.669  1016  1428 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:12.669  1016  1428 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-22 11:15:12.679  1016  1428 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:12.679  1016  1428 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:12.679  1016  1428 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:12.679  7451  7451 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:15:12.679  7451  7451 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:12.689  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 11:15:12.689  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 11:15:12.689  7428  7443 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:12.689  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:12.689  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:12.689  7428  7443 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:12.689  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-22 11:15:12.689  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-22 11:15:12.689  7428  7443 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-22 11:15:12.689  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-22 11:15:12.689  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 11:15:12.689  7428  7443 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-22 11:15:12.689  7428  7443 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-22 11:15:12.699  7428  7428 I DualScoManager: Instantiating Dual Sco Manager
08-22 11:15:12.699  7428  7428 I DualScoManager: Set HeadsetServiceHelper
,08-22 11:15:12.699  7428  7428 D BluetoothAtMessage: createCMTIContentObservers
,08-22 11:15:12.699  1016  3765 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-22 11:15:12.699  1016  3765 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:12.699  1016  3765 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:12.699  1016  3765 D SettingsProvider: selectionArgs: false
08-22 11:15:12.699  1016  3765 D SettingsProvider: selectionArgs: 1002
08-22 11:15:12.699  1016  3765 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:12.699  1016  3765 D SettingsProvider: ret = -1
,08-22 11:15:12.699  7428  7460 D HeadsetStateMachine: Enter Disconnected: -2
,08-22 11:15:12.699  7428  7428 D HeadsetService: mStartError = false
08-22 11:15:12.699  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
08-22 11:15:12.699  7428  7428 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-22 11:15:12.699  7428  7460 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-22 11:15:12.699  7428  7460 D HeadsetStateMachine: map size, before remove : 0
08-22 11:15:12.699  7428  7460 D HeadsetStateMachine: map size, after remove: 0
,08-22 11:15:12.709  7428  7428 D A2dpService: Received start request. Starting profile...
08-22 11:15:12.709  7428  7428 D A2dpService: start()
,08-22 11:15:12.709  7428  7428 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-22 11:15:12.709  7428  7428 I bluedroid: get_profile_interface avrcp
,08-22 11:15:12.719  7451  7451 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-22 11:15:12.719  7428  7428 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-22 11:15:12.719  7428  7428 D Avrcp   : Initialize Media Controller
,08-22 11:15:12.719  7428  7428 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-22 11:15:12.719  7428  7428 E Avrcp   : getActiveSessions
08-22 11:15:12.719  7428  7428 D Avrcp   : pick active media Controller
08-22 11:15:12.719  7428  7428 D Avrcp   : Get the active Media Controller 
,08-22 11:15:12.739  7428  7428 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-22 11:15:12.739  7428  7471 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include,
,08-22 11:15:12.739  7428  7428 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-22 11:15:12.739  7428  7428 D A2dpStateMachine: make
,08-22 11:15:12.739  7428  7428 I bluedroid: get_profile_interface a2dp
,08-22 11:15:12.749  7428  7473 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-22 11:15:12.749  7428  7428 E bt-btif : warning : media task started media_task_refcnt 1 
,08-22 11:15:12.749  7428  7428 D A2dpService: mStartError = false
08-22 11:15:12.749  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
08-22 11:15:12.749  7428  7428 I BluetoothHidServiceJni: classInitNative: succeeds
08-22 11:15:12.749  7451  7451 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-22 11:15:12.749  7428  7472 D A2dpStateMachine: Enter Disconnected: -2
08-22 11:15:12.749  7428  7471 D BluetoothMediaBrowser: no now playing list
08-22 11:15:12.749  7428  7471 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-22 11:15:12.749  7451  7451 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-22 11:15:12.749  7451  7451 D UserAnalysis: Create SecureDbHelper
,08-22 11:15:12.759  7428  7428 D HidService: Received start request. Starting profile...
08-22 11:15:12.759  7428  7428 D HidService: start()
08-22 11:15:12.759  7428  7428 I bluedroid: get_profile_interface hidhost
08-22 11:15:12.759  7428  7428 D HidService: setHidService(): set to: null
08-22 11:15:12.759  7428  7428 D HidService: mStartError = false
08-22 11:15:12.759  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:12.759  7428  7428 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-22 11:15:12.759  7428  7428 D HeadsetStateMachine: Try to query the phonestate on bind
,08-22 11:15:12.759  7451  7451 D IntelligenceServiceApplication: onCreate()
,08-22 11:15:12.759  1446  1472 I Telecom : BluetoothPhoneService: queryPhoneState
,08-22 11:15:12.759  1446  1446 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-22 11:15:12.759  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-22 11:15:12.759  1446  1472 I Telecom : BluetoothPhoneService: Result of Message : true
,08-22 11:15:12.769  7428  7428 D HealthService: Received start request. Starting profile...
08-22 11:15:12.769  7428  7428 D HealthService: start()
08-22 11:15:12.769  1016  1536 I ActivityManager: Killing 7047:com.sec.pcw.device/1000 (adj 15): empty #21
08-22 11:15:12.769  7428  7428 I bluedroid: get_profile_interface health
08-22 11:15:12.769  7428  7428 D HealthService: mStartError = false
,08-22 11:15:12.769  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:12.769  7428  7428 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-22 11:15:12.779  7428  7428 D PanService: Received start request. Starting profile...
,08-22 11:15:12.779  7428  7428 D PanService: start()
08-22 11:15:12.779  7428  7428 D BluetoothPanServiceJni: initializeNative(L110): pan
08-22 11:15:12.779  7428  7428 I bluedroid: get_profile_interface pan
,08-22 11:15:12.779  7451  7451 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-22 11:15:12.779  7428  7428 D PanService: mStartError = false
08-22 11:15:12.779  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
08-22 11:15:12.779  7428  7428 D HeadsetStateMachine: Proxy object connected
,08-22 11:15:12.779  7428  7428 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-22 11:15:12.779  7428  7460 D HeadsetStateMachine: Disconnected process message: 11
,08-22 11:15:12.779  1016  3764 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-22 11:15:12.779  7451  7451 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-22 11:15:12.779  7428  7428 D BluetoothMapService: Received start request. Starting profile...
08-22 11:15:12.779  7428  7428 D BluetoothMapService: start()
,08-22 11:15:12.789  7428  7428 D BluetoothMapService: mStartError = false
08-22 11:15:12.789  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:12.789  7428  7428 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-22 11:15:12.789  7451  7451 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-22 11:15:12.789  7428  7428 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-22 11:15:12.789  7428  7428 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-22 11:15:12.789  7428  7460 D HeadsetStateMachine: Disconnected process message: 18
08-22 11:15:12.789  7428  7428 D SapService: Received start request. Starting profile...
08-22 11:15:12.789  7428  7428 D SapService: start()
08-22 11:15:12.789  7428  7428 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-22 11:15:12.789  7428  7428 I bluedroid: get_profile_interface sap
08-22 11:15:12.789  7428  7428 D SapService: mStartError = false
08-22 11:15:12.789  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
08-22 11:15:12.789  7428  7428 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-22 11:15:12.789  7428  7428 D BluetoothA2dp: Proxy object connected
08-22 11:15:12.789  7428  7428 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-22 11:15:12.789  7428  7428 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-22 11:15:12.789  7428  7428 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,08-22 11:15:12.789  7428  7460 D HeadsetStateMachine: Disconnected process message: 10
08-22 11:15:12.789  7428  7460 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-22 11:15:12.789  7428  7460 D HeadsetStateMachine: Disconnected process message: 11
,08-22 11:15:12.799  7428  7428 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-22 11:15:12.799  7428  7428 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-22 11:15:12.799  7428  7428 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-22 11:15:12.799  1016  3768 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-22 11:15:12.799  1016  3768 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:12.799  1016  3768 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:12.799  1016  3768 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:12.799  1016  3768 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:12.819  7478  7478 E Zygote  : MountEmulatedStorage(),
,08-22 11:15:12.819  7478  7478 E Zygote  : v2,
08-22 11:15:12.819  1016  3768 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7478 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-22 11:15:12.819  7478  7478 I libpersona: KNOX_SDCARD checking this for 10105
08-22 11:15:12.819  7478  7478 I libpersona: KNOX_SDCARD not a persona
08-22 11:15:12.819  7478  7478 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:12.819  7478  7478 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:12.829  7478  7478 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 11:15:12.839  7428  7428 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-22 11:15:12.839  7428  7428 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-22 11:15:12.849  7478  7478 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:12.849  7478  7478 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:12.849  7428  7443 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-22 11:15:12.849  7428  7443 I bluedroid: enable
,08-22 11:15:12.849  7428  7443 I bt_hci_bdroid: init,
,08-22 11:15:12.849  7428  7494 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-22 11:15:12.859  7428  7443 I bt_vendor: bt-vendor : init
08-22 11:15:12.859  7428  7443 I bt_vendor: bt-vendor : get_bt_soc_type
08-22 11:15:12.859  7428  7443 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-22 11:15:12.859  7428  7443 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-22 11:15:12.859  7428  7443 D bt_userial_mct: userial_init
,08-22 11:15:12.859  7428  7443 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-22 11:15:12.859  7428  7443 I bt_vendor: Starting hciattach daemon
08-22 11:15:12.859  7428  7443 I bt_vendor: try to set false
,08-22 11:15:12.859  7428  7443 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-22 11:15:12.859  7428  7443 I bt_vendor: Starting hciattach daemon
08-22 11:15:12.859  7428  7443 I bt_vendor: try to set true
,08-22 11:15:12.879  7498  7498 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-22 11:15:12.929  7504  7504 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-22 11:15:12.939  7505  7505 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-22 11:15:12.949  1016  1029 I ActivityManager: Killing 7064:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-22 11:15:12.959  7509  7509 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-22 11:15:12.969  7510  7510 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-22 11:15:12.979  7511  7511 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-22 11:15:12.979  7512  7512 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-22 11:15:13.009   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-22 11:15:13.009   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 11:15:13.009  7478  7517 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-22 11:15:13.019   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-22 11:15:13.019   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 11:15:13.019  7478  7517 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-22 11:15:13.159  7478  7478 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:13.159  7478  7478 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:13.159  7478  7478 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:13.159  7478  7478 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.q.e.b(PG:170)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:13.159  7478  7478 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.q.k.d(PG:583)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.q.e.b(PG:170)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:13.159  7478  7478 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:13.159  7478  7478 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:13.159  7478  7478 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:13.159  7478  7478 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:13.169  1016  1537 I ActivityManager: Killing 7079:com.sec.android.soagent/u0a31 (adj 15): empty #21
08-22 11:15:13.179  1981  1981 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-22 11:15:13.179  7527  7527 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
08-22 11:15:13.179  1981  1981 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-22 11:15:13.189  7528  7528 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-22 11:15:13.209  7428  7443 I bt_vendor: bluetooth satus is on
08-22 11:15:13.209  7428  7496 D bt_userial_mct: userial_open(port:0)
08-22 11:15:13.209  7428  7496 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-22 11:15:13.219  7428  7496 I bt_vendor: Done intiailizing UART
08-22 11:15:13.219  7428  7496 I bt_vendor: Done intiailizing UART
08-22 11:15:13.219  7428  7496 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-22 11:15:13.219  7428  7496 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-22 11:15:13.219  7478  7520 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-22 11:15:13.229  7428  7530 D bt_userial_mct: Entering userial_read_thread()
08-22 11:15:13.229  7428  7494 I         : BTE_InitTraceLevels -- TRC_HCI
08-22 11:15:13.229  7428  7494 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-22 11:15:13.229  7428  7494 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-22 11:15:13.229  7428  7494 I         : BTE_InitTraceLevels -- TRC_AVDT
08-22 11:15:13.229  7428  7494 I         : BTE_InitTraceLevels -- TRC_AVRC
08-22 11:15:13.229  7428  7494 I         : BTE_InitTraceLevels -- TRC_A2D
08-22 11:15:13.229  7428  7494 I         : BTE_InitTraceLevels -- TRC_BNEP
08-22 11:15:13.229  7428  7494 I         : BTE_InitTraceLevels -- TRC_BTM
08-22 11:15:13.229  7428  7494 I         : BTE_InitTraceLevels -- TRC_GAP
08-22 11:15:13.229  7428  7494 I         : BTE_InitTraceLevels -- TRC_PAN
08-22 11:15:13.229  7428  7494 I         : BTE_InitTraceLevels -- TRC_SAP
08-22 11:15:13.229  7428  7494 I         : BTE_InitTraceLevels -- TRC_SDP
08-22 11:15:13.229  7428  7494 I         : BTE_InitTraceLevels -- TRC_GATT
08-22 11:15:13.229  7428  7494 I         : BTE_InitTraceLevels -- TRC_SMP
08-22 11:15:13.229  7428  7494 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-22 11:15:13.229  7428  7494 I         : BTE_InitTraceLevels -- TRC_BTIF
08-22 11:15:13.229  7428  7494 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-22 11:15:13.319  7428  7494 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-22 11:15:13.319  7428  7494 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4212ed1 
,08-22 11:15:13.319  7428  7494 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4212ed1 
,08-22 11:15:13.339  7428  7446 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-22 11:15:13.339  7428  7446 E bt-btif : Calling BTA_HhEnable
,08-22 11:15:13.339  7428  7446 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-22 11:15:13.339  7428  7446 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-22 11:15:13.339  7428  7446 E BluetoothServiceJni: populateRssiValuesNative
08-22 11:15:13.339  7428  7446 I bluedroid: getModelRssiValues
,08-22 11:15:13.339  7428  7446 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-22 11:15:13.339  7428  7446 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-22 11:15:13.379  1016  3764 I art     : Explicit concurrent mark sweep GC freed 66244(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.451ms total 141.525ms
,08-22 11:15:13.379  1016  3767 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:13.389  1016  3767 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:13.389  1016  3767 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:13.389  1016  3767 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-22 11:15:13.389  7428  7446 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-22 11:15:13.389  1016  1016 D SettingsProvider: name = bluetooth_name
,08-22 11:15:13.389  7428  7446 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 11:15:13.389  7428  7446 D BluetoothAdapterProperties: Scan Mode:20
08-22 11:15:13.389  7428  7446 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 11:15:13.389  7428  7446 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-22 11:15:13.389  7428  7446 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-22 11:15:13.389  7428  7446 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-22 11:15:13.389  7428  7446 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-22 11:15:13.399  7428  7446 E bt-btif : btif_sock_init: !vhci_init
,08-22 11:15:13.399  7428  7446 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-22 11:15:13.399  7428  7530 E bt_mct  : hci lib postload completed
,08-22 11:15:13.399  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:13.399  7428  7446 D IOP_DB_BT: db_open: db_open : handle 3027984400l, read 13894 bytes onto local cache
08-22 11:15:13.399  7428  7446 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-22 11:15:13.399  7428  7446 D IOP_DB_BT: db_query: result 1
08-22 11:15:13.399  7428  7446 I         : iop_db_open: iop_db_open status 0
08-22 11:15:13.399  7428  7446 D bte_conf: Device ID record 1 : primary
08-22 11:15:13.399  7428  7446 D bte_conf:   vendorId            = 0075
08-22 11:15:13.399  7428  7446 D bte_conf:   vendorIdSource      = 0001
08-22 11:15:13.399  7428  7446 D bte_conf:   product             = 0100
08-22 11:15:13.399  7428  7446 D bte_conf:   version             = 0200
08-22 11:15:13.399  7428  7446 D bte_conf:   clientExecutableURL = 
08-22 11:15:13.399  7428  7446 D bte_conf:   serviceDescription  = 
08-22 11:15:13.399  7428  7446 D bte_conf:   documentationURL    = 
08-22 11:15:13.399  7428  7446 D bte_conf: bte_load_did_conf no section named DID2.
08-22 11:15:13.399  7428  7443 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-22 11:15:13.399  7428  7443 D BluetoothAdapterProperties: ScanMode =  20
08-22 11:15:13.399  7428  7443 D BluetoothAdapterProperties: State =  11
08-22 11:15:13.399  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:13.399  7428  7446 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-22 11:15:13.409  1016  3768 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-22 11:15:13.409  7428  7443 D BluetoothAdapterProperties: Setting state to 12
,08-22 11:15:13.409  7428  7443 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-22 11:15:13.419  7428  7446 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-22 11:15:13.419  7428  7446 D BluetoothAdapterProperties: Scan Mode:21
,08-22 11:15:13.419  1016  1514 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-22 11:15:13.419  1016  1514 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:13.419  1016  1514 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:13.419  1016  1514 D SettingsProvider: selectionArgs: false
08-22 11:15:13.419  1016  1514 D SettingsProvider: selectionArgs: 1002
,08-22 11:15:13.419  1016  1514 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:13.419  7428  7446 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 11:15:13.419  1016  1514 D SettingsProvider: ret = -1
08-22 11:15:13.419  7428  7443 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-22 11:15:13.419  7428  7443 D BluetoothAdapterService: updateAdapterState state is 12
,08-22 11:15:13.429  1016  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:13.429  1016  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 11:15:13.429  1016  1504 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:13.429  1016  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:13.429  1016  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 11:15:13.429  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:13.429  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:13.429  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:13.429  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:13.429  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:13.429  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:13.429  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:13.429  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:13.439  7428  7443 D BluetoothAdapterService: Autoconnection is available 
08-22 11:15:13.439  7428  7443 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-22 11:15:13.439  7428  7443 D BluetoothAdapterService: starting service from this receiver
,08-22 11:15:13.439  1016  1537 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:13.439  1016  1537 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-22 11:15:13.439  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:13.439  1016  1537 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:13.439  1456  1473 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:13.439  1456  1473 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:13.449  1016  1537 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:13.449  7428  7447 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:13.449  7428  7447 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 11:15:13.449  1016  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:13.449  3060  3073 D BluetoothPan: Binding service...
,08-22 11:15:13.449  7428  7443 I BluetoothAdapterState: Entering On State from state = 11
,08-22 11:15:13.449  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:13.449  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:13.449  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:13.449  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:13.449  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:13.449  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:13.449  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:13.449  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:13.459  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-22 11:15:13.459  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 11:15:13.459  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:13.459  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:13.459  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:13.459  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:13.459  3060  7274 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-22 11:15:13.459  7428  7428 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-22 11:15:13.469  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-22 11:15:13.469  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-22 11:15:13.469  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:13.469  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:13.469  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:13.469  3060  3070 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 11:15:13.469  3060  3070 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:13.469  6774  6784 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:13.469  6774  6784 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 11:15:13.469  1016  1045 D BluetoothPan: Binding service...
,08-22 11:15:13.469  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-22 11:15:13.469  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-22 11:15:13.469  3060  3073 D BluetoothPbap: onBluetoothStateChange: up=true
,08-22 11:15:13.479  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-22 11:15:13.479  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 11:15:13.479  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:13.479  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:13.479  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:13.479  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 11:15:13.479  1016  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-22 11:15:13.479  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 11:15:13.479  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-22 11:15:13.479  1016  1016 D BluetoothA2dp: Proxy object connected
,08-22 11:15:13.479  7428  7428 I BluetoothPbapService: Handler(): got msg=1
,08-22 11:15:13.479  1016  1492 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-22 11:15:13.489  3060  3060 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 11:15:13.489  3060  3060 D PanProfile: Bluetooth service connected
,08-22 11:15:13.489  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 11:15:13.489  1446  6914 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:13.489  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 11:15:13.489  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:13.489  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:13.489  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:13.489  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-22 11:15:13.489  1446  6914 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:13.489  7428  7536 V BluetoothPbapService: PBAP Service initSocket try: 0
08-22 11:15:13.499  3060  3073 D BluetoothMap: onBluetoothStateChange: up=true
,08-22 11:15:13.499  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-22 11:15:13.499  3060  3060 D BluetoothInputDevice: Proxy object connected
08-22 11:15:13.499  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-22 11:15:13.499  3060  3060 D HidProfile: Bluetooth service connected
,08-22 11:15:13.499  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:13.499  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:13.499  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:13.499  1446  1472 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:13.499  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 11:15:13.499  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:13.499  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:13.499  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:13.499  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:13.499  1446  1472 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:13.499  1446  1459 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:13.499  1446  1459 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 11:15:13.499  7428  7436 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 11:15:13.499  3060  3060 D BluetoothPbap: Proxy object connected
08-22 11:15:13.499  3060  3060 D PbapServerProfile: Bluetooth service connected
08-22 11:15:13.499  3060  3060 D BluetoothMap: Proxy object connected
08-22 11:15:13.499  3060  3060 D MapProfile: Bluetooth service connected
08-22 11:15:13.499  3060  3060 D BluetoothMap: getConnectedDevices()
,08-22 11:15:13.499  3060  3073 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 11:15:13.499  7428  7536 D BluetoothSocket: bindListen(): myUserId = 0
,08-22 11:15:13.499  7428  7536 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 11:15:13.509  3060  3073 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-22 11:15:13.509  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-22 11:15:13.509  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 11:15:13.509  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:13.509  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:13.509  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:13.509  1016  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-22 11:15:13.509  7428  7536 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,08-22 11:15:13.509  7428  7536 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 11:15:13.509  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 11:15:13.509  7428  7536 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 11:15:13.509  7428  7536 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@86d94ab
08-22 11:15:13.509  7428  7536 D BluetoothSocket: channel: 19
08-22 11:15:13.509  7428  7536 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-22 11:15:13.509  3060  3060 D BluetoothA2dp: Proxy object connected
08-22 11:15:13.509  3060  3060 D A2dpProfile: Bluetooth service connected
,08-22 11:15:13.509  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:13.509  1016  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:13.509  1174  1183 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:13.509  1174  1183 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 11:15:13.509  3060  7274 D Bluetoothsap: onBluetoothStateChange: up=true,
08-22 11:15:13.509  3060  7274 D Bluetoothsap: Binding service...
,08-22 11:15:13.519  3060  7274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-22 11:15:13.519  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-22 11:15:13.519  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-22 11:15:13.519  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:13.519  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:13.519  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:13.519  3060  3060 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-22 11:15:13.519  3060  7274 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-22 11:15:13.519  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:13.519  3060  3060 D SapProfile: Bluetooth service connected
08-22 11:15:13.519  1016  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 11:15:13.519  3060  3060 D Bluetoothsap: getConnectedDevices()
08-22 11:15:13.519  1481  1493 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:13.519  1481  1493 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:13.519  7478  7493 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:13.519  7478  7493 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 11:15:13.519  1981  1994 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:13.519  1981  1994 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:13.529  1446  6914 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:13.529  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 11:15:13.529  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:13.529  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:13.529  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:13.529  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:13.529  1446  6914 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:13.529  3060  3073 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:13.529  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 11:15:13.529  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:13.529  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:13.529  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:13.529  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:13.529  3060  3060 D HeadsetProfile: Bluetooth service connected
,08-22 11:15:13.529  3060  3073 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:13.539  1481  1490 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:13.539  1016  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 11:15:13.539  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:13.539  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:13.539  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:13.539  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-22 11:15:13.539  1481  1490 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:13.539  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-22 11:15:13.539  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-22 11:15:13.539  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:13.539  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
,08-22 11:15:13.539  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-22 11:15:13.549  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-22 11:15:13.549  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 11:15:13.549  1174  1671 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:13.549  1174  1671 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:13.549  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:13.549  1174  1174 D BluetoothTile:  getBluetoothState : 12
,08-22 11:15:13.549  1174  1671 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:13.549  1446  1446 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@e87d397, true
,08-22 11:15:13.559  1446  1446 D BluetoothHeadset: registerMessageListener
,08-22 11:15:13.559  1919  1919 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 11:15:13.559  1016  1514 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:13.559  1016  1428 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-22 11:15:13.559  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:13.559  7428  7436 D HeadsetService: registerMessageListener
,08-22 11:15:13.559  1016  1492 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:15:13.559  1016  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-22 11:15:13.559  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-22 11:15:13.559  7428  7436 D HeadsetService: registerMessageListener
,08-22 11:15:13.569  7428  7460 D HeadsetStateMachine: Disconnected process message: 70
08-22 11:15:13.569  1016  1492 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:13.569  7428  7460 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@21369708
08-22 11:15:13.569  1016  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:13.569  1446  1446 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-22 11:15:13.569  3060  3060 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:13.569  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-22 11:15:13.569  1016  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 11:15:13.569  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:13.569  3060  3060 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-22 11:15:13.569  3060  3060 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-22 11:15:13.569  3060  3060 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-22 11:15:13.569  3060  3060 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-22 11:15:13.569  7428  7538 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-22 11:15:13.569  1446  1446 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-22 11:15:13.569  1446  1446 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-22 11:15:13.569  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-22 11:15:13.579  7428  7460 D HeadsetStateMachine: Disconnected process message: 9,
08-22 11:15:13.579  7428  7460 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-22 11:15:13.579  7428  7538 D BluetoothSocket: bindListen(): myUserId = 0
08-22 11:15:13.579  7428  7538 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 11:15:13.579  3060  3060 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 11:15:13.579  1016  3765 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-22 11:15:13.579  1016  3765 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 11:15:13.579  1016  3765 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:13.579  1016  3765 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:13.579  1016  3765 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 11:15:13.589  7428  7538 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
,08-22 11:15:13.589  7428  7538 D BluetoothSocket: bindListen(), new LocalSocket 
,08-22 11:15:13.589  7428  7538 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 11:15:13.589  7428  7538 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e72eea1
08-22 11:15:13.589  7428  7538 D BluetoothSocket: channel: 5
,08-22 11:15:13.599   283  7027 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-22 11:15:13.599   283  7027 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-22 11:15:13.599   283  7027 V voice   : voice_set_parameters: exit with code(-2)
08-22 11:15:13.599   283  7027 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-22 11:15:13.599   283  7027 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-22 11:15:13.599   283  7027 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-22 11:15:13.599   283  7027 V audio_hw_primary: adev_set_parameters: exit
08-22 11:15:13.599  7428  7460 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-22 11:15:13.609  3060  3060 D DockEventReceiver: finishStartingService: stopping service
,08-22 11:15:13.609  3060  3060 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 11:15:13.609  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:13.609  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-22 11:15:13.619  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:13.619  7428  7428 D BtConfig.SecureMode: isSecureModeOn:false
,08-22 11:15:13.619  1016  1214 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:13.619  1016  1214 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-22 11:15:13.619  1016  1214 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:13.619  1016  1214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:13.619  1016  1214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:13.629   288   288 E SMD     : DCD OFF
,08-22 11:15:13.629  1981  1981 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:13.639  1016  3767 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:15:13.639  1016  3767 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-22 11:15:13.639  1016  3767 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:13.639  1016  3767 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:13.639  1016  3767 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:13.649  1016  3765 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
,08-22 11:15:13.659  1981  7545 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-22 11:15:13.659  1981  1981 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-22 11:15:13.659  1016  1428 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:13.659  1016  1428 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:13.659  1016  1428 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:13.659  1016  1428 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:13.679  1016  3764 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:13.679  7428  7548 D BluetoothSocket: bindListen(): myUserId = 0
,08-22 11:15:13.679  7428  7548 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 11:15:13.679  1016  3764 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:13.679  1016  3764 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:13.679  1016  3764 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:13.679  7428  7548 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-22 11:15:13.679  7428  7548 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 11:15:13.679  7428  7548 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 11:15:13.679  7428  7548 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@345dee23
,08-22 11:15:13.689  7428  7548 D BluetoothSocket: channel: 12,
08-22 11:15:13.689  7428  7548 I BtOppRfcommListener: Accept thread started.
,08-22 11:15:13.689  1981  7545 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-22 11:15:14.419  1016  3371 D SSRM:n  : SIOP:: AP = 350
,08-22 11:15:15.329  6774  6827 D BluetoothAdapter: disable()
,08-22 11:15:15.329  1016  3767 D SettingsProvider: name = bluetooth_on
,08-22 11:15:15.329  7428  7443 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-22 11:15:15.339  7428  7443 D BluetoothAdapterProperties: Setting state to 13
08-22 11:15:15.339  7428  7443 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-22 11:15:15.339  7428  7443 D BluetoothAdapterService: Bluetooth PBAP supproted is true,
08-22 11:15:15.339  7428  7443 D BluetoothAdapterService: updateAdapterState state is 13
,08-22 11:15:15.339  1016  1214 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-22 11:15:15.339  1016  1214 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 11:15:15.339  1016  1214 W ActivityManager: userId = 0, bbcId = -10000,
08-22 11:15:15.339  1016  1214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:15.339  1016  1214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:15.349  7428  7428 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-22 11:15:15.349  7428  7443 D BluetoothAdapterService: Autoconnection is available 
08-22 11:15:15.349  7428  7443 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-22 11:15:15.349  7428  7443 D BluetoothAdapterService: terminating service from this receiver
08-22 11:15:15.349  7428  7428 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c9f3f20, channel: 19, state: LISTENING
08-22 11:15:15.349  7428  7428 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3c9f3f20, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@86d94ab, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@7c9d0d9mSocket: android.net.LocalSocket@2f663a9e impl:android.net.LocalSocketImpl@897497f fd:FileDescriptor[74]
08-22 11:15:15.349  7428  7428 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2f663a9e impl:android.net.LocalSocketImpl@897497f fd:FileDescriptor[74]
,08-22 11:15:15.349  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:15.349  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
,08-22 11:15:15.359  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-22 11:15:15.359  1174  1671 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:15.359  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 11:15:15.359  1174  1671 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:15.359  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:15.359  1174  1174 D BluetoothTile:  getBluetoothState : 13
,08-22 11:15:15.369  1174  1671 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-22 11:15:15.369  1919  1919 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 11:15:15.369  1016  1492 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ),
08-22 11:15:15.369  1016  3767 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 11:15:15.369  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:15.369  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-22 11:15:15.379  3060  3060 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:15.379  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 11:15:15.379  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:15.379  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:15.379  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:15.379  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:15.379  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:15.379  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:15.379  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:15.379  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:15.379  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:15.379  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:15.389  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:15.389  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:15.389  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:15.389  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:15.389  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:15.389  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 11:15:15.389  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:15.389  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:15.389  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:15.389  6774  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 11:15:15.389  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:15.389  1016  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-22 11:15:15.389  1016  1504 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:15.389  1016  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:15.389  1016  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:15.389  7428  7428 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@18092d4c, channel: 5, state: LISTENING
08-22 11:15:15.389  7428  7428 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@18092d4c, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e72eea1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c7da195mSocket: android.net.LocalSocket@36f762aa impl:android.net.LocalSocketImpl@e0fe9b fd:FileDescriptor[76]
08-22 11:15:15.389  7428  7428 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@36f762aa impl:android.net.LocalSocketImpl@e0fe9b fd:FileDescriptor[76]
,08-22 11:15:15.389  7428  7428 I BtOppRfcommListener: stopping Accept Thread
08-22 11:15:15.389  1016  1214 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:15:15.389  7428  7443 D BluetoothAdapterProperties: onBluetoothDisable()
08-22 11:15:15.389  1016  1214 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-22 11:15:15.389  7428  7428 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3441d238, channel: 12, state: LISTENING
08-22 11:15:15.389  7428  7443 D BluetoothAdapterProperties: mDiscovering is false
08-22 11:15:15.389  7428  7428 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3441d238, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@345dee23, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1d63c211mSocket: android.net.LocalSocket@12c0ff76 impl:android.net.LocalSocketImpl@1546e977 fd:FileDescriptor[80]
08-22 11:15:15.389  7428  7428 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@12c0ff76 impl:android.net.LocalSocketImpl@1546e977 fd:FileDescriptor[80]
08-22 11:15:15.399  7428  7548 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 11:15:15.399  7428  7548 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-22 11:15:15.399  1016  1504 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-22 11:15:15.399  7428  7443 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-22 11:15:15.399  1016  1214 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:15.399  1016  1214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:15.399  1016  1214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:15.399  3060  3060 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 11:15:15.399  1016  1028 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-22 11:15:15.399  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 11:15:15.409  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:15.409  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:15.409  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 11:15:15.409  7428  7446 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 11:15:15.409  7428  7446 D BluetoothAdapterProperties: Scan Mode:20
,08-22 11:15:15.409  3060  3060 D BluetoothPbap: Proxy object disconnected
08-22 11:15:15.409  3060  3060 D PbapServerProfile: Bluetooth service disconnected
,08-22 11:15:15.419  7428  7443 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-22 11:15:15.419  7428  7443 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-22 11:15:15.419  7428  7443 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-22 11:15:15.419  7428  7443 E bt-btif : cmd socket is not created
,08-22 11:15:15.419  7428  7494 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-22 11:15:15.419  7428  7494 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-22 11:15:15.419  7428  7494 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 11:15:15.419  7428  7494 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 11:15:15.419  7428  7494 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 11:15:15.419  7428  7443 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-22 11:15:15.429  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:15.429  3060  3060 D DockEventReceiver: finishStartingService: stopping service
,08-22 11:15:15.429  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:15.429  3060  3060 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 11:15:15.439  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:15.439  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-22 11:15:15.439  7428  7428 V BluetoothOppManager: cleanUp...
,08-22 11:15:15.469  1981  1981 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:15.469  1981  1981 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-22 11:15:15.619  7428  7494 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-22 11:15:15.619  7428  7494 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 11:15:15.619  7428  7494 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 11:15:15.619  7428  7494 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 11:15:15.619  7428  7494 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 11:15:15.619  7428  7494 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 11:15:15.619  7428  7494 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 11:15:15.619  7428  7494 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 11:15:15.619  7428  7494 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 11:15:15.619  7428  7494 W bt-btif : ag scb idx 1 not allocated
08-22 11:15:15.619  7428  7494 W bt-btif : ag scb idx 2 not allocated
08-22 11:15:15.619  7428  7494 E bt-btif : BTA AG is already disabled, ignoring ...
08-22 11:15:15.619  7428  7530 I bt_userial_mct: exiting userial_read_thread
08-22 11:15:15.619  7428  7530 D bt_userial_mct: Leaving userial_evt_read_thread()
08-22 11:15:15.619  7428  7446 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-22 11:15:15.619  7428  7496 I bt_vendor: hw_epilog_process
08-22 11:15:15.619  7428  7446 D bt_userial_mct: userial_close
08-22 11:15:15.619  7428  7446 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-22 11:15:16.019  7428  7446 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-22 11:15:16.019  7428  7446 I bt_vendor: bluetooth satus is on
08-22 11:15:16.019  7428  7446 I bt_vendor: bt-vendor : resetting BT status
08-22 11:15:16.019  7428  7446 I bt_vendor: Starting hciattach daemon
08-22 11:15:16.019  7428  7446 I bt_vendor: try to set false
,08-22 11:15:16.019  7428  7446 I bt_vendor: Starting hciattach daemon
08-22 11:15:16.019  7428  7446 I bt_vendor: try to set false
,08-22 11:15:16.019  7428  7446 I bt_vendor: cleanup
,08-22 11:15:16.019  7428  7494 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-22 11:15:16.019  7428  7446 I GKI_LINUX: GKI_exit_task 0 done
,08-22 11:15:16.019  7428  7446 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-22 11:15:16.019  7428  7443 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-22 11:15:16.019  7428  7443 D BtConfig.SecureMode: isSecureModeOn:false
,08-22 11:15:16.019  7428  7443 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-22 11:15:16.019  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-22 11:15:16.019  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-22 11:15:16.019  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-22 11:15:16.029  1016  1428 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,08-22 11:15:16.029  1016  1428 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-22 11:15:16.029  1016  1428 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:16.029  1016  1428 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:16.029  1016  1428 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:16.029  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-22 11:15:16.029  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 11:15:16.029  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-22 11:15:16.029  1016  1428 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:16.029  7428  7428 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 11:15:16.029  1016  1428 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-22 11:15:16.029  7428  7428 D BtGatt.GattService: Received stop request...Stopping profile...
,08-22 11:15:16.029  7428  7428 D BtGatt.GattService: stop()
08-22 11:15:16.029  7428  7428 D BtGatt.AdvertiseManager: advertise clients cleared
,08-22 11:15:16.029  1016  1428 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:16.029  1016  1428 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:16.029  1016  1428 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:16.029  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-22 11:15:16.029  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-22 11:15:16.029  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-22 11:15:16.029  1016  1514 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:16.039  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 11:15:16.039  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:16.039  1016  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:16.039  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:16.039  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-22 11:15:16.039  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 11:15:16.039  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-22 11:15:16.039  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:16.039  7428  7428 D HeadsetService: Received stop request...Stopping profile...
,08-22 11:15:16.039  1016  1514 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:16.039  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-22 11:15:16.039  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:16.039  1016  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:16.039  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:16.049  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-22 11:15:16.049  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-22 11:15:16.049  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-22 11:15:16.049  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:16.049  1016  3764 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-22 11:15:16.049  1016  3764 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-22 11:15:16.049  1016  3764 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:16.049  1016  3764 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:16.049  1016  3764 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:16.049  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService,
08-22 11:15:16.049  1016  1536 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:16.049  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-22 11:15:16.049  1016  1536 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-22 11:15:16.049  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-22 11:15:16.049  1016  1536 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:16.049  1016  1536 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:16.049  1016  1536 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 11:15:16.059  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-22 11:15:16.059  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-22 11:15:16.059  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:16.059  7428  7443 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-22 11:15:16.059  1016  1262 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:16.059  1016  1262 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-22 11:15:16.059  3060  3060 D HeadsetProfile: Bluetooth service disconnected
08-22 11:15:16.059  7428  7428 D A2dpService: Received stop request...Stopping profile...
,08-22 11:15:16.059  7428  7472 D A2dpStateMachine: Exit Disconnected: -1,
08-22 11:15:16.059  1016  1262 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:16.059  1016  1262 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:16.059  1016  1262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:16.059  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-22 11:15:16.059  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:16.059  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 11:15:16.059  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-22 11:15:16.059  7428  7443 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-22 11:15:16.059  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:16.059  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:16.059  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:16.059  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:16.059  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:16.059  7428  7443 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:16.059  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:16.059  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:16.059  7428  7443 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:16.059  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-22 11:15:16.059  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-22 11:15:16.059  7428  7443 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-22 11:15:16.059  7428  7443 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-22 11:15:16.059  7428  7443 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 11:15:16.059  7428  7443 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-22 11:15:16.059  7428  7443 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-22 11:15:16.069  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:16.069  1016  1016 D BluetoothA2dp: Proxy object disconnected
08-22 11:15:16.069  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-22 11:15:16.069  3060  3060 D BluetoothA2dp: Proxy object disconnected
08-22 11:15:16.069  3060  3060 D A2dpProfile: Bluetooth service disconnected
,08-22 11:15:16.069  7428  7428 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-22 11:15:16.069  7428  7428 D HidService: Received stop request...Stopping profile...
08-22 11:15:16.069  7428  7428 D HidService: Stopping Bluetooth HidService
08-22 11:15:16.069  7428  7428 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-22 11:15:16.069  7428  7428 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-22 11:15:16.069  7428  7428 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-22 11:15:16.069  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:16.069  7428  7428 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-22 11:15:16.069  7428  7428 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-22 11:15:16.069  7428  7428 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-22 11:15:16.069  7428  7428 D HealthService: Received stop request...Stopping profile...
,08-22 11:15:16.069  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:16.079  3060  3060 D BluetoothInputDevice: Proxy object disconnected
,08-22 11:15:16.079  3060  3060 D HidProfile: Bluetooth service disconnected
,08-22 11:15:16.079  7428  7428 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-22 11:15:16.079  7428  7428 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-22 11:15:16.079  7428  7428 D PanService: Received stop request...Stopping profile...
08-22 11:15:16.079  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:16.079  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-22 11:15:16.079  7428  7428 D BluetoothMapService: Received stop request...Stopping profile...
,08-22 11:15:16.079  3060  3060 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-22 11:15:16.079  3060  3060 D PanProfile: Bluetooth service disconnected
,08-22 11:15:16.089  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:16.089  7428  7428 D SapService: Received stop request...Stopping profile...
,08-22 11:15:16.089  7428  7428 D SapService: Stopping Bluetooth SapService
,08-22 11:15:16.089  7428  7428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d6ee319
,08-22 11:15:16.089  7428  7428 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-22 11:15:16.089  7428  7428 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 11:15:16.089  7428  7428 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-22 11:15:16.089  7428  7428 D BluetoothA2dp: Proxy object disconnected
08-22 11:15:16.089  7428  7428 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-22 11:15:16.089  7428  7473 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-22 11:15:16.089  7428  7428 I GKI_LINUX: GKI_exit_task 2 done
08-22 11:15:16.089  7428  7428 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-22 11:15:16.089  7428  7428 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-22 11:15:16.089  7428  7428 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:16.089  7428  7428 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:16.089  7428  7428 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-22 11:15:16.089  7428  7428 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:16.089  7428  7428 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:16.089  7428  7428 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-22 11:15:16.089  7428  7428 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-22 11:15:16.089  7428  7428 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-22 11:15:16.089  7428  7428 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:16.089  7428  7428 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:16.089  7428  7428 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 11:15:16.089  7428  7428 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-22 11:15:16.099  3060  3060 D BluetoothMap: Proxy object disconnected
,08-22 11:15:16.099  3060  3060 D MapProfile: Bluetooth service disconnected
,08-22 11:15:16.099  3060  3060 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-22 11:15:16.099  3060  3060 D SapProfile: Bluetooth service disconnected
,08-22 11:15:16.099  7428  7428 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true,
,08-22 11:15:16.099  7428  7428 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-22 11:15:16.099  7428  7428 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-22 11:15:16.099  7428  7428 E BluetoothAdapterService(762241817): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-22 11:15:16.099  7428  7428 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-22 11:15:16.099  7428  7428 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-22 11:15:16.099  7428  7443 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-22 11:15:16.099  7428  7443 D BluetoothAdapterProperties: Setting state to 10
08-22 11:15:16.099  7428  7443 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-22 11:15:16.099  7428  7443 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 11:15:16.099  7428  7443 D BluetoothAdapterService: updateAdapterState state is 10
08-22 11:15:16.099  1456  1473 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:16.099  1456  1473 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:16.099  7428  7443 D BluetoothAdapterService: Autoconnection is available 
08-22 11:15:16.099  7428  7443 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-22 11:15:16.099  7428  7443 I BluetoothAdapterState: Entering OffState
,08-22 11:15:16.099  7428  7436 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:16.099  7428  7436 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:16.099  3060  7274 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-22 11:15:16.109  3060  3073 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 11:15:16.109  3060  3073 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 11:15:16.109  6774  6784 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:16.109  6774  6784 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:16.109  6774  6784 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-22 11:15:16.109  6774  6784 D BluetoothLeAdvertiser: Exit stop advertising
08-22 11:15:16.109  6774  6784 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-22 11:15:16.109  6774  6784 D BluetoothLeScanner: Exiting stopAllScan
,08-22 11:15:16.109  3060  3070 D BluetoothPbap: onBluetoothStateChange: up=false
,08-22 11:15:16.109  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 11:15:16.109  3060  7274 D BluetoothMap: onBluetoothStateChange: up=false
,08-22 11:15:16.109  1446  1472 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 11:15:16.109  1446  1472 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 11:15:16.109  7428  7537 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 11:15:16.109  3060  3073 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 11:15:16.109  1174  1183 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 11:15:16.109  1174  1183 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:16.119  3060  3070 D Bluetoothsap: onBluetoothStateChange: up=false
,08-22 11:15:16.119  3060  3070 D Bluetoothsap: Unbinding service...
,08-22 11:15:16.119  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 11:15:16.119  1016  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:16.119  1481  1490 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 11:15:16.119  1481  1490 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:16.119  7478  7487 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 11:15:16.119  7478  7487 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:16.119  1981  1990 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-22 11:15:16.119  1981  1990 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 11:15:16.119  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-22 11:15:16.129  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-22 11:15:16.129  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:16.139  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
,08-22 11:15:16.139  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-22 11:15:16.139  7428  7446 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-22 11:15:16.139  1174  1174 D BluetoothAdapter: 358947328: getState() :  mService = null. Returning STATE_OFF
,08-22 11:15:16.139  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 11:15:16.139  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:16.139  1174  1174 D BluetoothTile:  getBluetoothState : 10
,08-22 11:15:16.149  1174  1671 D BluetoothAdapter: 358947328: getState() :  mService = null. Returning STATE_OFF
,08-22 11:15:16.149  1174  1671 D BluetoothAdapter: 358947328: getState() :  mService = null. Returning STATE_OFF
,08-22 11:15:16.149  1174  1174 D BluetoothAdapter: 358947328: getState() :  mService = null. Returning STATE_OFF
08-22 11:15:16.149  1174  1174 D BluetoothAdapter: 358947328: getState() :  mService = null. Returning STATE_OFF
08-22 11:15:16.149  1016  1504 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:16.149  1919  1919 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-22 11:15:16.149  1016  1536 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 11:15:16.149  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-22 11:15:16.149  7428  7428 I GKI_LINUX: GKI_exit_task 1 done
08-22 11:15:16.149  7428  7428 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-22 11:15:16.149  7428  7428 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-22 11:15:16.149  1981  2215 D BluetoothAdapter: 542772662: getState() :  mService = null. Returning STATE_OFF
08-22 11:15:16.149  1981  2215 D BluetoothAdapter: 542772662: getState() :  mService = null. Returning STATE_OFF
,08-22 11:15:16.149  3060  3060 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:16.149  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:16.149  1016  3765 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:15:16.149  1016  3765 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-22 11:15:16.149  1016  3765 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:16.149  1016  3765 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:16.149  1016  3765 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:16.159  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:16.159  7428  7428 I art     : System.exit called, status: 0
08-22 11:15:16.159  7428  7428 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-22 11:15:16.159  3060  3060 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 11:15:16.159  1016  1514 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-22 11:15:16.159  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 11:15:16.159  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:16.159  1016  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:16.159  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 11:15:16.169  3060  3060 D DockEventReceiver: finishStartingService: stopping service
,08-22 11:15:16.169  3060  3060 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 11:15:16.169  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:16.169  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-22 11:15:16.179  1016  1492 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-22 11:15:16.179  1016  1492 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-22 11:15:16.179  1016  1492 W BroadcastQueue: android.os.TransactionTooLargeException
08-22 11:15:16.179  1016  1492 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-22 11:15:16.179  1016  1492 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-22 11:15:16.179  1016  1492 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-22 11:15:16.179  1016  1492 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-22 11:15:16.179  1016  1492 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-22 11:15:16.179  1016  1492 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-22 11:15:16.179  1016  1492 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-22 11:15:16.179  1016  1492 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-22 11:15:16.179  1016  1492 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-22 11:15:16.179  1016  1492 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-22 11:15:16.179  1016  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:16.179  1016  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:16.179  1016  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:16.179  1016  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:16.189  7562  7562 E Zygote  : MountEmulatedStorage(),
08-22 11:15:16.189  7562  7562 E Zygote  : v2
08-22 11:15:16.189  7562  7562 I libpersona: KNOX_SDCARD checking this for 1002
08-22 11:15:16.189  7562  7562 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:16.199  7562  7562 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:16.199  7562  7562 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 11:15:16.199  7562  7562 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 11:15:16.199  1016  1492 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7562 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-22 11:15:16.219  7562  7562 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:16.219  7562  7562 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:16.229  7562  7562 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-22 11:15:16.229  7562  7562 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-22 11:15:16.259  7562  7562 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-22 11:15:16.289  7562  7562 D BtSettings.ProfileConfig: Adding GattService
,08-22 11:15:16.289  7562  7562 D BtSettings.ProfileConfig: Adding HeadsetService
,08-22 11:15:16.289  7562  7562 D BtSettings.ProfileConfig: Adding A2dpService
,08-22 11:15:16.289  7562  7562 D BtSettings.ProfileConfig: Adding HidService
,08-22 11:15:16.289  7562  7562 D BtSettings.ProfileConfig: Adding HealthService
,08-22 11:15:16.299  7562  7562 D BtSettings.ProfileConfig: Adding PanService
,08-22 11:15:16.299  7562  7562 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-22 11:15:16.299  7562  7562 D BtSettings.ProfileConfig: Adding SapService
08-22 11:15:16.299  7562  7562 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-22 11:15:16.299  7562  7562 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-22 11:15:16.299  7562  7562 D BtSettings.ProfileConfig: Adding SapClientService
,08-22 11:15:16.299  7562  7562 D BtSettings.ProfileConfig: Adding HidDevService
,08-22 11:15:16.299  7562  7562 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-22 11:15:16.299  1016  3765 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-22 11:15:16.299  1016  3765 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:16.299  1016  3765 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:16.299  1016  3765 D SettingsProvider: selectionArgs: false
08-22 11:15:16.299  1016  3765 D SettingsProvider: selectionArgs: 1002
08-22 11:15:16.299  1016  3765 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:16.299  1016  3765 D SettingsProvider: ret = -1
,08-22 11:15:16.299  1016  3768 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-22 11:15:16.299  1016  3768 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:16.299  1016  3768 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:16.299  1016  3768 D SettingsProvider: selectionArgs: false
08-22 11:15:16.299  1016  3768 D SettingsProvider: selectionArgs: 1002
08-22 11:15:16.299  1016  3768 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:16.299  1016  3768 D SettingsProvider: ret = -1
,08-22 11:15:16.299  1016  1514 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-22 11:15:16.299  1016  1514 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:16.299  1016  1514 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 11:15:16.299  1016  1514 D SettingsProvider: selectionArgs: false
08-22 11:15:16.299  1016  1514 D SettingsProvider: selectionArgs: 1002
08-22 11:15:16.299  1016  1514 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:16.299  1016  1514 D SettingsProvider: ret = -1
,08-22 11:15:16.309  1016  1492 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-22 11:15:16.309  1016  1492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:16.309  1016  1492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:16.309  1016  1492 D SettingsProvider: selectionArgs: false
08-22 11:15:16.309  1016  1492 D SettingsProvider: selectionArgs: 1002
08-22 11:15:16.309  1016  1492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:16.309  1016  1492 D SettingsProvider: ret = -1
,08-22 11:15:16.309  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-22 11:15:16.309  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-22 11:15:16.309  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:16.309  1016  1028 D SettingsProvider: selectionArgs: false
08-22 11:15:16.309  1016  1028 D SettingsProvider: selectionArgs: 1002
08-22 11:15:16.309  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:16.309  1016  1028 D SettingsProvider: ret = -1
,08-22 11:15:16.309  1016  1428 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-22 11:15:16.309  1016  1428 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-22 11:15:16.309  1016  1428 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:16.309  1016  1428 D SettingsProvider: selectionArgs: false
08-22 11:15:16.309  1016  1428 D SettingsProvider: selectionArgs: 1002
08-22 11:15:16.309  1016  1428 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:16.309  1016  1428 D SettingsProvider: ret = -1
,08-22 11:15:16.309  1016  1262 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-22 11:15:16.309  1016  1262 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:16.309  1016  1262 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:16.309  1016  1262 D SettingsProvider: selectionArgs: false
08-22 11:15:16.309  1016  1262 D SettingsProvider: selectionArgs: 1002
08-22 11:15:16.309  1016  1262 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:16.309  1016  1262 D SettingsProvider: ret = -1
,08-22 11:15:16.309  1016  3764 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-22 11:15:16.309  1016  3764 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:16.309  1016  3764 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:16.309  1016  3764 D SettingsProvider: selectionArgs: false
,08-22 11:15:16.309  1016  3764 D SettingsProvider: selectionArgs: 1002
08-22 11:15:16.309  1016  3764 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:16.309  1016  3764 D SettingsProvider: ret = -1
,08-22 11:15:16.309  1016  1537 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 11:15:16.309  1016  1537 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:16.309  1016  1537 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 11:15:16.309  1016  1537 D SettingsProvider: selectionArgs: false
08-22 11:15:16.309  1016  1537 D SettingsProvider: selectionArgs: 1002
,08-22 11:15:16.309  1016  1537 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:16.309  1016  1537 D SettingsProvider: ret = -1
,08-22 11:15:16.319  1016  1214 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-22 11:15:16.319  1016  1214 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:16.319  1016  1214 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:16.319  1016  1214 D SettingsProvider: selectionArgs: false
08-22 11:15:16.319  1016  1214 D SettingsProvider: selectionArgs: 1002
08-22 11:15:16.319  1016  1214 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:16.319  1016  1214 D SettingsProvider: ret = -1
,08-22 11:15:16.319  1016  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-22 11:15:16.319  1016  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:16.319  1016  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 11:15:16.319  1016  1029 D SettingsProvider: selectionArgs: false
08-22 11:15:16.319  1016  1029 D SettingsProvider: selectionArgs: 1002
08-22 11:15:16.319  1016  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:16.319  1016  1029 D SettingsProvider: ret = -1
,08-22 11:15:16.319  1016  1487 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-22 11:15:16.319  1016  1487 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:16.319  1016  1487 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:16.319  1016  1487 D SettingsProvider: selectionArgs: false
,08-22 11:15:16.319  1016  1487 D SettingsProvider: selectionArgs: 1002
08-22 11:15:16.319  1016  1487 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-22 11:15:16.319  1016  1487 D SettingsProvider: ret = -1
,08-22 11:15:16.329  1981  1981 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:16.329  1016  1504 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:15:16.329  1016  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-22 11:15:16.329  1016  1504 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:16.329  1016  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:16.329  1016  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:16.339  1981  7581 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-22 11:15:16.349  1981  1981 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-22 11:15:16.349  1016  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:16.349  1016  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:16.349  1016  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:16.349  1016  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:16.359  1981  7581 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-22 11:15:16.629   288   288 E SMD     : DCD OFF,
,08-22 11:15:18.339  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 11:15:18.339  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:18.799  1016  1214 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-22 11:15:18.799  1016  1214 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-22 11:15:18.799  1016  1214 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-22 11:15:18.799  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 11:15:18.799  1016  1214 D BatteryService: stay LED for fully charged
,08-22 11:15:18.809  1016  1016 I MotionRecognitionService: Plugged
,08-22 11:15:18.809  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 11:15:18.809  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-22 11:15:18.809  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 11:15:18.809  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-22 11:15:18.809  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-22 11:15:18.839  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-22 11:15:18.839  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-22 11:15:18.839  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-22 11:15:18.839  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-22 11:15:18.839  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-22 11:15:19.169  1016  1048 I PowerManagerService: [PWL] Off : 75s ago
08-22 11:15:19.169  1016  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-22 11:15:19.169  1016  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-22 11:15:19.169  1016  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1016, ws=null) (elapsedTime=15561)
,08-22 11:15:19.639   288   288 E SMD     : DCD OFF
,08-22 11:15:20.539  1016  1322 E Watchdog: !@Sync 4
,08-22 11:15:21.339  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:21.339  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@138d3afa added. We now have 6 listener(s)
08-22 11:15:21.339  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:21.339  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:21.339  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@327678ab added. We now have 7 listener(s)
08-22 11:15:21.339  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:21.339  6774  6827 I System.out: IsBluetoothEnabled
08-22 11:15:21.339  6774  6827 D BluetoothAdapter: disable()
,08-22 11:15:21.339  1016  1428 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-22 11:15:21.349  6774  6827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 11:15:21.349  6774  6827 D BluetoothAdapter: enable()
,08-22 11:15:21.349  1016  3767 W ActivityManager: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-22 11:15:21.349  1016  3767 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-22 11:15:21.349  1016  3767 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-22 11:15:21.349  1016  3767 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 11:15:21.349  1016  3767 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-22 11:15:21.349  1016  3767 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-22 11:15:21.349  1016  3767 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-22 11:15:21.349  1016  3767 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-22 11:15:21.349  1016  3767 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-22 11:15:21.349  1016  3767 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 11:15:21.349  1016  3767 D SettingsProvider: name = bluetooth_on
,08-22 11:15:21.359  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-22 11:15:21.359  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 11:15:21.359  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-22 11:15:21.359  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-22 11:15:21.389  7562  7562 D BluetoothAdapterState: make
,08-22 11:15:21.389  7562  7562 I bluedroid: init
,08-22 11:15:21.399  7562  7587 I BluetoothAdapterState: Entering OffState
,08-22 11:15:21.399  7562  7562 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-22 11:15:21.399  7562  7562 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-22 11:15:21.399  7562  7562 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-22 11:15:21.399  7562  7562 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-22 11:15:21.399  7562  7562 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-22 11:15:21.399  7562  7562 I bluedroid: get_profile_interface socket
08-22 11:15:21.399  7562  7562 I bluedroid: get_profile_interface map_client
08-22 11:15:21.399  7562  7590 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-22 11:15:21.399  7562  7562 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-22 11:15:21.409  7562  7590 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-22 11:15:21.409  7562  7590 E BluetoothServiceJni: populateRssiValuesNative
08-22 11:15:21.409  7562  7590 I bluedroid: getModelRssiValues
,08-22 11:15:21.409  7562  7590 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-22 11:15:21.409  7562  7590 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-22 11:15:21.409  7562  7590 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-22 11:15:21.409  1016  1016 D SettingsProvider: name = bluetooth_name
,08-22 11:15:21.419  7562  7562 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0,
08-22 11:15:21.419  1016  3768 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 11:15:21.419  1016  3768 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 11:15:21.419  1016  3768 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:21.419  1016  3768 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:21.419  1016  3768 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:21.419  7562  7574 I bluedroid: config_hci_snoop_log
,08-22 11:15:21.419  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-22 11:15:21.429  1016  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-22 11:15:21.429  1016  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-22 11:15:21.429  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-22 11:15:21.429  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-22 11:15:21.429  7562  7562 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-22 11:15:21.439  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-22 11:15:21.439  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 11:15:21.439  1016  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-22 11:15:21.449  1016  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-22 11:15:21.449  7562  7587 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-22 11:15:21.449  7562  7587 D BluetoothAdapterProperties: Setting state to 11
08-22 11:15:21.449  7562  7587 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-22 11:15:21.449  7562  7587 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 11:15:21.449  7562  7587 D BluetoothAdapterService: updateAdapterState state is 11
,08-22 11:15:21.459  7562  7587 D BluetoothAdapterService: Autoconnection is available 
08-22 11:15:21.459  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:21.459  7562  7587 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-22 11:15:21.459  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
,08-22 11:15:21.459  7562  7587 D BluetoothSecureManager: getInstant: null
08-22 11:15:21.459  7562  7587 D BluetoothSecureManager: calling getMethod for getService
08-22 11:15:21.459  7562  7587 D BluetoothSecureManager: calling getService
,08-22 11:15:21.459  1919  1919 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 11:15:21.469  7562  7587 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@f086924
,08-22 11:15:21.469  1016  1262 D BluetoothSecureManagerService: isSecureModeEnabled
,08-22 11:15:21.469  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-22 11:15:21.469  1016  1262 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable,
08-22 11:15:21.469  1174  1174 D BluetoothTile:  getBluetoothState : 11,
08-22 11:15:21.469  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:21.469  7562  7587 D BtConfig.SecureMode: isSecureModeOn:false
,08-22 11:15:21.469  1016  1428 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-22 11:15:21.469  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-22 11:15:21.469  7562  7587 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-22 11:15:21.469  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 11:15:21.469  7562  7587 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-22 11:15:21.469  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-22 11:15:21.469  7562  7587 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-22 11:15:21.469  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 11:15:21.469  7562  7587 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-22 11:15:21.469  3060  3060 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:21.469  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-22 11:15:21.469  7562  7587 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-22 11:15:21.469  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-22 11:15:21.469  1016  1537 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:15:21.469  1016  1537 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-22 11:15:21.469  7562  7587 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-22 11:15:21.469  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-22 11:15:21.469  1016  1536 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 11:15:21.479  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-22 11:15:21.479  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:21.479  7562  7587 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-22 11:15:21.479  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 11:15:21.479  1174  1671 D BluetoothTile:  handleUpdatestate:false name:null
08-22 11:15:21.479  1016  1537 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:21.479  1174  1671 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-22 11:15:21.479  1016  1537 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:21.479  1016  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 11:15:21.479  7562  7587 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-22 11:15:21.479  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 11:15:21.479  7562  7587 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 11:15:21.479  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-22 11:15:21.479  7562  7587 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:21.479  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-22 11:15:21.489  7562  7587 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-22 11:15:21.489  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-22 11:15:21.489  7562  7587 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-22 11:15:21.489  7562  7587 D BluetoothBondStateMachine: make
,08-22 11:15:21.489  3060  3060 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 11:15:21.489  7562  7587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-22 11:15:21.489  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-22 11:15:21.489  7562  7587 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-22 11:15:21.489  7562  7592 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-22 11:15:21.499  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:21.499  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-22 11:15:21.499  1016  3764 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:21.499  1016  3764 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-22 11:15:21.499  1016  3764 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:21.499  1016  3764 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:21.499  1016  3764 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:21.509  7562  7562 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 11:15:21.509  7562  7562 D BtGatt.GattService: Received start request. Starting profile...
,08-22 11:15:21.509  7562  7562 D BtGatt.GattService: start()
08-22 11:15:21.509  7562  7562 D BtGatt.GattService: start()
,08-22 11:15:21.509  7562  7562 I bluedroid: get_profile_interface gatt
,08-22 11:15:21.509  7562  7562 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12c645bf
,08-22 11:15:21.509  7562  7562 D BtGatt.AdvertiseManager: advertise manager created
,08-22 11:15:21.509  7562  7587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-22 11:15:21.509  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 11:15:21.509  7562  7587 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-22 11:15:21.519  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:21.519  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-22 11:15:21.519  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:21.519  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:21.519  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:21.529  7562  7562 D BtGatt.GattService: mStartError = false
08-22 11:15:21.529  7562  7562 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12c645bf
,08-22 11:15:21.529  7562  7587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-22 11:15:21.529  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-22 11:15:21.529  7562  7587 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-22 11:15:21.529  7562  7562 D HeadsetService: Received start request. Starting profile...
08-22 11:15:21.529  7562  7562 D HeadsetService: start()
,08-22 11:15:21.529  7562  7562 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-22 11:15:21.529  7562  7562 D HeadsetStateMachine: make
,08-22 11:15:21.529  1016  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:21.539  1016  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 11:15:21.539  7562  7562 E HeadsetStateMachine: # of Max HF connection is 2
,08-22 11:15:21.539  1016  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:21.539  1016  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:21.539  1016  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:21.539  7562  7587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-22 11:15:21.539  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 11:15:21.539  7562  7587 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-22 11:15:21.549  1016  1428 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:21.549  1016  1428 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-22 11:15:21.549  1016  1428 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:21.549  1016  1428 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:21.549  1016  1428 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:21.549  1016  1028 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-22 11:15:21.549  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-22 11:15:21.549  7562  7587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-22 11:15:21.549  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:21.549  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:21.549  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-22 11:15:21.549  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-22 11:15:21.549  7562  7587 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-22 11:15:21.549  1016  3764 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:21.549  1016  3764 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-22 11:15:21.559  1016  3764 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:21.559  1016  3764 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:21.559  1016  3764 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:21.559  7562  7587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-22 11:15:21.559  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-22 11:15:21.559  1016  1029 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-22 11:15:21.559  7562  7587 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-22 11:15:21.559  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-22 11:15:21.559  1016  1029 W ActivityManager: userId = 0, bbcId = -10000,
08-22 11:15:21.559  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:21.559  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-22 11:15:21.559  7562  7562 I bluedroid: get_profile_interface handsfree
,08-22 11:15:21.569  7562  7562 I DualScoManager: Instantiating Dual Sco Manager
,08-22 11:15:21.569  7562  7562 I DualScoManager: Set HeadsetServiceHelper
,08-22 11:15:21.579  1016  1262 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:21.579  1016  1262 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 11:15:21.579  7562  7562 D BluetoothAtMessage: createCMTIContentObservers
,08-22 11:15:21.579  1016  1262 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:21.579  1016  1262 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:21.579  1016  1262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:21.579  1016  1537 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-22 11:15:21.579  1016  1537 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-22 11:15:21.579  1016  1537 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:21.579  1016  1537 D SettingsProvider: selectionArgs: false
08-22 11:15:21.579  1016  1537 D SettingsProvider: selectionArgs: 1002
08-22 11:15:21.579  1016  1537 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 11:15:21.579  1016  1537 D SettingsProvider: ret = -1
,08-22 11:15:21.579  7562  7595 D HeadsetStateMachine: Enter Disconnected: -2
,08-22 11:15:21.579  7562  7562 D HeadsetService: mStartError = false
08-22 11:15:21.579  7562  7587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-22 11:15:21.579  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 11:15:21.579  7562  7562 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12c645bf
08-22 11:15:21.579  7562  7587 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-22 11:15:21.579  1016  1428 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:21.579  1016  1428 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-22 11:15:21.579  7562  7595 D HeadsetStateMachine: Clear mHeadsetBrsf
08-22 11:15:21.579  7562  7595 D HeadsetStateMachine: map size, before remove : 0
08-22 11:15:21.579  1016  1428 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:21.579  1016  1428 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:21.579  1016  1428 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:21.579  7562  7595 D HeadsetStateMachine: map size, after remove: 0
,08-22 11:15:21.589  7562  7587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-22 11:15:21.589  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 11:15:21.589  7562  7587 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-22 11:15:21.589  1016  3768 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:21.589  1016  3768 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-22 11:15:21.589  1016  3768 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:21.589  1016  3768 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:21.589  1016  3768 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:21.589  7562  7587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 11:15:21.589  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 11:15:21.589  7562  7587 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-22 11:15:21.589  7562  7587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-22 11:15:21.589  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-22 11:15:21.589  7562  7587 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-22 11:15:21.589  7562  7587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-22 11:15:21.589  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-22 11:15:21.589  7562  7587 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-22 11:15:21.589  7562  7587 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-22 11:15:21.589  7562  7587 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-22 11:15:21.589  7562  7587 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-22 11:15:21.589  7562  7562 E BluetoothAdapterService(314983871): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-22 11:15:21.589  7562  7587 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-22 11:15:21.599  7562  7562 D A2dpService: Received start request. Starting profile...
,08-22 11:15:21.599  7562  7562 D A2dpService: start()
,08-22 11:15:21.599  7562  7562 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-22 11:15:21.599  7562  7562 I bluedroid: get_profile_interface avrcp
,08-22 11:15:21.599  7562  7562 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-22 11:15:21.609  7562  7562 D Avrcp   : Initialize Media Controller
,08-22 11:15:21.609  7562  7562 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-22 11:15:21.609  7562  7562 E Avrcp   : getActiveSessions
,08-22 11:15:21.609  7562  7562 D Avrcp   : pick active media Controller
08-22 11:15:21.609  7562  7562 D Avrcp   : Get the active Media Controller 
,08-22 11:15:21.619  7562  7562 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-22 11:15:21.619  7562  7599 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-22 11:15:21.619  7562  7562 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-22 11:15:21.619  7562  7562 D A2dpStateMachine: make
,08-22 11:15:21.629  7562  7562 I bluedroid: get_profile_interface a2dp
,08-22 11:15:21.629  7562  7601 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-22 11:15:21.629  7562  7562 E bt-btif : warning : media task started media_task_refcnt 1 
,08-22 11:15:21.629  7562  7562 D A2dpService: mStartError = false
08-22 11:15:21.629  7562  7562 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12c645bf
,08-22 11:15:21.629  7562  7600 D A2dpStateMachine: Enter Disconnected: -2
08-22 11:15:21.629  7562  7562 I BluetoothHidServiceJni: classInitNative: succeeds
,08-22 11:15:21.629  7562  7562 D HidService: Received start request. Starting profile...
08-22 11:15:21.629  7562  7562 D HidService: start()
08-22 11:15:21.629  7562  7562 I bluedroid: get_profile_interface hidhost
08-22 11:15:21.629  7562  7562 D HidService: setHidService(): set to: null
08-22 11:15:21.629  7562  7562 D HidService: mStartError = false
08-22 11:15:21.629  7562  7562 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12c645bf
,08-22 11:15:21.629  7562  7562 D HeadsetStateMachine: Try to query the phonestate on bind
,08-22 11:15:21.629  1446  6914 I Telecom : BluetoothPhoneService: queryPhoneState
08-22 11:15:21.629  1446  1446 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-22 11:15:21.629  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-22 11:15:21.639  1446  6914 I Telecom : BluetoothPhoneService: Result of Message : true
,08-22 11:15:21.639  7562  7562 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-22 11:15:21.639  7562  7562 D HealthService: Received start request. Starting profile...
08-22 11:15:21.639  7562  7562 D HealthService: start()
,08-22 11:15:21.639  1981  1981 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:21.639  7562  7562 I bluedroid: get_profile_interface health
,08-22 11:15:21.639  7562  7562 D HealthService: mStartError = false
08-22 11:15:21.639  7562  7562 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12c645bf
08-22 11:15:21.639  7562  7562 D HeadsetStateMachine: Proxy object connected
08-22 11:15:21.639  7562  7562 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-22 11:15:21.639  7562  7562 D HeadsetPhoneState: sendDeviceDataStateChanged
08-22 11:15:21.639  7562  7562 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-22 11:15:21.639  7562  7562 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-22 11:15:21.639  7562  7595 D HeadsetStateMachine: Disconnected process message: 11
08-22 11:15:21.639  7562  7599 D BluetoothMediaBrowser: no now playing list
,08-22 11:15:21.639  7562  7562 E BluetoothAdapterService(314983871): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-22 11:15:21.639  7562  7595 D HeadsetStateMachine: Disconnected process message: 18
08-22 11:15:21.639  7562  7599 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-22 11:15:21.649  7562  7562 D PanService: Received start request. Starting profile...
08-22 11:15:21.649  7562  7562 D PanService: start()
08-22 11:15:21.649   331   331 I ServiceManager: Waiting for service AtCmdFwd...
08-22 11:15:21.649  7562  7562 D BluetoothPanServiceJni: initializeNative(L110): pan
08-22 11:15:21.649  7562  7562 I bluedroid: get_profile_interface pan
,08-22 11:15:21.649  7562  7562 D PanService: mStartError = false
08-22 11:15:21.649  7562  7562 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12c645bf
,08-22 11:15:21.649  7562  7562 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-22 11:15:21.649  7562  7595 D HeadsetStateMachine: Disconnected process message: 10
,08-22 11:15:21.649  7562  7595 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-22 11:15:21.649  7562  7595 D HeadsetStateMachine: Disconnected process message: 11
,08-22 11:15:21.649  7562  7562 D BluetoothMapService: Received start request. Starting profile...
08-22 11:15:21.649  7562  7562 D BluetoothMapService: start()
,08-22 11:15:21.649  7562  7562 D BluetoothMapService: mStartError = false
08-22 11:15:21.649  7562  7562 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12c645bf
,08-22 11:15:21.649  7562  7562 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-22 11:15:21.649  1981  1981 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-22 11:15:21.649  7562  7562 D SapService: Received start request. Starting profile...
08-22 11:15:21.649  7562  7562 D SapService: start()
08-22 11:15:21.649  7562  7562 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-22 11:15:21.649  7562  7562 I bluedroid: get_profile_interface sap
08-22 11:15:21.649  7562  7562 D SapService: mStartError = false
08-22 11:15:21.649  7562  7562 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12c645bf
08-22 11:15:21.649  7562  7562 D BluetoothA2dp: Proxy object connected
08-22 11:15:21.649  7562  7562 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-22 11:15:21.649  7562  7562 E BluetoothAdapterService(314983871): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-22 11:15:21.649  7562  7562 E BluetoothAdapterService(314983871): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-22 11:15:21.649  7562  7562 E BluetoothAdapterService(314983871): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-22 11:15:21.659  7562  7562 E BluetoothAdapterService(314983871): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-22 11:15:21.679  7562  7562 E BluetoothAdapterService(314983871): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-22 11:15:21.679  7562  7562 E BluetoothAdapterService(314983871): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-22 11:15:21.679  7562  7587 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-22 11:15:21.679  7562  7587 I bluedroid: enable
,08-22 11:15:21.679  7562  7587 I bt_hci_bdroid: init
,08-22 11:15:21.679  7562  7587 I bt_vendor: bt-vendor : init
08-22 11:15:21.679  7562  7587 I bt_vendor: bt-vendor : get_bt_soc_type
08-22 11:15:21.679  7562  7587 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-22 11:15:21.679  7562  7587 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-22 11:15:21.679  7562  7587 D bt_userial_mct: userial_init
08-22 11:15:21.679  7562  7605 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-22 11:15:21.679  7562  7587 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-22 11:15:21.679  7562  7587 I bt_vendor: Starting hciattach daemon
08-22 11:15:21.679  7562  7587 I bt_vendor: try to set false
,08-22 11:15:21.689  7562  7587 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-22 11:15:21.689  7562  7587 I bt_vendor: Starting hciattach daemon
08-22 11:15:21.689  7562  7587 I bt_vendor: try to set true
,08-22 11:15:21.699  7609  7609 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-22 11:15:21.739  7615  7615 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-22 11:15:21.749  7616  7616 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-22 11:15:21.769  7618  7618 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-22 11:15:21.779  7619  7619 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-22 11:15:21.779  7620  7620 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-22 11:15:21.789  7621  7621 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-22 11:15:21.979  7624  7624 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-22 11:15:21.989  7625  7625 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-22 11:15:22.049  7562  7587 I bt_vendor: bluetooth satus is on,
,08-22 11:15:22.049  7562  7607 D bt_userial_mct: userial_open(port:0),
08-22 11:15:22.049  7562  7607 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-22 11:15:22.049  7562  7607 I bt_vendor: Done intiailizing UART,
08-22 11:15:22.049  7562  7607 I bt_vendor: Done intiailizing UART
08-22 11:15:22.049  7562  7607 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-22 11:15:22.049  7562  7607 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
08-22 11:15:22.049  7562  7627 D bt_userial_mct: Entering userial_read_thread()
08-22 11:15:22.059  7562  7605 I         : BTE_InitTraceLevels -- TRC_HCI
08-22 11:15:22.059  7562  7605 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-22 11:15:22.059  7562  7605 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-22 11:15:22.059  7562  7605 I         : BTE_InitTraceLevels -- TRC_AVDT
08-22 11:15:22.059  7562  7605 I         : BTE_InitTraceLevels -- TRC_AVRC
08-22 11:15:22.059  7562  7605 I         : BTE_InitTraceLevels -- TRC_A2D
08-22 11:15:22.059  7562  7605 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-22 11:15:22.059  7562  7605 I         : BTE_InitTraceLevels -- TRC_BTM
08-22 11:15:22.059  7562  7605 I         : BTE_InitTraceLevels -- TRC_GAP
08-22 11:15:22.059  7562  7605 I         : BTE_InitTraceLevels -- TRC_PAN
08-22 11:15:22.059  7562  7605 I         : BTE_InitTraceLevels -- TRC_SAP
08-22 11:15:22.059  7562  7605 I         : BTE_InitTraceLevels -- TRC_SDP
,08-22 11:15:22.059  7562  7605 I         : BTE_InitTraceLevels -- TRC_GATT
08-22 11:15:22.059  7562  7605 I         : BTE_InitTraceLevels -- TRC_SMP
08-22 11:15:22.059  7562  7605 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-22 11:15:22.059  7562  7605 I         : BTE_InitTraceLevels -- TRC_BTIF
08-22 11:15:22.059  7562  7605 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-22 11:15:22.149  7562  7605 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-22 11:15:22.159  7562  7605 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4212ed1 
,08-22 11:15:22.159  7562  7605 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4212ed1 
,08-22 11:15:22.169  7562  7590 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-22 11:15:22.169  7562  7590 E bt-btif : Calling BTA_HhEnable
,08-22 11:15:22.179  7562  7590 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-22 11:15:22.179  7562  7590 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-22 11:15:22.179  7562  7590 E BluetoothServiceJni: populateRssiValuesNative
08-22 11:15:22.179  7562  7590 I bluedroid: getModelRssiValues
,08-22 11:15:22.179  7562  7590 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-22 11:15:22.179  7562  7590 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-22 11:15:22.179  1016  1016 D SettingsProvider: name = bluetooth_name
,08-22 11:15:22.179  7562  7590 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-22 11:15:22.189  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:22.189  7562  7590 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-22 11:15:22.189  7562  7590 D BluetoothAdapterProperties: Scan Mode:20
,08-22 11:15:22.189  7562  7590 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 11:15:22.189  7562  7590 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-22 11:15:22.189  7562  7590 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-22 11:15:22.189  7562  7590 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-22 11:15:22.189  7562  7590 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-22 11:15:22.199  7562  7590 E bt-btif : btif_sock_init: !vhci_init
,08-22 11:15:22.199  7562  7590 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-22 11:15:22.199  7562  7590 D IOP_DB_BT: db_open: db_open : handle 3027984400l, read 13894 bytes onto local cache
,08-22 11:15:22.199  7562  7590 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-22 11:15:22.199  7562  7590 D IOP_DB_BT: db_query: result 1
,08-22 11:15:22.199  7562  7627 E bt_mct  : hci lib postload completed
,08-22 11:15:22.199  7562  7590 I         : iop_db_open: iop_db_open status 0
,08-22 11:15:22.199  7562  7590 D bte_conf: Device ID record 1 : primary,
08-22 11:15:22.199  7562  7590 D bte_conf:   vendorId            = 0075
08-22 11:15:22.199  7562  7590 D bte_conf:   vendorIdSource      = 0001
08-22 11:15:22.199  7562  7590 D bte_conf:   product             = 0100
,08-22 11:15:22.199  7562  7590 D bte_conf:   version             = 0200
,08-22 11:15:22.199  7562  7590 D bte_conf:   clientExecutableURL = 
08-22 11:15:22.199  7562  7590 D bte_conf:   serviceDescription  = 
08-22 11:15:22.199  7562  7590 D bte_conf:   documentationURL    = 
08-22 11:15:22.199  7562  7590 D bte_conf: bte_load_did_conf no section named DID2.
08-22 11:15:22.199  7562  7590 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-22 11:15:22.199  7562  7587 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-22 11:15:22.199  7562  7587 D BluetoothAdapterProperties: ScanMode =  20
08-22 11:15:22.199  7562  7587 D BluetoothAdapterProperties: State =  11
,08-22 11:15:22.209  1016  1514 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-22 11:15:22.209  7562  7587 D BluetoothAdapterProperties: Setting state to 12,
08-22 11:15:22.209  7562  7587 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-22 11:15:22.209  7562  7590 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 11:15:22.209  7562  7590 D BluetoothAdapterProperties: Scan Mode:21
08-22 11:15:22.209  7562  7590 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 11:15:22.209  1016  3768 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-22 11:15:22.209  1016  3768 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-22 11:15:22.209  1016  3768 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 11:15:22.209  1016  3768 D SettingsProvider: selectionArgs: false
08-22 11:15:22.209  1016  3768 D SettingsProvider: selectionArgs: 1002
,08-22 11:15:22.209  1016  3768 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-22 11:15:22.219  1016  3768 D SettingsProvider: ret = -1
,08-22 11:15:22.219  7562  7587 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 11:15:22.219  7562  7587 D BluetoothAdapterService: updateAdapterState state is 12
,08-22 11:15:22.219  1016  1262 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:22.219  1016  1262 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.219  1016  1262 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.219  1016  1262 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:22.219  1016  1262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.229  7562  7587 D BluetoothAdapterService: Autoconnection is available 
08-22 11:15:22.229  7562  7587 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-22 11:15:22.229  7562  7587 D BluetoothAdapterService: starting service from this receiver
,08-22 11:15:22.229  1456  1473 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:22.229  1456  1473 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:22.229  1016  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 11:15:22.229  1016  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.229  3060  3073 D BluetoothPan: Binding service...
,08-22 11:15:22.239  1016  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.239  1016  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:22.239  1016  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.239  7562  7587 I BluetoothAdapterState: Entering On State from state = 11
,08-22 11:15:22.239  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:22.239  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:22.239  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:22.239  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:22.239  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:22.239  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:22.239  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:22.239  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:22.249  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-22 11:15:22.249  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.249  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:22.249  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.249  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:22.249  7562  7562 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-22 11:15:22.249  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.259  3060  7274 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-22 11:15:22.259  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-22 11:15:22.259  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.259  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.259  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:22.259  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.259  3060  3070 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 11:15:22.269  3060  3070 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 11:15:22.269  7562  7574 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 11:15:22.269  6774  6786 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:22.269  6774  6786 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:22.269  7562  7572 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 11:15:22.269  7562  7572 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:22.269  1016  1045 D BluetoothPan: Binding service...
08-22 11:15:22.269  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-22 11:15:22.269  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.269  3060  3073 D BluetoothPbap: onBluetoothStateChange: up=true
,08-22 11:15:22.269  7562  7562 I BluetoothPbapService: Handler(): got msg=1
,08-22 11:15:22.269  1016  3764 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-22 11:15:22.269  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-22 11:15:22.269  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.269  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:22.269  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:22.269  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.269  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 11:15:22.269  1016  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-22 11:15:22.279  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 11:15:22.279  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.279  1016  1016 D BluetoothA2dp: Proxy object connected
,08-22 11:15:22.279  1446  1459 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:22.279  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:22.279  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 11:15:22.279  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:22.279  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-22 11:15:22.279  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.279  3060  3060 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 11:15:22.279  3060  3060 D PanProfile: Bluetooth service connected
,08-22 11:15:22.279  1446  1459 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:22.279  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 11:15:22.279  3060  7274 D BluetoothMap: onBluetoothStateChange: up=true
08-22 11:15:22.289  7562  7632 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-22 11:15:22.289  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-22 11:15:22.289  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.289  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:22.289  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:22.289  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.289  1446  6914 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:22.289  3060  3060 D BluetoothInputDevice: Proxy object connected
08-22 11:15:22.289  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 11:15:22.289  3060  3060 D HidProfile: Bluetooth service connected
08-22 11:15:22.289  7562  7632 D BluetoothSocket: bindListen(): myUserId = 0
08-22 11:15:22.289  7562  7632 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 11:15:22.289  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:22.289  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.289  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:22.289  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.299  1446  6914 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:22.299  7562  7632 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-22 11:15:22.299  7562  7632 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 11:15:22.299  7562  7632 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 11:15:22.299  7562  7632 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e72eea1
,08-22 11:15:22.299  7562  7632 D BluetoothSocket: channel: 19
,08-22 11:15:22.299  7562  7632 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-22 11:15:22.299  1446  1472 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:22.299  1446  1472 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 11:15:22.299  3060  3073 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 11:15:22.299  3060  3060 D BluetoothPbap: Proxy object connected
,08-22 11:15:22.299  3060  3060 D PbapServerProfile: Bluetooth service connected
,08-22 11:15:22.299  3060  3073 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:22.299  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-22 11:15:22.299  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.299  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.299  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:22.299  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-22 11:15:22.299  3060  3060 D BluetoothMap: Proxy object connected
,08-22 11:15:22.299  3060  3060 D MapProfile: Bluetooth service connected
08-22 11:15:22.299  3060  3060 D BluetoothMap: getConnectedDevices()
,08-22 11:15:22.309  1016  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:22.309  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 11:15:22.309  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-22 11:15:22.309  1016  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:22.309  1174  5171 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 11:15:22.309  1174  5171 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:22.309  3060  3060 D BluetoothA2dp: Proxy object connected
08-22 11:15:22.309  3060  3070 D Bluetoothsap: onBluetoothStateChange: up=true
08-22 11:15:22.309  3060  3070 D Bluetoothsap: Binding service...
,08-22 11:15:22.309  3060  3060 D A2dpProfile: Bluetooth service connected
,08-22 11:15:22.309  3060  3070 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-22 11:15:22.369  6774  6827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:22.369  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:22.369  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:22.369  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 11:15:22.369  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:22.369  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:22.369  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:22.369  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:22.369  6774  6827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:22.369  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 11:15:22.369  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1477ab08 added. We now have 8 listener(s)
08-22 11:15:22.369  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:22.369  1016  3764 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-22 11:15:22.369  1016  3764 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-22 11:15:22.369  1016  3764 D SecContentProvider2: mCursor = null
,08-22 11:15:22.369  1016  3764 D WifiService: setWifiEnabled: false pid=6774, uid=10171
,08-22 11:15:22.379  1016  3764 D SettingsProvider: name = wifi_on
,08-22 11:15:22.379  6774  6827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:22.379  1016  3768 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-22 11:15:22.379  1016  3768 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-22 11:15:22.379  1016  3768 D SecContentProvider2: mCursor = null
,08-22 11:15:22.379  1016  3768 D WifiService: setWifiEnabled: true pid=6774, uid=10171
,08-22 11:15:22.379  1016  3768 W ActivityManager: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-22 11:15:22.379  1016  3768 W WifiService: Failed getting userId using ActivityManagerNative
08-22 11:15:22.379  1016  3768 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6774, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-22 11:15:22.379  1016  3768 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 11:15:22.379  1016  3768 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-22 11:15:22.379  1016  3768 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-22 11:15:22.379  1016  3768 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-22 11:15:22.379  1016  3768 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-22 11:15:22.379  1016  3768 D SettingsProvider: name = wifi_on
,08-22 11:15:22.389  1016  1126 E WifiHW  : ##################### set firmware type 0 #####################
,08-22 11:15:22.459  1016  1045 I art     : Explicit concurrent mark sweep GC freed 20251(1174KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.590ms total 150.206ms
08-22 11:15:22.459  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-22 11:15:22.459  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.459  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:22.459  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:22.459  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.469  3060  3070 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-22 11:15:22.469  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:22.469  1016  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:22.469  3060  3060 D Bluetoothsap: BluetoothSAP Proxy object connected
08-22 11:15:22.469  3060  3060 D SapProfile: Bluetooth service connected
08-22 11:15:22.469  3060  3060 D Bluetoothsap: getConnectedDevices()
,08-22 11:15:22.469  1481  1734 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 11:15:22.469  1481  1734 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:22.469  7478  7493 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 11:15:22.469  7478  7493 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:22.469  1981  3795 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 11:15:22.469  1981  3795 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 11:15:22.469  1446  1459 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:22.469  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 11:15:22.469  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:22.469  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:22.469  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:22.469  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.469  1446  1459 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:22.479  3060  3073 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:22.479  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 11:15:22.479  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:22.479  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.479  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:22.479  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.479  3060  3060 D HeadsetProfile: Bluetooth service connected
,08-22 11:15:22.479  3060  3073 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:22.479  1481  1679 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 11:15:22.479  1016  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 11:15:22.479  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 11:15:22.479  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:22.479  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:22.479  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.479  1481  1679 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 11:15:22.479  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-22 11:15:22.479  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-22 11:15:22.489  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:22.489  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
,08-22 11:15:22.489  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-22 11:15:22.489  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-22 11:15:22.499  1446  1446 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@10174984, true
,08-22 11:15:22.499  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 11:15:22.499  1174  1671 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:22.499  1446  1446 D BluetoothHeadset: registerMessageListener
,08-22 11:15:22.509  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:22.509  1174  1174 D BluetoothTile:  getBluetoothState : 12
,08-22 11:15:22.509  1919  1919 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 11:15:22.509  3060  3060 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 11:15:22.509  1016  3764 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:22.509  1016  1428 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-22 11:15:22.509  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 11:15:22.509  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:22.509  1174  1671 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:22.509  7562  7631 D HeadsetService: registerMessageListener
,08-22 11:15:22.519  7562  7631 D HeadsetService: registerMessageListener
,08-22 11:15:22.519  1016  1487 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 11:15:22.519  7562  7595 D HeadsetStateMachine: Disconnected process message: 70
08-22 11:15:22.519  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-22 11:15:22.519  7562  7595 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2d2ad8c6
08-22 11:15:22.519  1446  1446 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-22 11:15:22.519  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-22 11:15:22.519  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.519  1016  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:22.519  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:22.519  1174  1671 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 11:15:22.519  1446  1446 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-22 11:15:22.519  1446  1446 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-22 11:15:22.519  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-22 11:15:22.519  7562  7595 D HeadsetStateMachine: Disconnected process message: 9
,08-22 11:15:22.519  3060  3060 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-22 11:15:22.519  3060  3060 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-22 11:15:22.519  7562  7595 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-22 11:15:22.519  3060  3060 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-22 11:15:22.519  3060  3060 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-22 11:15:22.529  7562  7637 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-22 11:15:22.529   283   672 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-22 11:15:22.529   283   672 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-22 11:15:22.529   283   672 V voice   : voice_set_parameters: exit with code(-2)
08-22 11:15:22.529   283   672 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-22 11:15:22.529   283   672 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-22 11:15:22.529   283   672 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-22 11:15:22.529   283   672 V audio_hw_primary: adev_set_parameters: exit
08-22 11:15:22.529  7562  7595 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-22 11:15:22.539  7562  7637 D BluetoothSocket: bindListen(): myUserId = 0
08-22 11:15:22.539  7562  7637 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 11:15:22.539  3060  3060 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-22 11:15:22.539  1016  1537 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-22 11:15:22.539  1016  1537 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.539  1016  1537 W ActivityManager: userId = 0, bbcId = -10000,
08-22 11:15:22.539  1016  1537 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:22.539  7562  7637 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-22 11:15:22.539  7562  7637 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 11:15:22.539  1016  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 11:15:22.539  7562  7637 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 11:15:22.539  7562  7637 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@386ed087
08-22 11:15:22.539  7562  7637 D BluetoothSocket: channel: 5
,08-22 11:15:22.549  3060  3060 D DockEventReceiver: finishStartingService: stopping service
,08-22 11:15:22.549  3060  3060 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 11:15:22.559  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 11:15:22.559  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-22 11:15:22.559  7562  7562 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12c645bf
,08-22 11:15:22.559  7562  7562 D BtConfig.SecureMode: isSecureModeOn:false
,08-22 11:15:22.569  1016  1536 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 11:15:22.569  1016  1536 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.569  1016  1536 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.569  1016  1536 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:22.569  1016  1536 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 11:15:22.589  1981  1981 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-22 11:15:22.589  1016  1262 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 11:15:22.589  1016  1262 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-22 11:15:22.589  1016  1262 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:22.589  1016  1262 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:22.589  1016  1262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:22.599  1016  1536 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-22 11:15:22.599  1981  7650 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-22 11:15:22.599  1981  1981 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-22 11:15:22.609  1016  1514 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:22.609  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.609  1016  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:22.609  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:22.619  1016  1262 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 11:15:22.619  1016  1262 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.619  1016  1262 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:22.619  1016  1262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:22.629  7562  7653 D BluetoothSocket: bindListen(): myUserId = 0
08-22 11:15:22.629  7562  7653 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 11:15:22.629  7562  7653 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-22 11:15:22.629  7562  7653 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 11:15:22.629  7562  7653 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 11:15:22.629  7562  7653 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@345dee23
,08-22 11:15:22.629  7562  7653 D BluetoothSocket: channel: 12
08-22 11:15:22.629  7562  7653 I BtOppRfcommListener: Accept thread started.
,08-22 11:15:22.629  1981  7650 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-22 11:15:22.629   288   288 E SMD     : DCD OFF
,08-22 11:15:22.649   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 11:15:22.729  1016  1043 D Tethering: interfaceAdded wlan0
,08-22 11:15:22.739  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 11:15:22.739  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-22 11:15:22.739  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:22.749  1016  1130 E Tethering: No numeric data,
,08-22 11:15:22.759  1016  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-22 11:15:22.759  1016  1130 D Tethering: clearTetheredNotification()
08-22 11:15:22.759  1016  1130 D Tethering: InitialState.processMessage what=4
,08-22 11:15:22.759  1016  1043 D Tethering: interfaceAdded p2p0
,08-22 11:15:22.759  1016  1130 E Tethering: No numeric data,
08-22 11:15:22.769  1016  1043 D Tethering: p2p0 is not a tetherable iface, ignoring,
,08-22 11:15:22.769   278  1015 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-22 11:15:22.769  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-22 11:15:22.769   278  1015 D SoftapController: Softap fwReload - Ok
08-22 11:15:22.769  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:22.769  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-22 11:15:22.769  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
08-22 11:15:22.769  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:22.769  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-22 11:15:22.769  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:22.779  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 11:15:22.779  1174  1174 D HotspotTile: updateTetherState():false, false
,08-22 11:15:22.779  1016  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 11:15:22.779  1016  1130 D Tethering: clearTetheredNotification()
08-22 11:15:22.779   278  1015 D CommandListener: Setting iface cfg
08-22 11:15:22.779   278  1015 D CommandListener: Trying to bring down wlan0
,08-22 11:15:22.779  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 11:15:22.779  1174  1174 D HotspotTile: updateTetherState():false, false
08-22 11:15:22.779  1016  1123 V NetworkStats: performPollLocked() took 13ms
,08-22 11:15:22.779  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:22.779   278  1015 D CommandListener: Clearing all IP addresses on wlan0
,08-22 11:15:22.789  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:22.789  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:22.789  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-22 11:15:22.789  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:22.789  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:22.789  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:22.789  1016  1126 E WifiHW  : supplicant_name : p2p_supplicant
,08-22 11:15:22.789  1016  1123 V NetworkStats: performPollLocked() took 7ms
08-22 11:15:22.789  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:22.799  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:22.799  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:22.839  7655  7655 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-22 11:15:22.839  7655  7655 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-22 11:15:22.839  7655  7655 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-22 11:15:22.849  7655  7655 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-22 11:15:22.849   382   382 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7655
08-22 11:15:22.849   382   382 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-22 11:15:22.849  7655  7655 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-22 11:15:22.849  7655  7655 I wpa_supplicant: ssSupport state is = 1
08-22 11:15:22.849  7655  7655 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
08-22 11:15:22.849  7655  7655 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-22 11:15:22.849   382   382 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7655
08-22 11:15:22.849   382   382 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-22 11:15:22.889  1016  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-22 11:15:22.899  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-22 11:15:22.899  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:22.899  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 11:15:22.899  1174  1671 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 11:15:22.899  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:22.899  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:22.899  1174  1174 D HotspotTile: onReceive : 2, 0
,08-22 11:15:22.899  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:22.899  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:22.899  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:22.899  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-22 11:15:22.899  3060  3060 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:22.899  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:22.909  1016  1514 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 11:15:22.909  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:22.909  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:22.909  1016  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:22.909  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:22.909  6545  6545 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-22 11:15:22.909  6545  6545 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 11:15:22.909  6545  6545 D SecurityLogAgent: StateMachine : Current State = 1
08-22 11:15:22.909  6545  6545 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 11:15:22.909  1620  1620 I Hs20UtilService: Starting #19
08-22 11:15:22.909  1620  1640 I Hs20UtilService: Message received 5011
,08-22 11:15:22.999   382   382 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-22 11:15:23.009  7655  7655 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-22 11:15:23.049  7655  7655 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-22 11:15:23.049  7655  7655 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-22 11:15:23.059  7655  7655 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-22 11:15:23.059   382   382 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7655,
08-22 11:15:23.059   382   382 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-22 11:15:23.059  7655  7655 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-22 11:15:23.059  7655  7655 I wpa_supplicant: ssSupport state is = 1
08-22 11:15:23.059  7655  7655 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-22 11:15:23.059  7655  7655 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 11:15:23.059  7655  7655 E wpa_supplicant: SIM READ ERROR
08-22 11:15:23.059  7655  7655 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:23.059  7655  7655 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-22 11:15:23.059  7655  7655 E wpa_supplicant: SIM READ ERROR
08-22 11:15:23.059  7655  7655 I wpa_supplicant: Blacklist: Clear (all) 
08-22 11:15:23.059  7655  7655 I wpa_supplicant: wpa_default_ap_write_once
08-22 11:15:23.059  7655  7655 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-22 11:15:23.059  7655  7655 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:23.059  7655  7655 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-22 11:15:23.059  7655  7655 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:23.059  7655  7655 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-22 11:15:23.069  7655  7655 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-22 11:15:23.069  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:23.069  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:23.069  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:23.219  7655  7655 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-22 11:15:23.349  7655  7655 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-22 11:15:23.349  7655  7655 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-22 11:15:23.359  7655  7655 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-22 11:15:23.359   382   382 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7655
08-22 11:15:23.359   382   382 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-22 11:15:23.359  7655  7655 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-22 11:15:23.359  7655  7655 I wpa_supplicant: ssSupport state is = 1,
08-22 11:15:23.359  7655  7655 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-22 11:15:23.369  7655  7655 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-22 11:15:23.379  7655  7655 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-22 11:15:23.379   382   382 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7655
08-22 11:15:23.379   382   382 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-22 11:15:23.379  7655  7655 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-22 11:15:23.379  7655  7655 I wpa_supplicant: ssSupport state is = 1
08-22 11:15:23.379  7655  7655 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:23.379  7655  7655 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-22 11:15:23.379  7655  7655 E wpa_supplicant: SIM READ ERROR
08-22 11:15:23.379  7655  7655 I wpa_supplicant: wpa_default_ap_write_once
08-22 11:15:23.379  7655  7655 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-22 11:15:23.379  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 11:15:23.379  7655  7655 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-22 11:15:23.379  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 11:15:23.379  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 11:15:23.379  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-22 11:15:23.379  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 11:15:23.379  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 11:15:23.429  7655  7655 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-22 11:15:23.429  7655  7655 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-22 11:15:23.489  7655  7655 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-22 11:15:23.489  7655  7655 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-22 11:15:23.489  7655  7655 I wpa_supplicant: Skip scan - bUseNetwork false
08-22 11:15:23.499  1016  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-22 11:15:23.499  1016  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-22 11:15:23.499  7655  7655 I wpa_supplicant: HOTSPOT20_ENABLE called
08-22 11:15:23.499  7655  7655 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 11:15:23.499  7655  7655 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 11:15:23.499  7655  7655 E wpa_supplicant: SIM READ ERROR
08-22 11:15:23.499  7655  7655 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 11:15:23.519  7655  7655 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-22 11:15:23.529  7655  7655 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-22 11:15:23.529  1016  1126 D WifiConfigStore: Loading config and enabling all networks 
08-22 11:15:23.529  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:23.529  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:23.529  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-22 11:15:23.529  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:23.529  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-22 11:15:23.529  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:23.539  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 11:15:23.539  1174  1671 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 11:15:23.539  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-22 11:15:23.539  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:23.539  1174  1174 D HotspotTile: onReceive : 3, 0
,08-22 11:15:23.539  3060  3060 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 11:15:23.549  1016  1214 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:23.549  1016  1214 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:23.549  1016  1214 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:23.549  1016  1214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:23.549  1016  1214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:23.549  1620  1620 I Hs20UtilService: Starting #20
,08-22 11:15:23.549  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:23.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:23.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:23.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:23.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:23.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:23.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:23.549  6774  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:23.559  1016  1126 E WifiConfigStore: Not a HS20
,08-22 11:15:23.559  1620  1640 I Hs20UtilService: Message received 5011
,08-22 11:15:23.559  6545  6545 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-22 11:15:23.559  1016  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-22 11:15:23.559  6545  6545 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 11:15:23.559  6545  6545 D SecurityLogAgent: StateMachine : Current State = 1
08-22 11:15:23.559  6545  6545 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 11:15:23.559  6774  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:23.569  1016  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-22 11:15:23.569  1016  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-22 11:15:23.579  7655  7655 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-22 11:15:23.579  7655  7655 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-22 11:15:23.579  7655  7655 I wpa_supplicant: reset timer : RESET_TIMER 0
08-22 11:15:23.579  7655  7655 I wpa_supplicant: P2P: Current p2p state = IDLE
08-22 11:15:23.579  7655  7655 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-22 11:15:23.579  7655  7655 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-22 11:15:23.579  7655  7655 I wpa_supplicant: First Scan Start
08-22 11:15:23.579  7655  7655 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-22 11:15:23.579  1016  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-22 11:15:23.579  1016  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-22 11:15:23.579  1016  1126 I WifiNative-HAL: startHal
08-22 11:15:23.579  1016  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9d36888c
08-22 11:15:23.579  1016  1126 I WifiNative-HAL: Could not start hal
,08-22 11:15:23.579  6992  6992 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 11:15:23.579  1016  1126 E WifiNative-wlan0: do suspend true
,08-22 11:15:23.589  1016  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-22 11:15:23.589  1016  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-22 11:15:23.589  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
,08-22 11:15:23.589  1016  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:23.589  1016  1149 I WifiNative-HAL: startHal
08-22 11:15:23.589  1016  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9e4109bc
08-22 11:15:23.589  1016  1149 I WifiNative-HAL: Could not start hal
08-22 11:15:23.589  1016  1149 E WifiScanningService: could not start HAL
08-22 11:15:23.589  1016  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-22 11:15:23.589  1016  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-22 11:15:23.589  1016  1126 E WifiNative-wlan0: invaild command id : 215
,08-22 11:15:23.589  1016  1016 D RttService: SCAN_AVAILABLE : 3
08-22 11:15:23.589  1016  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-22 11:15:23.589  1016  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-22 11:15:23.589  1016  1126 E WifiNative-wlan0: invaild command id : 215
08-22 11:15:23.589  1016  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler },
08-22 11:15:23.599   278  1015 D CommandListener: Setting iface cfg
08-22 11:15:23.599   278  1015 D CommandListener: Trying to bring up p2p0
,08-22 11:15:23.599  1016  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-22 11:15:23.599  7655  7655 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-22 11:15:23.599  1016  1125 D WifiP2pService: P2pEnablingState
08-22 11:15:23.599  1016  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
08-22 11:15:23.599  7655  7655 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-22 11:15:23.599  1016  1125 D WifiP2pService: P2p socket connection successful
08-22 11:15:23.599  1016  1125 D WifiP2pService: P2pEnabledState
08-22 11:15:23.599  1016  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-22 11:15:23.599  1016  1128 E ConnectivityService: updateNetworkInfo()
,08-22 11:15:23.599  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-22 11:15:23.599  7655  7655 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-22 11:15:23.599  1016  1126 E WifiStateMachine: Failed to set frequency band 0
,08-22 11:15:23.599  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-22 11:15:23.599  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 11:15:23.599  1016  1046 D WifiDisplayController: disconnect
08-22 11:15:23.599  1016  1046 D WifiDisplayController: updateConnection
08-22 11:15:23.599  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 11:15:23.599  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-22 11:15:23.599  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:23.599  1016  1126 D SecContentProvider2: mCursor = null
,08-22 11:15:23.609  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:23.609  1016  1126 D SecContentProvider2: mCursor = null
,08-22 11:15:23.609  1016  1125 D WifiNative-p2p0: p2pGetDeviceAddress
08-22 11:15:23.609  1016  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-22 11:15:23.609  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-22 11:15:23.609  1016  3764 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 11:15:23.609  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-22 11:15:23.609  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-22 11:15:23.609  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-22 11:15:23.609  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 11:15:23.609  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-22 11:15:23.619  1016  1125 D WifiP2pService: DeviceAddress: 0a:76:28,
,08-22 11:15:23.619  1016  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-22 11:15:23.619  1016  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-22 11:15:23.619  1016  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-22 11:15:23.619  1016  1046 D WifiDisplayController:  secondary type: null
08-22 11:15:23.619  1016  1046 D WifiDisplayController:  wps: 0
08-22 11:15:23.619  1016  1046 D WifiDisplayController:  grpcapab: 0
08-22 11:15:23.619  1016  1046 D WifiDisplayController:  devcapab: 0
08-22 11:15:23.619  1016  1046 D WifiDisplayController:  status: 3
08-22 11:15:23.619  1016  1046 D WifiDisplayController:  wfdInfo: null
08-22 11:15:23.619  1016  1046 D WifiDisplayController:  groupownerAddress: null
08-22 11:15:23.619  1016  1046 D WifiDisplayController:  GOdeviceName: null
08-22 11:15:23.619  1016  1046 D WifiDisplayController:  interfaceAddress: 
08-22 11:15:23.619  1016  1046 D WifiDisplayController:  SConnectInfo : null
,08-22 11:15:23.619  3060  3060 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-22 11:15:23.619  3060  3060 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 11:15:23.619  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 11:15:23.619  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 11:15:23.619  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 11:15:23.619  3060  3060 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 11:15:23.619  3060  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 11:15:23.629  7353  7353 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 11:15:23.629  7353  7353 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-22 11:15:23.629  7353  7353 D FileShare-Client: Outbound.stopDelayTimer - 
,08-22 11:15:23.639  7368  7368 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 11:15:23.639  1016  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-22 11:15:23.639  1016  1125 D WifiP2pService: InactiveState
,08-22 11:15:23.639  1016  1125 D WifiP2pService: InactiveState{ what=143376 }
,08-22 11:15:23.639  1016  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-22 11:15:23.639  7655  7655 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-22 11:15:23.639  1016  1125 D WifiP2pService: InactiveState{ what=143376 }
08-22 11:15:23.639  1016  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-22 11:15:23.649   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 11:15:23.739  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 11:15:23.739  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 11:15:23.739  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 11:15:24.419  6774  6827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 11:15:24.419  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:24.419  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:24.419  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:24.419  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:24.419  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:24.419  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:24.419  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:24.419  6774  6827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:24.419  6774  6827 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-22 11:15:24.419  6774  6827 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-22 11:15:24.429  6774  6827 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@14621caf Bundle[{}]
,08-22 11:15:24.429  6774  6827 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 11:15:24.429  6774  6827 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-22 11:15:24.429  6774  6827 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-22 11:15:24.429  6774  6827 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-22 11:15:24.429  6774  6827 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-22 11:15:24.429  6774  6827 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-22 11:15:24.439  6774  6827 I System.out: Running OutgoingSocketThread
,08-22 11:15:24.439  6774  7664 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1344)
,08-22 11:15:24.449  1016  3371 D SSRM:n  : SIOP:: AP = 330
08-22 11:15:24.449  6774  7664 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46388
08-22 11:15:24.449  6774  7664 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-22 11:15:24.519  1016  3411 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-22 11:15:24.649   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 11:15:24.699  1016  2021 V SAMP_SPCM_test: CSC File load.. 
,08-22 11:15:24.699  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
,08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-22 11:15:24.709  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
,08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control,
08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
,08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
,08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
,08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
,08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
,08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-22 11:15:24.749  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-22 11:15:24.759  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-22 11:15:24.759  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,08-22 11:15:24.759  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
,08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
,08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
,08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
,08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
,08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth,
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
,08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
,08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
,08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
,08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-22 11:15:24.769  1016  2021 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
,08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-22 11:15:24.769  1016  2021 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-22 11:15:24.779  1016  2021 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:24.779  1016  2021 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:24.779  1016  2021 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:24.779  1016  2021 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:24.799  7665  7665 E Zygote  : MountEmulatedStorage(),
08-22 11:15:24.799  7655  7655 I wpa_supplicant: nl80211: Received scan results (30 BSSes)
08-22 11:15:24.799  1016  2021 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7665 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 11:15:24.799  7665  7665 E Zygote  : v2
08-22 11:15:24.799  7665  7665 I libpersona: KNOX_SDCARD checking this for 1000
08-22 11:15:24.799  7665  7665 I libpersona: KNOX_SDCARD not a persona
08-22 11:15:24.799  7665  7665 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:24.799  7655  7655 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-22 11:15:24.809  1016  7660 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-22 11:15:24.809  7655  7655 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-22 11:15:24.809  7655  7655 I wpa_supplicant: Trying to associate with  'G700'
,08-22 11:15:24.809  7655  7655 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-22 11:15:24.809  7665  7665 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:24.809  7655  7655 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-22 11:15:24.809  7665  7665 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:24.829  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 11:15:24.829  1016  1126 D SecContentProvider2: mCursor = null
,08-22 11:15:24.849  7665  7665 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:24.849  7665  7665 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:24.859  7665  7665 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 11:15:24.899  1016  2021 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-22 11:15:24.919  7655  7655 E wpa_supplicant: Cmd 35605 not handled
08-22 11:15:24.919  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:24.919  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:24.919  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:24.919  7655  7655 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-22 11:15:24.919  7655  7655 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-22 11:15:24.919  7655  7655 I wpa_supplicant: Associated with F4.99.3E
08-22 11:15:24.919  7655  7655 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-22 11:15:24.919  7655  7655 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-22 11:15:24.919  7655  7655 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-22 11:15:24.919  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:24.919  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 11:15:24.919  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:24.929  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-22 11:15:24.929  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 11:15:24.929  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 11:15:24.929  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-22 11:15:24.929  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-22 11:15:24.929  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-22 11:15:24.929  1016  1126 D SecContentProvider2: mCursor = null
08-22 11:15:24.929  1016  1043 D Tethering: interfaceStatusChanged wlan0, true,
,08-22 11:15:24.929  1016  1130 E Tethering: No numeric data
08-22 11:15:24.929  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:24.929  1016  1126 D SecContentProvider2: mCursor = null
,08-22 11:15:24.929  7655  7655 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-22 11:15:24.929  7655  7655 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE,
08-22 11:15:24.929  7655  7655 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-22 11:15:24.929  7655  7655 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-22 11:15:24.929  7655  7655 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-22 11:15:24.929  7655  7655 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED,
08-22 11:15:24.929  7655  7655 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=],
08-22 11:15:24.929  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
08-22 11:15:24.929  7655  7655 I wpa_supplicant: Blacklist: Clear (temp) 
08-22 11:15:24.929  7655  7655 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-22 11:15:24.929  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-22 11:15:24.929  1016  1043 D Tethering: interfaceStatusChanged wlan0, true,
,08-22 11:15:24.939  1016  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
08-22 11:15:24.939  1016  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-22 11:15:24.939  1016  1130 D Tethering: clearTetheredNotification()
,08-22 11:15:24.939  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-22 11:15:24.939  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-22 11:15:24.939  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:24.939  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:24.939  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 11:15:24.939  1174  1174 D HotspotTile: updateTetherState():false, false
08-22 11:15:24.939  1016  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-22 11:15:24.949  1016  1123 V NetworkStats: performPollLocked() took 4ms
,08-22 11:15:24.949  1016  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-22 11:15:24.949  1016  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-22 11:15:24.949  1016  1128 E ConnectivityService: updateNetworkInfo()
08-22 11:15:24.949  1016  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-22 11:15:24.949  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:24.949  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 11:15:24.949  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-22 11:15:24.949  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:24.949  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:24.959  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:24.959  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:24.959  1016  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 11:15:24.959  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:24.959  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:24.959  1016  1514 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:24.959  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:24.959  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:24.959  1016  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:24.959  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 11:15:24.959  1016  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 11:15:24.959  1620  1620 I Hs20UtilService: Starting #21
08-22 11:15:24.959  1620  1640 I Hs20UtilService: Message received 5007
,08-22 11:15:24.969  3060  3060 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-22 11:15:24.969  3060  3060 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 11:15:24.969  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 11:15:24.969  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-22 11:15:24.969  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-22 11:15:24.969  3060  3060 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 11:15:24.969  3060  3889 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 11:15:24.979   278  1015 D CommandListener: Setting iface cfg
,08-22 11:15:24.979  1016  1126 E WifiStateMachine: Start Dhcp Watchdog 3
,08-22 11:15:24.989  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 11:15:24.989  1016  1126 D SecContentProvider2: mCursor = null
,08-22 11:15:24.989  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:24.989  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:24.999  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:24.999  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:24.999  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:24.999  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:24.999  1016  1126 E WifiNative-wlan0: do suspend false
,08-22 11:15:24.999  1016  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-22 11:15:25.009  1016  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-22 11:15:25.009  1016  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 11:15:25.009  1016  1126 D SecContentProvider2: mCursor = null
,08-22 11:15:25.219  7684  7684 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-22 11:15:25.219  7684  7684 I dhcpcd  : version 5.5.6 starting,
,08-22 11:15:25.229  7684  7684 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-22 11:15:25.289  7684  7684 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-22 11:15:25.289  7684  7684 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-22 11:15:25.289  7684  7684 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-22 11:15:25.289  7684  7684 I dhcpcd  : bssid match,
08-22 11:15:25.289  7684  7684 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-22 11:15:25.359  7684  7684 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-22 11:15:25.409  7684  7684 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,08-22 11:15:25.439  6774  6827 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1345),
08-22 11:15:25.439  6774  6827 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1345)
08-22 11:15:25.439  6774  6827 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1350)
08-22 11:15:25.439  6774  6827 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-22 11:15:25.439  6774  6827 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1351)
,08-22 11:15:25.449  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:25.449  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4072a1 added. We now have 2 listener(s)
,08-22 11:15:25.449  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-22 11:15:25.449  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:25.449  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:25.449  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:25.449  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e40cc6 added. We now have 9 listener(s)
,08-22 11:15:25.449  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:25.459  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 11:15:25.469  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:25.469  6774  6827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:25.469  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:25.469  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:25.469  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-22 11:15:25.469  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:25.469  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:25.469  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:25.469  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:25.469  6774  6827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:25.469  6774  6827 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 11:15:25.469  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 11:15:25.469  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2606fb4 added. We now have 3 listener(s)
,08-22 11:15:25.479  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:25.489  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:25.489  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-22 11:15:25.489  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:25.489  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:25.489  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:25.489  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e5097dd added. We now have 10 listener(s)
08-22 11:15:25.489  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-22 11:15:25.489  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-22 11:15:25.489  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:25.489  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 11:15:25.489  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:25.489  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.489  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:25.489  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-22 11:15:25.489  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d4072a1 removed from the list
08-22 11:15:25.489  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:25.489  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e40cc6 removed from the list
,08-22 11:15:25.489  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:25.489  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:25.489  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.489  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:25.499  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 11:15:25.499  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:25.499  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:25.499  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e40cc6 not in the list
,08-22 11:15:25.499  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.499  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:25.499  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-22 11:15:25.499  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:25.499  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:25.499  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e5097dd removed from the list
08-22 11:15:25.499  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:25.499  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.499  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:25.499  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:25.499  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2606fb4 removed from the list
08-22 11:15:25.499  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:25.499  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28842f52 added. We now have 2 listener(s)
08-22 11:15:25.509  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-22 11:15:25.509  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 11:15:25.509  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:25.509  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:25.509  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@321f5223 added. We now have 9 listener(s)
08-22 11:15:25.509  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:25.509  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 11:15:25.519  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:25.519  6774  6827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:25.519  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:25.519  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:25.519  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-22 11:15:25.519  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:25.519  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:25.519  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:25.519  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:25.529  6774  6827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-22 11:15:25.529  6774  6827 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 11:15:25.529  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 11:15:25.529  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a43d4d9 added. We now have 3 listener(s)
,08-22 11:15:25.529  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-22 11:15:25.529  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:25.529  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:25.529  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:25.529  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3291ee9e added. We now have 10 listener(s)
08-22 11:15:25.529  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:25.529  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:25.529  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 11:15:25.529  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 11:15:25.529  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:25.529  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 11:15:25.529  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:25.539  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:25.539  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 11:15:25.549  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 11:15:25.549  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 11:15:25.549  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 11:15:25.549  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 11:15:25.549  6774  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 11:15:25.559  7562  7636 D BtGatt.GattService: registerClient() - UUID=ea71a465-b534-4021-8f93-d53748ac777c
,08-22 11:15:25.599  7562  7590 D BtGatt.GattService: onClientRegistered() - UUID=ea71a465-b534-4021-8f93-d53748ac777c, clientIf=6,
08-22 11:15:25.599  6774  6784 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-22 11:15:25.599  7562  7631 D BtGatt.GattService: start scan with filters
,08-22 11:15:25.609  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,08-22 11:15:25.609  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 11:15:25.609  7562  7594 D BtGatt.ScanManager: handling starting scan
08-22 11:15:25.609  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-22 11:15:25.609  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 11:15:25.609  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-22 11:15:25.609  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 11:15:25.609  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 11:15:25.619  7562  7594 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@12c645bf
,08-22 11:15:25.619  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-22 11:15:25.619  7562  7590 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-22 11:15:25.619  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:25.619  7562  7594 D BtGatt.ScanManager: allow scan with filters
08-22 11:15:25.619  7562  7594 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-22 11:15:25.619  7562  7594 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-22 11:15:25.619  7562  7590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-22 11:15:25.619  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:25.619  7562  7594 D BtGatt.ScanManager: Starting BLE batch scan
08-22 11:15:25.619  7562  7594 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 11:15:25.619  6774  6827 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation,
08-22 11:15:25.619  7562  7590 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-22 11:15:25.619  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:25.629  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
08-22 11:15:25.629  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 11:15:25.629  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.629  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 11:15:25.629  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 11:15:25.629  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
08-22 11:15:25.629  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:25.629  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 11:15:25.629  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-22 11:15:25.629  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-22 11:15:25.629  7562  7590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-22 11:15:25.629  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:25.629  7562  7631 D BtGatt.GattService: stopScan() - queue size =1
,08-22 11:15:25.629  7562  7636 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 11:15:25.629  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 11:15:25.629  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 11:15:25.629  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 11:15:25.629  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 11:15:25.629  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-22 11:15:25.639  7562  7594 D BtGatt.ScanManager: filter size is 1
08-22 11:15:25.639   288   288 E SMD     : DCD OFF
08-22 11:15:25.639  7562  7594 D BtGatt.ScanManager: delete FilterIndex - 3
,08-22 11:15:25.639  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:25.639  7562  7590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-22 11:15:25.639  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:25.639  7562  7594 D BtGatt.ScanManager: stopping BLe Batch
,08-22 11:15:25.639  7562  7590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-22 11:15:25.639  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:25.639  7562  7594 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-22 11:15:25.639  7562  7590 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-22 11:15:25.639  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:25.649  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 11:15:25.649  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 11:15:25.649  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 11:15:25.649   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 11:15:25.649  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:25.649  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:25.649  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 11:15:25.649  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:25.649  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:25.649  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:25.649  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 11:15:25.659  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:25.659  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:25.659  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:25.659  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:25.659  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28842f52 removed from the list
,08-22 11:15:25.659  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:25.659  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@321f5223 removed from the list
08-22 11:15:25.659  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 11:15:25.659  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:25.659  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.659  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:25.659  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 11:15:25.659  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:25.659  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:25.659  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@321f5223 not in the list
,08-22 11:15:25.659  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.659  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:25.659  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 11:15:25.659  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:25.659  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 11:15:25.659  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3291ee9e removed from the list
08-22 11:15:25.659  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:25.659  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.659  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:25.659  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:25.659  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a43d4d9 removed from the list
,08-22 11:15:25.669  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 11:15:25.669  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@132a56aa added. We now have 2 listener(s)
,08-22 11:15:25.669  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-22 11:15:25.669  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:25.669  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 11:15:25.669  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:25.669  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eae29b added. We now have 9 listener(s)
,08-22 11:15:25.669  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:25.669  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 11:15:25.679  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:25.679  6774  6827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:25.679  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:25.679  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:25.679  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:25.679  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:25.679  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:25.679  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:25.679  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:25.679  6774  6827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:25.679  6774  6827 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:15:25.679  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:25.679  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c9a4611 added. We now have 3 listener(s)
,08-22 11:15:25.679  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:25.689  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-22 11:15:25.689  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:25.689  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:25.689  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:25.689  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@312f3376 added. We now have 10 listener(s)
08-22 11:15:25.689  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:25.689  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:25.689  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:25.689  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 11:15:25.689  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 11:15:25.689  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 11:15:25.689  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 11:15:25.689  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:25.689  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 11:15:25.689  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 11:15:25.699  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 11:15:25.699  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 11:15:25.699  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-22 11:15:25.699  6774  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 11:15:25.699  7562  7574 D BtGatt.GattService: registerClient() - UUID=d08cd7c0-2dbe-4504-9d4f-51dc6099463e
,08-22 11:15:25.739  7562  7590 D BtGatt.GattService: onClientRegistered() - UUID=d08cd7c0-2dbe-4504-9d4f-51dc6099463e, clientIf=6
,08-22 11:15:25.749  6774  6786 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-22 11:15:25.749  7562  7631 D BtGatt.GattService: start scan with filters
,08-22 11:15:25.749  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 11:15:25.749  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 11:15:25.749  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 11:15:25.749  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 11:15:25.749  7562  7594 D BtGatt.ScanManager: handling starting scan
,08-22 11:15:25.749  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:25.749  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 11:15:25.749  7562  7590 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-22 11:15:25.749  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 11:15:25.749  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:25.749  7562  7594 D BtGatt.ScanManager: allow scan with filters
08-22 11:15:25.749  7562  7594 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-22 11:15:25.749  7562  7594 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-22 11:15:25.759  7562  7590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-22 11:15:25.759  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:25.759  7562  7594 D BtGatt.ScanManager: Starting BLE batch scan
,08-22 11:15:25.759  7562  7594 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 11:15:25.759  7562  7590 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-22 11:15:25.759  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:25.759  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 11:15:25.759  7562  7590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-22 11:15:25.759  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:25.769  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
08-22 11:15:25.769  6774  6827 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-22 11:15:25.769  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:25.769  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:25.769  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:25.769  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:25.769  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 11:15:25.769  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 11:15:25.769  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:25.769  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@132a56aa removed from the list
08-22 11:15:25.769  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:25.769  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eae29b removed from the list
08-22 11:15:25.769  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 11:15:25.769  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:25.769  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.769  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-22 11:15:25.769  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.769  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:25.769  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-22 11:15:25.769  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:25.769  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:25.769  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eae29b not in the list
,08-22 11:15:25.769  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 11:15:25.769  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 11:15:25.769  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
08-22 11:15:25.769  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 11:15:25.769  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-22 11:15:25.769  7562  7631 D BtGatt.GattService: stopScan() - queue size =1
08-22 11:15:25.769  7562  7572 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 11:15:25.779  7562  7594 D BtGatt.ScanManager: filter size is 1
08-22 11:15:25.779  7562  7594 D BtGatt.ScanManager: delete FilterIndex - 4
08-22 11:15:25.779  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 11:15:25.779  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 11:15:25.779  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 11:15:25.779  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 11:15:25.779  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 11:15:25.779  7562  7590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-22 11:15:25.779  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:25.779  7562  7594 D BtGatt.ScanManager: stopping BLe Batch
,08-22 11:15:25.779  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:25.779  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-22 11:15:25.779  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 11:15:25.779  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 11:15:25.779  7562  7590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-22 11:15:25.779  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:25.779  7562  7594 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-22 11:15:25.779  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:25.789  7562  7590 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-22 11:15:25.789  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:25.789  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 11:15:25.789  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:25.789  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 11:15:25.789  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:25.789  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 11:15:25.789  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:25.789  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@312f3376 removed from the list
,08-22 11:15:25.789  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:25.789  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.789  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:25.789  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:25.789  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c9a4611 removed from the list
,08-22 11:15:25.789  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 11:15:25.789  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dd31102 added. We now have 2 listener(s)
,08-22 11:15:25.799  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-22 11:15:25.799  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:25.799  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:25.799  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:25.799  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b990a13 added. We now have 9 listener(s)
08-22 11:15:25.799  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:25.799  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 11:15:25.799  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:25.799  6774  6827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:25.799  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:25.799  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:25.799  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:25.799  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:25.799  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 11:15:25.799  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 11:15:25.799  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 11:15:25.809  6774  6827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 11:15:25.809  6774  6827 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:15:25.809  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:25.809  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:25.809  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bb6a649 added. We now have 3 listener(s)
,08-22 11:15:25.809  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:25.809  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-22 11:15:25.809  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:25.809  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 11:15:25.809  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:25.809  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18e53b4e added. We now have 10 listener(s)
08-22 11:15:25.809  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 11:15:25.809  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:25.809  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 11:15:25.809  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 11:15:25.809  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:25.809  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 11:15:25.819  1016  1126 E WifiNative-wlan0: do suspend true
,08-22 11:15:25.819  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 11:15:25.819  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 11:15:25.819  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 11:15:25.829  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 11:15:25.829  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 11:15:25.829  6774  6827 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 11:15:25.829  7562  7631 D BtGatt.GattService: registerClient() - UUID=826833a6-7cce-48b2-9cbe-000d15c5ba57
,08-22 11:15:25.849  1016  1126 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-22 11:15:25.849  1016  1126 E WifiStateMachine: VerifyingLinkState enter
,08-22 11:15:25.849  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 11:15:25.849  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:25.849  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:25.849  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:25.849  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:25.849  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:25.849  1016  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-22 11:15:25.849  1016  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-22 11:15:25.849  1016  1128 E ConnectivityService: updateNetworkInfo()
,08-22 11:15:25.849  1016  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-22 11:15:25.849  1016  1128 D ConnectivityService: Adding iface wlan0 to network 504
,08-22 11:15:25.859  1016  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-22 11:15:25.859  1016  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-22 11:15:25.859  1016  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-22 11:15:25.859  1016  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-22 11:15:25.859  1016  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-22 11:15:25.869  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-22 11:15:25.869  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:25.869  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:25.869  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:25.869  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:25.869  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:25.869  7562  7590 D BtGatt.GattService: onClientRegistered() - UUID=826833a6-7cce-48b2-9cbe-000d15c5ba57, clientIf=6
,08-22 11:15:25.869  6774  6784 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-22 11:15:25.869  7562  7572 D BtGatt.GattService: start scan with filters
08-22 11:15:25.869  1016  1126 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-22 11:15:25.869  7562  7594 D BtGatt.ScanManager: handling starting scan
08-22 11:15:25.869  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 11:15:25.869  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 11:15:25.879  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 11:15:25.879  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 11:15:25.879  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-22 11:15:25.879  1016  1128 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-22 11:15:25.879  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-22 11:15:25.879  1016  1128 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
08-22 11:15:25.879  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 11:15:25.879  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-22 11:15:25.879  7562  7590 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-22 11:15:25.879  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:25.879  1016  1128 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-22 11:15:25.879  7562  7594 D BtGatt.ScanManager: allow scan with filters
08-22 11:15:25.879  7562  7594 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-22 11:15:25.879  7562  7594 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6,
08-22 11:15:25.879  1016  3767 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 11:15:25.879  1016  3767 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:25.879  1016  3767 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:25.879  1016  3767 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 11:15:25.879  1016  3767 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 11:15:25.889  1016  1128 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-22 11:15:25.889  1016  1128 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,08-22 11:15:25.889  1016  1128 D ConnectivityService: LTETest block dns file not exists
,08-22 11:15:25.889  7562  7590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-22 11:15:25.889  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:25.889  7562  7594 D BtGatt.ScanManager: Starting BLE batch scan
08-22 11:15:25.889  7562  7594 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 11:15:25.889  1620  1620 I Hs20UtilService: Starting #22
,08-22 11:15:25.889  1620  1640 I Hs20UtilService: Message received 5007
,08-22 11:15:25.889  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-22 11:15:25.889  7562  7590 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-22 11:15:25.889  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:25.889  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 11:15:25.889  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:25.889  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 11:15:25.889  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:25.889  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.889  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 11:15:25.889  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:25.889  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dd31102 removed from the list
08-22 11:15:25.889  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:25.889  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b990a13 removed from the list
08-22 11:15:25.889  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:25.889  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:25.889  1016  1128 V NetworkStats: updateIfacesLocked()
08-22 11:15:25.889  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:25.889  1016  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-22 11:15:25.889  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:25.899  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:25.899  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit,
08-22 11:15:25.899  1016  1128 V NetworkStats: performPollLocked() took 3ms
,08-22 11:15:25.899  7562  7590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-22 11:15:25.899  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:25.899  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 11:15:25.899  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 11:15:25.899  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:25.899  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:25.899  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:25.899  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:25.899  3060  3060 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 11:15:25.899  3060  3060 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-22 11:15:25.899  1016  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-22 11:15:25.909  1016  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-22 11:15:25.909  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.909  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-22 11:15:25.909  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.909  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 11:15:25.909  1016  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-22 11:15:25.909  1016  1128 E ConnectivityService: updateNetworkInfo()
08-22 11:15:25.909  1016  1128 E ConnectivityService: updateNetworkInfo()
08-22 11:15:25.909  1016  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-22 11:15:25.909  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-22 11:15:25.909  1016  1016 I WifiTrafficPoller: mBoosterFLAG : 0
08-22 11:15:25.909  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-22 11:15:25.909  1016  1128 V NetworkStats: updateIfacesLocked()
08-22 11:15:25.909  1016  1016 I WifiTrafficPoller: current booster mode : FullMode
08-22 11:15:25.909  1016  1128 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:25.909  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-22 11:15:25.909  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 11:15:25.909  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:25.909  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:25.909  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:25.909  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b990a13 not in the list
08-22 11:15:25.909  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 11:15:25.909  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-22 11:15:25.909  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 11:15:25.909  1016  1128 V NetworkStats: performPollLocked() took 4ms
08-22 11:15:25.909  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 11:15:25.909  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-22 11:15:25.909  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:25.909  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:25.909  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:25.909  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:25.909  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-22 11:15:25.909  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:25.909  7562  7631 D BtGatt.GattService: stopScan() - queue size =1
08-22 11:15:25.919  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:25.919  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:25.919  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:25.919  7562  7594 D BtGatt.ScanManager: filter size is 1
,08-22 11:15:25.919  7562  7594 D BtGatt.ScanManager: delete FilterIndex - 5
,08-22 11:15:25.919  7562  7636 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 11:15:25.919  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
,08-22 11:15:25.919  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 11:15:25.919  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 11:15:25.919  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 11:15:25.919  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-22 11:15:25.919  7562  7590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-22 11:15:25.919  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:25.919  7562  7594 D BtGatt.ScanManager: stopping BLe Batch
08-22 11:15:25.929  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:25.929  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 11:15:25.929  6774  6827 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 11:15:25.929  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 11:15:25.929  1016  1128 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-22 11:15:25.929  1016  7681 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:25.929  1016  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-22 11:15:25.929  1016  7681 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-22 11:15:25.929  1016  7681 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-22 11:15:25.929  1016  7681 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-22 11:15:25.929  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:25.929  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:25.929  1016  7681 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-22 11:15:25.929  7562  7590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-22 11:15:25.929  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 11:15:25.929  7562  7594 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-22 11:15:25.929   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 11:15:25.929   278  1011 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-22 11:15:25.929  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:25.929  7562  7590 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-22 11:15:25.929  7562  7590 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 11:15:25.929  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:25.929  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:25.929  1016  1128 D ConnectivityService:    accepting network in place of null
08-22 11:15:25.929  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:25.929  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:25.929  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18e53b4e removed from the list
08-22 11:15:25.929  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:25.929  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.929  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:25.929  6774  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 11:15:25.929  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:25.929  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bb6a649 removed from the list
08-22 11:15:25.929  6774  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 11:15:25.929  1016  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-22 11:15:25.929  1016  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-22 11:15:25.929  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:25.929  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dddbe5a added. We now have 2 listener(s)
,08-22 11:15:25.929  1481  1481 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-22 11:15:25.939  1481  1481 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-22 11:15:25.939  1016  1128 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-22 11:15:25.939  1016  1128 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-22 11:15:25.939  1016  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-22 11:15:25.939  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-22 11:15:25.939  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:25.939  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 11:15:25.939  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 11:15:25.939  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b05a88b added. We now have 9 listener(s)
08-22 11:15:25.939  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:25.939  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 11:15:25.939  1016  1128 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} },
08-22 11:15:25.939  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-22 11:15:25.939  1016  1130 D Tethering: MasterInitialState.processMessage what=3
,08-22 11:15:25.939  1016  1123 V NetworkStats: updateIfacesLocked()
08-22 11:15:25.939  1016  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-22 11:15:25.949  1016  1123 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:25.949  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:25.949  1016  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-22 11:15:25.949  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:25.949  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 11:15:25.949  1016  1537 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 11:15:25.949  1174  1652 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-22 11:15:25.949  1016  1537 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-22 11:15:25.949  1016  1537 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:25.949  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
08-22 11:15:25.949  1016  1123 V NetworkStats: performPollLocked() took 4ms
08-22 11:15:25.949  1016  1537 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:25.949  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-22 11:15:25.949  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-22 11:15:25.949  1016  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 11:15:25.949  1174  1174 D StatusBar.NetworkController: updateDataNetType()
08-22 11:15:25.949  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-22 11:15:25.949  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-22 11:15:25.949  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:25.949  1620  1620 I Hs20UtilService: Starting #23
,08-22 11:15:25.949  4824  6838 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-22 11:15:25.959  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:25.959  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-22 11:15:25.959  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-22 11:15:25.959  1620  1640 I Hs20UtilService: Message received 5007
08-22 11:15:25.959  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-22 11:15:25.959  3060  3060 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 11:15:25.959  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:25.959  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-22 11:15:25.959  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:25.959  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:25.959  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:25.959  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:25.959  3060  3060 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 11:15:25.959  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:25.959  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:25.959  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:25.959  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:25.959  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 11:15:25.959  1016  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-22 11:15:25.959  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 11:15:25.959  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-22 11:15:25.959  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 11:15:25.959  3060  3060 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-22 11:15:25.959  3060  3060 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-22 11:15:25.959  6774  6827 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 11:15:25.959  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 11:15:25.959  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 11:15:25.959  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 11:15:25.959  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 11:15:25.959  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 11:15:25.959  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 11:15:25.959  6774  6827 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 11:15:25.969  6774  6827 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 11:15:25.969  6774  6827 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 11:15:25.969  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 11:15:25.969  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e87d581 added. We now have 3 listener(s)
,08-22 11:15:25.969  1016  1492 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 11:15:25.969  1016  1492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 11:15:25.969  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:25.979  1016  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:25.979  1016  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:25.979  1016  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 11:15:25.979  6774  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 11:15:25.979  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-22 11:15:25.979  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 11:15:25.979  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 11:15:25.979  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 11:15:25.979  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35a96626 added. We now have 10 listener(s)
08-22 11:15:25.979  6774  6827 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 11:15:25.979  6774  6827 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 11:15:25.979  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:25.979  6774  6827 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 11:15:25.979  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:25.979  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.979  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 11:15:25.979  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 11:15:25.979  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dddbe5a removed from the list
08-22 11:15:25.979  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:25.979  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b05a88b removed from the list
08-22 11:15:25.979  6774  6827 D io.jxcore.node.ConnectivityMonitor: stop
08-22 11:15:25.979  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:25.979  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.979  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:25.989  1620  1620 I Hs20UtilService: Starting #24
08-22 11:15:25.989  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:25.989  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:25.989  1620  1640 I Hs20UtilService: Message received 5007
08-22 11:15:25.989  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:25.989  6774  6827 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b05a88b not in the list
08-22 11:15:25.989  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.989  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 11:15:25.989  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 11:15:25.989  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 11:15:25.989  6774  6827 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 11:15:25.989  6774  6827 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35a96626 removed from the list
08-22 11:15:25.989  6774  6827 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 11:15:25.989  6774  6827 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 11:15:25.989  6774  6827 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 11:15:25.989  6774  6827 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 11:15:25.989  6774  6827 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e87d581 removed from the list
08-22 11:15:25.989  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-22 11:15:25.989  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-22 11:15:25.989  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-22 11:15:25.989  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 11:15:25.989  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-22 11:15:25.989  6774  6827 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 11:15:25.989  3060  3060 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 11:15:25.989  3060  3060 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-22 11:15:25.999  6774  7720 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1358, name: My test thread name)
,08-22 11:15:25.999  6774  7720 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1358, thread name: My test thread name)
08-22 11:15:25.999  6774  7720 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1358, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-22 11:15:25.999  1016  3768 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-22 11:15:25.999  6774  7721 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1360, name: My test thread name)
,08-22 11:15:25.999  6774  7721 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1360, thread name: My test thread name)
08-22 11:15:25.999  6774  7721 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1360, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-22 11:15:25.999  1016  1029 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-22 11:15:25.999  1016  1029 D SecContentProvider2: mCursor = null
08-22 11:15:25.999  6774  6827 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-22 11:15:25.999  6774  6827 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-22 11:15:25.999  6774  6827 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-22 11:15:25.999  6774  6827 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-22 11:15:25.999  6774  6827 D com.test.thalitest.ThaliTestRunner: Total duration: 23488 ms
,08-22 11:15:25.999  6774  6827 I jxcore-log: Total number of executed tests:  80
08-22 11:15:25.999  6774  6827 I jxcore-log: 
,08-22 11:15:25.999  6774  6827 I jxcore-log: Number of passed tests:  80
08-22 11:15:25.999  6774  6827 I jxcore-log: 
08-22 11:15:25.999  6774  6827 I jxcore-log: Number of failed tests:  0
08-22 11:15:25.999  6774  6827 I jxcore-log: 
08-22 11:15:25.999  1016  1487 D SecContentProvider2: uri = 15 selection = getToastGravity
,08-22 11:15:25.999  1016  1487 D SecContentProvider2: mCursor = null
08-22 11:15:25.999  6774  6827 I jxcore-log: Number of ignored tests:  0
08-22 11:15:25.999  6774  6827 I jxcore-log: 
08-22 11:15:25.999  6774  6827 I jxcore-log: Total duration:  23488
08-22 11:15:25.999  6774  6827 I jxcore-log: 
08-22 11:15:25.999  6774  6827 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-22 11:15:25.999  6774  6827 I jxcore-log: 
,08-22 11:15:26.009  1016  1514 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-22 11:15:26.009  1016  1514 D SecContentProvider2: mCursor = null
08-22 11:15:26.009  1016  1214 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-22 11:15:26.009  1016  1214 D SecContentProvider2: mCursor = null
08-22 11:15:26.009  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:26.009  6774  6827 I jxcore-log: 
08-22 11:15:26.009  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:26.009  6774  6827 I jxcore-log: 
08-22 11:15:26.009  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:26.009  6774  6827 I jxcore-log: 
08-22 11:15:26.009  1016  1536 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-22 11:15:26.009  1016  1536 D SecContentProvider2: mCursor = null
08-22 11:15:26.009  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:26.009  6774  6827 I jxcore-log: 
08-22 11:15:26.009  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:26.009  6774  6827 I jxcore-log: 
08-22 11:15:26.009  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:26.009  6774  6827 I jxcore-log: 
08-22 11:15:26.019  1016  3767 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-22 11:15:26.019  1016  3767 D SecContentProvider2: mCursor = null
08-22 11:15:26.019  6774  6774 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-22 11:15:26.019  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:26.019  6774  6827 I jxcore-log: 
08-22 11:15:26.019  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 11:15:26.019  6774  6827 I jxcore-log: 
08-22 11:15:26.019  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:26.019  6774  6827 I jxcore-log: 
08-22 11:15:26.019  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:26.019  6774  6827 I jxcore-log: 
08-22 11:15:26.019  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 11:15:26.019  6774  6827 I jxcore-log: 
08-22 11:15:26.029  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 11:15:26.029  6774  6827 I jxcore-log: 
08-22 11:15:26.029  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:26.029  6774  6827 I jxcore-log: 
08-22 11:15:26.029  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:26.029  6774  6827 I jxcore-log: 
08-22 11:15:26.029  1016  7681 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-22 11:15:26.029  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 11:15:26.029  6774  6827 I jxcore-log: 
08-22 11:15:26.029  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 11:15:26.029  6774  6827 I jxcore-log: 
08-22 11:15:26.029  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:26.029  6774  6827 I jxcore-log: 
08-22 11:15:26.029  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 11:15:26.029  6774  6827 I jxcore-log: 
08-22 11:15:26.029  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 11:15:26.029  6774  6827 I jxcore-log: 
08-22 11:15:26.029  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 11:15:26.029  6774  6827 I jxcore-log: 
08-22 11:15:26.029  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 11:15:26.029  6774  6827 I jxcore-log: 
,08-22 11:15:26.029  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 11:15:26.029  6774  6827 I jxcore-log: 
,08-22 11:15:26.029  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 11:15:26.029  6774  6827 I jxcore-log: 
,08-22 11:15:26.029  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 11:15:26.029  6774  6827 I jxcore-log: 
,08-22 11:15:26.029  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 11:15:26.029  6774  6827 I jxcore-log: 
,08-22 11:15:26.039  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 11:15:26.039  6774  6827 I jxcore-log: 
,08-22 11:15:26.039  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 11:15:26.039  6774  6827 I jxcore-log: 
,08-22 11:15:26.039   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-22 11:15:26.049  1016  1492 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,08-22 11:15:26.059  1174  1174 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-22 11:15:26.079  1016  7681 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 22 Aug 2016 09:15:26 GMT], X-Android-Received-Millis=[1471857326089], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471857326064]}
,08-22 11:15:26.079  1016  7681 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-22 11:15:26.079  1016  7681 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-22 11:15:26.079  1016  1128 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-22 11:15:26.079  1016  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504],
08-22 11:15:26.079  1174  1652 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-22 11:15:26.079  1016  1128 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-22 11:15:26.079  4824  6838 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-22 11:15:26.079  1016  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-22 11:15:26.079  1016  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-22 11:15:26.089  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
,08-22 11:15:26.089  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0,
,08-22 11:15:26.089  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE,
,08-22 11:15:26.089  1174  1174 D StatusBar.NetworkController: updateDataNetType()
08-22 11:15:26.089  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-22 11:15:26.089  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-22 11:15:26.089  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-22 11:15:26.089  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-22 11:15:26.089  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-22 11:15:26.089  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 11:15:26.089  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-22 11:15:26.089  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:26.089  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:26.089  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 11:15:26.089  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 11:15:26.149  6774  6774 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-22 11:15:26.149  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 11:15:26.149  6774  6827 I jxcore-log: 
,08-22 11:15:26.279  7723  7723 D AndroidRuntime: ,
08-22 11:15:26.279  7723  7723 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-22 11:15:26.289  7723  7723 D AndroidRuntime: CheckJNI is OFF,
08-22 11:15:26.289  7723  7723 D AndroidRuntime: readGMSProperty: start
08-22 11:15:26.289  7723  7723 D AndroidRuntime: readGMSProperty: already setted!!,
08-22 11:15:26.289  7723  7723 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-22 11:15:26.289  7723  7723 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-22 11:15:26.289  7723  7723 D AndroidRuntime: readGMSProperty: end
08-22 11:15:26.289  7723  7723 D AndroidRuntime: addProductProperty: start
,08-22 11:15:26.289  6774  6774 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-22 11:15:26.289  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 11:15:26.289  6774  6827 I jxcore-log: 
,08-22 11:15:26.399  7723  7723 E AffinityControl: AffinityControl: registerfunction enter,
,08-22 11:15:26.429  7723  7723 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-22 11:15:26.429  6774  6774 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-22 11:15:26.429  6774  6827 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
08-22 11:15:26.429  6774  6827 I jxcore-log: 
,08-22 11:15:26.439  1016  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:26.449  1016  3764 D PackageManager: START PACKAGE DELETE: observer{941866107}
08-22 11:15:26.449  1016  3764 D PackageManager: pkg{<packageName>}
08-22 11:15:26.449  1016  3764 D PackageManager: user{0}
08-22 11:15:26.449  1016  3764 D PackageManager: caller{2000}
08-22 11:15:26.449  1016  3764 D PackageManager: flags{2}
,08-22 11:15:26.449  1016  3764 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-22 11:15:26.449  1016  3764 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,08-22 11:15:26.449  1016  3764 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-22 11:15:26.449  1016  3764 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-22 11:15:26.449  1016  3764 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-22 11:15:26.459  1016  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:26.459  1016  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-22 11:15:26.459  1016  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-22 11:15:26.459  1016  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-22 11:15:26.459  1016  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
08-22 11:15:26.459  1016  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-22 11:15:26.459  1016  1057 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-22 11:15:26.469  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-22 11:15:26.469  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:26.469  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:26.469  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:26.469  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:26.489  7733  7733 E Zygote  : MountEmulatedStorage(),
08-22 11:15:26.489  7733  7733 E Zygote  : v2
08-22 11:15:26.489  7733  7733 I libpersona: KNOX_SDCARD checking this for 1000
,08-22 11:15:26.489  7733  7733 I libpersona: KNOX_SDCARD not a persona
08-22 11:15:26.489  1016  1041 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7733 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 11:15:26.489  1016  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-22 11:15:26.489  1016  1041 I ActivityManager: Killing 6774:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-22 11:15:26.489  7733  7733 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:26.499  7733  7733 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:26.499  7733  7733 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:26.539  7733  7733 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:26.539  7733  7733 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:26.569  1016  1057 W PackageSettings: Skipping PackageSetting{f6099ba com.example.hello/10168} due to missing metadata
,08-22 11:15:26.589  1016  1536 I WindowState: WIN DEATH: Window{1d633168 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-22 11:15:26.589   258   458 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-22 11:15:26.589  1016  1041 I ActivityManager:   Force finishing activity ActivityRecord{3cd38f08 u0 com.test.thalitest/.MainActivity t2}
08-22 11:15:26.589   258  1055 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-22 11:15:26.599  1016  1536 D InputDispatcher: Focus left window: 6774
,08-22 11:15:26.599   258   456 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-22 11:15:26.599  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-22 11:15:26.599  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 11:15:26.619  1016  1028 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin,
08-22 11:15:26.619  1016  1028 D SecContentProvider2: mCursor = null,
08-22 11:15:26.619  1016  1041 D InputDispatcher: Focused application released
08-22 11:15:26.619  1016  1041 D FocusedStackFrame: Set to : 0
,08-22 11:15:26.629  1016  1041 W ActivityManager: mDVFSHelper.acquire()
,08-22 11:15:26.639  1016  1041 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-22 11:15:26.649  1016  1262 W ActivityManager: Spurious death for ProcessRecord{cc6ea98 6774:com.test.thalitest/u0a171}, curProc for 6774: null
,08-22 11:15:26.649   331   331 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-22 11:15:26.649  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-22 11:15:26.649  1016  1057 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-22 11:15:26.669  1498  1498 D Launcher: onRestart, Launcher: 771856341
,08-22 11:15:26.679  1016  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-22 11:15:26.699  7733  7733 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-22 11:15:26.699  7733  7733 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-22 11:15:26.699  7733  7733 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-22 11:15:26.709  7323  7337 I art     : WaitForGcToComplete blocked for 29.039ms for cause Background
,08-22 11:15:26.729  1016  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-22 11:15:26.749  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,08-22 11:15:26.749  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-22 11:15:26.749  2644  2644 I art     : Explicit concurrent mark sweep GC freed 20350(1149KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 1.909ms total 71.801ms
08-22 11:15:26.749  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-22 11:15:26.749  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-22 11:15:26.759  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-22 11:15:26.759  1919  1919 E SamsungIME: mOCRHelper is null
,08-22 11:15:26.769  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,08-22 11:15:26.769  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-22 11:15:26.779  4824  4824 I art     : Explicit concurrent mark sweep GC freed 23637(1440KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 12MB/21MB, paused 2.053ms total 120.969ms
,08-22 11:15:26.779  1498  1498 D Launcher: onStart, Launcher: 771856341
08-22 11:15:26.779  1498  1498 D Launcher.HomeView: onStart
,08-22 11:15:26.779  1498  1498 D Launcher: onResume, Launcher: 771856341
08-22 11:15:26.789  1481  1481 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-22 11:15:26.799  1016  1214 D SettingsProvider: name = kids_home_mode
08-22 11:15:26.799  1016  1214 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 11:15:26.799  1016  1214 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 11:15:26.799  1016  1214 D SettingsProvider: selectionArgs: false
08-22 11:15:26.799  1016  1214 D SettingsProvider: selectionArgs: 10006
08-22 11:15:26.799  1016  1214 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-22 11:15:26.799  1016  1214 D SettingsProvider: ret = -1
,08-22 11:15:26.809  1498  1498 D Launcher.HomeView: onResume
,08-22 11:15:26.809  1456  1456 D PersonaManager: isKioskContainerExistOnDevice
,08-22 11:15:26.819  1498  1498 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-22 11:15:26.819  7733  7733 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-22 11:15:26.819  7733  7733 I PCWCLIENTTRACE_PushUtil: sales region : global
08-22 11:15:26.819  7733  7733 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-22 11:15:26.819  7733  7733 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:26.839  1456  1456 D RegisteredServicesCache: empty dynamic service
,08-22 11:15:26.849  1016  1123 V NetworkStats: removeUidsLocked() for UIDs [10171]
,08-22 11:15:26.849  1016  1123 V NetworkStats: performPollLocked(flags=0x3)
,08-22 11:15:26.849  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:26.849  1016  3765 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-22 11:15:26.849  1016  3765 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-22 11:15:26.849  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 11:15:26.849  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:26.859  1016  3765 I ActivityManager: Killing 7094:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,08-22 11:15:26.859  1016  1123 V NetworkStats: performPollLocked() took 12ms
08-22 11:15:26.859  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:26.869  1498  1498 D MenuAppsGridFragment: onResume
,08-22 11:15:26.869  1498  1498 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-22 11:15:26.869  1498  1498 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-22 11:15:26.889  1016  1041 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-22 11:15:26.889  1016  1041 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.sconnect/com.samsung.android.sconnect.periph.PeriphStartReceiver}
08-22 11:15:26.889  1016  1041 W BroadcastQueue: android.os.TransactionTooLargeException
08-22 11:15:26.889  1016  1041 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-22 11:15:26.889  1016  1041 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-22 11:15:26.889  1016  1041 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-22 11:15:26.889  1016  1041 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-22 11:15:26.889  1016  1041 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-22 11:15:26.889  1016  1041 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:195)
08-22 11:15:26.889  1016  1041 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:26.889  1016  1041 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:26.889  1016  1041 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 11:15:26.889  1016  1041 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-22 11:15:26.889  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-22 11:15:26.889  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:26.889  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:26.889  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:26.889  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:26.899  1819  1819 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-22 11:15:26.909  7751  7751 E Zygote  : MountEmulatedStorage()
08-22 11:15:26.909  7751  7751 E Zygote  : v2
08-22 11:15:26.909  7751  7751 I libpersona: KNOX_SDCARD checking this for 10121
08-22 11:15:26.909  7751  7751 I libpersona: KNOX_SDCARD not a persona
08-22 11:15:26.909  7751  7751 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:26.909  1016  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7751 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-22 11:15:26.909  7751  7751 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:26.909  1016  1262 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-22 11:15:26.909  1016  1262 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-22 11:15:26.909  7751  7751 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:26.909  1016  1262 W ActivityManager: userId = 0, bbcId = -10000
,08-22 11:15:26.909  1016  1262 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:26.909  1016  1262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-22 11:15:26.919  1016  3764 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-22 11:15:26.919  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-22 11:15:26.919  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-22 11:15:26.919  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-22 11:15:26.919  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-22 11:15:26.919  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-22 11:15:26.919  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-22 11:15:26.919  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-22 11:15:26.919  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-22 11:15:26.919  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-22 11:15:26.919  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-22 11:15:26.919  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-22 11:15:26.919  1016  1016 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-22 11:15:26.919  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:26.919  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:26.919  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:26.919  1016  3764 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:26.939  7764  7764 E Zygote  : MountEmulatedStorage()
08-22 11:15:26.939  7764  7764 E Zygote  : v2
08-22 11:15:26.939  7764  7764 I libpersona: KNOX_SDCARD checking this for 10031
08-22 11:15:26.939  7764  7764 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:26.939  7764  7764 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:26.939  7764  7764 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:26.939  7764  7764 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:26.949  1016  1128 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network,
08-22 11:15:26.949  7751  7751 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:15:26.949  1016  3764 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7764 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-22 11:15:26.949  7751  7751 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:26.949  1016  1537 D ActivityManager: handle home activity for 0
08-22 11:15:26.949  1016  1537 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,08-22 11:15:26.949  1016  1537 D KnoxTimeoutHandler: post home show event for user 0
08-22 11:15:26.949  1016  1537 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-22 11:15:26.949  1016  1537 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-22 11:15:26.949  1016  1537 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-22 11:15:26.949  1498  1498 D Launcher.HomeView: onPause
,08-22 11:15:26.949  1498  1498 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-22 11:15:26.949  1456  1456 D RegisteredComponentCache: Collect Tech packages for Knox
,08-22 11:15:26.959  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-22 11:15:26.959  1016  1160 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml,
,08-22 11:15:26.959  1456  1456 D PersonaManager: isKioskContainerExistOnDevice
,08-22 11:15:26.969  2600  2608 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 10
,08-22 11:15:26.969   313   313 I art     : Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 686us total 27.555ms,
,08-22 11:15:26.969  1016  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
08-22 11:15:26.969  1016  1040 W TextServicesManagerService: no available spell checker services found
08-22 11:15:26.969  1016  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-22 11:15:26.989  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-22 11:15:26.989  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:26.989   258   258 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher,
,08-22 11:15:26.999   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 19.221ms
,08-22 11:15:26.999  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-22 11:15:26.999  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
,08-22 11:15:27.009  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,08-22 11:15:27.009  1016  1016 V EnterpriseBillingPolicy: uID is 10171
08-22 11:15:27.009  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-22 11:15:27.009  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-22 11:15:27.009  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-22 11:15:27.009  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:27.009  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-22 11:15:27.009  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-22 11:15:27.009  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-22 11:15:27.009  1819  1819 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-22 11:15:27.009  1819  1819 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-22 11:15:27.009  1819  1819 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-22 11:15:27.009  1819  1819 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-22 11:15:27.009  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-22 11:15:27.019  1016  3371 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-22 11:15:27.019   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 637us total 20.739ms
,08-22 11:15:27.029  1016  1487 D InputDispatcher: Focus entered window: 1498
,08-22 11:15:27.029  1819  1819 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-22 11:15:27.029  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 11:15:27.029  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-22 11:15:27.029  1498  1498 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-22 11:15:27.029  1819  1819 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-22 11:15:27.039  7764  7764 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:27.039  7764  7764 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:27.039  7751  7751 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 11:15:27.039  7751  7751 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-22 11:15:27.039  7751  7751 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-22 11:15:27.049  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-22 11:15:27.049  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-22 11:15:27.049  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-22 11:15:27.049  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-22 11:15:27.049  1498  1498 V ActivityThread: updateVisibility : ActivityRecord{1fcb1ad8 token=android.os.BinderProxy@1a84fb64 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-22 11:15:27.049  1498  1498 D Launcher.HomeView: onStop
,08-22 11:15:27.059  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:27.059  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:27.059  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-22 11:15:27.059  1016  1492 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-22 11:15:27.059  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:27.059  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:27.059  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:27.059  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:27.069  1016  7782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-22 11:15:27.069  1016  1492 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6774 uid 10171
,08-22 11:15:27.069  7751  7751 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:27.079  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 11:15:27.079  7784  7784 E Zygote  : MountEmulatedStorage()
08-22 11:15:27.079  7784  7784 I libpersona: KNOX_SDCARD checking this for 10001
08-22 11:15:27.079  7784  7784 E Zygote  : v2
08-22 11:15:27.079  7784  7784 I libpersona: KNOX_SDCARD not a persona
08-22 11:15:27.079  7784  7784 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:27.079  7784  7784 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:27.079  1016  1514 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-22 11:15:27.079  1016  1514 D SecContentProvider2: mCursor = null
08-22 11:15:27.079  7784  7784 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:27.079  1016  1016 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7784 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 11:15:27.089  1919  1919 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
08-22 11:15:27.089  1174  1174 I StatusBar: Icon Only
08-22 11:15:27.089  1016  1537 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
08-22 11:15:27.089  1174  1174 D PanelView: There is/are notification(s) 
08-22 11:15:27.089  1016  1537 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-22 11:15:27.099  1016  1537 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:27.099  1016  1537 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:27.099  1016  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-22 11:15:27.099  7751  7751 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-22 11:15:27.109  1016  1057 W art     : Suspending all threads took: 8.018ms
,08-22 11:15:27.119  7751  7751 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-22 11:15:27.119  7784  7784 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:27.119  7784  7784 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:27.129  1016  1041 W ActivityManager: mDVFSHelper.release()
,08-22 11:15:27.159  1016  1514 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-22 11:15:27.159  1016  1514 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-22 11:15:27.159  1016  1514 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:27.159  1016  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:27.159  1016  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-22 11:15:27.159  1016  3764 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 11:15:27.159  1016  1028 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 11:15:27.159  1981  2205 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-22 11:15:27.179  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{10acc3a5 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:144710
,08-22 11:15:27.179  1016  1057 I art     : Explicit concurrent mark sweep GC freed 85473(5MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 24MB/36MB, paused 12.835ms total 355.076ms
,08-22 11:15:27.189  6992  7801 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-22 11:15:27.189  6992  7801 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-22 11:15:27.189  6992  7801 I System.out: (HTTPLog)-Static: isShipBuild true
08-22 11:15:27.199  6992  7801 I System.out: (HTTPLog)-Thread-1265-646019568: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-22 11:15:27.199  6992  7801 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 11:15:27.199   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 11:15:27.199   278  1011 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,08-22 11:15:27.239  7254  7254 D WaitQueueForNetworkActivate: notifyNetworkActivated
08-22 11:15:27.239  1016  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-22 11:15:27.239  6992  7801 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-22 11:15:27.249  7158  7158 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:27.249  7158  7158 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-22 11:15:27.249  7158  7158 I DIAGMON_AGENT: ./extraInfo: "NG700"
08-22 11:15:27.249  7158  7158 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-22 11:15:27.259  7125  7125 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-22 11:15:27.259  7175  7175 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-22 11:15:27.259  7175  7175 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,08-22 11:15:27.259  7175  7175 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-22 11:15:27.269  7175  7175 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-22 11:15:27.269  7175  7175 I SA      : [OR] == isSIMCardReady false ==
,08-22 11:15:27.269  2756  7807 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-22 11:15:27.269  7175  7175 I SA      : [SCU] == networkStateCheck == true
,08-22 11:15:27.269  2756  7807 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-22 11:15:27.269  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:27.279  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:27.279  2756  7807 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-22 11:15:27.289  7175  7175 I SA      : [DM] getCountryCodeFromCSC : PL
,08-22 11:15:27.289  7175  7175 I SA      : isChinaCountryCode : false
08-22 11:15:27.299  7175  7175 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-22 11:15:27.299  7175  7175 I SA      : [OR] == networkStateCheck true ==
,08-22 11:15:27.299  6992  7801 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-22 11:15:27.319  7175  7175 I SA      : [OR] GetMyCountryZoneTask
,08-22 11:15:27.319  7175  7175 I SA      : [OR] onReceive END
,08-22 11:15:27.319  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 11:15:27.319  1016  1492 I ActivityManager: Killing 7202:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-22 11:15:27.329  1226  1226 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-22 11:15:27.339  2756  7807 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-22 11:15:27.339  2756  7807 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-22 11:15:27.339  2756  7807 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
08-22 11:15:27.339  2756  7807 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
08-22 11:15:27.339  2756  7807 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-22 11:15:27.349  2756  7807 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-22 11:15:27.349  1016  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-22 11:15:27.349  2756  7807 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
08-22 11:15:27.349  1016  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 11:15:27.349  1016  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 11:15:27.349  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:27.349  2756  7807 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-22 11:15:27.349  1016  1487 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,08-22 11:15:27.349  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
08-22 11:15:27.349  1016  1057 D PackageManager: delete codoeFile: 
,08-22 11:15:27.359  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:27.359  1016  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:27.359  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-22 11:15:27.359  1016  1057 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,08-22 11:15:27.359  1016  1057 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-22 11:15:27.369  1016  3767 D PersonaManager: isKioskContainerExistOnDevice
,08-22 11:15:27.369  2756  7807 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-22 11:15:27.369  7175  7811 I SA      : [SRS] prepareGetMyCountryZone
,08-22 11:15:27.369  1016  1057 D PackageManager: result of delete: 1{941866107}
08-22 11:15:27.369  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:27.379  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:27.379  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 11:15:27.379  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-22 11:15:27.379  7175  7811 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-22 11:15:27.379  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:27.379  7175  7811 I SA      : [SSP] query invoked
,08-22 11:15:27.389  1016  1537 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,08-22 11:15:27.389  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 11:15:27.389  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-22 11:15:27.389  1016  1537 D SecContentProvider2: mCursor = null
,08-22 11:15:27.389  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 11:15:27.389  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-22 11:15:27.389  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 11:15:27.389  1016  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-22 11:15:27.399  1016  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-22 11:15:27.399  7723  7723 D AndroidRuntime: Shutting down VM
,08-22 11:15:27.399  1016  1040 W libprocessgroup: failed to open /acct/uid_10121/pid_7094/cgroup.procs: No such file or directory
,08-22 11:15:27.399  7175  7811 I SA      : [TPMU] GetMccFromDB : null
,08-22 11:15:27.409  1016  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-22 11:15:27.409  1016  1057 D PackageManager: userId{-1}
08-22 11:15:27.409  1016  1057 D PackageManager: andCode{true}
,08-22 11:15:27.409  1016  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-22 11:15:27.409  7175  7811 I SA      : [SCU] getMccFromPreferece mcc = 260
08-22 11:15:27.409  7175  7811 I SA      : [LBE] isSupportCheckDomainRegion : false
08-22 11:15:27.409  7175  7811 I SA      : [TPM] isNoProxy(default) : true
,08-22 11:15:27.419  1016  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:27.419  1016  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:27.419  1016  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:27.419  1016  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:27.419  2756  7807 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-22 11:15:27.429  7175  7811 E File    : fail readDirectory() errno=2
,08-22 11:15:27.439  7814  7814 E Zygote  : MountEmulatedStorage()
08-22 11:15:27.439  7814  7814 E Zygote  : v2
08-22 11:15:27.439  7814  7814 I libpersona: KNOX_SDCARD checking this for 10003
,08-22 11:15:27.439  7814  7814 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 11:15:27.439  7814  7814 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:27.449  7814  7814 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 11:15:27.449  1016  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7814 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-22 11:15:27.449  1016  1214 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
08-22 11:15:27.449  7814  7814 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 11:15:27.449  1016  1214 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:27.449  1016  1214 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:27.449  1016  1214 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:27.449  1016  1214 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:27.469  7822  7822 E Zygote  : MountEmulatedStorage()
,08-22 11:15:27.469  7822  7822 E Zygote  : v2
,08-22 11:15:27.469  7822  7822 I libpersona: KNOX_SDCARD checking this for 10008
08-22 11:15:27.469  7822  7822 I libpersona: KNOX_SDCARD not a persona,
08-22 11:15:27.469  7822  7822 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:27.469  7822  7822 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 11:15:27.469  7822  7822 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-22 11:15:27.479  1016  1214 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7822 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 11:15:27.479  7814  7814 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:27.479  7814  7814 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:27.499  7822  7822 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 11:15:27.509  7822  7822 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:27.529  1016  1504 I ActivityManager: Killing 7238:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-22 11:15:27.549  1498  1498 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1a84fb64 time:145080
,08-22 11:15:27.599  7723  7723 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,08-22 11:15:27.629  1016  3768 I ActivityManager: Killing 6941:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,08-22 11:15:27.639  7822  7822 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-22 11:15:27.639  1016  1262 I ActivityManager: Killing 4318:com.google.process.gapps/u0a11 (adj 15): empty #21
,08-22 11:15:27.639  1016  3765 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
08-22 11:15:27.639  1016  3765 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-22 11:15:27.639  1016  3765 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:27.639  7822  7822 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-22 11:15:27.639  1016  3765 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-22 11:15:27.639  1016  3765 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-22 11:15:27.649  7822  7822 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-22 11:15:27.649  1016  3768 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 11:15:27.649  1016  3768 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-22 11:15:27.659  1016  3768 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:27.659  1016  3768 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 11:15:27.659  1016  3768 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 11:15:27.659  7822  7822 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-22 11:15:27.669   278  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 11:15:27.669   278  1011 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,08-22 11:15:27.669  7254  7254 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-22 11:15:27.669  2852  2852 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 22 11:15:27 GMT+02:00 2016
,08-22 11:15:27.669  1016  1492 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-22 11:15:27.669  1016  1492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-22 11:15:27.669  4824  4824 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-22 11:15:27.669  7254  7254 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,08-22 11:15:27.669  1016  1492 W ActivityManager: userId = 0, bbcId = -10000
08-22 11:15:27.669  1016  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 11:15:27.669  7254  7254 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,08-22 11:15:27.669  7254  7254 D InitializeManagerStateMachine: exit::IDLE
08-22 11:15:27.669  7254  7254 D InitializeManagerStateMachine: entry::NETWORK_CHECK
08-22 11:15:27.669  1016  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-22 11:15:27.679  7254  7254 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
,08-22 11:15:27.679  7254  7254 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-22 11:15:27.679  7254  7254 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
,08-22 11:15:27.679  7254  7254 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,08-22 11:15:27.679  7254  7254 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
,08-22 11:15:27.679  7254  7254 D InitializeManagerStateMachine: entry::SUCCESS
,08-22 11:15:27.679  7254  7254 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-22 11:15:27.679  4824  7271 I iu.UploadsManager: num queued entries: 0
,08-22 11:15:27.679  2852  2852 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-22 11:15:27.689  4824  7271 I iu.UploadsManager: num updated entries: 0
,08-22 11:15:27.689  1016  1428 W ActivityManager: ProcessRecord{3a8ddf83 4318:com.google.process.gapps/u0a11} is already killed
,08-22 11:15:27.689   255   255 E lowmemorykiller: Error writing /proc/4318/oom_score_adj; errno=22
08-22 11:15:27.689  1016  1428 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-22 11:15:27.689  4824  7271 I iu.SyncManager: NEXT; no task
08-22 11:15:27.689  1016  1428 I ActivityManager: Existing provider com.google.android.gsf/.gservices.GservicesProvider is crashing; detaching ProcessRecord{35b91feb 4824:com.google.android.gms/u0a11}
,08-22 11:15:27.689  2852  2852 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-22 11:15:27.689  1016  1428 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gsf
,08-22 11:15:27.699  2852  2852 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-22 11:15:27.699  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:27.699  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:27.699  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 11:15:27.699  1016  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 11:15:27.699  2852  2852 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-22 11:15:27.699  2852  7851 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-22 11:15:27.699  2852  7851 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-22 11:15:27.709  7852  7852 E Zygote  : MountEmulatedStorage(),
08-22 11:15:27.709  7852  7852 E Zygote  : v2
08-22 11:15:27.709  7852  7852 I libpersona: KNOX_SDCARD checking this for 10011
08-22 11:15:27.709  7852  7852 I libpersona: KNOX_SDCARD not a persona
,08-22 11:15:27.709  7852  7852 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 11:15:27.709  1016  1428 I ActivityManager: Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=7852 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
08-22 11:15:27.719  7852  7852 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 11:15:27.719  7254  7254 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-22 11:15:27.719  7254  7254 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-22 11:15:27.719  7254  7254 D InitializeManagerStateMachine: exit::SUCCESS,
08-22 11:15:27.719  7254  7254 D InitializeManagerStateMachine: entry::IDLE
08-22 11:15:27.719  7852  7852 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 11:15:27.719  2852  7851 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,08-22 11:15:27.719  2852  7851 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
08-22 11:15:27.719  1016  1029 I ActivityManager: Killing 7451:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-22 11:15:27.719  2852  7851 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,08-22 11:15:27.729  2852  7851 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,08-22 11:15:27.729  2852  7851 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-22 11:15:27.729  2852  2852 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-22 11:15:27.739  7852  7852 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 11:15:27.749  7852  7852 D ActivityThread: Added TimaKeyStore provider
,08-22 11:15:27.779  7852  7852 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-22 11:15:27.789  7852  7852 E SQLiteLog: (28) failed to open "/data/user/0/com.google.android.gsf/databases/gservices.db" with flag (131138) and mode_t (0) due to error (30)
,08-22 11:15:27.789  7852  7852 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:27.789  7852  7852 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:27.789  7852  7852 D AndroidRuntime: Shutting down VM
,08-22 11:15:27.789  7852  7852 E AndroidRuntime: FATAL EXCEPTION: main
08-22 11:15:27.789  7852  7852 E AndroidRuntime: Process: com.google.process.gapps, PID: 7852
08-22 11:15:27.789  7852  7852 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.content.ContentP,rovider.attachInfo(ContentProvider.java:1729)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-22 11:15:27.789  7852  7852 E AndroidRuntime: 	... 11 more
,08-22 11:15:27.789  1016  3768 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.process.gapps
,08-22 11:15:27.799  7852  7852 I Process : Sending signal. PID: 7852 SIG: 9
,08-22 11:15:27.799  1981  7849 I qtaguid : Tagging socket 57 with tag 1000040700000000{268436487,0} for uid -1, pid: 1981, getuid(): 10011
,08-22 11:15:27.799  1016  7867 E DropBoxManagerService: Can't write: system_app_crash
08-22 11:15:27.799  1016  7867 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop198.tmp: open failed: EROFS (Read-only file system)
08-22 11:15:27.799  1016  7867 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-22 11:15:27.799  1016  7867 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 11:15:27.799  1016  7867 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 11:15:27.799  1016  7867 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 11:15:27.799  1016  7867 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-22 11:15:27.799  1016  7867 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-22 11:15:27.799  1016  7867 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 11:15:27.799  1016  7867 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 11:15:27.799  1016  7867 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 11:15:27.799  1016  7867 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-22 11:15:27.799  1016  7867 E DropBoxManagerService: 	... 5 more
,08-22 11:15:27.819  1981  1981 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/ns.db" with flag (131138) and mode_t (0) due to error (30)
,08-22 11:15:27.829  1981  1981 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/ns.db'.
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1508)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at ivm.g(:com.google.android.gms:204)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at ivm.e(:com.google.android.gms:176)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at ivh.a(:com.google.android.gms:22519)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at oek.b(:com.google.android.gms:342)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at oeh.a(:com.google.android.gms:844)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at oei.handleMessage(:com.google.android.gms:13054)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 11:15:27.829  1981  1981 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-22 11:15:27.829  1981  1981 D AndroidRuntime: Shutting down VM
,08-22 11:15:27.869  1016  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-22 11:15:27.869  1016  1128 V NetworkStats: updateIfacesLocked()
,08-22 11:15:27.869  1016  1128 V NetworkStats: performPollLocked(flags=0x1)
08-22 11:15:27.869  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:27.869  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-22 11:15:27.869  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 11:15:27.879  1016  1128 V NetworkStats: performPollLocked() took 5ms
,08-22 11:15:27.879  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:27.879  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:27.879  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 11:15:27.879  1016  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]

```
