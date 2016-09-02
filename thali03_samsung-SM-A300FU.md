#### Test 83444050ceb1988_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main,
09-02 19:07:40.398   329   329 I ServiceManager: Waiting for service AtCmdFwd...
09-02 19:07:40.658  7215  7215 D AndroidRuntime: 
09-02 19:07:40.658  7215  7215 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-02 19:07:40.658  7215  7215 D AndroidRuntime: CheckJNI is OFF
09-02 19:07:40.658  7215  7215 D AndroidRuntime: readGMSProperty: start
09-02 19:07:40.658  7215  7215 D AndroidRuntime: readGMSProperty: already setted!!
09-02 19:07:40.658  7215  7215 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-02 19:07:40.658  7215  7215 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-02 19:07:40.658  7215  7215 D AndroidRuntime: readGMSProperty: end
09-02 19:07:40.658  7215  7215 D AndroidRuntime: addProductProperty: start
09-02 19:07:40.798  7215  7215 E AffinityControl: AffinityControl: registerfunction enter
09-02 19:07:40.828  7215  7215 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-02 19:07:40.838  1019  4273 E PersonaManagerService: inState():  stateMachine is null !!
09-02 19:07:40.838  1019  4273 I PersonaManagerService: PersonaId don't exist
09-02 19:07:40.838  1019  4273 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-02 19:07:40.848  1019  4273 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
09-02 19:07:40.858  1019  4273 W ActivityManager: mDVFSHelper.acquire()
09-02 19:07:40.858  1019  4273 D FocusedStackFrame: Set to : 0
09-02 19:07:40.868  1019  4273 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:40.868  1019  4273 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:40.868  1019  4273 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:40.868  1019  4273 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:40.868  1019  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-02 19:07:40.868  1019  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-02 19:07:40.878  1019  4273 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7226 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-02 19:07:40.878  1019  4273 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-02 19:07:40.878  1019  4273 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-02 19:07:40.878  1019  4273 D InputDispatcher: Focused application set to: xxxx
09-02 19:07:40.878  1019  4273 D InputDispatcher: Focus left window: 1487
09-02 19:07:40.878  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-02 19:07:40.888  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-02 19:07:40.888  7215  7215 D AndroidRuntime: Shutting down VM
09-02 19:07:40.888   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-02 19:07:40.888  7226  7226 E Zygote  : MountEmulatedStorage()
09-02 19:07:40.888  7226  7226 E Zygote  : v2
09-02 19:07:40.888  7226  7226 I libpersona: KNOX_SDCARD checking this for 10170
09-02 19:07:40.888  7226  7226 I libpersona: KNOX_SDCARD not a persona
09-02 19:07:40.888  7226  7226 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 19:07:40.898  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-02 19:07:40.898  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
09-02 19:07:40.898  7226  7226 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 19:07:40.898  7226  7226 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-02 19:07:40.928  7226  7226 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 19:07:40.928  7226  7226 D ActivityThread: Added TimaKeyStore provider
09-02 19:07:40.928  1019  1338 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-02 19:07:40.928  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-02 19:07:40.948  1019  1338 D PersonaManager: isKioskContainerExistOnDevice
09-02 19:07:40.958  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-02 19:07:40.978   258   797 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
09-02 19:07:40.978   258   447 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
09-02 19:07:40.988  1487  1487 V ActivityThread: updateVisibility : ActivityRecord{198659b token=android.os.BinderProxy@2032f032 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-02 19:07:40.988  1487  1487 D Launcher: onTrimMemory. Level: 20
09-02 19:07:41.048  7226  7226 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-02 19:07:41.068  7226  7226 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 310-312)
09-02 19:07:41.068  7226  7226 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-02 19:07:41.088  7215  7215 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-02 19:07:41.098  7226  7226 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {355d84af}
,09-02 19:07:41.098  7226  7226 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-02 19:07:41.098  7226  7226 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-02 19:07:41.128  7226  7226 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-02 19:07:41.128  7226  7226 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 19:07:41.138  7226  7226 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-02 19:07:41.148  7226  7226 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-02 19:07:41.148  7226  7226 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-02 19:07:41.148  7226  7226 I Adreno-EGL: Build Date: 04/06/15 Mon
09-02 19:07:41.148  7226  7226 I Adreno-EGL: Local Branch: 
09-02 19:07:41.148  7226  7226 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-02 19:07:41.148  7226  7226 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-02 19:07:41.148  7226  7226 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-02 19:07:41.208  7226  7226 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-02 19:07:41.228  7226  7226 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-02 19:07:41.228  7226  7226 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-02 19:07:41.238  7226  7226 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-02 19:07:41.238  7226  7226 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-02 19:07:41.338  7226  7226 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 19:07:41.348  7226  7226 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-02 19:07:41.358  7226  7226 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-02 19:07:41.358  7226  7226 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-02 19:07:41.368  7226  7226 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-02 19:07:41.368  7226  7226 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 19:07:41.368  7226  7226 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 19:07:41.398   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 19:07:41.448  1019  1044 W ActivityManager: Activity pause timeout for ActivityRecord{1e524414 u0 com.test.thalitest/.MainActivity t164}
,09-02 19:07:41.468  7226  7266 D OpenGLRenderer: Render dirty regions requested: true
,09-02 19:07:41.468  1019  1338 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-02 19:07:41.468  1019  1338 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-02 19:07:41.468  1019  1338 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-02 19:07:41.468  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-02 19:07:41.468  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,09-02 19:07:41.478  7226  7253 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-02 19:07:41.478  7226  7226 V ActivityThread: updateVisibility : ActivityRecord{331b068f token=android.os.BinderProxy@1f9c41f0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true,
,09-02 19:07:41.488  7226  7226 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-02 19:07:41.488  7226  7226 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-02 19:07:41.498   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-02 19:07:41.508  1019  4259 D InputDispatcher: Focus entered window: 7226
,09-02 19:07:41.508  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-02 19:07:41.508  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
09-02 19:07:41.508  7226  7226 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-02 19:07:41.508  7226  7266 I OpenGLRenderer: Initialized EGL, version 1.4
,09-02 19:07:41.518  7226  7266 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-02 19:07:41.518  7226  7266 D OpenGLRenderer: Enabling debug mode 0
,09-02 19:07:41.538  1019  4273 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-02 19:07:41.538  1178  1178 D PanelView: There is/are notification(s) 
,09-02 19:07:41.538  1019  7270 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-02 19:07:41.558  1019  1049 I ActivityManager: Displayed Component not be shown by security: +602ms (total +42s352ms)
,09-02 19:07:41.558  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e524414 u0 com.test.thalitest/.MainActivity t164} time:160801
09-02 19:07:41.558  1019  1049 W ActivityManager: mDVFSHelper.release()
,09-02 19:07:41.558  7226  7226 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-02 19:07:41.558  7226  7226 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1f9c41f0 time:160807
09-02 19:07:41.558   258   797 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-02 19:07:41.568   258   443 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,09-02 19:07:41.588  1869  1869 I SamsungIME: getCurrentCandidateView
,09-02 19:07:41.638  7226  7226 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7226
,09-02 19:07:41.678  1869  1869 D SamsungIME: Dismiss ExpandCandiate
,09-02 19:07:41.768  7226  7226 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-02 19:07:41.778   288   288 E SMD     : DCD OFF,
,09-02 19:07:41.838  1869  1869 I SamsungIME: getDebugLevel  : 0x4f4c
,09-02 19:07:41.878  1869  1869 I SamsungIME: getDebugLevel  : 0x4f4c
,09-02 19:07:41.888  1869  1869 I SamsungIME: KeybaordView init() : load resources
,09-02 19:07:41.908  7226  7272 D jxcore_app_log: JniHelper::setJavaVM(0xb85222b0), pthread_self() = -1196746344
,09-02 19:07:41.908  1869  1869 I SamsungIME: getCurrentKeyboard
09-02 19:07:41.908  1869  1869 I SamsungIME: getTextKeyboard
,09-02 19:07:41.908  7226  7272 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-02 19:07:41.908  7226  7272 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-02 19:07:41.908  7226  7272 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-02 19:07:41.908  7226  7272 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-02 19:07:41.908  7226  7272 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-02 19:07:41.918  7226  7272 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f5d7bdd added. We now have 1 listener(s)
,09-02 19:07:41.918  7226  7272 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,09-02 19:07:41.918  7226  7272 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-02 19:07:41.918  7226  7272 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 19:07:41.918  7226  7272 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 19:07:41.928  7226  7272 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-02 19:07:41.928  7226  7272 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-02 19:07:41.928  7226  7272 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-02 19:07:41.928  7226  7272 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
09-02 19:07:41.928  7226  7272 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-02 19:07:41.928  7226  7272 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-02 19:07:41.928  7226  7272 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-02 19:07:41.928  7226  7272 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-02 19:07:41.928  7226  7272 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-02 19:07:41.928  7226  7272 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-02 19:07:41.928  7226  7272 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-02 19:07:41.928  7226  7272 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-02 19:07:41.928  7226  7272 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-02 19:07:41.928  7226  7272 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-02 19:07:41.928  7226  7272 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35fc0720 added. We now have 1 listener(s)
09-02 19:07:41.928  7226  7272 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:07:41.928  7226  7272 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 19:07:41.928  7226  7272 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-02 19:07:41.928  7226  7272 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-02 19:07:41.928  7226  7272 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-02 19:07:41.928  7226  7272 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-02 19:07:41.938  7226  7272 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:07:41.938  7226  7272 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,09-02 19:07:41.948  7226  7272 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-02 19:07:41.948  7226  7272 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:41.948  7226  7272 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:41.948  7226  7272 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:41.948  7226  7272 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:41.948  7226  7272 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:41.948  7226  7272 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:41.948  7226  7272 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:41.948  7226  7272 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:07:41.948  7226  7272 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-02 19:07:41.948  7226  7272 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:07:41.948  7226  7272 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-02 19:07:41.948  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:41.948  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:41.958  1869  1869 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-02 19:07:41.978  7226  7226 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-02 19:07:42.398   329   329 I ServiceManager: Waiting for service AtCmdFwd...
09-02 19:07:42.468  7226  7279 W jxcore-log: Initializing JXcore engine
09-02 19:07:42.468  7226  7279 W jxcore-log: JXcore engine is ready
09-02 19:07:42.528  2012  2012 E audit   : type=1400 msg=audit(1472836062.528:205): avc:  denied  { ioctl } for  pid=7279 comm="Thread-1360" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-02 19:07:42.528  2012  2012 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-02 19:07:42.528  2012  2012 E audit   : type=1300 msg=audit(1472836062.528:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9e07a8f8 items=0 ppid=315 ppcomm=main pid=7279 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1360" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-02 19:07:42.528  2012  2012 E audit   : type=1320 msg=audit(1472836062.528:205): 
09-02 19:07:42.538  7226  7279 W jxcore-log: Starting JXcore engine
09-02 19:07:42.648  7226  7279 W jxcore-log: Platform android
09-02 19:07:42.648  7226  7279 W jxcore-log: 
09-02 19:07:42.648  7226  7279 W jxcore-log: Process ARCH arm
09-02 19:07:42.648  7226  7279 W jxcore-log: 
,09-02 19:07:42.848  7226  7279 I jxcore-log: JXcore Cordova bridge is ready!,
09-02 19:07:42.848  7226  7279 I jxcore-log: 
09-02 19:07:42.848  7226  7279 W jxcore-log: JXcore engine is started
,09-02 19:07:42.858  7226  7272 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-02 19:07:42.858  7226  7226 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-02 19:07:43.398   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 19:07:43.448  1019  3349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-02 19:07:44.088  1019  3325 D SSRM:n  : SIOP:: AP = 300
,09-02 19:07:44.398   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 19:07:44.778   288   288 E SMD     : DCD OFF,
,09-02 19:07:45.398   329   329 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,09-02 19:07:46.988  1019  1338 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-02 19:07:46.988  1019  1338 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4282, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-02 19:07:46.988  1019  1338 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-02 19:07:46.988  1019  1338 D BatteryService: stay LED for charging
09-02 19:07:46.988  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-02 19:07:46.988  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-02 19:07:46.998  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-02 19:07:46.998  1019  1019 I MotionRecognitionService: Plugged
09-02 19:07:46.998  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
09-02 19:07:46.998  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-02 19:07:46.998  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-02 19:07:47.008  3188  3188 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
09-02 19:07:47.008  3188  3330 D HeadsetStateMachine: Disconnected process message: 10
,09-02 19:07:47.018  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-02 19:07:47.018  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-02 19:07:47.018  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-02 19:07:47.778   288   288 E SMD     : DCD OFF
,09-02 19:07:48.658  1019  1051 I PowerManagerService: [PWL] Off : 105s ago
,09-02 19:07:48.818  1019  1315 E Watchdog: !@Sync 5,
,09-02 19:07:50.778   288   288 E SMD     : DCD OFF,
,09-02 19:07:50.908  1019  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-02 19:07:50.958  1758  3116 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-02 19:07:53.778   288   288 E SMD     : DCD OFF
,09-02 19:07:54.118  1019  3325 D SSRM:n  : SIOP:: AP = 320
,09-02 19:07:55.228  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
09-02 19:07:55.228  7226  7279 I jxcore-log: 
,09-02 19:07:55.228  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
09-02 19:07:55.228  7226  7279 I jxcore-log: 
,09-02 19:07:55.238  7226  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:55.238  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:55.238  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:55.238  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:55.238  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:55.238  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:55.238  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:55.238  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:07:55.238  7226  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 19:07:55.238  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-02 19:07:55.238  7226  7279 I jxcore-log: 
,09-02 19:07:55.248  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-02 19:07:55.248  7226  7279 I jxcore-log: 
,09-02 19:07:55.908  7226  7279 D executeNativeTests: Running unit tests
,09-02 19:07:55.998  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:07:55.998  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d added. We now have 2 listener(s)
,09-02 19:07:55.998  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-02 19:07:55.998  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:07:55.998  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:07:55.998  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:55.998  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 added. We now have 2 listener(s)
09-02 19:07:55.998  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:07:55.998  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 19:07:55.998  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:07:56.008  7226  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:56.008  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:56.008  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:56.008  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:56.008  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:56.008  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:56.008  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:56.008  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:07:56.008  7226  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 19:07:56.008  7226  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:07:56.008  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:56.008  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-02 19:07:56.008  7226  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 19:07:56.008  7226  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-02 19:07:56.018  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:56.018  7226  7279 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-02 19:07:56.018  7226  7279 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 19:07:56.018  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 19:07:56.018  7226  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 19:07:56.018  7226  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-02 19:07:56.018  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:07:56.018  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.018  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:56.018  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.018  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.018  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:56.018  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:07:56.018  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d removed from the list
09-02 19:07:56.018  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.018  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 removed from the list
09-02 19:07:56.018  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.018  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.018  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.018  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:56.018  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 19:07:56.018  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:56.018  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.018  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
,09-02 19:07:56.018  7226  7279 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-02 19:07:56.018  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:56.018  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.018  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:56.018  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.018  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.018  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.018  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.018  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.018  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
,09-02 19:07:56.018  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.018  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.018  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.018  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.018  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.018  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:56.018  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:56.018  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.018  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
,09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 19:07:56.028  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:56.028  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.028  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:56.028  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.028  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.028  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.028  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.028  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.028  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.028  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.028  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.028  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.028  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.028  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.028  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:56.028  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:56.028  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.028  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.028  7226  7279 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 19:07:56.028  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:56.038  7226  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:56.038  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:56.038  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:56.038  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:56.038  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:56.038  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:56.038  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:56.038  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 19:07:56.038  7226  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:56.038  7226  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:07:56.038  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:07:56.038  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:07:56.038  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:07:56.038  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:56.038  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 19:07:56.038  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:56.048  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 19:07:56.048  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:56.048  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 19:07:56.058  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 19:07:56.058  7226  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-02 19:07:56.058  7226  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-02 19:07:56.058  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 19:07:56.058  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 19:07:56.058  7226  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 19:07:56.068  3188  3326 D BtGatt.GattService: registerClient() - UUID=c4bcebad-565a-4343-be40-8fc37955a951
,09-02 19:07:56.118  3188  3265 D BtGatt.GattService: onClientRegistered() - UUID=c4bcebad-565a-4343-be40-8fc37955a951, clientIf=6
,09-02 19:07:56.118  7226  7235 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-02 19:07:56.118  3188  3202 D BtGatt.GattService: start scan with filters
,09-02 19:07:56.118  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 19:07:56.118  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 19:07:56.118  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 19:07:56.118  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 19:07:56.118  3188  3329 D BtGatt.ScanManager: handling starting scan
,09-02 19:07:56.118  3188  3329 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:07:56.118  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:07:56.118  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 19:07:56.118  7226  7226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:07:56.128  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 19:07:56.128  3188  3265 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-02 19:07:56.128  7226  7279 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 19:07:56.128  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:56.128  3188  3329 D BtGatt.ScanManager: allow scan with filters
09-02 19:07:56.128  3188  3329 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-02 19:07:56.128  3188  3329 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-02 19:07:56.128  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:07:56.128  7226  7279 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 19:07:56.128  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.128  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 19:07:56.128  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.128  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-02 19:07:56.128  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 19:07:56.128  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 19:07:56.128  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:07:56.128  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-02 19:07:56.138  3188  3265 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-02 19:07:56.138  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:56.138  3188  3329 D BtGatt.ScanManager: Starting BLE batch scan
09-02 19:07:56.138  3188  3329 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-02 19:07:56.138  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-02 19:07:56.138  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 19:07:56.138  3188  3352 D BtGatt.GattService: stopScan() - queue size =1
,09-02 19:07:56.138  3188  3326 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 19:07:56.148  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-02 19:07:56.148  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 19:07:56.148  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 19:07:56.148  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 19:07:56.148  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 19:07:56.148  3188  3265 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-02 19:07:56.148  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:56.148  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:07:56.148  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 19:07:56.148  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 19:07:56.148  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 19:07:56.148  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:56.148  7226  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:07:56.148  7226  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:07:56.148  7226  7226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:07:56.148  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.148  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.148  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:56.148  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.148  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.148  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.148  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.148  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.148  7226  7279 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-02 19:07:56.158  3188  3265 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-02 19:07:56.158  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:56.158  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:07:56.158  3188  3329 D BtGatt.ScanManager: filter size is 1
,09-02 19:07:56.158  3188  3329 D BtGatt.ScanManager: delete FilterIndex - 3
,09-02 19:07:56.168  7226  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:56.168  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:56.168  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:56.168  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:56.168  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:56.168  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:56.168  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:56.168  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:07:56.168  3188  3265 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-02 19:07:56.168  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:56.168  3188  3329 D BtGatt.ScanManager: stopping BLe Batch
,09-02 19:07:56.168  7226  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 19:07:56.168  7226  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:07:56.178  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:07:56.178  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:07:56.178  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:07:56.178  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:56.178  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 19:07:56.178  3188  3265 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-02 19:07:56.178  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:56.178  3188  3329 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 19:07:56.178  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:56.178  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 19:07:56.178  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:56.188  3188  3265 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-02 19:07:56.188  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:56.188  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 19:07:56.188  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 19:07:56.188  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 19:07:56.188  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 19:07:56.188  7226  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 19:07:56.198  3188  3199 D BtGatt.GattService: registerClient() - UUID=c524a0dd-7040-4437-96f2-a29c6977067e
,09-02 19:07:56.238  3188  3265 D BtGatt.GattService: onClientRegistered() - UUID=c524a0dd-7040-4437-96f2-a29c6977067e, clientIf=6
,09-02 19:07:56.238  7226  7234 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-02 19:07:56.238  3188  3352 D BtGatt.GattService: start scan with filters
09-02 19:07:56.238  3188  3329 D BtGatt.ScanManager: handling starting scan
09-02 19:07:56.238  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 19:07:56.238  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 19:07:56.238  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 19:07:56.238  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 19:07:56.238  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:07:56.248  7226  7226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 19:07:56.248  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 19:07:56.248  3188  3265 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-02 19:07:56.248  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:56.248  3188  3329 D BtGatt.ScanManager: allow scan with filters
09-02 19:07:56.248  3188  3329 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 19:07:56.248  3188  3329 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-02 19:07:56.248  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-02 19:07:56.258  3188  3265 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-02 19:07:56.258  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:56.258  3188  3329 D BtGatt.ScanManager: Starting BLE batch scan
09-02 19:07:56.258  3188  3329 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-02 19:07:56.258  7226  7279 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 19:07:56.268  3188  3265 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-02 19:07:56.268  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:56.268  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:56.268  7226  7279 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 19:07:56.268  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.268  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 19:07:56.268  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.268  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 19:07:56.268  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 19:07:56.268  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-02 19:07:56.268  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:07:56.268  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-02 19:07:56.268  3188  3265 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-02 19:07:56.268  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:56.278  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 19:07:56.278  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 19:07:56.278  3188  3326 D BtGatt.GattService: stopScan() - queue size =1
,09-02 19:07:56.278  3188  3329 D BtGatt.ScanManager: filter size is 1
,09-02 19:07:56.278  3188  3329 D BtGatt.ScanManager: delete FilterIndex - 4
,09-02 19:07:56.278  3188  3199 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 19:07:56.278  3188  3265 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-02 19:07:56.288  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:07:56.288  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 19:07:56.288  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 19:07:56.288  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 19:07:56.288  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 19:07:56.288  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:56.288  3188  3329 D BtGatt.ScanManager: stopping BLe Batch
,09-02 19:07:56.288  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:07:56.288  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 19:07:56.288  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 19:07:56.288  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 19:07:56.288  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:07:56.298  3188  3265 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
09-02 19:07:56.298  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:56.298  3188  3329 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 19:07:56.298  3188  3265 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-02 19:07:56.298  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:56.298  7226  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 19:07:56.298  7226  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:07:56.298  7226  7226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:07:56.298  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.298  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.298  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:07:56.298  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.298  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.298  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.298  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.298  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.298  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.298  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:56.298  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:56.298  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 19:07:56.298  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.298  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
,09-02 19:07:56.298  7226  7279 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-02 19:07:56.308  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:07:56.308  7226  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:56.308  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:56.308  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:56.308  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:56.308  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:07:56.308  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:56.308  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:56.308  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:07:56.308  7226  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 19:07:56.308  7226  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:07:56.318  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:56.318  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:56.318  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 19:07:56.318  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:07:56.318  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:07:56.318  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:07:56.318  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 19:07:56.328  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 19:07:56.328  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 19:07:56.328  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 19:07:56.328  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 19:07:56.338  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 19:07:56.338  7226  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 19:07:56.338  3188  3352 D BtGatt.GattService: registerClient() - UUID=24537eee-891e-4b48-9402-91b125afd1e6
,09-02 19:07:56.378  3188  3265 D BtGatt.GattService: onClientRegistered() - UUID=24537eee-891e-4b48-9402-91b125afd1e6, clientIf=6
,09-02 19:07:56.378  7226  7235 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-02 19:07:56.378  3188  3202 D BtGatt.GattService: start scan with filters
,09-02 19:07:56.378  3188  3329 D BtGatt.ScanManager: handling starting scan
,09-02 19:07:56.378  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 19:07:56.378  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 19:07:56.378  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 19:07:56.378  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 19:07:56.388  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:07:56.388  7226  7226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 19:07:56.388  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 19:07:56.388  3188  3265 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-02 19:07:56.388  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:56.388  3188  3329 D BtGatt.ScanManager: allow scan with filters
,09-02 19:07:56.388  3188  3329 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 19:07:56.388  3188  3329 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
09-02 19:07:56.388  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 19:07:56.388  7226  7279 I io.jxcore.node.ConnectionHelper: start: OK
,09-02 19:07:56.388  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:07:56.388  7226  7279 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 19:07:56.388  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.388  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 19:07:56.388  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.388  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 19:07:56.388  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 19:07:56.388  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 19:07:56.388  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:07:56.388  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 19:07:56.388  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 19:07:56.388  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 19:07:56.398  3188  3352 D BtGatt.GattService: stopScan() - queue size =1,
,09-02 19:07:56.398  3188  3265 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-02 19:07:56.398  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:07:56.398  3188  3329 D BtGatt.ScanManager: Starting BLE batch scan
09-02 19:07:56.398  3188  3329 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-02 19:07:56.398  3188  3202 D BtGatt.GattService: unregisterClient() - clientIf=6
09-02 19:07:56.398  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:07:56.398  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-02 19:07:56.398  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 19:07:56.398  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 19:07:56.398  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 19:07:56.398  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
09-02 19:07:56.398  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 19:07:56.398  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-02 19:07:56.398  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 19:07:56.398  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:07:56.398  3188  3265 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-02 19:07:56.398  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:56.398  7226  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 19:07:56.398  7226  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:07:56.398  7226  7226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:07:56.398  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:56.398  7226  7279 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 19:07:56.398  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 19:07:56.398  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:56.398  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.398  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.398  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:07:56.398  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.398  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.398  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.398  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 19:07:56.398  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.398  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.398  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:07:56.408  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.408  7226  7279 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-02 19:07:56.408  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:56.408  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.408  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.408  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.408  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.408  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:07:56.408  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.408  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.408  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.408  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.408  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:07:56.408  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.408  3188  3265 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-02 19:07:56.408  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.408  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.408  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 19:07:56.408  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:07:56.408  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.408  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 19:07:56.408  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.408  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.408  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
,09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:07:56.408  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
,09-02 19:07:56.408  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.408  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.408  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.408  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:07:56.408  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.408  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list,
09-02 19:07:56.408  3188  3329 D BtGatt.ScanManager: filter size is 1
09-02 19:07:56.408  3188  3329 D BtGatt.ScanManager: delete FilterIndex - 5
09-02 19:07:56.408  7226  7279 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-02 19:07:56.408  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:07:56.408  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.408  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 19:07:56.408  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.408  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.408  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.408  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.408  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.408  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.408  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.408  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.408  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:56.408  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.418  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.418  7226  7279 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-02 19:07:56.418  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:56.418  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.418  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:56.418  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.418  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.418  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.418  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.418  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.418  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.418  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.418  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.418  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.418  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.418  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.418  3188  3265 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-02 19:07:56.418  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:56.418  3188  3329 D BtGatt.ScanManager: stopping BLe Batch
09-02 19:07:56.418  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:56.418  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,09-02 19:07:56.418  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.418  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.418  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-02 19:07:56.418  7226  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 19:07:56.418  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 19:07:56.418  7226  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-02 19:07:56.418  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 19:07:56.418  7226  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 19:07:56.418  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:56.418  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.418  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-02 19:07:56.418  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.418  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.418  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.418  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.418  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.418  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.418  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.418  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.418  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.418  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-02 19:07:56.418  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.418  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:56.418  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:56.418  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.418  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.418  7226  7279 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:07:56.418  7226  7279 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 19:07:56.418  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 19:07:56.418  3188  3265 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-02 19:07:56.418  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:56.418  3188  3329 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-02 19:07:56.418  7226  7279 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:07:56.418  7226  7279 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-02 19:07:56.418  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-02 19:07:56.418  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 19:07:56.418  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 19:07:56.418  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 19:07:56.418  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-02 19:07:56.418  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 19:07:56.418  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 19:07:56.418  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 19:07:56.428  7226  7279 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-02 19:07:56.428  7226  7279 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 19:07:56.428  7226  7279 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-02 19:07:56.428  7226  7279 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:07:56.428  7226  7279 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 19:07:56.428  7226  7279 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-02 19:07:56.428  7226  7279 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 19:07:56.428  7226  7279 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 19:07:56.428  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-02 19:07:56.428  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-02 19:07:56.428  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-02 19:07:56.428  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-02 19:07:56.428  3188  3265 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-02 19:07:56.428  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:07:56.428  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-02 19:07:56.428  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-02 19:07:56.428  7226  7279 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-02 19:07:56.428  7226  7279 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-02 19:07:56.428  7226  7279 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-02 19:07:56.428  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:56.428  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.428  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:56.428  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.428  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:07:56.428  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.428  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-02 19:07:56.428  7226  7289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1424)
09-02 19:07:56.428  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.428  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:07:56.428  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.428  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.428  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.428  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.428  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:07:56.428  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.428  7226  7290 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1424
,09-02 19:07:56.428  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:56.428  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:56.428  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.428  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
,09-02 19:07:56.428  7226  7279 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-02 19:07:56.438  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:56.438  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.438  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:56.438  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.438  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.438  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.438  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.438  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.438  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.438  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.438  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.438  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.438  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.438  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:56.438  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:56.438  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:56.438  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:07:56.438  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
,09-02 19:07:56.438  7226  7279 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-02 19:07:56.438  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:56.438  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.438  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 19:07:56.438  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.438  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.438  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.438  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.438  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.438  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.438  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.438  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.438  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.438  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.438  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:56.438  7226  7289 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,09-02 19:07:56.438  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:56.438  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:56.438  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.438  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.438  7226  7289 D BluetoothSocket: connect(): myUserId = 0
09-02 19:07:56.438  7226  7289 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:07:56.438  7226  7279 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-02 19:07:56.438  7226  7279 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-02 19:07:56.438  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 19:07:56.438  7226  7279 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-02 19:07:56.438  7226  7279 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 19:07:56.438  7226  7279 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-02 19:07:56.438  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 19:07:56.438  7226  7279 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-02 19:07:56.438  7226  7279 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 19:07:56.438  7226  7279 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 19:07:56.438  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-02 19:07:56.438  7226  7279 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-02 19:07:56.438  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:56.438  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.438  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:56.438  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.438  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.438  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.438  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
,09-02 19:07:56.438  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.438  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.438  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.438  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.438  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.438  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.438  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:56.438  3188  3326 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 19:07:56.448  7226  7289 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.448  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
,09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.448  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.448  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.448  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.448  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.448  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.448  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.448  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.448  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.448  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.448  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.448  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.448  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:56.448  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.448  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.448  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.448  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.448  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.448  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.448  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.448  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.448  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:5,6.448  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.448  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:07:56.448  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
,09-02 19:07:56.448  7226  7279 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-02 19:07:56.448  7226  7279 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-02 19:07:56.448  7226  7279 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 19:07:56.448  7226  7226 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-02 19:07:56.448  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-02 19:07:56.448  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.448  7226  7279 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-02 19:07:56.448  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.448  7226  7226 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-02 19:07:56.448  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-02 19:07:56.448  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:07:56.448  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 19:07:56.448  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.448  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.448  7226  7291 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-02 19:07:56.448  7226  7291 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-02 19:07:56.458  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:07:56.458  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.458  7226  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:07:56.458  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:56.458  7226  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:07:56.458  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.458  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:56.458  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.458  7226  7226 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-02 19:07:56.458  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.458  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.458  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.458  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.458  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.458  7226  7226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:07:56.458  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.458  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.458  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.458  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.458  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:56.458  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:56.458  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:56.458  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.458  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
,09-02 19:07:56.458  7226  7279 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-02 19:07:56.458  7226  7279 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 19:07:56.458  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 19:07:56.458  7226  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 19:07:56.458  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:56.458  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.458  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:56.458  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.458  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.458  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.458  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.458  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.458  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.458  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.458  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.458  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.458  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.458  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:56.458  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 19:07:56.458  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:56.458  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.458  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
,09-02 19:07:56.458  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:07:56.458  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.458  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:56.468  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.468  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.468  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.468  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.468  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.468  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.468  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.468  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.468  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.468  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.468  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:56.468  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:56.468  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:56.468  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.468  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
,09-02 19:07:56.468  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:07:56.468  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:07:56.468  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:07:56.468  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:07:56.468  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.468  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.468  7226  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2106216d not in the list
09-02 19:07:56.468  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.468  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
09-02 19:07:56.468  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:07:56.468  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.468  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:07:56.468  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:07:56.468  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:07:56.468  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:07:56.468  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:07:56.468  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:07:56.468  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3519a1a2 not in the list
,09-02 19:07:56.468  7226  7279 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-02 19:07:56.468  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 19:07:56.468  7226  7279 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-02 19:07:56.468  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 19:07:56.468  7226  7279 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-02 19:07:56.468  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-02 19:07:56.468  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 19:07:56.468  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-02 19:07:56.468  7226  7279 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-02 19:07:56.468  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 19:07:56.468  7226  7279 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-02 19:07:56.468  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 19:07:56.468  7226  7279 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-02 19:07:56.468  7226  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-02 19:07:56.468  7226  7279 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-02 19:07:56.468  7226  7279 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-02 19:07:56.468  7226  7279 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-02 19:07:56.468  7226  7279 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-02 19:07:56.468  7226  7279 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-02 19:07:56.468  7226  7279 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-02 19:07:56.468  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:56.468  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3980b7b4 added. We now have 2 listener(s)
09-02 19:07:56.468  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:07:56.478  7226  7279 D BluetoothAdapter: enable()
,09-02 19:07:56.478  7226  7279 D BluetoothAdapter: enable(): BT is already enabled..!
,09-02 19:07:56.478  1019  1338 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-02 19:07:56.478  1019  1338 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-02 19:07:56.478  1019  1338 D SecContentProvider2: mCursor = null
,09-02 19:07:56.478  1019  1338 D WifiService: setWifiEnabled: true pid=7226, uid=10170
,09-02 19:07:56.478  1019  1338 W ActivityManager: Permission Denial: getCurrentUser() from pid=7226, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-02 19:07:56.488  1019  1338 W WifiService: Failed getting userId using ActivityManagerNative
09-02 19:07:56.488  1019  1338 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7226, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-02 19:07:56.488  1019  1338 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-02 19:07:56.488  1019  1338 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-02 19:07:56.488  1019  1338 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-02 19:07:56.488  1019  1338 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-02 19:07:56.488  1019  1338 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-02 19:07:56.488  1019  1338 D SettingsProvider: name = wifi_on
09-02 19:07:56.488  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:07:56.488  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cff3fdd added. We now have 3 listener(s)
09-02 19:07:56.488  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:07:56.488  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:07:56.488  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11b752 added. We now have 4 listener(s)
09-02 19:07:56.488  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:07:56.498  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:07:56.498  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8d23a23 added. We now have 5 listener(s)
09-02 19:07:56.498  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:07:56.498  1019  1485 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-02 19:07:56.498  1019  1485 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-02 19:07:56.498  1019  1485 D SecContentProvider2: mCursor = null
,09-02 19:07:56.498  1019  1485 D WifiService: setWifiEnabled: false pid=7226, uid=10170
,09-02 19:07:56.498  1019  1485 D SettingsProvider: name = wifi_on
,09-02 19:07:56.508  7226  7279 D BluetoothAdapter: disable()
,09-02 19:07:56.508  1019  1505 D SettingsProvider: name = bluetooth_on
09-02 19:07:56.508  1019  1127 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-02 19:07:56.508  1376  1376 I wpa_supplicant: reset timer : RESET_TIMER 0
09-02 19:07:56.508  1376  1376 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-02 19:07:56.508  1376  1376 I wpa_supplicant: P2P: Current p2p state = IDLE
09-02 19:07:56.508  1376  1376 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-02 19:07:56.518  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-02 19:07:56.518  1019  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
09-02 19:07:56.518  3188  3262 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-02 19:07:56.518  3188  3262 D BluetoothAdapterProperties: Setting state to 13
09-02 19:07:56.518  3188  3262 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-02 19:07:56.518  3188  3262 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 19:07:56.518  1376  1376 I wpa_supplicant: Scan aborted because the firmware maybe busy.
09-02 19:07:56.518  3188  3262 D BluetoothAdapterService: updateAdapterState state is 13
09-02 19:07:56.518  1376  1376 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.,
09-02 19:07:56.518  1376  1376 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
,09-02 19:07:56.518  1019  1338 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:07:56.518  1019  1338 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 19:07:56.528  1019  1338 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:56.528  1019  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:56.528  1019  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:07:56.528  3188  3188 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-02 19:07:56.528  3188  3262 D BluetoothAdapterService: Autoconnection is available 
,09-02 19:07:56.528  3188  3262 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-02 19:07:56.528  3188  3262 D BluetoothAdapterService: terminating service from this receiver
09-02 19:07:56.528  3188  3188 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@28548f4e, channel: 19, state: LISTENING
,09-02 19:07:56.528  3188  3188 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@28548f4e, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36d80776, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@13fef86fmSocket: android.net.LocalSocket@81bc97c impl:android.net.LocalSocketImpl@3d20c205 fd:FileDescriptor[80]
09-02 19:07:56.528  3188  3188 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@81bc97c impl:android.net.LocalSocketImpl@3d20c205 fd:FileDescriptor[80]
,09-02 19:07:56.528  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-02 19:07:56.528  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-02 19:07:56.528  7226  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:07:56.528  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:56.528  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:56.528  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:56.528  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:07:56.528  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:56.528  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:56.528  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:07:56.528  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:56.528  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:56.528  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
09-02 19:07:56.528  3188  3262 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 19:07:56.528  3188  3262 D BluetoothAdapterProperties: mDiscovering is false
,09-02 19:07:56.528  1019  1136 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-02 19:07:56.528  3188  3262 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-02 19:07:56.538  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:56.538  7226  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 19:07:56.538  7226  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:07:56.538  4850  4850 D BluetoothPbap: Proxy object disconnected
,09-02 19:07:56.538  4850  4850 D PbapServerProfile: Bluetooth service disconnected
,09-02 19:07:56.538  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:56.548  3188  3265 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 19:07:56.548  3188  3265 D BluetoothAdapterProperties: Scan Mode:20
,09-02 19:07:56.548  3188  3262 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-02 19:07:56.548  3188  3262 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-02 19:07:56.548  3188  3262 E bt-btif : cmd socket is not created
,09-02 19:07:56.548  7226  7289 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3934fcd9, channel: -1, state: INIT
09-02 19:07:56.548  7226  7289 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3934fcd9, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@296ff69e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e04557fmSocket: android.net.LocalSocket@391f494c impl:android.net.LocalSocketImpl@176f8d95 fd:FileDescriptor[106]
,09-02 19:07:56.548  7226  7289 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@391f494c impl:android.net.LocalSocketImpl@176f8d95 fd:FileDescriptor[106]
09-02 19:07:56.548  7226  7289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1424)
09-02 19:07:56.548  3188  3266 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
09-02 19:07:56.548  1019  1127 E WifiNative-wlan0: do suspend true
09-02 19:07:56.548  3188  3262 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-02 19:07:56.548  3188  5309 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 19:07:56.548  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:56.558  3188  3266 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-02 19:07:56.558  3188  3266 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:07:56.558  3188  3266 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 19:07:56.558  3188  3266 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:07:56.558  3188  3266 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:07:56.558  3188  3266 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-02 19:07:56.558  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:56.558  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:56.558  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:56.558  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:56.558  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:07:56.558  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:07:56.558  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 19:07:56.558  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 19:07:56.558  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 19:07:56.558  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:07:56.558  7226  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 19:07:56.558  3188  3266 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,09-02 19:07:56.558  3188  3266 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
09-02 19:07:56.558  3188  3266 W bt-btif : invalid rfc slot id: 4
,09-02 19:07:56.558  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:56.568  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:07:56.568  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
,09-02 19:07:56.578  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,09-02 19:07:56.578  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 19:07:56.578  1178  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:07:56.578  1178  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:07:56.578  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:07:56.578  1178  1178 D BluetoothTile:  getBluetoothState : 13
,09-02 19:07:56.578  1178  1731 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-02 19:07:56.588  1869  1869 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 19:07:56.588  1019  1488 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 19:07:56.598  1019  1485 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-02 19:07:56.598  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-02 19:07:56.598  1019  1126 D WifiP2pService: InactiveState{ what=143375 }
09-02 19:07:56.598  1019  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-02 19:07:56.598  3188  3188 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2c2cac8b, channel: 5, state: LISTENING
09-02 19:07:56.598  3188  3188 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2c2cac8b, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27855177, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a1a0168mSocket: android.net.LocalSocket@17f07981 impl:android.net.LocalSocketImpl@312f3a26 fd:FileDescriptor[82]
09-02 19:07:56.598  3188  3188 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@17f07981 impl:android.net.LocalSocketImpl@312f3a26 fd:FileDescriptor[82]
,09-02 19:07:56.598  3188  3188 I BtOppRfcommListener: stopping Accept Thread
09-02 19:07:56.598  3188  3188 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@34378667, channel: 12, state: LISTENING
09-02 19:07:56.598  3188  3188 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@34378667, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18beca49, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@141cc14mSocket: android.net.LocalSocket@aa2cbd impl:android.net.LocalSocketImpl@3944d2b2 fd:FileDescriptor[85]
09-02 19:07:56.598  3188  3188 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@aa2cbd impl:android.net.LocalSocketImpl@3944d2b2 fd:FileDescriptor[85]
09-02 19:07:56.598  3188  5309 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-02 19:07:56.598  4850  4850 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:07:56.598  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:56.608  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:56.608   278   981 D CommandListener: Clearing all IP addresses on wlan0
,09-02 19:07:56.618  1636  2677 V NativeCrypto: Read error: ssl=0xb8a60650: I/O error during system call, Connection timed out
,09-02 19:07:56.618  1019  1129 E ConnectivityService: updateNetworkInfo()
,09-02 19:07:56.618  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-02 19:07:56.618  1019  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:07:56.618  1019  1129 E ConnectivityService: updateNetworkInfo()
09-02 19:07:56.618  1019  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,09-02 19:07:56.628  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 19:07:56.628  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-02 19:07:56.628  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:07:56.628  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:56.628  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:56.628  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:07:56.628  1019  1126 D WifiP2pService: InactiveState{ what=131204 },
09-02 19:07:56.638  1019  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
09-02 19:07:56.638  1019  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-02 19:07:56.638  1019  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
,09-02 19:07:56.648  1019  1126 D WifiP2pService: P2pDisablingState
09-02 19:07:56.648  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
09-02 19:07:56.648  1019  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
09-02 19:07:56.648  1019  1152 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:56.648  1019  1126 D WifiP2pService: p2p socket connection lost
09-02 19:07:56.648  1019  1019 D RttService: SCAN_AVAILABLE : 1
09-02 19:07:56.648  1019  1126 D WifiP2pService: P2pDisabledState
09-02 19:07:56.648  1019  1153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:07:56.648  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-02 19:07:56.648  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:07:56.648  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 19:07:56.648  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:56.648  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:56.648  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:56.648  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:56.648  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-02 19:07:56.648  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
09-02 19:07:56.648  1019  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-02 19:07:56.658  1019  1127 E WifiNative-wlan0: do suspend true
09-02 19:07:56.658  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-02 19:07:56.658  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 19:07:56.658  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
09-02 19:07:56.658  1019  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-02 19:07:56.658  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 19:07:56.658  1019  1049 D WifiDisplayController: disconnect
09-02 19:07:56.658  1019  1049 D WifiDisplayController: updateConnection
09-02 19:07:56.658  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 19:07:56.658  1019  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 19:07:56.668  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-02 19:07:56.668  1019  1505 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
09-02 19:07:56.668  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-02 19:07:56.688  1019  1126 D WifiP2pService: P2pDisabledState{ what=143375 },
09-02 19:07:56.688  1019  1126 D WifiP2pService: DefaultState{ what=143375 }
,09-02 19:07:56.698  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-02 19:07:56.698  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:07:56.698  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
,09-02 19:07:56.698  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-02 19:07:56.698  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:56.698  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-02 19:07:56.698  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:07:56.718   278   981 D CommandListener: Clearing all IP addresses on wlan0,
09-02 19:07:56.718  1019  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-02 19:07:56.718  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit,
09-02 19:07:56.718  1019  1129 V NetworkStats: updateIfacesLocked()
09-02 19:07:56.718  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 19:07:56.718  1019  1129 V NetworkStats: performPollLocked(flags=0x1),
09-02 19:07:56.718  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 19:07:56.718  1376  1376 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-02 19:07:56.718  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-02 19:07:56.718  1019  1129 V NetworkStats: performPollLocked() took 7ms
09-02 19:07:56.718  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:07:56.728  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-02 19:07:56.728  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 19:07:56.728  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
09-02 19:07:56.728  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-02 19:07:56.728  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:56.728  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:56.728  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:56.728  1019  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-02 19:07:56.728  1178  1726 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-02 19:07:56.728  1019  1129 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:56.728  1019  1745 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 19:07:56.728  1019  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-02 19:07:56.728  1448  1448 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-02 19:07:56.728  1019  1129 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-02 19:07:56.728  1448  1448 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:07:56.728  1019  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 19:07:56.728  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:07:56.728  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:56.738  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-02 19:07:56.738  1019  1131 D Tethering: MasterInitialState.processMessage what=3
,09-02 19:07:56.738  1019  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-02 19:07:56.738  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
,09-02 19:07:56.738  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-02 19:07:56.738  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-02 19:07:56.738  1178  1178 D StatusBar.NetworkController: updateDataNetType()
09-02 19:07:56.738  1019  1124 V NetworkStats: updateIfacesLocked()
,09-02 19:07:56.738  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:56.738  1019  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-02 19:07:56.738  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-02 19:07:56.748  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 19:07:56.748  1019  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-02 19:07:56.748  1019  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 19:07:56.748  1019  1127 D SecContentProvider2: mCursor = null
,09-02 19:07:56.748  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-02 19:07:56.748  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-02 19:07:56.758  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-02 19:07:56.758  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 26 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,09-02 19:07:56.758  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-02 19:07:56.758  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-02 19:07:56.758  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-02 19:07:56.758  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 19:07:56.758  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-02 19:07:56.758  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:56.758  1019  1124 V NetworkStats: performPollLocked() took 17ms
09-02 19:07:56.758  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:56.758  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:56.758  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:07:56.758  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:07:56.758  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-02 19:07:56.768  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-02 19:07:56.768  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-02 19:07:56.768  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:07:56.768  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:56.768  1178  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-02 19:07:56.768  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:07:56.768  1178  1178 D HotspotTile: onReceive : 0, 0
09-02 19:07:56.768  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:56.768  3188  3262 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-02 19:07:56.768  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:56.768  3188  3262 D BtConfig.SecureMode: isSecureModeOn:false
09-02 19:07:56.768  3188  3262 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-02 19:07:56.768  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
09-02 19:07:56.768  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-02 19:07:56.768  3188  3262 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-02 19:07:56.768  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-02 19:07:56.768  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-02 19:07:56.768  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-02 19:07:56.768  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-02 19:07:56.768  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:07:56.768  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:56.768  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:56.768  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:56.768  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:56.768  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:07:56.768  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:56.768  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:56.768  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:07:56.768  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:07:56.768  7226  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:07:56.768  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:07:56.768  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:07:56.768  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:07:56.768  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:07:56.768  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:07:56.768  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:07:56.768  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:07:56.768  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:07:56.768  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:07:56.778  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:07:56.778  7226  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:07:56.778  1019  1494 I art     : Explicit concurrent mark sweep GC freed 51261(3MB) AllocSpace objects, 36(576KB) LOS objects, 33% free, 23MB/35MB, paused 9.225ms total 189.520ms
,09-02 19:07:56.778  1019  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false,
09-02 19:07:56.778  1019  4260 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:07:56.778  1019  1129 D ConnectivityService: nai.networkMonitor.doQuit(),
,09-02 19:07:56.778  1019  4260 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-02 19:07:56.778  1019  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-02 19:07:56.778  1019  1129 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:07:56.778  1636  2677 V NativeCrypto: SSL shutdown failed: ssl=0xb8a60650: I/O error during system call, Broken pipe
09-02 19:07:56.778  4850  4850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 19:07:56.778  1019  4260 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:56.778  1019  4260 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:56.778  1019  4260 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:07:56.778  1019  1129 E ConnectivityService: updateNetworkInfo()
09-02 19:07:56.778  1019  1129 E ConnectivityService: updateNetworkInfo()
09-02 19:07:56.778   288   288 E SMD     : DCD OFF
09-02 19:07:56.778  1019  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-02 19:07:56.788  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService,
09-02 19:07:56.788  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-02 19:07:56.788  1019  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:07:56.788  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-02 19:07:56.788  1019  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-02 19:07:56.788  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:56.788  1019  1097 V AlarmManager: waitForAlarm result :4
09-02 19:07:56.788  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:56.788  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:56.788  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:56.788  1019  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-02 19:07:56.788  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:56.788  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:07:56.788  1019  1494 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:56.788  1019  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:56.788  1019  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:07:56.798  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-02 19:07:56.798  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-02 19:07:56.798  3188  3188 V BluetoothOppManager: cleanUp...
09-02 19:07:56.798  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-02 19:07:56.798  3188  3188 D HeadsetService: Received stop request...Stopping profile...
,09-02 19:07:56.798  1019  1136 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-02 19:07:56.798  1019  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 19:07:56.798  1019  1136 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:56.798  1019  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:07:56.798  1019  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 19:07:56.808  4850  4850 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:07:56.808  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:07:56.808  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 19:07:56.808  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:56.808  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:56.808  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:07:56.808  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-02 19:07:56.808  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
09-02 19:07:56.808  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-02 19:07:56.818  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-02 19:07:56.818  1636  1636 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 19:07:56.818  1019  4260 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:07:56.818  1019  4260 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-02 19:07:56.818  1019  4260 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:56.818  1019  4260 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:56.818  1019  4260 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:07:56.828  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-02 19:07:56.828  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-02 19:07:56.828  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-02 19:07:56.828  1019  1019 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-02 19:07:56.828  1019  1019 V AlarmManagerEXT: <AppSync3 Whitelist>
09-02 19:07:56.828  1019  1019 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-02 19:07:56.828  3188  3188 D A2dpService: Received stop request...Stopping profile...
,09-02 19:07:56.828  3188  3336 D A2dpStateMachine: Exit Disconnected: -1
,09-02 19:07:56.828  1019  4273 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:07:56.828  4850  4850 D DockEventReceiver: finishStartingService: stopping service
09-02 19:07:56.828  1019  4273 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 19:07:56.838  1019  4273 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:56.838  1019  4273 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:56.838  1019  4273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:07:56.838  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-02 19:07:56.838  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-02 19:07:56.838  1376  1376 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 19:07:56.838  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-02 19:07:56.838  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-02 19:07:56.838  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,09-02 19:07:56.838  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-02 19:07:56.838  4850  4850 D BluetoothNotiBroadcastReceiver: onReceive,
09-02 19:07:56.838  1019  1219 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:07:56.838  1019  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 19:07:56.838  1019  1219 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:56.838  1019  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:56.838  1019  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:07:56.838  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:07:56.838  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-02 19:07:56.838  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-02 19:07:56.838  3188  3262 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-02 19:07:56.848  1019  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:07:56.848  4850  4850 D HeadsetProfile: Bluetooth service disconnected
09-02 19:07:56.848  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-02 19:07:56.848  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:56.848  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:56.848  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:07:56.848  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-02 19:07:56.848  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:07:56.848  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 19:07:56.848  3188  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 19:07:56.848  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:07:56.848  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-02 19:07:56.848  3188  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:07:56.848  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-02 19:07:56.848  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-02 19:07:56.848  3188  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-02 19:07:56.848  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-02 19:07:56.848  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-02 19:07:56.848  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,09-02 19:07:56.848  3188  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-02 19:07:56.848  3188  3262 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-02 19:07:56.858  3188  3188 D HidService: Received stop request...Stopping profile...
09-02 19:07:56.858  3188  3188 D HidService: Stopping Bluetooth HidService
09-02 19:07:56.858  3188  3188 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 19:07:56.858  3188  3188 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-02 19:07:56.858  3188  3188 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 19:07:56.858  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
09-02 19:07:56.858  1019  1019 D BluetoothA2dp: Proxy object disconnected
09-02 19:07:56.858  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-02 19:07:56.858  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-02 19:07:56.858  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-02 19:07:56.858  3188  3188 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 19:07:56.858  3188  3188 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-02 19:07:56.858  3188  3188 D HealthService: Received stop request...Stopping profile...
,09-02 19:07:56.858  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
09-02 19:07:56.858  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
09-02 19:07:56.858  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
09-02 19:07:56.858  4850  4850 D BluetoothA2dp: Proxy object disconnected
09-02 19:07:56.868  4850  4850 D A2dpProfile: Bluetooth service disconnected
09-02 19:07:56.868  4850  4850 D BluetoothInputDevice: Proxy object disconnected
,09-02 19:07:56.868  4850  4850 D HidProfile: Bluetooth service disconnected
,09-02 19:07:56.868  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:56.868  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-02 19:07:56.868  3188  3188 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-02 19:07:56.868  3188  3188 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-02 19:07:56.868  3188  3188 D PanService: Received stop request...Stopping profile...
09-02 19:07:56.868  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:07:56.878  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-02 19:07:56.878  4850  4850 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 19:07:56.878  4850  4850 D PanProfile: Bluetooth service disconnected
,09-02 19:07:56.878  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-02 19:07:56.878  1019  4260 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
09-02 19:07:56.878  3188  3188 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 19:07:56.878  3188  3188 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-02 19:07:56.878  1376  1376 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-02 19:07:56.878  1019  4260 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:56.878  1019  4260 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:56.878  1019  4260 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:56.878  1019  4260 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:56.878  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 19:07:56.878  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
09-02 19:07:56.878  3188  3188 D BluetoothMapService: Received stop request...Stopping profile...
09-02 19:07:56.878  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 19:07:56.888  7306  7306 E Zygote  : MountEmulatedStorage()
,09-02 19:07:56.898  7306  7306 E Zygote  : v2
,09-02 19:07:56.898  7306  7306 I libpersona: KNOX_SDCARD checking this for 10055
09-02 19:07:56.898  7306  7306 I libpersona: KNOX_SDCARD not a persona
,09-02 19:07:56.898  7306  7306 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 19:07:56.898  1019  4260 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7306 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
,09-02 19:07:56.898  7306  7306 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 19:07:56.898  7306  7306 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-02 19:07:56.898  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
09-02 19:07:56.898  1376  1376 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-02 19:07:56.908  1376  1376 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,09-02 19:07:56.908  1376  1376 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-02 19:07:56.908  1376  1376 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-02 19:07:56.908  1376  1376 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-02 19:07:56.908  4850  4850 D BluetoothMap: Proxy object disconnected
09-02 19:07:56.908  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:07:56.908  4850  4850 D MapProfile: Bluetooth service disconnected
09-02 19:07:56.908  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:07:56.908  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:07:56.908  3188  3188 D SapService: Received stop request...Stopping profile...
09-02 19:07:56.908  3188  3188 D SapService: Stopping Bluetooth SapService
09-02 19:07:56.908  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:07:56.908  1019  1131 D Tethering: InitialState.processMessage what=4
,09-02 19:07:56.908  3188  3188 D BluetoothA2dp: Proxy object disconnected
09-02 19:07:56.908  3188  3188 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-02 19:07:56.908  3188  3337 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-02 19:07:56.908  3188  3188 I GKI_LINUX: GKI_exit_task 2 done
09-02 19:07:56.908  3188  3188 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-02 19:07:56.908  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-02 19:07:56.908  3188  3188 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-02 19:07:56.908  3188  3188 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:07:56.908  3188  3188 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 19:07:56.908  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-02 19:07:56.908  3188  3188 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-02 19:07:56.908  3188  3188 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:07:56.908  3188  3188 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 19:07:56.908  3188  3188 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 19:07:56.908  3188  3188 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-02 19:07:56.908  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-02 19:07:56.908  3188  3188 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-02 19:07:56.908  3188  3188 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:07:56.908  3188  3188 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 19:07:56.908  3188  3188 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 19:07:56.908  3188  3188 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-02 19:07:56.908  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-02 19:07:56.908  3188  3188 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-02 19:07:56.908  3188  3188 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 19:07:56.908  3188  3188 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-02 19:07:56.908  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-02 19:07:56.908  3188  3188 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-02 19:07:56.908  3188  3188 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-02 19:07:56.908  3188  3188 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-02 19:07:56.918  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:07:56.918  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:07:56.918  4850  4850 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,09-02 19:07:56.918  1019  1131 E Tethering: No numeric data
09-02 19:07:56.918  4850  4850 D SapProfile: Bluetooth service disconnected
09-02 19:07:56.918  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:07:56.918  1019  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 19:07:56.918  1019  1131 D Tethering: clearTetheredNotification()
09-02 19:07:56.918  3188  3262 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-02 19:07:56.918  3188  3262 D BluetoothAdapterProperties: Setting state to 10
09-02 19:07:56.918  3188  3262 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-02 19:07:56.918  3188  3262 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 19:07:56.918  3188  3262 D BluetoothAdapterService: updateAdapterState state is 10
,09-02 19:07:56.918  3188  3262 D BluetoothAdapterService: Autoconnection is available 
,09-02 19:07:56.918  3188  3262 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-02 19:07:56.918  3188  3262 I BluetoothAdapterState: Entering OffState
,09-02 19:07:56.918  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:07:56.918  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:07:56.918  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 19:07:56.928  1019  1124 V NetworkStats: performPollLocked(flags=0x1)
09-02 19:07:56.928  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:07:56.928  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 19:07:56.928  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 19:07:56.928  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 19:07:56.928  1178  1178 D HotspotTile: updateTetherState():false, false
,09-02 19:07:56.928  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:56.928  1019  1124 V NetworkStats: performPollLocked() took 4ms
,09-02 19:07:56.928  1448  1471 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:07:56.928  1448  1471 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:07:56.928  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:56.928  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:07:56.938  7306  7306 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:56.938  7306  7306 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:56.938  3188  3352 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:07:56.948  4850  4858 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-02 19:07:56.958  7226  7226 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 19:07:56.958  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-02 19:07:56.958  4850  7303 D BluetoothMap: onBluetoothStateChange: up=false
,09-02 19:07:56.968  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:07:56.968  1019  1048 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 19:07:56.968  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:07:56.968  4850  4859 D BluetoothPbap: onBluetoothStateChange: up=false
,09-02 19:07:56.968  1423  7304 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:07:56.968  1423  7304 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:07:56.968  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-02 19:07:56.968  7306  7306 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
09-02 19:07:56.968  7226  7234 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:07:56.968  7226  7234 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 19:07:56.968  7226  7234 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-02 19:07:56.968  7226  7234 D BluetoothLeAdvertiser: Exit stop advertising
09-02 19:07:56.968  7226  7234 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-02 19:07:56.968  7226  7234 D BluetoothLeScanner: Exiting stopAllScan
,09-02 19:07:56.978  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-02 19:07:56.978  1436  1457 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:07:56.978  1436  1457 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 19:07:56.978  1758  1963 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:07:56.978  1758  1963 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 19:07:56.978  3188  3199 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:07:56.978  3188  3199 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 19:07:56.978  4850  4858 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:07:56.988  1636  1650 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:07:56.988  1636  1650 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 19:07:56.988  4850  7303 D Bluetoothsap: onBluetoothStateChange: up=false
09-02 19:07:56.988  4850  7303 D Bluetoothsap: Unbinding service...
,09-02 19:07:56.998  4850  4859 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:07:56.998  4850  4859 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 19:07:56.998  1178  2417 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:07:56.998  1178  2417 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:07:56.998  1448  1448 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:56.998  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-02 19:07:56.998  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:56.998  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
09-02 19:07:56.998  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-02 19:07:57.008  1448  1448 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:57.008  7306  7306 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
09-02 19:07:57.008  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 19:07:57.008  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:07:57.008  1178  1178 D BluetoothTile:  getBluetoothState : 10
09-02 19:07:57.008  1448  1448 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:57.008  7306  7306 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-02 19:07:57.008  7306  7306 D UserAnalysis: Create SecureDbHelper,
,09-02 19:07:57.008  1869  1869 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0,
09-02 19:07:57.008  1448  1448 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 19:07:57.008  1448  1448 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:57.008  4850  4850 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:07:57.018  1448  1448 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 19:07:57.018  1448  1448 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:57.018  1019  1485 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 19:07:57.018  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:07:57.018  1019  1497 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-02 19:07:57.018  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-02 19:07:57.018  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:57.018  7306  7306 D IntelligenceServiceApplication: onCreate()
09-02 19:07:57.018  1448  1448 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 19:07:57.018  1448  1448 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:57.018  1448  1448 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:57.028  1448  1448 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:57.028  1448  1448 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 19:07:57.028  1448  1448 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:57.028  1448  1448 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 19:07:57.028  1019  1136 I ActivityManager: Killing 6833:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
09-02 19:07:57.028  1448  1448 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-02 19:07:57.028  1448  1448 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 19:07:57.028  1448  1448 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:57.038  1448  1448 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 19:07:57.038  1448  1448 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:57.038  7306  7306 D IntelligenceServiceApplication: no applications having user consent for prediction
09-02 19:07:57.038  1019  1219 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-02 19:07:57.038  1019  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-02 19:07:57.038  1448  1448 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 19:07:57.038  1019  1488 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4245, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-02 19:07:57.038  1448  1448 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-02 19:07:57.038  1019  1488 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-02 19:07:57.038  1019  1488 D BatteryService: stay LED for charging
09-02 19:07:57.038  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-02 19:07:57.038  1019  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.038  1019  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.038  1019  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.038  1019  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:57.038  1448  1448 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 19:07:57.038  1448  1448 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:57.048  1448  1448 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 19:07:57.048  1448  1448 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-02 19:07:57.048  1448  1448 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-02 19:07:57.048  1448  1448 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-02 19:07:57.048  7335  7335 E Zygote  : MountEmulatedStorage()
09-02 19:07:57.048  7335  7335 I libpersona: KNOX_SDCARD checking this for 10105
,09-02 19:07:57.048  7335  7335 E Zygote  : v2
09-02 19:07:57.048  7335  7335 I libpersona: KNOX_SDCARD not a persona
09-02 19:07:57.048  1448  1448 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-02 19:07:57.048  1448  1448 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-02 19:07:57.048  7335  7335 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 19:07:57.048  1019  1219 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7335 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-02 19:07:57.058  1448  1448 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-02 19:07:57.058  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-02 19:07:57.058  7306  7306 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-02 19:07:57.058  1019  1019 I MotionRecognitionService: Plugged
09-02 19:07:57.058  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,09-02 19:07:57.058  7335  7335 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 19:07:57.058  7335  7335 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-02 19:07:57.058  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-02 19:07:57.058  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
09-02 19:07:57.058  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-02 19:07:57.058  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
09-02 19:07:57.058  7306  7306 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-02 19:07:57.078  7335  7335 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:57.078  7335  7335 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:57.088  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-02 19:07:57.088  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-02 19:07:57.088  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-02 19:07:57.118  1376  1376 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 19:07:57.158  1376  1376 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,09-02 19:07:57.158  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false,
09-02 19:07:57.158  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:07:57.158  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:07:57.168  1019  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-02 19:07:57.168  1019  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-02 19:07:57.168  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-02 19:07:57.168  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 19:07:57.178  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 19:07:57.178  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:57.178  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:57.178  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:57.178  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:07:57.178  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:07:57.178  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-02 19:07:57.178  1178  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-02 19:07:57.178  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:07:57.178  1178  1178 D HotspotTile: onReceive : 1, 0
,09-02 19:07:57.178  1758  2203 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:07:57.178  4850  4850 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:07:57.178  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:57.188  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:57.198   257   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-02 19:07:57.198   257   520 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 19:07:57.198  7335  7357 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-02 19:07:57.208   257   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-02 19:07:57.208   257   520 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 19:07:57.208  7335  7357 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-02 19:07:57.238  1019  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:07:57.238  1019  1019 I ApplicationPolicy: updateDataUsageMap
,09-02 19:07:57.258  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:57.258  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:07:57.258  1019  1043 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:07:57.358  7335  7335 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.io.File.exists(File.java:363)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:07:57.358  7335  7335 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:07:57.358  7335  7335 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:07:57.358  7335  7335 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.q.e.b(PG:170)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:07:57.358  7335  7335 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.q.k.d(PG:583)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.q.e.b(PG:170)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:07:57.358  7335  7335 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.io.File.exists(File.java:363)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:07:57.358  7335  7335 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.io.File.exists(File.java:363)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:07:57.358  7335  7335 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:07:57.358  7335  7335 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:07:57.358  1019  1031 I ActivityManager: Killing 6866:com.google.android.apps.docs/u0a87 (adj 15): empty #21
09-02 19:07:57.368  1019  1338 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 19:07:57.368  1019  1338 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 19:07:57.368  1019  1338 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:57.368  1019  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:57.368  1019  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-02 19:07:57.368  1663  1663 I Hs20UtilService: Starting #8
09-02 19:07:57.368  1663  1703 I Hs20UtilService: Message received 5007
09-02 19:07:57.368  4850  4850 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-02 19:07:57.378  4850  4850 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-02 19:07:57.378  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-02 19:07:57.378  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 19:07:57.378  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:07:57.378  4850  4850 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-02 19:07:57.378  4850  4937 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-02 19:07:57.388  4850  4850 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-02 19:07:57.388  4850  4850 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 19:07:57.388  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-02 19:07:57.398  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 19:07:57.398  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:07:57.398  4850  4850 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-02 19:07:57.398  4850  4937 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-02 19:07:57.398  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
09-02 19:07:57.398  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.398  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.398  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.398  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.408  7368  7368 E Zygote  : MountEmulatedStorage()
09-02 19:07:57.408  7368  7368 I libpersona: KNOX_SDCARD checking this for 10064
09-02 19:07:57.408  7368  7368 E Zygote  : v2
09-02 19:07:57.408  7368  7368 I libpersona: KNOX_SDCARD not a persona
09-02 19:07:57.408  1019  1031 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7368 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 19:07:57.408  7368  7368 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 19:07:57.418  7368  7368 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 19:07:57.418  7368  7368 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:07:57.438  7335  7367 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-02 19:07:57.438  7368  7368 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:57.438  7368  7368 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:57.458  7368  7368 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-02 19:07:57.468  1019  1494 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 19:07:57.468  1019  1494 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:57.468  1019  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:07:57.468  1019  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-02 19:07:57.478  7368  7368 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 19:07:57.478  7368  7368 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-02 19:07:57.508  7368  7368 D FileShare-Client: Outbound.stopDelayTimer - 
,09-02 19:07:57.508  1019  1494 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-02 19:07:57.508  1019  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:57.508  1019  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.508  1019  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.508  1019  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:57.518  7385  7385 E Zygote  : MountEmulatedStorage(),
09-02 19:07:57.518  1019  1494 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7385 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 19:07:57.518  7385  7385 E Zygote  : v2
09-02 19:07:57.518  7385  7385 I libpersona: KNOX_SDCARD checking this for 10065
09-02 19:07:57.518  7385  7385 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-02 19:07:57.518  7385  7385 I libpersona: KNOX_SDCARD not a persona
,09-02 19:07:57.518  1019  1494 I ActivityManager: Killing 6886:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,09-02 19:07:57.528  7385  7385 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 19:07:57.528  7385  7385 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:07:57.548  7385  7385 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:57.548  7385  7385 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:57.568  7385  7385 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 19:07:57.568  1019  1505 I ActivityManager: Killing 6925:com.sec.pcw.device/1000 (adj 15): empty #21
,09-02 19:07:57.578  1019  1488 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 19:07:57.578  1019  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 19:07:57.578  1019  1488 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:57.578  1019  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:07:57.578  1019  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:07:57.578  1663  1663 I Hs20UtilService: Starting #9
09-02 19:07:57.578  4850  4850 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-02 19:07:57.578  4850  4850 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-02 19:07:57.578  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-02 19:07:57.578  1663  1703 I Hs20UtilService: Message received 5007
09-02 19:07:57.578  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-02 19:07:57.578  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:07:57.578  4850  4850 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-02 19:07:57.578  4850  4937 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 19:07:57.588  1019  1032 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 19:07:57.588  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:07:57.588  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:57.588  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:57.588  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:07:57.588  1663  1663 I Hs20UtilService: Starting #10
09-02 19:07:57.588  1663  1703 I Hs20UtilService: Message received 5011
,09-02 19:07:57.588  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-02 19:07:57.598  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.598  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.598  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.598  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:57.608  7400  7400 E Zygote  : MountEmulatedStorage(),
09-02 19:07:57.608  7400  7400 E Zygote  : v2
09-02 19:07:57.608  7400  7400 I libpersona: KNOX_SDCARD checking this for 1000
,09-02 19:07:57.608  7400  7400 I libpersona: KNOX_SDCARD not a persona
,09-02 19:07:57.608  7400  7400 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 19:07:57.608  7400  7400 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-02 19:07:57.618  7400  7400 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-02 19:07:57.618  1019  1031 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7400 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-02 19:07:57.628  7400  7400 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:57.638  7400  7400 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:57.668  7400  7400 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-02 19:07:57.668  7400  7400 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 19:07:57.668  7400  7400 D SecurityLogAgent: StateMachine : Current State = 1
,09-02 19:07:57.668  7400  7400 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 19:07:57.668  1019  1367 I ActivityManager: Killing 6799:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-02 19:07:57.688  1019  4260 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:57.688  1019  4260 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:57.688  1019  4260 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:57.688  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:57.688  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:57.688  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:57.708  1019  4259 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:57.708  1019  4259 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:57.708  1019  4259 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:57.708  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:57.708  1019  1019 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:07:57.708  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
09-02 19:07:57.708  1019  1019 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-02 19:07:57.708  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.708  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.708  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:57.708  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:57.738  1019  1046 D Tethering: interfaceRemoved wlan0
09-02 19:07:57.738  1019  1046 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-02 19:07:57.738  7416  7416 E Zygote  : MountEmulatedStorage()
,09-02 19:07:57.738  7416  7416 E Zygote  : v2
09-02 19:07:57.738  7416  7416 I libpersona: KNOX_SDCARD checking this for 10102,
09-02 19:07:57.738  7416  7416 I libpersona: KNOX_SDCARD not a persona
,09-02 19:07:57.738  7416  7416 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-02 19:07:57.738  7416  7416 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-02 19:07:57.748  7416  7416 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
09-02 19:07:57.748  1019  1019 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7416 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-02 19:07:57.768  7416  7416 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:57.768  7416  7416 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:57.788  7416  7416 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-02 19:07:57.968  1019  1046 D Tethering: interfaceRemoved p2p0
09-02 19:07:57.968  1019  1046 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-02 19:07:57.978  7416  7436 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-02 19:07:57.978  7416  7436 I Babel_SMS: MmsConfig.loadMmsSettings
,09-02 19:07:57.978  7416  7436 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-02 19:07:57.978  7416  7436 I Babel_SMS: MmsConfig.loadFromDatabase
,09-02 19:07:57.998  7416  7436 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-02 19:07:57.998  7416  7436 I Babel_SMS: MmsConfig.loadFromResources
,09-02 19:07:58.008  7416  7436 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-02 19:07:58.008  7416  7436 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-02 19:07:58.028  1019  4259 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-02 19:07:58.028  1019  4259 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-02 19:07:58.028  1019  4259 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:58.028  1019  4259 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:07:58.028  1019  4259 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-02 19:07:58.048  7416  7416 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:07:58.058  7416  7416 I Babel_Crash: startup - clean
,09-02 19:07:58.078  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:58.078  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:07:58.078  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:58.088  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:58.088  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:07:58.088  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:58.088  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:58.088  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:07:58.088  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:58.098  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:58.098  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:07:58.098  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:58.098  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.098  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:58.098  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:58.098  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.108  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:58.108  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:58.108  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.108  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:58.108  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:58.108  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.108  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:58.108  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:58.108  7416  7416 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 19:07:58.108  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.108  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:58.108  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:58.118  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.118  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:58.118  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:58.118  7416  7416 W AudioCapabilities: Unsupported mime audio/evrc
,09-02 19:07:58.118  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.118  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:58.118  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:58.118  7416  7416 W AudioCapabilities: Unsupported mime audio/qcelp
,09-02 19:07:58.118  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.118  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:58.118  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-02 19:07:58.128  7416  7416 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-02 19:07:58.128  7416  7416 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-02 19:07:58.128  4850  4850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 19:07:58.128  1019  1485 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-02 19:07:58.128  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 19:07:58.128  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:58.128  7416  7416 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-02 19:07:58.128  1019  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:07:58.128  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 19:07:58.128  7416  7416 W AudioCapabilities: Unsupported mime audio/x-ima
,09-02 19:07:58.138  7416  7416 W AudioCapabilities: Unsupported mime audio/qcelp
,09-02 19:07:58.138  1636  1636 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 19:07:58.138  7416  7416 W AudioCapabilities: Unsupported mime audio/evrc
,09-02 19:07:58.138  4850  4850 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:07:58.148  4850  4850 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 19:07:58.148  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:07:58.148  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-02 19:07:58.178  1019  1032 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-02 19:07:58.178  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.178  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 19:07:58.178  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:07:58.178  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:07:58.178  7416  7416 W VideoCapabilities: Unsupported mime video/wvc1
,09-02 19:07:58.178  1663  1663 I Hs20UtilService: Starting #11
,09-02 19:07:58.178  7416  7416 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-02 19:07:58.178  1663  1703 I Hs20UtilService: Message received 5011
,09-02 19:07:58.188  7400  7400 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-02 19:07:58.188  7400  7400 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 19:07:58.188  7400  7400 D SecurityLogAgent: StateMachine : Current State = 1
09-02 19:07:58.188  7400  7400 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 19:07:58.188  1019  4259 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-02 19:07:58.188  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.188  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:58.188  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:58.188  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.198  7416  7416 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-02 19:07:58.208  7442  7442 E Zygote  : MountEmulatedStorage(),
09-02 19:07:58.208  7442  7442 E Zygote  : v2
09-02 19:07:58.208  7442  7442 I libpersona: KNOX_SDCARD checking this for 1000
09-02 19:07:58.208  7442  7442 I libpersona: KNOX_SDCARD not a persona
,09-02 19:07:58.208  7442  7442 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 19:07:58.208  1019  4259 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7442 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-02 19:07:58.208  7442  7442 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 19:07:58.208  7416  7416 W VideoCapabilities: Unsupported mime video/wvc1,
09-02 19:07:58.208  7442  7442 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:07:58.218  7416  7416 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-02 19:07:58.218  7416  7416 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-02 19:07:58.218  7416  7416 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-02 19:07:58.218  7416  7416 W VideoCapabilities: Unsupported mime video/mp43
,09-02 19:07:58.228  7416  7416 W VideoCapabilities: Unsupported mime video/sorenson
,09-02 19:07:58.228  7416  7416 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-02 19:07:58.228  7442  7442 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:58.228  7442  7442 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:58.248  7416  7416 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-02 19:07:58.258  7442  7442 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-02 19:07:58.258  7442  7442 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-02 19:07:58.258  7442  7442 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-02 19:07:58.268  7416  7416 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 19:07:58.268  7416  7416 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 19:07:58.278  7442  7442 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-02 19:07:58.278  7442  7442 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-02 19:07:58.278  7442  7442 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-02 19:07:58.278  7442  7442 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:07:58.278  7416  7416 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 19:07:58.278  1019  1031 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,09-02 19:07:58.278  1019  1031 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-02 19:07:58.278  1019  1031 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-02 19:07:58.278  1019  1031 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-02 19:07:58.278  1019  1031 I ActivityManager: Killing 6992:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-02 19:07:58.278  7416  7416 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-02 19:07:58.288  7442  7457 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-02 19:07:58.288  7416  7416 I vclib   : onServiceConnected
,09-02 19:07:58.288  1019  1019 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-02 19:07:58.288  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.288  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:58.288  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:58.288  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.298  7459  7459 E Zygote  : MountEmulatedStorage()
,09-02 19:07:58.298  7459  7459 E Zygote  : v2
,09-02 19:07:58.298  7459  7459 I libpersona: KNOX_SDCARD checking this for 10001
09-02 19:07:58.298  7459  7459 I libpersona: KNOX_SDCARD not a persona
,09-02 19:07:58.298  1019  1019 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7459 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-02 19:07:58.308  7459  7459 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 19:07:58.308  1019  1032 I ActivityManager: Killing 7015:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,09-02 19:07:58.308  7459  7459 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 19:07:58.308  7459  7459 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:07:58.328  7459  7459 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:58.328  7459  7459 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:58.388  1019  1488 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-02 19:07:58.388  1019  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.388  1019  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.388  1019  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:58.388  1019  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.408  7476  7476 E Zygote  : MountEmulatedStorage()
,09-02 19:07:58.408  7476  7476 E Zygote  : v2
09-02 19:07:58.408  7476  7476 I libpersona: KNOX_SDCARD checking this for 1000
09-02 19:07:58.408  7476  7476 I libpersona: KNOX_SDCARD not a persona
,09-02 19:07:58.408  7476  7476 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 19:07:58.408  1019  1488 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7476 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
09-02 19:07:58.408  1019  1488 I ActivityManager: Killing 7032:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,09-02 19:07:58.408  7476  7476 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 19:07:58.408  7476  7476 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-02 19:07:58.428  7476  7476 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:58.428  7476  7476 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:58.428   315   315 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 22.561ms
,09-02 19:07:58.448   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.456ms
,09-02 19:07:58.458  7476  7476 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-02 19:07:58.468   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 566us total 16.291ms
,09-02 19:07:58.578  7476  7476 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-02 19:07:58.588  7476  7476 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-02 19:07:58.598  7476  7476 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:07:58.598  7476  7476 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-02 19:07:58.598  7476  7476 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-02 19:07:58.598  7476  7476 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-02 19:07:58.598  1019  1219 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-02 19:07:58.598  1019  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-02 19:07:58.598  1019  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.598  1019  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:58.598  1019  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-02 19:07:58.618  7491  7491 E Zygote  : MountEmulatedStorage(),
09-02 19:07:58.618  7491  7491 E Zygote  : v2
09-02 19:07:58.618  7491  7491 I libpersona: KNOX_SDCARD checking this for 10008
09-02 19:07:58.618  7491  7491 I libpersona: KNOX_SDCARD not a persona
09-02 19:07:58.618  1019  1219 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7491 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 19:07:58.628  1019  1219 I ActivityManager: Killing 7058:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
09-02 19:07:58.628  7491  7491 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 19:07:58.628  7491  7491 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 19:07:58.638  7491  7491 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-02 19:07:58.648  7491  7491 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:58.658  7491  7491 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:58.728  1019  1505 I ActivityManager: Killing 6972:com.android.mms/u0a41 (adj 15): empty #21
,09-02 19:07:58.728  1019  1032 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-02 19:07:58.728  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-02 19:07:58.728  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:58.728  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:07:58.728  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-02 19:07:58.738  1019  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-02 19:07:58.748  3856  7506 I iu.SyncManager: SYNC; picasa accounts
,09-02 19:07:58.758  3856  3856 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-02 19:07:58.768  1019  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-02 19:07:58.768  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,09-02 19:07:58.768  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:58.768  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:07:58.768  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-02 19:07:58.778  3856  3856 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 19:07:58.778  3856  3856 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-02 19:07:58.788  2814  2814 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 02 19:07:58 GMT+02:00 2016
,09-02 19:07:58.788  1019  1497 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-02 19:07:58.788  1019  1497 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-02 19:07:58.788  1019  1497 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:58.788  1019  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:07:58.788  1019  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-02 19:07:58.788  2814  2814 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-02 19:07:58.798  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-02 19:07:58.798  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.798  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:58.798  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:58.798  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.798  2814  2814 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-02 19:07:58.808  2814  2814 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-02 19:07:58.808  2814  2814 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-02 19:07:58.808  2814  7508 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-02 19:07:58.808  2814  7508 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-02 19:07:58.808  1019  1032 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7509 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
,09-02 19:07:58.818  7509  7509 E Zygote  : MountEmulatedStorage()
09-02 19:07:58.818  7509  7509 I libpersona: KNOX_SDCARD checking this for 10031
09-02 19:07:58.818  7509  7509 E Zygote  : v2
09-02 19:07:58.818  7509  7509 I libpersona: KNOX_SDCARD not a persona
,09-02 19:07:58.818  7509  7509 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 19:07:58.818  7509  7509 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-02 19:07:58.818  7509  7509 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:07:58.818  2814  7508 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-02 19:07:58.828  2814  7508 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-02 19:07:58.828  2814  2814 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-02 19:07:58.838  7509  7509 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-02 19:07:58.838  7509  7509 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:58.868  1019  1505 D CountryDetector: No listener is left
,09-02 19:07:58.868  7509  7509 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-02 19:07:58.868  1019  1494 I ActivityManager: Killing 7090:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-02 19:07:58.878  1019  1338 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-02 19:07:58.888  2751  7524 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-02 19:07:58.888  1019  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.888  1019  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:58.888  1019  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.888  1019  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:58.888  2751  7524 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-02 19:07:58.888  2751  7524 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-02 19:07:58.888  2751  7524 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-02 19:07:58.898  2751  7524 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-02 19:07:58.898  1019  1338 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7525 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 19:07:58.898  7525  7525 E Zygote  : MountEmulatedStorage()
09-02 19:07:58.898  7525  7525 I libpersona: KNOX_SDCARD checking this for 10032
09-02 19:07:58.898  7525  7525 E Zygote  : v2
09-02 19:07:58.898  7525  7525 I libpersona: KNOX_SDCARD not a persona,
09-02 19:07:58.898  7525  7525 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 19:07:58.908  7525  7525 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-02 19:07:58.908  7525  7525 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-02 19:07:58.928  7525  7525 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:58.928  7525  7525 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:58.978  7525  7540 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-02 19:07:58.978  7525  7540 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-02 19:07:58.988  7525  7525 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-02 19:07:58.988  1019  1219 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-02 19:07:58.988  1019  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.988  1019  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:58.988  1019  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:58.988  1019  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:58.988  7525  7540 D SPPClientService: PushLog.txt file is not deleted.
09-02 19:07:58.988  7525  7540 D SPPClientService: PushLog.txt file is not deleted.
,09-02 19:07:58.988  7525  7540 D SPPClientService: ============PushLog. stop!
,09-02 19:07:58.998  7542  7542 E Zygote  : MountEmulatedStorage(),
09-02 19:07:58.998  7542  7542 E Zygote  : v2
09-02 19:07:58.998  7542  7542 I libpersona: KNOX_SDCARD checking this for 10036
09-02 19:07:58.998  7542  7542 I libpersona: KNOX_SDCARD not a persona
,09-02 19:07:59.008  7542  7542 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 19:07:59.008  1019  1219 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7542 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 19:07:59.008  1019  1219 I ActivityManager: Killing 7106:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,09-02 19:07:59.008  1019  4273 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-02 19:07:59.008  1019  4273 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-02 19:07:59.008  1019  4273 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:59.008  1019  4273 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,09-02 19:07:59.008  1019  4273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-02 19:07:59.008  7542  7542 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 19:07:59.018  7542  7542 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-02 19:07:59.028  7542  7542 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:59.038  7542  7542 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:59.038  7525  7548 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-02 19:07:59.068  7542  7542 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@37e795b7
,09-02 19:07:59.078  7542  7542 I SA      : [SSP] onCreated
,09-02 19:07:59.088  7542  7542 I SA      : [TPM] There is no property file
,09-02 19:07:59.098  7542  7542 I SA      : [SCU] isHaveSA() - false
,09-02 19:07:59.098  7542  7542 I SA      : [TPM] getModelProperty : null
,09-02 19:07:59.098  7542  7542 I SA      : [TPM] getCSCProperty : null
,09-02 19:07:59.098  7542  7542 I SA      : [DM] FLOATING AMOLED FEATURE: true
,09-02 19:07:59.098  7542  7542 I SA      : [DM] PRODUCT AMOLED FEATURE: false
,09-02 19:07:59.098  7542  7542 I SA      : [DM] TFT FEATURE: false
,09-02 19:07:59.108  7542  7542 I SA      : [DM] init START
,09-02 19:07:59.108  7542  7542 I SA      : [DM] This device is not a Vodafone
,09-02 19:07:59.118  7542  7542 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-02 19:07:59.118  7542  7542 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-02 19:07:59.118  7542  7542 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-02 19:07:59.118  7542  7542 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-02 19:07:59.118  7542  7542 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-02 19:07:59.118  7542  7542 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-02 19:07:59.128  7542  7542 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-02 19:07:59.128  7542  7542 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-02 19:07:59.128  7542  7542 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-02 19:07:59.128  7542  7542 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-02 19:07:59.128  7542  7542 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-02 19:07:59.128  7542  7542 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-02 19:07:59.138  7542  7542 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-02 19:07:59.138  7542  7542 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,09-02 19:07:59.138  7542  7542 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,09-02 19:07:59.138  7542  7542 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,09-02 19:07:59.138  7542  7542 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,09-02 19:07:59.138  7542  7542 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,09-02 19:07:59.138  7542  7542 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-02 19:07:59.138  7542  7542 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-02 19:07:59.138  7542  7542 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-02 19:07:59.148  7542  7542 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-02 19:07:59.148  7542  7542 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-02 19:07:59.148  7542  7542 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-02 19:07:59.148  7542  7542 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-02 19:07:59.148  7542  7542 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-02 19:07:59.148  7542  7542 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-02 19:07:59.148  7542  7542 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-02 19:07:59.148  7542  7542 I SA      : [SCU] isHaveSA() - false
09-02 19:07:59.148  7542  7542 I SA      : support phone number id : false
09-02 19:07:59.148  7542  7542 I SA      : [DM] Supports Ref Jpn : true
,09-02 19:07:59.148  7542  7542 I SA      : [DM] init END
,09-02 19:07:59.158  7542  7542 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-02 19:07:59.158  7542  7542 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,09-02 19:07:59.158  7542  7542 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-02 19:07:59.168  7542  7542 I SA      : [SLFUCHKMGR] constructor called
,09-02 19:07:59.168  7542  7542 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-02 19:07:59.168  7542  7542 I SA      : [OR] == isSIMCardReady false ==
,09-02 19:07:59.178  7542  7542 I SA      : [SCU] == networkStateCheck == false
,09-02 19:07:59.178  7542  7542 I SA      : [OR] onReceive END
,09-02 19:07:59.178  1019  1485 I ActivityManager: Killing 7122:com.wsomacp/u0a23 (adj 15): empty #21
,09-02 19:07:59.188  1231  1231 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:07:59.188  1781  1781 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-02 19:07:59.198  2645  6376 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,09-02 19:07:59.198  1781  1781 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-02 19:07:59.198  1781  1781 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-02 19:07:59.198  1781  1781 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-02 19:07:59.198  1781  1781 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-02 19:07:59.208  1781  1781 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-02 19:07:59.208  1781  1781 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-02 19:07:59.208  1019  4260 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-02 19:07:59.208  1019  4260 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:59.208  1019  4260 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:59.208  1019  4260 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:59.208  1019  4260 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:59.218  7564  7564 E Zygote  : MountEmulatedStorage(),
09-02 19:07:59.218  1019  4260 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7564 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-02 19:07:59.218  7564  7564 E Zygote  : v2
09-02 19:07:59.218  7564  7564 I libpersona: KNOX_SDCARD checking this for 10077
,09-02 19:07:59.218  7564  7564 I libpersona: KNOX_SDCARD not a persona
,09-02 19:07:59.228  7564  7564 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-02 19:07:59.228  7564  7564 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-02 19:07:59.228  7564  7564 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,09-02 19:07:59.238  7564  7564 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:59.248  7564  7564 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:59.448  1019  1494 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-02 19:07:59.448  1019  1494 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-02 19:07:59.448  1019  1494 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:07:59.448  1019  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:07:59.448  1019  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-02 19:07:59.458  1019  1136 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-02 19:07:59.458  1019  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:59.458  1019  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:07:59.458  1019  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:59.458  1019  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:07:59.468  7582  7582 E Zygote  : MountEmulatedStorage()
09-02 19:07:59.468  7582  7582 E Zygote  : v2
09-02 19:07:59.468  7582  7582 I libpersona: KNOX_SDCARD checking this for 10110
09-02 19:07:59.468  7582  7582 I libpersona: KNOX_SDCARD not a persona
,09-02 19:07:59.468  1019  1136 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7582 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 19:07:59.468  7582  7582 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 19:07:59.468  1019  4259 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-02 19:07:59.468  1019  4259 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
09-02 19:07:59.478  1019  4259 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:07:59.478  1019  4259 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:07:59.478  1019  4259 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-02 19:07:59.478  7416  7581 I Babel   : connection state changed from UNKNOWN to DISCONNECTED,
,09-02 19:07:59.478  7582  7582 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-02 19:07:59.478  7582  7582 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-02 19:07:59.478  1019  4273 I ActivityManager: Killing 7163:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-02 19:07:59.498  7582  7582 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:07:59.498  7582  7582 D ActivityThread: Added TimaKeyStore provider
,09-02 19:07:59.538  1019  1488 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-02 19:07:59.538  1019  1488 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-02 19:07:59.538  1019  1488 D SecContentProvider2: mCursor = null
,09-02 19:07:59.538  1019  1488 D WifiService: setWifiEnabled: true pid=7226, uid=10170
,09-02 19:07:59.538  1019  1488 W ActivityManager: Permission Denial: getCurrentUser() from pid=7226, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-02 19:07:59.538  1019  1488 W WifiService: Failed getting userId using ActivityManagerNative
09-02 19:07:59.538  1019  1488 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7226, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-02 19:07:59.538  1019  1488 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-02 19:07:59.538  1019  1488 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-02 19:07:59.538  1019  1488 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-02 19:07:59.538  1019  1488 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-02 19:07:59.538  1019  1488 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-02 19:07:59.538  1019  1488 D SettingsProvider: name = wifi_on
,09-02 19:07:59.598  1019  1127 E WifiHW  : ##################### set firmware type 0 #####################
,09-02 19:07:59.668  1019  4260 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-02 19:07:59.778   288   288 E SMD     : DCD OFF
,09-02 19:07:59.788   257   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-02 19:07:59.788   257   520 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 19:07:59.788  7582  7601 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-02 19:07:59.798   257   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-02 19:07:59.798   257   520 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 19:07:59.798  7582  7601 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-02 19:07:59.808   257   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/,
09-02 19:07:59.808  7582  7602 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
09-02 19:07:59.808   257   520 W Vold    : Returning OperationFailed - no handler for errno 0,
,09-02 19:07:59.818   257   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-02 19:07:59.818   257   520 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 19:07:59.818  7582  7602 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-02 19:07:59.828  7582  7582 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
09-02 19:07:59.828  7582  7582 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-02 19:07:59.828  7582  7582 I GAv4    :   adb logcat -s GAv4
,09-02 19:07:59.848  7582  7582 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-02 19:07:59.848  1019  1505 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-02 19:07:59.858  7582  7582 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-02 19:07:59.868  7582  7610 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-02 19:07:59.958  1019  1046 D Tethering: interfaceAdded wlan0
,09-02 19:07:59.968  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:07:59.968  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:07:59.968  1019  1131 E Tethering: No numeric data
,09-02 19:07:59.968  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 19:07:59.978  1019  1124 V NetworkStats: performPollLocked(flags=0x1),
09-02 19:07:59.978  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:07:59.978  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-02 19:07:59.978  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 19:07:59.978  1019  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-02 19:07:59.978  1019  1131 D Tethering: clearTetheredNotification(),
09-02 19:07:59.978  1019  1131 D Tethering: InitialState.processMessage what=4
,09-02 19:07:59.978  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 19:07:59.978  1178  1178 D HotspotTile: updateTetherState():false, false
,09-02 19:07:59.978  1019  1124 V NetworkStats: performPollLocked() took 6ms
09-02 19:07:59.978  1019  1046 D Tethering: interfaceAdded p2p0
,09-02 19:07:59.988  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:59.988  1019  1124 V NetworkStats: performPollLocked(flags=0x1)
09-02 19:07:59.988  1019  1131 E Tethering: No numeric data
09-02 19:07:59.988  1019  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 19:07:59.988  1019  1131 D Tethering: clearTetheredNotification()
09-02 19:07:59.988  1019  1046 D Tethering: p2p0 is not a tetherable iface, ignoring
09-02 19:07:59.988   278   981 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-02 19:07:59.988   278   981 D SoftapController: Softap fwReload - Ok
09-02 19:07:59.988  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:07:59.988  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 19:07:59.988  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 19:07:59.988  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 19:07:59.988  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
09-02 19:07:59.988  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 19:07:59.988   278   981 D CommandListener: Setting iface cfg
09-02 19:07:59.988   278   981 D CommandListener: Trying to bring down wlan0
,09-02 19:07:59.988  1178  1178 D HotspotTile: updateTetherState():false, false
09-02 19:07:59.988  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 19:07:59.988   278   981 D CommandListener: Clearing all IP addresses on wlan0
,09-02 19:07:59.988  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:59.988  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:59.988  1019  1097 V AlarmManager: waitForAlarm result :8
,09-02 19:07:59.988  1019  1124 V NetworkStats: performPollLocked() took 6ms
,09-02 19:07:59.988  1019  1127 E WifiHW  : supplicant_name : p2p_supplicant
09-02 19:07:59.988  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:07:59.998  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:07:59.998  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:07:59.998  1019  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-02 19:07:59.998  1019  1127 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-02 19:08:00.008  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-02 19:08:00.008  4850  4850 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:08:00.008  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 19:08:00.008  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 19:08:00.008  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:00.008  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:00.008  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:00.008  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:00.008  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:08:00.018  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-02 19:08:00.018  1178  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-02 19:08:00.018  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:08:00.018  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:00.018  1178  1178 D HotspotTile: onReceive : 2, 0
,09-02 19:08:00.018  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:00.048  7618  7618 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-02 19:08:00.048  7618  7618 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-02 19:08:00.048  7618  7618 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-02 19:08:00.058  7618  7618 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-02 19:08:00.068   399   399 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7618
09-02 19:08:00.068   399   399 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
09-02 19:08:00.068  7618  7618 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-02 19:08:00.068  7618  7618 I wpa_supplicant: ssSupport state is = 1
09-02 19:08:00.068  7618  7618 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-02 19:08:00.068  7618  7618 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-02 19:08:00.068   399   399 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7618
09-02 19:08:00.068   399   399 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-02 19:08:00.148  1019  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 19:08:00.158  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:00.158  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:00.158  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-02 19:08:00.178  7582  7582 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-02 19:08:00.198  7582  7582 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 9444-9446)
09-02 19:08:00.198  7582  7582 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-02 19:08:00.208  7582  7582 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {28548f4e}
,09-02 19:08:00.208  7582  7582 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-02 19:08:00.208  7582  7582 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-02 19:08:00.228  7582  7582 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
09-02 19:08:00.228  7582  7582 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-02 19:08:00.228  7582  7582 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-02 19:08:00.248  7582  7582 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-02 19:08:00.248  7582  7582 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-02 19:08:00.248  7582  7582 I Adreno-EGL: Build Date: 04/06/15 Mon
09-02 19:08:00.248  7582  7582 I Adreno-EGL: Local Branch: 
09-02 19:08:00.248  7582  7582 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-02 19:08:00.248  7582  7582 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-02 19:08:00.248  7582  7582 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-02 19:08:00.258   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,09-02 19:08:00.258  7618  7618 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-02 19:08:00.308  7582  7582 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-02 19:08:00.308  7582  7641 W cr.media: Requires BLUETOOTH permission
,09-02 19:08:00.318  7582  7582 I NSApplication: Starting up...
,09-02 19:08:00.318  7618  7618 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-02 19:08:00.318  1019  1505 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
09-02 19:08:00.318  7618  7618 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-02 19:08:00.318  1019  1488 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-02 19:08:00.328  1019  1367 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-02 19:08:00.328  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.328  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.328  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.328  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.328  7618  7618 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
09-02 19:08:00.328   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7618
09-02 19:08:00.328   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-02 19:08:00.328  7618  7618 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-02 19:08:00.328  7618  7618 I wpa_supplicant: ssSupport state is = 1
,09-02 19:08:00.328  7618  7618 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-02 19:08:00.338  7618  7618 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 19:08:00.338  7618  7618 E wpa_supplicant: SIM READ ERROR
09-02 19:08:00.338  1019  1367 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7647 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-02 19:08:00.338  7618  7618 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:00.338  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:08:00.338  7618  7618 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 19:08:00.338  7618  7618 E wpa_supplicant: SIM READ ERROR
09-02 19:08:00.338  7618  7618 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 19:08:00.338  7618  7618 I wpa_supplicant: wpa_default_ap_write_once
09-02 19:08:00.338  7618  7618 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-02 19:08:00.338  7618  7618 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:00.338  7618  7618 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-02 19:08:00.338  7618  7618 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:00.338  7618  7618 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 19:08:00.338  7618  7618 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 19:08:00.338  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:00.338  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:08:00.338  1019  1367 I ActivityManager: Killing 6761:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-02 19:08:00.338  7647  7647 E Zygote  : MountEmulatedStorage()
09-02 19:08:00.338  7647  7647 E Zygote  : v2
09-02 19:08:00.338  7647  7647 I libpersona: KNOX_SDCARD checking this for 10117
09-02 19:08:00.338  7647  7647 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:00.348  7647  7647 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 19:08:00.348  7647  7647 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 19:08:00.348  7647  7647 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-02 19:08:00.368  7647  7647 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:00.368  7647  7647 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:00.378  7647  7647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-02 19:08:00.418  7618  7618 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-02 19:08:00.668  7618  7618 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-02 19:08:00.668  7618  7618 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-02 19:08:00.688  7618  7618 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-02 19:08:00.688   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7618
09-02 19:08:00.688   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-02 19:08:00.688  7618  7618 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
,09-02 19:08:00.688  7618  7618 I wpa_supplicant: ssSupport state is = 1
,09-02 19:08:00.708  7618  7618 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-02 19:08:00.708  7618  7618 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-02 19:08:00.718  1019  1097 V AlarmManager: waitForAlarm result :4
,09-02 19:08:00.718  7618  7618 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
09-02 19:08:00.718   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7618
09-02 19:08:00.718   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-02 19:08:00.718  7618  7618 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-02 19:08:00.718  7618  7618 I wpa_supplicant: ssSupport state is = 1
09-02 19:08:00.718  7618  7618 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:00.718  7618  7618 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 19:08:00.718  7618  7618 E wpa_supplicant: SIM READ ERROR
09-02 19:08:00.718  7618  7618 I wpa_supplicant: wpa_default_ap_write_once
09-02 19:08:00.718  7618  7618 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-02 19:08:00.718  7618  7618 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-02 19:08:00.718  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false,
09-02 19:08:00.718  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 19:08:00.718  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
09-02 19:08:00.718  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 19:08:00.718  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-02 19:08:00.728  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
09-02 19:08:00.728  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 19:08:00.728  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,09-02 19:08:00.728  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-02 19:08:00.738  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,09-02 19:08:00.738  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-02 19:08:00.738  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
09-02 19:08:00.738  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,09-02 19:08:00.768  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-02 19:08:00.768  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,09-02 19:08:00.778  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-02 19:08:00.778  1019  4259 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-02 19:08:00.778  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.778  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.778  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.778  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.788  7618  7618 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-02 19:08:00.788  7618  7618 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-02 19:08:00.788  7671  7671 E Zygote  : MountEmulatedStorage()
,09-02 19:08:00.788  7671  7671 I libpersona: KNOX_SDCARD checking this for 10121
09-02 19:08:00.788  7671  7671 E Zygote  : v2
09-02 19:08:00.788  7671  7671 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:00.788  7671  7671 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-02 19:08:00.798  1019  4259 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7671 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,09-02 19:08:00.798  1019  4259 I ActivityManager: Killing 6743:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
,09-02 19:08:00.798  7671  7671 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 19:08:00.798  7671  7671 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:00.808  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-02 19:08:00.828  7671  7671 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:00.828  7671  7671 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:00.848  7671  7671 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:08:00.848  7671  7671 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-02 19:08:00.848  7671  7671 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-02 19:08:00.858  7671  7671 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:08:00.858  7671  7671 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-02 19:08:00.868  7671  7671 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-02 19:08:00.868  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-02 19:08:00.868  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.868  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.868  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:00.868  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:00.878  7688  7688 E Zygote  : MountEmulatedStorage()
,09-02 19:08:00.888  7688  7688 E Zygote  : v2
09-02 19:08:00.888  7688  7688 I libpersona: KNOX_SDCARD checking this for 10141
,09-02 19:08:00.888  7688  7688 I libpersona: KNOX_SDCARD not a persona,
,09-02 19:08:00.888  7688  7688 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-02 19:08:00.888  1019  1031 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7688 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,09-02 19:08:00.888  1019  1031 I ActivityManager: Killing 7139:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-02 19:08:00.888  7688  7688 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 19:08:00.888  7688  7688 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:00.908  7618  7618 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
,09-02 19:08:00.908  7618  7618 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-02 19:08:00.908  7618  7618 I wpa_supplicant: Skip scan - bUseNetwork false
,09-02 19:08:00.918  7688  7688 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:00.918  7688  7688 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:00.928  7688  7688 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-02 19:08:00.928  7688  7688 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:08:00.928  7688  7688 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 19:08:00.928  7688  7688 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-02 19:08:00.968  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
,09-02 19:08:00.968  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-02 19:08:00.968  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 19:08:00.998  1019  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-02 19:08:01.008  1019  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-02 19:08:01.008  7618  7618 I wpa_supplicant: HOTSPOT20_ENABLE called
09-02 19:08:01.008  7618  7618 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:01.008  7618  7618 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 19:08:01.008  7618  7618 E wpa_supplicant: SIM READ ERROR
09-02 19:08:01.008  7618  7618 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 19:08:01.008  1019  1488 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 19:08:01.028  1019  1338 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 19:08:01.048  7618  7618 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-02 19:08:01.048  7618  7618 I wpa_supplicant: Skip scan - bUseNetwork false
,09-02 19:08:01.048  1019  1127 D WifiConfigStore: Loading config and enabling all networks 
,09-02 19:08:01.058  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-02 19:08:01.058  1019  1127 E WifiConfigStore: Not a HS20
,09-02 19:08:01.058  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:01.058  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 19:08:01.058  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:01.058  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:01.058  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:01.058  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:01.058  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:01.058  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:08:01.058  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-02 19:08:01.058  1019  1219 D RCPManagerService: exchangeData() failure , invalid userId
09-02 19:08:01.068  1178  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-02 19:08:01.068  4850  4850 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:08:01.068  1178  1178 D HotspotTile: onReceive : 3, 0
,09-02 19:08:01.068  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:08:01.068  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:01.068  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:01.068  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:01.068  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:01.068  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:08:01.068  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:01.068  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:01.068  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:01.068  1019  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-02 19:08:01.068  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:08:01.068  7226  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:08:01.068  1019  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-02 19:08:01.068  7618  7618 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-02 19:08:01.068  7618  7618 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-02 19:08:01.068  7618  7618 I wpa_supplicant: reset timer : RESET_TIMER 0
09-02 19:08:01.068  7618  7618 I wpa_supplicant: P2P: Current p2p state = IDLE
09-02 19:08:01.068  7618  7618 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-02 19:08:01.068  7618  7618 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-02 19:08:01.068  7618  7618 I wpa_supplicant: First Scan Start
,09-02 19:08:01.078  7618  7618 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-02 19:08:01.078  1019  1127 D WifiNative-wlan0: Setting external_sim to 1
,09-02 19:08:01.078  1019  1127 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 19:08:01.078  1019  1127 I WifiNative-HAL: startHal
09-02 19:08:01.078  1019  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9efa888c
09-02 19:08:01.078  1019  1127 I WifiNative-HAL: Could not start hal
,09-02 19:08:01.078  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:08:01.078  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:01.078  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:01.078  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:01.078  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:01.078  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:08:01.078  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:01.078  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:01.078  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:01.078  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:08:01.078  1019  1127 E WifiNative-wlan0: do suspend true
09-02 19:08:01.078  7226  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:08:01.078  7416  7416 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:08:01.078  1019  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-02 19:08:01.078  1019  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-02 19:08:01.078  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
,09-02 19:08:01.078  1019  1152 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 19:08:01.088  1019  1152 I WifiNative-HAL: startHal
,09-02 19:08:01.088  1019  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-02 19:08:01.088  1019  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-02 19:08:01.088  1019  1127 E WifiNative-wlan0: invaild command id : 215
,09-02 19:08:01.088  1019  1019 D RttService: SCAN_AVAILABLE : 3
09-02 19:08:01.088  1019  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9de6a9bc
09-02 19:08:01.088  1019  1152 I WifiNative-HAL: Could not start hal
09-02 19:08:01.088  1019  1152 E WifiScanningService: could not start HAL
,09-02 19:08:01.088   278   981 D CommandListener: Setting iface cfg
09-02 19:08:01.088  1019  1153 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:08:01.088   278   981 D CommandListener: Trying to bring up p2p0
,09-02 19:08:01.088  7618  7618 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-02 19:08:01.088  1019  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-02 19:08:01.088  7618  7618 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-02 19:08:01.088  1019  1126 D WifiP2pService: P2pEnablingState,
09-02 19:08:01.088  1019  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
09-02 19:08:01.088  1019  1126 D WifiP2pService: P2p socket connection successful
,09-02 19:08:01.088  1019  1126 D WifiP2pService: P2pEnabledState
,09-02 19:08:01.088  7618  7618 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-02 19:08:01.088  1019  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-02 19:08:01.088  1019  1127 E WifiStateMachine: Failed to set frequency band 0
,09-02 19:08:01.088  1019  1338 D RCPManagerService: exchangeData() failure , invalid userId
09-02 19:08:01.088  1019  1129 E ConnectivityService: updateNetworkInfo()
,09-02 19:08:01.088  1019  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 19:08:01.088  1019  1127 D SecContentProvider2: mCursor = null
,09-02 19:08:01.098  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-02 19:08:01.098  1019  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,09-02 19:08:01.098  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 19:08:01.098  1019  1049 D WifiDisplayController: disconnect
,09-02 19:08:01.098  1019  1049 D WifiDisplayController: updateConnection
09-02 19:08:01.098  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-02 19:08:01.098  1019  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 19:08:01.098  1019  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 19:08:01.098  1019  1127 D SecContentProvider2: mCursor = null
,09-02 19:08:01.098  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:08:01.098  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
09-02 19:08:01.098  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 19:08:01.098  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-02 19:08:01.108  1019  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,09-02 19:08:01.108  1019  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,09-02 19:08:01.108  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-02 19:08:01.108  1019  4273 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-02 19:08:01.108  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-02 19:08:01.108  1019  1049 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-02 19:08:01.108  1019  1049 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-02 19:08:01.108  1019  1049 D WifiDisplayController:  primary type: 10-0050F204-5
09-02 19:08:01.108  1019  1049 D WifiDisplayController:  secondary type: null
09-02 19:08:01.108  1019  1049 D WifiDisplayController:  wps: 0
09-02 19:08:01.108  1019  1049 D WifiDisplayController:  grpcapab: 0
09-02 19:08:01.108  1019  1049 D WifiDisplayController:  devcapab: 0
09-02 19:08:01.108  1019  1049 D WifiDisplayController:  status: 3
09-02 19:08:01.108  1019  1049 D WifiDisplayController:  wfdInfo: null
09-02 19:08:01.108  1019  1049 D WifiDisplayController:  groupownerAddress: null
09-02 19:08:01.108  1019  1049 D WifiDisplayController:  GOdeviceName: null
09-02 19:08:01.108  1019  1049 D WifiDisplayController:  interfaceAddress: 
09-02 19:08:01.108  1019  1049 D WifiDisplayController:  SConnectInfo : null
,09-02 19:08:01.108  1019  1126 D WifiP2pService: DeviceAddress: 0a:75:42
,09-02 19:08:01.128  1019  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-02 19:08:01.128  1019  1126 D WifiP2pService: InactiveState
,09-02 19:08:01.128  1019  1126 D WifiP2pService: InactiveState{ what=143376 }
09-02 19:08:01.128  1019  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-02 19:08:01.128  7618  7618 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-02 19:08:01.128  1019  1126 D WifiP2pService: InactiveState{ what=143376 }
09-02 19:08:01.128  1019  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-02 19:08:01.148  1019  1367 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,09-02 19:08:01.158  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:01.158  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:01.158  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:01.158  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:01.168  7714  7714 E Zygote  : MountEmulatedStorage()
,09-02 19:08:01.168  7714  7714 I libpersona: KNOX_SDCARD checking this for 10068
09-02 19:08:01.168  7714  7714 E Zygote  : v2
09-02 19:08:01.168  7714  7714 I libpersona: KNOX_SDCARD not a persona
09-02 19:08:01.168  7714  7714 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 19:08:01.168  1019  1367 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7714 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,09-02 19:08:01.168  7714  7714 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 19:08:01.168  7714  7714 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-02 19:08:01.178  1019  4273 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 19:08:01.188  1019  1136 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 19:08:01.198  7714  7714 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:01.198  7714  7714 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:01.218  7714  7714 D BadgeProvider: onCreate
,09-02 19:08:01.218  7714  7714 D BadgeProvider: DatabaseHelper
,09-02 19:08:01.218  1019  1505 D RCPManagerService: exchangeData() failure , invalid userId
,09-02 19:08:01.218  1019  1497 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-02 19:08:01.218  1019  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:01.218  1019  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:01.218  1019  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:01.218  1019  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:01.238  7730  7730 E Zygote  : MountEmulatedStorage(),
09-02 19:08:01.238  7730  7730 I libpersona: KNOX_SDCARD checking this for 10009
09-02 19:08:01.238  7730  7730 E Zygote  : v2
09-02 19:08:01.238  7730  7730 I libpersona: KNOX_SDCARD not a persona
09-02 19:08:01.238  7730  7730 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 19:08:01.238  7730  7730 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 19:08:01.238  7730  7730 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-02 19:08:01.248  7714  7729 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-02 19:08:01.248  1019  1497 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7730 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,09-02 19:08:01.248  1019  1497 I ActivityManager: Killing 6355:com.samsung.android.sm/1000 (adj 15): empty #21
09-02 19:08:01.258  1019  1497 I ActivityManager: Killing 6956:com.android.vending/u0a26 (adj 15): empty #22
,09-02 19:08:01.278   315   315 I art     : Explicit concurrent mark sweep GC freed 8665(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 26.382ms
,09-02 19:08:01.278  7730  7730 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 19:08:01.278  7730  7730 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:01.288   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 17.660ms
,09-02 19:08:01.298  7714  7724 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,09-02 19:08:01.298  1487  1487 D Launcher.Model: reloadBadges entered.
09-02 19:08:01.298  7714  7724 D BadgeProvider: sendNotify, [notify] : null
09-02 19:08:01.298  7714  7724 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-02 19:08:01.298  7714  7724 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-02 19:08:01.298  7714  7724 D BadgeProvider: update, [UpdateCount] : 1
,09-02 19:08:01.308   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.817ms
,09-02 19:08:01.378  1019  1136 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-02 19:08:01.378  1019  1136 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:08:01.378  1019  1136 W ActivityManager: userId = 0, bbcId = -10000,
09-02 19:08:01.378  1019  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:01.378  1019  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,09-02 19:08:01.388  7400  7400 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 19:08:01.388  1663  1663 I Hs20UtilService: Starting #12
,09-02 19:08:01.388  1663  1703 I Hs20UtilService: Message received 5011
09-02 19:08:01.388  7400  7400 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 19:08:01.388  7400  7400 D SecurityLogAgent: StateMachine : Current State = 1
09-02 19:08:01.388  7400  7400 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 19:08:01.398  1019  1338 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 19:08:01.398  1019  1338 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:08:01.398  1019  1338 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:01.398  1019  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:01.398  1019  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:08:01.398  1663  1663 I Hs20UtilService: Starting #13
09-02 19:08:01.398  7400  7400 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 19:08:01.398  7400  7400 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 19:08:01.398  7400  7400 D SecurityLogAgent: StateMachine : Current State = 1
09-02 19:08:01.398  7400  7400 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 19:08:01.408  1663  1703 I Hs20UtilService: Message received 5011
,09-02 19:08:01.408  1019  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,09-02 19:08:01.408  1019  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-02 19:08:01.408  1019  1127 E WifiNative-wlan0: invaild command id : 215
,09-02 19:08:01.408   278   977 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-02 19:08:01.408   278   977 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-02 19:08:01.418  4850  4850 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-02 19:08:01.418  4850  4850 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 19:08:01.418  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,09-02 19:08:01.428  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 19:08:01.428  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:08:01.428  4850  4850 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 19:08:01.428  4850  4937 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 19:08:01.438  1019  4259 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-02 19:08:01.438  7368  7368 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 19:08:01.438  1019  4259 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-02 19:08:01.438  7368  7368 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-02 19:08:01.438  7368  7368 D FileShare-Client: Outbound.stopDelayTimer - 
,09-02 19:08:01.448  1019  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-02 19:08:01.448  7385  7385 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 19:08:01.448  1019  1494 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:01.448  1019  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:01.448  1019  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-02 19:08:01.448  1019  4273 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-02 19:08:01.458  1019  1219 I art     : Explicit concurrent mark sweep GC freed 55541(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.776ms total 156.032ms
,09-02 19:08:01.468  1019  1338 I ActivityManager: Killing 7306:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-02 19:08:02.288  7618  7618 I wpa_supplicant: nl80211: Received scan results (34 BSSes)
,09-02 19:08:02.298  7618  7618 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,09-02 19:08:02.298  1019  7704 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
09-02 19:08:02.298  7618  7618 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-02 19:08:02.298  7618  7618 I wpa_supplicant: Trying to associate with  'G700',
09-02 19:08:02.298  7618  7618 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,09-02 19:08:02.298  7618  7618 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,09-02 19:08:02.328  1019  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 19:08:02.328  1019  1127 D SecContentProvider2: mCursor = null
,09-02 19:08:02.418  7618  7618 E wpa_supplicant: Cmd 35605 not handled
,09-02 19:08:02.418  7618  7618 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-02 19:08:02.418  7618  7618 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-02 19:08:02.418  7618  7618 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-02 19:08:02.418  7618  7618 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-02 19:08:02.418  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:02.418  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:08:02.418  7618  7618 I wpa_supplicant: Associated with F4.99.3E
,09-02 19:08:02.418  7618  7618 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-02 19:08:02.418  7618  7618 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-02 19:08:02.418  7618  7618 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-02 19:08:02.418  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 19:08:02.418  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:02.418  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:08:02.418  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:08:02.428  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:02.428  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:08:02.428  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 19:08:02.428  7618  7618 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-02 19:08:02.428  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, true
09-02 19:08:02.428  1019  1046 D Tethering: interfaceStatusChanged wlan0, true
09-02 19:08:02.428  7618  7618 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-02 19:08:02.428  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-02 19:08:02.428  1019  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 19:08:02.428  1019  1127 D SecContentProvider2: mCursor = null
,09-02 19:08:02.428  7618  7618 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-02 19:08:02.428  7618  7618 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-02 19:08:02.428  7618  7618 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 19:08:02.428  7618  7618 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-02 19:08:02.428  7618  7618 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-02 19:08:02.428  1019  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 19:08:02.428  7618  7618 I wpa_supplicant: Blacklist: Clear (temp) 
09-02 19:08:02.428  1019  1127 D SecContentProvider2: mCursor = null
09-02 19:08:02.428  7618  7618 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-02 19:08:02.438  1019  1131 E Tethering: No numeric data
09-02 19:08:02.438  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, true
09-02 19:08:02.438  1019  1046 D Tethering: interfaceStatusChanged wlan0, true
09-02 19:08:02.438  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-02 19:08:02.438  1019  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-02 19:08:02.438  1019  1131 D Tethering: clearTetheredNotification()
09-02 19:08:02.438  1019  1124 V NetworkStats: performPollLocked(flags=0x1)
09-02 19:08:02.438  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:02.438  1019  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-02 19:08:02.438  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-02 19:08:02.438  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 19:08:02.438  1178  1178 D HotspotTile: updateTetherState():false, false
09-02 19:08:02.438  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 19:08:02.438  1019  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,09-02 19:08:02.448  1019  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,09-02 19:08:02.448  1019  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-02 19:08:02.448  1019  1129 E ConnectivityService: updateNetworkInfo()
09-02 19:08:02.448  1019  1124 V NetworkStats: performPollLocked() took 6ms
09-02 19:08:02.448  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:02.448  1019  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-02 19:08:02.458  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-02 19:08:02.458  1019  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 19:08:02.458  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:02.458  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-02 19:08:02.458  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.458  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.458  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.458  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:02.458  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:02.458  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:02.458  1019  4260 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 19:08:02.458  1019  4260 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:08:02.458  1019  4260 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:02.458  1019  4260 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:02.458  1019  4260 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:08:02.468  1663  1663 I Hs20UtilService: Starting #14
,09-02 19:08:02.468  1663  1703 I Hs20UtilService: Message received 5007
,09-02 19:08:02.468  1019  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 19:08:02.468  4850  4850 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-02 19:08:02.478  4850  4850 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 19:08:02.478  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-02 19:08:02.478   278   981 D CommandListener: Setting iface cfg
,09-02 19:08:02.478  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-02 19:08:02.478  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:08:02.478  4850  4850 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 19:08:02.478  4850  4937 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 19:08:02.488  1019  1127 E WifiStateMachine: Start Dhcp Watchdog 2
,09-02 19:08:02.488  1019  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 19:08:02.488  1019  1127 D SecContentProvider2: mCursor = null
,09-02 19:08:02.498  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-02 19:08:02.498  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 19:08:02.508  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-02 19:08:02.508  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.508  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.508  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.508  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:02.508  1019  1127 E WifiNative-wlan0: do suspend false
,09-02 19:08:02.508  1019  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-02 19:08:02.508  1019  1126 D WifiP2pService: P2pEnabledState{ what=143375 },
09-02 19:08:02.508  1019  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 19:08:02.508  1019  1127 D SecContentProvider2: mCursor = null
,09-02 19:08:02.598  1019  1494 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-02 19:08:02.598  1019  1494 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-02 19:08:02.598  1019  1494 D SecContentProvider2: mCursor = null
,09-02 19:08:02.598  1019  1494 D WifiService: setWifiEnabled: false pid=7226, uid=10170
,09-02 19:08:02.598  1019  1494 D SettingsProvider: name = wifi_on
,09-02 19:08:02.608  1019  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 19:08:02.618  1019  1127 E WifiNative-wlan0: do suspend true,
,09-02 19:08:02.638  1019  1126 D WifiP2pService: InactiveState{ what=143375 },
,09-02 19:08:02.638  1019  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-02 19:08:02.638   278   981 D CommandListener: Clearing all IP addresses on wlan0
,09-02 19:08:02.648  1019  1129 E ConnectivityService: updateNetworkInfo()
,09-02 19:08:02.648  1019  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:08:02.648  1019  1129 E ConnectivityService: updateNetworkInfo()
09-02 19:08:02.648  1019  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-02 19:08:02.658   278   981 E Netd    : no such netId 503
,09-02 19:08:02.658  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-02 19:08:02.658  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:02.658  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 19:08:02.658  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.658  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.658  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.658  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.658  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-02 19:08:02.668  1019  1129 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
,09-02 19:08:02.668  1019  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-02 19:08:02.668  1019  1129 V NetworkStats: updateIfacesLocked()
,09-02 19:08:02.668  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
09-02 19:08:02.668  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:02.678  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 19:08:02.678  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 19:08:02.678  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
,09-02 19:08:02.678  1019  1152 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 19:08:02.678  1019  1019 D RttService: SCAN_AVAILABLE : 1
,09-02 19:08:02.678  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit,
09-02 19:08:02.678  1019  1129 V NetworkStats: performPollLocked() took 8ms
09-02 19:08:02.678  1019  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 19:08:02.678  1019  1126 D WifiP2pService: InactiveState{ what=131204 }
09-02 19:08:02.678  1019  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-02 19:08:02.688  1019  1153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:08:02.688  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:02.688  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:02.688  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-02 19:08:02.688  1019  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-02 19:08:02.688  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:02.688  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 19:08:02.688  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.688  1019  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-02 19:08:02.688  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:02.688  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.688  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.688  1019  1129 D ConnectivityService: nai.networkMonitor.doQuit()
09-02 19:08:02.688  1019  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-02 19:08:02.688  1019  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-02 19:08:02.688  1019  7750 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 19:08:02.688  1019  1129 E ConnectivityService: updateNetworkInfo()
09-02 19:08:02.688  1019  7750 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,09-02 19:08:02.688  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:08:02.688  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
09-02 19:08:02.688  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 19:08:02.688  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
09-02 19:08:02.688  1019  1129 E ConnectivityService: updateNetworkInfo()
09-02 19:08:02.688  1019  1497 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 19:08:02.688  1019  1497 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:02.688  1019  1497 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 19:08:02.688  1019  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:02.688  1019  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-02 19:08:02.688  1019  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:08:02.698  1663  1663 I Hs20UtilService: Starting #15
,09-02 19:08:02.698  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-02 19:08:02.698  1663  1703 I Hs20UtilService: Message received 5007
,09-02 19:08:02.698  1019  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,09-02 19:08:02.698  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 19:08:02.698  1019  1049 D WifiDisplayController: disconnect
,09-02 19:08:02.698  1019  1049 D WifiDisplayController: updateConnection
09-02 19:08:02.698  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-02 19:08:02.698  1019  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 19:08:02.698  1019  1126 D WifiP2pService: P2pDisablingState
,09-02 19:08:02.698  1019  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
09-02 19:08:02.698  1019  1126 D WifiP2pService: p2p socket connection lost
,09-02 19:08:02.698  1019  1127 E WifiNative-wlan0: do suspend true
09-02 19:08:02.698  1019  1126 D WifiP2pService: P2pDisabledState
,09-02 19:08:02.708  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false],
09-02 19:08:02.708  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
09-02 19:08:02.708  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 19:08:02.708  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null,
09-02 19:08:02.708  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-02 19:08:02.708  1019  1031 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
09-02 19:08:02.708  4850  4850 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-02 19:08:02.708  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-02 19:08:02.708  4850  4850 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 19:08:02.708  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 19:08:02.708  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-02 19:08:02.708  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:08:02.708  4850  4850 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 19:08:02.718  4850  4937 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 19:08:02.728  4850  4850 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-02 19:08:02.728  4850  4850 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-02 19:08:02.728  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-02 19:08:02.728  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 19:08:02.728  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:08:02.728  4850  4850 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 19:08:02.728  4850  4937 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-02 19:08:02.728  7368  7368 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-02 19:08:02.728  7368  7368 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-02 19:08:02.728  7368  7368 D FileShare-Client: Outbound.stopDelayTimer - 
,09-02 19:08:02.728  1019  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
09-02 19:08:02.728  1019  1126 D WifiP2pService: DefaultState{ what=143375 }
,09-02 19:08:02.728  7753  7753 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-02 19:08:02.738  7753  7753 I dhcpcd  : version 5.5.6 starting
,09-02 19:08:02.738   278   981 D CommandListener: Clearing all IP addresses on wlan0
,09-02 19:08:02.738  7753  7753 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-02 19:08:02.738  7385  7385 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 19:08:02.748  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-02 19:08:02.748  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:02.748  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 19:08:02.748  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.748  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.748  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.748  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.748  7618  7618 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-02 19:08:02.748  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-02 19:08:02.768  1019  4259 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 19:08:02.768  1019  4259 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:08:02.768  1019  4259 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:02.768  1019  4259 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:02.768  1019  4259 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-02 19:08:02.768  1019  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 19:08:02.768  1019  1127 D SecContentProvider2: mCursor = null
,09-02 19:08:02.768  1663  1663 I Hs20UtilService: Starting #16,
,09-02 19:08:02.768  1663  1703 I Hs20UtilService: Message received 5007
,09-02 19:08:02.778  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-02 19:08:02.778  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:02.778  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 19:08:02.778  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.778  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.778  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.778  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:02.788   288   288 E SMD     : DCD OFF
,09-02 19:08:02.798  4850  4850 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:08:02.798  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:08:02.798  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:02.798  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:02.798  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:02.798  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:08:02.798  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:08:02.798  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:02.798  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:02.798  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:02.798  4850  4850 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-02 19:08:02.798  4850  4850 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 19:08:02.808  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-02 19:08:02.808  7226  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:02.808  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-02 19:08:02.808  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 19:08:02.808  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-02 19:08:02.808  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-02 19:08:02.808  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:02.808  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:02.808  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:08:02.808  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:08:02.808  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:02.808  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:02.808  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:08:02.808  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
09-02 19:08:02.808  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:08:02.808  4850  4850 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-02 19:08:02.808  4850  4937 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-02 19:08:02.808  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 19:08:02.808  7226  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:08:02.808  7753  7753 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-02 19:08:02.808  7753  7753 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-02 19:08:02.808  7753  7753 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-02 19:08:02.818  7753  7753 I dhcpcd  : bssid match
09-02 19:08:02.818  7753  7753 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-02 19:08:02.828  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 19:08:02.828  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 19:08:02.828  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:02.828  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:02.838  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.838  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:02.838  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:02.838  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:02.838  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-02 19:08:02.838  1178  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-02 19:08:02.838  1178  1178 D HotspotTile: onReceive : 0, 0
,09-02 19:08:02.848  1019  1136 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 19:08:02.848  1019  1136 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
09-02 19:08:02.848  1019  1136 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:02.848  1019  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-02 19:08:02.848  1019  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-02 19:08:02.848  1663  1663 I Hs20UtilService: Starting #17
09-02 19:08:02.848  1663  1703 I Hs20UtilService: Message received 5011
,09-02 19:08:02.848  7400  7400 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 19:08:02.848  7400  7400 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 19:08:02.848  7400  7400 D SecurityLogAgent: StateMachine : Current State = 1
09-02 19:08:02.848  7400  7400 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 19:08:02.868  7618  7618 I wpa_supplicant: Blacklist: Clear (all) ,
,09-02 19:08:02.868  7753  7753 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,09-02 19:08:02.968  7753  7753 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,09-02 19:08:02.998  7618  7618 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-02 19:08:02.998  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 19:08:02.998  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 19:08:02.998  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-02 19:08:03.018  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false,
09-02 19:08:03.018  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:08:03.018  1019  1046 D Tethering: interfaceStatusChanged wlan0, false,
09-02 19:08:03.018  1019  1131 D Tethering: InitialState.processMessage what=4
09-02 19:08:03.028  7618  7618 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-02 19:08:03.028  7618  7618 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-02 19:08:03.028  7618  7618 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e,
09-02 19:08:03.028  7618  7618 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-02 19:08:03.028  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:08:03.028  7618  7618 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-02 19:08:03.028  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:08:03.028  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:03.028  1019  1124 V NetworkStats: performPollLocked(flags=0x1)
09-02 19:08:03.028  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:08:03.038  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 19:08:03.028  1019  1131 E Tethering: No numeric data
09-02 19:08:03.038  1178  1178 D HotspotTile: updateTetherState():false, false
,09-02 19:08:03.028  1019  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 19:08:03.028  1019  1131 D Tethering: clearTetheredNotification()
09-02 19:08:03.028  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:03.028  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:08:03.038  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:03.038  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-02 19:08:03.038  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 19:08:03.038  1019  1124 V NetworkStats: performPollLocked() took 6ms
09-02 19:08:03.038  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:03.038  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:03.038  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:03.328  7618  7618 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 19:08:03.368  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,09-02 19:08:03.368  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:08:03.368  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 19:08:03.368  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,09-02 19:08:03.368  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:08:03.368  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 19:08:03.368  7618  7618 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,09-02 19:08:03.448  1019  3349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-02 19:08:03.478  1019  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-02 19:08:03.478  1019  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-02 19:08:03.488  7416  7416 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:08:03.488  1758  2203 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:08:03.488  4850  4850 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:08:03.498  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:03.498  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-02 19:08:03.498  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:03.498  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-02 19:08:03.498  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:03.498  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:03.498  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:03.498  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:03.498  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:03.498  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:03.498  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-02 19:08:03.498  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:08:03.498  1178  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-02 19:08:03.498  1178  1178 D HotspotTile: onReceive : 1, 0
,09-02 19:08:03.498  1019  1136 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 19:08:03.498  1019  1136 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:08:03.498  1019  1136 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:03.498  1019  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:03.498  1019  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:08:03.508  1663  1663 I Hs20UtilService: Starting #18
,09-02 19:08:03.508  7400  7400 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-02 19:08:03.508  7400  7400 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-02 19:08:03.508  1663  1703 I Hs20UtilService: Message received 5011
,09-02 19:08:03.508  7400  7400 D SecurityLogAgent: StateMachine : Current State = 1
,09-02 19:08:03.508  7400  7400 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 19:08:04.138  1019  3325 D SSRM:n  : SIOP:: AP = 340
,09-02 19:08:04.178   278   975 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-02 19:08:04.178  1019  1046 D Tethering: interfaceRemoved wlan0
,09-02 19:08:04.188  1019  1046 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-02 19:08:04.348  1019  1046 D Tethering: interfaceRemoved p2p0
,09-02 19:08:04.348  1019  1046 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-02 19:08:05.168  1019  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-02 19:08:05.398   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 19:08:05.608  7226  7279 D BluetoothAdapter: enable()
,09-02 19:08:05.608  1019  1497 W ActivityManager: Permission Denial: getCurrentUser() from pid=7226, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-02 19:08:05.618  1019  1497 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-02 19:08:05.618  1019  1497 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7226, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-02 19:08:05.618  1019  1497 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-02 19:08:05.618  1019  1497 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-02 19:08:05.618  1019  1497 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-02 19:08:05.618  1019  1497 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-02 19:08:05.618  1019  1497 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-02 19:08:05.618  1019  1497 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-02 19:08:05.618  1019  1497 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 19:08:05.618  1019  1497 D SettingsProvider: name = bluetooth_on,
,09-02 19:08:05.628  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-02 19:08:05.628  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 19:08:05.628  1019  1048 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-02 19:08:05.638  3188  3262 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON,
09-02 19:08:05.638  1019  1219 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:05.638  3188  3262 D BluetoothAdapterProperties: Setting state to 11
09-02 19:08:05.638  1019  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-02 19:08:05.638  3188  3262 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-02 19:08:05.638  3188  3262 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 19:08:05.638  3188  3262 D BluetoothAdapterService: updateAdapterState state is 11
09-02 19:08:05.638  3188  3262 D BluetoothAdapterService: Autoconnection is available 
09-02 19:08:05.638  3188  3262 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-02 19:08:05.638  3188  3262 D BtConfig.SecureMode: isSecureModeOn:false
09-02 19:08:05.638  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-02 19:08:05.638  3188  3262 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-02 19:08:05.638  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-02 19:08:05.638  3188  3262 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-02 19:08:05.638  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-02 19:08:05.638  3188  3262 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-02 19:08:05.638  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 19:08:05.638  3188  3262 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-02 19:08:05.638  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-02 19:08:05.638  3188  3262 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-02 19:08:05.638  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-02 19:08:05.638  3188  3262 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-02 19:08:05.638  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:05.638  3188  3262 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-02 19:08:05.638  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 19:08:05.638  3188  3262 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-02 19:08:05.638  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService,
09-02 19:08:05.638  3188  3262 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:05.648  1019  1219 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:05.638  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:05.648  1019  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-02 19:08:05.638  3188  3262 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:05.638  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-02 19:08:05.638  3188  3262 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-02 19:08:05.638  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-02 19:08:05.638  3188  3262 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-02 19:08:05.638  3188  3262 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-02 19:08:05.638  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,09-02 19:08:05.638  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-02 19:08:05.638  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-02 19:08:05.638  1019  1219 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.638  1019  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.638  1019  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:08:05.638  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-02 19:08:05.638  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-02 19:08:05.638  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-02 19:08:05.648  3188  3188 D HeadsetService: Received start request. Starting profile...
09-02 19:08:05.648  3188  3188 D HeadsetService: start()
09-02 19:08:05.648  3188  3188 D HeadsetStateMachine: make
09-02 19:08:05.648  1019  1219 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.648  1019  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.648  1019  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:08:05.648  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-02 19:08:05.648  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 19:08:05.648  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-02 19:08:05.648  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:05.648  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
,09-02 19:08:05.648  3188  3188 E HeadsetStateMachine: # of Max HF connection is 2
,09-02 19:08:05.668  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 19:08:05.668  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:05.668  1178  1178 D BluetoothTile:  getBluetoothState : 11
,09-02 19:08:05.668  1178  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:08:05.668  1178  1731 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-02 19:08:05.668  1869  1869 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 19:08:05.678  1019  1485 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 19:08:05.678  4850  4850 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED,
09-02 19:08:05.678  1019  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-02 19:08:05.678  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-02 19:08:05.678  1019  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:05.678  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:08:05.678  1019  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.678  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-02 19:08:05.678  1019  1136 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.678  1019  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.678  1019  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:05.678  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:05.678  1019  1367 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-02 19:08:05.678  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.678  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-02 19:08:05.678  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-02 19:08:05.678  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-02 19:08:05.688  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.688  1019  1367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.688  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-02 19:08:05.688  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:05.688  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.688  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.688  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.688  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:05.688  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,09-02 19:08:05.688  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-02 19:08:05.688  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-02 19:08:05.688  1019  4259 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-02 19:08:05.688  1019  4259 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.688  1019  4259 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-02 19:08:05.688  1019  4259 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.688  1019  4259 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom,
,09-02 19:08:05.688  3188  3188 I bluedroid: get_profile_interface handsfree
09-02 19:08:05.688  1019  1219 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:05.688  1019  1219 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.688  1019  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.688  1019  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.688  1019  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:05.698  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-02 19:08:05.698  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:05.698  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-02 19:08:05.698  1019  4273 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,09-02 19:08:05.698  1019  4273 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-02 19:08:05.698  1019  4273 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.698  1019  4273 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.698  1019  4273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:05.698  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-02 19:08:05.698  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 19:08:05.698  3188  3262 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-02 19:08:05.708  1636  1636 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 19:08:05.708  1019  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:05.708  4850  4850 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 19:08:05.708  3188  3188 E DualScoManager: Dual Sco Manager already instantiated
09-02 19:08:05.708  3188  3188 I DualScoManager: Set HeadsetServiceHelper
09-02 19:08:05.708  3188  3188 D BluetoothAtMessage: createCMTIContentObservers
09-02 19:08:05.708  1019  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.718  1019  1505 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-02 19:08:05.718  1019  1505 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:08:05.718  1019  1505 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:08:05.718  1019  1505 D SettingsProvider: selectionArgs: false
09-02 19:08:05.718  1019  1505 D SettingsProvider: selectionArgs: 1002
09-02 19:08:05.718  1019  1488 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:05.718  1019  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.718  1019  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:08:05.718  1019  1505 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:05.718  1019  1505 D SettingsProvider: ret = -1
,09-02 19:08:05.718  3188  7783 D HeadsetStateMachine: Enter Disconnected: -2
,09-02 19:08:05.718  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 19:08:05.718  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService,
09-02 19:08:05.718  3188  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:05.718  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:05.718  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:05.718  3188  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:05.718  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-02 19:08:05.718  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-02 19:08:05.718  3188  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-02 19:08:05.718  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-02 19:08:05.718  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-02 19:08:05.718  3188  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-02 19:08:05.718  3188  3262 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-02 19:08:05.718  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:05.718  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
09-02 19:08:05.718  3188  3188 D HeadsetService: mStartError = false
09-02 19:08:05.718  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:08:05.728  3188  3188 D A2dpService: Received start request. Starting profile...
,09-02 19:08:05.728  3188  3188 D A2dpService: start()
09-02 19:08:05.728  3188  3188 I bluedroid: get_profile_interface avrcp
,09-02 19:08:05.728  3188  7783 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-02 19:08:05.728  1019  4273 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
09-02 19:08:05.728  3188  7783 D HeadsetStateMachine: map size, before remove : 0,
,09-02 19:08:05.728  1019  4273 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:05.728  3188  7783 D HeadsetStateMachine: map size, after remove: 0
09-02 19:08:05.728  1019  4273 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:05.728  3188  3188 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController,
09-02 19:08:05.728  1019  4273 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:05.728  3188  3188 D Avrcp   : Initialize Media Controller
09-02 19:08:05.728  1019  4273 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:05.728  3188  3188 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-02 19:08:05.728  3188  3188 E Avrcp   : getActiveSessions
09-02 19:08:05.728  3188  3188 D Avrcp   : pick active media Controller
09-02 19:08:05.728  3188  3188 D Avrcp   : Get the active Media Controller 
,09-02 19:08:05.748  7785  7785 E Zygote  : MountEmulatedStorage()
,09-02 19:08:05.748  7785  7785 E Zygote  : v2
09-02 19:08:05.748  7785  7785 I libpersona: KNOX_SDCARD checking this for 10055
09-02 19:08:05.748  7785  7785 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 19:08:05.748  7785  7785 I libpersona: KNOX_SDCARD not a persona
09-02 19:08:05.748  7785  7785 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 19:08:05.748  1019  4273 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7785 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
09-02 19:08:05.748  7785  7785 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:05.758  3188  3188 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-02 19:08:05.758  3188  7784 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
09-02 19:08:05.758  3188  3188 D A2dpStateMachine: make
,09-02 19:08:05.758  3188  3188 I bluedroid: get_profile_interface a2dp
,09-02 19:08:05.758  3188  7793 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-02 19:08:05.768  3188  3188 E bt-btif : warning : media task started media_task_refcnt 1 
,09-02 19:08:05.768  3188  3188 D A2dpService: mStartError = false
09-02 19:08:05.768  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:08:05.768  3188  3188 D HidService: Received start request. Starting profile...
09-02 19:08:05.768  3188  3188 D HidService: start()
09-02 19:08:05.768  3188  3188 I bluedroid: get_profile_interface hidhost
09-02 19:08:05.768  3188  3188 D HidService: setHidService(): set to: null
09-02 19:08:05.768  3188  3188 D HidService: mStartError = false
09-02 19:08:05.768  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
09-02 19:08:05.768  3188  3188 D HeadsetStateMachine: Try to query the phonestate on bind
09-02 19:08:05.768  3188  7792 D A2dpStateMachine: Enter Disconnected: -2
,09-02 19:08:05.768  1423  7302 I Telecom : BluetoothPhoneService: queryPhoneState
09-02 19:08:05.768  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-02 19:08:05.768  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-02 19:08:05.768  1423  7302 I Telecom : BluetoothPhoneService: Result of Message : true
,09-02 19:08:05.778  3188  3188 D HealthService: Received start request. Starting profile...
09-02 19:08:05.778  3188  3188 D HealthService: start()
09-02 19:08:05.778  3188  7784 D BluetoothMediaBrowser: no now playing list
09-02 19:08:05.778  3188  7784 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-02 19:08:05.778  3188  3188 I bluedroid: get_profile_interface health
,09-02 19:08:05.778  3188  3188 D HealthService: mStartError = false
09-02 19:08:05.778  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:08:05.778  3188  3188 D HeadsetStateMachine: Proxy object connected
09-02 19:08:05.778  3188  3188 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-02 19:08:05.778  3188  7783 D HeadsetStateMachine: Disconnected process message: 11
09-02 19:08:05.778  3188  3188 D PanService: Received start request. Starting profile...
09-02 19:08:05.778  3188  3188 D PanService: start()
09-02 19:08:05.778  3188  3188 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 19:08:05.778  3188  3188 I bluedroid: get_profile_interface pan
09-02 19:08:05.778  3188  3188 D PanService: mStartError = false
09-02 19:08:05.778  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:08:05.778  3188  3188 D BluetoothMapService: Received start request. Starting profile...
09-02 19:08:05.778  3188  3188 D BluetoothMapService: start()
,09-02 19:08:05.788  3188  3188 D BluetoothMapService: mStartError = false
09-02 19:08:05.788  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
09-02 19:08:05.788  3188  3188 D HeadsetPhoneState: sendDeviceDataStateChanged
09-02 19:08:05.788  3188  3188 D HeadsetPhoneState: Signal level : previous=0 curr=4
,09-02 19:08:05.788  3188  7783 D HeadsetStateMachine: Disconnected process message: 18
09-02 19:08:05.788  3188  3188 D SapService: Received start request. Starting profile...
09-02 19:08:05.788  3188  3188 D SapService: start()
09-02 19:08:05.788  3188  3188 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-02 19:08:05.788  3188  3188 I bluedroid: get_profile_interface sap
09-02 19:08:05.788  3188  3188 D SapService: mStartError = false
09-02 19:08:05.788  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
09-02 19:08:05.788  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-02 19:08:05.788  3188  3188 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-02 19:08:05.788  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-02 19:08:05.788  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,09-02 19:08:05.788   288   288 E SMD     : DCD OFF
,09-02 19:08:05.788  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-02 19:08:05.788  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
09-02 19:08:05.788  3188  7783 D HeadsetStateMachine: Disconnected process message: 10
09-02 19:08:05.788  3188  7783 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-02 19:08:05.788  3188  7783 D HeadsetStateMachine: Disconnected process message: 11
,09-02 19:08:05.798  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-02 19:08:05.798  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-02 19:08:05.808  7785  7785 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:05.808  3188  3262 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-02 19:08:05.808  7785  7785 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:05.808  3188  3262 I bluedroid: enable
,09-02 19:08:05.808  3188  3265 E bt-btif : Calling BTA_HhEnable
,09-02 19:08:05.818  3188  3265 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-02 19:08:05.818  3188  3265 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-02 19:08:05.818  3188  3265 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
09-02 19:08:05.818  3188  3265 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-02 19:08:05.818  3188  3265 E BluetoothServiceJni: populateRssiValuesNative
09-02 19:08:05.818  3188  3265 I bluedroid: getModelRssiValues
09-02 19:08:05.818  3188  3265 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-02 19:08:05.818  3188  3265 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-02 19:08:05.818  3188  3265 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-02 19:08:05.818  1019  1019 D SettingsProvider: name = bluetooth_name
,09-02 19:08:05.818  3188  3265 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-02 19:08:05.818  3188  3265 D BluetoothAdapterProperties: Scan Mode:20
,09-02 19:08:05.818  3188  3265 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 19:08:05.818  3188  3265 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,09-02 19:08:05.818  3188  3265 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-02 19:08:05.818  3188  3265 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
09-02 19:08:05.818  3188  3265 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-02 19:08:05.818  3188  3265 E bt-btif : JVenable fails
,09-02 19:08:05.828  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:05.828  3188  3265 D bte_conf: Device ID record 1 : primary
09-02 19:08:05.828  3188  3265 D bte_conf:   vendorId            = 0075
,09-02 19:08:05.828  3188  3265 D bte_conf:   vendorIdSource      = 0001
09-02 19:08:05.828  3188  3265 D bte_conf:   product             = 0100
09-02 19:08:05.828  3188  3265 D bte_conf:   version             = 0200
09-02 19:08:05.828  3188  3265 D bte_conf:   clientExecutableURL = 
09-02 19:08:05.828  3188  3265 D bte_conf:   serviceDescription  = 
09-02 19:08:05.828  3188  3265 D bte_conf:   documentationURL    = 
,09-02 19:08:05.828  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:05.828  3188  3265 D bte_conf: bte_load_did_conf no section named DID2.
,09-02 19:08:05.828  3188  3265 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-02 19:08:05.828  3188  3262 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-02 19:08:05.828  3188  3262 D BluetoothAdapterProperties: ScanMode =  20
09-02 19:08:05.828  3188  3262 D BluetoothAdapterProperties: State =  11
,09-02 19:08:05.828  3188  3265 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-02 19:08:05.828  1019  1494 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-02 19:08:05.838  3188  3265 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 19:08:05.838  3188  3265 D BluetoothAdapterProperties: Scan Mode:21
09-02 19:08:05.838  3188  3265 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 19:08:05.838  3188  3262 D BluetoothAdapterProperties: Setting state to 12
,09-02 19:08:05.838  3188  3262 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 19:08:05.838  7785  7785 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-02 19:08:05.838  1019  1136 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-02 19:08:05.838  1019  1136 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:08:05.838  1019  1136 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:08:05.838  1019  1136 D SettingsProvider: selectionArgs: false
09-02 19:08:05.838  1019  1136 D SettingsProvider: selectionArgs: 1002
09-02 19:08:05.838  1019  1136 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:05.838  1019  1136 D SettingsProvider: ret = -1
,09-02 19:08:05.838  3188  3262 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 19:08:05.838  3188  3262 D BluetoothAdapterService: updateAdapterState state is 12
,09-02 19:08:05.838  1019  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:05.838  1019  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.838  1019  1497 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.838  1019  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.838  1019  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:05.848  3188  3262 D BluetoothAdapterService: Autoconnection is available 
,09-02 19:08:05.848  3188  3262 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-02 19:08:05.848  3188  3262 D BluetoothAdapterService: starting service from this receiver
09-02 19:08:05.848  1019  1367 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:05.848  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.848  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.848  1019  1367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:08:05.848  4850  7303 D BluetoothPan: Binding service...
09-02 19:08:05.848  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:05.848  3188  3262 I BluetoothAdapterState: Entering On State from state = 11
,09-02 19:08:05.848  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-02 19:08:05.848  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.848  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.848  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.848  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:05.848  3188  3188 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-02 19:08:05.858  1019  1048 D BluetoothPan: Binding service...
,09-02 19:08:05.858  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-02 19:08:05.858  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:05.858  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:05.858  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:05.858  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:08:05.858  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:05.858  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:05.858  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:05.858  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:08:05.858  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-02 19:08:05.858  1448  1471 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 19:08:05.858  1448  1471 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:05.858  4850  4859 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:05.858  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 19:08:05.858  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:05.858  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.858  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.858  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-02 19:08:05.858  7226  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:05.858  4850  4859 E BluetoothHeadset: BluetoothHeadset service is binded
09-02 19:08:05.858  3188  3188 I BluetoothPbapService: Handler(): got msg=1
,09-02 19:08:05.868  1019  1048 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:05.868  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 19:08:05.868  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-02 19:08:05.868  1019  1048 E BluetoothHeadset: BluetoothHeadset service is binded
09-02 19:08:05.868  1019  1031 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-02 19:08:05.868  3188  7325 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 19:08:05.868  3188  7325 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:05.868  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:05.868  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:05.868  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:05.868  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:08:05.868  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:05.868  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:05.868  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:05.868  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:05.868  1019  1048 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 19:08:05.868  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.868  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.868  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.868  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:05.868  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
,09-02 19:08:05.868  7226  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:05.868  4850  4850 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 19:08:05.868  4850  4850 D PanProfile: Bluetooth service connected
,09-02 19:08:05.878  3188  3188 D BluetoothA2dp: Proxy object connected
09-02 19:08:05.878  3188  3188 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-02 19:08:05.878  1423  1458 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:05.878  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 19:08:05.878  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:05.878  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.878  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.878  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:05.878  1423  1458 E BluetoothHeadset: BluetoothHeadset service is binded
09-02 19:08:05.878  4850  4859 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 19:08:05.878  7785  7785 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-02 19:08:05.878  3188  7806 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-02 19:08:05.878  7785  7785 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-02 19:08:05.878  7785  7785 D UserAnalysis: Create SecureDbHelper
09-02 19:08:05.878  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-02 19:08:05.878  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.878  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-02 19:08:05.878  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.878  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:05.878  4850  4850 D HeadsetProfile: Bluetooth service connected
,09-02 19:08:05.878  7335  7350 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:05.878  3188  7806 D BluetoothSocket: bindListen(): myUserId = 0
09-02 19:08:05.878  7335  7350 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 19:08:05.878  3188  7806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:08:05.888  4850  4859 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 19:08:05.888  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-02 19:08:05.888  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.888  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.888  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.888  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-02 19:08:05.888  3188  7806 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-02 19:08:05.888  3188  7806 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 19:08:05.888  3188  7806 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 19:08:05.888  3188  7806 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e54265b
,09-02 19:08:05.888  4850  4850 D BluetoothInputDevice: Proxy object connected
,09-02 19:08:05.888  4850  4850 D HidProfile: Bluetooth service connected
,09-02 19:08:05.888  3188  7806 D BluetoothSocket: channel: 19
09-02 19:08:05.888  3188  7806 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-02 19:08:05.888  1423  1432 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-02 19:08:05.888  7785  7785 D IntelligenceServiceApplication: onCreate()
09-02 19:08:05.888  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 19:08:05.888  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:05.888  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.888  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.888  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-02 19:08:05.888  1423  1432 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:05.888  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:05.888  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 19:08:05.888  1019  1048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 19:08:05.888  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-02 19:08:05.888  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 19:08:05.888  1019  1048 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:05.888  1019  1019 D BluetoothA2dp: Proxy object connected
09-02 19:08:05.898  4850  4859 D BluetoothPbap: onBluetoothStateChange: up=true
,09-02 19:08:05.898  1019  4273 I ActivityManager: Killing 7335:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-02 19:08:05.898  4850  4850 D BluetoothMap: Proxy object connected
09-02 19:08:05.898  4850  4850 D MapProfile: Bluetooth service connected
09-02 19:08:05.898  4850  4850 D BluetoothMap: getConnectedDevices()
,09-02 19:08:05.898  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-02 19:08:05.898  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.898  7785  7785 D IntelligenceServiceApplication: no applications having user consent for prediction
09-02 19:08:05.898  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.898  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.898  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:05.898  1423  1432 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:05.898  1019  4260 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-02 19:08:05.898  1423  1432 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 19:08:05.898  7226  7235 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:05.898  7226  7235 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:05.908  4850  4850 D BluetoothPbap: Proxy object connected
09-02 19:08:05.908  4850  4850 D PbapServerProfile: Bluetooth service connected
,09-02 19:08:05.908  1448  1467 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:05.908  1019  1048 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 19:08:05.908  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:05.908  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.908  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.908  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:05.908  1448  1467 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:05.908  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-02 19:08:05.908  1436  1457 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:05.908  1436  1457 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 19:08:05.908  1758  1963 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:05.908  1758  1963 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 19:08:05.908  3188  3202 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:05.908  3188  3202 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 19:08:05.908  4850  4858 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 19:08:05.908  4850  4858 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:05.908  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 19:08:05.918  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.918  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.918  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.918  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-02 19:08:05.918  4850  4850 D BluetoothA2dp: Proxy object connected
09-02 19:08:05.918  1636  4370 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:05.918  1636  4370 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:05.918  4850  4850 D A2dpProfile: Bluetooth service connected
09-02 19:08:05.918  4850  7303 D Bluetoothsap: onBluetoothStateChange: up=true
09-02 19:08:05.918  4850  7303 D Bluetoothsap: Binding service...
,09-02 19:08:05.918  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-02 19:08:05.918  4850  7303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-02 19:08:05.918  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-02 19:08:05.918  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.918  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:05.928  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:08:05.928  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:05.928  4850  7303 D Bluetoothsap: bindService called to Bluetooth SAP Service
09-02 19:08:05.928  4850  4859 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:05.928  4850  4859 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:05.928  1178  2369 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:05.928  1178  2369 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:05.928  4850  4850 D Bluetoothsap: BluetoothSAP Proxy object connected
09-02 19:08:05.928  4850  4850 D SapProfile: Bluetooth service connected
09-02 19:08:05.928  4850  4850 D Bluetoothsap: getConnectedDevices()
,09-02 19:08:05.928  1423  1458 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:05.928  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 19:08:05.928  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:05.928  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:05.928  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.928  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:05.938  1423  1458 E BluetoothHeadset: BluetoothHeadset service is binded
09-02 19:08:05.938  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-02 19:08:05.938  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-02 19:08:05.938  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:05.938  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
09-02 19:08:05.938  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-02 19:08:05.938  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,09-02 19:08:05.948  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-02 19:08:05.948  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:05.948  1423  1423 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1f5d7bdd, true
,09-02 19:08:05.948  1178  1178 D BluetoothTile:  getBluetoothState : 12
,09-02 19:08:05.948  1423  1423 D BluetoothHeadset: registerMessageListener
,09-02 19:08:05.948  1178  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:08:05.948  1869  1869 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 19:08:05.948  4850  4850 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:05.958  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:08:05.958  1019  4260 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 19:08:05.958  3188  7325 D HeadsetService: registerMessageListener
,09-02 19:08:05.958  3188  7325 D HeadsetService: registerMessageListener
09-02 19:08:05.958  3188  7783 D HeadsetStateMachine: Disconnected process message: 70
09-02 19:08:05.958  3188  7783 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2e63ef8
,09-02 19:08:05.958  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-02 19:08:05.958  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-02 19:08:05.958  1178  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:08:05.958  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:05.958  1019  4259 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-02 19:08:05.958  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-02 19:08:05.958  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-02 19:08:05.958  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-02 19:08:05.958  4850  4850 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-02 19:08:05.958  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-02 19:08:05.958  4850  4850 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-02 19:08:05.958  4850  4850 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-02 19:08:05.958  4850  4850 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-02 19:08:05.968  1178  1731 D BluetoothTile:  handleUpdatestate:false name:null
09-02 19:08:05.968  3188  7809 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-02 19:08:05.968  3188  7783 D HeadsetStateMachine: Disconnected process message: 9
09-02 19:08:05.968  3188  7783 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-02 19:08:05.968   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-02 19:08:05.968   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-02 19:08:05.968   283   283 V voice   : voice_set_parameters: exit with code(-2)
09-02 19:08:05.968   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-02 19:08:05.968   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-02 19:08:05.968   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-02 19:08:05.968   283   283 V audio_hw_primary: adev_set_parameters: exit
09-02 19:08:05.968  3188  7783 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-02 19:08:05.968  3188  7809 D BluetoothSocket: bindListen(): myUserId = 0
09-02 19:08:05.968  3188  7809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:08:05.968  3188  7809 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-02 19:08:05.968  3188  7809 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 19:08:05.968  3188  7809 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 19:08:05.968  3188  7809 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f088fd1
09-02 19:08:05.968  3188  7809 D BluetoothSocket: channel: 5
,09-02 19:08:05.978  4850  4850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 19:08:05.978  1019  4273 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-02 19:08:05.978  1019  4273 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 19:08:05.978  1019  4273 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:05.978  1019  4273 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:05.978  1019  4273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 19:08:05.988  1636  1636 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 19:08:05.988  4850  4850 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:08:05.988  4850  4850 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 19:08:05.998  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:05.998  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-02 19:08:05.998  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:08:05.998  3188  3188 D BtConfig.SecureMode: isSecureModeOn:false
,09-02 19:08:05.998  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:05.998  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-02 19:08:06.008  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:06.008  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:06.008  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:06.008  1019  1485 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-02 19:08:06.008  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:06.008  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:06.018  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:06.018  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:06.028  7812  7812 E Zygote  : MountEmulatedStorage(),
09-02 19:08:06.028  7812  7812 E Zygote  : v2
09-02 19:08:06.028  7812  7812 I libpersona: KNOX_SDCARD checking this for 10105
09-02 19:08:06.028  7812  7812 I libpersona: KNOX_SDCARD not a persona
09-02 19:08:06.028  7812  7812 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 19:08:06.028  7812  7812 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-02 19:08:06.028  7812  7812 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
09-02 19:08:06.028  1019  1485 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7812 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-02 19:08:06.028  1019  4260 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-02 19:08:06.038  3188  7822 D BluetoothSocket: bindListen(): myUserId = 0
09-02 19:08:06.038  3188  7822 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:08:06.048  3188  7822 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
09-02 19:08:06.048  3188  7822 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 19:08:06.048  3188  7822 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 19:08:06.048  3188  7822 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@235580d
,09-02 19:08:06.048  3188  7822 D BluetoothSocket: channel: 12
09-02 19:08:06.048  3188  7822 I BtOppRfcommListener: Accept thread started.
,09-02 19:08:06.058  7812  7812 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:06.058  7812  7812 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:06.168   257   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-02 19:08:06.168   257   520 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 19:08:06.178  7812  7834 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-02 19:08:06.188   257   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-02 19:08:06.188   257   520 W Vold    : Returning OperationFailed - no handler for errno 0
,09-02 19:08:06.188  7812  7834 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-02 19:08:06.368  7812  7812 D StrictMode: StrictMode policy violation; ~duration=179 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.io.File.exists(File.java:363)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-02 19:08:06.368  7812  7812 D StrictMode: StrictMode policy violation; ~duration=178 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:08:06.368  7812  7812 D StrictMode: StrictMode policy violation; ~duration=176 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:08:06.368  7812  7812 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.q.e.b(PG:170)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09,-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:08:06.368  7812  7812 D StrictMode: StrictMode policy violation; ~duration=171 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.q.k.d(PG:583)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.q.e.b(PG:170)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:08:06.368  7812  7812 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.io.File.exists(File.java:363)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:08:06.368  7812  7812 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.io.File.exists(File.java:363)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:08:06.378  1019  1032 I ActivityManager: Killing 7442:com.sec.pcw.device/1000 (adj 15): empty #21
09-02 19:08:06.368  7812  7812 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:08:06.368  7812  7812 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:08:06.398   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 19:08:06.438  7812  7838 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-02 19:08:06.468  1019  1494 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-02 19:08:06.468  1019  1494 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:06.468  1019  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:06.468  1019  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-02 19:08:07.088  1019  1494 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-02 19:08:07.088  1019  1494 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4303, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-02 19:08:07.088  1019  1494 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-02 19:08:07.088  1019  1494 D BatteryService: stay LED for charging
,09-02 19:08:07.088  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-02 19:08:07.088  1019  1019 I MotionRecognitionService: Plugged,
09-02 19:08:07.088  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
09-02 19:08:07.098  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-02 19:08:07.098  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-02 19:08:07.098  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
09-02 19:08:07.098  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-02 19:08:07.108  3188  3188 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-02 19:08:07.108  3188  7783 D HeadsetStateMachine: Disconnected process message: 10
,09-02 19:08:07.118  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-02 19:08:07.128  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-02 19:08:07.128  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-02 19:08:07.408   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 19:08:08.398   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,09-02 19:08:08.648  7226  7279 D BluetoothAdapter: disable()
,09-02 19:08:08.648  1019  1031 D SettingsProvider: name = bluetooth_on
,09-02 19:08:08.668  3188  3262 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-02 19:08:08.668  3188  3262 D BluetoothAdapterProperties: Setting state to 13
09-02 19:08:08.668  1019  4260 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:08.668  3188  3262 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 19:08:08.668  1019  4260 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-02 19:08:08.668  3188  3262 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 19:08:08.668  3188  3262 D BluetoothAdapterService: updateAdapterState state is 13
,09-02 19:08:08.668  1019  4260 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:08.668  1019  4260 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:08.668  1019  4260 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:08:08.668  3188  3188 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-02 19:08:08.668  3188  3188 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1898a3c2, channel: 19, state: LISTENING
,09-02 19:08:08.668  3188  3188 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1898a3c2, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e54265b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@24ef05d3mSocket: android.net.LocalSocket@21bdf510 impl:android.net.LocalSocketImpl@18ec6809 fd:FileDescriptor[80]
09-02 19:08:08.668  3188  3188 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@21bdf510 impl:android.net.LocalSocketImpl@18ec6809 fd:FileDescriptor[80]
09-02 19:08:08.668  3188  3262 D BluetoothAdapterService: Autoconnection is available 
09-02 19:08:08.668  3188  3262 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-02 19:08:08.668  3188  3262 D BluetoothAdapterService: terminating service from this receiver
,09-02 19:08:08.668  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:08.668  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
,09-02 19:08:08.678  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,09-02 19:08:08.678  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 19:08:08.678  1178  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:08:08.688  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:08.688  1178  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:08:08.688  1178  1178 D BluetoothTile:  getBluetoothState : 13
,09-02 19:08:08.688  1869  1869 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 19:08:08.688  1019  1505 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-02 19:08:08.688  4850  4850 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:08.688  1178  1731 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-02 19:08:08.688  1019  1488 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-02 19:08:08.698  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-02 19:08:08.698  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:08:08.698  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:08.698  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:08.698  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:08.698  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:08:08.698  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:08:08.698  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:08.698  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:08.698  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:08.698  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:08:08.698  7226  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:08.708  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:08:08.708  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:08.708  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:08.708  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:08.708  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:08:08.708  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 19:08:08.708  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:08.708  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:08.708  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:08.708  7226  7226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 19:08:08.708  7226  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:08.708  1019  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-02 19:08:08.718  1019  1136 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:08.718  1019  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:08.718  1019  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:08.718  4850  4850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 19:08:08.718  1019  1338 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-02 19:08:08.718  1019  1338 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 19:08:08.718  3188  3262 D BluetoothAdapterProperties: onBluetoothDisable()
09-02 19:08:08.718  3188  3262 D BluetoothAdapterProperties: mDiscovering is false
09-02 19:08:08.718  3188  3188 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@24513a0e, channel: 5, state: LISTENING
,09-02 19:08:08.718  3188  3188 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@24513a0e, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f088fd1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b1a2c2fmSocket: android.net.LocalSocket@2ef5523c impl:android.net.LocalSocketImpl@13ea7bc5 fd:FileDescriptor[82]
09-02 19:08:08.718  3188  3188 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2ef5523c impl:android.net.LocalSocketImpl@13ea7bc5 fd:FileDescriptor[82]
09-02 19:08:08.718  3188  3188 I BtOppRfcommListener: stopping Accept Thread
,09-02 19:08:08.718  3188  3188 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2beae91a, channel: 12, state: LISTENING
09-02 19:08:08.718  3188  3188 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2beae91a, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@235580d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a275c4bmSocket: android.net.LocalSocket@1de35628 impl:android.net.LocalSocketImpl@8fc0f41 fd:FileDescriptor[86]
09-02 19:08:08.718  3188  3188 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1de35628 impl:android.net.LocalSocketImpl@8fc0f41 fd:FileDescriptor[86]
09-02 19:08:08.718  1019  1031 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-02 19:08:08.718  3188  7822 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 19:08:08.718  3188  7822 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-02 19:08:08.728  3188  3262 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-02 19:08:08.728  1019  1338 W ActivityManager: userId = 0, bbcId = -10000,
09-02 19:08:08.728  1019  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:08.728  1019  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 19:08:08.738  3188  3265 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 19:08:08.738  3188  3265 D BluetoothAdapterProperties: Scan Mode:20
,09-02 19:08:08.738  3188  3262 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-02 19:08:08.748  3188  3262 E bt-btif : btif_dm_generic_evtsock_thread_handle:6, rfc_init:1, vhci_init:1
,09-02 19:08:08.748  3188  3262 E bt-btif : cmd socket is not created
,09-02 19:08:08.748  3188  3262 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-02 19:08:08.748  3188  3266 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,09-02 19:08:08.748  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:08.748  4850  4850 D BluetoothPbap: Proxy object disconnected
09-02 19:08:08.748  4850  4850 D PbapServerProfile: Bluetooth service disconnected
,09-02 19:08:08.758  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:08.758  3188  3266 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-02 19:08:08.758  3188  3266 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:08:08.758  3188  3266 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-02 19:08:08.758  3188  3266 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 19:08:08.758  3188  3266 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 19:08:08.758  3188  3266 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-02 19:08:08.758  1636  1636 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 19:08:08.768  3188  3188 V BluetoothOppManager: cleanUp...
,09-02 19:08:08.768  4850  4850 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:08:08.768  4850  4850 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 19:08:08.778  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:08.778  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-02 19:08:08.788   288   288 E SMD     : DCD OFF
,09-02 19:08:08.948  3188  3262 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-02 19:08:08.948  3188  3262 D BtConfig.SecureMode: isSecureModeOn:false
09-02 19:08:08.948  3188  3262 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-02 19:08:08.948  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-02 19:08:08.948  3188  3262 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-02 19:08:08.948  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-02 19:08:08.948  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-02 19:08:08.948  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-02 19:08:08.948  1019  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:08.948  1019  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-02 19:08:08.948  1019  1497 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:08.948  1019  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:08.948  1019  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:08.948  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-02 19:08:08.948  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-02 19:08:08.948  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-02 19:08:08.948  1019  1367 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:08.948  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 19:08:08.958  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:08.958  1019  1367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:08.958  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:08.958  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,09-02 19:08:08.958  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 19:08:08.958  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-02 19:08:08.958  1019  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:08.958  1019  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 19:08:08.958  3188  3188 D HeadsetService: Received stop request...Stopping profile...
,09-02 19:08:08.958  1019  1494 W ActivityManager: userId = 0, bbcId = -10000,
09-02 19:08:08.958  1019  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:08.958  1019  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:08.958  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:08:08.968  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-02 19:08:08.968  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-02 19:08:08.968  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-02 19:08:08.968  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-02 19:08:08.968  4850  4850 D HeadsetProfile: Bluetooth service disconnected
09-02 19:08:08.968  1019  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:08.968  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-02 19:08:08.968  3188  3188 D A2dpService: Received stop request...Stopping profile...
09-02 19:08:08.968  3188  7792 D A2dpStateMachine: Exit Disconnected: -1
,09-02 19:08:08.968  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:08.968  1019  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:08.968  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:08:08.968  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,09-02 19:08:08.968  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-02 19:08:08.968  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-02 19:08:08.968  1019  1367 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:08.968  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
09-02 19:08:08.978  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 19:08:08.978  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:08.978  1019  1367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:08.978  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:08.978  1019  1019 D BluetoothA2dp: Proxy object disconnected
,09-02 19:08:08.978  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-02 19:08:08.978  4850  4850 D BluetoothA2dp: Proxy object disconnected
09-02 19:08:08.978  4850  4850 D A2dpProfile: Bluetooth service disconnected
,09-02 19:08:08.978  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-02 19:08:08.978  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-02 19:08:08.978  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-02 19:08:08.978  1019  4260 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:08.978  1019  4260 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 19:08:08.978  1019  4260 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:08.978  1019  4260 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:08:08.978  1019  4260 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:08:08.988  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-02 19:08:08.988  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 19:08:08.988  3188  3262 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-02 19:08:08.988  1019  1338 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:08.988  1019  1338 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 19:08:08.988  1019  1338 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:08.988  1019  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:08.988  1019  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:08:08.988  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:08.988  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:08.988  3188  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 19:08:08.988  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:08.988  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:08.988  3188  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-02 19:08:08.988  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-02 19:08:08.988  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-02 19:08:08.988  3188  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-02 19:08:08.988  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
,09-02 19:08:08.988  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-02 19:08:08.988  3188  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-02 19:08:08.988  3188  3262 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-02 19:08:08.988  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-02 19:08:08.988  3188  3188 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 19:08:08.988  3188  3188 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-02 19:08:08.988  3188  3188 D HidService: Received stop request...Stopping profile...
,09-02 19:08:08.988  3188  3188 D HidService: Stopping Bluetooth HidService
09-02 19:08:08.988  3188  3188 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 19:08:08.988  3188  3188 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-02 19:08:08.988  3188  3188 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-02 19:08:08.988  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:08:08.998  4850  4850 D BluetoothInputDevice: Proxy object disconnected
,09-02 19:08:08.998  3188  3188 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 19:08:08.998  3188  3188 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 19:08:08.998  3188  3188 D HealthService: Received stop request...Stopping profile...
,09-02 19:08:08.998  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:08:08.998  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-02 19:08:08.998  3188  3188 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 19:08:08.998  3188  3188 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-02 19:08:08.998  4850  4850 D HidProfile: Bluetooth service disconnected
09-02 19:08:08.998  3188  3188 D PanService: Received stop request...Stopping profile...
09-02 19:08:08.998  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:08:08.998  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-02 19:08:08.998  3188  3188 D BluetoothA2dp: Proxy object disconnected
,09-02 19:08:08.998  3188  3188 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-02 19:08:08.998  3188  7793 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-02 19:08:08.998  3188  3188 I GKI_LINUX: GKI_exit_task 2 done
09-02 19:08:08.998  3188  3188 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-02 19:08:08.998  4850  4850 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 19:08:08.998  4850  4850 D PanProfile: Bluetooth service disconnected
,09-02 19:08:08.998  3188  3188 D BluetoothMapService: Received stop request...Stopping profile...
,09-02 19:08:09.008  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:08:09.008  3188  3188 D SapService: Received stop request...Stopping profile...
09-02 19:08:09.008  3188  3188 D SapService: Stopping Bluetooth SapService
09-02 19:08:09.008  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:08:09.008  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-02 19:08:09.008  3188  3188 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-02 19:08:09.008  3188  3188 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:09.008  3188  3188 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:09.008  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-02 19:08:09.008  3188  3188 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-02 19:08:09.008  3188  3188 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:09.008  3188  3188 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:09.008  3188  3188 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 19:08:09.008  3188  3188 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 19:08:09.008  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-02 19:08:09.008  3188  3188 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-02 19:08:09.008  3188  3188 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:09.008  3188  3188 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:09.008  3188  3188 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 19:08:09.008  3188  3188 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-02 19:08:09.008  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-02 19:08:09.008  3188  3188 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-02 19:08:09.008  3188  3188 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 19:08:09.008  3188  3188 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-02 19:08:09.008  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-02 19:08:09.008  3188  3188 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-02 19:08:09.008  3188  3188 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-02 19:08:09.008  3188  3188 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-02 19:08:09.018  3188  3262 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-02 19:08:09.018  4850  4850 D BluetoothMap: Proxy object disconnected
09-02 19:08:09.018  3188  3262 D BluetoothAdapterProperties: Setting state to 10
09-02 19:08:09.018  3188  3262 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-02 19:08:09.018  3188  3262 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 19:08:09.018  3188  3262 D BluetoothAdapterService: updateAdapterState state is 10
,09-02 19:08:09.018  4850  4850 D MapProfile: Bluetooth service disconnected
09-02 19:08:09.018  4850  4850 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-02 19:08:09.018  4850  4850 D SapProfile: Bluetooth service disconnected
09-02 19:08:09.018  3188  3262 D BluetoothAdapterService: Autoconnection is available 
09-02 19:08:09.018  3188  3262 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,09-02 19:08:09.018  3188  3262 I BluetoothAdapterState: Entering OffState
09-02 19:08:09.018  7812  7827 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:08:09.018  7812  7827 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:09.018  1448  2495 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:08:09.018  1448  2495 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:09.018  3188  3326 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:08:09.018  4850  4858 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-02 19:08:09.018  4850  4859 D BluetoothMap: onBluetoothStateChange: up=false
,09-02 19:08:09.018  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:08:09.018  1019  1048 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 19:08:09.018  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:08:09.018  4850  7303 D BluetoothPbap: onBluetoothStateChange: up=false
,09-02 19:08:09.028  1423  1432 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:08:09.028  1423  1432 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:09.028  7226  7235 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:08:09.028  7226  7235 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-02 19:08:09.028  7226  7235 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-02 19:08:09.028  7226  7235 D BluetoothLeAdvertiser: Exit stop advertising
09-02 19:08:09.028  7226  7235 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-02 19:08:09.028  7226  7235 D BluetoothLeScanner: Exiting stopAllScan
,09-02 19:08:09.028  1436  1457 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:08:09.028  1436  1457 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:09.028  1758  1774 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:08:09.028  1758  1774 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:09.028  3188  3202 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:08:09.028  3188  3202 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:09.028  4850  4858 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 19:08:09.028  1636  1646 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:08:09.028  1636  1646 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:09.028  4850  4859 D Bluetoothsap: onBluetoothStateChange: up=false
09-02 19:08:09.028  4850  4859 D Bluetoothsap: Unbinding service...
,09-02 19:08:09.028  4850  7303 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-02 19:08:09.038  4850  7303 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:09.038  1178  1634 D BluetoothAdapter: onBluetoothStateChange: up=false
09-02 19:08:09.038  1178  1634 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-02 19:08:09.038  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:09.038  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
09-02 19:08:09.038  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-02 19:08:09.038  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 19:08:09.048  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:09.048  1178  1178 D BluetoothTile:  getBluetoothState : 10
,09-02 19:08:09.048  1869  1869 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 19:08:09.048  1019  1367 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 19:08:09.048  1019  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-02 19:08:09.048  4850  4850 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:09.048  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 19:08:09.058  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:09.058  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:09.058  4850  4850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 19:08:09.058  1019  1485 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-02 19:08:09.058  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 19:08:09.058  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:09.058  1019  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:09.058  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 19:08:09.068  4850  4850 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:08:09.068  1636  1636 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 19:08:09.068  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-02 19:08:09.068  4850  4850 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 19:08:09.088  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:09.088  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-02 19:08:09.268  1019  1097 V AlarmManager: waitForAlarm result :4
,09-02 19:08:09.278   278   977 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-02 19:08:09.278   278   977 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-02 19:08:09.288  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:09.288  1019  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 19:08:09.288  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,09-02 19:08:09.408   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-02 19:08:10.398   329   329 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-02 19:08:11.668  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 19:08:11.668  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:11.788   288   288 E SMD     : DCD OFF
,09-02 19:08:14.168  1019  3325 D SSRM:n  : SIOP:: AP = 320
,09-02 19:08:14.668  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-02 19:08:14.668  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@de0deaa added. We now have 6 listener(s)
09-02 19:08:14.668  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:08:14.668  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:08:14.668  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e12ca9b added. We now have 7 listener(s)
09-02 19:08:14.668  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:08:14.668  7226  7279 I System.out: IsBluetoothEnabled
09-02 19:08:14.668  7226  7279 D BluetoothAdapter: disable()
,09-02 19:08:14.678  1019  1219 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.,
,09-02 19:08:14.678  7226  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:08:14.678  7226  7279 D BluetoothAdapter: enable()
,09-02 19:08:14.678  1019  1338 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-02 19:08:14.678  1019  1338 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7226, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-02 19:08:14.678  1019  1338 W BluetoothManagerService: ,	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-02 19:08:14.678  1019  1338 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-02 19:08:14.678  1019  1338 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-02 19:08:14.678  1019  1338 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-02 19:08:14.678  1019  1338 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
09-02 19:08:14.678  1019  1338 W ActivityManager: Permission Denial: getCurrentUser() from pid=7226, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-02 19:08:14.678  1019  1338 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-02 19:08:14.678  1019  1338 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 19:08:14.688  1019  1338 D SettingsProvider: name = bluetooth_on,
,09-02 19:08:14.698  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-02 19:08:14.698  1019  1048 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-02 19:08:14.698  1019  1048 D SecContentProvider: uri = 3 selection = isBluetoothEnabled,
09-02 19:08:14.698  3188  3262 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-02 19:08:14.698  3188  3262 D BluetoothAdapterProperties: Setting state to 11,
09-02 19:08:14.698  3188  3262 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-02 19:08:14.698  3188  3262 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-02 19:08:14.698  3188  3262 D BluetoothAdapterService: updateAdapterState state is 11
09-02 19:08:14.698  3188  3262 D BluetoothAdapterService: Autoconnection is available 
09-02 19:08:14.698  3188  3262 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-02 19:08:14.698  3188  3262 D BtConfig.SecureMode: isSecureModeOn:false
09-02 19:08:14.698  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService,
09-02 19:08:14.698  3188  3262 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-02 19:08:14.698  1019  1367 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:14.698  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-02 19:08:14.698  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-02 19:08:14.698  3188  3262 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-02 19:08:14.698  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-02 19:08:14.698  3188  3262 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-02 19:08:14.698  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-02 19:08:14.698  3188  3262 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
,09-02 19:08:14.698  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-02 19:08:14.698  3188  3262 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-02 19:08:14.698  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-02 19:08:14.698  3188  3262 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-02 19:08:14.698  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:14.698  3188  3262 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-02 19:08:14.698  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 19:08:14.698  3188  3262 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-02 19:08:14.698  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-02 19:08:14.698  3188  3262 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:14.698  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:14.698  3188  3262 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:14.698  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-02 19:08:14.698  3188  3262 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-02 19:08:14.698  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-02 19:08:14.698  3188  3262 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-02 19:08:14.698  3188  3262 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-02 19:08:14.698  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-02 19:08:14.698  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-02 19:08:14.698  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-02 19:08:14.708  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:14.708  1019  1367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:14.708  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:08:14.708  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-02 19:08:14.708  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-02 19:08:14.708  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-02 19:08:14.708  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:14.708  3188  3188 D HeadsetService: Received start request. Starting profile...
09-02 19:08:14.708  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
09-02 19:08:14.708  3188  3188 D HeadsetService: start()
09-02 19:08:14.708  3188  3188 D HeadsetStateMachine: make
,09-02 19:08:14.718  1869  1869 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 19:08:14.718  3188  3188 E HeadsetStateMachine: # of Max HF connection is 2,
09-02 19:08:14.718  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-02 19:08:14.718  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:14.718  1178  1178 D BluetoothTile:  getBluetoothState : 11
,09-02 19:08:14.718  4850  4850 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:14.728  1019  1497 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 19:08:14.728  1019  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:14.728  1019  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 19:08:14.728  1019  1494 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:14.728  1178  1731 D BluetoothTile:  handleUpdatestate:false name:null
09-02 19:08:14.728  1019  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:14.728  1019  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:14.728  1178  1731 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-02 19:08:14.728  1019  1338 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-02 19:08:14.728  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-02 19:08:14.728  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:14.728  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-02 19:08:14.728  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-02 19:08:14.728  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-02 19:08:14.738  1019  4260 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-02 19:08:14.738  1019  4260 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-02 19:08:14.738  1019  4260 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:14.738  1019  4260 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:14.738  1019  4260 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-02 19:08:14.738  1019  4273 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:14.738  1636  1636 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 19:08:14.738  1019  4273 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 19:08:14.738  1019  4273 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:14.738  1019  4273 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:14.738  1019  4273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:14.748  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-02 19:08:14.748  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-02 19:08:14.748  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-02 19:08:14.748  1019  1031 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-02 19:08:14.748  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-02 19:08:14.748  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:14.748  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:14.748  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-02 19:08:14.748  3188  3188 I bluedroid: get_profile_interface handsfree
,09-02 19:08:14.748  1019  1338 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:14.748  1019  1338 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-02 19:08:14.748  1019  1338 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:14.748  1019  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:14.748  1019  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:14.758  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,09-02 19:08:14.758  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-02 19:08:14.758  4850  4850 D BluetoothNotiBroadcastReceiver: onReceive
09-02 19:08:14.758  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-02 19:08:14.758  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:14.758  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
09-02 19:08:14.758  1019  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:14.758  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 19:08:14.758  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:14.758  1019  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:14.758  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:14.768  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-02 19:08:14.768  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-02 19:08:14.768  3188  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-02 19:08:14.768  3188  3188 E DualScoManager: Dual Sco Manager already instantiated
09-02 19:08:14.768  3188  3188 I DualScoManager: Set HeadsetServiceHelper
09-02 19:08:14.768  3188  3188 D BluetoothAtMessage: createCMTIContentObservers
09-02 19:08:14.768  1019  4260 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:14.768  1019  4260 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 19:08:14.768  1019  1136 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-02 19:08:14.768  1019  1136 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:08:14.768  1019  1136 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:08:14.768  1019  4260 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:14.768  1019  4260 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:14.768  1019  1136 D SettingsProvider: selectionArgs: false
09-02 19:08:14.768  1019  4260 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-02 19:08:14.768  1019  1136 D SettingsProvider: selectionArgs: 1002
09-02 19:08:14.768  1019  1136 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:14.768  1019  1136 D SettingsProvider: ret = -1
09-02 19:08:14.768  3188  7860 D HeadsetStateMachine: Enter Disconnected: -2
,09-02 19:08:14.768  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-02 19:08:14.768  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-02 19:08:14.768  3188  3262 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-02 19:08:14.778  3188  3188 D HeadsetService: mStartError = false
09-02 19:08:14.778  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:08:14.778  1019  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:14.778  1019  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-02 19:08:14.778  1019  1494 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:14.778  1019  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:14.778  3188  3188 D A2dpService: Received start request. Starting profile...
09-02 19:08:14.778  3188  3188 D A2dpService: start()
09-02 19:08:14.778  3188  3188 I bluedroid: get_profile_interface avrcp
09-02 19:08:14.778  1019  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:14.778  3188  7860 D HeadsetStateMachine: Clear mHeadsetBrsf
09-02 19:08:14.778  3188  7860 D HeadsetStateMachine: map size, before remove : 0
09-02 19:08:14.778  3188  7860 D HeadsetStateMachine: map size, after remove: 0
,09-02 19:08:14.778  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:14.778  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:14.778  3188  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-02 19:08:14.778  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:14.778  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:14.778  3188  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-02 19:08:14.778  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-02 19:08:14.778  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-02 19:08:14.778  3188  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-02 19:08:14.778  3188  3262 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
,09-02 19:08:14.778  3188  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-02 19:08:14.778  3188  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-02 19:08:14.778  3188  3262 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-02 19:08:14.778  3188  3188 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-02 19:08:14.778  3188  3188 D Avrcp   : Initialize Media Controller
09-02 19:08:14.778  3188  3188 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-02 19:08:14.778  3188  3188 E Avrcp   : getActiveSessions
09-02 19:08:14.778  3188  3188 D Avrcp   : pick active media Controller
09-02 19:08:14.778  3188  3188 D Avrcp   : Get the active Media Controller 
,09-02 19:08:14.788  3188  3188 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-02 19:08:14.788  3188  3188 D A2dpStateMachine: make,
09-02 19:08:14.788  3188  7861 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
09-02 19:08:14.788  3188  3188 I bluedroid: get_profile_interface a2dp
,09-02 19:08:14.788  3188  7863 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-02 19:08:14.788   288   288 E SMD     : DCD OFF
09-02 19:08:14.788  3188  3188 E bt-btif : warning : media task started media_task_refcnt 1 
,09-02 19:08:14.798  3188  3188 D A2dpService: mStartError = false
09-02 19:08:14.798  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
09-02 19:08:14.798  3188  3188 D HeadsetStateMachine: Try to query the phonestate on bind
09-02 19:08:14.798  1423  7302 I Telecom : BluetoothPhoneService: queryPhoneState
09-02 19:08:14.798  3188  7862 D A2dpStateMachine: Enter Disconnected: -2
,09-02 19:08:14.798  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-02 19:08:14.798  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-02 19:08:14.798  1423  7302 I Telecom : BluetoothPhoneService: Result of Message : true
,09-02 19:08:14.798  3188  3188 D HidService: Received start request. Starting profile...
09-02 19:08:14.798  3188  3188 D HidService: start()
09-02 19:08:14.798  3188  3188 I bluedroid: get_profile_interface hidhost
09-02 19:08:14.798  3188  3188 D HidService: setHidService(): set to: null
09-02 19:08:14.798  3188  3188 D HidService: mStartError = false
09-02 19:08:14.798  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
09-02 19:08:14.798  3188  3188 D HeadsetStateMachine: Proxy object connected
09-02 19:08:14.798  3188  3188 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-02 19:08:14.798  3188  7860 D HeadsetStateMachine: Disconnected process message: 11
09-02 19:08:14.798  3188  3188 D HealthService: Received start request. Starting profile...
09-02 19:08:14.798  3188  3188 D HealthService: start()
,09-02 19:08:14.798  3188  3188 I bluedroid: get_profile_interface health
09-02 19:08:14.798  3188  3188 D HealthService: mStartError = false
09-02 19:08:14.798  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:08:14.798  3188  3188 D HeadsetPhoneState: sendDeviceDataStateChanged
09-02 19:08:14.798  3188  3188 D HeadsetPhoneState: Signal level : previous=0 curr=4
09-02 19:08:14.798  3188  7860 D HeadsetStateMachine: Disconnected process message: 18
,09-02 19:08:14.798  3188  3188 D PanService: Received start request. Starting profile...
09-02 19:08:14.798  3188  3188 D PanService: start()
09-02 19:08:14.798  3188  3188 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 19:08:14.798  3188  3188 I bluedroid: get_profile_interface pan
09-02 19:08:14.798  3188  3188 D PanService: mStartError = false
09-02 19:08:14.798  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:08:14.798  3188  3188 D BluetoothMapService: Received start request. Starting profile...
,09-02 19:08:14.798  3188  3188 D BluetoothMapService: start()
,09-02 19:08:14.808  3188  3188 D BluetoothMapService: mStartError = false
09-02 19:08:14.808  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
09-02 19:08:14.808  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-02 19:08:14.808  3188  3188 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-02 19:08:14.808  3188  3188 D SapService: Received start request. Starting profile...
09-02 19:08:14.808  3188  3188 D SapService: start()
09-02 19:08:14.808  3188  3188 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-02 19:08:14.808  3188  3188 I bluedroid: get_profile_interface sap
09-02 19:08:14.808  3188  3188 D SapService: mStartError = false
09-02 19:08:14.808  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:08:14.808  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-02 19:08:14.808  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-02 19:08:14.808  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-02 19:08:14.808  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
09-02 19:08:14.808  3188  7860 D HeadsetStateMachine: Disconnected process message: 10
09-02 19:08:14.808  3188  7860 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-02 19:08:14.808  3188  7860 D HeadsetStateMachine: Disconnected process message: 11
,09-02 19:08:14.808  3188  7861 D BluetoothMediaBrowser: no now playing list
09-02 19:08:14.808  3188  7861 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-02 19:08:14.818  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-02 19:08:14.818  3188  3188 E BluetoothAdapterService(933274766): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-02 19:08:14.828  3188  3262 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-02 19:08:14.828  3188  3262 I bluedroid: enable
,09-02 19:08:14.828  3188  3265 E bt-btif : Calling BTA_HhEnable
,09-02 19:08:14.828  3188  3265 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-02 19:08:14.828  3188  3265 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-02 19:08:14.828  3188  3265 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-02 19:08:14.838  3188  3265 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,09-02 19:08:14.838  3188  3265 E BluetoothServiceJni: populateRssiValuesNative
09-02 19:08:14.838  3188  3265 I bluedroid: getModelRssiValues
,09-02 19:08:14.838  3188  3265 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-02 19:08:14.838  3188  3265 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-02 19:08:14.838  1019  1019 D SettingsProvider: name = bluetooth_name
,09-02 19:08:14.838  3188  3265 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-02 19:08:14.838  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:14.848  3188  3265 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-02 19:08:14.848  3188  3265 D BluetoothAdapterProperties: Scan Mode:20
,09-02 19:08:14.848  3188  3265 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 19:08:14.848  3188  3265 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-02 19:08:14.848  3188  3265 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
,09-02 19:08:14.848  3188  3265 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
09-02 19:08:14.848  3188  3265 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-02 19:08:14.848  3188  3265 E bt-btif : JVenable fails
,09-02 19:08:14.848  3188  3265 D bte_conf: Device ID record 1 : primary
,09-02 19:08:14.848  3188  3265 D bte_conf:   vendorId            = 0075
09-02 19:08:14.848  3188  3265 D bte_conf:   vendorIdSource      = 0001
09-02 19:08:14.848  3188  3265 D bte_conf:   product             = 0100,
09-02 19:08:14.848  3188  3265 D bte_conf:   version             = 0200
09-02 19:08:14.848  3188  3265 D bte_conf:   clientExecutableURL = ,
09-02 19:08:14.848  3188  3265 D bte_conf:   serviceDescription  = 
09-02 19:08:14.848  3188  3265 D bte_conf:   documentationURL    = 
,09-02 19:08:14.848  3188  3265 D bte_conf: bte_load_did_conf no section named DID2.
09-02 19:08:14.848  3188  3265 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-02 19:08:14.848  3188  3265 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-02 19:08:14.848  3188  3262 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-02 19:08:14.848  3188  3262 D BluetoothAdapterProperties: ScanMode =  20
09-02 19:08:14.848  3188  3262 D BluetoothAdapterProperties: State =  11
09-02 19:08:14.848  1019  4273 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled,
09-02 19:08:14.848  3188  3262 D BluetoothAdapterProperties: Setting state to 12
09-02 19:08:14.848  3188  3262 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 19:08:14.858  3188  3265 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-02 19:08:14.858  3188  3265 D BluetoothAdapterProperties: Scan Mode:21
,09-02 19:08:14.858  3188  3265 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 19:08:14.858  1019  4259 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-02 19:08:14.858  1019  4259 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-02 19:08:14.858  1019  4259 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-02 19:08:14.858  1019  4259 D SettingsProvider: selectionArgs: false
09-02 19:08:14.858  1019  4259 D SettingsProvider: selectionArgs: 1002
09-02 19:08:14.858  1019  4259 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-02 19:08:14.858  1019  4259 D SettingsProvider: ret = -1
,09-02 19:08:14.858  3188  3262 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-02 19:08:14.858  3188  3262 D BluetoothAdapterService: updateAdapterState state is 12
,09-02 19:08:14.858  1019  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-02 19:08:14.858  1019  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 19:08:14.858  1019  1488 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:14.858  1019  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:08:14.858  1019  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:14.868  3188  3262 D BluetoothAdapterService: Autoconnection is available 
09-02 19:08:14.868  3188  3262 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-02 19:08:14.868  3188  3262 D BluetoothAdapterService: starting service from this receiver
,09-02 19:08:14.868  1019  1497 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:14.868  4850  7303 D BluetoothPan: Binding service...
09-02 19:08:14.868  1019  1497 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-02 19:08:14.868  1019  1497 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:14.868  1019  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:14.868  1019  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:14.868  3188  3262 I BluetoothAdapterState: Entering On State from state = 11
,09-02 19:08:14.868  3188  3188 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-02 19:08:14.868  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:14.868  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:14.868  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:14.868  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:08:14.868  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:14.868  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:14.868  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:14.868  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:14.878  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-02 19:08:14.878  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-02 19:08:14.878  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:14.878  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:14.878  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:14.878  7226  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:14.878  3188  3188 I BluetoothPbapService: Handler(): got msg=1
,09-02 19:08:14.878  1019  1032 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-02 19:08:14.888  7812  7829 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 19:08:14.888  7812  7829 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:14.888  4850  4850 D BluetoothPan: BluetoothPAN Proxy object connected
,09-02 19:08:14.888  1019  1048 D BluetoothPan: Binding service...
09-02 19:08:14.888  4850  4850 D PanProfile: Bluetooth service connected
,09-02 19:08:14.888  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-02 19:08:14.888  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-02 19:08:14.888  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 19:08:14.888  1448  1812 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 19:08:14.888  1448  1812 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:14.888  3188  7868 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-02 19:08:14.888  4850  4859 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:14.898  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 19:08:14.898  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:14.898  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:14.898  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:14.898  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:14.898  4850  4859 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:14.898  1019  1048 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:14.898  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 19:08:14.898  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-02 19:08:14.898  1019  1048 E BluetoothHeadset: BluetoothHeadset service is binded
09-02 19:08:14.898  3188  3352 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 19:08:14.898  4850  4850 D HeadsetProfile: Bluetooth service connected
,09-02 19:08:14.898  3188  7868 D BluetoothSocket: bindListen(): myUserId = 0
09-02 19:08:14.898  3188  3352 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:14.898  3188  7868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 19:08:14.898  1019  1048 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 19:08:14.898  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 19:08:14.898  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:14.898  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:14.898  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:14.898  3188  3188 D BluetoothA2dp: Proxy object connected
09-02 19:08:14.898  3188  3188 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-02 19:08:14.898  1423  1458 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:14.908  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 19:08:14.908  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:14.908  3188  7868 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-02 19:08:14.908  3188  7868 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 19:08:14.908  3188  7868 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 19:08:14.908  3188  7868 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a2df81e
09-02 19:08:14.908  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:14.908  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:14.908  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:14.908  3188  7868 D BluetoothSocket: channel: 19
09-02 19:08:14.908  3188  7868 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-02 19:08:14.908  1423  1458 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:14.908  4850  4858 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-02 19:08:15.048  1019  1048 I art     : Explicit concurrent mark sweep GC freed 48989(2MB) AllocSpace objects, 8(129KB) LOS objects, 33% free, 23MB/34MB, paused 2.297ms total 137.180ms
09-02 19:08:15.048  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-02 19:08:15.048  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-02 19:08:15.048  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:15.048  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:15.048  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:15.048  4850  4859 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 19:08:15.048  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-02 19:08:15.048  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-02 19:08:15.048  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:15.048  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:15.048  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:15.048  4850  4850 D BluetoothInputDevice: Proxy object connected
09-02 19:08:15.048  4850  4850 D HidProfile: Bluetooth service connected
,09-02 19:08:15.048  1423  7304 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:15.058  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 19:08:15.058  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:15.058  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:15.058  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:15.058  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:15.058  1423  7304 E BluetoothHeadset: BluetoothHeadset service is binded
09-02 19:08:15.058  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:15.058  1019  1048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 19:08:15.058  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 19:08:15.058  1019  1048 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:15.058  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-02 19:08:15.058  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 19:08:15.058  1019  1019 D BluetoothA2dp: Proxy object connected
09-02 19:08:15.058  4850  4859 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 19:08:15.058  4850  4850 D BluetoothMap: Proxy object connected
09-02 19:08:15.058  4850  4850 D MapProfile: Bluetooth service connected
09-02 19:08:15.058  4850  4850 D BluetoothMap: getConnectedDevices()
,09-02 19:08:15.058  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-02 19:08:15.058  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-02 19:08:15.058  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:15.058  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:15.058  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:15.058  4850  4850 D BluetoothPbap: Proxy object connected
09-02 19:08:15.058  4850  4850 D PbapServerProfile: Bluetooth service connected
09-02 19:08:15.058  1423  1458 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:15.058  1423  1458 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:15.058  7226  7234 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:15.068  7226  7234 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:15.068  1448  2496 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:15.068  1019  1048 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-02 19:08:15.068  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:15.068  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:15.068  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:15.068  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:15.068  1448  2496 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:15.068  1436  1457 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:15.068  1436  1457 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:15.068  1758  1963 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 19:08:15.068  1758  1963 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 19:08:15.068  3188  7808 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 19:08:15.068  3188  7808 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 19:08:15.068  4850  7303 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-02 19:08:15.068  4850  7303 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:15.068  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-02 19:08:15.068  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-02 19:08:15.068  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:15.068  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:15.068  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:15.078  4850  4850 D BluetoothA2dp: Proxy object connected
,09-02 19:08:15.078  4850  4850 D A2dpProfile: Bluetooth service connected
09-02 19:08:15.078  1636  1646 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-02 19:08:15.078  1636  1646 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 19:08:15.078  4850  4859 D Bluetoothsap: onBluetoothStateChange: up=true
09-02 19:08:15.078  4850  4859 D Bluetoothsap: Binding service...
,09-02 19:08:15.078  4850  4859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-02 19:08:15.078  1019  1048 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-02 19:08:15.078  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-02 19:08:15.078  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:15.078  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:15.078  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:15.078  4850  4859 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-02 19:08:15.078  4850  7303 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:15.078  4850  4850 D Bluetoothsap: BluetoothSAP Proxy object connected
09-02 19:08:15.078  4850  7303 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-02 19:08:15.078  4850  4850 D SapProfile: Bluetooth service connected
09-02 19:08:15.078  4850  4850 D Bluetoothsap: getConnectedDevices()
,09-02 19:08:15.078  1178  2417 D BluetoothAdapter: onBluetoothStateChange: up=true
09-02 19:08:15.078  1178  2417 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-02 19:08:15.078  1423  7304 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-02 19:08:15.078  1019  1048 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-02 19:08:15.078  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-02 19:08:15.078  1019  1048 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:15.078  1019  1048 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:08:15.088  1019  1048 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:15.088  1423  7304 E BluetoothHeadset: BluetoothHeadset service is binded
,09-02 19:08:15.088  1019  1048 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-02 19:08:15.088  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-02 19:08:15.088  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
09-02 19:08:15.088  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
,09-02 19:08:15.088  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-02 19:08:15.088  1423  1423 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@794352, true
,09-02 19:08:15.098  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,09-02 19:08:15.098  1423  1423 D BluetoothHeadset: registerMessageListener
,09-02 19:08:15.098  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-02 19:08:15.098  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:15.098  1178  1178 D BluetoothTile:  getBluetoothState : 12
,09-02 19:08:15.098  1178  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:08:15.098  1019  1136 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-02 19:08:15.098  1019  4260 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-02 19:08:15.098  1869  1869 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-02 19:08:15.098  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-02 19:08:15.108  4850  4850 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-02 19:08:15.108  1178  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:08:15.108  1178  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-02 19:08:15.108  3188  3352 D HeadsetService: registerMessageListener
,09-02 19:08:15.108  3188  3352 D HeadsetService: registerMessageListener
,09-02 19:08:15.108  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:08:15.108  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-02 19:08:15.108  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-02 19:08:15.108  3188  7860 D HeadsetStateMachine: Disconnected process message: 70
09-02 19:08:15.108  3188  7860 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3c5ff8ff
,09-02 19:08:15.118  4850  4850 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-02 19:08:15.118  4850  4850 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-02 19:08:15.118  4850  4850 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-02 19:08:15.118  4850  4850 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-02 19:08:15.118  3188  7869 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-02 19:08:15.118  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-02 19:08:15.118  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-02 19:08:15.118  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-02 19:08:15.118  3188  7860 D HeadsetStateMachine: Disconnected process message: 9
,09-02 19:08:15.118  3188  7860 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-02 19:08:15.128   283   727 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-02 19:08:15.128   283   727 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-02 19:08:15.128   283   727 V voice   : voice_set_parameters: exit with code(-2)
09-02 19:08:15.128   283   727 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-02 19:08:15.128   283   727 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-02 19:08:15.128   283   727 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-02 19:08:15.128   283   727 V audio_hw_primary: adev_set_parameters: exit
09-02 19:08:15.128  3188  7869 D BluetoothSocket: bindListen(): myUserId = 0
09-02 19:08:15.128  3188  7869 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:08:15.128  3188  7860 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-02 19:08:15.128  3188  7869 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
,09-02 19:08:15.128  3188  7869 D BluetoothSocket: bindListen(), new LocalSocket 
09-02 19:08:15.128  3188  7869 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-02 19:08:15.128  3188  7869 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@6f4e6cc
09-02 19:08:15.128  3188  7869 D BluetoothSocket: channel: 5
,09-02 19:08:15.128  4850  4850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 19:08:15.128  1019  1136 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-02 19:08:15.128  1019  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-02 19:08:15.128  1019  1136 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:15.128  1019  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:15.128  1019  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-02 19:08:15.138  1636  1636 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 19:08:15.148  4850  4850 D DockEventReceiver: finishStartingService: stopping service
,09-02 19:08:15.148  4850  4850 D BluetoothNotiBroadcastReceiver: onReceive
,09-02 19:08:15.148  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-02 19:08:15.148  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-02 19:08:15.158  3188  3188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37a0a48e
,09-02 19:08:15.158  3188  3188 D BtConfig.SecureMode: isSecureModeOn:false
,09-02 19:08:15.158  1019  1505 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-02 19:08:15.158  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-02 19:08:15.158  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:15.158  1019  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:15.158  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-02 19:08:15.168  1019  1136 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-02 19:08:15.178  3188  7874 D BluetoothSocket: bindListen(): myUserId = 0
,09-02 19:08:15.178  3188  7874 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 19:08:15.178  3188  7874 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[87]}
,09-02 19:08:15.178  3188  7874 D BluetoothSocket: bindListen(), new LocalSocket 
,09-02 19:08:15.178  3188  7874 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-02 19:08:15.178  3188  7874 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1befa3b8
,09-02 19:08:15.178  3188  7874 D BluetoothSocket: channel: 12
,09-02 19:08:15.188  3188  7874 I BtOppRfcommListener: Accept thread started.
,09-02 19:08:15.698  7226  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:15.698  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:15.698  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:15.698  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 19:08:15.698  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:15.698  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:15.698  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:15.698  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:15.708  7226  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:15.708  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:08:15.708  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@69dae38 added. We now have 8 listener(s)
,09-02 19:08:15.708  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:08:15.708  1019  1505 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-02 19:08:15.708  1019  1505 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-02 19:08:15.708  1019  1505 D SecContentProvider2: mCursor = null
,09-02 19:08:15.718  1019  1505 D WifiService: setWifiEnabled: false pid=7226, uid=10170
,09-02 19:08:15.718  1019  1505 D SettingsProvider: name = wifi_on
,09-02 19:08:15.718  7226  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:15.718  1019  1338 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-02 19:08:15.718  1019  1338 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-02 19:08:15.718  1019  1338 D SecContentProvider2: mCursor = null
,09-02 19:08:15.728  1019  1338 D WifiService: setWifiEnabled: true pid=7226, uid=10170
,09-02 19:08:15.728  1019  1338 W ActivityManager: Permission Denial: getCurrentUser() from pid=7226, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-02 19:08:15.728  1019  1338 W WifiService: Failed getting userId using ActivityManagerNative
09-02 19:08:15.728  1019  1338 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7226, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-02 19:08:15.728  1019  1338 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-02 19:08:15.728  1019  1338 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-02 19:08:15.728  1019  1338 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-02 19:08:15.728  1019  1338 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-02 19:08:15.728  1019  1338 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-02 19:08:15.728  1019  1338 D SettingsProvider: name = wifi_on
,09-02 19:08:15.738  1019  1127 E WifiHW  : ##################### set firmware type 0 #####################
,09-02 19:08:16.078  1019  1046 D Tethering: interfaceAdded wlan0
,09-02 19:08:16.078  1019  1131 E Tethering: No numeric data
,09-02 19:08:16.078  1019  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 19:08:16.078  1019  1131 D Tethering: clearTetheredNotification()
,09-02 19:08:16.078  1019  1124 V NetworkStats: performPollLocked(flags=0x1)
09-02 19:08:16.078  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:16.088  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 19:08:16.088  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 19:08:16.088  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 19:08:16.088  1178  1178 D HotspotTile: updateTetherState():false, false
09-02 19:08:16.088  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:16.088  1019  1124 V NetworkStats: performPollLocked() took 7ms
,09-02 19:08:16.098  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:16.098  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:08:16.098  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:16.098  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:08:16.098  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:16.098  1019  1131 D Tethering: InitialState.processMessage what=4
,09-02 19:08:16.098  1019  1131 E Tethering: No numeric data
,09-02 19:08:16.098  1019  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-02 19:08:16.098  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-02 19:08:16.098  1019  1131 D Tethering: clearTetheredNotification()
09-02 19:08:16.098  1178  1178 D HotspotTile: updateTetherState():false, false
09-02 19:08:16.108  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:16.108  1019  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-02 19:08:16.108  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 19:08:16.108  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 19:08:16.108  1019  1046 D Tethering: interfaceAdded p2p0
,09-02 19:08:16.108  1019  1046 D Tethering: p2p0 is not a tetherable iface, ignoring
09-02 19:08:16.108  1019  1124 V NetworkStats: performPollLocked() took 6ms
09-02 19:08:16.108  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:16.108  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:16.118  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:16.118  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 19:08:16.118  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-02 19:08:16.118  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 19:08:16.118   278   981 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
09-02 19:08:16.118   278   981 D SoftapController: Softap fwReload - Ok
,09-02 19:08:16.118   278   981 D CommandListener: Setting iface cfg
09-02 19:08:16.118   278   981 D CommandListener: Trying to bring down wlan0
,09-02 19:08:16.128   278   981 D CommandListener: Clearing all IP addresses on wlan0,
,09-02 19:08:16.128  1019  1127 E WifiHW  : supplicant_name : p2p_supplicant
,09-02 19:08:16.138  1019  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,09-02 19:08:16.148  4850  4850 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:08:16.148  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-02 19:08:16.148  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 19:08:16.148  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-02 19:08:16.148  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:16.148  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:16.148  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:16.148  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:16.148  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:16.148  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:16.148  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-02 19:08:16.148  1178  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-02 19:08:16.158  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:16.158  1178  1178 D HotspotTile: onReceive : 2, 0
,09-02 19:08:16.158  1019  1505 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-02 19:08:16.158  1019  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:08:16.158  1019  1505 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:16.158  1019  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:08:16.168  1019  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:08:16.168  1663  1663 I Hs20UtilService: Starting #19
,09-02 19:08:16.168  7400  7400 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-02 19:08:16.168  1663  1703 I Hs20UtilService: Message received 5011
,09-02 19:08:16.168  7400  7400 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 19:08:16.168  7400  7400 D SecurityLogAgent: StateMachine : Current State = 1
,09-02 19:08:16.168  7400  7400 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 19:08:16.178  7885  7885 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-02 19:08:16.178  7885  7885 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-02 19:08:16.178  7885  7885 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-02 19:08:16.198  7885  7885 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-02 19:08:16.198   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7885
09-02 19:08:16.198   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-02 19:08:16.198  7885  7885 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-02 19:08:16.198  7885  7885 I wpa_supplicant: ssSupport state is = 1
09-02 19:08:16.198  7885  7885 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-02 19:08:16.198  7885  7885 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-02 19:08:16.198   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7885
09-02 19:08:16.198   399   399 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-02 19:08:16.328   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,09-02 19:08:16.338  7885  7885 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-02 19:08:16.378  7885  7885 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-02 19:08:16.378  7885  7885 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-02 19:08:16.398  7885  7885 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,09-02 19:08:16.398   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7885
09-02 19:08:16.398   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-02 19:08:16.398  7885  7885 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-02 19:08:16.398  7885  7885 I wpa_supplicant: ssSupport state is = 1,
09-02 19:08:16.398  7885  7885 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:16.398  7885  7885 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-02 19:08:16.398  7885  7885 E wpa_supplicant: SIM READ ERROR
09-02 19:08:16.398  7885  7885 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-02 19:08:16.398  7885  7885 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 19:08:16.398  7885  7885 E wpa_supplicant: SIM READ ERROR,
09-02 19:08:16.398  7885  7885 I wpa_supplicant: Blacklist: Clear (all) 
09-02 19:08:16.398  7885  7885 I wpa_supplicant: wpa_default_ap_write_once,
09-02 19:08:16.398  7885  7885 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-02 19:08:16.398  7885  7885 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-02 19:08:16.398  7885  7885 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
,09-02 19:08:16.398  7885  7885 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:16.398  7885  7885 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,09-02 19:08:16.398  7885  7885 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-02 19:08:16.408  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:08:16.408  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
,09-02 19:08:16.408  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:08:16.508  7885  7885 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-02 19:08:16.678  7885  7885 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-02 19:08:16.678  7885  7885 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-02 19:08:16.688  7885  7885 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
09-02 19:08:16.688   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7885
09-02 19:08:16.688   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-02 19:08:16.688  7885  7885 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-02 19:08:16.688  7885  7885 I wpa_supplicant: ssSupport state is = 1
09-02 19:08:16.688  7885  7885 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-02 19:08:16.688  7885  7885 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-02 19:08:16.708  7885  7885 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-02 19:08:16.708   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7885
09-02 19:08:16.708   399   399 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-02 19:08:16.708  7885  7885 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-02 19:08:16.708  7885  7885 I wpa_supplicant: ssSupport state is = 1
09-02 19:08:16.708  7885  7885 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:16.708  7885  7885 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-02 19:08:16.708  7885  7885 E wpa_supplicant: SIM READ ERROR
09-02 19:08:16.708  7885  7885 I wpa_supplicant: wpa_default_ap_write_once
,09-02 19:08:16.708  7885  7885 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-02 19:08:16.708  7885  7885 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-02 19:08:16.718  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false,
09-02 19:08:16.718  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
09-02 19:08:16.718  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-02 19:08:16.718  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false,
09-02 19:08:16.718  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 19:08:16.718  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-02 19:08:16.828  7885  7885 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-02 19:08:16.828  7885  7885 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-02 19:08:16.948  7885  7885 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-02 19:08:16.948  7885  7885 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-02 19:08:16.948  7885  7885 I wpa_supplicant: Skip scan - bUseNetwork false
,09-02 19:08:16.958  1019  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-02 19:08:16.958  1019  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-02 19:08:16.958  7885  7885 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-02 19:08:16.958  7885  7885 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-02 19:08:16.958  7885  7885 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-02 19:08:16.958  7885  7885 E wpa_supplicant: SIM READ ERROR
09-02 19:08:16.958  7885  7885 I wpa_supplicant: Blacklist: Clear (all) 
,09-02 19:08:16.978  7885  7885 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-02 19:08:16.988  7885  7885 I wpa_supplicant: Skip scan - bUseNetwork false
09-02 19:08:16.988  1019  1127 D WifiConfigStore: Loading config and enabling all networks 
,09-02 19:08:16.998  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-02 19:08:16.998  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:16.998  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 19:08:16.998  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:16.998  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:17.008  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:17.008  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:17.008  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-02 19:08:17.008  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-02 19:08:17.008  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:08:17.008  1178  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-02 19:08:17.008  1178  1178 D HotspotTile: onReceive : 3, 0
,09-02 19:08:17.008  4850  4850 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-02 19:08:17.008  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-02 19:08:17.008  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:17.008  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:17.008  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:17.008  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:17.008  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:17.008  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:17.008  7226  7226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:17.018  1019  1032 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 19:08:17.018  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:08:17.018  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:17.018  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:17.018  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:08:17.018  1019  1127 E WifiConfigStore: Not a HS20
,09-02 19:08:17.018  1663  1663 I Hs20UtilService: Starting #20
,09-02 19:08:17.018  1663  1703 I Hs20UtilService: Message received 5011
,09-02 19:08:17.018  7226  7226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:17.028  7400  7400 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-02 19:08:17.028  7400  7400 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-02 19:08:17.028  7400  7400 D SecurityLogAgent: StateMachine : Current State = 1
09-02 19:08:17.028  7400  7400 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-02 19:08:17.028  1019  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-02 19:08:17.038  1019  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-02 19:08:17.038  7885  7885 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-02 19:08:17.038  7885  7885 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-02 19:08:17.038  7885  7885 I wpa_supplicant: reset timer : RESET_TIMER 0
09-02 19:08:17.038  7885  7885 I wpa_supplicant: P2P: Current p2p state = IDLE
09-02 19:08:17.038  7885  7885 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-02 19:08:17.038  7885  7885 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-02 19:08:17.038  7885  7885 I wpa_supplicant: First Scan Start
,09-02 19:08:17.038  7885  7885 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-02 19:08:17.038  1019  1127 D WifiNative-wlan0: Setting external_sim to 1
,09-02 19:08:17.038  1019  1127 D WifiStateMachine: Setting OUI to DA-A1-19
09-02 19:08:17.038  1019  1127 I WifiNative-HAL: startHal
09-02 19:08:17.038  1019  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9efa888c
09-02 19:08:17.038  1019  1127 I WifiNative-HAL: Could not start hal
,09-02 19:08:17.048  7416  7416 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-02 19:08:17.048  1019  1127 E WifiNative-wlan0: do suspend true
,09-02 19:08:17.048  1019  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-02 19:08:17.048   278   981 D CommandListener: Setting iface cfg
09-02 19:08:17.048   278   981 D CommandListener: Trying to bring up p2p0
,09-02 19:08:17.048  1019  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-02 19:08:17.048  1019  1126 D WifiP2pService: P2pEnablingState
,09-02 19:08:17.048  1019  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-02 19:08:17.048  1019  1126 D WifiP2pService: P2p socket connection successful
,09-02 19:08:17.048  1019  1126 D WifiP2pService: P2pEnabledState
,09-02 19:08:17.058  1019  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-02 19:08:17.058  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-02 19:08:17.058  1019  1129 E ConnectivityService: updateNetworkInfo()
,09-02 19:08:17.058  1019  1049 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,09-02 19:08:17.058  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 19:08:17.058  1019  1049 D WifiDisplayController: disconnect
09-02 19:08:17.058  1019  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-02 19:08:17.058  1019  1049 D WifiDisplayController: updateConnection
09-02 19:08:17.058  1019  1049 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-02 19:08:17.058  1019  1049 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-02 19:08:17.058  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
09-02 19:08:17.058  1019  1152 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:08:17.058  1019  1152 I WifiNative-HAL: startHal
,09-02 19:08:17.058  1019  1019 D RttService: SCAN_AVAILABLE : 3
,09-02 19:08:17.058  1019  1153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-02 19:08:17.058  1019  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-02 19:08:17.058  1019  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-02 19:08:17.058  1019  1127 E WifiNative-wlan0: invaild command id : 215
,09-02 19:08:17.058  1019  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-02 19:08:17.058  1019  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-02 19:08:17.058  1019  1127 E WifiNative-wlan0: invaild command id : 215
,09-02 19:08:17.058  1019  1049 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-02 19:08:17.058  1019  1049 D WifiDisplayAdapter: onP2pDisconnected
09-02 19:08:17.058  1019  1049 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-02 19:08:17.058  1019  1049 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-02 19:08:17.068  1019  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,09-02 19:08:17.068  7885  7885 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-02 19:08:17.068  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-02 19:08:17.068  1019  4260 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-02 19:08:17.068  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-02 19:08:17.068  7885  7885 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-02 19:08:17.068  1019  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9de6a9bc
,09-02 19:08:17.068  1019  1152 I WifiNative-HAL: Could not start hal,
09-02 19:08:17.068  1019  1152 E WifiScanningService: could not start HAL
09-02 19:08:17.068  1019  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
09-02 19:08:17.068  7885  7885 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-02 19:08:17.068  1019  1126 D WifiP2pService: DeviceAddress: 0a:75:42
09-02 19:08:17.068  4850  4850 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-02 19:08:17.068  4850  4850 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-02 19:08:17.068  1019  1127 E WifiStateMachine: Failed to set frequency band 0
09-02 19:08:17.068  1019  1049 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-02 19:08:17.068  1019  1049 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-02 19:08:17.068  1019  1049 D WifiDisplayController:  primary type: 10-0050F204-5
09-02 19:08:17.068  1019  1049 D WifiDisplayController:  secondary type: null
09-02 19:08:17.068  1019  1049 D WifiDisplayController:  wps: 0
09-02 19:08:17.068  1019  1049 D WifiDisplayController:  grpcapab: 0
09-02 19:08:17.068  1019  1049 D WifiDisplayController:  devcapab: 0
09-02 19:08:17.068  1019  1049 D WifiDisplayController:  status: 3
09-02 19:08:17.068  1019  1049 D WifiDisplayController:  wfdInfo: null
09-02 19:08:17.068  1019  1049 D WifiDisplayController:  groupownerAddress: null
09-02 19:08:17.068  1019  1049 D WifiDisplayController:  GOdeviceName: null
09-02 19:08:17.068  1019  1049 D WifiDisplayController:  interfaceAddress: 
09-02 19:08:17.068  1019  1049 D WifiDisplayController:  SConnectInfo : null
09-02 19:08:17.068  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-02 19:08:17.068  1019  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 19:08:17.068  1019  1127 D SecContentProvider2: mCursor = null
,09-02 19:08:17.078  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-02 19:08:17.078  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:08:17.078  1019  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 19:08:17.078  1019  1127 D SecContentProvider2: mCursor = null
09-02 19:08:17.078  4850  4850 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-02 19:08:17.078  4850  4937 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 19:08:17.078  7368  7368 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 19:08:17.078  7368  7368 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-02 19:08:17.078  7368  7368 D FileShare-Client: Outbound.stopDelayTimer - 
,09-02 19:08:17.088  1019  1046 D Tethering: interfaceLinkStateChanged p2p0, false
09-02 19:08:17.088  1019  1046 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-02 19:08:17.088  1019  1046 D Tethering: interfaceStatusChanged p2p0, false
,09-02 19:08:17.088  7385  7385 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-02 19:08:17.108  1019  1126 D WifiP2pService: sending p2p persistent groups changed broadcast,
09-02 19:08:17.108  1019  1126 D WifiP2pService: InactiveState
,09-02 19:08:17.108  1019  1126 D WifiP2pService: InactiveState{ what=143376 }
,09-02 19:08:17.108  1019  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-02 19:08:17.108  7885  7885 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-02 19:08:17.108  1019  1126 D WifiP2pService: InactiveState{ what=143376 }
,09-02 19:08:17.108  1019  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-02 19:08:17.138  1019  1219 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-02 19:08:17.758  7226  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 19:08:17.758  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:17.758  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:17.758  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:17.758  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:17.758  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:17.758  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:17.758  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:17.768  7226  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:17.768  7226  7279 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-02 19:08:17.768  7226  7279 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-02 19:08:17.768  7226  7279 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1c7c10ec Bundle[{}]
,09-02 19:08:17.768  7226  7279 I io.jxcore.node.LifeCycleMonitor: start: OK
09-02 19:08:17.768  7226  7279 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-02 19:08:17.768  7226  7279 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-02 19:08:17.768  7226  7279 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-02 19:08:17.778  7226  7279 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-02 19:08:17.778  7226  7279 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-02 19:08:17.778  7226  7279 I System.out: Running OutgoingSocketThread
,09-02 19:08:17.778  7226  7895 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1454)
,09-02 19:08:17.788  7226  7895 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49690
,09-02 19:08:17.788  7226  7895 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-02 19:08:17.788   288   288 E SMD     : DCD OFF
,09-02 19:08:18.268  7885  7885 I wpa_supplicant: nl80211: Received scan results (35 BSSes)
,09-02 19:08:18.278  7885  7885 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-02 19:08:18.278  1019  7891 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-02 19:08:18.278  7885  7885 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-02 19:08:18.278  7885  7885 I wpa_supplicant: Trying to associate with  'G700'
09-02 19:08:18.278  7885  7885 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-02 19:08:18.278  7885  7885 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-02 19:08:18.298  1019  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 19:08:18.298  1019  1127 D SecContentProvider2: mCursor = null
,09-02 19:08:18.398  7885  7885 E wpa_supplicant: Cmd 35605 not handled
,09-02 19:08:18.398  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:18.398  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
,09-02 19:08:18.398  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-02 19:08:18.398  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false,
,09-02 19:08:18.398  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:08:18.398  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:08:18.398  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-02 19:08:18.398  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, false
09-02 19:08:18.398  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-02 19:08:18.398  1019  1046 D Tethering: interfaceStatusChanged wlan0, false
09-02 19:08:18.398  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, true
09-02 19:08:18.398  1019  1046 D Tethering: interfaceStatusChanged wlan0, true
09-02 19:08:18.408  1019  1131 E Tethering: No numeric data
09-02 19:08:18.408  1019  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-02 19:08:18.408  1019  1131 D Tethering: clearTetheredNotification()
09-02 19:08:18.408  7885  7885 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-02 19:08:18.408  7885  7885 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-02 19:08:18.408  7885  7885 I wpa_supplicant: Associated with F4.99.3E
,09-02 19:08:18.408  7885  7885 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-02 19:08:18.408  7885  7885 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-02 19:08:18.408  7885  7885 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-02 19:08:18.408  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:18.408  1019  1124 V NetworkStats: performPollLocked(flags=0x1)
09-02 19:08:18.408  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-02 19:08:18.418  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-02 19:08:18.408  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 19:08:18.418  1178  1178 D HotspotTile: updateTetherState():false, false,
09-02 19:08:18.418  7885  7885 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-02 19:08:18.418  1019  1124 V NetworkStats: performPollLocked() took 6ms
09-02 19:08:18.418  7885  7885 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-02 19:08:18.418  7885  7885 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-02 19:08:18.418  7885  7885 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-02 19:08:18.418  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:18.418  1019  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-02 19:08:18.418  7885  7885 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-02 19:08:18.418  1019  1127 D SecContentProvider2: mCursor = null
09-02 19:08:18.418  7885  7885 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-02 19:08:18.418  7885  7885 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-02 19:08:18.418  7885  7885 I wpa_supplicant: Blacklist: Clear (temp) 
09-02 19:08:18.418  7885  7885 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-02 19:08:18.428  1019  1046 D Tethering: interfaceLinkStateChanged wlan0, true
09-02 19:08:18.428  1019  1046 D Tethering: interfaceStatusChanged wlan0, true
,09-02 19:08:18.428  1019  1046 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-02 19:08:18.428  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:18.428  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:18.428  1019  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 19:08:18.428  1019  1127 D SecContentProvider2: mCursor = null
,09-02 19:08:18.438  1019  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-02 19:08:18.438  1019  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,09-02 19:08:18.448  1019  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 19:08:18.448  1019  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-02 19:08:18.448  1019  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-02 19:08:18.448  1019  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:08:18.448  1019  1129 E ConnectivityService: updateNetworkInfo()
,09-02 19:08:18.448  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-02 19:08:18.458  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-02 19:08:18.458  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 19:08:18.458  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:18.458  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:18.458  1019  1485 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 19:08:18.458  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:18.458  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:18.458  1019  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 19:08:18.458  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:08:18.458  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:18.458  1019  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:18.458  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-02 19:08:18.458  1663  1663 I Hs20UtilService: Starting #21
,09-02 19:08:18.468  1663  1703 I Hs20UtilService: Message received 5007
,09-02 19:08:18.468  4850  4850 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
09-02 19:08:18.468  4850  4850 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 19:08:18.468   278   981 D CommandListener: Setting iface cfg
,09-02 19:08:18.468  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-02 19:08:18.478  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 19:08:18.478  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:08:18.478  4850  4850 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-02 19:08:18.478  4850  4937 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-02 19:08:18.488  1019  1127 E WifiStateMachine: Start Dhcp Watchdog 3
,09-02 19:08:18.488  1019  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 19:08:18.488  1019  1127 D SecContentProvider2: mCursor = null
,09-02 19:08:18.498  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-02 19:08:18.498  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-02 19:08:18.498  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-02 19:08:18.498  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:18.498  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:18.498  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:18.498  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:18.508  1019  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-02 19:08:18.508  1019  1127 D SecContentProvider2: mCursor = null
,09-02 19:08:18.518  1019  1127 E WifiNative-wlan0: do suspend false
,09-02 19:08:18.518  1019  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-02 19:08:18.518  1019  1126 D WifiP2pService: P2pEnabledState{ what=143375 },
,09-02 19:08:18.728  7899  7899 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-02 19:08:18.738  7899  7899 I dhcpcd  : version 5.5.6 starting,
,09-02 19:08:18.738  7899  7899 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-02 19:08:18.788  7226  7279 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1455),
09-02 19:08:18.788  7226  7279 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1455)
,09-02 19:08:18.788  7226  7279 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1460),
,09-02 19:08:18.788  7226  7279 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-02 19:08:18.788  7226  7279 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1461)
,09-02 19:08:18.788  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-02 19:08:18.788  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13886e11 added. We now have 2 listener(s)
,09-02 19:08:18.788  7899  7899 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-02 19:08:18.788  7899  7899 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-02 19:08:18.788  7899  7899 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-02 19:08:18.788  7899  7899 I dhcpcd  : bssid match
09-02 19:08:18.788  7899  7899 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
09-02 19:08:18.798  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-02 19:08:18.798  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:08:18.798  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 19:08:18.798  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:08:18.798  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14c63b76 added. We now have 9 listener(s)
09-02 19:08:18.798  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:08:18.798  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 19:08:18.798  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:08:18.798  7226  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-02 19:08:18.798  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:18.798  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:18.798  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:18.798  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:18.798  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:18.798  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:18.798  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:08:18.798  7226  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 19:08:18.798  7226  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:08:18.808  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 19:08:18.808  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259b75e4 added. We now have 3 listener(s)
09-02 19:08:18.808  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:08:18.808  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:18.808  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-02 19:08:18.808  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:08:18.808  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:08:18.808  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:08:18.808  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3374da4d added. We now have 10 listener(s)
,09-02 19:08:18.808  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:08:18.808  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:08:18.808  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:08:18.808  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-02 19:08:18.808  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:08:18.808  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:18.808  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:08:18.808  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 19:08:18.808  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13886e11 removed from the list
09-02 19:08:18.808  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:18.808  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14c63b76 removed from the list
09-02 19:08:18.808  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 19:08:18.808  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:08:18.808  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:08:18.808  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:18.808  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:08:18.808  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 19:08:18.808  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:18.808  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14c63b76 not in the list
09-02 19:08:18.808  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:08:18.808  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:18.808  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:08:18.808  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:08:18.808  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:18.808  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3374da4d removed from the list
,09-02 19:08:18.808  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:08:18.808  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:08:18.808  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:18.808  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:08:18.808  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@259b75e4 removed from the list
09-02 19:08:18.808  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:08:18.808  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27d29902 added. We now have 2 listener(s)
,09-02 19:08:18.808  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-02 19:08:18.808  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:08:18.808  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:08:18.808  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 19:08:18.808  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d5f213 added. We now have 9 listener(s)
09-02 19:08:18.808  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:08:18.808  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 19:08:18.818  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:08:18.818  7226  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:08:18.818  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:18.818  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:18.818  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:18.818  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:18.818  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:18.818  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:18.818  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 19:08:18.818  1019  1315 E Watchdog: !@Sync 6
,09-02 19:08:18.818  7226  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:18.818  7226  7279 D io.jxcore.node.ConnectivityMonitor: start: OK,
09-02 19:08:18.818  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:08:18.818  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d41ce49 added. We now have 3 listener(s)
09-02 19:08:18.818  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:08:18.828  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:18.828  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-02 19:08:18.828  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:08:18.828  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:08:18.828  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:08:18.828  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2755434e added. We now have 10 listener(s)
09-02 19:08:18.828  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:08:18.828  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:08:18.828  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:08:18.828  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:08:18.828  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:08:18.828  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 19:08:18.828  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 19:08:18.828  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 19:08:18.828  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 19:08:18.838  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 19:08:18.838  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 19:08:18.838  7226  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 19:08:18.838  3188  7325 D BtGatt.GattService: registerClient() - UUID=cdb9c982-0685-41b9-8a25-062a7d4501a8
,09-02 19:08:18.878  3188  3265 D BtGatt.GattService: onClientRegistered() - UUID=cdb9c982-0685-41b9-8a25-062a7d4501a8, clientIf=6
,09-02 19:08:18.878  7226  7235 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-02 19:08:18.878  3188  3202 D BtGatt.GattService: start scan with filters
,09-02 19:08:18.888  3188  3329 D BtGatt.ScanManager: handling starting scan
09-02 19:08:18.888  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 19:08:18.888  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 19:08:18.888  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 19:08:18.888  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 19:08:18.888  3188  3265 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-02 19:08:18.888  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:08:18.888  7899  7899 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
09-02 19:08:18.888  3188  3329 D BtGatt.ScanManager: allow scan with filters
09-02 19:08:18.888  3188  3329 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 19:08:18.888  3188  3329 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,09-02 19:08:18.888  3188  3265 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-02 19:08:18.888  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:18.888  3188  3329 D BtGatt.ScanManager: Starting BLE batch scan
09-02 19:08:18.888  3188  3329 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
,09-02 19:08:18.898  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 19:08:18.898  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 19:08:18.898  7226  7226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:08:18.898  3188  3265 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-02 19:08:18.898  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:18.898  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 19:08:18.898  3188  3265 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-02 19:08:18.898  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:18.908  7226  7279 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-02 19:08:18.908  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 19:08:18.908  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-02 19:08:18.908  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:18.908  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-02 19:08:18.908  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 19:08:18.908  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-02 19:08:18.908  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-02 19:08:18.908  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-02 19:08:18.908  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-02 19:08:18.908  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 19:08:18.908  3188  3199 D BtGatt.GattService: stopScan() - queue size =1
,09-02 19:08:18.918  3188  3326 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 19:08:18.918  3188  3329 D BtGatt.ScanManager: filter size is 1
,09-02 19:08:18.918  3188  3329 D BtGatt.ScanManager: delete FilterIndex - 6
,09-02 19:08:18.918  3188  3265 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-02 19:08:18.918  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:18.918  3188  3329 D BtGatt.ScanManager: stopping BLe Batch
,09-02 19:08:18.918  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:08:18.918  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 19:08:18.918  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 19:08:18.918  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 19:08:18.918  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 19:08:18.918  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:08:18.918  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 19:08:18.928  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 19:08:18.928  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 19:08:18.928  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:08:18.928  3188  3265 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-02 19:08:18.928  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:18.928  3188  3329 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 19:08:18.928  3188  3265 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-02 19:08:18.928  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:18.928  7226  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 19:08:18.928  7226  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:08:18.928  7226  7226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:08:18.928  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:08:18.928  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 19:08:18.928  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:08:18.928  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 19:08:18.928  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:18.928  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:08:18.928  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 19:08:18.928  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27d29902 removed from the list
09-02 19:08:18.928  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:18.928  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d5f213 removed from the list
,09-02 19:08:18.928  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:08:18.928  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:08:18.938  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:08:18.938  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:18.938  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:08:18.938  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:08:18.938  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:08:18.938  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38d5f213 not in the list
09-02 19:08:18.938  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:18.938  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:18.938  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:08:18.938  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 19:08:18.938  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:18.938  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2755434e removed from the list
,09-02 19:08:18.938  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-02 19:08:18.938  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:18.938  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:08:18.938  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:08:18.938  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d41ce49 removed from the list
09-02 19:08:18.938  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:08:18.938  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1746465a added. We now have 2 listener(s)
09-02 19:08:18.938  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-02 19:08:18.938  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:08:18.938  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:08:18.938  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-02 19:08:18.938  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f7908b added. We now have 9 listener(s)
09-02 19:08:18.938  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:08:18.938  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
09-02 19:08:18.948  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:08:18.948  7226  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:08:18.948  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:18.948  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:18.948  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:18.948  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:18.948  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:18.948  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:18.948  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:18.948  7226  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:18.948  7226  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:08:18.948  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:08:18.948  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@114ffd81 added. We now have 3 listener(s)
,09-02 19:08:18.948  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 19:08:18.948  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:18.958  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-02 19:08:18.958  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:08:18.958  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:08:18.958  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:08:18.958  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11126e26 added. We now have 10 listener(s)
09-02 19:08:18.958  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 19:08:18.958  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:08:18.958  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:08:18.958  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:08:18.958  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:08:18.958  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:08:18.958  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 19:08:18.958  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 19:08:18.968  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 19:08:18.968  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 19:08:18.968  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 19:08:18.968  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 19:08:18.968  7226  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 19:08:18.968  3188  3326 D BtGatt.GattService: registerClient() - UUID=b22bb7e7-fe00-4bc2-bcbe-6bd92c982ab6
,09-02 19:08:18.978  7899  7899 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,09-02 19:08:19.008  3188  3265 D BtGatt.GattService: onClientRegistered() - UUID=b22bb7e7-fe00-4bc2-bcbe-6bd92c982ab6, clientIf=6
,09-02 19:08:19.008  7226  7234 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-02 19:08:19.008  3188  3352 D BtGatt.GattService: start scan with filters
,09-02 19:08:19.018  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
09-02 19:08:19.018  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 19:08:19.018  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 19:08:19.018  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
09-02 19:08:19.018  3188  3329 D BtGatt.ScanManager: handling starting scan
09-02 19:08:19.018  3188  3265 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-02 19:08:19.018  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:19.018  3188  3329 D BtGatt.ScanManager: allow scan with filters,
09-02 19:08:19.018  3188  3329 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 19:08:19.018  3188  3329 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,09-02 19:08:19.018  3188  3265 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-02 19:08:19.018  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:08:19.018  3188  3329 D BtGatt.ScanManager: Starting BLE batch scan
09-02 19:08:19.018  3188  3329 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-02 19:08:19.018  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:08:19.018  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 19:08:19.018  7226  7226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:08:19.028  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-02 19:08:19.028  3188  3265 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-02 19:08:19.028  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:19.028  3188  3265 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-02 19:08:19.028  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:19.038  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:08:19.038  7226  7279 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-02 19:08:19.038  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:08:19.038  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:08:19.038  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:08:19.038  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:08:19.038  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:19.038  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 19:08:19.038  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:08:19.038  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1746465a removed from the list
09-02 19:08:19.038  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:19.038  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f7908b removed from the list
09-02 19:08:19.038  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:08:19.038  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:08:19.038  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:19.038  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-02 19:08:19.038  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:19.038  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:08:19.038  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:08:19.038  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 19:08:19.038  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:19.038  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f7908b not in the list
09-02 19:08:19.038  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 19:08:19.038  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:08:19.038  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 19:08:19.038  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 19:08:19.038  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 19:08:19.038  3188  3202 D BtGatt.GattService: stopScan() - queue size =1
09-02 19:08:19.038  3188  3329 D BtGatt.ScanManager: filter size is 1,
09-02 19:08:19.038  3188  3329 D BtGatt.ScanManager: delete FilterIndex - 7
,09-02 19:08:19.048  3188  3199 D BtGatt.GattService: unregisterClient() - clientIf=6
09-02 19:08:19.048  3188  3265 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-02 19:08:19.048  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:08:19.048  3188  3329 D BtGatt.ScanManager: stopping BLe Batch
,09-02 19:08:19.048  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-02 19:08:19.048  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 19:08:19.048  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 19:08:19.048  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 19:08:19.048  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 19:08:19.048  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,09-02 19:08:19.048  3188  3265 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-02 19:08:19.048  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:08:19.048  3188  3329 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 19:08:19.048  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 19:08:19.048  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 19:08:19.048  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 19:08:19.048  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,09-02 19:08:19.058  3188  3265 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-02 19:08:19.058  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:19.058  7226  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:08:19.058  7226  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:08:19.058  7226  7226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:08:19.058  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:08:19.058  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:08:19.058  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-02 19:08:19.058  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11126e26 removed from the list
,09-02 19:08:19.058  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:08:19.058  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:19.058  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:08:19.058  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:08:19.058  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@114ffd81 removed from the list
,09-02 19:08:19.058  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:08:19.058  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62746b2 added. We now have 2 listener(s)
,09-02 19:08:19.058  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-02 19:08:19.058  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:08:19.058  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:08:19.058  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:08:19.058  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35ef8603 added. We now have 9 listener(s)
,09-02 19:08:19.058  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:08:19.058  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 19:08:19.068  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:08:19.078  7226  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:08:19.078  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:19.078  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:19.078  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:19.078  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:19.078  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:19.078  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:19.078  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:19.078  7226  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:19.078  7226  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 19:08:19.078  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:08:19.078  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d9ddbb9 added. We now have 3 listener(s)
,09-02 19:08:19.078  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:19.078  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-02 19:08:19.078  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:08:19.078  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:08:19.078  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:08:19.078  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f3f1bfe added. We now have 10 listener(s)
09-02 19:08:19.078  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:08:19.078  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:08:19.088  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 19:08:19.088  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 19:08:19.088  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 19:08:19.088  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 19:08:19.088  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:19.088  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 19:08:19.098  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 19:08:19.098  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,09-02 19:08:19.108  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 19:08:19.108  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 19:08:19.108  7226  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 19:08:19.118  3188  3352 D BtGatt.GattService: registerClient() - UUID=49e61563-3349-46a5-9269-9af741856747,
,09-02 19:08:19.168  3188  3265 D BtGatt.GattService: onClientRegistered() - UUID=49e61563-3349-46a5-9269-9af741856747, clientIf=6,
09-02 19:08:19.168  7226  7234 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-02 19:08:19.168  3188  3326 D BtGatt.GattService: start scan with filters,
09-02 19:08:19.168  3188  3329 D BtGatt.ScanManager: handling starting scan
,09-02 19:08:19.178  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
09-02 19:08:19.178  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-02 19:08:19.178  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 19:08:19.178  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 19:08:19.178  3188  3265 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-02 19:08:19.178  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:08:19.178  3188  3329 D BtGatt.ScanManager: allow scan with filters
09-02 19:08:19.178  3188  3329 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-02 19:08:19.178  3188  3329 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,09-02 19:08:19.178  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:08:19.178  7226  7226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 19:08:19.178  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 19:08:19.178  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 19:08:19.188  3188  3265 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-02 19:08:19.188  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:08:19.188  3188  3329 D BtGatt.ScanManager: Starting BLE batch scan
09-02 19:08:19.188  3188  3329 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-02 19:08:19.188  3188  3265 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-02 19:08:19.188  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:19.188  3188  3265 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-02 19:08:19.188  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:19.198  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 19:08:19.198  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 19:08:19.198  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 19:08:19.198  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:08:19.198  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:19.198  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 19:08:19.198  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:08:19.198  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62746b2 removed from the list
09-02 19:08:19.198  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:19.198  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35ef8603 removed from the list
09-02 19:08:19.198  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
09-02 19:08:19.198  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 19:08:19.198  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:19.198  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-02 19:08:19.198  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:19.198  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:08:19.198  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 19:08:19.198  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:08:19.198  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:08:19.198  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35ef8603 not in the list
09-02 19:08:19.198  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-02 19:08:19.198  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 19:08:19.198  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-02 19:08:19.198  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-02 19:08:19.198  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-02 19:08:19.198  3188  3199 D BtGatt.GattService: stopScan() - queue size =1
,09-02 19:08:19.198  3188  3326 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-02 19:08:19.198  3188  3329 D BtGatt.ScanManager: filter size is 1
09-02 19:08:19.198  3188  3329 D BtGatt.ScanManager: delete FilterIndex - 8
,09-02 19:08:19.198  3188  3265 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-02 19:08:19.198  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 19:08:19.198  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 19:08:19.198  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 19:08:19.198  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 19:08:19.198  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-02 19:08:19.208  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:08:19.208  3188  3329 D BtGatt.ScanManager: stopping BLe Batch
,09-02 19:08:19.208  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 19:08:19.208  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 19:08:19.208  7226  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-02 19:08:19.208  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 19:08:19.208  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:08:19.208  3188  3265 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-02 19:08:19.208  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-02 19:08:19.208  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:08:19.208  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:08:19.208  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:19.208  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f3f1bfe removed from the list
09-02 19:08:19.208  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 19:08:19.208  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:19.208  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:08:19.208  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:08:19.208  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d9ddbb9 removed from the list
,09-02 19:08:19.208  7226  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 19:08:19.208  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:08:19.208  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46cfa0a added. We now have 2 listener(s)
,09-02 19:08:19.208  7226  7226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 19:08:19.208  7226  7226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 19:08:19.208  3188  3329 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-02 19:08:19.208  3188  3265 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-02 19:08:19.208  3188  3265 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-02 19:08:19.208  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-02 19:08:19.208  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:08:19.208  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 19:08:19.208  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:08:19.208  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@451b27b added. We now have 9 listener(s)
09-02 19:08:19.208  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:08:19.218  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 19:08:19.218  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 19:08:19.218  7226  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 19:08:19.218  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 19:08:19.218  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 19:08:19.218  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 19:08:19.218  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 19:08:19.218  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 19:08:19.218  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 19:08:19.218  7226  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 19:08:19.218  7226  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 19:08:19.218  7226  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 19:08:19.218  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 19:08:19.218  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269248f1 added. We now have 3 listener(s)
,09-02 19:08:19.228  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:19.228  7226  7226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 19:08:19.228  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-02 19:08:19.228  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 19:08:19.228  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 19:08:19.228  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 19:08:19.228  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e8acd6 added. We now have 10 listener(s)
,09-02 19:08:19.228  7226  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 19:08:19.228  7226  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 19:08:19.228  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 19:08:19.228  7226  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 19:08:19.228  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 19:08:19.228  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:19.228  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 19:08:19.228  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 19:08:19.228  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46cfa0a removed from the list
,09-02 19:08:19.228  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:19.228  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@451b27b removed from the list
09-02 19:08:19.228  7226  7279 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 19:08:19.228  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:19.228  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:08:19.228  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:19.238  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 19:08:19.238  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 19:08:19.238  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 19:08:19.238  7226  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@451b27b not in the list
09-02 19:08:19.238  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 19:08:19.238  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 19:08:19.238  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 19:08:19.238  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 19:08:19.238  7226  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 19:08:19.238  7226  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e8acd6 removed from the list
09-02 19:08:19.238  7226  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-02 19:08:19.238  7226  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 19:08:19.238  7226  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 19:08:19.238  7226  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 19:08:19.238  7226  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269248f1 removed from the list
,09-02 19:08:19.238  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-02 19:08:19.238  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-02 19:08:19.238  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-02 19:08:19.238  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 19:08:19.238  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-02 19:08:19.238  7226  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 19:08:19.248  7226  7930 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1468, name: My test thread name)
,09-02 19:08:19.248  7226  7930 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1468, thread name: My test thread name)
,09-02 19:08:19.248  7226  7930 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1468, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 19:08:19.248  7226  7931 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1470, name: My test thread name)
,09-02 19:08:19.248  7226  7931 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1470, thread name: My test thread name)
,09-02 19:08:19.248  7226  7931 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1470, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 19:08:19.248  7226  7279 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-02 19:08:19.248  7226  7279 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-02 19:08:19.248  7226  7279 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-02 19:08:19.248  7226  7279 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-02 19:08:19.248  7226  7279 D com.test.thalitest.ThaliTestRunner: Total duration: 23259 ms
,09-02 19:08:19.258  7226  7279 I jxcore-log: *Native tests were executed*
09-02 19:08:19.258  7226  7279 I jxcore-log: 
,09-02 19:08:19.258  7226  7279 I jxcore-log: Total number of executed tests:  80
09-02 19:08:19.258  7226  7279 I jxcore-log: 
,09-02 19:08:19.258  7226  7279 I jxcore-log: Number of passed tests:  80
09-02 19:08:19.258  7226  7279 I jxcore-log: 
,09-02 19:08:19.258  7226  7279 I jxcore-log: Number of failed tests:  0
09-02 19:08:19.258  7226  7279 I jxcore-log: 
,09-02 19:08:19.258  7226  7279 I jxcore-log: Number of ignored tests:  0
09-02 19:08:19.258  7226  7279 I jxcore-log: 
,09-02 19:08:19.258  7226  7279 I jxcore-log: Total duration:  23259
09-02 19:08:19.258  7226  7279 I jxcore-log: 
,09-02 19:08:19.258  7226  7279 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-02 19:08:19.258  7226  7279 I jxcore-log: 
,09-02 19:08:19.258  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:08:19.258  7226  7279 I jxcore-log: 
09-02 19:08:19.268  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:08:19.268  7226  7279 I jxcore-log: 
09-02 19:08:19.268  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:08:19.268  7226  7279 I jxcore-log: 
09-02 19:08:19.268  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:08:19.268  7226  7279 I jxcore-log: 
09-02 19:08:19.268  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:08:19.268  7226  7279 I jxcore-log: 
09-02 19:08:19.268  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:08:19.268  7226  7279 I jxcore-log: 
09-02 19:08:19.268  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 19:08:19.268  7226  7279 I jxcore-log: 
09-02 19:08:19.278  7226  7226 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-02 19:08:19.278  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:08:19.278  7226  7279 I jxcore-log: 
09-02 19:08:19.278  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:08:19.278  7226  7279 I jxcore-log: 
09-02 19:08:19.278  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 19:08:19.278  7226  7279 I jxcore-log: 
,09-02 19:08:19.278  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 19:08:19.278  7226  7279 I jxcore-log: 
,09-02 19:08:19.278  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 19:08:19.278  7226  7279 I jxcore-log: 
,09-02 19:08:19.278  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:08:19.278  7226  7279 I jxcore-log: 
,09-02 19:08:19.278  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:08:19.278  7226  7279 I jxcore-log: 
09-02 19:08:19.278  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
,09-02 19:08:19.278  7226  7279 I jxcore-log: 
09-02 19:08:19.278  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 19:08:19.278  7226  7279 I jxcore-log: 
,09-02 19:08:19.278  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 19:08:19.278  7226  7279 I jxcore-log: 
09-02 19:08:19.278  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
,09-02 19:08:19.278  7226  7279 I jxcore-log: 
09-02 19:08:19.288  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 19:08:19.288  7226  7279 I jxcore-log: 
,09-02 19:08:19.288  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 19:08:19.288  7226  7279 I jxcore-log: 
,09-02 19:08:19.288  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:08:19.288  7226  7279 I jxcore-log: 
,09-02 19:08:19.288  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:08:19.288  7226  7279 I jxcore-log: 
09-02 19:08:19.288  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:08:19.288  7226  7279 I jxcore-log: 
,09-02 19:08:19.288  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:08:19.288  7226  7279 I jxcore-log: 
,09-02 19:08:19.288  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:08:19.288  7226  7279 I jxcore-log: 
,09-02 19:08:19.288  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:08:19.288  7226  7279 I jxcore-log: 
,09-02 19:08:19.288  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 19:08:19.288  7226  7279 I jxcore-log: 
,09-02 19:08:19.328  1019  1127 E WifiNative-wlan0: do suspend true,
,09-02 19:08:19.358  1019  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-02 19:08:19.358  1019  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-02 19:08:19.358  1019  1127 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-02 19:08:19.358  1019  1127 E WifiStateMachine: VerifyingLinkState enter
,09-02 19:08:19.368  1019  1129 E ConnectivityService: updateNetworkInfo()
,09-02 19:08:19.368  1019  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null,
09-02 19:08:19.368  1019  1129 D ConnectivityService: Adding iface wlan0 to network 504
,09-02 19:08:19.378  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-02 19:08:19.378  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-02 19:08:19.378  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 19:08:19.378  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.378  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.378  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.378  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.378  1019  1146 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-02 19:08:19.378  1019  1146 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-02 19:08:19.378  1019  1146 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-02 19:08:19.378  1019  1146 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-02 19:08:19.378  1019  1146 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-02 19:08:19.388  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-02 19:08:19.388  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:19.388  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-02 19:08:19.388  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.388  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.388  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.388  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:19.398  1019  1127 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check,
,09-02 19:08:19.408  1019  1219 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 19:08:19.408  1019  1219 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-02 19:08:19.408  1019  1219 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:19.408  1019  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:19.408  1019  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-02 19:08:19.408  1663  1663 I Hs20UtilService: Starting #22
09-02 19:08:19.408  1663  1703 I Hs20UtilService: Message received 5007
09-02 19:08:19.408  1019  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-02 19:08:19.408  1019  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-02 19:08:19.418  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-02 19:08:19.418  1019  1129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,09-02 19:08:19.418  1019  1129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,09-02 19:08:19.418  1019  1129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,09-02 19:08:19.418  1019  1129 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-02 19:08:19.418  1019  1129 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-02 19:08:19.418  1019  1129 D ConnectivityService: LTETest block dns file not exists
09-02 19:08:19.428  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-02 19:08:19.428  1019  1019 I WifiTrafficPoller: mBoosterFLAG : 0,
09-02 19:08:19.428  1019  1019 I WifiTrafficPoller: current booster mode : FullMode
,09-02 19:08:19.428  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-02 19:08:19.428  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:19.428  7226  7226 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-02 19:08:19.428  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-02 19:08:19.428  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.428  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.428  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.428  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.428  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 19:08:19.428  7226  7279 I jxcore-log: 
,09-02 19:08:19.438  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:19.438  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-02 19:08:19.438  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:19.438  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.438  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.438  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:19.438  4850  4850 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-02 19:08:19.438  4850  4850 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-02 19:08:19.438  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:19.438  1019  1129 V NetworkStats: updateIfacesLocked()
09-02 19:08:19.438  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 19:08:19.438  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
09-02 19:08:19.438  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 19:08:19.448  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:19.448  1019  1129 V NetworkStats: performPollLocked() took 6ms
,09-02 19:08:19.458  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:19.458  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:19.458  1019  1032 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 19:08:19.458  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 19:08:19.458  1019  1129 E ConnectivityService: updateNetworkInfo()
09-02 19:08:19.458  1019  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-02 19:08:19.458  1019  1129 E ConnectivityService: updateNetworkInfo()
09-02 19:08:19.458  1019  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-02 19:08:19.458  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:19.458  1019  1129 V NetworkStats: updateIfacesLocked()
09-02 19:08:19.458  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:19.458  1019  1129 V NetworkStats: performPollLocked(flags=0x1)
09-02 19:08:19.458  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:19.458  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-02 19:08:19.468  1663  1663 I Hs20UtilService: Starting #23
,09-02 19:08:19.468  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 19:08:19.468  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 19:08:19.468  1663  1703 I Hs20UtilService: Message received 5007
09-02 19:08:19.468  4850  4850 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-02 19:08:19.468  4850  4850 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-02 19:08:19.468  1019  1129 V NetworkStats: performPollLocked() took 6ms
,09-02 19:08:19.468  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:19.468  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
09-02 19:08:19.468  1019  1129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-02 19:08:19.468  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:19.468  1019  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-02 19:08:19.468  1019  7897 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:08:19.468  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-02 19:08:19.468  1019  7897 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-02 19:08:19.468  1019  7897 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-02 19:08:19.468  1019  7897 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-02 19:08:19.468  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-02 19:08:19.468  4850  4850 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-02 19:08:19.468  4850  4850 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-02 19:08:19.468  4850  4937 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-02 19:08:19.468  1019  7897 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-02 19:08:19.478  1019  1129 D ConnectivityService:    accepting network in place of null
09-02 19:08:19.478  1019  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-02 19:08:19.478  1019  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,09-02 19:08:19.478  1019  1129 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-02 19:08:19.478  1448  1448 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-02 19:08:19.478  1019  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-02 19:08:19.478  1448  1448 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 19:08:19.478  1019  1338 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-02 19:08:19.478   278   977 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-02 19:08:19.478  1019  1338 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-02 19:08:19.478   278   977 D Netd    : getNetworkForDns: using netid 504 for uid 1000
09-02 19:08:19.478  1019  1129 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-02 19:08:19.478  1019  1338 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:19.478  1019  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:19.478  1019  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-02 19:08:19.478  1663  1663 I Hs20UtilService: Starting #24
09-02 19:08:19.478  1019  1129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-02 19:08:19.478  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-02 19:08:19.478  1019  1131 D Tethering: MasterInitialState.processMessage what=3
09-02 19:08:19.488  1019  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-02 19:08:19.488  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:19.488  1019  1124 V NetworkStats: updateIfacesLocked()
09-02 19:08:19.488  1019  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-02 19:08:19.488  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 19:08:19.488  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-02 19:08:19.488  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
09-02 19:08:19.488  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-02 19:08:19.488  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-02 19:08:19.488  1178  1178 D StatusBar.NetworkController: updateDataNetType()
09-02 19:08:19.488  1663  1703 I Hs20UtilService: Message received 5007
,09-02 19:08:19.488  1019  1048 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-02 19:08:19.488  1019  1124 V NetworkStats: performPollLocked() took 5ms
09-02 19:08:19.488  1178  1726 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 19:08:19.488  1019  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-02 19:08:19.488  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:19.488  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:19.488  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:19.488  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:19.488  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:19.488  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-02 19:08:19.488  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-02 19:08:19.488  4850  4850 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-02 19:08:19.488  4850  4850 I NearbySettings: MountReceiver.onReceive - Keep current state
09-02 19:08:19.488  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-02 19:08:19.488  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 26 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,09-02 19:08:19.488  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-02 19:08:19.488  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-02 19:08:19.488  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:19.488  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-02 19:08:19.488  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.488  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.488  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.488  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:19.498  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:19.498  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:19.498  1019  1338 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-02 19:08:19.508  1019  1488 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-02 19:08:19.508  1019  1488 D SecContentProvider2: mCursor = null
,09-02 19:08:19.508  1019  4260 D SecContentProvider2: uri = 15 selection = getToastGravity
09-02 19:08:19.508  1019  4260 D SecContentProvider2: mCursor = null
,09-02 19:08:19.508  1019  1497 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-02 19:08:19.508  1019  1497 D SecContentProvider2: mCursor = null
,09-02 19:08:19.508  1019  1032 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-02 19:08:19.508  1019  1032 D SecContentProvider2: mCursor = null
,09-02 19:08:19.508  1019  4273 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-02 19:08:19.508  1019  4273 D SecContentProvider2: mCursor = null
,09-02 19:08:19.508  1019  1494 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-02 19:08:19.508  1019  1494 D SecContentProvider2: mCursor = null
,09-02 19:08:19.538   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-02 19:08:19.538  1019  1338 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
,09-02 19:08:19.548  1178  1178 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-02 19:08:19.558  7226  7226 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-02 19:08:19.558  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 19:08:19.558  7226  7279 I jxcore-log: 
,09-02 19:08:19.568  7932  7932 D AndroidRuntime: 
09-02 19:08:19.568  7932  7932 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-02 19:08:19.568  7932  7932 D AndroidRuntime: CheckJNI is OFF,
09-02 19:08:19.578  7932  7932 D AndroidRuntime: readGMSProperty: start
09-02 19:08:19.578  7932  7932 D AndroidRuntime: readGMSProperty: already setted!!
,09-02 19:08:19.578  7932  7932 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-02 19:08:19.578  7932  7932 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-02 19:08:19.578  7932  7932 D AndroidRuntime: readGMSProperty: end
,09-02 19:08:19.578  7932  7932 D AndroidRuntime: addProductProperty: start
,09-02 19:08:19.598  1019  7897 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-02 19:08:19.668  1019  7897 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 02 Sep 2016 17:08:19 GMT], X-Android-Received-Millis=[1472836099675], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472836099642]}
09-02 19:08:19.668  1019  7897 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-02 19:08:19.668  1019  7897 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-02 19:08:19.668  1019  1129 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-02 19:08:19.668  1019  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,09-02 19:08:19.668  1019  1129 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-02 19:08:19.668  1178  1726 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-02 19:08:19.668  1019  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-02 19:08:19.668  1019  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-02 19:08:19.668  1178  1178 D StatusBar.NetworkController: EthernetConnected: false,
,09-02 19:08:19.668  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0,
,09-02 19:08:19.668  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,09-02 19:08:19.668  1178  1178 D StatusBar.NetworkController: updateDataNetType(),
09-02 19:08:19.668  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-02 19:08:19.668  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-02 19:08:19.678  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-02 19:08:19.678  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 26 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte,
09-02 19:08:19.678  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-02 19:08:19.678  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-02 19:08:19.678  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-02 19:08:19.678  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-02 19:08:19.678  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.678  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-02 19:08:19.678  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-02 19:08:19.678  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-02 19:08:19.698  7932  7932 E AffinityControl: AffinityControl: registerfunction enter,
,09-02 19:08:19.708  7226  7226 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 19:08:19.708  7226  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 19:08:19.708  7226  7279 I jxcore-log: 
,09-02 19:08:19.718  7932  7932 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-02 19:08:19.738  1019  1367 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-02 19:08:19.738  1019  1367 D PackageManager: START PACKAGE DELETE: observer{139593006}
09-02 19:08:19.738  1019  1367 D PackageManager: pkg{<packageName>}
09-02 19:08:19.738  1019  1367 D PackageManager: user{0}
09-02 19:08:19.738  1019  1367 D PackageManager: caller{2000}
09-02 19:08:19.738  1019  1367 D PackageManager: flags{2}
09-02 19:08:19.738  1019  1367 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-02 19:08:19.738  1019  1367 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
,09-02 19:08:19.738  1019  1367 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-02 19:08:19.738  1019  1367 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-02 19:08:19.738  1019  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-02 19:08:19.738  1019  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,09-02 19:08:19.748  1019  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-02 19:08:19.748  1019  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
09-02 19:08:19.748  1019  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-02 19:08:19.748  1019  1058 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,09-02 19:08:19.788  1019  1044 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
09-02 19:08:19.788  1019  1044 I ActivityManager: Killing 7226:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-02 19:08:19.868  1019  1044 I ActivityManager:   Force finishing activity ActivityRecord{1e524414 u0 com.test.thalitest/.MainActivity t164}
,09-02 19:08:19.878  1019  1044 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-02 19:08:19.888  1019  1044 D InputDispatcher: Focus left window: 7226
,09-02 19:08:19.888   258  1888 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,09-02 19:08:19.888   258   797 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,09-02 19:08:19.888  1019  1044 D InputDispatcher: Focused application released
,09-02 19:08:19.888  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-02 19:08:19.888  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-02 19:08:19.898  1019  1058 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,09-02 19:08:19.898  1019  1136 W WindowManager: Failed looking up window
09-02 19:08:19.898  1019  1136 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@225b9c47 does not exist
09-02 19:08:19.898  1019  1136 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11074)
09-02 19:08:19.898  1019  1136 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11065)
09-02 19:08:19.898  1019  1136 W WindowManager: 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1644)
09-02 19:08:19.898  1019  1136 W WindowManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
,09-02 19:08:19.898  1019  1136 I WindowState: WIN DEATH: null
,09-02 19:08:19.908  1019  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-02 19:08:19.938  1019  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-02 19:08:19.948  2830  2830 I art     : Explicit concurrent mark sweep GC freed 16602(991KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 853us total 40.196ms
,09-02 19:08:19.948  1869  1869 E SamsungIME: mOCRHelper is null
,09-02 19:08:19.968  1758  2019 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-02 19:08:19.978  1019  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 19:08:19.988  2814  2814 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 02 19:08:19 GMT+02:00 2016
,09-02 19:08:19.988  1436  1436 D PersonaManager: isKioskContainerExistOnDevice
,09-02 19:08:19.998  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,09-02 19:08:19.998  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-02 19:08:19.998  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,09-02 19:08:20.008  1019  1019 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-02 19:08:20.008  1019  1019 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,09-02 19:08:20.008  1019  1124 V NetworkStats: removeUidsLocked() for UIDs [10170]
,09-02 19:08:20.008  1019  1124 V NetworkStats: performPollLocked(flags=0x3)
09-02 19:08:20.008  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:20.018  1436  1436 D RegisteredServicesCache: empty dynamic service
,09-02 19:08:20.018  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-02 19:08:20.018  1019  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-02 19:08:20.028  1019  1124 V NetworkStats: performPollLocked() took 15ms
09-02 19:08:20.028  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:20.038  1019  1367 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-02 19:08:20.038  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-02 19:08:20.038  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:20.038  1019  1367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-02 19:08:20.038  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-02 19:08:20.048  1019  1485 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-02 19:08:20.048  1019  1485 D SecContentProvider2: mCursor = null
,09-02 19:08:20.048  1019  1019 I OTPFW   : ProvisionData::getAllEntries Enter
,09-02 19:08:20.058  2814  2814 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-02 19:08:20.058  1019  1019 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-02 19:08:20.058  1019  4259 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
09-02 19:08:20.058  1019  4259 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-02 19:08:20.058  1019  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
09-02 19:08:20.058  1019  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-02 19:08:20.058  1019  1043 W TextServicesManagerService: no available spell checker services found
,09-02 19:08:20.058  1019  4259 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-02 19:08:20.068  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.068  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.068  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.068  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:20.078  2814  2814 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-02 19:08:20.078  2814  2814 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-02 19:08:20.078  1019  4259 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7950 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,09-02 19:08:20.088  7950  7950 E Zygote  : MountEmulatedStorage(),
09-02 19:08:20.088  7950  7950 I libpersona: KNOX_SDCARD checking this for 10090
,09-02 19:08:20.088  7950  7950 E Zygote  : v2
09-02 19:08:20.088  7950  7950 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:20.088  7950  7950 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 19:08:20.088  7950  7950 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 19:08:20.088  7950  7950 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:20.098  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:20.098  2814  2814 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-02 19:08:20.098  2814  7949 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-02 19:08:20.108  1436  1436 D RegisteredComponentCache: Collect Tech packages for Knox
,09-02 19:08:20.108  1436  1436 D PersonaManager: isKioskContainerExistOnDevice
,09-02 19:08:20.118  7950  7950 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:20.118  7950  7950 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:20.128  2814  7949 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,09-02 19:08:20.138  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-02 19:08:20.138  1019  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-02 19:08:20.138  2814  7949 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,09-02 19:08:20.138  2814  7949 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-02 19:08:20.158  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:20.168  1019  1044 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-02 19:08:20.178  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.178  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.178  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.178  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:20.188  7965  7965 E Zygote  : MountEmulatedStorage()
09-02 19:08:20.188  7965  7965 E Zygote  : v2
09-02 19:08:20.188  7965  7965 I libpersona: KNOX_SDCARD checking this for 10052
09-02 19:08:20.188  7965  7965 I libpersona: KNOX_SDCARD not a persona
09-02 19:08:20.188  7965  7965 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 19:08:20.188  1019  1044 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7965 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
09-02 19:08:20.188  7965  7965 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 19:08:20.198  7965  7965 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-02 19:08:20.198  1019  1044 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,09-02 19:08:20.198  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:20.198  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.198  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.198  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:20.208  1019  1058 I art     : Explicit concurrent mark sweep GC freed 68165(4MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 3.590ms total 221.396ms
09-02 19:08:20.208  1019  1029 I art     : WaitForGcToComplete blocked for 160.512ms for cause HeapTrim
,09-02 19:08:20.218  7979  7979 E Zygote  : MountEmulatedStorage()
09-02 19:08:20.218  7979  7979 E Zygote  : v2
09-02 19:08:20.218  7979  7979 I libpersona: KNOX_SDCARD checking this for 10098
09-02 19:08:20.218  7979  7979 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:20.218  7979  7979 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 19:08:20.218  1019  1044 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7979 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-02 19:08:20.218  7979  7979 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 19:08:20.218  7950  7950 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
09-02 19:08:20.218  7979  7979 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:20.228  7950  7950 D elm:15121: ELMEngine.ELMEngine( context ).
09-02 19:08:20.228  1019  4259 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-02 19:08:20.228  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:20.238  7950  7950 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-02 19:08:20.238  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-02 19:08:20.238  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.238  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:20.238  1019  1058 D PackageManager: delete codoeFile: 
,09-02 19:08:20.248  7994  7994 E Zygote  : MountEmulatedStorage()
09-02 19:08:20.248  7994  7994 E Zygote  : v2
09-02 19:08:20.248  7994  7994 I libpersona: KNOX_SDCARD checking this for 10032
09-02 19:08:20.248  7994  7994 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:20.248  7994  7994 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 19:08:20.258  7965  7965 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:20.258  7994  7994 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 19:08:20.258  7965  7965 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:20.258  7994  7994 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-02 19:08:20.258  1019  1058 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,09-02 19:08:20.258  1019  1058 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,09-02 19:08:20.258  1019  1058 D PackageManager: result of delete: 1{139593006}
,09-02 19:08:20.268  1019  4259 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7994 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-02 19:08:20.268  1019  4273 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-02 19:08:20.268  1019  4273 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-02 19:08:20.268  7979  7979 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 19:08:20.268  1019  4273 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:20.268  1019  4273 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:20.268  1019  4273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-02 19:08:20.278  7979  7979 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:20.278  7950  7950 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-02 19:08:20.278  7950  7950 D elm:15121: ElmAgentService : onCreate()
,09-02 19:08:20.288  7950  8008 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
09-02 19:08:20.288  7950  8008 D elm:15121: MainReceiver.listeningToPackageRemoved()
09-02 19:08:20.288  7950  8008 D elm:15121: MDMBridge.getInstance()
09-02 19:08:20.288  7950  8008 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-02 19:08:20.288  7932  7932 D AndroidRuntime: Shutting down VM
,09-02 19:08:20.288  7994  7994 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:20.288  7950  8008 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-02 19:08:20.288  7994  7994 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:20.288  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:20.318  7950  7950 D elm:15121: ElmAgentService : onDestroy().
,09-02 19:08:20.318  1019  4259 I ActivityManager: Killing 7459:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-02 19:08:20.318  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:20.328  2814  7949 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-02 19:08:20.328  1019  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-02 19:08:20.328  1019  1058 D PackageManager: userId{-1}
09-02 19:08:20.328  1019  1058 D PackageManager: andCode{true}
,09-02 19:08:20.338  1019  4259 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,09-02 19:08:20.338  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-02 19:08:20.338  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-02 19:08:20.338  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-02 19:08:20.338  1019  1019 V EnterpriseBillingPolicy: uID is 10170
09-02 19:08:20.338  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
09-02 19:08:20.338  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-02 19:08:20.338  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.338  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.338  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.338  1019  4259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:20.338  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-02 19:08:20.338  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-02 19:08:20.338  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,09-02 19:08:20.338  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-02 19:08:20.348  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-02 19:08:20.348  2814  7949 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-02 19:08:20.348  2814  7949 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,09-02 19:08:20.358  8013  8013 E Zygote  : MountEmulatedStorage()
09-02 19:08:20.358  8013  8013 E Zygote  : v2
09-02 19:08:20.358  8013  8013 I libpersona: KNOX_SDCARD checking this for 1000
09-02 19:08:20.358  8013  8013 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:20.358  8013  8013 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-02 19:08:20.358  8013  8013 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 19:08:20.358  1019  4259 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=8013 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-02 19:08:20.358  1019  4259 I ActivityManager: Killing 7476:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,09-02 19:08:20.358  8013  8013 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-02 19:08:20.358  1019  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-02 19:08:20.378  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:20.378  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.378  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:20.378  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:20.388  8028  8028 E Zygote  : MountEmulatedStorage(),
09-02 19:08:20.388  8028  8028 E Zygote  : v2
09-02 19:08:20.388  8028  8028 I libpersona: KNOX_SDCARD checking this for 10003
09-02 19:08:20.388  8028  8028 I libpersona: KNOX_SDCARD not a persona
09-02 19:08:20.388  8028  8028 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 19:08:20.388  1019  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8028 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-02 19:08:20.388  8028  8028 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 19:08:20.388  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-02 19:08:20.398  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-02 19:08:20.398  1019  3325 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-02 19:08:20.398  1019  1019 V EnterpriseBillingPolicy: uID is 10170
09-02 19:08:20.398  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
09-02 19:08:20.398  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-02 19:08:20.398  8028  8028 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-02 19:08:20.398  1019  1019 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
09-02 19:08:20.398  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-02 19:08:20.398  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null,
09-02 19:08:20.398  1019  1163 D TaskPersister: removeObsoleteFile: deleting file=164_task.xml
09-02 19:08:20.398  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-02 19:08:20.398  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-02 19:08:20.398  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null,
09-02 19:08:20.398  1019  4260 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,09-02 19:08:20.408  1019  4260 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-02 19:08:20.408  1019  4260 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:20.408  1019  4260 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:20.408  1019  4260 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-02 19:08:20.408  2814  2814 I KLMS-2.5.123: : KLMSIntentService(): onDestroy(),
,09-02 19:08:20.418  8013  8013 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:20.418  8013  8013 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:20.428  8028  8028 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:20.428  8028  8028 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:20.448  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-02 19:08:20.458  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:20.468  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:20.468  1019  1367 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-02 19:08:20.468  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-02 19:08:20.468  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:20.478  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:20.478  1019  1367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-02 19:08:20.478  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-02 19:08:20.478  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-02 19:08:20.478  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:08:20.478  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-02 19:08:20.478  1019  1488 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-02 19:08:20.478  1019  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-02 19:08:20.488  1019  1129 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-02 19:08:20.488  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:20.488  1019  1488 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:20.488  1019  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:20.488  1019  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-02 19:08:20.498  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-02 19:08:20.498  7994  8044 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-02 19:08:20.498  7994  8044 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version,
,09-02 19:08:20.498  7932  7932 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
09-02 19:08:20.498  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-02 19:08:20.498  7785  7785 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.,
,09-02 19:08:20.508  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-02 19:08:20.508  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-02 19:08:20.508  1019  1497 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,09-02 19:08:20.508  1019  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:20.508  1019  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.508  1019  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.508  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-02 19:08:20.508  1019  1497 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.518  7994  8044 D SPPClientService: PushLog.txt file is not deleted.
09-02 19:08:20.518  7994  8044 D SPPClientService: PushLog.txt file is not deleted.
09-02 19:08:20.518  7994  8044 D SPPClientService: ============PushLog. stop!
09-02 19:08:20.518  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-02 19:08:20.518  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-02 19:08:20.518  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-02 19:08:20.518  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-02 19:08:20.518  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-02 19:08:20.528  8048  8048 E Zygote  : MountEmulatedStorage()
09-02 19:08:20.528  8048  8048 E Zygote  : v2
09-02 19:08:20.528  8048  8048 I libpersona: KNOX_SDCARD checking this for 1000
09-02 19:08:20.528  8048  8048 I libpersona: KNOX_SDCARD not a persona
09-02 19:08:20.528  8048  8048 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 19:08:20.528  1019  1497 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=8048 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-02 19:08:20.528  1019  1497 I ActivityManager: Killing 7491:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
09-02 19:08:20.538  8048  8048 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 19:08:20.538  1019  1497 I ActivityManager: Killing 7509:com.sec.android.soagent/u0a31 (adj 15): empty #21
09-02 19:08:20.538  8048  8048 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-02 19:08:20.538  1019  1485 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
09-02 19:08:20.548  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.548  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.548  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.548  1019  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.548  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
09-02 19:08:20.548  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
09-02 19:08:20.548  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
09-02 19:08:20.548  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-02 19:08:20.548  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-02 19:08:20.548  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-02 19:08:20.548  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-02 19:08:20.548  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
09-02 19:08:20.548  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
09-02 19:08:20.548  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
09-02 19:08:20.548  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
09-02 19:08:20.548  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-02 19:08:20.548  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-02 19:08:20.558  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-02 19:08:20.558  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
09-02 19:08:20.558  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
09-02 19:08:20.558  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,09-02 19:08:20.558  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false,
09-02 19:08:20.558  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
09-02 19:08:20.558  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
09-02 19:08:20.558  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
09-02 19:08:20.558  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
09-02 19:08:20.558  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
09-02 19:08:20.558  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,09-02 19:08:20.558  8061  8061 E Zygote  : MountEmulatedStorage(),
09-02 19:08:20.558  8061  8061 E Zygote  : v2
09-02 19:08:20.558  8061  8061 I libpersona: KNOX_SDCARD checking this for 1000
09-02 19:08:20.558  8061  8061 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:20.568  8061  8061 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-02 19:08:20.568  8061  8061 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-02 19:08:20.568  1019  1485 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8061 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-02 19:08:20.568  1019  1485 I ActivityManager: Killing 7542:com.osp.app.signin/u0a36 (adj 15): empty #21,
09-02 19:08:20.568  8061  8061 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-02 19:08:20.568  1019  1031 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
09-02 19:08:20.568  1019  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
09-02 19:08:20.568  1019  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-02 19:08:20.568  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
09-02 19:08:20.568  1019  1043 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
09-02 19:08:20.578  8048  8048 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-02 19:08:20.578  8048  8048 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:20.578  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-02 19:08:20.578  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:20.578  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,09-02 19:08:20.588  8061  8061 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 19:08:20.588  8061  8061 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:20.598  7785  7785 D BluetoothAdapter: cancelDiscovery
,09-02 19:08:20.608  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-02 19:08:20.608  3188  7325 D BluetoothAdapterProperties: mDiscovering is false
,09-02 19:08:20.608  3188  7325 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
09-02 19:08:20.608  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.608  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.608  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-02 19:08:20.608  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-02 19:08:20.608  7785  7785 D BluetoothAdapter: cancelDiscovery = true
,09-02 19:08:20.608  7785  7785 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,09-02 19:08:20.628  8080  8080 E Zygote  : MountEmulatedStorage()
09-02 19:08:20.628  8080  8080 E Zygote  : v2
09-02 19:08:20.628  8080  8080 I libpersona: KNOX_SDCARD checking this for 10039
09-02 19:08:20.628  8080  8080 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-02 19:08:20.628  8080  8080 I libpersona: KNOX_SDCARD not a persona
,09-02 19:08:20.628  1019  1031 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=8080 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-02 19:08:20.628  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-02 19:08:20.628  1019  4273 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
09-02 19:08:20.628  7785  7785 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-02 19:08:20.628  7785  7785 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,09-02 19:08:20.628  7785  7785 E SQLiteLog: (3850) statement aborts at 17: [INSERT INTO dump_log(timestamp,message) VALUES (?,?)] disk I/O error
,09-02 19:08:20.628  7785  7785 E SQLiteDatabase: Error inserting timestamp=1472836100619 message=Predictor: service stopped by removePlaceCategories()
09-02 19:08:20.628  7785  7785 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 19:08:20.628  7785  7785 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-02 19:08:20.628  7785  7785 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
09-02 19:08:20.628  7785  7785 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-02 19:08:20.628  7785  7785 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-02 19:08:20.628  7785  7785 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-02 19:08:20.628  7785  7785 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-02 19:08:20.628  7785  7785 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
09-02 19:08:20.628  7785  7785 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
09-02 19:08:20.628  7785  7785 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 19:08:20.628  7785  7785 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 19:08:20.628  7785  7785 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:08:20.628  7785  7785 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:08:20.628  7785  7785 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:08:20.628  7785  7785 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:08:20.628  7785  7785 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:08:20.628  7785  7785 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:08:20.628  7785  7785 E UserAnalysis: It failed to insert to dump_log table
09-02 19:08:20.638  8080  8080 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-02 19:08:20.638  8080  8080 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-02 19:08:20.648  8048  8048 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-02 19:08:20.648  1019  1485 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
09-02 19:08:20.648  1019  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,09-02 19:08:20.648   315   315 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 617us total 25.732ms
,09-02 19:08:20.658  1019  1485 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:20.658  1019  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-02 19:08:20.658  1019  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,09-02 19:08:20.668  8080  8080 D TimaKeyStoreProvider: TimaSignature is unavailable
09-02 19:08:20.668  8080  8080 D ActivityThread: Added TimaKeyStore provider
,09-02 19:08:20.668   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 625us total 17.340ms
,09-02 19:08:20.688  1636  1636 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/ns.db" with flag (131138) and mode_t (0) due to error (30)
,09-02 19:08:20.688   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 16.895ms
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/ns.db'.
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:262)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:176)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:08:20.688  1636  1636 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-02 19:08:20.688  1636  1636 D AndroidRuntime: Shutting down VM
,09-02 19:08:20.688  1636  1636 E AndroidRuntime: FATAL EXCEPTION: main
09-02 19:08:20.688  1636  1636 E AndroidRuntime: Process: com.google.process.gapps, PID: 1636
09-02 19:08:20.688  1636  1636 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:262)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:176)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:08:20.688  1636  1636 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-02 19:08:20.698  1019  1367 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.process.gapps
,09-02 19:08:20.698  8080  8080 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-02 19:08:20.698  8080  8080 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-02 19:08:20.698  8080  8080 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-02 19:08:20.698  8080  8080 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-02 19:08:20.698  8080  8080 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-02 19:08:20.698  8080  8080 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-02 19:08:20.698  8080  8080 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-02 19:08:20.698  8048  8048 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db" with flag (131138) and mode_t (0) due to error (30)
,09-02 19:08:20.698  8048  8048 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/lowpowercontext-system-db'.
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2443)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(DataStore.java:85)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextProvider.onCreate(LowpowerContextProvider.java:303)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:08:20.698  8048  8048 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-02 19:08:20.708  8048  8048 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/sm.db" with flag (131138) and mode_t (0) due to error (30)
,09-02 19:08:20.708  8048  8048 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/sm.db'.
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at com.samsung.android.sm.database.b.<init>(SmDatabaseHelper.java:65)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at com.samsung.android.sm.database.b.a(SmDatabaseHelper.java:54)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at com.samsung.android.sm.database.SmProvider.onCreate(SmProvider.java:89)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:08:20.708  8048  8048 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:08:20.708  8048  8048 D AndroidRuntime: Shutting down VM
,09-02 19:08:20.708  8048  8048 E AndroidRuntime: FATAL EXCEPTION: main
09-02 19:08:20.708  8048  8048 E AndroidRuntime: Process: com.samsung.android.sm, PID: 8048
09-02 19:08:20.708  8048  8048 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.sm.database.SmProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at com.samsung.android.sm.database.b.<init>(SmDatabaseHelper.java:65)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at com.samsung.android.sm.database.b.a(SmDatabaseHelper.java:54)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at com.samsung.android.sm.database.SmProvider.onCreate(SmProvider.java:89)
09-02 19:08:20.708  8048  8048 E ,AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-02 19:08:20.708  8048  8048 E AndroidRuntime: 	... 11 more
,09-02 19:08:20.718  1636  1636 I Process : Sending signal. PID: 1636 SIG: 9
,09-02 19:08:20.718  1019  1505 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
,09-02 19:08:20.718  1019  8095 E DropBoxManagerService: Can't write: system_app_crash
09-02 19:08:20.718  1019  8095 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop192.tmp: open failed: EROFS (Read-only file system)
09-02 19:08:20.718  1019  8095 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-02 19:08:20.718  1019  8095 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 19:08:20.718  1019  8095 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 19:08:20.718  1019  8095 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 19:08:20.718  1019  8095 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-02 19:08:20.718  1019  8095 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
09-02 19:08:20.718  1019  8095 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 19:08:20.718  1019  8095 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 19:08:20.718  1019  8095 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 19:08:20.718  1019  8095 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-02 19:08:20.718  1019  8095 E DropBoxManagerService: 	... 5 more
,09-02 19:08:20.718  1019  8097 E DropBoxManagerService: Can't write: system_app_crash
09-02 19:08:20.718  1019  8097 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop193.tmp: open failed: EROFS (Read-only file system)
09-02 19:08:20.718  1019  8097 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-02 19:08:20.718  1019  8097 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 19:08:20.718  1019  8097 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 19:08:20.718  1019  8097 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 19:08:20.718  1019  8097 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-02 19:08:20.718  1019  8097 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
09-02 19:08:20.718  1019  8097 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 19:08:20.718  1019  8097 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 19:08:20.718  1019  8097 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 19:08:20.718  1019  8097 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-02 19:08:20.718  1019  8097 E DropBoxManagerService: 	... 5 more
,09-02 19:08:20.728  8061  8061 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
09-02 19:08:20.728  1019  1031 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
09-02 19:08:20.728  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
09-02 19:08:20.728  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-02 19:08:20.728  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-02 19:08:20.728  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
09-02 19:08:20.728  1019  1136 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
09-02 19:08:20.728  8048  8048 I Process : Sending signal. PID: 8048 SIG: 9
09-02 19:08:20.738  1019  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
