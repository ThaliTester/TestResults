#### Test 83268893665f77c_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main,
09-06 16:55:26.681   292   292 E SMD     : DCD OFF
09-06 16:55:26.961  6836  6836 D AndroidRuntime: 
09-06 16:55:26.961  6836  6836 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-06 16:55:26.961  6836  6836 D AndroidRuntime: CheckJNI is OFF
09-06 16:55:26.961  6836  6836 D AndroidRuntime: readGMSProperty: start
09-06 16:55:26.961  6836  6836 D AndroidRuntime: readGMSProperty: already setted!!
09-06 16:55:26.961  6836  6836 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-06 16:55:26.961  6836  6836 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-06 16:55:26.961  6836  6836 D AndroidRuntime: readGMSProperty: end
09-06 16:55:26.961  6836  6836 D AndroidRuntime: addProductProperty: start
09-06 16:55:27.111  6836  6836 E AffinityControl: AffinityControl: registerfunction enter
09-06 16:55:27.141  6836  6836 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-06 16:55:27.161  1015  1452 E PersonaManagerService: inState():  stateMachine is null !!
09-06 16:55:27.161  1015  1452 I PersonaManagerService: PersonaId don't exist
09-06 16:55:27.161  1015  1452 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-06 16:55:27.161  1015  1452 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
09-06 16:55:27.191  1015  1452 W ActivityManager: mDVFSHelper.acquire()
09-06 16:55:27.201   257   257 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-06 16:55:27.201   257   257 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
09-06 16:55:27.211  1015  1452 D FocusedStackFrame: Set to : 0
09-06 16:55:27.221  1015  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-06 16:55:27.221  1015  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-06 16:55:27.221  1015  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:27.221  1015  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:27.221  1015  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:27.221  1015  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:27.231  6847  6847 E Zygote  : MountEmulatedStorage()
09-06 16:55:27.231  6847  6847 E Zygote  : v2
09-06 16:55:27.231  6847  6847 I libpersona: KNOX_SDCARD checking this for 10171
09-06 16:55:27.231  6847  6847 I libpersona: KNOX_SDCARD not a persona
09-06 16:55:27.231  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-06 16:55:27.231  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-06 16:55:27.231  1015  1452 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6847 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-06 16:55:27.231  1015  1452 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-06 16:55:27.231  1015  1452 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 16:55:27.241  6847  6847 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 16:55:27.241   257   257 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
09-06 16:55:27.241  6847  6847 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 16:55:27.241  6847  6847 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-06 16:55:27.241  1015  1452 D InputDispatcher: Focused application set to: xxxx
09-06 16:55:27.241  1015  1452 D InputDispatcher: Focus left window: 1497
09-06 16:55:27.241  6836  6836 D AndroidRuntime: Shutting down VM
09-06 16:55:27.251  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 16:55:27.251  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-06 16:55:27.261  6847  6847 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 16:55:27.261  6847  6847 D ActivityThread: Added TimaKeyStore provider
09-06 16:55:27.271  1015  1211 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-06 16:55:27.271  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-06 16:55:27.281  1015  1015 V ActivityManager: Display changed displayId=0
09-06 16:55:27.291  1015  1211 D PersonaManager: isKioskContainerExistOnDevice
09-06 16:55:27.301  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-06 16:55:27.331   257  1095 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
09-06 16:55:27.331   257   441 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
09-06 16:55:27.331  1497  1497 V ActivityThread: updateVisibility : ActivityRecord{3bac45c token=android.os.BinderProxy@9905841 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-06 16:55:27.341  1497  1497 D Launcher: onTrimMemory. Level: 20
09-06 16:55:27.421  6847  6847 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-06 16:55:27.451  6836  6836 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-06 16:55:27.461  6847  6847 I cr.library_loader: Time to load native libraries: 13 ms (timestamps 7711-7724)
09-06 16:55:27.461  6847  6847 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-06 16:55:27.481  6847  6847 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c678c82}
09-06 16:55:27.481  6847  6847 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-06 16:55:27.491  6847  6847 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 16:55:27.521  6847  6847 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
09-06 16:55:27.531  6847  6847 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 16:55:27.541  6847  6847 E SysUtils: ApplicationContext is null in ApplicationStatus
09-06 16:55:27.581  6847  6847 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 16:55:27.581  6847  6847 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 16:55:27.581  6847  6847 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 16:55:27.581  6847  6847 I Adreno-EGL: Local Branch: 
09-06 16:55:27.581  6847  6847 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 16:55:27.581  6847  6847 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 16:55:27.581  6847  6847 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
09-06 16:55:27.681  6847  6847 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-06 16:55:27.711  6847  6847 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-06 16:55:27.711  6847  6847 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-06 16:55:27.721  6847  6847 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-06 16:55:27.721  6847  6847 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-06 16:55:27.801  1015  1040 W ActivityManager: Activity pause timeout for ActivityRecord{23612713 u0 com.test.thalitest/.MainActivity t2}
09-06 16:55:27.831  6847  6847 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 16:55:27.841  6847  6847 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-06 16:55:27.851  6847  6847 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-06 16:55:27.851  6847  6847 D PhoneWindow: *FMB* installDecor flags : -2139027200
09-06 16:55:27.861  6847  6847 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-06 16:55:27.871  6847  6847 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 16:55:27.871  6847  6847 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 16:55:27.881  1015  1325 E Watchdog: !@Sync 3
09-06 16:55:27.981  6847  6888 D OpenGLRenderer: Render dirty regions requested: true
09-06 16:55:27.981  1015  1213 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-06 16:55:27.981  1015  1213 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 16:55:27.981  1015  1213 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-06 16:55:27.991  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-06 16:55:27.991  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
09-06 16:55:27.991  6847  6875 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
09-06 16:55:28.001  6847  6847 V ActivityThread: updateVisibility : ActivityRecord{20af73e2 token=android.os.BinderProxy@1dbc90d7 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-06 16:55:28.001  6847  6847 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-06 16:55:28.001  6847  6847 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-06 16:55:28.011   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
09-06 16:55:28.031  1015  4377 D InputDispatcher: Focus entered window: 6847
09-06 16:55:28.031  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 16:55:28.031  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-06 16:55:28.031  6847  6847 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-06 16:55:28.031  6847  6888 I OpenGLRenderer: Initialized EGL, version 1.4
09-06 16:55:28.041  6847  6888 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-06 16:55:28.041  6847  6888 D OpenGLRenderer: Enabling debug mode 0
09-06 16:55:28.061  1015  1211 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-06 16:55:28.071  1169  1169 I StatusBar: Icon Only
09-06 16:55:28.071  1169  1169 D PanelView: There is/are notification(s) 
09-06 16:55:28.081  1015  1045 I ActivityManager: Displayed Component not be shown by security: +781ms (total +863ms)
09-06 16:55:28.081  1015  1045 W ActivityManager: mDVFSHelper.release()
09-06 16:55:28.081  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{23612713 u0 com.test.thalitest/.MainActivity t2} time:108345
09-06 16:55:28.081  6847  6847 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-06 16:55:28.081  6847  6847 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1dbc90d7 time:108346
09-06 16:55:28.091   257   441 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
09-06 16:55:28.091  1015  6892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-06 16:55:28.091   257  1990 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
09-06 16:55:28.101  1870  1870 I SamsungIME: getCurrentCandidateView
09-06 16:55:28.191  6847  6847 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6847
,09-06 16:55:28.221  1870  1870 D SamsungIME: Dismiss ExpandCandiate
,09-06 16:55:28.381  1870  1870 I SamsungIME: getDebugLevel  : 0x4f4c
,09-06 16:55:28.421  1870  1870 I SamsungIME: getDebugLevel  : 0x4f4c
,09-06 16:55:28.441  1870  1870 I SamsungIME: KeybaordView init() : load resources
,09-06 16:55:28.461  6847  6847 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-06 16:55:28.461  1870  1870 I SamsungIME: getCurrentKeyboard
,09-06 16:55:28.461  1870  1870 I SamsungIME: getTextKeyboard
,09-06 16:55:28.481  1870  1870 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-06 16:55:28.551  6847  6894 D jxcore_app_log: JniHelper::setJavaVM(0xb735b2b0), pthread_self() = -1215406696
,09-06 16:55:28.561  6847  6894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 16:55:28.561  6847  6894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 16:55:28.561  6847  6894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 16:55:28.561  6847  6894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 16:55:28.561  6847  6894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-06 16:55:28.561  6847  6894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36047748 added. We now have 1 listener(s)
,09-06 16:55:28.561  6847  6894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,09-06 16:55:28.561  6847  6894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 16:55:28.571  6847  6894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 16:55:28.571  6847  6894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:55:28.571  6847  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 16:55:28.571  6847  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 16:55:28.571  6847  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 16:55:28.571  6847  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
09-06 16:55:28.571  6847  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 16:55:28.571  6847  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 16:55:28.571  6847  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 16:55:28.571  6847  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 16:55:28.571  6847  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 16:55:28.571  6847  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 16:55:28.571  6847  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 16:55:28.571  6847  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 16:55:28.571  6847  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1,
09-06 16:55:28.571  6847  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-06 16:55:28.571  6847  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ded5dc7 added. We now have 1 listener(s)
09-06 16:55:28.571  6847  6894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:55:28.581  6847  6894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
09-06 16:55:28.581  6847  6894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413,
09-06 16:55:28.581  6847  6894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2,
09-06 16:55:28.581  6847  6894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 16:55:28.581  6847  6894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-06 16:55:28.581  6847  6894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:55:28.581  6847  6894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27,
,09-06 16:55:28.591  6847  6894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage,
09-06 16:55:28.591  6847  6894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:28.591  6847  6894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:28.591  6847  6894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:28.591  6847  6894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:28.591  6847  6894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:28.591  6847  6894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:28.591  6847  6894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:28.591  6847  6894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:55:28.591  6847  6894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 16:55:28.591  6847  6894 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:55:28.591  6847  6894 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 16:55:28.591  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-06 16:55:28.601  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:28.621  6847  6847 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 16:55:29.161  6847  6901 W jxcore-log: Initializing JXcore engine
09-06 16:55:29.161  6847  6901 W jxcore-log: JXcore engine is ready
,09-06 16:55:29.211  1994  1994 E audit   : type=1400 msg=audit(1473173729.211:205): avc:  denied  { ioctl } for  pid=6901 comm="Thread-1255" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2079 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-06 16:55:29.221  1994  1994 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-06 16:55:29.221  1994  1994 E audit   : type=1300 msg=audit(1473173729.211:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f9368f8 items=0 ppid=321 ppcomm=main pid=6901 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1255" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-06 16:55:29.221  1994  1994 E audit   : type=1320 msg=audit(1473173729.211:205): 
,09-06 16:55:29.231  6847  6901 W jxcore-log: Starting JXcore engine
,09-06 16:55:29.331  6847  6901 W jxcore-log: Platform android
09-06 16:55:29.331  6847  6901 W jxcore-log: 
09-06 16:55:29.331  6847  6901 W jxcore-log: Process ARCH arm
09-06 16:55:29.331  6847  6901 W jxcore-log: 
,09-06 16:55:29.391   332   332 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-06 16:55:29.391   332   332 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-06 16:55:29.541  6847  6901 I jxcore-log: JXcore Cordova bridge is ready!,
09-06 16:55:29.541  6847  6901 I jxcore-log: 
09-06 16:55:29.541  6847  6901 W jxcore-log: JXcore engine is started
,09-06 16:55:29.541  6847  6894 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 16:55:29.541  6847  6847 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,09-06 16:55:29.671   292   292 E SMD     : DCD OFF
,09-06 16:55:29.861  1015  1496 I art     : Explicit concurrent mark sweep GC freed 35590(1826KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 24MB/36MB, paused 2.537ms total 143.837ms
,09-06 16:55:32.221  1015  1047 I PowerManagerService: [PWL] Off : 50s ago
,09-06 16:55:32.321  1015  3370 D SSRM:n  : SIOP:: AP = 310
,09-06 16:55:32.671   292   292 E SMD     : DCD OFF
,09-06 16:55:34.391   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 16:55:35.391   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 16:55:35.521  5697  5697 D FactoryTest: Not factory mode
,09-06 16:55:35.521  5697  5697 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-06 16:55:35.531  5697  5697 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-06 16:55:35.531  5697  5697 D MTPRx   : still no open session command from host, so toast
,09-06 16:55:35.531  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
09-06 16:55:35.531  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-06 16:55:35.531  5697  5697 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115796
09-06 16:55:35.531  1015  4377 E PersonaManagerService: inState():  stateMachine is null !!
09-06 16:55:35.531  1015  4377 I PersonaManagerService: PersonaId don't exist
09-06 16:55:35.531  1015  4377 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-06 16:55:35.541  1015  4377 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-06 16:55:35.541  1015  4377 W ActivityManager: userId = 0, bbcId = -10000,
09-06 16:55:35.541  1015  4377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:35.541  1015  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-06 16:55:35.541  1015  4377 W ActivityManager: mDVFSHelper.acquire()
,09-06 16:55:35.561  1015  4377 D PersonaManager: isKioskContainerExistOnDevice
,09-06 16:55:35.561  1015  4377 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 16:55:35.561  1015  4377 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 16:55:35.561  1015  4377 D InputDispatcher: Focused application set to: xxxx
09-06 16:55:35.561  1015  4377 D InputDispatcher: Focus left window: 6847
,09-06 16:55:35.571  5697  5697 E MTPRx   : started activity for popup
,09-06 16:55:35.571  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 16:55:35.571  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 16:55:35.591  5697  5697 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-06 16:55:35.591  5697  5697 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-06 16:55:35.591  5697  5697 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-06 16:55:35.591  5697  5697 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 16:55:35.601  5697  5697 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 16:55:35.601  5697  5697 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 16:55:35.621  5697  5697 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-06 16:55:35.631  1015  1453 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 16:55:35.631  1015  1453 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 16:55:35.631  1015  1453 D InputDispatcher: Focused application set to: xxxx
,09-06 16:55:35.631  1015  1453 D InputDispatcher: Focus entered window: 6847
,09-06 16:55:35.641  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 16:55:35.641  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 16:55:35.641  1015  1213 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-06 16:55:35.641  1015  1213 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@38dfaf12 attribute=null, token = android.os.BinderProxy@3ed62962
,09-06 16:55:35.671   292   292 E SMD     : DCD OFF
,09-06 16:55:35.671  5697  5697 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-06 16:55:35.681  5697  5697 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-06 16:55:35.681  5697  5697 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-06 16:55:35.701  6847  6847 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-06 16:55:35.711  6847  6847 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-06 16:55:35.711  6847  6847 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-06 16:55:35.711  6847  6847 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-06 16:55:35.711  1015  1496 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-06 16:55:35.711  1015  1496 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 16:55:35.711  1015  1496 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-06 16:55:35.711  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-06 16:55:35.711  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,09-06 16:55:35.721  6847  6847 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 16:55:35.721  6847  6847 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-06 16:55:35.731  6847  6847 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@25d29383 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@1b778e8, 16908290=android.view.AbsSavedState$1@1b778e8}, android:focusedViewId=100}]}]
09-06 16:55:35.731  6847  6847 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-06 16:55:35.731  6847  6847 V ActivityThread: updateVisibility : ActivityRecord{20af73e2 token=android.os.BinderProxy@1dbc90d7 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-06 16:55:35.731  6847  6847 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 16:55:35.731  6847  6847 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-06 16:55:35.731  6847  6847 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1dbc90d7 time:115992
,09-06 16:55:35.741  1015  1495 D PersonaManager: isKioskContainerExistOnDevice
,09-06 16:55:35.971  1015  4041 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 16:55:35.971  1015  4041 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-06 16:55:35.971  1015  4041 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 16:55:35.971  1015  4041 D BatteryService: stay LED for fully charged
09-06 16:55:35.971  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 16:55:35.971  1015  1015 I MotionRecognitionService: Plugged
,09-06 16:55:35.971  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 16:55:35.971  1169  1169 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 16:55:35.971  1169  1169 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 16:55:35.981  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 16:55:35.981  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 16:55:35.991  3197  3197 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 16:55:35.991  3197  3310 D HeadsetStateMachine: Disconnected process message: 10
,09-06 16:55:35.991  1169  1169 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-06 16:55:35.991  1169  1169 D SViewCoverView: level :100 plugged : 2
,09-06 16:55:35.991  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 16:55:35.991  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 16:55:35.991  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 16:55:36.391   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 16:55:37.271  1015  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-06 16:55:37.391   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 16:55:38.391   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 16:55:38.551  1015  1040 W ActivityManager: mDVFSHelper.release()
,09-06 16:55:38.671   292   292 E SMD     : DCD OFF
,09-06 16:55:39.391   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-06 16:55:39.741  1015  1093 V AlarmManager: waitForAlarm result :4
,09-06 16:55:39.741  1015  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-06 16:55:39.841  4873  4873 D ConnectivityManager: CallingUid : 10011, CallingPid : 4873
,09-06 16:55:39.851  1015  1213 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 16:55:39.851  1015  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-06 16:55:39.851  1015  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
09-06 16:55:39.851  1015  1126 D ConnectivityService: apparently satisfied.  currentScore=60
,09-06 16:55:39.851  4873  6909 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-06 16:55:39.901  4873  6910 W DriveInitializer: Background init thread started
,09-06 16:55:39.931   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-06 16:55:39.931   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 16:55:39.931  4873  6910 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-06 16:55:39.991  4873  6910 W DriveInitializer: Background init thread ended
,09-06 16:55:41.681   292   292 E SMD     : DCD OFF,
,09-06 16:55:41.751  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
09-06 16:55:41.751  6847  6901 I jxcore-log: 
,09-06 16:55:41.751  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
09-06 16:55:41.751  6847  6901 I jxcore-log: 
,09-06 16:55:41.761  6847  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:41.761  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:41.761  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:41.761  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:41.761  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:41.761  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,09-06 16:55:41.761  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:41.761  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:55:41.761  6847  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,09-06 16:55:41.761  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 16:55:41.761  6847  6901 I jxcore-log: 
,09-06 16:55:41.761  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 16:55:41.761  6847  6901 I jxcore-log: 
,09-06 16:55:42.191  1015  3412 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-06 16:55:42.331  1015  3370 D SSRM:n  : SIOP:: AP = 320
,09-06 16:55:42.441  6847  6901 D executeNativeTests: Running unit tests,
,09-06 16:55:42.531  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:55:42.531  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 added. We now have 2 listener(s)
,09-06 16:55:42.531  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 16:55:42.531  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:55:42.531  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:55:42.531  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:55:42.531  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 added. We now have 2 listener(s)
09-06 16:55:42.531  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:55:42.531  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 16:55:42.531  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:55:42.541  6847  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:42.541  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:42.541  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:42.541  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:42.541  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:42.541  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:42.541  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:42.541  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:55:42.541  6847  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 16:55:42.541  6847  6901 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 16:55:42.541  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:42.551  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:42.551  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-06 16:55:42.551  6847  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
09-06 16:55:42.551  6847  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 16:55:42.551  6847  6901 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
09-06 16:55:42.551  6847  6901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 16:55:42.551  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-06 16:55:42.551  6847  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 16:55:42.551  6847  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-06 16:55:42.551  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:42.551  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-06 16:55:42.551  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:42.551  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:42.551  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.551  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:55:42.551  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:55:42.551  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 removed from the list
09-06 16:55:42.551  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.551  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 removed from the list
09-06 16:55:42.551  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:42.551  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.551  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.551  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.551  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:42.551  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:42.551  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.551  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-06 16:55:42.561  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:42.561  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:42.561  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:42.561  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:42.561  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.561  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.561  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:42.561  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.561  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:42.561  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does no,t exist in the list - probably already removed
09-06 16:55:42.561  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.561  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.561  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:55:42.561  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-06 16:55:42.561  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:42.561  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.561  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list,
,09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110],
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 16:55:42.561  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:42.561  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 16:55:42.561  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:42.561  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:42.561  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.561  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.561  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:42.561  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-06 16:55:42.561  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:42.561  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:42.561  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.561  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:55:42.561  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.561  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.561  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:42.561  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:42.561  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.561  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
,09-06 16:55:42.561  6847  6901 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 16:55:42.571  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:55:42.571  6847  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:42.571  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:42.571  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:42.571  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:42.571  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:42.571  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:42.571  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:42.571  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:55:42.571  6847  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 16:55:42.571  6847  6901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:55:42.571  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:55:42.571  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 16:55:42.571  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:55:42.571  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:42.571  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 16:55:42.571  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:42.581  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:42.581  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 16:55:42.581  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 16:55:42.591  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 16:55:42.591  6847  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-06 16:55:42.591  6847  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-06 16:55:42.591  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 16:55:42.591  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 16:55:42.591  6847  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 16:55:42.611  3197  3207 D BtGatt.GattService: registerClient() - UUID=3ee8b2c6-3a02-4649-a279-8e0c04371b6e
,09-06 16:55:42.651  3197  3296 D BtGatt.GattService: onClientRegistered() - UUID=3ee8b2c6-3a02-4649-a279-8e0c04371b6e, clientIf=6
09-06 16:55:42.661  6847  6857 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 16:55:42.661  3197  3389 D BtGatt.GattService: start scan with filters
,09-06 16:55:42.661  3197  3306 D BtGatt.ScanManager: handling starting scan
,09-06 16:55:42.661  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 16:55:42.661  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 16:55:42.661  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 16:55:42.661  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 16:55:42.671  3197  3306 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:42.671  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 16:55:42.671  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 16:55:42.671  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 16:55:42.681  3197  3296 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 16:55:42.681  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:55:42.681  3197  3306 D BtGatt.ScanManager: allow scan with filters
09-06 16:55:42.681  3197  3306 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 16:55:42.681  3197  3306 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-06 16:55:42.681  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 16:55:42.691  3197  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 16:55:42.691  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:55:42.691  3197  3306 D BtGatt.ScanManager: Starting BLE batch scan
09-06 16:55:42.691  3197  3306 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-06 16:55:42.691  6847  6901 I io.jxcore.node.ConnectionHelper: start: OK
09-06 16:55:42.701  3197  3296 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 16:55:42.701  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:55:42.701  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:42.701  6847  6901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 16:55:42.701  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:42.701  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 16:55:42.701  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.701  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 16:55:42.701  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 16:55:42.701  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 16:55:42.711  3197  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 16:55:42.711  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:55:42.711  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 16:55:42.711  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 16:55:42.711  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 16:55:42.711  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 16:55:42.711  3197  3210 D BtGatt.GattService: stopScan() - queue size =1
,09-06 16:55:42.711  3197  3306 D BtGatt.ScanManager: filter size is 1
09-06 16:55:42.711  3197  3306 D BtGatt.ScanManager: delete FilterIndex - 3
,09-06 16:55:42.711  3197  3389 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 16:55:42.721  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:55:42.721  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 16:55:42.721  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 16:55:42.721  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 16:55:42.721  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 16:55:42.721  3197  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 16:55:42.721  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:55:42.721  3197  3306 D BtGatt.ScanManager: stopping BLe Batch
,09-06 16:55:42.721  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 16:55:42.731  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 16:55:42.731  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 16:55:42.731  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 16:55:42.731  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 16:55:42.731  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 16:55:42.731  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 16:55:42.731  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
09-06 16:55:42.731  3197  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 16:55:42.731  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:55:42.731  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:42.731  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.731  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:55:42.731  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list,
09-06 16:55:42.731  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.731  3197  3306 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 16:55:42.731  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
,09-06 16:55:42.731  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:42.731  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.731  6847  6901 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 16:55:42.731  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:55:42.741  3197  3296 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-06 16:55:42.741  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:55:42.741  6847  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:42.741  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:42.741  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:42.741  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:42.741  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:42.741  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:42.741  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:42.741  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:55:42.741  6847  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 16:55:42.741  6847  6901 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 16:55:42.751  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:42.751  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:42.751  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:55:42.751  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-06 16:55:42.751  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:55:42.751  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:42.751  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 16:55:42.751  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 16:55:42.761  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 16:55:42.761  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 16:55:42.761  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 16:55:42.761  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 16:55:42.761  6847  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 16:55:42.771  3197  3389 D BtGatt.GattService: registerClient() - UUID=6978b2a9-53ae-431f-90e0-e9062edb8f5f
,09-06 16:55:42.811  3197  3296 D BtGatt.GattService: onClientRegistered() - UUID=6978b2a9-53ae-431f-90e0-e9062edb8f5f, clientIf=6
,09-06 16:55:42.811  6847  6855 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 16:55:42.811  3197  3390 D BtGatt.GattService: start scan with filters
,09-06 16:55:42.811  3197  3306 D BtGatt.ScanManager: handling starting scan
,09-06 16:55:42.811  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 16:55:42.811  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 16:55:42.811  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 16:55:42.811  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 16:55:42.821  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 16:55:42.821  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 16:55:42.821  3197  3296 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 16:55:42.821  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:55:42.821  3197  3306 D BtGatt.ScanManager: allow scan with filters
,09-06 16:55:42.821  3197  3306 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 16:55:42.821  3197  3306 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-06 16:55:42.821  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 16:55:42.821  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 16:55:42.821  3197  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 16:55:42.831  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:55:42.831  3197  3306 D BtGatt.ScanManager: Starting BLE batch scan
09-06 16:55:42.831  3197  3306 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-06 16:55:42.831  6847  6901 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 16:55:42.831  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 16:55:42.831  6847  6901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 16:55:42.831  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 16:55:42.831  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 16:55:42.831  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 16:55:42.831  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 16:55:42.831  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 16:55:42.831  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 16:55:42.831  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 16:55:42.831  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 16:55:42.831  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-06 16:55:42.831  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 16:55:42.831  3197  3296 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 16:55:42.831  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:55:42.831  3197  3207 D BtGatt.GattService: stopScan() - queue size =1
,09-06 16:55:42.841  3197  3389 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 16:55:42.841  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:55:42.841  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 16:55:42.841  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 16:55:42.841  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 16:55:42.841  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 16:55:42.841  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 16:55:42.841  3197  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 16:55:42.841  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 16:55:42.841  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 16:55:42.841  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 16:55:42.841  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:55:42.841  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 16:55:42.841  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-06 16:55:42.841  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:42.841  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.841  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 16:55:42.841  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:55:42.841  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:42.841  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.841  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:55:42.841  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:42.841  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop,
09-06 16:55:42.841  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.841  3197  3306 D BtGatt.ScanManager: filter size is 1
09-06 16:55:42.841  3197  3306 D BtGatt.ScanManager: delete FilterIndex - 4
09-06 16:55:42.841  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.841  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.841  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 16:55:42.841  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:42.841  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.841  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:42.841  6847  6901 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 16:55:42.851  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:55:42.851  6847  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:42.851  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:42.851  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:42.851  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:42.851  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:42.851  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:42.851  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:42.851  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:55:42.851  3197  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 16:55:42.851  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:55:42.851  3197  3306 D BtGatt.ScanManager: stopping BLe Batch
,09-06 16:55:42.851  6847  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 16:55:42.851  6847  6901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:55:42.851  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:55:42.851  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 16:55:42.851  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:55:42.851  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:42.851  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 16:55:42.861  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-06 16:55:42.861  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 16:55:42.861  3197  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 16:55:42.861  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:55:42.861  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:42.861  3197  3306 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 16:55:42.871  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 16:55:42.871  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 16:55:42.871  3197  3296 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 16:55:42.871  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:55:42.871  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 16:55:42.871  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 16:55:42.871  6847  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 16:55:42.871  3197  3390 D BtGatt.GattService: registerClient() - UUID=6723742e-b598-464a-b8c2-3ea5db7a5e3a
,09-06 16:55:42.921  3197  3296 D BtGatt.GattService: onClientRegistered() - UUID=6723742e-b598-464a-b8c2-3ea5db7a5e3a, clientIf=6
,09-06 16:55:42.921  6847  6855 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 16:55:42.921  3197  3210 D BtGatt.GattService: start scan with filters
,09-06 16:55:42.921  3197  3306 D BtGatt.ScanManager: handling starting scan
,09-06 16:55:42.921  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 16:55:42.921  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 16:55:42.921  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 16:55:42.921  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 16:55:42.931  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 16:55:42.931  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 16:55:42.931  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 16:55:42.931  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 16:55:42.931  3197  3296 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 16:55:42.931  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:55:42.941  3197  3306 D BtGatt.ScanManager: allow scan with filters
,09-06 16:55:42.941  3197  3306 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 16:55:42.941  3197  3306 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-06 16:55:42.941  3197  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 16:55:42.941  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:55:42.941  3197  3306 D BtGatt.ScanManager: Starting BLE batch scan
09-06 16:55:42.941  3197  3306 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 16:55:42.941  6847  6901 I io.jxcore.node.ConnectionHelper: start: OK
09-06 16:55:42.941  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:42.941  6847  6901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 16:55:42.941  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:42.941  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 16:55:42.941  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.941  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 16:55:42.941  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 16:55:42.941  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 16:55:42.941  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 16:55:42.941  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 16:55:42.941  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 16:55:42.941  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 16:55:42.941  3197  3390 D BtGatt.GattService: stopScan() - queue size =1
,09-06 16:55:42.951  3197  3390 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 16:55:42.951  3197  3296 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 16:55:42.951  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:55:42.951  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 16:55:42.951  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-06 16:55:42.951  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 16:55:42.951  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-06 16:55:42.951  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 16:55:42.961  3197  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 16:55:42.961  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:55:42.961  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 16:55:42.961  3197  3306 D BtGatt.ScanManager: filter size is 1
,09-06 16:55:42.961  3197  3306 D BtGatt.ScanManager: delete FilterIndex - 5
,09-06 16:55:42.961  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 16:55:42.961  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 16:55:42.961  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 16:55:42.961  3197  3296 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 16:55:42.971  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:55:42.971  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:55:42.971  3197  3306 D BtGatt.ScanManager: stopping BLe Batch
09-06 16:55:42.971  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:55:42.971  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:55:42.971  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:42.971  6847  6901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 16:55:42.971  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:42.971  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:42.971  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:42.971  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.971  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:55:42.971  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:42.971  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.971  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:42.971  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:42.971  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.971  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:55:42.971  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.971  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.971  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:42.971  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:42.971  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.971  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:42.971  6847  6901 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-06 16:55:42.971  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:42.971  3197  3296 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 16:55:42.971  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:55:42.971  6847  6901 V io.jxcore.node.StartStopOperation: isTarget,State: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:42.971  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:42.971  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:42.971  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.971  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.971  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:42.971  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.971  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:42.971  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:42.971  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.971  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.971  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.971  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.971  3197  3306 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 16:55:42.971  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:42.971  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:42.981  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.981  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:42.981  3197  3296 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 16:55:42.981  3197  3296 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:55:42.981  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 16:55:42.981  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:42.981  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:42.981  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:42.981  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:42.981  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.981  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.981  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:42.981  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.981  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:42.981  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:42.981  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.981  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.981  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.981  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.981  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:42.981  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:42.981  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.981  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:42.981  6847  6901 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-06 16:55:42.981  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:42.981  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:42.981  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:42.981  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:42.991  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.991  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.991  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:42.991  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.991  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:42.991  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:42.991  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.991  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.991  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.991  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.991  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:42.991  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:42.991  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.991  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:42.991  6847  6901 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-06 16:55:42.991  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:42.991  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:42.991  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:42.991  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:42.991  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.991  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.991  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:42.991  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.991  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:42.991  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:42.991  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.991  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.991  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:42.991  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:42.991  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:42.991  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:42.991  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:42.991  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.001  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 16:55:43.001  6847  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 16:55:43.001  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 16:55:43.001  6847  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 16:55:43.001  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 16:55:43.001  6847  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 16:55:43.001  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:43.001  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:43.001  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:43.001  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:43.001  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.001  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.001  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:43.001  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.001  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.001  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:43.001  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.001  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.001  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.001  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.001  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:43.001  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:43.001  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.001  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.001  6847  6901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 16:55:43.001  6847  6901 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 16:55:43.001  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 16:55:43.011  6847  6901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 16:55:43.011  6847  6901 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 16:55:43.011  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 16:55:43.011  6847  6901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 16:55:43.011  6847  6901 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 16:55:43.011  6847  6901 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 16:55:43.011  6847  6901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 16:55:43.011  6847  6901 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 16:55:43.011  6847  6901 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 16:55:43.011  6847  6901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 16:55:43.011  6847  6901 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 16:55:43.011  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-06 16:55:43.011  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-06 16:55:43.011  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 16:55:43.011  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-06 16:55:43.021  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 16:55:43.021  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 16:55:43.021  6847  6901 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 16:55:43.021  6847  6901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 16:55:43.021  6847  6901 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 16:55:43.021  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:43.021  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:43.021  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:43.021  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:43.021  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.021  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.021  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-06 16:55:43.021  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:43.021  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.021  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.021  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:43.021  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.021  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.021  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.021  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.021  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:43.021  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:43.021  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.021  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.021  6847  6901 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 16:55:43.021  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:43.021  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:43.021  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:43.021  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:43.021  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.021  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.021  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:43.021  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.021  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.021  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:43.021  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.021  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.021  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.021  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.021  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:43.021  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:43.021  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.021  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.021  6847  6922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1319)
09-06 16:55:43.021  6847  6901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 16:55:43.021  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:43.021  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:43.021  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:43.021  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:43.021  6847  6923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1319
09-06 16:55:43.031  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.031  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.031  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.031  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.031  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:43.031  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.031  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.031  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.031  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.031  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.031  6847  6901 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 16:55:43.031  6847  6901 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 16:55:43.031  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 16:55:43.031  6847  6901 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 16:55:43.031  6847  6901 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 16:55:43.031  6847  6901 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 16:55:43.031  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 16:55:43.031  6847  6901 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 16:55:43.031  6847  6901 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 16:55:43.031  6847  6901 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 16:55:43.031  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 16:55:43.031  6847  6901 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 16:55:43.031  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:43.031  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:43.031  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:43.031  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.031  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.031  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.031  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.031  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:43.031  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.031  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.031  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.031  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.031  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:43.031  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.031  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.031  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.031  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.031  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:43.031  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.031  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.031  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:43.031  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.031  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.031  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:43.031  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:43.031  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:43.031  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:43.031  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.031  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.031  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.031  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.031  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:43.031  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.031  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.031  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.031  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.031  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.031  6847  6922 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-06 16:55:43.031  6847  6901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:55:43.031  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 16:55:43.031  6847  6922 D BluetoothSocket: connect(): myUserId = 0
09-06 16:55:43.041  6847  6922 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 16:55:43.041  6847  6901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 16:55:43.041  6847  6901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 16:55:43.041  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 16:55:43.041  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 16:55:43.041  6847  6847 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 16:55:43.041  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:43.041  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 16:55:43.041  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 16:55:43.041  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 16:55:43.041  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.041  6847  6901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 16:55:43.041  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:43.041  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.041  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 16:55:43.041  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 16:55:43.041  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 16:55:43.041  6847  6847 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 16:55:43.041  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.041  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.041  3197  3390 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:55:43.041  6847  6924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 16:55:43.041  6847  6924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-06 16:55:43.041  6847  6922 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
09-06 16:55:43.041  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:55:43.041  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:55:43.041  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:55:43.041  6847  6847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-06 16:55:43.041  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.041  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:55:43.041  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:43.041  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:43.041  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:43.041  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:43.041  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.041  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.041  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:43.041  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.041  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.041  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:43.041  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.041  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.041  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.041  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.041  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:43.041  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:43.041  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.041  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.041  6847  6901 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 16:55:43.041  6847  6901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 16:55:43.041  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 16:55:43.041  6847  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 16:55:43.041  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:43.041  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:43.041  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:43.041  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:43.041  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.041  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.041  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:43.041  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.041  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.041  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:43.041  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.041  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.041  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.041  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.051  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:43.051  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:43.051  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.051  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.051  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:43.051  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:43.051  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:43.051  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:43.051  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.051  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.051  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:43.051  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.051  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.051  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:43.051  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.051  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.051  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.051  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.051  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:43.051  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:43.051  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.051  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.051  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:55:43.051  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:55:43.051  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:55:43.051  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:55:43.051  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.051  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.051  6847  6901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f7a0671 not in the list
09-06 16:55:43.051  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.051  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
09-06 16:55:43.051  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:55:43.051  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.051  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.051  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:55:43.051  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:55:43.051  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:55:43.051  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:55:43.051  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:55:43.051  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1515c56 not in the list
,09-06 16:55:43.051  6847  6901 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 16:55:43.051  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 16:55:43.051  6847  6901 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-06 16:55:43.051  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 16:55:43.051  6847  6901 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-06 16:55:43.051  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 16:55:43.061  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 16:55:43.061  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-06 16:55:43.061  6847  6901 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 16:55:43.061  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 16:55:43.061  6847  6901 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 16:55:43.061  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 16:55:43.061  6847  6901 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 16:55:43.061  6847  6901 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-06 16:55:43.061  6847  6901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 16:55:43.061  6847  6901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 16:55:43.061  6847  6901 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 16:55:43.061  6847  6901 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 16:55:43.061  6847  6901 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 16:55:43.061  6847  6901 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-06 16:55:43.061  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:55:43.061  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8c18b48 added. We now have 2 listener(s)
09-06 16:55:43.061  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:55:43.061  6847  6901 D BluetoothAdapter: enable()
09-06 16:55:43.061  6847  6901 D BluetoothAdapter: enable(): BT is already enabled..!
09-06 16:55:43.071  1015  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 16:55:43.071  1015  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 16:55:43.071  1015  1027 D SecContentProvider2: mCursor = null
09-06 16:55:43.071  1015  1027 D WifiService: setWifiEnabled: true pid=6847, uid=10171
09-06 16:55:43.071  1015  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 16:55:43.071  1015  1027 W WifiService: Failed getting userId using ActivityManagerNative
09-06 16:55:43.071  1015  1027 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 16:55:43.071  1015  1027 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 16:55:43.071  1015  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 16:55:43.071  1015  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 16:55:43.071  1015  1027 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 16:55:43.071  1015  1027 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-06 16:55:43.071  1015  1027 D SettingsProvider: name = wifi_on
09-06 16:55:43.071  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:55:43.071  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34886de1 added. We now have 3 listener(s)
09-06 16:55:43.071  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:55:43.081  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:55:43.081  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c978706 added. We now have 4 listener(s)
09-06 16:55:43.081  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:55:43.081  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:55:43.081  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c4c81c7 added. We now have 5 listener(s)
09-06 16:55:43.081  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:55:43.081  1015  4041 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 16:55:43.081  1015  4041 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 16:55:43.081  1015  4041 D SecContentProvider2: mCursor = null
09-06 16:55:43.091  1015  4041 D WifiService: setWifiEnabled: false pid=6847, uid=10171
09-06 16:55:43.091  1015  4041 D SettingsProvider: name = wifi_on
09-06 16:55:43.091  1015  1124 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-06 16:55:43.091  1333  1333 I wpa_supplicant: reset timer : RESET_TIMER 0,
09-06 16:55:43.091  1333  1333 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-06 16:55:43.101  1333  1333 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 16:55:43.101  1333  1333 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 16:55:43.101  6847  6901 D BluetoothAdapter: disable()
,09-06 16:55:43.101  1015  1453 D SettingsProvider: name = bluetooth_on,
,09-06 16:55:43.101  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 16:55:43.111  3197  3293 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-06 16:55:43.111  3197  3293 D BluetoothAdapterProperties: Setting state to 13
09-06 16:55:43.111  3197  3293 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-06 16:55:43.111  3197  3293 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 16:55:43.111  3197  3293 D BluetoothAdapterService: updateAdapterState state is 13
,09-06 16:55:43.111  1015  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 16:55:43.111  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 16:55:43.111  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:43.111  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 16:55:43.111  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:43.121  3197  3197 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-06 16:55:43.121  3197  3197 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2a1b0e24, channel: 19, state: LISTENING
09-06 16:55:43.121  3197  3293 D BluetoothAdapterService: Autoconnection is available 
09-06 16:55:43.121  3197  3293 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-06 16:55:43.121  3197  3293 D BluetoothAdapterService: terminating service from this receiver
,09-06 16:55:43.121  3197  3197 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2a1b0e24, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a3d198c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3fac2d8dmSocket: android.net.LocalSocket@1a3e8b42 impl:android.net.LocalSocketImpl@321b9753 fd:FileDescriptor[74]
09-06 16:55:43.121  3197  3197 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1a3e8b42 impl:android.net.LocalSocketImpl@321b9753 fd:FileDescriptor[74]
,09-06 16:55:43.121  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:55:43.121  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:43.121  6847  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:55:43.121  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:43.121  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:43.121  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:43.121  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:43.121  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:43.121  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:43.121  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:55:43.131  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 16:55:43.131  6847  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 16:55:43.131  6847  6901 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 16:55:43.131  1015  4377 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 16:55:43.131  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:43.131  1015  4377 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:43.131  1015  4377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:43.131  1015  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:43.131  3197  3293 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 16:55:43.131  3197  3293 D BluetoothAdapterProperties: mDiscovering is false
,09-06 16:55:43.131  4098  4098 D BluetoothPbap: Proxy object disconnected
,09-06 16:55:43.131  4098  4098 D PbapServerProfile: Bluetooth service disconnected
,09-06 16:55:43.131  1015  1478 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 16:55:43.141  3197  3293 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-06 16:55:43.141  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:43.141  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,09-06 16:55:43.141  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:43.141  1015  1124 E WifiNative-wlan0: do suspend true
09-06 16:55:43.141  1015  1123 D WifiP2pService: InactiveState{ what=147461 }
09-06 16:55:43.141  1333  1333 I wpa_supplicant: nl80211: Received scan results (11 BSSes)
09-06 16:55:43.141  1015  1123 D WifiP2pService: P2pEnabledState{ what=147461 }
09-06 16:55:43.141  1015  1123 D WifiP2pService: DefaultState{ what=147461 }
,09-06 16:55:43.151  1169  1169 D BluetoothTile:  onBluetoothStateChange:
,09-06 16:55:43.151  1169  1728 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 16:55:43.151  1169  1169 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 16:55:43.151  1169  1728 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 16:55:43.151  1169  1169 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:55:43.151  1169  1169 D BluetoothTile:  getBluetoothState : 13
,09-06 16:55:43.161  1169  1728 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 16:55:43.161  1870  1870 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 16:55:43.161  1015  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 16:55:43.161  4098  4098 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:55:43.171  1015  1453 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 16:55:43.171  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-06 16:55:43.171  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 16:55:43.171  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 16:55:43.171  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:43.171  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:43.171  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:43.171  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:43.171  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:43.171  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 16:55:43.171  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 16:55:43.171  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 16:55:43.171  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:43.171  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 16:55:43.171  1015  1211 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 16:55:43.171  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 16:55:43.171  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:43.171  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:43.171  1015  1211 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:43.171  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:43.181  3197  3296 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-06 16:55:43.181  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:43.191  3197  3296 D BluetoothAdapterProperties: Scan Mode:20
,09-06 16:55:43.191  3197  3197 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@22bb1589, channel: 5, state: LISTENING
,09-06 16:55:43.191  3197  3197 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@22bb1589, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1814b8d5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3b2e198emSocket: android.net.LocalSocket@103e55af impl:android.net.LocalSocketImpl@1cfffdbc fd:FileDescriptor[76]
09-06 16:55:43.191  3197  3197 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@103e55af impl:android.net.LocalSocketImpl@1cfffdbc fd:FileDescriptor[76]
,09-06 16:55:43.191  3197  3293 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 16:55:43.191  3197  3293 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-06 16:55:43.191  3197  3293 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-06 16:55:43.191  3197  3293 E bt-btif : cmd socket is not created
09-06 16:55:43.191  3197  5272 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-06 16:55:43.191  3197  3331 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-06 16:55:43.191  3197  3331 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-06 16:55:43.191  3197  3197 I BtOppRfcommListener: stopping Accept Thread
09-06 16:55:43.191  3197  3197 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@13b68145, channel: 12, state: LISTENING
09-06 16:55:43.191  3197  3197 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@13b68145, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f2346b7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@76409amSocket: android.net.LocalSocket@b249dcb impl:android.net.LocalSocketImpl@3cad39a8 fd:FileDescriptor[79]
09-06 16:55:43.191  3197  3197 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@b249dcb impl:android.net.LocalSocketImpl@3cad39a8 fd:FileDescriptor[79]
09-06 16:55:43.191  3197  3293 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 16:55:43.191  3197  3331 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 16:55:43.191  3197  3331 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:55:43.191  3197  3331 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-06 16:55:43.191  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:43.191  3197  5272 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 16:55:43.201  6847  6922 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@33d071d, channel: -1, state: INIT
09-06 16:55:43.201  6847  6922 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@33d071d, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16950d92, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@18857363mSocket: android.net.LocalSocket@3b8c7b60 impl:android.net.LocalSocketImpl@34a7f819 fd:FileDescriptor[105]
09-06 16:55:43.201  6847  6922 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3b8c7b60 impl:android.net.LocalSocketImpl@34a7f819 fd:FileDescriptor[105]
,09-06 16:55:43.201  3197  3197 V BluetoothOppManager: cleanUp...
09-06 16:55:43.201  6847  6922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1319)
,09-06 16:55:43.201  4098  4098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 16:55:43.201  1015  1028 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 16:55:43.201  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-06 16:55:43.211  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:43.211  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:43.211  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings,
,09-06 16:55:43.211  4098  4098 D DockEventReceiver: finishStartingService: stopping service
,09-06 16:55:43.221  4098  4098 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 16:55:43.221  1169  1169 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:43.221  1169  1169 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-06 16:55:43.221  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-06 16:55:43.221  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:43.221  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:43.221  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:43.231  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:43.241  6930  6930 E Zygote  : MountEmulatedStorage()
,09-06 16:55:43.241  6930  6930 E Zygote  : v2
09-06 16:55:43.241  1015  1028 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6930 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
09-06 16:55:43.241  6930  6930 I libpersona: KNOX_SDCARD checking this for 10055
09-06 16:55:43.241  6930  6930 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:43.251  6930  6930 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 16:55:43.251  6930  6930 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 16:55:43.251  6930  6930 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 16:55:43.281  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
09-06 16:55:43.281  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 16:55:43.281   277  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-06 16:55:43.281  1951  3027 V NativeCrypto: Read error: ssl=0xb785a920: I/O error during system call, Connection timed out
,09-06 16:55:43.291  1951  3027 V NativeCrypto: SSL shutdown failed: ssl=0xb785a920: I/O error during system call, Broken pipe
,09-06 16:55:43.291  1169  1169 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 16:55:43.291  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 16:55:43.291  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.291  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.291  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.291  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 16:55:43.291  6930  6930 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:43.291  1951  3027 E GCM     : Wifi connection closed with errorCode 20
09-06 16:55:43.291  6930  6930 D ActivityThread: Added TimaKeyStore provider
09-06 16:55:43.291  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 16:55:43.291  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 16:55:43.291  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 16:55:43.291  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,09-06 16:55:43.291  1015  4041 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,09-06 16:55:43.291  1015  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:43.291  1015  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:43.291  1015  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-06 16:55:43.291  1015  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:43.291  1015  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,09-06 16:55:43.291  1015  1735 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 16:55:43.301  1015  1735 I qtaguid : Tagging socket 362 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
,09-06 16:55:43.311  1015  1123 D WifiP2pService: InactiveState{ what=131204 }
,09-06 16:55:43.311  1015  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
09-06 16:55:43.311  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-06 16:55:43.311  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 16:55:43.321  1015  1735 I qtaguid : Untagging socket 362
09-06 16:55:43.321  1015  1735 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 16:55:43.321  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 16:55:43.321  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 16:55:43.321  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.321  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 16:55:43.321  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:43.321  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.321  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.321  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.321  1015  1015 D RttService: SCAN_AVAILABLE : 1
09-06 16:55:43.321  1015  1148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 16:55:43.331  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-06 16:55:43.331  1015  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost,
09-06 16:55:43.331  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:55:43.331  1015  1045 D WifiDisplayAdapter: onP2pDisconnected,
,09-06 16:55:43.331  1015  1123 D WifiP2pService: P2pDisablingState
09-06 16:55:43.331  1015  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
09-06 16:55:43.331  1015  1123 D WifiP2pService: p2p socket connection lost
,09-06 16:55:43.331  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 16:55:43.331  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 16:55:43.331  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-06 16:55:43.331  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 16:55:43.331  1015  1045 D WifiDisplayController: disconnect
09-06 16:55:43.331  1015  1045 D WifiDisplayController: updateConnection
09-06 16:55:43.331  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 16:55:43.331  1015  1124 E WifiNative-wlan0: do suspend true
09-06 16:55:43.331  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 16:55:43.331  1015  1123 D WifiP2pService: P2pDisabledState
,09-06 16:55:43.341  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 16:55:43.341  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 16:55:43.341  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-06 16:55:43.341  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 16:55:43.341  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 16:55:43.341  1169  1169 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 16:55:43.351  1015  1485 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 16:55:43.351  1169  1169 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 16:55:43.351  6930  6930 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-06 16:55:43.381  1015  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 16:55:43.381  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-06 16:55:43.381  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:43.381  1015  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:43.381  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:43.381  6930  6930 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-06 16:55:43.381  6930  6930 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-06 16:55:43.381  6930  6930 D UserAnalysis: Create SecureDbHelper
,09-06 16:55:43.391  3197  3331 W bt-l2cap: HC lpm_result_cb 0
,09-06 16:55:43.391  3197  3374 I bt_userial_mct: exiting userial_read_thread
09-06 16:55:43.391  3197  3374 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 16:55:43.391  3197  3331 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:55:43.391  3197  3331 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 16:55:43.391  3197  3331 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 16:55:43.391  3197  3296 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 16:55:43.391  3197  3331 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:55:43.391  3197  3331 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 16:55:43.391  3197  3331 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 16:55:43.391  3197  3331 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:55:43.391  3197  3331 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 16:55:43.391  3197  3333 I bt_vendor: hw_epilog_process
09-06 16:55:43.391  3197  3331 W bt-btif : ag scb idx 1 not allocated
09-06 16:55:43.391  3197  3331 W bt-btif : ag scb idx 2 not allocated
09-06 16:55:43.391  3197  3331 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 16:55:43.391  3197  3296 D bt_userial_mct: userial_close
09-06 16:55:43.391  3197  3296 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-06 16:55:43.391  6930  6930 D IntelligenceServiceApplication: onCreate()
,09-06 16:55:43.401  1015  4041 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-06 16:55:43.401  1015  4041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:43.401  1015  4041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:43.401  6930  6930 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-06 16:55:43.401  1015  4041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:43.401  1015  4041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:43.421  6954  6954 E Zygote  : MountEmulatedStorage()
,09-06 16:55:43.421  1015  4041 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6954 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-06 16:55:43.421  6954  6954 E Zygote  : v2
09-06 16:55:43.421  6954  6954 I libpersona: KNOX_SDCARD checking this for 10105
09-06 16:55:43.421  6954  6954 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:43.421  6954  6954 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 16:55:43.421  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
09-06 16:55:43.421  6954  6954 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 16:55:43.431  6954  6954 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-06 16:55:43.431  6930  6930 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-06 16:55:43.461  6930  6930 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-06 16:55:43.481  6954  6954 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:43.481  6954  6954 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:43.481  1015  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-06 16:55:43.481  1015  1123 D WifiP2pService: DefaultState{ what=143375 }
,09-06 16:55:43.491  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 16:55:43.491  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 16:55:43.491  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.491  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 16:55:43.491  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.491  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.491   277  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 16:55:43.491   277  1009 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-06 16:55:43.491   277  1013 D CommandListener: Clearing all IP addresses on wlan0
09-06 16:55:43.501  1015  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-06 16:55:43.501  1015  1126 V NetworkStats: updateIfacesLocked()
09-06 16:55:43.501  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:43.501  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
09-06 16:55:43.501  1015  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-06 16:55:43.501  1015  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-06 16:55:43.501  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 16:55:43.501  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 16:55:43.501  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 16:55:43.501  1333  1333 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-06 16:55:43.511  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:43.511  1015  1126 V NetworkStats: performPollLocked() took 10ms
,09-06 16:55:43.511  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-06 16:55:43.511  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 16:55:43.511  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 16:55:43.511  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.511  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.511  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.511  1015  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-06 16:55:43.521  1015  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:43.521  1015  1126 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 16:55:43.521  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 16:55:43.521  1015  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-06 16:55:43.521  1169  1712 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 16:55:43.521  1015  1126 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,09-06 16:55:43.521  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 16:55:43.521  1015  1124 D SecContentProvider2: mCursor = null
,09-06 16:55:43.521  1479  1479 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 16:55:43.521  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE,
09-06 16:55:43.521  1479  1479 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:55:43.521  4873  6909 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 16:55:43.521  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-06 16:55:43.521  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 16:55:43.521  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.521  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.521  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 16:55:43.521  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.521  1169  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 16:55:43.521  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-06 16:55:43.521  1169  1169 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 16:55:43.521  1169  1169 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-06 16:55:43.531  1169  1169 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 16:55:43.531  1169  1169 D HotspotTile: onReceive : 0, 0,
,09-06 16:55:43.531  4098  4098 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 16:55:43.531  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:43.531  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:55:43.531  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-06 16:55:43.541  1015  1126 D ConnectivityService: nai.networkMonitor.doQuit()
09-06 16:55:43.541  1015  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-06 16:55:43.541  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 16:55:43.541  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 16:55:43.541  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-06 16:55:43.541  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-06 16:55:43.541  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:43.541  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:43.541  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:43.541  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:43.541  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:43.541  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:43.541  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:43.541  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:43.541  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 16:55:43.541  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:43.541  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:55:43.541  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-06 16:55:43.541  1015  1128 D Tethering: MasterInitialState.processMessage what=3
,09-06 16:55:43.541  1015  1121 V NetworkStats: updateIfacesLocked()
09-06 16:55:43.541  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:43.541  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 16:55:43.541  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 16:55:43.541  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 16:55:43.551  1169  1169 D StatusBar.NetworkController: EthernetConnected: false
09-06 16:55:43.551  1169  1169 D StatusBar.NetworkController: getUpdateDataNetType(): 0,
09-06 16:55:43.551  1169  1169 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 16:55:43.551  1015  1121 V NetworkStats: performPollLocked() took 6ms
09-06 16:55:43.551  1169  1169 D StatusBar.NetworkController: updateDataNetType()
09-06 16:55:43.551  1169  1169 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-06 16:55:43.551  1169  1169 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-06 16:55:43.551  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:55:43.551  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:43.551  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:43.551  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:43.551  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:43.551  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:43.551  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:43.551  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:43.551  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:43.551  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:55:43.551  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:43.551  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:55:43.551  6847  6847 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 16:55:43.571  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
09-06 16:55:43.571  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-06 16:55:43.571  1169  1169 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-06 16:55:43.571  1169  1169 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-06 16:55:43.571  1169  1169 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-06 16:55:43.571  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:43.571  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:43.571  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:55:43.571  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:43.571  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 16:55:43.571  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 16:55:43.571  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:43.571  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.571  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.571  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.571  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 16:55:43.571  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 16:55:43.581  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:43.581  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 16:55:43.581  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:43.611  1333  1333 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 16:55:43.621  3197  3296 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 16:55:43.621  3197  3296 I bt_vendor: bluetooth satus is on
09-06 16:55:43.621  3197  3296 I bt_vendor: bt-vendor : resetting BT status
09-06 16:55:43.621  3197  3296 I bt_vendor: Starting hciattach daemon
09-06 16:55:43.621  3197  3296 I bt_vendor: try to set false
,09-06 16:55:43.621  3197  3296 I bt_vendor: Starting hciattach daemon
09-06 16:55:43.621  3197  3296 I bt_vendor: try to set false
,09-06 16:55:43.621  3197  3296 I bt_vendor: cleanup
,09-06 16:55:43.621  3197  3331 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-06 16:55:43.621  3197  3296 I GKI_LINUX: GKI_exit_task 0 done
09-06 16:55:43.621  3197  3296 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-06 16:55:43.631  3197  3293 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 16:55:43.631  3197  3293 D BtConfig.SecureMode: isSecureModeOn:false
09-06 16:55:43.631  3197  3293 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-06 16:55:43.631  3197  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 16:55:43.631  3197  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 16:55:43.631  3197  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-06 16:55:43.631  1015  1452 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 16:55:43.631  1015  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-06 16:55:43.631  1015  1452 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:43.631  1015  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:43.631  1015  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:43.631  3197  3197 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 16:55:43.641  3197  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 16:55:43.641  3197  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 16:55:43.641  3197  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 16:55:43.641  3197  3197 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 16:55:43.641  3197  3197 D BtGatt.GattService: stop()
09-06 16:55:43.641  3197  3197 D BtGatt.AdvertiseManager: advertise clients cleared
,09-06 16:55:43.641  1015  4377 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:43.641  1015  4377 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 16:55:43.641  1015  4377 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:43.641  1015  4377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:43.641  1015  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:43.641  3197  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 16:55:43.641  3197  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 16:55:43.641  3197  3197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:43.641  3197  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 16:55:43.651  1015  1211 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 16:55:43.651  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 16:55:43.651  3197  3197 D HeadsetService: Received stop request...Stopping profile...
,09-06 16:55:43.651  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:43.651  1015  1211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:43.651  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:43.651  3197  3197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
09-06 16:55:43.651  3197  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-06 16:55:43.651  3197  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 16:55:43.651  3197  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 16:55:43.661  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-06 16:55:43.661  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:43.661  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 16:55:43.661  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:43.661  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:43.661  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:43.661  1333  1333 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-06 16:55:43.661  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 16:55:43.661  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-06 16:55:43.661  3197  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-06 16:55:43.661  3197  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-06 16:55:43.661  3197  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 16:55:43.661  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 16:55:43.671  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 16:55:43.671  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 16:55:43.671  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 16:55:43.671   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 16:55:43.671   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 16:55:43.671  1015  4377 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:43.671  1015  4377 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 16:55:43.671  1015  4377 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:43.671  1015  4377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:43.671  1015  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:43.671  3197  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-06 16:55:43.671  3197  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 16:55:43.671  3197  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 16:55:43.671  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 16:55:43.671  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 16:55:43.681  1015  1211 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:43.681  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 16:55:43.681  6954  6975 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 16:55:43.681  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:43.681  1015  1211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:43.681  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 16:55:43.681  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 16:55:43.681  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 16:55:43.681  3197  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 16:55:43.681  3197  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 16:55:43.681  3197  3293 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 16:55:43.681  1015  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:43.681  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 16:55:43.681  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 16:55:43.681  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:43.681  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:43.681  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 16:55:43.681  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:43.681  3197  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-06 16:55:43.681  3197  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 16:55:43.681  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 16:55:43.681  4098  4098 D HeadsetProfile: Bluetooth service disconnected
09-06 16:55:43.681  3197  3293 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 16:55:43.681  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 16:55:43.681  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 16:55:43.691  1333  1333 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-06 16:55:43.691  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:43.691  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:43.691  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
09-06 16:55:43.691  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 16:55:43.691  1333  1333 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-06 16:55:43.691  1333  1333 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-06 16:55:43.691  1333  1333 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-06 16:55:43.691  1333  1333 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-06 16:55:43.691  3197  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 16:55:43.691  3197  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 16:55:43.691  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 16:55:43.691  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 16:55:43.691  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 16:55:43.691  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 16:55:43.691  3197  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 16:55:43.691  3197  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,09-06 16:55:43.691  3197  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 16:55:43.691  3197  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 16:55:43.691  3197  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,09-06 16:55:43.691  3197  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 16:55:43.691  3197  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 16:55:43.691  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 16:55:43.691  3197  3293 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 16:55:43.691  3197  3293 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 16:55:43.691  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 16:55:43.691  3197  3293 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-06 16:55:43.691  3197  3197 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-06 16:55:43.691  3197  3293 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-06 16:55:43.701  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 16:55:43.701  1015  1128 D Tethering: InitialState.processMessage what=4
,09-06 16:55:43.701  3197  3197 D A2dpService: Received stop request...Stopping profile...
,09-06 16:55:43.701  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 16:55:43.701  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 16:55:43.701  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 16:55:43.701  3197  3318 D A2dpStateMachine: Exit Disconnected: -1
,09-06 16:55:43.701  3197  3197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:43.711  4098  4098 D BluetoothA2dp: Proxy object disconnected
09-06 16:55:43.711  4098  4098 D A2dpProfile: Bluetooth service disconnected
09-06 16:55:43.711  1015  1015 D BluetoothA2dp: Proxy object disconnected
09-06 16:55:43.711  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-06 16:55:43.711  3197  3197 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-06 16:55:43.711  3197  3197 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 16:55:43.711  3197  3197 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-06 16:55:43.711  3197  3197 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-06 16:55:43.711  3197  3197 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-06 16:55:43.711  1015  1128 E Tethering: No numeric data
,09-06 16:55:43.711  3197  3197 D HidService: Received stop request...Stopping profile...
,09-06 16:55:43.711  3197  3197 D HidService: Stopping Bluetooth HidService
09-06 16:55:43.711  3197  3197 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 16:55:43.711  3197  3197 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-06 16:55:43.711  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 16:55:43.711  3197  3197 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 16:55:43.711  3197  3197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
09-06 16:55:43.711  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 16:55:43.711  1015  1128 D Tethering: clearTetheredNotification()
09-06 16:55:43.711  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 16:55:43.711  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 16:55:43.711  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 16:55:43.711  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 16:55:43.711  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:43.711  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 16:55:43.711  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 16:55:43.721  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 16:55:43.721  1169  1169 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 16:55:43.721  1169  1169 D HotspotTile: updateTetherState():false, false
,09-06 16:55:43.721  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 16:55:43.721  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 16:55:43.721   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 16:55:43.721   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 16:55:43.721  3197  3197 D HealthService: Received stop request...Stopping profile...
09-06 16:55:43.721  3197  3197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
09-06 16:55:43.721  1015  1121 V NetworkStats: performPollLocked() took 10ms
09-06 16:55:43.721  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:43.721  3197  3197 D PanService: Received stop request...Stopping profile...
09-06 16:55:43.721  3197  3197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
09-06 16:55:43.721  6954  6975 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 16:55:43.721  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 16:55:43.721  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 16:55:43.731  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:43.731  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:55:43.731  3197  3197 D BluetoothMapService: Received stop request...Stopping profile...
,09-06 16:55:43.731  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 16:55:43.731  4098  4098 D BluetoothInputDevice: Proxy object disconnected
09-06 16:55:43.731  4098  4098 D HidProfile: Bluetooth service disconnected
09-06 16:55:43.731  4098  4098 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 16:55:43.731  4098  4098 D PanProfile: Bluetooth service disconnected
,09-06 16:55:43.731  3197  3197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:43.731  4098  4098 D BluetoothMap: Proxy object disconnected
,09-06 16:55:43.731  4098  4098 D MapProfile: Bluetooth service disconnected
09-06 16:55:43.731  3197  3197 D SapService: Received stop request...Stopping profile...
09-06 16:55:43.731  3197  3197 D SapService: Stopping Bluetooth SapService
09-06 16:55:43.731  3197  3197 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
09-06 16:55:43.731  3197  3197 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-06 16:55:43.731  3197  3197 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 16:55:43.731  3197  3197 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-06 16:55:43.731  3197  3197 D BluetoothA2dp: Proxy object disconnected
09-06 16:55:43.731  3197  3197 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-06 16:55:43.741  3197  3319 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 16:55:43.741  4098  4098 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-06 16:55:43.741  4098  4098 D SapProfile: Bluetooth service disconnected
09-06 16:55:43.741  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 16:55:43.741  3197  3197 I GKI_LINUX: GKI_exit_task 2 done
,09-06 16:55:43.741  3197  3197 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 16:55:43.741  3197  3197 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-06 16:55:43.741  3197  3197 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 16:55:43.741  3197  3197 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 16:55:43.741  3197  3197 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-06 16:55:43.741  3197  3197 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 16:55:43.741  3197  3197 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 16:55:43.741  3197  3197 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-06 16:55:43.741  3197  3197 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 16:55:43.741  3197  3197 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-06 16:55:43.741  3197  3197 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 16:55:43.741  3197  3197 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-06 16:55:43.741  3197  3197 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 16:55:43.741  3197  3197 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-06 16:55:43.741  3197  3197 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-06 16:55:43.741  3197  3197 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 16:55:43.741  3197  3197 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-06 16:55:43.741  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 16:55:43.741  3197  3197 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-06 16:55:43.741  3197  3197 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-06 16:55:43.741  3197  3197 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-06 16:55:43.751   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8e9f7c8
09-06 16:55:43.751   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,09-06 16:55:43.751   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
09-06 16:55:43.751   272   301 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1192626040)
09-06 16:55:43.751  3197  3293 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-06 16:55:43.751  3197  3293 D BluetoothAdapterProperties: Setting state to 10
09-06 16:55:43.751  3197  3293 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 16:55:43.751  3197  3293 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 16:55:43.751  3197  3293 D BluetoothAdapterService: updateAdapterState state is 10
09-06 16:55:43.751  3197  3293 D BluetoothAdapterService: Autoconnection is available 
09-06 16:55:43.751  3197  3293 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-06 16:55:43.751  3197  3293 I BluetoothAdapterState: Entering OffState
09-06 16:55:43.751  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 16:55:43.751  4098  4108 D BluetoothMap: onBluetoothStateChange: up=false
,09-06 16:55:43.751  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 16:55:43.751  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 16:55:43.751  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 16:55:43.761  1169  5713 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 16:55:43.761  1169  5713 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 16:55:43.761  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 16:55:43.761  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 16:55:43.761  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 16:55:43.761  3197  3390 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 16:55:43.761  1479  1479 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 16:55:43.761  4098  4115 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 16:55:43.761  1479  1479 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 16:55:43.791  4098  4108 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 16:55:43.791  4098  4108 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 16:55:43.791  1951  2162 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 16:55:43.791  1951  2162 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 16:55:43.791  4098  4115 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 16:55:43.791  1446  6978 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 16:55:43.791  1446  6978 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 16:55:43.791  1460  1471 D BluetoothAdapter: onBluetoothStateChange: up=false,
09-06 16:55:43.791  1460  1471 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 16:55:43.791  1479  2460 D BluetoothAdapter: onBluetoothStateChange: up=false,
09-06 16:55:43.791  1479  2460 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 16:55:43.791  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 16:55:43.791  4098  4108 D Bluetoothsap: onBluetoothStateChange: up=false
09-06 16:55:43.791  4098  4108 D Bluetoothsap: Unbinding service...
09-06 16:55:43.791  6847  6857 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 16:55:43.791  6847  6857 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 16:55:43.791  6847  6857 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-06 16:55:43.791  6847  6857 D BluetoothLeAdvertiser: Exit stop advertising
09-06 16:55:43.791  6847  6857 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-06 16:55:43.791  6847  6857 D BluetoothLeScanner: Exiting stopAllScan
09-06 16:55:43.791  3197  3210 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 16:55:43.791  3197  3210 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 16:55:43.791  4098  4115 D BluetoothPbap: onBluetoothStateChange: up=false
,09-06 16:55:43.801  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-06 16:55:43.801  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 16:55:43.801   272   301 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
09-06 16:55:43.801   272   301 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
09-06 16:55:43.801   272   301 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1192626040) wakelock released: 1, error no: 0
09-06 16:55:43.801   272   301 I rmt_storage: 
09-06 16:55:43.801   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8e9f7c8
,09-06 16:55:43.811  1333  1333 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 16:55:43.821  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:55:43.821  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
,09-06 16:55:43.821  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 16:55:43.831  1169  1169 D BluetoothAdapter: 686330628: getState() :  mService = null. Returning STATE_OFF
09-06 16:55:43.831  1169  1169 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 16:55:43.831  1169  1728 D BluetoothAdapter: 686330628: getState() :  mService = null. Returning STATE_OFF
09-06 16:55:43.831  1169  1169 D BluetoothTile:  getBluetoothState : 10
09-06 16:55:43.831  1169  1169 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:55:43.831  1169  1728 D BluetoothAdapter: 686330628: getState() :  mService = null. Returning STATE_OFF
09-06 16:55:43.831  1169  1169 D BluetoothAdapter: 686330628: getState() :  mService = null. Returning STATE_OFF
09-06 16:55:43.831  1169  1169 D BluetoothAdapter: 686330628: getState() :  mService = null. Returning STATE_OFF
,09-06 16:55:43.831  1015  1496 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 16:55:43.841  1015  4377 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 16:55:43.841  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-06 16:55:43.841  1870  1870 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 16:55:43.841  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:43.841  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:43.841  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:43.841  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:43.841  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:43.841  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:43.841  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:43.841  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:43.841  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:55:43.841  1015  1452 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 16:55:43.841  1015  1452 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 16:55:43.841  4098  4098 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:55:43.851  1015  1452 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:43.851  1015  1452 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:43.851  1015  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:43.851  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:43.851  1951  2166 D BluetoothAdapter: 603148151: getState() :  mService = null. Returning STATE_OFF
09-06 16:55:43.851  1951  2166 D BluetoothAdapter: 603148151: getState() :  mService = null. Returning STATE_OFF
,09-06 16:55:43.861  3197  3296 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-06 16:55:43.861  3197  3197 I GKI_LINUX: GKI_exit_task 1 done
09-06 16:55:43.861  3197  3197 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 16:55:43.861  3197  3197 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 16:55:43.861  3197  3197 I art     : System.exit called, status: 0
09-06 16:55:43.861  3197  3197 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 16:55:43.871  1333  1333 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
09-06 16:55:43.871  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 16:55:43.871  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 16:55:43.871  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 16:55:43.881  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-06 16:55:43.881  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 16:55:43.881  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 16:55:43.881  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 16:55:43.881  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.881  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.881  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.881  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:43.881  1169  1169 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 16:55:43.881  1169  1169 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-06 16:55:43.881  1169  1169 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 16:55:43.881  1169  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 16:55:43.881  1169  1169 D HotspotTile: onReceive : 1, 0
,09-06 16:55:43.891  4098  4098 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 16:55:43.891  1951  2166 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:43.891  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:43.891  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:43.921  1015  1213 I ActivityManager: Process com.android.bluetooth (pid 3197)(adj 0) has died(31,719)
,09-06 16:55:43.981  1015  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 16:55:43.981  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:43.981  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:43.981  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:43.981  1015  1452 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-06 16:55:44.001  1015  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 16:55:44.001  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.001  1015  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:44.001  6954  6954 D StrictMode: StrictMode policy violation; ~duration=311 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 16:55:44.001  6954  6954 D StrictMode: StrictMode policy violation; ~duration=310 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.go,ogle.android.apps.gmm.shared.i.h.a(PG:252)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 16:55:44.001  6954  6954 D StrictMode: StrictMode policy violation; ~duration=309 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at andr,oid.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 16:55:44.001  6954  6954 D StrictMode: StrictMode policy violation; ~duration=305 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 16:55:44.001  6954  6954 D StrictMode: StrictMode policy violation; ~duration=269 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.q.k.d(PG:583)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 16:55:44.001  6954  6954 D StrictMode: StrictMode policy violation; ~duration=203 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 16:55:44.001  6954  6954 D StrictMode: StrictMode policy violation; ~duration=202 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 16:55:44.001  6954  6954 D StrictMode: StrictMode policy violation; ~duration=202 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 16:55:44.001  6954  6954 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 16:55:44.011  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 16:55:44.031  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 16:55:44.041  1951  1951 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=51c0828f-137d-4dd2-9ebd-17398e558765
09-06 16:55:44.041  1015  1015 I ApplicationPolicy: updateDataUsageMap
09-06 16:55:44.041  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:55:44.051  1015  1478 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-06 16:55:44.051  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
09-06 16:55:44.051  1951  1951 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-06 16:55:44.051  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:44.051  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:44.051  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 16:55:44.061  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:44.061  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:44.071  1951  1951 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-06 16:55:44.071  1951  1951 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-06 16:55:44.081  1951  1951 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-06 16:55:44.081  6954  7006 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-06 16:55:44.081  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 16:55:44.081  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 16:55:44.091  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.091  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 16:55:44.091  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 16:55:44.091  4098  4098 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 16:55:44.101  1619  1619 I Hs20UtilService: Starting #8
,09-06 16:55:44.101  1619  1674 I Hs20UtilService: Message received 5007
,09-06 16:55:44.101  4098  4098 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 16:55:44.101  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 16:55:44.101  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 16:55:44.101  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 16:55:44.101  4098  4098 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 16:55:44.111  1015  4377 I ActivityManager: Killing 6537:com.google.android.apps.plus/u0a117 (adj 15): empty #21
09-06 16:55:44.111  4098  4213 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 16:55:44.111  1015  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 16:55:44.121  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.121  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:44.121  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:44.121  1015  4041 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 16:55:44.131  1015  4041 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:44.131  1015  4041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:44.131  1015  4041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-06 16:55:44.131  1015  1452 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.131  1015  1452 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:44.131  1015  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-06 16:55:44.131  1015  1452 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-06 16:55:44.131  1015  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:44.131  1015  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:44.131  1015  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:44.131  1015  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:44.141  7014  7014 E Zygote  : MountEmulatedStorage()
09-06 16:55:44.141  7014  7014 I libpersona: KNOX_SDCARD checking this for 10102
09-06 16:55:44.141  7014  7014 E Zygote  : v2
09-06 16:55:44.141  7014  7014 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:44.151  7014  7014 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 16:55:44.151  1015  1452 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7014 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,09-06 16:55:44.151  7014  7014 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 16:55:44.151  7014  7014 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 16:55:44.171  7014  7014 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:44.171  7014  7014 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:44.191  7014  7014 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-06 16:55:44.251  1951  2155 W GCoreFlp: No location to return for getLastLocation()
,09-06 16:55:44.351  1951  2155 I art     : Explicit concurrent mark sweep GC freed 68042(3MB) AllocSpace objects, 27(816KB) LOS objects, 39% free, 11MB/19MB, paused 1.411ms total 91.773ms
,09-06 16:55:44.371  1015  1042 D Tethering: interfaceRemoved wlan0
,09-06 16:55:44.371  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-06 16:55:44.381  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 16:55:44.381  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.381  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:44.381  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:44.381  1015  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 16:55:44.391  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.391  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:44.391  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:44.391  1015  1213 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 16:55:44.391  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.391  1015  1213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:44.391  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:44.401   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 16:55:44.401  4873  6953 D UdcContextInitService: registered all accounts: true
,09-06 16:55:44.411  1951  2158 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 16:55:44.441  4314  4323 I art     : Explicit concurrent mark sweep GC freed 1474(50KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 685us total 25.623ms
,09-06 16:55:44.451  7014  7035 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-06 16:55:44.451  7014  7035 I Babel_SMS: MmsConfig.loadMmsSettings
,09-06 16:55:44.451  7014  7035 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-06 16:55:44.451  7014  7035 I Babel_SMS: MmsConfig.loadFromDatabase
,09-06 16:55:44.461  1951  2167 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-06 16:55:44.471  1015  1042 D Tethering: interfaceRemoved p2p0
,09-06 16:55:44.471  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-06 16:55:44.501  7014  7035 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-06 16:55:44.501  7014  7035 I Babel_SMS: MmsConfig.loadFromResources
,09-06 16:55:44.501  7014  7035 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-06 16:55:44.501  7014  7035 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-06 16:55:44.521  1015  1453 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
09-06 16:55:44.521  1015  1453 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-06 16:55:44.531  1015  1453 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.531  1015  1453 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:44.531  1015  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 16:55:44.541  1951  2167 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,09-06 16:55:44.551  7014  7014 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 16:55:44.551  7014  7014 I Babel_Crash: startup - clean
,09-06 16:55:44.591  1951  2167 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,09-06 16:55:44.601  4098  4098 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 16:55:44.601  1015  1027 I ActivityManager: Killing 6427:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-06 16:55:44.601  4098  4098 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 16:55:44.611  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 16:55:44.611  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 16:55:44.611  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 16:55:44.611  4098  4098 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 16:55:44.611  4098  4213 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 16:55:44.611  1015  1453 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-06 16:55:44.611  1015  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:44.611  1015  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:44.621  1015  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:44.621  1015  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:44.621  7014  7014 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 16:55:44.621  7014  7014 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 16:55:44.631  7014  7014 W AudioCapabilities: Unsupported mime audio/qcelp
09-06 16:55:44.631  7039  7039 E Zygote  : MountEmulatedStorage()
09-06 16:55:44.631  7039  7039 E Zygote  : v2
09-06 16:55:44.631  7039  7039 I libpersona: KNOX_SDCARD checking this for 10064
09-06 16:55:44.631  7039  7039 I libpersona: KNOX_SDCARD not a persona
09-06 16:55:44.631  7039  7039 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 16:55:44.631  1015  1453 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7039 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 16:55:44.631  7039  7039 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 16:55:44.631  7039  7039 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 16:55:44.631  7014  7014 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-06 16:55:44.641  7014  7014 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-06 16:55:44.641  7014  7014 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-06 16:55:44.641  7014  7014 W AudioCapabilities: Unsupported mime audio/x-ima
,09-06 16:55:44.641  7014  7014 W AudioCapabilities: Unsupported mime audio/qcelp
,09-06 16:55:44.641  7014  7014 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 16:55:44.651  7014  7014 W VideoCapabilities: Unsupported mime video/wvc1
,09-06 16:55:44.651  7039  7039 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:44.661  7039  7039 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:44.661  7014  7014 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 16:55:44.671  7039  7039 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-06 16:55:44.671  7014  7014 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-06 16:55:44.671  7014  7014 W VideoCapabilities: Unsupported mime video/wvc1
,09-06 16:55:44.671  7014  7014 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 16:55:44.671  7014  7014 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-06 16:55:44.671  7014  7014 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-06 16:55:44.681  7014  7014 W VideoCapabilities: Unsupported mime video/mp43
09-06 16:55:44.681   292   292 E SMD     : DCD OFF
,09-06 16:55:44.681  7014  7014 W VideoCapabilities: Unsupported mime video/sorenson
,09-06 16:55:44.691  7014  7014 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-06 16:55:44.691  7039  7039 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 16:55:44.701  7039  7039 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 16:55:44.701  7014  7014 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-06 16:55:44.731  7039  7039 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 16:55:44.731  1015  1496 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-06 16:55:44.731  1015  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:44.731  1015  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:44.731  1015  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:44.731  1015  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:44.731  7014  7014 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,09-06 16:55:44.731  7014  7014 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 16:55:44.741  7014  7014 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 16:55:44.741  7014  7014 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 16:55:44.741  7054  7054 E Zygote  : MountEmulatedStorage()
09-06 16:55:44.741  7054  7054 E Zygote  : v2
09-06 16:55:44.751  7054  7054 I libpersona: KNOX_SDCARD checking this for 10065
09-06 16:55:44.751  7054  7054 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:44.751  7054  7054 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 16:55:44.751  1015  1496 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7054 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 16:55:44.751  7054  7054 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 16:55:44.751  1015  1496 I ActivityManager: Killing 6569:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
09-06 16:55:44.751  7054  7054 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 16:55:44.751  1015  1453 I ActivityManager: Killing 6598:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
09-06 16:55:44.751  7014  7014 I vclib   : onServiceConnected
,09-06 16:55:44.761  7054  7054 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:44.771  7054  7054 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:44.791  7054  7054 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 16:55:44.791  1015  1211 I ActivityManager: Killing 6618:com.samsung.android.sm/1000 (adj 15): empty #21
,09-06 16:55:44.801  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 16:55:44.801  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 16:55:44.801  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:44.801  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:44.801  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 16:55:44.801  4098  4098 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 16:55:44.801  1619  1619 I Hs20UtilService: Starting #9
09-06 16:55:44.801  4098  4098 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 16:55:44.811  1619  1674 I Hs20UtilService: Message received 5007
,09-06 16:55:44.811  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 16:55:44.811  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 16:55:44.811  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 16:55:44.811  4098  4098 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 16:55:44.811  4098  4213 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 16:55:44.821  1015  1213 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 16:55:44.821  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 16:55:44.821  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:44.821  1015  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 16:55:44.821  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 16:55:44.821  1619  1619 I Hs20UtilService: Starting #10
09-06 16:55:44.821  1619  1674 I Hs20UtilService: Message received 5011
,09-06 16:55:44.821  6637  6637 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 16:55:44.821  6637  6637 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 16:55:44.821  6637  6637 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 16:55:44.821  6637  6637 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 16:55:44.831  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.831  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:44.831  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 16:55:44.841  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.841  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:44.841  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 16:55:44.841  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.841  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:44.841  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 16:55:44.841  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.841  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:44.841  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 16:55:44.851  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.851  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:44.851  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 16:55:44.851  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.851  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:44.851  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 16:55:44.861  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.861  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:44.861  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 16:55:44.861  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.861  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:44.861  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 16:55:44.861  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.861  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:44.861  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 16:55:44.861  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.861  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:44.861  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 16:55:44.871  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:44.871  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:44.871  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 16:55:44.871  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:44.871  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:44.871  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 16:55:44.871  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:44.871  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:44.871  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 16:55:44.881  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:44.881  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:44.881  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-06 16:55:44.881  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:44.881  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:44.881  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 16:55:44.881  4098  4098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 16:55:44.891  1015  4041 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 16:55:44.891  1015  4041 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 16:55:44.891  1015  4041 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:44.891  1015  4041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:44.891  1015  4041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 16:55:44.901  4098  4098 D DockEventReceiver: finishStartingService: stopping service
,09-06 16:55:44.901  4098  4098 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 16:55:44.901  1169  1169 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:55:44.901  1169  1169 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-06 16:55:44.911  1015  4377 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-06 16:55:44.911  1015  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:44.911  1015  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:44.911  1015  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:44.911  1015  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:44.931  7071  7071 E Zygote  : MountEmulatedStorage()
09-06 16:55:44.931  7071  7071 E Zygote  : v2
09-06 16:55:44.931  7071  7071 I libpersona: KNOX_SDCARD checking this for 1002
,09-06 16:55:44.931  7071  7071 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:44.931  7071  7071 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-06 16:55:44.931  1015  4377 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7071 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-06 16:55:44.931  7071  7071 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 16:55:44.941  7071  7071 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 16:55:44.961  7071  7071 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:44.961  7071  7071 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:44.981  7071  7071 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-06 16:55:44.981  7071  7071 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 16:55:45.011  7071  7071 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-06 16:55:45.051  7071  7071 D BtSettings.ProfileConfig: Adding GattService
,09-06 16:55:45.051  7071  7071 D BtSettings.ProfileConfig: Adding HeadsetService
,09-06 16:55:45.051  7071  7071 D BtSettings.ProfileConfig: Adding A2dpService
,09-06 16:55:45.051  7071  7071 D BtSettings.ProfileConfig: Adding HidService
,09-06 16:55:45.051  7071  7071 D BtSettings.ProfileConfig: Adding HealthService
,09-06 16:55:45.051  7071  7071 D BtSettings.ProfileConfig: Adding PanService
,09-06 16:55:45.051  7071  7071 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-06 16:55:45.061  7071  7071 D BtSettings.ProfileConfig: Adding SapService
,09-06 16:55:45.061  7071  7071 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-06 16:55:45.061  7071  7071 D BtSettings.ProfileConfig: Adding A2dpSinkService
,09-06 16:55:45.061  7071  7071 D BtSettings.ProfileConfig: Adding SapClientService
,09-06 16:55:45.061  7071  7071 D BtSettings.ProfileConfig: Adding HidDevService
,09-06 16:55:45.061  7071  7071 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-06 16:55:45.061  1015  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-06 16:55:45.061  1015  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 16:55:45.061  1015  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 16:55:45.061  1015  1478 D SettingsProvider: selectionArgs: false
09-06 16:55:45.071  1015  1478 D SettingsProvider: selectionArgs: 1002
,09-06 16:55:45.071  1015  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 16:55:45.071  1015  1478 D SettingsProvider: ret = -1
,09-06 16:55:45.071  1015  1211 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-06 16:55:45.071  1015  1211 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:45.071  1015  1211 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:45.071  1015  1211 D SettingsProvider: selectionArgs: false
09-06 16:55:45.071  1015  1211 D SettingsProvider: selectionArgs: 1002
,09-06 16:55:45.071  1015  1211 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:45.071  1015  1211 D SettingsProvider: ret = -1
,09-06 16:55:45.071  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-06 16:55:45.071  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:45.071  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 16:55:45.071  1015  1028 D SettingsProvider: selectionArgs: false
09-06 16:55:45.071  1015  1028 D SettingsProvider: selectionArgs: 1002
,09-06 16:55:45.071  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:45.071  1015  1028 D SettingsProvider: ret = -1
,09-06 16:55:45.071  1015  1452 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,09-06 16:55:45.071  1015  1452 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:45.081  1015  1452 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 16:55:45.081  1015  1452 D SettingsProvider: selectionArgs: false
09-06 16:55:45.081  1015  1452 D SettingsProvider: selectionArgs: 1002
,09-06 16:55:45.081  1015  1452 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:45.081  1015  1452 D SettingsProvider: ret = -1
,09-06 16:55:45.081  1015  4377 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,09-06 16:55:45.081  1015  4377 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:45.081  1015  4377 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 16:55:45.081  1015  4377 D SettingsProvider: selectionArgs: false
09-06 16:55:45.081  1015  4377 D SettingsProvider: selectionArgs: 1002
,09-06 16:55:45.081  1015  4377 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:45.081  1015  4377 D SettingsProvider: ret = -1
,09-06 16:55:45.081  1015  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,09-06 16:55:45.081  1015  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:45.081  1015  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 16:55:45.081  1015  1495 D SettingsProvider: selectionArgs: false
09-06 16:55:45.081  1015  1495 D SettingsProvider: selectionArgs: 1002
,09-06 16:55:45.081  1015  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:45.081  1015  1495 D SettingsProvider: ret = -1
,09-06 16:55:45.081  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,09-06 16:55:45.081  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:45.081  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 16:55:45.081  1015  1027 D SettingsProvider: selectionArgs: false
09-06 16:55:45.081  1015  1027 D SettingsProvider: selectionArgs: 1002
,09-06 16:55:45.091  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:45.091  1015  1027 D SettingsProvider: ret = -1
,09-06 16:55:45.091  1015  1485 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,09-06 16:55:45.091  1015  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:45.091  1015  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 16:55:45.091  1015  1485 D SettingsProvider: selectionArgs: false
09-06 16:55:45.091  1015  1485 D SettingsProvider: selectionArgs: 1002
,09-06 16:55:45.091  1015  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 16:55:45.091  1015  1485 D SettingsProvider: ret = -1
,09-06 16:55:45.091  1015  1496 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 16:55:45.091  1015  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:45.091  1015  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:45.091  1015  1496 D SettingsProvider: selectionArgs: false
,09-06 16:55:45.091  1015  1496 D SettingsProvider: selectionArgs: 1002
,09-06 16:55:45.091  1015  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:45.091  1015  1496 D SettingsProvider: ret = -1
,09-06 16:55:45.091  1015  1213 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,09-06 16:55:45.091  1015  1213 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:45.091  1015  1213 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:45.091  1015  1213 D SettingsProvider: selectionArgs: false
,09-06 16:55:45.091  1015  1213 D SettingsProvider: selectionArgs: 1002
09-06 16:55:45.091  1015  1213 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:45.091  1015  1213 D SettingsProvider: ret = -1
,09-06 16:55:45.101  1015  1453 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,09-06 16:55:45.101  1015  1453 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:45.101  1015  1453 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 16:55:45.101  1015  1453 D SettingsProvider: selectionArgs: false
09-06 16:55:45.101  1015  1453 D SettingsProvider: selectionArgs: 1002
,09-06 16:55:45.101  1015  1453 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:45.101  1015  1453 D SettingsProvider: ret = -1
,09-06 16:55:45.101  1015  4041 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,09-06 16:55:45.101  1015  4041 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:45.101  1015  4041 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 16:55:45.101  1015  4041 D SettingsProvider: selectionArgs: false
09-06 16:55:45.101  1015  4041 D SettingsProvider: selectionArgs: 1002
,09-06 16:55:45.101  1015  4041 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 16:55:45.101  1015  4041 D SettingsProvider: ret = -1
,09-06 16:55:45.111  1015  1478 I ActivityManager: Killing 6672:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-06 16:55:45.111  1951  1951 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-06 16:55:45.121  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-06 16:55:45.121  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 16:55:45.121  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 16:55:45.121  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:45.121  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:45.121  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:45.131  1951  7087 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 16:55:45.131  1951  1951 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 16:55:45.131  1015  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 16:55:45.131  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 16:55:45.141  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:45.141  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:45.141  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 16:55:45.141  1015  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 16:55:45.141  1619  1619 I Hs20UtilService: Starting #11
,09-06 16:55:45.141  1619  1674 I Hs20UtilService: Message received 5011
,09-06 16:55:45.141  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:45.141  1015  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:45.141  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:45.151  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 16:55:45.151  6637  6637 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 16:55:45.151  6637  6637 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 16:55:45.151  6637  6637 D SecurityLogAgent: StateMachine : Current State = 1
09-06 16:55:45.151  6637  6637 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 16:55:45.151  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:45.151  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:45.151  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:45.161  1015  1485 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-06 16:55:45.161  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.171  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.171  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.171  1951  7087 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-06 16:55:45.171  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.191  7089  7089 E Zygote  : MountEmulatedStorage(),
09-06 16:55:45.191  1015  1485 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7089 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 16:55:45.191  7089  7089 E Zygote  : v2
09-06 16:55:45.191  7089  7089 I libpersona: KNOX_SDCARD checking this for 1000
09-06 16:55:45.191  7089  7089 I libpersona: KNOX_SDCARD not a persona
09-06 16:55:45.201  7089  7089 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 16:55:45.201  7089  7089 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 16:55:45.201  7089  7089 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 16:55:45.221  7089  7089 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:45.221  7089  7089 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:45.251  7089  7089 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-06 16:55:45.251  7089  7089 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-06 16:55:45.251  7089  7089 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-06 16:55:45.261  7089  7089 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-06 16:55:45.261  7089  7089 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-06 16:55:45.261  7089  7089 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-06 16:55:45.261  7089  7089 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:55:45.271  1015  1213 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,09-06 16:55:45.271  1015  1213 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-06 16:55:45.271  7089  7104 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-06 16:55:45.281  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-06 16:55:45.281  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.281  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.281  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.281  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.301  7106  7106 E Zygote  : MountEmulatedStorage()
,09-06 16:55:45.301  7106  7106 E Zygote  : v2
09-06 16:55:45.301  7106  7106 I libpersona: KNOX_SDCARD checking this for 10001
,09-06 16:55:45.301  7106  7106 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:45.301  7106  7106 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 16:55:45.301  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7106 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 16:55:45.301  1015  4377 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-06 16:55:45.311  1015  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.311  1015  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 16:55:45.311  1015  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.311  1015  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.311  7106  7106 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 16:55:45.311  7106  7106 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 16:55:45.331  7106  7106 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:45.331   321   321 I art     : Explicit concurrent mark sweep GC freed 8711(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 772us total 30.344ms
,09-06 16:55:45.331  7106  7106 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:45.351   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 679us total 19.495ms
,09-06 16:55:45.371   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 675us total 19.280ms,
,09-06 16:55:45.381  7121  7121 E Zygote  : MountEmulatedStorage(),
,09-06 16:55:45.391  7121  7121 E Zygote  : v2
09-06 16:55:45.391  7121  7121 I libpersona: KNOX_SDCARD checking this for 10031
09-06 16:55:45.391  7121  7121 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:45.391  7121  7121 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 16:55:45.391  1015  4377 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7121 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,09-06 16:55:45.391  7121  7121 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-06 16:55:45.391  7121  7121 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 16:55:45.401   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 16:55:45.401  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-06 16:55:45.401  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.401  1752  1752 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
09-06 16:55:45.401  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.401  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.401  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.411  7121  7121 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:45.411  7121  7121 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:45.421  7136  7136 E Zygote  : MountEmulatedStorage()
09-06 16:55:45.421  7136  7136 I libpersona: KNOX_SDCARD checking this for 10121
09-06 16:55:45.421  7136  7136 E Zygote  : v2
09-06 16:55:45.421  7136  7136 I libpersona: KNOX_SDCARD not a persona
09-06 16:55:45.421  7136  7136 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 16:55:45.431  1015  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7136 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-06 16:55:45.431  7136  7136 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 16:55:45.431  7136  7136 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 16:55:45.451  2479  2487 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,09-06 16:55:45.451  1752  1752 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-06 16:55:45.451  1752  1752 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
09-06 16:55:45.451  1752  1752 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
09-06 16:55:45.451  1752  1752 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE,
,09-06 16:55:45.461  1752  1752 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 16:55:45.461  1752  1752 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
09-06 16:55:45.461  7136  7136 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:45.461  7136  7136 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:45.461  1015  4041 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-06 16:55:45.461  1015  4041 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 16:55:45.461  1015  4041 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 16:55:45.461  1015  4041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.461  1015  4041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.481  7151  7151 E Zygote  : MountEmulatedStorage()
,09-06 16:55:45.481  7151  7151 E Zygote  : v2
09-06 16:55:45.481  7151  7151 I libpersona: KNOX_SDCARD checking this for 10077
,09-06 16:55:45.481  7151  7151 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:45.481  7151  7151 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 16:55:45.481  1015  4041 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7151 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 16:55:45.481  7151  7151 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 16:55:45.481  7151  7151 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-06 16:55:45.491  7136  7136 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 16:55:45.491  7136  7136 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-06 16:55:45.491  7136  7136 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 16:55:45.501  7121  7121 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-06 16:55:45.501  1015  1496 I ActivityManager: Killing 6687:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,09-06 16:55:45.511  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-06 16:55:45.511  7136  7136 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:55:45.511  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.521  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.521  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.521  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.521  2785  7166 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
09-06 16:55:45.521  7151  7151 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:45.521  7151  7151 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:45.521  2785  7166 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
09-06 16:55:45.521  2785  7166 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-06 16:55:45.531  2785  7166 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-06 16:55:45.531  2785  7166 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-06 16:55:45.531  7169  7169 E Zygote  : MountEmulatedStorage()
,09-06 16:55:45.531  7169  7169 E Zygote  : v2
09-06 16:55:45.531  7169  7169 I libpersona: KNOX_SDCARD checking this for 10032
09-06 16:55:45.531  7169  7169 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:45.541  7169  7169 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 16:55:45.541  1015  1028 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7169 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-06 16:55:45.541  7169  7169 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 16:55:45.541  7169  7169 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-06 16:55:45.551  7136  7136 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-06 16:55:45.551  7136  7136 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-06 16:55:45.551  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-06 16:55:45.551  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.551  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.551  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.551  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.571  7184  7184 E Zygote  : MountEmulatedStorage()
09-06 16:55:45.571  7184  7184 I libpersona: KNOX_SDCARD checking this for 10141
09-06 16:55:45.571  7184  7184 E Zygote  : v2,
09-06 16:55:45.571  7184  7184 I libpersona: KNOX_SDCARD not a persona
09-06 16:55:45.571  7184  7184 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 16:55:45.571  7184  7184 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 16:55:45.571  7184  7184 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 16:55:45.571  7169  7169 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 16:55:45.571  1015  1028 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7184 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
09-06 16:55:45.571  7169  7169 D ActivityThread: Added TimaKeyStore provider
09-06 16:55:45.571  1015  1028 I ActivityManager: Killing 6703:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,09-06 16:55:45.581  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-06 16:55:45.581  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.581  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.581  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.581  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.601  7184  7184 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:45.601  7184  7184 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:45.601  7200  7200 E Zygote  : MountEmulatedStorage()
,09-06 16:55:45.601  7200  7200 E Zygote  : v2
09-06 16:55:45.601  7200  7200 I libpersona: KNOX_SDCARD checking this for 1000
09-06 16:55:45.601  7200  7200 I libpersona: KNOX_SDCARD not a persona
09-06 16:55:45.601  1015  1028 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7200 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-06 16:55:45.601  1015  1028 I ActivityManager: Killing 6652:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-06 16:55:45.601  7200  7200 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 16:55:45.601  7200  7200 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 16:55:45.611  7200  7200 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 16:55:45.621  7184  7184 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-06 16:55:45.621  7184  7184 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 16:55:45.631  7184  7184 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 16:55:45.631  7184  7184 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-06 16:55:45.641  7200  7200 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:45.641  7200  7200 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:45.671  7169  7215 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-06 16:55:45.671  7169  7215 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-06 16:55:45.671  7169  7169 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true,
,09-06 16:55:45.681  1015  1496 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-06 16:55:45.681  7200  7200 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-06 16:55:45.681  1015  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.681  1015  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.681  1015  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.681  1015  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.691  1015  1478 D RCPManagerService: exchangeData() failure , invalid userId,
,09-06 16:55:45.701  7169  7215 D SPPClientService: PushLog.txt file is not deleted.
09-06 16:55:45.701  7169  7215 D SPPClientService: PushLog.txt file is not deleted.
09-06 16:55:45.701  7169  7215 D SPPClientService: ============PushLog. stop!
,09-06 16:55:45.711  7217  7217 E Zygote  : MountEmulatedStorage(),
09-06 16:55:45.711  7217  7217 E Zygote  : v2
09-06 16:55:45.711  7217  7217 I libpersona: KNOX_SDCARD checking this for 10036
09-06 16:55:45.711  7217  7217 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:45.711  7217  7217 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 16:55:45.711  7217  7217 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 16:55:45.711  7217  7217 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
,09-06 16:55:45.711  1015  1496 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7217 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 16:55:45.721  1015  1496 I ActivityManager: Killing 6725:com.qualcomm.timeservice/1000 (adj 15): empty #21
,09-06 16:55:45.721  1015  1213 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-06 16:55:45.721  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-06 16:55:45.721  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:45.721  1015  1213 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-06 16:55:45.721  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
09-06 16:55:45.721  1015  1213 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 16:55:45.731  7217  7217 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:45.741  7217  7217 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:45.781  7217  7217 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@20e8e22a
,09-06 16:55:45.781  1015  1485 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 16:55:45.801  1015  1496 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 16:55:45.801  7217  7217 I SA      : [SSP] onCreated
,09-06 16:55:45.811  7217  7217 I SA      : [TPM] There is no property file
,09-06 16:55:45.811  7217  7217 I SA      : [SCU] isHaveSA() - false
09-06 16:55:45.821  7217  7217 I SA      : [TPM] getModelProperty : null
09-06 16:55:45.821  7217  7217 I SA      : [TPM] getCSCProperty : null
09-06 16:55:45.821  7217  7217 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-06 16:55:45.821  7217  7217 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-06 16:55:45.821  7217  7217 I SA      : [DM] TFT FEATURE: false
,09-06 16:55:45.831  7217  7217 I SA      : [DM] init START
,09-06 16:55:45.831  7169  7227 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-06 16:55:45.831  7217  7217 I SA      : [DM] This device is not a Vodafone
,09-06 16:55:45.841  7217  7217 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-06 16:55:45.841  7217  7217 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
09-06 16:55:45.841  7217  7217 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-06 16:55:45.841  7217  7217 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
09-06 16:55:45.841  7217  7217 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-06 16:55:45.841  7217  7217 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-06 16:55:45.841  7217  7217 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
09-06 16:55:45.841  7217  7217 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-06 16:55:45.841  7217  7217 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
09-06 16:55:45.841  7217  7217 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
09-06 16:55:45.851  7217  7217 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-06 16:55:45.861  7200  7200 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
09-06 16:55:45.861  7217  7217 I SA      : [SCU] isHaveSA() - false
09-06 16:55:45.861  7217  7217 I SA      : support phone number id : false
09-06 16:55:45.861  7217  7217 I SA      : [DM] Supports Ref Jpn : true
09-06 16:55:45.861  7217  7217 I SA      : [DM] init END
09-06 16:55:45.861  7217  7217 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
09-06 16:55:45.861  7217  7217 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-06 16:55:45.861  7217  7217 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-06 16:55:45.871  7200  7200 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-06 16:55:45.871  7200  7200 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:55:45.871  7200  7200 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-06 16:55:45.871  7200  7200 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-06 16:55:45.871  7200  7200 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
09-06 16:55:45.881  7217  7217 I SA      : [SLFUCHKMGR] constructor called
09-06 16:55:45.881  1015  4041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-06 16:55:45.881  1015  4041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.881  1015  4041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.881  1015  4041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.881  1015  4041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.891  7217  7217 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-06 16:55:45.891  7217  7217 I SA      : [OR] == isSIMCardReady false ==
,09-06 16:55:45.891  7247  7247 E Zygote  : MountEmulatedStorage()
09-06 16:55:45.891  7247  7247 E Zygote  : v2
09-06 16:55:45.891  7247  7247 I libpersona: KNOX_SDCARD checking this for 10008
09-06 16:55:45.891  7247  7247 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:45.891  7247  7247 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 16:55:45.891  1015  1495 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 16:55:45.901  1015  4041 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7247 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 16:55:45.901  1015  4041 I ActivityManager: Killing 6140:com.android.mms/u0a41 (adj 15): empty #21
,09-06 16:55:45.901  1015  1213 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 16:55:45.901  7247  7247 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 16:55:45.901  7247  7247 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-06 16:55:45.911  7217  7217 I SA      : [SCU] == networkStateCheck == false
09-06 16:55:45.911  1015  1452 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
09-06 16:55:45.911  7217  7217 I SA      : [OR] onReceive END
,09-06 16:55:45.911  1015  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 16:55:45.911  1015  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.911  1015  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:45.911  1015  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:45.911  1015  1478 D CountryDetector: No listener is left
,09-06 16:55:45.931  7263  7263 E Zygote  : MountEmulatedStorage(),
,09-06 16:55:45.931  7263  7263 E Zygote  : v2
09-06 16:55:45.931  7263  7263 I libpersona: KNOX_SDCARD checking this for 10068
09-06 16:55:45.931  7263  7263 I libpersona: KNOX_SDCARD not a persona
09-06 16:55:45.931  7263  7263 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 16:55:45.931  1015  1452 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7263 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
09-06 16:55:45.941  7263  7263 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 16:55:45.941  1015  1485 I ActivityManager: Killing 6746:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,09-06 16:55:45.941  7263  7263 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-06 16:55:45.941  7247  7247 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 16:55:45.941  7247  7247 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:45.951  1224  1224 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:55:45.961  7263  7263 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:45.961  7263  7263 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:45.991  1015  1027 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 16:55:46.001  7263  7263 D BadgeProvider: onCreate
,09-06 16:55:46.001  7263  7263 D BadgeProvider: DatabaseHelper
,09-06 16:55:46.011  1015  4377 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 16:55:46.011  1015  1485 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-06 16:55:46.021  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:46.021  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:46.021  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:46.021  1015  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:46.021  7263  7272 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-06 16:55:46.031  7279  7279 E Zygote  : MountEmulatedStorage(),
09-06 16:55:46.031  7279  7279 E Zygote  : v2
09-06 16:55:46.031  7279  7279 I libpersona: KNOX_SDCARD checking this for 10009
,09-06 16:55:46.031  7279  7279 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:46.031  7279  7279 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 16:55:46.041  7279  7279 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 16:55:46.041  1015  1485 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7279 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-06 16:55:46.041  1015  1478 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-06 16:55:46.041  1015  1478 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-06 16:55:46.041  1015  1478 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 16:55:46.041  1015  1478 D BatteryService: stay LED for fully charged
09-06 16:55:46.041  7279  7279 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-06 16:55:46.041  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-06 16:55:46.041  1015  1485 I ActivityManager: Killing 6575:com.android.calendar/u0a131 (adj 15): empty #21
09-06 16:55:46.041  1015  1485 I ActivityManager: Killing 6763:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #22
09-06 16:55:46.041  1015  1015 I MotionRecognitionService: Plugged
09-06 16:55:46.041  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 16:55:46.051  1169  1169 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-06 16:55:46.051  1169  1169 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 16:55:46.051  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 16:55:46.051  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 16:55:46.061  1169  1169 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-06 16:55:46.061  1169  1169 D SViewCoverView: level :100 plugged : 2
,09-06 16:55:46.071  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 16:55:46.071  7279  7279 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:46.071  7279  7279 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:46.081  1015  4377 I ActivityManager: Killing 6778:com.google.android.gms:car/u0a11 (adj 15): empty #21
,09-06 16:55:46.081  7263  7271 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-06 16:55:46.081  7263  7271 D BadgeProvider: sendNotify, [notify] : null
09-06 16:55:46.081  7263  7271 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-06 16:55:46.081  7263  7271 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-06 16:55:46.081  7263  7271 D BadgeProvider: update, [UpdateCount] : 1
,09-06 16:55:46.081  1497  1497 D Launcher.Model: reloadBadges entered.
,09-06 16:55:46.081  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 16:55:46.081  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 16:55:46.091  2908  2908 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 06 16:55:46 GMT+02:00 2016
,09-06 16:55:46.091  1015  1478 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-06 16:55:46.091  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-06 16:55:46.101  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:46.101  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:46.101  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-06 16:55:46.111  2908  2908 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-06 16:55:46.111  2908  2908 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-06 16:55:46.111  1015  1478 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-06 16:55:46.111  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-06 16:55:46.121  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:46.121  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:46.121  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 16:55:46.121  2908  2908 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-06 16:55:46.121  1015  4041 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-06 16:55:46.121  1015  4041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:46.121  1015  4041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:46.121  1015  4041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:46.121  1015  4041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:46.121  2908  2908 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-06 16:55:46.131  7296  7296 E Zygote  : MountEmulatedStorage()
,09-06 16:55:46.141  7296  7296 E Zygote  : v2
09-06 16:55:46.141  7296  7296 I libpersona: KNOX_SDCARD checking this for 10110
09-06 16:55:46.141  7296  7296 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 16:55:46.141  7296  7296 I libpersona: KNOX_SDCARD not a persona
09-06 16:55:46.141  2908  7294 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
09-06 16:55:46.141  1015  1028 D WifiService: setWifiEnabled: true pid=6847, uid=10171
09-06 16:55:46.141  1015  1028 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 16:55:46.141  1015  1028 W ActivityManager: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
09-06 16:55:46.141  1015  1028 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 16:55:46.141  1015  1028 D SecContentProvider2: mCursor = null
09-06 16:55:46.141  7296  7296 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 16:55:46.141  1015  1028 W WifiService: Failed getting userId using ActivityManagerNative
09-06 16:55:46.141  1015  1028 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 16:55:46.141  1015  1028 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972),
09-06 16:55:46.141  1015  1028 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 16:55:46.141  1015  1028 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 16:55:46.141  1015  1028 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 16:55:46.141  1015  1028 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-06 16:55:46.141  1015  1028 D SettingsProvider: name = wifi_on
09-06 16:55:46.141  7296  7296 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-06 16:55:46.141  2908  7294 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION,
,09-06 16:55:46.151  2908  7294 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
09-06 16:55:46.151  1015  1124 E WifiHW  : ##################### set firmware type 0 #####################
09-06 16:55:46.151  2908  7294 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-06 16:55:46.171  1015  4041 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7296 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 16:55:46.171  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-06 16:55:46.171  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-06 16:55:46.191  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:46.191  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:46.191  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
09-06 16:55:46.191   321   321 I art     : Explicit concurrent mark sweep GC freed 8690(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 27.127ms
,09-06 16:55:46.201  7296  7296 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 16:55:46.201  7296  7296 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:46.201  7014  7295 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-06 16:55:46.211  2908  2908 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-06 16:55:46.211   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 16.787ms,
,09-06 16:55:46.221  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-06 16:55:46.221  1015  1211 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-06 16:55:46.231  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-06 16:55:46.231   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 727us total 19.017ms
,09-06 16:55:46.241  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-06 16:55:46.251  1015  1453 I ActivityManager: Killing 6076:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-06 16:55:46.261  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 16:55:46.261  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-06 16:55:46.261  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:46.261  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:46.261  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:46.291  1015  1485 I art     : Explicit concurrent mark sweep GC freed 61881(3MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 24MB/36MB, paused 3.018ms total 195.137ms
,09-06 16:55:46.291  4873  7315 I iu.SyncManager: SYNC; picasa accounts
,09-06 16:55:46.311  1015  1028 I ActivityManager: Killing 5876:com.android.vending/u0a26 (adj 15): empty #21
,09-06 16:55:46.321  4873  4873 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-06 16:55:46.401   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 16:55:46.441  1015  1452 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 16:55:46.561   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-06 16:55:46.561   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 16:55:46.561  7296  7327 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-06 16:55:46.561   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-06 16:55:46.561   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 16:55:46.571  7296  7327 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-06 16:55:46.571   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-06 16:55:46.571   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 16:55:46.571  7296  7328 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-06 16:55:46.581  7296  7296 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-06 16:55:46.581  7296  7296 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-06 16:55:46.581  7296  7296 I GAv4    :   adb logcat -s GAv4
,09-06 16:55:46.581   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-06 16:55:46.581   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 16:55:46.581  7296  7328 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-06 16:55:46.621  1015  1042 D Tethering: interfaceAdded wlan0,
09-06 16:55:46.621  1015  1213 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
09-06 16:55:46.621  7296  7296 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-06 16:55:46.631  1015  1128 E Tethering: No numeric data
,09-06 16:55:46.631  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 16:55:46.631  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 16:55:46.631  1015  1128 D Tethering: clearTetheredNotification()
09-06 16:55:46.631  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 16:55:46.631  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 16:55:46.631  1015  1128 D Tethering: InitialState.processMessage what=4
,09-06 16:55:46.631  1015  1128 E Tethering: No numeric data
,09-06 16:55:46.631  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 16:55:46.631  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:46.631  1015  1042 D Tethering: interfaceAdded p2p0
09-06 16:55:46.631  7296  7296 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
09-06 16:55:46.631  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 16:55:46.641  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 16:55:46.641  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
09-06 16:55:46.641   277  1013 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-06 16:55:46.641   277  1013 D SoftapController: Softap fwReload - Ok,
09-06 16:55:46.641  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 16:55:46.641  1169  1169 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 16:55:46.641  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
09-06 16:55:46.641  1169  1169 D HotspotTile: updateTetherState():false, false
,09-06 16:55:46.641  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
09-06 16:55:46.641  1015  1121 V NetworkStats: performPollLocked() took 5ms
09-06 16:55:46.641  1015  1128 D Tethering: clearTetheredNotification()
09-06 16:55:46.641  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 16:55:46.641  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:46.641   277  1013 D CommandListener: Setting iface cfg
09-06 16:55:46.641   277  1013 D CommandListener: Trying to bring down wlan0
,09-06 16:55:46.641   277  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-06 16:55:46.641  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 16:55:46.641  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:46.641  1169  1169 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 16:55:46.641  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 16:55:46.641  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 16:55:46.651  1169  1169 D HotspotTile: updateTetherState():false, false
,09-06 16:55:46.651  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:46.651  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:46.651  1015  1121 V NetworkStats: performPollLocked() took 4ms
,09-06 16:55:46.651  1015  1124 E WifiHW  : supplicant_name : p2p_supplicant
09-06 16:55:46.651  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:55:46.651  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:46.651  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:55:46.651  1951  2167 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,09-06 16:55:46.651  1951  2161 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,09-06 16:55:46.661  7296  7331 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,09-06 16:55:46.701  7332  7332 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
09-06 16:55:46.701  7332  7332 I wpa_supplicant: Successfully initialized wpa_supplicant
09-06 16:55:46.701  7332  7332 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-06 16:55:46.741  7332  7332 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-06 16:55:46.741   406   406 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7332,
09-06 16:55:46.741   406   406 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
09-06 16:55:46.741  7332  7332 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-06 16:55:46.741  7332  7332 I wpa_supplicant: ssSupport state is = 1
09-06 16:55:46.741  7332  7332 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-06 16:55:46.741  7332  7332 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-06 16:55:46.741   406   406 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7332,
09-06 16:55:46.741   406   406 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-06 16:55:46.751  1015  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,09-06 16:55:46.761  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 16:55:46.761  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 16:55:46.761  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:46.761  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:46.761  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 16:55:46.761  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 16:55:46.761  1169  1169 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 16:55:46.761  1169  1169 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 16:55:46.761  1169  1169 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-06 16:55:46.761  1169  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
09-06 16:55:46.761  1169  1169 D HotspotTile: onReceive : 2, 0
,09-06 16:55:46.761  4098  4098 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 16:55:46.771  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:46.771  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:46.911  1015  1211 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 16:55:46.921  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:46.921  1015  1211 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 16:55:46.921  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-06 16:55:46.921   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,09-06 16:55:46.931  7332  7332 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-06 16:55:46.961  7296  7296 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-06 16:55:46.981  7332  7332 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 16:55:46.981  7332  7332 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-06 16:55:46.981  7296  7296 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 7244-7246)
,09-06 16:55:46.981  7296  7296 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-06 16:55:46.991  7296  7296 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3fac2d8d},
09-06 16:55:46.991  7296  7296 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-06 16:55:46.991  7296  7296 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 16:55:46.991  7332  7332 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
09-06 16:55:46.991   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7332
09-06 16:55:46.991   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 16:55:46.991  7332  7332 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
,09-06 16:55:46.991  7332  7332 I wpa_supplicant: ssSupport state is = 1
09-06 16:55:46.991  7332  7332 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-06 16:55:46.991  7332  7332 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 16:55:46.991  7332  7332 E wpa_supplicant: SIM READ ERROR
09-06 16:55:46.991  7332  7332 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 16:55:46.991  7332  7332 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 16:55:46.991  7332  7332 E wpa_supplicant: SIM READ ERROR
09-06 16:55:46.991  7332  7332 I wpa_supplicant: Blacklist: Clear (all) 
09-06 16:55:46.991  7332  7332 I wpa_supplicant: wpa_default_ap_write_once
09-06 16:55:46.991  7332  7332 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 16:55:47.001  7332  7332 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 16:55:47.001  7332  7332 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-06 16:55:47.001  7332  7332 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 16:55:47.001  7332  7332 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,09-06 16:55:47.001  7332  7332 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-06 16:55:47.001  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 16:55:47.001  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 16:55:47.001  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 16:55:47.011  7296  7296 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,09-06 16:55:47.011  7296  7296 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,09-06 16:55:47.021  7296  7296 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-06 16:55:47.031  7296  7296 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 16:55:47.031  7296  7296 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 16:55:47.031  7296  7296 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 16:55:47.031  7296  7296 I Adreno-EGL: Local Branch: 
09-06 16:55:47.031  7296  7296 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 16:55:47.031  7296  7296 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 16:55:47.031  7296  7296 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 16:55:47.051  7332  7332 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-06 16:55:47.101  7296  7296 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-06 16:55:47.111  7296  7362 W cr.media: Requires BLUETOOTH permission
,09-06 16:55:47.121  7296  7296 I NSApplication: Starting up...
,09-06 16:55:47.121  1015  4041 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 16:55:47.131  1015  1211 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-06 16:55:47.131  1015  4377 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-06 16:55:47.131  1015  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:47.131  1015  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:47.131  1015  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:47.131  1015  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:47.151  1015  4377 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7367 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-06 16:55:47.151  7367  7367 E Zygote  : MountEmulatedStorage()
09-06 16:55:47.151  7367  7367 E Zygote  : v2
09-06 16:55:47.151  7367  7367 I libpersona: KNOX_SDCARD checking this for 10117
09-06 16:55:47.151  7367  7367 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:47.161  7367  7367 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 16:55:47.161  1015  4377 I ActivityManager: Killing 7039:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-06 16:55:47.161  7367  7367 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 16:55:47.161  7367  7367 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 16:55:47.171  7332  7332 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-06 16:55:47.171  7332  7332 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-06 16:55:47.191  7367  7367 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 16:55:47.191  7332  7332 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-06 16:55:47.191   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7332
09-06 16:55:47.191   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 16:55:47.191  7332  7332 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-06 16:55:47.191  7332  7332 I wpa_supplicant: ssSupport state is = 1
09-06 16:55:47.191  7367  7367 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:47.191  7332  7332 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 16:55:47.201  7332  7332 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-06 16:55:47.211  7332  7332 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-06 16:55:47.211   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7332
09-06 16:55:47.211   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 16:55:47.211  7332  7332 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-06 16:55:47.211  7332  7332 I wpa_supplicant: ssSupport state is = 1
09-06 16:55:47.211  7332  7332 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 16:55:47.211  7332  7332 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 16:55:47.211  7332  7332 E wpa_supplicant: SIM READ ERROR
09-06 16:55:47.211  7332  7332 I wpa_supplicant: wpa_default_ap_write_once
09-06 16:55:47.211  7332  7332 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 16:55:47.211  7332  7332 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 16:55:47.211  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,09-06 16:55:47.211  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
09-06 16:55:47.211  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 16:55:47.211  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 16:55:47.211  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-06 16:55:47.211  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 16:55:47.221  7367  7367 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 16:55:47.281  7332  7332 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-06 16:55:47.281  7332  7332 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-06 16:55:47.401   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 16:55:47.451  7332  7332 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-06 16:55:47.451  7332  7332 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-06 16:55:47.451  7332  7332 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 16:55:47.461  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-06 16:55:47.461  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-06 16:55:47.461  7332  7332 I wpa_supplicant: HOTSPOT20_ENABLE called
09-06 16:55:47.461  7332  7332 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-06 16:55:47.461  7332  7332 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 16:55:47.461  7332  7332 E wpa_supplicant: SIM READ ERROR
09-06 16:55:47.461  7332  7332 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 16:55:47.481  7332  7332 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-06 16:55:47.501  7332  7332 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 16:55:47.501  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 16:55:47.501  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 16:55:47.501  1169  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 16:55:47.501  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:47.501  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:47.501  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:47.501  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:47.501  1169  1169 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 16:55:47.501  1169  1169 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-06 16:55:47.511  1169  1169 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 16:55:47.501  1015  1124 D WifiConfigStore: Loading config and enabling all networks ,
,09-06 16:55:47.511  1169  1169 D HotspotTile: onReceive : 3, 0
,09-06 16:55:47.511  4098  4098 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 16:55:47.511  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:47.511  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:47.511  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:47.511  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:47.511  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:47.511  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:47.511  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:47.511  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:47.511  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:55:47.511  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:47.511  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:55:47.511  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 16:55:47.511  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:47.511  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:47.511  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:47.511  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:55:47.511  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:47.511  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:47.511  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:47.511  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:55:47.511  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:47.511  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:55:47.521  1015  1124 E WifiConfigStore: Not a HS20
,09-06 16:55:47.521  1015  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 16:55:47.521  1015  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-06 16:55:47.521  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-06 16:55:47.521  7332  7332 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-06 16:55:47.521  7332  7332 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-06 16:55:47.521  7332  7332 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 16:55:47.521  7332  7332 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 16:55:47.521  7332  7332 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-06 16:55:47.521  7332  7332 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-06 16:55:47.521  7332  7332 I wpa_supplicant: First Scan Start
,09-06 16:55:47.531  7332  7332 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 16:55:47.531  1015  1124 D WifiNative-wlan0: Setting external_sim to 1
,09-06 16:55:47.531  7014  7014 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 16:55:47.531  1015  1124 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 16:55:47.531  1015  1124 I WifiNative-HAL: startHal
09-06 16:55:47.531  1015  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9d58288c
09-06 16:55:47.531  1015  1124 I WifiNative-HAL: Could not start hal
,09-06 16:55:47.531  1015  1124 E WifiNative-wlan0: do suspend true
,09-06 16:55:47.531  1015  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-06 16:55:47.531  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3,
,09-06 16:55:47.541   277  1013 D CommandListener: Setting iface cfg
09-06 16:55:47.541   277  1013 D CommandListener: Trying to bring up p2p0
09-06 16:55:47.541  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 16:55:47.541  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:47.541  1015  1147 I WifiNative-HAL: startHal
09-06 16:55:47.541  1015  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9ea3a9bc
09-06 16:55:47.541  1015  1147 I WifiNative-HAL: Could not start hal
09-06 16:55:47.541  1015  1147 E WifiScanningService: could not start HAL
09-06 16:55:47.541  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 16:55:47.541  1015  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 16:55:47.541  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 16:55:47.541  1015  1124 E WifiNative-wlan0: invaild command id : 215
09-06 16:55:47.541  1015  1015 D RttService: SCAN_AVAILABLE : 3
,09-06 16:55:47.541  1015  1148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:55:47.541  1015  1123 D WifiP2pService: P2pEnablingState
,09-06 16:55:47.541  1015  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
09-06 16:55:47.541  1015  1123 D WifiP2pService: P2p socket connection successful
,09-06 16:55:47.541  7332  7332 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 16:55:47.541  1015  1123 D WifiP2pService: P2pEnabledState
09-06 16:55:47.541  7332  7332 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 16:55:47.541  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-06 16:55:47.541  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-06 16:55:47.541  7332  7332 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-06 16:55:47.541  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-06 16:55:47.541  1015  1124 E WifiStateMachine: Failed to set frequency band 0
,09-06 16:55:47.541  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 16:55:47.541  1015  1124 D SecContentProvider2: mCursor = null
09-06 16:55:47.541  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-06 16:55:47.541  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 16:55:47.541  1015  1045 D WifiDisplayController: disconnect
09-06 16:55:47.541  1015  1045 D WifiDisplayController: updateConnection
09-06 16:55:47.541  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 16:55:47.541  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 16:55:47.551  1169  1169 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 16:55:47.551  1015  1452 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 16:55:47.551  1169  1169 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 16:55:47.551  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress
09-06 16:55:47.551  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,09-06 16:55:47.551  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 16:55:47.551  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-06 16:55:47.551  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 16:55:47.551  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 16:55:47.551  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 16:55:47.551  1015  1124 D SecContentProvider2: mCursor = null
,09-06 16:55:47.551  1015  1123 D WifiP2pService: DeviceAddress: 0a:76:28
,09-06 16:55:47.551  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-06 16:55:47.551  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-06 16:55:47.551  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
09-06 16:55:47.551  1015  1045 D WifiDisplayController:  secondary type: null
09-06 16:55:47.551  1015  1045 D WifiDisplayController:  wps: 0
09-06 16:55:47.551  1015  1045 D WifiDisplayController:  grpcapab: 0
09-06 16:55:47.551  1015  1045 D WifiDisplayController:  devcapab: 0
09-06 16:55:47.551  1015  1045 D WifiDisplayController:  status: 3
09-06 16:55:47.551  1015  1045 D WifiDisplayController:  wfdInfo: null
09-06 16:55:47.551  1015  1045 D WifiDisplayController:  groupownerAddress: null
09-06 16:55:47.551  1015  1045 D WifiDisplayController:  GOdeviceName: null
09-06 16:55:47.551  1015  1045 D WifiDisplayController:  interfaceAddress: 
09-06 16:55:47.551  1015  1045 D WifiDisplayController:  SConnectInfo : null
,09-06 16:55:47.631  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 16:55:47.631  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 16:55:47.631  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
09-06 16:55:47.631  1015  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
09-06 16:55:47.631  1015  1123 D WifiP2pService: InactiveState
09-06 16:55:47.631  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
,09-06 16:55:47.631  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
09-06 16:55:47.631  7332  7332 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 16:55:47.631  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
,09-06 16:55:47.631  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 16:55:47.631  1015  1028 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-06 16:55:47.631  1015  1028 I ActivityManager: Killing 7054:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,09-06 16:55:47.641  1015  1485 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 16:55:47.641  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 16:55:47.641  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:47.641  1015  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:47.641  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 16:55:47.641  1619  1619 I Hs20UtilService: Starting #12
,09-06 16:55:47.641  1619  1674 I Hs20UtilService: Message received 5011
,09-06 16:55:47.651  6637  6637 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 16:55:47.651  6637  6637 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 16:55:47.651  6637  6637 D SecurityLogAgent: StateMachine : Current State = 1
09-06 16:55:47.651  6637  6637 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 16:55:47.661  1015  1211 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 16:55:47.661  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 16:55:47.661  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:47.661  1015  1211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 16:55:47.661  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 16:55:47.661  6637  6637 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 16:55:47.661  6637  6637 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 16:55:47.661  6637  6637 D SecurityLogAgent: StateMachine : Current State = 1
09-06 16:55:47.661  6637  6637 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-06 16:55:47.661  1619  1619 I Hs20UtilService: Starting #13
,09-06 16:55:47.671  1619  1674 I Hs20UtilService: Message received 5011
,09-06 16:55:47.671  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 16:55:47.671  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 16:55:47.671  1015  1124 E WifiNative-wlan0: invaild command id : 215
,09-06 16:55:47.671  4098  4098 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 16:55:47.671  4098  4098 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 16:55:47.671  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 16:55:47.681  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 16:55:47.681  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 16:55:47.681  4098  4098 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 16:55:47.681  4098  4213 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 16:55:47.681   292   292 E SMD     : DCD OFF
,09-06 16:55:47.681  1015  1453 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-06 16:55:47.681  1015  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:47.681  1015  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:47.681  1015  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:47.681  1015  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:47.691  7395  7395 E Zygote  : MountEmulatedStorage()
,09-06 16:55:47.701  7395  7395 E Zygote  : v2
09-06 16:55:47.701  7395  7395 I libpersona: KNOX_SDCARD checking this for 10064
09-06 16:55:47.701  7395  7395 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:47.701  7395  7395 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 16:55:47.701  1015  1453 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7395 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 16:55:47.701  7395  7395 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 16:55:47.711  7395  7395 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 16:55:47.731  7395  7395 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:47.731  7395  7395 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:47.741  7395  7395 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-06 16:55:47.751  7395  7395 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 16:55:47.751  7395  7395 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 16:55:47.781  7395  7395 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 16:55:47.781  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-06 16:55:47.781  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:47.781  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:47.781  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:47.781  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:47.791  7412  7412 E Zygote  : MountEmulatedStorage(),
,09-06 16:55:47.791  7412  7412 E Zygote  : v2
09-06 16:55:47.791  7412  7412 I libpersona: KNOX_SDCARD checking this for 10065
09-06 16:55:47.791  7412  7412 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:47.791  1015  1028 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7412 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-06 16:55:47.801  7412  7412 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-06 16:55:47.801  1015  1028 I ActivityManager: Killing 6930:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-06 16:55:47.801  7412  7412 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 16:55:47.801  7412  7412 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 16:55:47.821  7412  7412 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:47.821  7412  7412 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:47.841  7412  7412 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 16:55:47.851  1015  1211 I ActivityManager: Killing 7071:com.android.bluetooth/1002 (adj 15): empty #21
,09-06 16:55:48.411   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 16:55:48.721  7332  7332 I wpa_supplicant: nl80211: Received scan results (19 BSSes)
09-06 16:55:48.721  7332  7332 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 16:55:48.721  7332  7332 I wpa_supplicant: Trying to associate with SSID '4E47373030',
09-06 16:55:48.721  7332  7332 I wpa_supplicant: Trying to associate with  'G700'
09-06 16:55:48.721  7332  7332 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-06 16:55:48.721  7332  7332 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-06 16:55:48.731  1015  7387 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,09-06 16:55:48.741  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 16:55:48.741  1015  1124 D SecContentProvider2: mCursor = null
,09-06 16:55:48.911  7332  7332 E wpa_supplicant: Cmd 35605 not handled
,09-06 16:55:48.911  7332  7332 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 16:55:48.911  7332  7332 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
09-06 16:55:48.911  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 16:55:48.911  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 16:55:48.911  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 16:55:48.911  7332  7332 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-06 16:55:48.911  7332  7332 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-06 16:55:48.911  7332  7332 I wpa_supplicant: Associated with F4.99.3E
09-06 16:55:48.911  7332  7332 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 16:55:48.911  7332  7332 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-06 16:55:48.911  7332  7332 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-06 16:55:48.911  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 16:55:48.911  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 16:55:48.911  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 16:55:48.911  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true,
09-06 16:55:48.911  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-06 16:55:48.911  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,09-06 16:55:48.911  1015  1128 E Tethering: No numeric data
,09-06 16:55:48.911  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 16:55:48.911  1015  1128 D Tethering: clearTetheredNotification()
,09-06 16:55:48.911  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 16:55:48.911  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:55:48.921  1169  1169 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 16:55:48.921  1169  1169 D HotspotTile: updateTetherState():false, false
09-06 16:55:48.921  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 16:55:48.921  1015  1124 D SecContentProvider2: mCursor = null
,09-06 16:55:48.921  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 16:55:48.921  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 16:55:48.921  7332  7332 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 16:55:48.921  7332  7332 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-06 16:55:48.921  7332  7332 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-06 16:55:48.921  7332  7332 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-06 16:55:48.921  1015  1121 V NetworkStats: performPollLocked() took 6ms
09-06 16:55:48.921  7332  7332 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 16:55:48.921  7332  7332 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-06 16:55:48.921  7332  7332 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-06 16:55:48.921  7332  7332 I wpa_supplicant: Blacklist: Clear (temp) 
09-06 16:55:48.921  7332  7332 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-06 16:55:48.921  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:48.921  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 16:55:48.921  1015  1124 D SecContentProvider2: mCursor = null
09-06 16:55:48.921  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 16:55:48.921  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
09-06 16:55:48.921  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-06 16:55:48.931  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:48.931  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:55:48.931  1015  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-06 16:55:48.931  1015  1124 E WifiConfigStore: setLastSelectedConfiguration -1,
,09-06 16:55:48.931  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 16:55:48.931  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 16:55:48.941  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:48.941  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:48.941  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:48.941  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 16:55:48.941  1015  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-06 16:55:48.941  1015  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-06 16:55:48.941  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 16:55:48.941  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 16:55:48.941  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 16:55:48.941  1015  1452 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 16:55:48.941  1015  1452 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 16:55:48.951  1015  1452 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:48.951  1015  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:48.951  1015  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 16:55:48.951  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 16:55:48.951  1619  1619 I Hs20UtilService: Starting #14
09-06 16:55:48.951  1619  1674 I Hs20UtilService: Message received 5007
,09-06 16:55:48.951  4098  4098 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 16:55:48.951  4098  4098 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 16:55:48.961  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 16:55:48.961  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 16:55:48.961   277  1013 D CommandListener: Setting iface cfg
09-06 16:55:48.961  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 16:55:48.961  4098  4098 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 16:55:48.961  4098  4213 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 16:55:48.971  1015  1124 E WifiStateMachine: Start Dhcp Watchdog 2
,09-06 16:55:48.971  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 16:55:48.971  1015  1124 D SecContentProvider2: mCursor = null
,09-06 16:55:48.971  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 16:55:48.971  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 16:55:48.971  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:48.971  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:48.971  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 16:55:48.981  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-06 16:55:48.981  1015  1124 E WifiNative-wlan0: do suspend false,
,09-06 16:55:48.981  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
,09-06 16:55:48.991  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 16:55:48.991  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 16:55:48.991  1015  1124 D SecContentProvider2: mCursor = null
,09-06 16:55:49.161  1015  1211 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 16:55:49.161  1015  1211 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 16:55:49.161  1015  1211 D SecContentProvider2: mCursor = null
,09-06 16:55:49.161  1015  1211 D WifiService: setWifiEnabled: false pid=6847, uid=10171
,09-06 16:55:49.161  1015  1211 D SettingsProvider: name = wifi_on
,09-06 16:55:49.161  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 16:55:49.181  1015  1124 E WifiNative-wlan0: do suspend true,
,09-06 16:55:49.201  1015  1123 D WifiP2pService: InactiveState{ what=143375 },
09-06 16:55:49.201   277  1013 D CommandListener: Clearing all IP addresses on wlan0,
09-06 16:55:49.201  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
09-06 16:55:49.211  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 16:55:49.211  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 16:55:49.211  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 16:55:49.211  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-06 16:55:49.211   277  1013 E Netd    : no such netId 503
09-06 16:55:49.211  7430  7430 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-06 16:55:49.221  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-06 16:55:49.221  1015  1123 D WifiP2pService: InactiveState{ what=131204 }
09-06 16:55:49.221  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 16:55:49.221  1015  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
09-06 16:55:49.221  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.221  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.221  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.221  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.221  1015  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 16:55:49.221  7430  7430 I dhcpcd  : version 5.5.6 starting
,09-06 16:55:49.221  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-06 16:55:49.221  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:49.221  1015  1126 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
09-06 16:55:49.221  1015  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-06 16:55:49.231  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 16:55:49.221  1015  1126 V NetworkStats: updateIfacesLocked()
09-06 16:55:49.231  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 16:55:49.221  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
09-06 16:55:49.231  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 16:55:49.231  7430  7430 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
09-06 16:55:49.231  1015  1126 V NetworkStats: performPollLocked() took 5ms
09-06 16:55:49.231  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:55:49.241  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 16:55:49.241  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 16:55:49.241  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.241  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.241  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.241  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.241  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 16:55:49.241  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 16:55:49.241  1015  1015 D RttService: SCAN_AVAILABLE : 1
09-06 16:55:49.241  1015  1148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 16:55:49.251  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 16:55:49.251  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-06 16:55:49.251  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 16:55:49.251  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 16:55:49.251  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-06 16:55:49.261  1015  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,09-06 16:55:49.261  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
09-06 16:55:49.261  1015  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-06 16:55:49.261  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
09-06 16:55:49.261  1015  1123 D WifiP2pService: P2pDisablingState
09-06 16:55:49.261  1015  1126 D ConnectivityService: nai.networkMonitor.doQuit()
09-06 16:55:49.261  1015  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
09-06 16:55:49.261  1015  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-06 16:55:49.261  1015  1123 D WifiP2pService: p2p socket connection lost,
09-06 16:55:49.261  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 16:55:49.261  1015  1123 D WifiP2pService: P2pDisabledState
09-06 16:55:49.261  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-06 16:55:49.261  1015  1124 E WifiNative-wlan0: do suspend true
09-06 16:55:49.261  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-06 16:55:49.271  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-06 16:55:49.271  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 16:55:49.271  1015  1045 D WifiDisplayController: disconnect
09-06 16:55:49.271  1015  1045 D WifiDisplayController: updateConnection
09-06 16:55:49.271  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 16:55:49.271  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 16:55:49.271  1015  1453 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 16:55:49.271  1015  1453 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 16:55:49.271  1015  1453 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:49.271  1015  1453 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:49.271  1015  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
09-06 16:55:49.271  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 16:55:49.271  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-06 16:55:49.271  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 16:55:49.271  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 16:55:49.271  1619  1619 I Hs20UtilService: Starting #15
,09-06 16:55:49.271  1169  1169 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-06 16:55:49.271  1015  1496 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 16:55:49.271  1169  1169 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 16:55:49.281  4098  4098 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 16:55:49.281  4098  4098 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 16:55:49.281  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 16:55:49.281  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 16:55:49.281  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 16:55:49.281  1619  1674 I Hs20UtilService: Message received 5007
,09-06 16:55:49.281  4098  4098 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 16:55:49.281  4098  4213 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 16:55:49.291  4098  4098 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 16:55:49.291  4098  4098 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 16:55:49.291  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 16:55:49.291   277  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-06 16:55:49.301  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 16:55:49.301  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 16:55:49.301  4098  4098 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 16:55:49.301  4098  4213 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-06 16:55:49.301  1015  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-06 16:55:49.301  1015  1123 D WifiP2pService: DefaultState{ what=143375 }
,09-06 16:55:49.301  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 16:55:49.301  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 16:55:49.301  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.301  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.301  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.301  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 16:55:49.301  7395  7395 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 16:55:49.301  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 16:55:49.301  7332  7332 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-06 16:55:49.301  7395  7395 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-06 16:55:49.301  7395  7395 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 16:55:49.311  7430  7430 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-06 16:55:49.311  7430  7430 E dhcpcd  : wlan0: sendmsg: Network is unreachable
09-06 16:55:49.311  7430  7430 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-06 16:55:49.311  7430  7430 I dhcpcd  : bssid match
,09-06 16:55:49.311  7430  7430 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,09-06 16:55:49.311  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 16:55:49.311  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 16:55:49.311  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.311  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.311  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 16:55:49.311  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 16:55:49.321  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 16:55:49.321  1015  1124 D SecContentProvider2: mCursor = null
,09-06 16:55:49.321  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 16:55:49.321  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 16:55:49.321  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.321  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.321  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.321  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 16:55:49.321  1169  1169 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 16:55:49.321  1169  1169 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-06 16:55:49.321  1169  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 16:55:49.321  1169  1169 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 16:55:49.321  1169  1169 D HotspotTile: onReceive : 0, 0
,09-06 16:55:49.321  4098  4098 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,09-06 16:55:49.331  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:49.331  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:49.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:49.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:49.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:49.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:49.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:49.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:49.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:55:49.331  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:49.331  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:55:49.331  7412  7412 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-06 16:55:49.331  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:49.331  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:49.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:49.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:49.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:49.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:49.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:49.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:49.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:55:49.331  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 16:55:49.331  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:55:49.331  1015  1452 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 16:55:49.331  1015  1452 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 16:55:49.331  1015  1452 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:49.331  1015  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:49.331  1015  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 16:55:49.341  1619  1619 I Hs20UtilService: Starting #16
09-06 16:55:49.341  4098  4098 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 16:55:49.341  4098  4098 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 16:55:49.341  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 16:55:49.341  1619  1674 I Hs20UtilService: Message received 5007
,09-06 16:55:49.341  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 16:55:49.341  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 16:55:49.341  4098  4098 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 16:55:49.341  4098  4213 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 16:55:49.351  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 16:55:49.351  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 16:55:49.351  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:49.351  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:49.351  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 16:55:49.351  1619  1619 I Hs20UtilService: Starting #17
,09-06 16:55:49.351  6637  6637 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 16:55:49.351  6637  6637 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 16:55:49.351  6637  6637 D SecurityLogAgent: StateMachine : Current State = 1
09-06 16:55:49.351  6637  6637 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 16:55:49.351  1619  1674 I Hs20UtilService: Message received 5011
,09-06 16:55:49.361  7430  7430 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,09-06 16:55:49.411   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-06 16:55:49.451  7332  7332 I wpa_supplicant: Blacklist: Clear (all) 
09-06 16:55:49.451  7430  7430 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,09-06 16:55:49.561  7332  7332 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,09-06 16:55:49.561  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,09-06 16:55:49.561  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-06 16:55:49.561  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 16:55:49.581  7332  7332 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
09-06 16:55:49.581  7332  7332 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,09-06 16:55:49.581  7332  7332 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-06 16:55:49.581  7332  7332 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-06 16:55:49.581  7332  7332 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-06 16:55:49.581  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 16:55:49.581  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 16:55:49.591  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 16:55:49.591  1015  1128 D Tethering: InitialState.processMessage what=4
09-06 16:55:49.591  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 16:55:49.591  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 16:55:49.591  1015  1128 E Tethering: No numeric data
,09-06 16:55:49.591  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 16:55:49.591  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 16:55:49.591  1015  1128 D Tethering: clearTetheredNotification()
09-06 16:55:49.591  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 16:55:49.591  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 16:55:49.591  1169  1169 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-06 16:55:49.591  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 16:55:49.591  1169  1169 D HotspotTile: updateTetherState():false, false
09-06 16:55:49.591  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:55:49.591  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 16:55:49.591  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 16:55:49.591  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 16:55:49.591  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:49.591  1015  1121 V NetworkStats: performPollLocked() took 5ms
09-06 16:55:49.601  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:55:49.601  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:55:49.831  7332  7332 I wpa_supplicant: Blacklist: Clear (all) ,
,09-06 16:55:49.901  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 16:55:49.901  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 16:55:49.901  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,09-06 16:55:49.951  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-06 16:55:49.951  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-06 16:55:49.951  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 16:55:49.951  7332  7332 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-06 16:55:49.961  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
09-06 16:55:49.961  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 16:55:49.981  1015  1040 W ProcessCpuTracker: Skipping unknown process pid 7332
,09-06 16:55:49.981  7014  7014 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,09-06 16:55:49.991  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 16:55:49.991  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 16:55:49.991  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.991  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.991  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:55:49.991  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 16:55:49.991  1169  1169 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 16:55:49.991  1169  1169 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-06 16:55:49.991  1169  1169 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 16:55:50.001  1169  1169 D HotspotTile: onReceive : 1, 0
,09-06 16:55:50.001  1169  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 16:55:50.001  1951  2166 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 16:55:50.001  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:50.001  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:50.001  4098  4098 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 16:55:50.011  1015  1478 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 16:55:50.011  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 16:55:50.011  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:50.011  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:50.011  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 16:55:50.011  1619  1619 I Hs20UtilService: Starting #18
,09-06 16:55:50.011  1619  1674 I Hs20UtilService: Message received 5011
,09-06 16:55:50.011  6637  6637 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 16:55:50.011  6637  6637 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 16:55:50.011  6637  6637 D SecurityLogAgent: StateMachine : Current State = 1
09-06 16:55:50.011  6637  6637 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 16:55:50.181  1015  1027 I ActivityManager: Killing 6954:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-06 16:55:50.431   277  1007 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-06 16:55:50.431  1015  1042 D Tethering: interfaceRemoved wlan0
,09-06 16:55:50.441  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-06 16:55:50.681  1015  1042 D Tethering: interfaceRemoved p2p0
,09-06 16:55:50.681  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-06 16:55:50.681   292   292 E SMD     : DCD OFF,
,09-06 16:55:51.561  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-06 16:55:52.171  6847  6901 D BluetoothAdapter: enable()
,09-06 16:55:52.171  1015  1478 W ActivityManager: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,09-06 16:55:52.171  1015  1478 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
09-06 16:55:52.171  1015  1478 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 16:55:52.171  1015  1478 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 16:55:52.171  1015  1478 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-06 16:55:52.171  1015  1478 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-06 16:55:52.171  1015  1478 W BluetoothManagerService: ,	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-06 16:55:52.171  1015  1478 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
09-06 16:55:52.171  1015  1478 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 16:55:52.171  1015  1478 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,09-06 16:55:52.171  1015  1478 D SettingsProvider: name = bluetooth_on,
,09-06 16:55:52.181  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-06 16:55:52.181  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 16:55:52.181  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
09-06 16:55:52.181  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-06 16:55:52.191  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 16:55:52.191  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:52.191  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:52.191  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:52.211  1015  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7461 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,09-06 16:55:52.211  7461  7461 E Zygote  : MountEmulatedStorage(),
09-06 16:55:52.211  7461  7461 I libpersona: KNOX_SDCARD checking this for 1002
,09-06 16:55:52.211  7461  7461 E Zygote  : v2
09-06 16:55:52.211  7461  7461 I libpersona: KNOX_SDCARD not a persona
09-06 16:55:52.211  7461  7461 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-06 16:55:52.211  7461  7461 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-06 16:55:52.221  7461  7461 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 16:55:52.261  7461  7461 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:52.261  7461  7461 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:52.281  7461  7461 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-06 16:55:52.281  7461  7461 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 16:55:52.311  7461  7461 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-06 16:55:52.351  7461  7461 D BtSettings.ProfileConfig: Adding GattService
,09-06 16:55:52.351  7461  7461 D BtSettings.ProfileConfig: Adding HeadsetService
,09-06 16:55:52.351  7461  7461 D BtSettings.ProfileConfig: Adding A2dpService
09-06 16:55:52.351  7461  7461 D BtSettings.ProfileConfig: Adding HidService
,09-06 16:55:52.351  1015  3370 D SSRM:n  : SIOP:: AP = 320
09-06 16:55:52.351  7461  7461 D BtSettings.ProfileConfig: Adding HealthService
09-06 16:55:52.351  7461  7461 D BtSettings.ProfileConfig: Adding PanService
,09-06 16:55:52.351  7461  7461 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-06 16:55:52.351  7461  7461 D BtSettings.ProfileConfig: Adding SapService
09-06 16:55:52.351  7461  7461 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-06 16:55:52.351  7461  7461 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-06 16:55:52.351  7461  7461 D BtSettings.ProfileConfig: Adding SapClientService
,09-06 16:55:52.351  7461  7461 D BtSettings.ProfileConfig: Adding HidDevService
09-06 16:55:52.351  7461  7461 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-06 16:55:52.351  1015  1485 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-06 16:55:52.351  1015  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:52.351  1015  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 16:55:52.351  1015  1485 D SettingsProvider: selectionArgs: false
09-06 16:55:52.351  1015  1485 D SettingsProvider: selectionArgs: 1002
09-06 16:55:52.351  1015  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:52.351  1015  1485 D SettingsProvider: ret = -1
,09-06 16:55:52.351  1015  1213 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-06 16:55:52.351  1015  1213 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:52.351  1015  1213 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:52.351  1015  1213 D SettingsProvider: selectionArgs: false
09-06 16:55:52.351  1015  1213 D SettingsProvider: selectionArgs: 1002
,09-06 16:55:52.351  1015  1213 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:52.351  1015  1213 D SettingsProvider: ret = -1
09-06 16:55:52.351  1015  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-06 16:55:52.351  1015  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 16:55:52.351  1015  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:52.351  1015  1495 D SettingsProvider: selectionArgs: false
09-06 16:55:52.351  1015  1495 D SettingsProvider: selectionArgs: 1002
09-06 16:55:52.351  1015  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 16:55:52.361  1015  1495 D SettingsProvider: ret = -1
09-06 16:55:52.361  1015  4377 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,09-06 16:55:52.361  1015  4377 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:52.361  1015  4377 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:52.361  1015  4377 D SettingsProvider: selectionArgs: false
09-06 16:55:52.361  1015  4377 D SettingsProvider: selectionArgs: 1002
09-06 16:55:52.361  1015  4377 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 16:55:52.361  1015  4377 D SettingsProvider: ret = -1
09-06 16:55:52.361  1015  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-06 16:55:52.361  1015  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:52.361  1015  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 16:55:52.361  1015  1478 D SettingsProvider: selectionArgs: false
09-06 16:55:52.361  1015  1478 D SettingsProvider: selectionArgs: 1002
,09-06 16:55:52.361  1015  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:52.361  1015  1478 D SettingsProvider: ret = -1
09-06 16:55:52.361  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,09-06 16:55:52.361  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:52.361  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:52.361  1015  1028 D SettingsProvider: selectionArgs: false
09-06 16:55:52.361  1015  1028 D SettingsProvider: selectionArgs: 1002
09-06 16:55:52.361  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:52.361  1015  1028 D SettingsProvider: ret = -1
09-06 16:55:52.361  1015  1496 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-06 16:55:52.361  1015  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:52.361  1015  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 16:55:52.361  1015  1496 D SettingsProvider: selectionArgs: false
09-06 16:55:52.361  1015  1496 D SettingsProvider: selectionArgs: 1002
09-06 16:55:52.361  1015  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:52.361  1015  1496 D SettingsProvider: ret = -1
09-06 16:55:52.361  1015  1453 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-06 16:55:52.361  1015  1453 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:52.361  1015  1453 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:52.361  1015  1453 D SettingsProvider: selectionArgs: false
09-06 16:55:52.361  1015  1453 D SettingsProvider: selectionArgs: 1002
09-06 16:55:52.361  1015  1453 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:52.361  1015  1453 D SettingsProvider: ret = -1
09-06 16:55:52.361  1015  1452 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-06 16:55:52.361  1015  1452 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:52.361  1015  1452 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 16:55:52.361  1015  1452 D SettingsProvider: selectionArgs: false
09-06 16:55:52.361  1015  1452 D SettingsProvider: selectionArgs: 1002
09-06 16:55:52.361  1015  1452 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 16:55:52.361  1015  1452 D SettingsProvider: ret = -1
09-06 16:55:52.361  1015  1211 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,09-06 16:55:52.361  1015  1211 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
09-06 16:55:52.361  1015  1211 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:52.361  1015  1211 D SettingsProvider: selectionArgs: false
09-06 16:55:52.361  1015  1211 D SettingsProvider: selectionArgs: 1002
09-06 16:55:52.361  1015  1211 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:52.361  1015  1211 D SettingsProvider: ret = -1
09-06 16:55:52.361  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-06 16:55:52.361  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:52.361  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:52.361  1015  1027 D SettingsProvider: selectionArgs: false
09-06 16:55:52.361  1015  1027 D SettingsProvider: selectionArgs: 1002
09-06 16:55:52.361  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:52.361  1015  1027 D SettingsProvider: ret = -1
09-06 16:55:52.361  1015  4041 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-06 16:55:52.361  1015  4041 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:52.361  1015  4041 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:52.361  1015  4041 D SettingsProvider: selectionArgs: false
09-06 16:55:52.361  1015  4041 D SettingsProvider: selectionArgs: 1002
09-06 16:55:52.361  1015  4041 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:52.361  1015  4041 D SettingsProvider: ret = -1
,09-06 16:55:52.391  7461  7461 D BluetoothAdapterState: make,
,09-06 16:55:52.391  7461  7461 I bluedroid: init,
,09-06 16:55:52.391  7461  7476 I BluetoothAdapterState: Entering OffState
,09-06 16:55:52.391  7461  7461 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-06 16:55:52.391  7461  7461 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-06 16:55:52.401  7461  7461 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 16:55:52.401  7461  7461 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-06 16:55:52.401  7461  7461 E bt-btif : btif_fetch_local_ble_random_bdaddr
,09-06 16:55:52.401  7461  7461 I bluedroid: get_profile_interface socket
09-06 16:55:52.401  7461  7461 I bluedroid: get_profile_interface map_client
09-06 16:55:52.401  7461  7479 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting,
,09-06 16:55:52.401  7461  7461 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-06 16:55:52.411  7461  7479 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-06 16:55:52.411  7461  7479 E BluetoothServiceJni: populateRssiValuesNative
09-06 16:55:52.411  7461  7461 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 16:55:52.411  7461  7479 I bluedroid: getModelRssiValues
09-06 16:55:52.411  7461  7479 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 16:55:52.411  7461  7479 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 16:55:52.411  1015  1211 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 16:55:52.411  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 16:55:52.411  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:52.411  1015  1211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 16:55:52.411  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:52.411  1015  1015 D SettingsProvider: name = bluetooth_name
,09-06 16:55:52.411  7461  7479 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-06 16:55:52.421  7461  7475 I bluedroid: config_hci_snoop_log
,09-06 16:55:52.421  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-06 16:55:52.421  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,09-06 16:55:52.421  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-06 16:55:52.421  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-06 16:55:52.421  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 16:55:52.431  7461  7461 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-06 16:55:52.441  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 16:55:52.441  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 16:55:52.441  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-06 16:55:52.441  7461  7476 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-06 16:55:52.441  7461  7476 D BluetoothAdapterProperties: Setting state to 11
,09-06 16:55:52.441  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 16:55:52.441  7461  7476 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 16:55:52.441  7461  7476 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-06 16:55:52.451  7461  7476 D BluetoothAdapterService: updateAdapterState state is 11
,09-06 16:55:52.451  7461  7476 D BluetoothAdapterService: Autoconnection is available 
09-06 16:55:52.451  7461  7476 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-06 16:55:52.451  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:55:52.451  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,09-06 16:55:52.461  7461  7476 D BluetoothSecureManager: getInstant: null
09-06 16:55:52.461  7461  7476 D BluetoothSecureManager: calling getMethod for getService
,09-06 16:55:52.461  7461  7476 D BluetoothSecureManager: calling getService
09-06 16:55:52.461  7461  7476 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@6cc6e0b
,09-06 16:55:52.461  1169  1169 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 16:55:52.461  1169  1169 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:52.461  1169  1169 D BluetoothTile:  getBluetoothState : 11
09-06 16:55:52.461  1870  1870 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 16:55:52.461  1015  1453 D BluetoothSecureManagerService: isSecureModeEnabled
,09-06 16:55:52.461  1015  1453 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-06 16:55:52.461  7461  7476 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 16:55:52.461  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 16:55:52.461  7461  7476 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-06 16:55:52.461  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 16:55:52.461  1015  1496 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 16:55:52.471  7461  7476 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-06 16:55:52.471  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 16:55:52.471  4098  4098 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:55:52.471  7461  7476 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-06 16:55:52.471  1015  1453 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-06 16:55:52.471  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 16:55:52.471  7461  7476 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-06 16:55:52.471  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-06 16:55:52.471  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 16:55:52.471  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 16:55:52.471  7461  7476 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-06 16:55:52.471  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 16:55:52.471  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 16:55:52.471  7461  7476 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-06 16:55:52.471  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 16:55:52.471  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:52.471  7461  7476 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-06 16:55:52.471  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 16:55:52.471  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 16:55:52.471  1169  1728 D BluetoothTile:  handleUpdatestate:false name:null
09-06 16:55:52.471  1169  1728 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-06 16:55:52.471  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:52.481  7461  7476 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-06 16:55:52.481  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 16:55:52.481  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:52.481  7461  7476 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 16:55:52.481  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 16:55:52.481  7461  7476 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-06 16:55:52.481  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 16:55:52.481  7461  7476 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-06 16:55:52.481  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-06 16:55:52.481  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:52.481  4098  4098 D BluetoothNotiBroadcastReceiver: onReceive
09-06 16:55:52.481  7461  7476 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-06 16:55:52.491  7461  7476 D BluetoothBondStateMachine: make
,09-06 16:55:52.491  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 16:55:52.491  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 16:55:52.491  7461  7476 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-06 16:55:52.501  7461  7482 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 16:55:52.501  1015  4377 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:52.501  1015  4377 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-06 16:55:52.501  1169  1169 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:52.501  1169  1169 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-06 16:55:52.501  1015  4377 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:52.501  1015  4377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:52.501  1015  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:52.501  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 16:55:52.501  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 16:55:52.501  7461  7476 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 16:55:52.501  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-06 16:55:52.501  7461  7461 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 16:55:52.501  7461  7461 D BtGatt.GattService: Received start request. Starting profile...
09-06 16:55:52.501  7461  7461 D BtGatt.GattService: start()
09-06 16:55:52.501  7461  7461 D BtGatt.GattService: start()
09-06 16:55:52.501  7461  7461 I bluedroid: get_profile_interface gatt
,09-06 16:55:52.501  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
09-06 16:55:52.501  7461  7461 D BtGatt.AdvertiseManager: advertise manager created
09-06 16:55:52.501  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:52.501  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:52.501  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:52.501  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:52.511  7484  7484 E Zygote  : MountEmulatedStorage()
09-06 16:55:52.521  7484  7484 E Zygote  : v2
09-06 16:55:52.521  7484  7484 I libpersona: KNOX_SDCARD checking this for 10055
09-06 16:55:52.521  7484  7484 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:52.521  7484  7484 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-06 16:55:52.521  1015  1027 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7484 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-06 16:55:52.521  1015  1213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:52.521  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-06 16:55:52.521  7484  7484 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 16:55:52.521  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:52.521  1015  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:52.521  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 16:55:52.521  7484  7484 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 16:55:52.521  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService,
,09-06 16:55:52.521  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 16:55:52.521  1015  1211 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:52.521  7461  7476 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 16:55:52.521  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 16:55:52.531  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:52.531  1015  1211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:52.531  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:52.531  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-06 16:55:52.531  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 16:55:52.531  7461  7476 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-06 16:55:52.531  1015  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:52.531  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 16:55:52.531  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:52.531  1015  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:52.531  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 16:55:52.531  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-06 16:55:52.531  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 16:55:52.531  7461  7476 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 16:55:52.531  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:52.531  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 16:55:52.531  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:52.531  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:52.531  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:52.531  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-06 16:55:52.541  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-06 16:55:52.541  7461  7476 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 16:55:52.541  1015  1211 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:52.541  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 16:55:52.541  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:52.541  1015  1211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:52.541  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:52.541  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 16:55:52.541  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 16:55:52.541  7461  7476 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 16:55:52.541  1015  4041 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:52.541  1015  4041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 16:55:52.541  1015  4041 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:52.541  1015  4041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:52.541  1015  4041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:52.541  7461  7461 D BtGatt.GattService: mStartError = false
09-06 16:55:52.541  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
09-06 16:55:52.541  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-06 16:55:52.541  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 16:55:52.541  7461  7476 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 16:55:52.541  1015  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:52.541  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 16:55:52.551  7461  7461 D HeadsetService: Received start request. Starting profile...
09-06 16:55:52.551  7461  7461 D HeadsetService: start()
09-06 16:55:52.551  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:52.551  1015  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:52.551  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 16:55:52.551  7461  7461 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 16:55:52.551  7461  7461 D HeadsetStateMachine: make
09-06 16:55:52.551  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 16:55:52.551  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 16:55:52.551  7461  7476 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 16:55:52.551  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 16:55:52.551  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 16:55:52.551  7461  7476 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 16:55:52.551  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 16:55:52.551  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 16:55:52.551  7461  7476 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 16:55:52.551  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 16:55:52.551  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 16:55:52.551  7461  7476 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 16:55:52.551  7461  7476 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-06 16:55:52.551  7461  7461 E HeadsetStateMachine: # of Max HF connection is 2
,09-06 16:55:52.561  1015  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-06 16:55:52.561  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-06 16:55:52.561  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:52.561  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:52.561  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 16:55:52.561  1015  1452 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-06 16:55:52.561  1015  1452 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:52.561  1015  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-06 16:55:52.561  1015  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:52.561  1015  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 16:55:52.561  7461  7461 I bluedroid: get_profile_interface handsfree,
09-06 16:55:52.561  7484  7484 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 16:55:52.561  7484  7484 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:52.581  7461  7461 I DualScoManager: Instantiating Dual Sco Manager
09-06 16:55:52.581  7461  7461 I DualScoManager: Set HeadsetServiceHelper
,09-06 16:55:52.591  7461  7461 D BluetoothAtMessage: createCMTIContentObservers
09-06 16:55:52.591  1015  1496 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-06 16:55:52.591  1015  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:52.591  1015  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:52.591  1015  1496 D SettingsProvider: selectionArgs: false
09-06 16:55:52.591  1015  1496 D SettingsProvider: selectionArgs: 1002
09-06 16:55:52.591  1015  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:52.591  1015  1496 D SettingsProvider: ret = -1
,09-06 16:55:52.591  7461  7498 D HeadsetStateMachine: Enter Disconnected: -2
09-06 16:55:52.591  7461  7461 D HeadsetService: mStartError = false
09-06 16:55:52.591  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:52.591  7461  7461 D A2dpService: Received start request. Starting profile...
09-06 16:55:52.591  7461  7498 D HeadsetStateMachine: Clear mHeadsetBrsf
09-06 16:55:52.591  7461  7461 D A2dpService: start()
,09-06 16:55:52.591  7461  7498 D HeadsetStateMachine: map size, before remove : 0
,09-06 16:55:52.591  7461  7498 D HeadsetStateMachine: map size, after remove: 0
09-06 16:55:52.591  7461  7461 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-06 16:55:52.601  7484  7484 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-06 16:55:52.601  7461  7461 I bluedroid: get_profile_interface avrcp
,09-06 16:55:52.601  7461  7461 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 16:55:52.601  7461  7461 D Avrcp   : Initialize Media Controller
,09-06 16:55:52.601  7461  7461 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-06 16:55:52.601  7461  7461 E Avrcp   : getActiveSessions
,09-06 16:55:52.611  7461  7461 D Avrcp   : pick active media Controller
09-06 16:55:52.611  7461  7461 D Avrcp   : Get the active Media Controller 
,09-06 16:55:52.621  7461  7461 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-06 16:55:52.621  7461  7504 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-06 16:55:52.621  7461  7461 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 16:55:52.621  7461  7461 D A2dpStateMachine: make
,09-06 16:55:52.631  7461  7461 I bluedroid: get_profile_interface a2dp
,09-06 16:55:52.631  7461  7506 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-06 16:55:52.631  7461  7461 E bt-btif : warning : media task started media_task_refcnt 1 
,09-06 16:55:52.631  7461  7461 D A2dpService: mStartError = false
09-06 16:55:52.631  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:52.631  7461  7461 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 16:55:52.631  7461  7461 D HidService: Received start request. Starting profile...
09-06 16:55:52.631  7461  7461 D HidService: start()
09-06 16:55:52.631  7461  7461 I bluedroid: get_profile_interface hidhost
09-06 16:55:52.631  7484  7484 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
09-06 16:55:52.631  7461  7461 D HidService: setHidService(): set to: null
09-06 16:55:52.631  7461  7461 D HidService: mStartError = false
09-06 16:55:52.631  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:52.631  7461  7461 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 16:55:52.631  7484  7484 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-06 16:55:52.631  7484  7484 D UserAnalysis: Create SecureDbHelper
09-06 16:55:52.631  7461  7505 D A2dpStateMachine: Enter Disconnected: -2
,09-06 16:55:52.641  7461  7461 D HealthService: Received start request. Starting profile...
09-06 16:55:52.641  7461  7461 D HealthService: start()
,09-06 16:55:52.641  7461  7461 I bluedroid: get_profile_interface health
09-06 16:55:52.641  7461  7461 D HealthService: mStartError = false
09-06 16:55:52.641  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:52.641  7461  7461 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 16:55:52.641  7484  7484 D IntelligenceServiceApplication: onCreate()
09-06 16:55:52.641  7461  7461 D PanService: Received start request. Starting profile...
09-06 16:55:52.641  7461  7461 D PanService: start()
09-06 16:55:52.641  7461  7461 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 16:55:52.641  7461  7461 I bluedroid: get_profile_interface pan
,09-06 16:55:52.641  7461  7461 D PanService: mStartError = false
09-06 16:55:52.641  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:52.641  7461  7504 D BluetoothMediaBrowser: no now playing list
,09-06 16:55:52.641  7461  7504 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-06 16:55:52.651  7461  7461 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-06 16:55:52.651  7461  7461 D BluetoothMapService: Received start request. Starting profile...
,09-06 16:55:52.651  7461  7461 D BluetoothMapService: start()
,09-06 16:55:52.651  1015  1452 I ActivityManager: Killing 7089:com.sec.pcw.device/1000 (adj 15): empty #21
,09-06 16:55:52.651  7484  7484 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-06 16:55:52.651  7461  7461 D BluetoothMapService: mStartError = false
09-06 16:55:52.651  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:52.651  7461  7461 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-06 16:55:52.661  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-06 16:55:52.661  7461  7461 D SapService: Received start request. Starting profile...
09-06 16:55:52.661  7461  7461 D SapService: start()
09-06 16:55:52.661  7461  7461 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-06 16:55:52.661  7461  7461 I bluedroid: get_profile_interface sap
09-06 16:55:52.661  7461  7461 D SapService: mStartError = false
09-06 16:55:52.661  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:52.661  7461  7461 D HeadsetStateMachine: Try to query the phonestate on bind
09-06 16:55:52.661  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-06 16:55:52.661  1446  1465 I Telecom : BluetoothPhoneService: queryPhoneState
,09-06 16:55:52.661  1446  1446 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-06 16:55:52.661  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 16:55:52.661  1446  1465 I Telecom : BluetoothPhoneService: Result of Message : true
,09-06 16:55:52.661  7461  7461 D HeadsetStateMachine: Proxy object connected
,09-06 16:55:52.661  7461  7461 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-06 16:55:52.661  7461  7461 D HeadsetPhoneState: sendDeviceDataStateChanged
09-06 16:55:52.661  7461  7498 D HeadsetStateMachine: Disconnected process message: 11
09-06 16:55:52.661  7461  7461 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-06 16:55:52.661  7461  7461 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-06 16:55:52.661  7461  7461 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 16:55:52.661  7461  7461 D BluetoothA2dp: Proxy object connected
09-06 16:55:52.661  7461  7461 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-06 16:55:52.661  7461  7461 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-06 16:55:52.661  7461  7461 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-06 16:55:52.661  7461  7461 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-06 16:55:52.661  7461  7461 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-06 16:55:52.661  7461  7498 D HeadsetStateMachine: Disconnected process message: 18
09-06 16:55:52.661  7461  7498 D HeadsetStateMachine: Disconnected process message: 10
,09-06 16:55:52.671  7461  7498 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 16:55:52.671  7461  7498 D HeadsetStateMachine: Disconnected process message: 11
,09-06 16:55:52.671  7484  7484 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-06 16:55:52.671  1015  1496 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-06 16:55:52.671  1015  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:52.671  1015  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:52.671  1015  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:52.671  1015  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:52.691  7511  7511 E Zygote  : MountEmulatedStorage(),
09-06 16:55:52.691  7511  7511 E Zygote  : v2
09-06 16:55:52.691  7511  7511 I libpersona: KNOX_SDCARD checking this for 10105
09-06 16:55:52.691  7511  7511 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:52.691  1015  1496 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7511 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,09-06 16:55:52.691  7511  7511 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 16:55:52.691  7511  7511 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 16:55:52.691  7511  7511 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 16:55:52.711  7511  7511 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:52.721  7511  7511 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:52.721  7461  7461 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-06 16:55:52.721  7461  7461 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-06 16:55:52.731  7461  7476 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-06 16:55:52.731  7461  7476 I bluedroid: enable
,09-06 16:55:52.731  7461  7476 I bt_hci_bdroid: init
,09-06 16:55:52.741  7461  7527 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-06 16:55:52.741  7461  7476 I bt_vendor: bt-vendor : init
09-06 16:55:52.741  7461  7476 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 16:55:52.741  7461  7476 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 16:55:52.741  7461  7476 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
09-06 16:55:52.741  7461  7476 D bt_userial_mct: userial_init
,09-06 16:55:52.741  7461  7476 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 16:55:52.741  7461  7476 I bt_vendor: Starting hciattach daemon
09-06 16:55:52.741  7461  7476 I bt_vendor: try to set false
,09-06 16:55:52.741  7461  7476 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,09-06 16:55:52.741  7461  7476 I bt_vendor: Starting hciattach daemon
09-06 16:55:52.741  7461  7476 I bt_vendor: try to set true
,09-06 16:55:52.761  7531  7531 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-06 16:55:52.811  7537  7537 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-06 16:55:52.811  7538  7538 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-06 16:55:52.831  7542  7542 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 16:55:52.841  7543  7543 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-06 16:55:52.851  7544  7544 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 16:55:52.861  7545  7545 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-06 16:55:52.881   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 16:55:52.881   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 16:55:52.891  7511  7547 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 16:55:52.891   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-06 16:55:52.891   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 16:55:52.891  7511  7547 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-06 16:55:53.031  7511  7511 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 16:55:53.031  7511  7511 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 16:55:53.031  7511  7511 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 16:55:53.031  7511  7511 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 16:55:53.031  7511  7511 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.q.k.d(PG:583)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.q.e.b(PG:170)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 16:55:53.031  7511  7511 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 16:55:53.031  7511  7511 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 16:55:53.031  7511  7511 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 16:55:53.031  7511  7511 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 16:55:53.041  1015  1452 I ActivityManager: Killing 7106:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
09-06 16:55:53.041  1951  1951 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-06 16:55:53.051  1951  1951 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 16:55:53.081  7511  7559 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-06 16:55:53.091  7560  7560 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
09-06 16:55:53.101  7561  7561 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 16:55:53.121  1015  4377 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 16:55:53.121  1015  4377 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:53.121  1015  4377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:53.121  1015  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-06 16:55:53.151  7461  7476 I bt_vendor: bluetooth satus is on
,09-06 16:55:53.151  7461  7529 D bt_userial_mct: userial_open(port:0)
,09-06 16:55:53.151  7461  7529 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-06 16:55:53.151  7461  7529 I bt_vendor: Done intiailizing UART
,09-06 16:55:53.151  7461  7529 I bt_vendor: Done intiailizing UART
,09-06 16:55:53.151  7461  7529 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
09-06 16:55:53.151  7461  7529 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-06 16:55:53.161  7461  7527 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 16:55:53.161  7461  7527 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 16:55:53.161  7461  7527 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 16:55:53.161  7461  7527 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 16:55:53.161  7461  7527 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 16:55:53.161  7461  7527 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 16:55:53.161  7461  7527 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 16:55:53.161  7461  7527 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 16:55:53.161  7461  7527 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 16:55:53.161  7461  7527 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 16:55:53.161  7461  7527 I         : BTE_InitTraceLevels -- TRC_SAP
09-06 16:55:53.161  7461  7527 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 16:55:53.161  7461  7527 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 16:55:53.161  7461  7527 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 16:55:53.161  7461  7527 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 16:55:53.161  7461  7527 I         : BTE_InitTraceLevels -- TRC_BTIF
09-06 16:55:53.161  7461  7527 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
09-06 16:55:53.161  7461  7565 D bt_userial_mct: Entering userial_read_thread()
,09-06 16:55:53.251  7461  7527 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-06 16:55:53.261  7461  7527 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa42a0ed1 
,09-06 16:55:53.261  7461  7527 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa42a0ed1 
,09-06 16:55:53.271  7461  7479 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-06 16:55:53.281  7461  7479 E bt-btif : Calling BTA_HhEnable
,09-06 16:55:53.281  7461  7479 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-06 16:55:53.281  7461  7479 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-06 16:55:53.281  7461  7479 E BluetoothServiceJni: populateRssiValuesNative
09-06 16:55:53.281  7461  7479 I bluedroid: getModelRssiValues
,09-06 16:55:53.281  7461  7479 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 16:55:53.281  7461  7479 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 16:55:53.281  1015  1015 D SettingsProvider: name = bluetooth_name
,09-06 16:55:53.281  7461  7479 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-06 16:55:53.291  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:53.291  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:53.291  7461  7479 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-06 16:55:53.301  7461  7479 D BluetoothAdapterProperties: Scan Mode:20
,09-06 16:55:53.301  7461  7479 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 16:55:53.301  7461  7479 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,09-06 16:55:53.301  7461  7479 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-06 16:55:53.301  7461  7479 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-06 16:55:53.301  7461  7479 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-06 16:55:53.301  7461  7479 E bt-btif : btif_sock_init: !vhci_init
,09-06 16:55:53.301  7461  7479 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-06 16:55:53.301  7461  7565 E bt_mct  : hci lib postload completed
,09-06 16:55:53.301  7461  7479 D IOP_DB_BT: db_open: db_open : handle 3028193296l, read 13894 bytes onto local cache
09-06 16:55:53.311  7461  7479 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-06 16:55:53.311  7461  7479 D IOP_DB_BT: db_query: result 1
09-06 16:55:53.311  7461  7479 I         : iop_db_open: iop_db_open status 0
,09-06 16:55:53.311  7461  7479 D bte_conf: Device ID record 1 : primary
09-06 16:55:53.311  7461  7479 D bte_conf:   vendorId            = 0075
09-06 16:55:53.311  7461  7479 D bte_conf:   vendorIdSource      = 0001
09-06 16:55:53.311  7461  7479 D bte_conf:   product             = 0100
09-06 16:55:53.311  7461  7479 D bte_conf:   version             = 0200
09-06 16:55:53.311  7461  7479 D bte_conf:   clientExecutableURL = 
09-06 16:55:53.311  7461  7479 D bte_conf:   serviceDescription  = 
09-06 16:55:53.311  7461  7479 D bte_conf:   documentationURL    = 
09-06 16:55:53.311  7461  7479 D bte_conf: bte_load_did_conf no section named DID2.
09-06 16:55:53.311  7461  7479 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 16:55:53.311  7461  7476 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-06 16:55:53.311  7461  7476 D BluetoothAdapterProperties: ScanMode =  20
,09-06 16:55:53.311  7461  7476 D BluetoothAdapterProperties: State =  11
,09-06 16:55:53.311  1015  1478 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 16:55:53.311  7461  7476 D BluetoothAdapterProperties: Setting state to 12,
,09-06 16:55:53.311  7461  7476 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 16:55:53.321  7461  7479 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 16:55:53.321  7461  7479 D BluetoothAdapterProperties: Scan Mode:21
09-06 16:55:53.321  7461  7479 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 16:55:53.321  1015  1452 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-06 16:55:53.321  1015  1452 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:53.321  1015  1452 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:53.321  1015  1452 D SettingsProvider: selectionArgs: false
09-06 16:55:53.321  1015  1452 D SettingsProvider: selectionArgs: 1002
09-06 16:55:53.321  1015  1452 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:53.321  1015  1452 D SettingsProvider: ret = -1
,09-06 16:55:53.321  7461  7476 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 16:55:53.321  7461  7476 D BluetoothAdapterService: updateAdapterState state is 12
,09-06 16:55:53.321  1015  4041 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:53.321  1015  4041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 16:55:53.321  1015  4041 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:53.321  1015  4041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:53.321  1015  4041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:53.321  7461  7476 D BluetoothAdapterService: Autoconnection is available 
09-06 16:55:53.321  7461  7476 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-06 16:55:53.321  7461  7476 D BluetoothAdapterService: starting service from this receiver
,09-06 16:55:53.321  1015  1453 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:53.331  1015  1453 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 16:55:53.331  4098  4108 D BluetoothMap: onBluetoothStateChange: up=true
09-06 16:55:53.331  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-06 16:55:53.331  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:53.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:53.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:53.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:53.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:53.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:53.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:53.331  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:55:53.331  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-06 16:55:53.331  1015  1453 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:53.331  1015  1453 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:53.331  1015  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 16:55:53.331  7461  7476 I BluetoothAdapterState: Entering On State from state = 11
,09-06 16:55:53.341  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:53.341  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:53.341  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:53.341  1169  1977 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 16:55:53.341  1169  1977 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 16:55:53.341  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 16:55:53.341  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:55:53.341  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 16:55:53.341  7511  7522 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 16:55:53.341  7511  7522 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 16:55:53.341  1015  1044 D BluetoothPan: Binding service...
,09-06 16:55:53.351  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 16:55:53.351  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 16:55:53.351  4098  4115 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 16:55:53.351  4098  4115 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-06 16:55:53.351  7461  7461 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-06 16:55:53.351  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 16:55:53.351  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 16:55:53.351  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:53.351  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:53.351  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:53.351  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:53.351  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:55:53.351  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:53.351  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:53.351  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:55:53.351  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:55:53.361  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:53.361  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:53.361  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:53.361  4098  4098 D BluetoothA2dp: Proxy object connected
,09-06 16:55:53.361  4098  4098 D A2dpProfile: Bluetooth service connected
09-06 16:55:53.361  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 16:55:53.361  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 16:55:53.361  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 16:55:53.361  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 16:55:53.361  1479  1910 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 16:55:53.371  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 16:55:53.371  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 16:55:53.371  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:53.371  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:53.371  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:53.371  1479  1910 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 16:55:53.371  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 16:55:53.371  7461  7461 I BluetoothPbapService: Handler(): got msg=1
,09-06 16:55:53.371  4098  4108 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 16:55:53.371  4098  4098 D BluetoothMap: Proxy object connected
09-06 16:55:53.371  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 16:55:53.371  4098  4098 D MapProfile: Bluetooth service connected,
09-06 16:55:53.371  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-06 16:55:53.371  4098  4098 D BluetoothMap: getConnectedDevices()
09-06 16:55:53.381  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:53.381  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 16:55:53.381  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-06 16:55:53.381  1015  1485 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-06 16:55:53.381  4098  4108 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 16:55:53.381  1446  1463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 16:55:53.381  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 16:55:53.381  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 16:55:53.381  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:53.381  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:53.381  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:53.381  1446  1463 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 16:55:53.391  4098  4115 D BluetoothPan: Binding service...
,09-06 16:55:53.391  4098  4098 D HeadsetProfile: Bluetooth service connected
,09-06 16:55:53.391  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 16:55:53.391  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 16:55:53.391  7461  7570 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-06 16:55:53.391  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:53.391  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:53.391  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:53.391  7461  7480 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 16:55:53.391  4098  4098 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 16:55:53.391  4098  4098 D PanProfile: Bluetooth service connected
,09-06 16:55:53.391  7461  7570 D BluetoothSocket: bindListen(): myUserId = 0
09-06 16:55:53.391  7461  7570 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 16:55:53.401  1446  6978 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 16:55:53.401  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 16:55:53.401  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 16:55:53.401  7461  7570 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-06 16:55:53.401  7461  7570 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 16:55:53.401  7461  7570 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 16:55:53.401  7461  7570 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b323ebf
09-06 16:55:53.401  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:53.401  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:53.401  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:53.401  1446  6978 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 16:55:53.401  4098  4108 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 16:55:53.401  4098  4108 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 16:55:53.401  7461  7570 D BluetoothSocket: channel: 19
09-06 16:55:53.401  7461  7570 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-06 16:55:53.401  1951  2195 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 16:55:53.401  1951  2195 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 16:55:53.401  4098  4115 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 16:55:53.401  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-06 16:55:53.401  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 16:55:53.401  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:53.401  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 16:55:53.411  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:53.411  4098  4098 D BluetoothInputDevice: Proxy object connected
,09-06 16:55:53.411  4098  4098 D HidProfile: Bluetooth service connected
09-06 16:55:53.411  1446  1463 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 16:55:53.411  1446  1463 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 16:55:53.411  7461  7471 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 16:55:53.411  7461  7471 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 16:55:53.411  1460  1477 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 16:55:53.411  1460  1477 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 16:55:53.411  1479  1708 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 16:55:53.411  1479  1708 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 16:55:53.411  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 16:55:53.411  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 16:55:53.411  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 16:55:53.411  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 16:55:53.421  1015  1015 D BluetoothA2dp: Proxy object connected
,09-06 16:55:53.421  4098  4108 D Bluetoothsap: onBluetoothStateChange: up=true
09-06 16:55:53.421  4098  4108 D Bluetoothsap: Binding service...
,09-06 16:55:53.421  4098  4108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-06 16:55:53.421  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-06 16:55:53.421  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 16:55:53.421  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:53.421  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:53.421  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:53.431  4098  4098 D Bluetoothsap: BluetoothSAP Proxy object connected
09-06 16:55:53.431  4098  4098 D SapProfile: Bluetooth service connected
09-06 16:55:53.431  4098  4098 D Bluetoothsap: getConnectedDevices()
,09-06 16:55:53.431  4098  4108 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-06 16:55:53.431  6847  7317 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 16:55:53.431  6847  7317 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 16:55:53.431  1446  3309 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 16:55:53.431  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 16:55:53.431  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 16:55:53.431  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:53.431  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:53.431  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:53.441  1446  3309 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 16:55:53.441  4098  4115 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 16:55:53.441  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-06 16:55:53.441  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 16:55:53.441  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:53.441  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:53.441  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:53.441  4098  4098 D BluetoothPbap: Proxy object connected
,09-06 16:55:53.441  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-06 16:55:53.441  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 16:55:53.451  4098  4098 D PbapServerProfile: Bluetooth service connected
,09-06 16:55:53.451  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:55:53.451  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
,09-06 16:55:53.451  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 16:55:53.451  1446  1446 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@8c1cdeb, true
09-06 16:55:53.461  1169  1169 D BluetoothTile:  onBluetoothStateChange:
,09-06 16:55:53.461  1446  1446 D BluetoothHeadset: registerMessageListener
,09-06 16:55:53.461  1169  1169 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
09-06 16:55:53.461  1169  1169 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 16:55:53.461  1169  1169 D BluetoothTile:  getBluetoothState : 12
,09-06 16:55:53.461  1870  1870 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 16:55:53.461  1169  1728 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 16:55:53.461  1015  1211 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 16:55:53.471  1015  4377 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-06 16:55:53.471  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 16:55:53.471  4098  4098 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:55:53.471  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:55:53.471  1169  1728 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 16:55:53.471  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-06 16:55:53.471  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 16:55:53.471  7461  7471 D HeadsetService: registerMessageListener
09-06 16:55:53.471  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-06 16:55:53.471  7461  7471 D HeadsetService: registerMessageListener
09-06 16:55:53.471  7461  7498 D HeadsetStateMachine: Disconnected process message: 70
,09-06 16:55:53.471  7461  7498 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1a3d198c
09-06 16:55:53.471  1446  1446 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-06 16:55:53.471  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 16:55:53.481  1169  1728 D BluetoothTile:  handleUpdatestate:false name:null,
,09-06 16:55:53.481  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:53.481  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:53.481  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 16:55:53.481  7461  7573 D BluetoothMapMasInstance: set MAP SDP message type : 1
09-06 16:55:53.481  1446  1446 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-06 16:55:53.481  1446  1446 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-06 16:55:53.481  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-06 16:55:53.481  4098  4098 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-06 16:55:53.481  4098  4098 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,09-06 16:55:53.481  4098  4098 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-06 16:55:53.481  4098  4098 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-06 16:55:53.481  7461  7498 D HeadsetStateMachine: Disconnected process message: 9
,09-06 16:55:53.481  7461  7498 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-06 16:55:53.491  7461  7573 D BluetoothSocket: bindListen(): myUserId = 0
09-06 16:55:53.491  7461  7573 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 16:55:53.491  7461  7573 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-06 16:55:53.491  7461  7573 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 16:55:53.491  7461  7573 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-06 16:55:53.491  7461  7573 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1814b8d5
09-06 16:55:53.491  7461  7573 D BluetoothSocket: channel: 5
,09-06 16:55:53.501   285   687 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-06 16:55:53.501   285   687 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-06 16:55:53.501   285   687 V voice   : voice_set_parameters: exit with code(-2)
09-06 16:55:53.501   285   687 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-06 16:55:53.501   285   687 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-06 16:55:53.501   285   687 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-06 16:55:53.501   285   687 V audio_hw_primary: adev_set_parameters: exit
,09-06 16:55:53.501  7461  7498 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-06 16:55:53.501  4098  4098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 ,
,09-06 16:55:53.501  1015  4041 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 16:55:53.501  1015  4041 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 16:55:53.501  1015  4041 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:53.501  1015  4041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:53.501  1015  4041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 16:55:53.511  4098  4098 D DockEventReceiver: finishStartingService: stopping service
,09-06 16:55:53.511  4098  4098 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 16:55:53.521  1169  1169 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:53.521  1169  1169 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-06 16:55:53.521  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:53.521  7461  7461 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 16:55:53.521  1015  1211 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 16:55:53.521  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
09-06 16:55:53.521  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:53.521  1015  1211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:53.531  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:53.551  1951  1951 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 16:55:53.551  1015  4041 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 16:55:53.551  1015  4041 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 16:55:53.551  1015  4041 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:53.551  1015  4041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:53.551  1015  4041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:53.561  1015  1213 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 16:55:53.561  1951  7580 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 16:55:53.561  1951  1951 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 16:55:53.571  1015  4377 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 16:55:53.571  1015  4377 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:53.571  1015  4377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:53.571  1015  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:53.581  7461  7583 D BluetoothSocket: bindListen(): myUserId = 0
,09-06 16:55:53.581  7461  7583 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 16:55:53.591  7461  7583 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
,09-06 16:55:53.591  7461  7583 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 16:55:53.591  7461  7583 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 16:55:53.591  7461  7583 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f2346b7
,09-06 16:55:53.591  7461  7583 D BluetoothSocket: channel: 12
09-06 16:55:53.591  7461  7583 I BtOppRfcommListener: Accept thread started.
,09-06 16:55:53.601  1015  1211 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 16:55:53.601  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:53.601  1015  1211 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:53.601  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:53.611  1951  7580 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-06 16:55:53.681   292   292 E SMD     : DCD OFF
,09-06 16:55:55.181  6847  6901 D BluetoothAdapter: disable()
,09-06 16:55:55.181  1015  4041 D SettingsProvider: name = bluetooth_on
,09-06 16:55:55.191  7461  7476 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-06 16:55:55.191  7461  7476 D BluetoothAdapterProperties: Setting state to 13
09-06 16:55:55.191  7461  7476 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 16:55:55.191  7461  7476 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 16:55:55.191  7461  7476 D BluetoothAdapterService: updateAdapterState state is 13
,09-06 16:55:55.191  1015  1211 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 16:55:55.191  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 16:55:55.191  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:55.201  1015  1211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 16:55:55.201  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:55.201  7461  7476 D BluetoothAdapterService: Autoconnection is available 
09-06 16:55:55.201  7461  7476 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-06 16:55:55.201  7461  7476 D BluetoothAdapterService: terminating service from this receiver
,09-06 16:55:55.201  7461  7461 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-06 16:55:55.201  1015  4377 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 16:55:55.201  1015  4377 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:55.201  1015  4377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:55.201  1015  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:55.201  7461  7461 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2a1b0e24, channel: 19, state: LISTENING
09-06 16:55:55.201  7461  7461 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2a1b0e24, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b323ebf, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3fac2d8dmSocket: android.net.LocalSocket@1a3e8b42 impl:android.net.LocalSocketImpl@321b9753 fd:FileDescriptor[74]
09-06 16:55:55.201  7461  7461 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1a3e8b42 impl:android.net.LocalSocketImpl@321b9753 fd:FileDescriptor[74]
,09-06 16:55:55.201  7461  7476 D BluetoothAdapterProperties: onBluetoothDisable()
,09-06 16:55:55.211  7461  7476 D BluetoothAdapterProperties: mDiscovering is false
,09-06 16:55:55.211  1015  4041 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 16:55:55.211  7461  7476 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-06 16:55:55.211  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:55:55.211  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,09-06 16:55:55.221  1169  1169 D BluetoothTile:  onBluetoothStateChange:
,09-06 16:55:55.221  1169  1169 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 16:55:55.221  1169  1169 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:55.221  1169  1169 D BluetoothTile:  getBluetoothState : 13
,09-06 16:55:55.221  1015  1485 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 16:55:55.221  4098  4098 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:55:55.221  1169  1728 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 16:55:55.231  1870  1870 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 16:55:55.231  1015  1478 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 16:55:55.231  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 16:55:55.231  1169  1728 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 16:55:55.231  1169  1728 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 16:55:55.231  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 16:55:55.231  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:55.231  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:55.231  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:55.231  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:55.231  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:55.231  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:55.231  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:55.231  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:55:55.241  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 16:55:55.241  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:55:55.241  1015  1211 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 16:55:55.241  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 16:55:55.241  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 16:55:55.241  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:55:55.241  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:55:55.241  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:55:55.241  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:55:55.241  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 16:55:55.241  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:55:55.241  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:55:55.241  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:55:55.251  7461  7479 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 16:55:55.251  7461  7479 D BluetoothAdapterProperties: Scan Mode:20
,09-06 16:55:55.251  6847  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 16:55:55.251  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:55.251  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 16:55:55.251  1015  1211 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:55.251  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:55.261  7461  7476 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 16:55:55.261  7461  7476 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-06 16:55:55.261  4098  4098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 16:55:55.261  7461  7476 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-06 16:55:55.261  7461  7476 E bt-btif : cmd socket is not created
09-06 16:55:55.261  7461  7583 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-06 16:55:55.261  7461  7476 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 16:55:55.261  7461  7527 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-06 16:55:55.261  7461  7527 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-06 16:55:55.261  7461  7527 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 16:55:55.261  7461  7527 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:55:55.261  7461  7527 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-06 16:55:55.271  1015  1453 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 16:55:55.271  1015  1453 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 16:55:55.271  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:55.271  1015  1453 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:55.271  1015  1453 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:55.271  1015  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 16:55:55.281  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:55.281  4098  4098 D BluetoothPbap: Proxy object disconnected
,09-06 16:55:55.281  4098  4098 D PbapServerProfile: Bluetooth service disconnected
,09-06 16:55:55.291  7461  7461 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b0ce890, channel: 5, state: LISTENING
09-06 16:55:55.291  7461  7461 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1b0ce890, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1814b8d5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@22bb1589mSocket: android.net.LocalSocket@3b2e198e impl:android.net.LocalSocketImpl@103e55af fd:FileDescriptor[76]
09-06 16:55:55.291  7461  7461 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3b2e198e impl:android.net.LocalSocketImpl@103e55af fd:FileDescriptor[76]
,09-06 16:55:55.291  7461  7461 I BtOppRfcommListener: stopping Accept Thread
09-06 16:55:55.291  7461  7461 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1cfffdbc, channel: 12, state: LISTENING
09-06 16:55:55.291  7461  7461 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1cfffdbc, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f2346b7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@13b68145mSocket: android.net.LocalSocket@76409a impl:android.net.LocalSocketImpl@b249dcb fd:FileDescriptor[79]
09-06 16:55:55.291  7461  7461 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@76409a impl:android.net.LocalSocketImpl@b249dcb fd:FileDescriptor[79]
,09-06 16:55:55.291  7461  7583 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 16:55:55.291  4098  4098 D DockEventReceiver: finishStartingService: stopping service
,09-06 16:55:55.291  4098  4098 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 16:55:55.301  1169  1169 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:55:55.301  1169  1169 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-06 16:55:55.301  7461  7461 V BluetoothOppManager: cleanUp...
,09-06 16:55:55.321  1951  1951 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 16:55:55.331  1951  1951 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 16:55:55.461  7461  7527 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-06 16:55:55.471  7461  7527 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:55:55.471  7461  7527 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 16:55:55.471  7461  7527 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 16:55:55.471  7461  7527 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:55:55.471  7461  7527 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 16:55:55.471  7461  7527 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 16:55:55.471  7461  7527 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 16:55:55.471  7461  7527 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 16:55:55.471  7461  7527 W bt-btif : ag scb idx 1 not allocated
09-06 16:55:55.471  7461  7527 W bt-btif : ag scb idx 2 not allocated
09-06 16:55:55.471  7461  7527 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 16:55:55.471  7461  7565 I bt_userial_mct: exiting userial_read_thread
09-06 16:55:55.471  7461  7565 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 16:55:55.471  7461  7479 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 16:55:55.471  7461  7529 I bt_vendor: hw_epilog_process
09-06 16:55:55.471  7461  7479 D bt_userial_mct: userial_close
09-06 16:55:55.471  7461  7479 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-06 16:55:56.091  1015  4041 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 16:55:56.101  1015  4041 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-06 16:55:56.101  1169  1169 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-06 16:55:56.101  1015  4041 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
09-06 16:55:56.101  1169  1169 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 16:55:56.101  1015  4041 D BatteryService: stay LED for fully charged
09-06 16:55:56.101  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 16:55:56.101  1015  1015 I MotionRecognitionService: Plugged
09-06 16:55:56.101  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 16:55:56.111  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 16:55:56.111  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 16:55:56.121  7461  7461 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 16:55:56.121  7461  7498 D HeadsetStateMachine: Disconnected process message: 10
,09-06 16:55:56.131  1169  1169 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-06 16:55:56.131  1169  1169 D SViewCoverView: level :100 plugged : 2
,09-06 16:55:56.131  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,09-06 16:55:56.131  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 16:55:56.131  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 16:55:56.211  7461  7479 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off,
,09-06 16:55:56.211  7461  7479 I bt_vendor: bluetooth satus is on
,09-06 16:55:56.211  7461  7479 I bt_vendor: bt-vendor : resetting BT status
09-06 16:55:56.211  7461  7479 I bt_vendor: Starting hciattach daemon
,09-06 16:55:56.211  7461  7479 I bt_vendor: try to set false
,09-06 16:55:56.211  7461  7479 I bt_vendor: Starting hciattach daemon,
,09-06 16:55:56.211  7461  7479 I bt_vendor: try to set false
,09-06 16:55:56.221  1015  4377 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-06 16:55:56.211  7461  7479 I bt_vendor: cleanup
,09-06 16:55:56.221  1015  4377 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-06 16:55:56.211  7461  7527 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-06 16:55:56.211  7461  7479 I GKI_LINUX: GKI_exit_task 0 done
09-06 16:55:56.211  7461  7479 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-06 16:55:56.211  7461  7476 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-06 16:55:56.211  7461  7476 D BtConfig.SecureMode: isSecureModeOn:false
09-06 16:55:56.211  7461  7476 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-06 16:55:56.211  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,09-06 16:55:56.211  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 16:55:56.211  7461  7476 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-06 16:55:56.231  1015  1211 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:56.221  1015  4377 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:56.231  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-06 16:55:56.221  1015  4377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:56.221  1015  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 16:55:56.221  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 16:55:56.221  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 16:55:56.221  7461  7476 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-06 16:55:56.231  7461  7461 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 16:55:56.231  7461  7461 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 16:55:56.231  7461  7461 D BtGatt.GattService: stop()
09-06 16:55:56.231  7461  7461 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 16:55:56.231  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:56.231  1015  1211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:56.231  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:56.231  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 16:55:56.231  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 16:55:56.231  7461  7476 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 16:55:56.231  1015  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:56.231  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 16:55:56.231  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:56.231  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
09-06 16:55:56.231  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:56.231  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:56.231  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-06 16:55:56.231  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 16:55:56.231  7461  7476 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-06 16:55:56.231  1015  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:56.231  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 16:55:56.231  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:56.231  1015  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:56.231  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:56.241  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-06 16:55:56.241  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 16:55:56.241  7461  7476 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 16:55:56.241  7461  7461 D HeadsetService: Received stop request...Stopping profile...
,09-06 16:55:56.241  1015  1213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:56.241  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 16:55:56.241  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:56.241  1015  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:56.241  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:56.241  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:56.241  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-06 16:55:56.241  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-06 16:55:56.241  7461  7476 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 16:55:56.241  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-06 16:55:56.251  4098  4098 D HeadsetProfile: Bluetooth service disconnected
,09-06 16:55:56.251  1015  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:56.251  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 16:55:56.251  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:56.251  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 16:55:56.251  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:56.251  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-06 16:55:56.251  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 16:55:56.251  7461  7476 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 16:55:56.251  1015  1213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:55:56.251  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 16:55:56.251  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:56.251  1015  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:56.251  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:56.251  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-06 16:55:56.251  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 16:55:56.261  7461  7476 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-06 16:55:56.261  1015  1211 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 16:55:56.261  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 16:55:56.261  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:56.261  1015  1211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:56.261  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:55:56.261  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 16:55:56.261  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 16:55:56.261  7461  7476 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 16:55:56.261  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,09-06 16:55:56.261  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 16:55:56.261  7461  7476 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService,
09-06 16:55:56.261  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 16:55:56.261  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService,
09-06 16:55:56.261  7461  7476 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,09-06 16:55:56.261  7461  7476 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 16:55:56.261  7461  7476 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 16:55:56.261  7461  7476 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 16:55:56.261  7461  7476 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 16:55:56.271  7461  7461 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-06 16:55:56.271  7461  7461 D A2dpService: Received stop request...Stopping profile...
09-06 16:55:56.271  7461  7505 D A2dpStateMachine: Exit Disconnected: -1
,09-06 16:55:56.271  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:56.271  1015  1015 D BluetoothA2dp: Proxy object disconnected
,09-06 16:55:56.271  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 16:55:56.271  4098  4098 D BluetoothA2dp: Proxy object disconnected
,09-06 16:55:56.271  4098  4098 D A2dpProfile: Bluetooth service disconnected
,09-06 16:55:56.271  7461  7461 D HidService: Received stop request...Stopping profile...
,09-06 16:55:56.271  7461  7461 D HidService: Stopping Bluetooth HidService
,09-06 16:55:56.271  7461  7461 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 16:55:56.271  7461  7461 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-06 16:55:56.271  7461  7461 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 16:55:56.271  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:56.281  4098  4098 D BluetoothInputDevice: Proxy object disconnected
,09-06 16:55:56.281  4098  4098 D HidProfile: Bluetooth service disconnected
,09-06 16:55:56.281  7461  7461 D HealthService: Received stop request...Stopping profile...
,09-06 16:55:56.281  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:56.281  7461  7461 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,09-06 16:55:56.281  7461  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 16:55:56.281  7461  7461 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-06 16:55:56.281  7461  7461 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-06 16:55:56.291  7461  7461 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-06 16:55:56.291  7461  7461 D PanService: Received stop request...Stopping profile...
,09-06 16:55:56.291  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:56.291  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 16:55:56.291  7461  7461 D BluetoothMapService: Received stop request...Stopping profile...
,09-06 16:55:56.291  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:56.291  7461  7461 D SapService: Received stop request...Stopping profile...
09-06 16:55:56.291  7461  7461 D SapService: Stopping Bluetooth SapService
09-06 16:55:56.291  7461  7461 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@253f6bcd
,09-06 16:55:56.301  4098  4098 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 16:55:56.301  4098  4098 D PanProfile: Bluetooth service disconnected
,09-06 16:55:56.301  7461  7461 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-06 16:55:56.301  7461  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 16:55:56.301  7461  7461 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-06 16:55:56.301  7461  7461 D BluetoothA2dp: Proxy object disconnected
09-06 16:55:56.301  7461  7461 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-06 16:55:56.301  7461  7506 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-06 16:55:56.301  7461  7461 I GKI_LINUX: GKI_exit_task 2 done
09-06 16:55:56.301  7461  7461 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 16:55:56.301  7461  7461 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,09-06 16:55:56.301  7461  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 16:55:56.301  7461  7461 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 16:55:56.301  7461  7461 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-06 16:55:56.301  7461  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 16:55:56.301  7461  7461 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 16:55:56.301  7461  7461 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 16:55:56.301  7461  7461 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-06 16:55:56.301  7461  7461 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-06 16:55:56.301  7461  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 16:55:56.301  7461  7461 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 16:55:56.301  7461  7461 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 16:55:56.301  7461  7461 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-06 16:55:56.301  4098  4098 D BluetoothMap: Proxy object disconnected
09-06 16:55:56.301  4098  4098 D MapProfile: Bluetooth service disconnected
09-06 16:55:56.301  4098  4098 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-06 16:55:56.301  4098  4098 D SapProfile: Bluetooth service disconnected
,09-06 16:55:56.301  7461  7461 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-06 16:55:56.301  7461  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 16:55:56.301  7461  7461 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-06 16:55:56.301  7461  7461 E BluetoothAdapterService(624913357): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-06 16:55:56.301  7461  7461 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-06 16:55:56.301  7461  7461 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-06 16:55:56.301  7461  7476 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-06 16:55:56.311  7461  7476 D BluetoothAdapterProperties: Setting state to 10
,09-06 16:55:56.311  7461  7476 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-06 16:55:56.311  7461  7476 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 16:55:56.311  7461  7476 D BluetoothAdapterService: updateAdapterState state is 10
,09-06 16:55:56.311  7461  7476 D BluetoothAdapterService: Autoconnection is available 
,09-06 16:55:56.311  7461  7476 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,09-06 16:55:56.311  7461  7476 I BluetoothAdapterState: Entering OffState
,09-06 16:55:56.311  4098  4115 D BluetoothMap: onBluetoothStateChange: up=false
,09-06 16:55:56.311  1169  1193 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 16:55:56.311  1169  1193 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 16:55:56.311  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 16:55:56.311  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 16:55:56.311  7511  7521 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 16:55:56.311  7511  7521 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 16:55:56.311  4098  4108 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 16:55:56.321  7461  7480 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 16:55:56.321  4098  4108 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 16:55:56.321  4098  4108 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 16:55:56.321  1951  1964 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 16:55:56.321  1951  1964 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 16:55:56.321  4098  7569 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 16:55:56.321  1446  3309 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 16:55:56.321  1446  3309 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 16:55:56.321  7461  7475 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 16:55:56.321  7461  7475 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 16:55:56.321  1460  1477 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 16:55:56.321  1460  1477 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 16:55:56.321  1479  1490 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 16:55:56.321  1479  1490 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 16:55:56.331  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 16:55:56.331  4098  4115 D Bluetoothsap: onBluetoothStateChange: up=false
,09-06 16:55:56.331  4098  4115 D Bluetoothsap: Unbinding service...
,09-06 16:55:56.331  6847  6857 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 16:55:56.331  6847  6857 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 16:55:56.331  6847  6857 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-06 16:55:56.331  6847  6857 D BluetoothLeAdvertiser: Exit stop advertising
09-06 16:55:56.331  6847  6857 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-06 16:55:56.331  6847  6857 D BluetoothLeScanner: Exiting stopAllScan
,09-06 16:55:56.331  4098  4108 D BluetoothPbap: onBluetoothStateChange: up=false
,09-06 16:55:56.331  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-06 16:55:56.331  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 16:55:56.341  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:56.341  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
09-06 16:55:56.341  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 16:55:56.341  7461  7479 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-06 16:55:56.341  7461  7461 I GKI_LINUX: GKI_exit_task 1 done
09-06 16:55:56.341  7461  7461 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-06 16:55:56.341  7461  7461 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 16:55:56.341  1169  1169 D BluetoothAdapter: 686330628: getState() :  mService = null. Returning STATE_OFF
09-06 16:55:56.341  1169  1169 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 16:55:56.341  1169  1728 D BluetoothAdapter: 686330628: getState() :  mService = null. Returning STATE_OFF
,09-06 16:55:56.341  1169  1169 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:55:56.341  1169  1169 D BluetoothTile:  getBluetoothState : 10
09-06 16:55:56.341  1169  1169 D BluetoothAdapter: 686330628: getState() :  mService = null. Returning STATE_OFF
09-06 16:55:56.341  1169  1169 D BluetoothAdapter: 686330628: getState() :  mService = null. Returning STATE_OFF
,09-06 16:55:56.351  1015  1495 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-06 16:55:56.351  1169  1728 D BluetoothAdapter: 686330628: getState() :  mService = null. Returning STATE_OFF
09-06 16:55:56.351  1015  1211 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 16:55:56.351  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-06 16:55:56.351  1870  1870 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 16:55:56.351  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 16:55:56.351  1951  2166 D BluetoothAdapter: 603148151: getState() :  mService = null. Returning STATE_OFF
,09-06 16:55:56.351  4098  4098 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:55:56.351  1951  2166 D BluetoothAdapter: 603148151: getState() :  mService = null. Returning STATE_OFF
,09-06 16:55:56.351  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:56.351  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:55:56.351  7461  7461 I art     : System.exit called, status: 0
09-06 16:55:56.351  7461  7461 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 16:55:56.351  1015  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 16:55:56.351  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 16:55:56.351  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:56.351  1015  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 16:55:56.351  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 16:55:56.351  4098  4098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 16:55:56.361  1015  1478 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 16:55:56.361  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0,
09-06 16:55:56.361  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:55:56.361  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:55:56.361  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 16:55:56.371  4098  4098 D DockEventReceiver: finishStartingService: stopping service
,09-06 16:55:56.371  4098  4098 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 16:55:56.371  1169  1169 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:55:56.371  1169  1169 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-06 16:55:56.381  1015  1453 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-06 16:55:56.381  1015  1453 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-06 16:55:56.391  1015  1453 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
09-06 16:55:56.391  1015  1453 W BroadcastQueue: android.os.TransactionTooLargeException
09-06 16:55:56.391  1015  1453 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 16:55:56.391  1015  1453 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 16:55:56.391  1015  1453 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-06 16:55:56.391  1015  1453 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-06 16:55:56.391  1015  1453 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-06 16:55:56.391  1015  1453 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-06 16:55:56.391  1015  1453 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-06 16:55:56.391  1015  1453 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-06 16:55:56.391  1015  1453 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 16:55:56.391  1015  1453 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-06 16:55:56.391  1015  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:56.391  1015  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:56.391  1015  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:55:56.391  1015  1453 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:55:56.401  7599  7599 E Zygote  : MountEmulatedStorage()
,09-06 16:55:56.401  1015  1453 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7599 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-06 16:55:56.401  7599  7599 E Zygote  : v2
09-06 16:55:56.401  7599  7599 I libpersona: KNOX_SDCARD checking this for 1002
09-06 16:55:56.401  7599  7599 I libpersona: KNOX_SDCARD not a persona
,09-06 16:55:56.411  7599  7599 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 16:55:56.411  7599  7599 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-06 16:55:56.411  7599  7599 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 16:55:56.421  7599  7599 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:55:56.431  7599  7599 D ActivityThread: Added TimaKeyStore provider
,09-06 16:55:56.441  7599  7599 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-06 16:55:56.441  7599  7599 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 16:55:56.461  7599  7599 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-06 16:55:56.491  7599  7599 D BtSettings.ProfileConfig: Adding GattService
,09-06 16:55:56.491  7599  7599 D BtSettings.ProfileConfig: Adding HeadsetService
09-06 16:55:56.491  7599  7599 D BtSettings.ProfileConfig: Adding A2dpService
,09-06 16:55:56.491  7599  7599 D BtSettings.ProfileConfig: Adding HidService
09-06 16:55:56.491  7599  7599 D BtSettings.ProfileConfig: Adding HealthService
09-06 16:55:56.491  7599  7599 D BtSettings.ProfileConfig: Adding PanService
,09-06 16:55:56.491  7599  7599 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-06 16:55:56.491  7599  7599 D BtSettings.ProfileConfig: Adding SapService
09-06 16:55:56.491  7599  7599 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-06 16:55:56.491  7599  7599 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-06 16:55:56.491  7599  7599 D BtSettings.ProfileConfig: Adding SapClientService
,09-06 16:55:56.491  7599  7599 D BtSettings.ProfileConfig: Adding HidDevService
09-06 16:55:56.491  7599  7599 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-06 16:55:56.501  1015  1485 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-06 16:55:56.501  1015  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:56.501  1015  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:56.501  1015  1485 D SettingsProvider: selectionArgs: false
09-06 16:55:56.501  1015  1485 D SettingsProvider: selectionArgs: 1002
09-06 16:55:56.501  1015  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:56.501  1015  1485 D SettingsProvider: ret = -1
,09-06 16:55:56.501  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-06 16:55:56.501  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 16:55:56.501  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:56.501  1015  1027 D SettingsProvider: selectionArgs: false
09-06 16:55:56.501  1015  1027 D SettingsProvider: selectionArgs: 1002
,09-06 16:55:56.501  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:56.501  1015  1027 D SettingsProvider: ret = -1
,09-06 16:55:56.501  1015  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-06 16:55:56.501  1015  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:56.501  1015  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:56.501  1015  1495 D SettingsProvider: selectionArgs: false
09-06 16:55:56.501  1015  1495 D SettingsProvider: selectionArgs: 1002
09-06 16:55:56.501  1015  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:56.501  1015  1495 D SettingsProvider: ret = -1
,09-06 16:55:56.501  1015  1211 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-06 16:55:56.501  1015  1211 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 16:55:56.501  1015  1211 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:56.501  1015  1211 D SettingsProvider: selectionArgs: false
09-06 16:55:56.501  1015  1211 D SettingsProvider: selectionArgs: 1002
09-06 16:55:56.501  1015  1211 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 16:55:56.501  1015  1211 D SettingsProvider: ret = -1
,09-06 16:55:56.501  1015  4377 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-06 16:55:56.501  1015  4377 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 16:55:56.501  1015  4377 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:56.501  1015  4377 D SettingsProvider: selectionArgs: false
09-06 16:55:56.501  1015  4377 D SettingsProvider: selectionArgs: 1002
09-06 16:55:56.501  1015  4377 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:56.501  1015  4377 D SettingsProvider: ret = -1
,09-06 16:55:56.501  1015  1452 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-06 16:55:56.501  1015  1452 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:56.501  1015  1452 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:56.501  1015  1452 D SettingsProvider: selectionArgs: false
09-06 16:55:56.501  1015  1452 D SettingsProvider: selectionArgs: 1002
09-06 16:55:56.501  1015  1452 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:56.501  1015  1452 D SettingsProvider: ret = -1
,09-06 16:55:56.501  1015  1213 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-06 16:55:56.501  1015  1213 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:56.501  1015  1213 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:56.501  1015  1213 D SettingsProvider: selectionArgs: false
09-06 16:55:56.501  1015  1213 D SettingsProvider: selectionArgs: 1002
09-06 16:55:56.501  1015  1213 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:56.501  1015  1213 D SettingsProvider: ret = -1
,09-06 16:55:56.501  1015  1453 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-06 16:55:56.511  1015  1453 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:56.511  1015  1453 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:56.511  1015  1453 D SettingsProvider: selectionArgs: false
09-06 16:55:56.511  1015  1453 D SettingsProvider: selectionArgs: 1002
09-06 16:55:56.511  1015  1453 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:56.511  1015  1453 D SettingsProvider: ret = -1
,09-06 16:55:56.511  1015  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-06 16:55:56.511  1015  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:56.511  1015  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:56.511  1015  1478 D SettingsProvider: selectionArgs: false
09-06 16:55:56.511  1015  1478 D SettingsProvider: selectionArgs: 1002
09-06 16:55:56.511  1015  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 16:55:56.511  1015  1478 D SettingsProvider: ret = -1
09-06 16:55:56.511  1015  4041 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-06 16:55:56.511  1015  4041 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 16:55:56.511  1015  4041 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:56.511  1015  4041 D SettingsProvider: selectionArgs: false
09-06 16:55:56.511  1015  4041 D SettingsProvider: selectionArgs: 1002
09-06 16:55:56.511  1015  4041 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:56.511  1015  4041 D SettingsProvider: ret = -1
,09-06 16:55:56.511  1015  1485 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-06 16:55:56.511  1015  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 16:55:56.511  1015  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:56.511  1015  1485 D SettingsProvider: selectionArgs: false
09-06 16:55:56.511  1015  1485 D SettingsProvider: selectionArgs: 1002
09-06 16:55:56.511  1015  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:55:56.511  1015  1485 D SettingsProvider: ret = -1
,09-06 16:55:56.511  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-06 16:55:56.511  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:55:56.511  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:55:56.511  1015  1027 D SettingsProvider: selectionArgs: false
09-06 16:55:56.511  1015  1027 D SettingsProvider: selectionArgs: 1002
09-06 16:55:56.511  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 16:55:56.511  1015  1027 D SettingsProvider: ret = -1
,09-06 16:55:56.521  1951  1951 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 16:55:56.521  1015  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 16:55:56.521  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 16:55:56.521  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:56.521  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:56.521  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:56.531  1951  1951 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 16:55:56.531  1951  7615 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 16:55:56.681   292   292 E SMD     : DCD OFF
,09-06 16:55:56.691  1015  1028 I art     : Explicit concurrent mark sweep GC freed 69175(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.465ms total 153.785ms
,09-06 16:55:56.691  1015  1453 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 16:55:56.691  1015  1453 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:55:56.691  1015  1453 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:55:56.691  1015  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:55:56.701  1951  7615 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-06 16:55:57.231  1015  1047 I PowerManagerService: [PWL] Off : 75s ago
,09-06 16:55:57.231  1015  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-06 16:55:57.231  1015  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-06 16:55:57.231  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=13688)
,09-06 16:55:57.891  1015  1325 E Watchdog: !@Sync 4
,09-06 16:55:58.201  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 16:55:58.201  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:55:59.411   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 16:55:59.691   292   292 E SMD     : DCD OFF
,09-06 16:55:59.991  1015  1093 V AlarmManager: waitForAlarm result :8
,09-06 16:56:00.411   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 16:56:01.201  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
,09-06 16:56:01.201  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@157270de added. We now have 6 listener(s)
,09-06 16:56:01.201  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:56:01.201  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 16:56:01.201  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29d1e2bf added. We now have 7 listener(s)
,09-06 16:56:01.201  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:56:01.201  6847  6901 I System.out: IsBluetoothEnabled
,09-06 16:56:01.201  6847  6901 D BluetoothAdapter: disable()
,09-06 16:56:01.201  1015  4041 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.,
,09-06 16:56:01.211  6847  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:01.211  6847  6901 D BluetoothAdapter: enable()
,09-06 16:56:01.211  1015  1213 W ActivityManager: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-06 16:56:01.211  1015  1213 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-06 16:56:01.211  1015  1213 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 16:56:01.211  1015  1213 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 16:56:01.211  1015  1213 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-06 16:56:01.211  1015  1213 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-06 16:56:01.211  1015  1213 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-06 16:56:01.211  1015  1213 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 16:56:01.211  1015  1213 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 16:56:01.211  1015  1213 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 16:56:01.221  1015  1213 D SettingsProvider: name = bluetooth_on
,09-06 16:56:01.231  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 16:56:01.231  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 16:56:01.241  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,09-06 16:56:01.241  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-06 16:56:01.261  7599  7599 D BluetoothAdapterState: make
,09-06 16:56:01.271  7599  7599 I bluedroid: init
,09-06 16:56:01.271  7599  7621 I BluetoothAdapterState: Entering OffState
,09-06 16:56:01.271  7599  7599 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-06 16:56:01.271  7599  7599 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 16:56:01.271  7599  7599 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 16:56:01.271  7599  7599 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found,
,09-06 16:56:01.271  7599  7599 E bt-btif : btif_fetch_local_ble_random_bdaddr,
09-06 16:56:01.281  7599  7599 I bluedroid: get_profile_interface socket
09-06 16:56:01.281  7599  7624 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-06 16:56:01.281  7599  7599 I bluedroid: get_profile_interface map_client
,09-06 16:56:01.281  7599  7599 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-06 16:56:01.281  7599  7624 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
09-06 16:56:01.281  7599  7624 E BluetoothServiceJni: populateRssiValuesNative
09-06 16:56:01.281  7599  7624 I bluedroid: getModelRssiValues
09-06 16:56:01.281  7599  7624 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 16:56:01.281  7599  7624 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 16:56:01.281  1015  1015 D SettingsProvider: name = bluetooth_name
,09-06 16:56:01.281  7599  7624 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-06 16:56:01.291  7599  7599 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 16:56:01.291  1015  1452 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 16:56:01.291  1015  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 16:56:01.291  1015  1452 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:56:01.291  1015  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 16:56:01.291  1015  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:01.291  7599  7609 I bluedroid: config_hci_snoop_log
,09-06 16:56:01.301  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-06 16:56:01.301  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,09-06 16:56:01.301  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-06 16:56:01.301  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-06 16:56:01.301  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 16:56:01.301  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 16:56:01.301  7599  7599 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-06 16:56:01.301  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 16:56:01.311  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-06 16:56:01.311  7599  7621 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-06 16:56:01.311  7599  7621 D BluetoothAdapterProperties: Setting state to 11
,09-06 16:56:01.311  7599  7621 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 16:56:01.311  7599  7621 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-06 16:56:01.311  7599  7621 D BluetoothAdapterService: updateAdapterState state is 11
,09-06 16:56:01.311  7599  7621 D BluetoothAdapterService: Autoconnection is available 
09-06 16:56:01.311  7599  7621 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-06 16:56:01.321  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:56:01.321  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,09-06 16:56:01.321  7599  7621 D BluetoothSecureManager: getInstant: null
09-06 16:56:01.321  7599  7621 D BluetoothSecureManager: calling getMethod for getService
09-06 16:56:01.321  7599  7621 D BluetoothSecureManager: calling getService
09-06 16:56:01.321  7599  7621 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@161464e8
,09-06 16:56:01.321  1015  1485 D BluetoothSecureManagerService: isSecureModeEnabled
09-06 16:56:01.331  1015  1485 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-06 16:56:01.331  7599  7621 D BtConfig.SecureMode: isSecureModeOn:false
09-06 16:56:01.331  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 16:56:01.331  7599  7621 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-06 16:56:01.331  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 16:56:01.331  1169  1169 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 16:56:01.331  1169  1169 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:01.331  1169  1169 D BluetoothTile:  getBluetoothState : 11
,09-06 16:56:01.331  7599  7621 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-06 16:56:01.331  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 16:56:01.331  7599  7621 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,09-06 16:56:01.331  1169  1728 D BluetoothTile:  handleUpdatestate:false name:null
09-06 16:56:01.331  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 16:56:01.331  1169  1728 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-06 16:56:01.331  7599  7621 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-06 16:56:01.331  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 16:56:01.331  4098  4098 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:56:01.331  1870  1870 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 16:56:01.341  7599  7621 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService,
09-06 16:56:01.341  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-06 16:56:01.341  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:01.341  7599  7621 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-06 16:56:01.341  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 16:56:01.341  7599  7621 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-06 16:56:01.341  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 16:56:01.341  7599  7621 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-06 16:56:01.341  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 16:56:01.341  7599  7621 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 16:56:01.341  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 16:56:01.341  7599  7621 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-06 16:56:01.341  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 16:56:01.341  7599  7621 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-06 16:56:01.341  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-06 16:56:01.341  1015  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 16:56:01.351  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-06 16:56:01.351  1015  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 16:56:01.351  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 16:56:01.351  7599  7621 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-06 16:56:01.351  1015  1452 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 16:56:01.351  7599  7621 D BluetoothBondStateMachine: make
,09-06 16:56:01.351  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 16:56:01.351  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:56:01.351  1015  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:56:01.351  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:56:01.361  4098  4098 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 16:56:01.361  7599  7621 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 16:56:01.361  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 16:56:01.361  7599  7621 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-06 16:56:01.361  7599  7625 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 16:56:01.361  1169  1169 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:56:01.361  1169  1169 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-06 16:56:01.371  1015  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 16:56:01.371  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-06 16:56:01.381  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:01.381  1015  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:01.381  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:01.381  7599  7621 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 16:56:01.381  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 16:56:01.381  7599  7621 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 16:56:01.381  1015  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 16:56:01.381  7599  7599 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 16:56:01.381  7599  7599 D BtGatt.GattService: Received start request. Starting profile...
,09-06 16:56:01.381  7599  7599 D BtGatt.GattService: start()
09-06 16:56:01.381  7599  7599 D BtGatt.GattService: start()
09-06 16:56:01.381  7599  7599 I bluedroid: get_profile_interface gatt
,09-06 16:56:01.381  7599  7599 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13729f93
09-06 16:56:01.381  7599  7599 D BtGatt.AdvertiseManager: advertise manager created
,09-06 16:56:01.381  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 16:56:01.381  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:56:01.381  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:01.381  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:01.391  7599  7621 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 16:56:01.391  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 16:56:01.391  7599  7621 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 16:56:01.391  1015  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:56:01.391  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 16:56:01.391  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:56:01.391  1015  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:01.391  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:01.401  7599  7621 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-06 16:56:01.401  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 16:56:01.401  7599  7621 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 16:56:01.401  1015  1452 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:56:01.401  1015  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 16:56:01.401  1015  1452 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:56:01.401  7599  7599 D BtGatt.GattService: mStartError = false
,09-06 16:56:01.401  7599  7599 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13729f93
,09-06 16:56:01.401  7599  7599 D HeadsetService: Received start request. Starting profile...
,09-06 16:56:01.401  7599  7599 D HeadsetService: start(),
09-06 16:56:01.401   332   332 I ServiceManager: Waiting for service AtCmdFwd...
09-06 16:56:01.401  7599  7599 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-06 16:56:01.401  7599  7599 D HeadsetStateMachine: make,
09-06 16:56:01.401  1015  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:01.411  1015  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:01.411  7599  7599 E HeadsetStateMachine: # of Max HF connection is 2
,09-06 16:56:01.411  7599  7621 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-06 16:56:01.411  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 16:56:01.411  7599  7621 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 16:56:01.411  1015  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:56:01.411  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 16:56:01.411  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:56:01.411  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:01.411  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:01.411  7599  7621 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-06 16:56:01.411  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 16:56:01.411  7599  7621 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 16:56:01.411  1015  1211 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:56:01.411  1015  1211 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 16:56:01.421  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:01.421  1015  1211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:01.421  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:01.421  1015  1213 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-06 16:56:01.421  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-06 16:56:01.421  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:01.421  1015  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 16:56:01.421  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 16:56:01.421  7599  7621 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-06 16:56:01.421  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 16:56:01.421  7599  7621 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 16:56:01.421  1015  1485 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-06 16:56:01.421  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-06 16:56:01.421  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:56:01.431  1015  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:01.431  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-06 16:56:01.431  7599  7599 I bluedroid: get_profile_interface handsfree
,09-06 16:56:01.431  1015  4041 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-06 16:56:01.431  1015  4041 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 16:56:01.431  1015  4041 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:56:01.431  1015  4041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:01.431  1015  4041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:01.441  7599  7621 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-06 16:56:01.441  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 16:56:01.441  7599  7621 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 16:56:01.441  1015  1453 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:56:01.441  1015  1453 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 16:56:01.441  1015  1453 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:56:01.441  1015  1453 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:01.441  1015  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:01.441  7599  7621 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 16:56:01.441  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 16:56:01.441  7599  7621 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 16:56:01.441  7599  7621 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 16:56:01.441  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 16:56:01.441  7599  7621 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 16:56:01.441  7599  7621 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 16:56:01.441  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 16:56:01.441  7599  7621 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 16:56:01.441  7599  7621 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 16:56:01.441  7599  7621 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 16:56:01.441  7599  7621 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 16:56:01.441  7599  7621 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-06 16:56:01.441  7599  7599 I DualScoManager: Instantiating Dual Sco Manager
,09-06 16:56:01.441  7599  7599 I DualScoManager: Set HeadsetServiceHelper
,09-06 16:56:01.441  7599  7599 D BluetoothAtMessage: createCMTIContentObservers
,09-06 16:56:01.451  1015  1496 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-06 16:56:01.451  1015  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:56:01.451  1015  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:56:01.451  1015  1496 D SettingsProvider: selectionArgs: false
09-06 16:56:01.451  1015  1496 D SettingsProvider: selectionArgs: 1002
09-06 16:56:01.451  1015  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:56:01.451  1015  1496 D SettingsProvider: ret = -1
,09-06 16:56:01.451  7599  7632 D HeadsetStateMachine: Enter Disconnected: -2
,09-06 16:56:01.451  7599  7599 D HeadsetService: mStartError = false
09-06 16:56:01.451  7599  7599 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13729f93
,09-06 16:56:01.451  7599  7632 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-06 16:56:01.451  7599  7632 D HeadsetStateMachine: map size, before remove : 0
,09-06 16:56:01.451  7599  7632 D HeadsetStateMachine: map size, after remove: 0
,09-06 16:56:01.451  7599  7599 D A2dpService: Received start request. Starting profile...
09-06 16:56:01.451  7599  7599 D A2dpService: start()
,09-06 16:56:01.461  7599  7599 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-06 16:56:01.461  7599  7599 I bluedroid: get_profile_interface avrcp
,09-06 16:56:01.461  1951  1951 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 16:56:01.471  7599  7599 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 16:56:01.471  7599  7599 D Avrcp   : Initialize Media Controller
09-06 16:56:01.471  7599  7599 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-06 16:56:01.471  1951  1951 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 16:56:01.471  7599  7599 E Avrcp   : getActiveSessions
09-06 16:56:01.471  7599  7599 D Avrcp   : pick active media Controller
09-06 16:56:01.471  7599  7599 D Avrcp   : Get the active Media Controller 
,09-06 16:56:01.491  7599  7599 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-06 16:56:01.491  7599  7633 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-06 16:56:01.491  7599  7599 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 16:56:01.491  7599  7599 D A2dpStateMachine: make
,09-06 16:56:01.491  7599  7599 I bluedroid: get_profile_interface a2dp
,09-06 16:56:01.491  7599  7635 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-06 16:56:01.491  7599  7599 E bt-btif : warning : media task started media_task_refcnt 1 
,09-06 16:56:01.501  7599  7633 D BluetoothMediaBrowser: no now playing list
09-06 16:56:01.501  7599  7633 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-06 16:56:01.501  7599  7599 D A2dpService: mStartError = false
,09-06 16:56:01.501  7599  7599 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13729f93
,09-06 16:56:01.501  7599  7599 E BluetoothAdapterService(326279059): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-06 16:56:01.501  7599  7634 D A2dpStateMachine: Enter Disconnected: -2,
09-06 16:56:01.501  7599  7599 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 16:56:01.501  7599  7599 D HidService: Received start request. Starting profile...
09-06 16:56:01.501  7599  7599 D HidService: start()
09-06 16:56:01.501  7599  7599 I bluedroid: get_profile_interface hidhost
09-06 16:56:01.501  7599  7599 D HidService: setHidService(): set to: null
09-06 16:56:01.501  7599  7599 D HidService: mStartError = false
09-06 16:56:01.501  7599  7599 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13729f93
,09-06 16:56:01.501  7599  7599 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 16:56:01.501  7599  7599 D HealthService: Received start request. Starting profile...
,09-06 16:56:01.501  7599  7599 D HealthService: start()
,09-06 16:56:01.511  7599  7599 I bluedroid: get_profile_interface health
,09-06 16:56:01.511  7599  7599 D HealthService: mStartError = false,
09-06 16:56:01.511  7599  7599 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13729f93
09-06 16:56:01.511  7599  7599 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 16:56:01.511  7599  7599 D PanService: Received start request. Starting profile...,
09-06 16:56:01.511  7599  7599 D PanService: start()
09-06 16:56:01.511  7599  7599 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 16:56:01.511  1446  3309 I Telecom : BluetoothPhoneService: queryPhoneState,
09-06 16:56:01.511  7599  7599 I bluedroid: get_profile_interface pan
09-06 16:56:01.511  7599  7599 D PanService: mStartError = false,
,09-06 16:56:01.511  7599  7599 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13729f93
09-06 16:56:01.511  1446  1446 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-06 16:56:01.511  7599  7599 D HeadsetStateMachine: Try to query the phonestate on bind
09-06 16:56:01.511  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-06 16:56:01.511  1446  3309 I Telecom : BluetoothPhoneService: Result of Message : true
,09-06 16:56:01.511  7599  7599 D HeadsetStateMachine: Proxy object connected
,09-06 16:56:01.521  7599  7599 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-06 16:56:01.521  7599  7632 D HeadsetStateMachine: Disconnected process message: 11
,09-06 16:56:01.521  7599  7599 D BluetoothMapService: Received start request. Starting profile...
,09-06 16:56:01.521  7599  7599 D BluetoothMapService: start()
,09-06 16:56:01.521  7599  7599 D BluetoothMapService: mStartError = false
09-06 16:56:01.521  7599  7599 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13729f93
,09-06 16:56:01.521  7599  7599 D HeadsetPhoneState: sendDeviceDataStateChanged
09-06 16:56:01.521  7599  7599 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-06 16:56:01.521  7599  7632 D HeadsetStateMachine: Disconnected process message: 18
09-06 16:56:01.521  7599  7599 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-06 16:56:01.521  7599  7599 D SapService: Received start request. Starting profile...
,09-06 16:56:01.521  7599  7599 D SapService: start()
09-06 16:56:01.521  7599  7599 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-06 16:56:01.521  7599  7599 I bluedroid: get_profile_interface sap
09-06 16:56:01.521  7599  7599 D SapService: mStartError = false
09-06 16:56:01.521  7599  7599 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13729f93
09-06 16:56:01.521  7599  7599 E BluetoothAdapterService(326279059): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-06 16:56:01.521  7599  7599 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 16:56:01.521  7599  7599 D BluetoothA2dp: Proxy object connected
09-06 16:56:01.521  7599  7599 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-06 16:56:01.521  7599  7632 D HeadsetStateMachine: Disconnected process message: 10
09-06 16:56:01.521  7599  7632 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 16:56:01.531  7599  7632 D HeadsetStateMachine: Disconnected process message: 11
,09-06 16:56:01.531  7599  7599 E BluetoothAdapterService(326279059): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-06 16:56:01.531  7599  7599 E BluetoothAdapterService(326279059): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-06 16:56:01.531  7599  7599 E BluetoothAdapterService(326279059): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,09-06 16:56:01.531  7599  7599 E BluetoothAdapterService(326279059): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-06 16:56:01.551  7599  7599 E BluetoothAdapterService(326279059): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-06 16:56:01.551  7599  7599 E BluetoothAdapterService(326279059): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-06 16:56:01.551  7599  7621 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-06 16:56:01.551  7599  7621 I bluedroid: enable
09-06 16:56:01.551  7599  7621 I bt_hci_bdroid: init
,09-06 16:56:01.551  7599  7639 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-06 16:56:01.551  7599  7621 I bt_vendor: bt-vendor : init
,09-06 16:56:01.551  7599  7621 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 16:56:01.551  7599  7621 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 16:56:01.551  7599  7621 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
09-06 16:56:01.551  7599  7621 D bt_userial_mct: userial_init
09-06 16:56:01.551  7599  7621 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 16:56:01.551  7599  7621 I bt_vendor: Starting hciattach daemon
09-06 16:56:01.551  7599  7621 I bt_vendor: try to set false
,09-06 16:56:01.551  7599  7621 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 16:56:01.551  7599  7621 I bt_vendor: Starting hciattach daemon
09-06 16:56:01.551  7599  7621 I bt_vendor: try to set true
,09-06 16:56:01.571  7643  7643 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-06 16:56:01.611  7649  7649 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-06 16:56:01.621  7650  7650 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-06 16:56:01.641  7652  7652 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 16:56:01.641  7653  7653 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-06 16:56:01.651  7654  7654 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 16:56:01.661  7655  7655 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-06 16:56:01.851  7658  7658 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,09-06 16:56:01.861  7659  7659 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-06 16:56:01.921  7599  7621 I bt_vendor: bluetooth satus is on
09-06 16:56:01.921  7599  7641 D bt_userial_mct: userial_open(port:0)
,09-06 16:56:01.921  7599  7641 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-06 16:56:01.921  7599  7641 I bt_vendor: Done intiailizing UART,
,09-06 16:56:01.921  7599  7641 I bt_vendor: Done intiailizing UART
09-06 16:56:01.921  7599  7641 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-06 16:56:01.921  7599  7641 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-06 16:56:01.921  7599  7639 I         : BTE_InitTraceLevels -- TRC_HCI
09-06 16:56:01.921  7599  7639 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 16:56:01.921  7599  7639 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-06 16:56:01.921  7599  7639 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 16:56:01.921  7599  7639 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 16:56:01.921  7599  7639 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 16:56:01.921  7599  7639 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 16:56:01.921  7599  7639 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 16:56:01.921  7599  7639 I         : BTE_InitTraceLevels -- TRC_GAP,
09-06 16:56:01.921  7599  7639 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 16:56:01.921  7599  7639 I         : BTE_InitTraceLevels -- TRC_SAP
09-06 16:56:01.921  7599  7639 I         : BTE_InitTraceLevels -- TRC_SDP,
09-06 16:56:01.921  7599  7639 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 16:56:01.921  7599  7639 I         : BTE_InitTraceLevels -- TRC_SMP
,09-06 16:56:01.921  7599  7639 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 16:56:01.921  7599  7639 I         : BTE_InitTraceLevels -- TRC_BTIF
09-06 16:56:01.921  7599  7639 I         : BTE_InitTraceLevels -- TRC_PROTOCOL,
09-06 16:56:01.931  7599  7662 D bt_userial_mct: Entering userial_read_thread()
,09-06 16:56:02.021  7599  7639 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-06 16:56:02.021  7599  7639 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa429aed1 
,09-06 16:56:02.021  7599  7639 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa429aed1 
,09-06 16:56:02.041  7599  7624 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-06 16:56:02.041  7599  7624 E bt-btif : Calling BTA_HhEnable
,09-06 16:56:02.041  7599  7624 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-06 16:56:02.041  7599  7624 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-06 16:56:02.041  7599  7624 E BluetoothServiceJni: populateRssiValuesNative
09-06 16:56:02.041  7599  7624 I bluedroid: getModelRssiValues
09-06 16:56:02.051  7599  7624 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 16:56:02.051  7599  7624 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 16:56:02.051  7599  7624 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3),
,09-06 16:56:02.051  1015  1015 D SettingsProvider: name = bluetooth_name
,09-06 16:56:02.051  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:02.061  7599  7624 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-06 16:56:02.061  7599  7624 D BluetoothAdapterProperties: Scan Mode:20
,09-06 16:56:02.061  7599  7624 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 16:56:02.061  7599  7624 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,09-06 16:56:02.061  7599  7624 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,09-06 16:56:02.061  7599  7624 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-06 16:56:02.061  7599  7624 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-06 16:56:02.061  7599  7624 E bt-btif : btif_sock_init: !vhci_init
09-06 16:56:02.061  7599  7624 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-06 16:56:02.061  7599  7662 E bt_mct  : hci lib postload completed
09-06 16:56:02.061  7599  7624 D IOP_DB_BT: db_open: db_open : handle 3028062224l, read 13894 bytes onto local cache
,09-06 16:56:02.071  7599  7624 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-06 16:56:02.071  7599  7624 D IOP_DB_BT: db_query: result 1
,09-06 16:56:02.071  7599  7624 I         : iop_db_open: iop_db_open status 0
,09-06 16:56:02.071  7599  7624 D bte_conf: Device ID record 1 : primary
,09-06 16:56:02.071  7599  7624 D bte_conf:   vendorId            = 0075
,09-06 16:56:02.071  7599  7624 D bte_conf:   vendorIdSource      = 0001
09-06 16:56:02.071  7599  7624 D bte_conf:   product             = 0100
,09-06 16:56:02.071  7599  7624 D bte_conf:   version             = 0200
09-06 16:56:02.071  7599  7624 D bte_conf:   clientExecutableURL = 
,09-06 16:56:02.071  7599  7624 D bte_conf:   serviceDescription  = 
09-06 16:56:02.071  7599  7624 D bte_conf:   documentationURL    = 
09-06 16:56:02.071  7599  7624 D bte_conf: bte_load_did_conf no section named DID2.
,09-06 16:56:02.081  7599  7624 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 16:56:02.081  7599  7621 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-06 16:56:02.081  7599  7621 D BluetoothAdapterProperties: ScanMode =  20
,09-06 16:56:02.081  7599  7621 D BluetoothAdapterProperties: State =  11
,09-06 16:56:02.081  1015  4377 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 16:56:02.081  7599  7621 D BluetoothAdapterProperties: Setting state to 12
09-06 16:56:02.081  7599  7621 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 16:56:02.091  7599  7624 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-06 16:56:02.091  7599  7624 D BluetoothAdapterProperties: Scan Mode:21
09-06 16:56:02.091  7599  7624 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 16:56:02.091  1015  1028 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-06 16:56:02.091  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:56:02.091  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:56:02.091  1015  1028 D SettingsProvider: selectionArgs: false
09-06 16:56:02.091  1015  1028 D SettingsProvider: selectionArgs: 1002
09-06 16:56:02.091  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:56:02.091  1015  1028 D SettingsProvider: ret = -1
,09-06 16:56:02.091  7599  7621 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 16:56:02.091  7599  7621 D BluetoothAdapterService: updateAdapterState state is 12
,09-06 16:56:02.091  1015  4377 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:56:02.091  1015  4377 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 16:56:02.091  1015  4377 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:02.091  1015  4377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:02.091  1015  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:02.101  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:02.101  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:02.101  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:02.101  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:56:02.101  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:02.101  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:02.101  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:02.101  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:56:02.101  4098  4108 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 16:56:02.111  7599  7621 D BluetoothAdapterService: Autoconnection is available 
09-06 16:56:02.111  7599  7621 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-06 16:56:02.111  7599  7621 D BluetoothAdapterService: starting service from this receiver
,09-06 16:56:02.111  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:56:02.111  1015  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:56:02.111  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 16:56:02.111  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:02.111  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:02.111  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:02.111  7599  7621 I BluetoothAdapterState: Entering On State from state = 11
,09-06 16:56:02.111  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-06 16:56:02.111  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 16:56:02.121  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:02.121  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:02.121  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:02.121  1169  5713 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 16:56:02.121  1169  5713 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 16:56:02.121  7599  7609 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 16:56:02.121  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 16:56:02.121  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 16:56:02.121  7511  7522 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 16:56:02.121  7511  7522 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 16:56:02.121  1015  1044 D BluetoothPan: Binding service...
,09-06 16:56:02.121  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 16:56:02.121  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 16:56:02.121  4098  7569 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 16:56:02.131  7599  7599 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
09-06 16:56:02.131  4098  7569 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 16:56:02.131  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 16:56:02.131  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 16:56:02.131  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:56:02.131  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:02.131  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:02.131  4098  4098 D BluetoothA2dp: Proxy object connected
,09-06 16:56:02.131  4098  4098 D A2dpProfile: Bluetooth service connected
,09-06 16:56:02.141  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 16:56:02.141  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 16:56:02.141  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 16:56:02.141  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 16:56:02.141  1479  1488 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 16:56:02.141  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 16:56:02.141  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 16:56:02.141  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:02.141  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:02.141  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:02.141  1479  1488 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 16:56:02.141  4098  4108 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 16:56:02.151  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 16:56:02.151  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 16:56:02.151  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:02.151  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:02.151  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:02.151  4098  4108 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 16:56:02.151  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 16:56:02.151  7599  7599 I BluetoothPbapService: Handler(): got msg=1
,09-06 16:56:02.151  4098  4098 D BluetoothMap: Proxy object connected
09-06 16:56:02.151  4098  4098 D MapProfile: Bluetooth service connected
09-06 16:56:02.151  4098  4098 D BluetoothMap: getConnectedDevices()
,09-06 16:56:02.151  1015  1452 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 16:56:02.151  1446  6978 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 16:56:02.151  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 16:56:02.151  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 16:56:02.151  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:02.151  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:02.151  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:02.151  1446  6978 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 16:56:02.151  4098  7569 D BluetoothPan: Binding service...
,09-06 16:56:02.161  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 16:56:02.161  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 16:56:02.161  7599  7667 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-06 16:56:02.161  4098  4098 D HeadsetProfile: Bluetooth service connected
,09-06 16:56:02.161  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:02.161  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:02.161  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:02.161  1446  1463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 16:56:02.161  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 16:56:02.161  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 16:56:02.161  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:02.161  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:02.161  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:02.161  1446  1463 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 16:56:02.161  4098  4115 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 16:56:02.161  4098  4115 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 16:56:02.161  7599  7667 D BluetoothSocket: bindListen(): myUserId = 0
09-06 16:56:02.161  7599  7667 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 16:56:02.171  1951  2159 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 16:56:02.171  1951  2159 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 16:56:02.171  4098  4098 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 16:56:02.171  4098  4098 D PanProfile: Bluetooth service connected
,09-06 16:56:02.171  7599  7667 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-06 16:56:02.171  7599  7667 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 16:56:02.171  7599  7667 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-06 16:56:02.171  7599  7667 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1814b8d5
09-06 16:56:02.171  7599  7667 D BluetoothSocket: channel: 19
09-06 16:56:02.171  7599  7667 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-06 16:56:02.171  4098  4108 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 16:56:02.171  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-06 16:56:02.171  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 16:56:02.171  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:02.171  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:02.171  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:02.171  1446  6978 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 16:56:02.171  1446  6978 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 16:56:02.171  4098  4098 D BluetoothInputDevice: Proxy object connected
09-06 16:56:02.171  4098  4098 D HidProfile: Bluetooth service connected
,09-06 16:56:02.171  1460  1471 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 16:56:02.171  1460  1471 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 16:56:02.171  1479  1708 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 16:56:02.171  1479  1708 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 16:56:02.171  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 16:56:02.171  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 16:56:02.171  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 16:56:02.171  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-06 16:56:02.181  1015  1015 D BluetoothA2dp: Proxy object connected
09-06 16:56:02.181  7599  7609 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 16:56:02.181  7599  7609 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 16:56:02.181  4098  4108 D Bluetoothsap: onBluetoothStateChange: up=true
09-06 16:56:02.181  4098  4108 D Bluetoothsap: Binding service...
,09-06 16:56:02.181  4098  4108 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-06 16:56:02.181  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-06 16:56:02.181  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 16:56:02.181  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:56:02.181  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:02.181  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:02.181  4098  4108 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-06 16:56:02.181  6847  6855 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 16:56:02.181  6847  6855 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 16:56:02.191  4098  4098 D Bluetoothsap: BluetoothSAP Proxy object connected
09-06 16:56:02.191  4098  4098 D SapProfile: Bluetooth service connected
09-06 16:56:02.191  4098  4098 D Bluetoothsap: getConnectedDevices()
,09-06 16:56:02.191  1446  1465 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 16:56:02.191  1015  3412 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 16:56:02.191  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 16:56:02.191  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 16:56:02.191  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:56:02.191  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:02.191  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:02.191  1446  1465 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 16:56:02.191  4098  4115 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 16:56:02.191  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-06 16:56:02.191  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 16:56:02.191  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:56:02.191  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:02.191  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:02.201  4098  4098 D BluetoothPbap: Proxy object connected
09-06 16:56:02.201  4098  4098 D PbapServerProfile: Bluetooth service connected
,09-06 16:56:02.201  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-06 16:56:02.201  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 16:56:02.201  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:56:02.201  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
,09-06 16:56:02.201  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 16:56:02.211  1169  1169 D BluetoothTile:  onBluetoothStateChange:
,09-06 16:56:02.211  1169  1169 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 16:56:02.211  1169  1728 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 16:56:02.211  1169  1728 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 16:56:02.211  1169  1169 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:56:02.211  1169  1169 D BluetoothTile:  getBluetoothState : 12
,09-06 16:56:02.221  1446  1446 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@36047748, true
,09-06 16:56:02.221  1446  1446 D BluetoothHeadset: registerMessageListener
,09-06 16:56:02.221  1870  1870 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 16:56:02.221  4098  4098 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 16:56:02.221  7599  7609 D HeadsetService: registerMessageListener
09-06 16:56:02.221  1015  1452 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 16:56:02.221  1015  1452 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 16:56:02.221  1015  1452 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:02.221  1015  1452 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:56:02.221  1015  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:56:02.231  1169  1728 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 16:56:02.231  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:02.231  7599  7609 D HeadsetService: registerMessageListener
,09-06 16:56:02.231  7599  7632 D HeadsetStateMachine: Disconnected process message: 70
09-06 16:56:02.231  7599  7632 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1ae1c8ea
,09-06 16:56:02.231  1446  1446 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-06 16:56:02.231  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 16:56:02.231  1446  1446 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-06 16:56:02.231  1446  1446 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-06 16:56:02.231  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-06 16:56:02.231  7599  7669 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-06 16:56:02.231  4098  4098 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-06 16:56:02.231  4098  4098 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-06 16:56:02.231  4098  4098 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-06 16:56:02.231  4098  4098 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-06 16:56:02.231  1015  1211 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 16:56:02.241  1015  1028 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-06 16:56:02.241  1169  1169 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 16:56:02.241  7599  7669 D BluetoothSocket: bindListen(): myUserId = 0
09-06 16:56:02.241  7599  7669 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 16:56:02.241  7599  7669 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-06 16:56:02.241  7599  7669 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 16:56:02.241  7599  7669 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 16:56:02.241  7599  7669 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c5607db
,09-06 16:56:02.241  7599  7632 D HeadsetStateMachine: Disconnected process message: 9
09-06 16:56:02.241  7599  7632 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-06 16:56:02.241  7599  7669 D BluetoothSocket: channel: 5
,09-06 16:56:02.251  6847  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:02.251  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:02.251  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:02.251  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 16:56:02.251  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:02.251  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:02.251  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:02.251  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:56:02.251  4098  4098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 16:56:02.251   285   285 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-06 16:56:02.251   285   285 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-06 16:56:02.251   285   285 V voice   : voice_set_parameters: exit with code(-2)
09-06 16:56:02.251   285   285 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-06 16:56:02.251   285   285 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-06 16:56:02.251  1015  1452 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 16:56:02.251   285   285 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-06 16:56:02.251  1015  1452 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-06 16:56:02.251   285   285 V audio_hw_primary: adev_set_parameters: exit
,09-06 16:56:02.251  7599  7632 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
09-06 16:56:02.251  1015  1452 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:02.251  1015  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:02.251  1015  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 16:56:02.251  6847  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:56:02.251  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:02.251  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@202ded8c added. We now have 8 listener(s)
09-06 16:56:02.251  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:56:02.261  1015  1478 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 16:56:02.261  1015  1478 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 16:56:02.261  1015  1478 D SecContentProvider2: mCursor = null
,09-06 16:56:02.261  1015  1478 D WifiService: setWifiEnabled: false pid=6847, uid=10171
09-06 16:56:02.261  1015  1478 D SettingsProvider: name = wifi_on
,09-06 16:56:02.261  4098  4098 D DockEventReceiver: finishStartingService: stopping service
,09-06 16:56:02.271  4098  4098 D BluetoothNotiBroadcastReceiver: onReceive
09-06 16:56:02.271  6847  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:02.271  1015  1452 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 16:56:02.271  1015  1452 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 16:56:02.271  1015  1452 D SecContentProvider2: mCursor = null
,09-06 16:56:02.271  1015  1452 D WifiService: setWifiEnabled: true pid=6847, uid=10171
09-06 16:56:02.271  1015  1452 W ActivityManager: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-06 16:56:02.271  1015  1452 W WifiService: Failed getting userId using ActivityManagerNative
09-06 16:56:02.271  1015  1452 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6847, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-06 16:56:02.271  1015  1452 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-06 16:56:02.271  1015  1452 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 16:56:02.271  1015  1452 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 16:56:02.271  1015  1452 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 16:56:02.271  1015  1452 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-06 16:56:02.271  1015  1452 D SettingsProvider: name = wifi_on
,09-06 16:56:02.271  1169  1169 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 16:56:02.271  1169  1169 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-06 16:56:02.281  1015  1124 E WifiHW  : ##################### set firmware type 0 #####################
,09-06 16:56:02.281  7599  7599 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13729f93
09-06 16:56:02.281  7599  7599 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 16:56:02.281  1015  1213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 16:56:02.281  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-06 16:56:02.281  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:02.281  1015  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:02.281  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 16:56:02.311  1951  1951 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 16:56:02.311  1015  1453 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 16:56:02.311  1015  1453 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:02.311  1015  1453 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
09-06 16:56:02.311  1015  1453 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:56:02.311  1015  1453 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:56:02.311  1015  4041 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 16:56:02.321  1951  7681 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 16:56:02.321  1951  1951 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 16:56:02.331  1015  1211 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 16:56:02.331  1015  1211 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:56:02.331  1015  1211 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:56:02.331  1015  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:56:02.341  7599  7682 D BluetoothSocket: bindListen(): myUserId = 0
09-06 16:56:02.341  7599  7682 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 16:56:02.341  7599  7682 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
09-06 16:56:02.341  7599  7682 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 16:56:02.341  7599  7682 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 16:56:02.341  7599  7682 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f2346b7
09-06 16:56:02.341  7599  7682 D BluetoothSocket: channel: 12
09-06 16:56:02.341  7599  7682 I BtOppRfcommListener: Accept thread started.
,09-06 16:56:02.341  1015  4377 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 16:56:02.351  1015  4377 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:56:02.351  1015  4377 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 16:56:02.351  1015  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:56:02.361  1951  7681 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-06 16:56:02.371  1015  2053 V SAMP_SPCM_test: CSC File load.. 
,09-06 16:56:02.381  1015  3370 D SSRM:n  : SIOP:: AP = 310
,09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
,09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
,09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
,09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-06 16:56:02.381  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-06 16:56:02.401   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application,
09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
,09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
,09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
,09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-06 16:56:02.411  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize,
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
,09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
,09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming,
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
,09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
,09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-06 16:56:02.421  1015  2053 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,09-06 16:56:02.431  1015  2053 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,09-06 16:56:02.431  1015  2053 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 16:56:02.431  1015  2053 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:56:02.431  1015  2053 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:56:02.431  1015  2053 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:56:02.441  7683  7683 E Zygote  : MountEmulatedStorage()
09-06 16:56:02.441  7683  7683 I libpersona: KNOX_SDCARD checking this for 1000
09-06 16:56:02.441  7683  7683 E Zygote  : v2
09-06 16:56:02.441  7683  7683 I libpersona: KNOX_SDCARD not a persona
09-06 16:56:02.441  1015  2053 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7683 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-06 16:56:02.441  7683  7683 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 16:56:02.451  7683  7683 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 16:56:02.451  7683  7683 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 16:56:02.471  7683  7683 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:56:02.471  7683  7683 D ActivityThread: Added TimaKeyStore provider
,09-06 16:56:02.491  7683  7683 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 16:56:02.521  1015  2053 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-06 16:56:02.621  1015  1042 D Tethering: interfaceAdded wlan0
,09-06 16:56:02.621  1015  1128 E Tethering: No numeric data
,09-06 16:56:02.631  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
,09-06 16:56:02.631  1015  1128 D Tethering: clearTetheredNotification(),
09-06 16:56:02.631  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:02.631  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 16:56:02.631  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 16:56:02.631  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 16:56:02.631  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 16:56:02.631  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 16:56:02.641  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 16:56:02.641  1015  1128 D Tethering: InitialState.processMessage what=4
,09-06 16:56:02.641  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:02.641  1015  1121 V NetworkStats: performPollLocked() took 9ms
,09-06 16:56:02.641  1015  1128 E Tethering: No numeric data
09-06 16:56:02.641  1015  1042 D Tethering: interfaceAdded p2p0
,09-06 16:56:02.641  1169  1169 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 16:56:02.651  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-06 16:56:02.651  1169  1169 D HotspotTile: updateTetherState():false, false
,09-06 16:56:02.651  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:56:02.651  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 16:56:02.651  1015  1128 D Tethering: clearTetheredNotification()
,09-06 16:56:02.651  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:56:02.651  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 16:56:02.651  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
09-06 16:56:02.661   277  1013 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-06 16:56:02.661  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 16:56:02.661   277  1013 D SoftapController: Softap fwReload - Ok,
,09-06 16:56:02.661  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:02.661  1169  1169 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 16:56:02.661   277  1013 D CommandListener: Setting iface cfg
09-06 16:56:02.661  1169  1169 D HotspotTile: updateTetherState():false, false
09-06 16:56:02.661   277  1013 D CommandListener: Trying to bring down wlan0
09-06 16:56:02.661  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 16:56:02.661   277  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-06 16:56:02.661  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 16:56:02.661  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 16:56:02.671  1015  1121 V NetworkStats: performPollLocked() took 7ms
,09-06 16:56:02.671  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:56:02.671  1015  1124 E WifiHW  : supplicant_name : p2p_supplicant
,09-06 16:56:02.671  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:02.671  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:56:02.691   292   292 E SMD     : DCD OFF,
,09-06 16:56:02.711  7706  7706 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-06 16:56:02.711  7706  7706 I wpa_supplicant: Successfully initialized wpa_supplicant
09-06 16:56:02.711  7706  7706 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-06 16:56:02.721  7706  7706 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-06 16:56:02.731   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7706,
09-06 16:56:02.731   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 16:56:02.731  7706  7706 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
09-06 16:56:02.731  7706  7706 I wpa_supplicant: ssSupport state is = 1
09-06 16:56:02.731  7706  7706 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,09-06 16:56:02.731  7706  7706 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-06 16:56:02.731   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7706,
09-06 16:56:02.731   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-06 16:56:02.781  1015  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
09-06 16:56:02.781  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-06 16:56:02.781  1169  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 16:56:02.781  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 16:56:02.781  1169  1169 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 16:56:02.781  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 16:56:02.781  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:02.781  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:02.781  1169  1169 D HotspotTile: onReceive : 2, 0
09-06 16:56:02.781  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 16:56:02.781  1169  1169 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 16:56:02.781  1169  1169 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-06 16:56:02.781  4098  4098 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 16:56:02.791  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:02.791  1015  1213 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 16:56:02.791  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 16:56:02.791  1015  1213 W ActivityManager: userId = 0, bbcId = -10000,
09-06 16:56:02.791  1015  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 16:56:02.791  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 16:56:02.791  1619  1619 I Hs20UtilService: Starting #19
,09-06 16:56:02.791  1619  1674 I Hs20UtilService: Message received 5011
,09-06 16:56:02.801  6637  6637 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 16:56:02.801  6637  6637 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 16:56:02.801  6637  6637 D SecurityLogAgent: StateMachine : Current State = 1,
09-06 16:56:02.801  6637  6637 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 16:56:02.891   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,09-06 16:56:02.891  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-06 16:56:02.941  7706  7706 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 16:56:02.941  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 16:56:02.951  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-06 16:56:02.951   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7706
09-06 16:56:02.951   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 16:56:02.951  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,09-06 16:56:02.951  7706  7706 I wpa_supplicant: ssSupport state is = 1
09-06 16:56:02.951  7706  7706 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 16:56:02.951  7706  7706 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 16:56:02.951  7706  7706 E wpa_supplicant: SIM READ ERROR
,09-06 16:56:02.951  7706  7706 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 16:56:02.951  7706  7706 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 16:56:02.951  7706  7706 E wpa_supplicant: SIM READ ERROR
09-06 16:56:02.951  7706  7706 I wpa_supplicant: Blacklist: Clear (all) 
09-06 16:56:02.951  7706  7706 I wpa_supplicant: wpa_default_ap_write_once
09-06 16:56:02.951  7706  7706 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
09-06 16:56:02.951  7706  7706 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 16:56:02.951  7706  7706 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-06 16:56:02.951  7706  7706 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 16:56:02.951  7706  7706 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-06 16:56:02.951  7706  7706 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-06 16:56:02.951  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-06 16:56:02.951  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 16:56:02.951  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 16:56:03.021  7706  7706 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-06 16:56:03.181  7706  7706 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-06 16:56:03.181  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-06 16:56:03.191  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-06 16:56:03.191   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7706
09-06 16:56:03.191   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 16:56:03.191  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,09-06 16:56:03.191  7706  7706 I wpa_supplicant: ssSupport state is = 1
09-06 16:56:03.191  7706  7706 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 16:56:03.201  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 16:56:03.211  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-06 16:56:03.211   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7706
09-06 16:56:03.211   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 16:56:03.211  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-06 16:56:03.211  7706  7706 I wpa_supplicant: ssSupport state is = 1
09-06 16:56:03.211  7706  7706 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 16:56:03.211  7706  7706 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-06 16:56:03.211  7706  7706 E wpa_supplicant: SIM READ ERROR
09-06 16:56:03.211  7706  7706 I wpa_supplicant: wpa_default_ap_write_once
09-06 16:56:03.211  7706  7706 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,09-06 16:56:03.211  7706  7706 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 16:56:03.211  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 16:56:03.211  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
09-06 16:56:03.211  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 16:56:03.221  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
09-06 16:56:03.221  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 16:56:03.221  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-06 16:56:03.361  7706  7706 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-06 16:56:03.361  7706  7706 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=,
,09-06 16:56:03.411   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 16:56:03.421  7706  7706 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-06 16:56:03.421  7706  7706 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-06 16:56:03.421  7706  7706 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 16:56:03.431  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
09-06 16:56:03.431  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 16:56:03.431  7706  7706 I wpa_supplicant: HOTSPOT20_ENABLE called
09-06 16:56:03.431  7706  7706 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-06 16:56:03.431  7706  7706 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-06 16:56:03.431  7706  7706 E wpa_supplicant: SIM READ ERROR
,09-06 16:56:03.431  7706  7706 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 16:56:03.461  7706  7706 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-06 16:56:03.471  7706  7706 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 16:56:03.471  1015  1124 D WifiConfigStore: Loading config and enabling all networks 
,09-06 16:56:03.471  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-06 16:56:03.471  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 16:56:03.471  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:03.471  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:03.471  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:03.471  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 16:56:03.471  1169  1169 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 16:56:03.471  1169  1728 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 16:56:03.471  1169  1169 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-06 16:56:03.471  1169  1169 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 16:56:03.481  1169  1169 D HotspotTile: onReceive : 3, 0
,09-06 16:56:03.481  4098  4098 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 16:56:03.481  1015  1124 E WifiConfigStore: Not a HS20
,09-06 16:56:03.481  1015  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 16:56:03.491  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:03.491  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:03.491  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:03.491  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:03.491  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:03.491  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:03.491  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:03.491  6847  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:56:03.491  1015  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-06 16:56:03.491  1015  1496 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 16:56:03.491  6847  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:56:03.491  1015  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-06 16:56:03.491  7706  7706 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-06 16:56:03.491  7706  7706 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-06 16:56:03.491  7706  7706 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 16:56:03.491  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 16:56:03.491  7706  7706 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 16:56:03.491  7706  7706 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-06 16:56:03.491  7706  7706 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-06 16:56:03.491  7706  7706 I wpa_supplicant: First Scan Start
09-06 16:56:03.491  7706  7706 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 16:56:03.491  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:56:03.491  1015  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:03.491  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 16:56:03.501  1015  1124 D WifiNative-wlan0: Setting external_sim to 1
,09-06 16:56:03.501  1015  1124 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 16:56:03.501  1015  1124 I WifiNative-HAL: startHal
09-06 16:56:03.501  1015  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9d58288c
09-06 16:56:03.501  1015  1124 I WifiNative-HAL: Could not start hal
,09-06 16:56:03.501  7014  7014 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 16:56:03.501  1619  1619 I Hs20UtilService: Starting #20
,09-06 16:56:03.501  1619  1674 I Hs20UtilService: Message received 5011
,09-06 16:56:03.501  1015  1124 E WifiNative-wlan0: do suspend true
09-06 16:56:03.501  6637  6637 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 16:56:03.501  6637  6637 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 16:56:03.501  6637  6637 D SecurityLogAgent: StateMachine : Current State = 1
09-06 16:56:03.501  6637  6637 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 16:56:03.501  1015  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-06 16:56:03.511   277  1013 D CommandListener: Setting iface cfg
09-06 16:56:03.511   277  1013 D CommandListener: Trying to bring up p2p0
,09-06 16:56:03.511  1015  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-06 16:56:03.511  1015  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 16:56:03.511  1015  1123 D WifiP2pService: P2pEnablingState
09-06 16:56:03.511  1015  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-06 16:56:03.511  1015  1123 D WifiP2pService: P2p socket connection successful
,09-06 16:56:03.511  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3,
09-06 16:56:03.511  1015  1123 D WifiP2pService: P2pEnabledState
09-06 16:56:03.511  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:03.511  1015  1147 I WifiNative-HAL: startHal
09-06 16:56:03.511  1015  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9ea3a9bc
09-06 16:56:03.511  1015  1147 I WifiNative-HAL: Could not start hal
09-06 16:56:03.511  1015  1147 E WifiScanningService: could not start HAL
09-06 16:56:03.511  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 16:56:03.511  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 16:56:03.511  1015  1124 E WifiNative-wlan0: invaild command id : 215
09-06 16:56:03.511  1015  1015 D RttService: SCAN_AVAILABLE : 3
09-06 16:56:03.511  1015  1148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 16:56:03.511  1015  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-06 16:56:03.521  1015  1126 E ConnectivityService: updateNetworkInfo()
,09-06 16:56:03.521  7706  7706 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 16:56:03.521  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 16:56:03.521  7706  7706 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-06 16:56:03.521  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-06 16:56:03.521  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 16:56:03.521  1015  1045 D WifiDisplayController: disconnect
09-06 16:56:03.521  1015  1045 D WifiDisplayController: updateConnection
09-06 16:56:03.521  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 16:56:03.521  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 16:56:03.521  7706  7706 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-06 16:56:03.521  1015  1124 E WifiStateMachine: Failed to set frequency band 0
,09-06 16:56:03.521  1015  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 16:56:03.521  1015  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 16:56:03.521  1015  1124 E WifiNative-wlan0: invaild command id : 215
,09-06 16:56:03.521  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-06 16:56:03.521  1015  1124 D SecContentProvider2: mCursor = null
,09-06 16:56:03.521  1169  1169 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 16:56:03.521  1015  1211 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 16:56:03.521  1169  1169 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 16:56:03.531  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress
09-06 16:56:03.531  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 16:56:03.531  1015  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
09-06 16:56:03.531  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
09-06 16:56:03.531  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 16:56:03.531  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 16:56:03.531  4098  4098 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 16:56:03.531  4098  4098 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 16:56:03.531  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
09-06 16:56:03.531  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 16:56:03.531  1015  1124 D SecContentProvider2: mCursor = null
09-06 16:56:03.531  1015  1123 D WifiP2pService: DeviceAddress: 0a:76:28
,09-06 16:56:03.531  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 16:56:03.531  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-06 16:56:03.531  4098  4098 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 16:56:03.531  4098  4213 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 16:56:03.531  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-06 16:56:03.531  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-06 16:56:03.531  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
09-06 16:56:03.531  1015  1045 D WifiDisplayController:  secondary type: null
09-06 16:56:03.531  1015  1045 D WifiDisplayController:  wps: 0
09-06 16:56:03.531  1015  1045 D WifiDisplayController:  grpcapab: 0
09-06 16:56:03.531  1015  1045 D WifiDisplayController:  devcapab: 0
09-06 16:56:03.531  1015  1045 D WifiDisplayController:  status: 3
09-06 16:56:03.531  1015  1045 D WifiDisplayController:  wfdInfo: null
09-06 16:56:03.531  1015  1045 D WifiDisplayController:  groupownerAddress: null
09-06 16:56:03.531  1015  1045 D WifiDisplayController:  GOdeviceName: null
09-06 16:56:03.531  1015  1045 D WifiDisplayController:  interfaceAddress: 
09-06 16:56:03.531  1015  1045 D WifiDisplayController:  SConnectInfo : null
,09-06 16:56:03.541  7395  7395 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 16:56:03.541  7395  7395 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-06 16:56:03.541  7395  7395 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 16:56:03.541  7412  7412 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 16:56:03.551  1015  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-06 16:56:03.551  1015  1123 D WifiP2pService: InactiveState
,09-06 16:56:03.551  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
,09-06 16:56:03.551  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 16:56:03.551  7706  7706 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-06 16:56:03.551  1015  1123 D WifiP2pService: InactiveState{ what=143376 }
,09-06 16:56:03.551  1015  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 16:56:03.631  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,09-06 16:56:03.631  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-06 16:56:03.631  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 16:56:04.291  6847  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 16:56:04.291  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:04.291  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:04.291  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:04.291  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:04.291  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:04.291  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:04.291  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:56:04.301  6847  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:56:04.301  6847  6901 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-06 16:56:04.301  6847  6901 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-06 16:56:04.311  6847  6901 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@25d29383 Bundle[{}]
,09-06 16:56:04.311  6847  6901 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 16:56:04.311  6847  6901 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-06 16:56:04.311  6847  6901 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-06 16:56:04.311  6847  6901 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-06 16:56:04.311  6847  6901 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-06 16:56:04.311  6847  6901 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 16:56:04.321  6847  6901 I System.out: Running OutgoingSocketThread
,09-06 16:56:04.321  6847  7715 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1350)
,09-06 16:56:04.321  6847  7715 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 54768
,09-06 16:56:04.321  6847  7715 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-06 16:56:04.411   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,09-06 16:56:04.771  7706  7706 I wpa_supplicant: nl80211: Received scan results (27 BSSes)
09-06 16:56:04.771  7706  7706 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 16:56:04.781  1015  7712 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
09-06 16:56:04.781  7706  7706 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-06 16:56:04.781  7706  7706 I wpa_supplicant: Trying to associate with  'G700'
09-06 16:56:04.781  7706  7706 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-06 16:56:04.781  7706  7706 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-06 16:56:04.801  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 16:56:04.801  1015  1124 D SecContentProvider2: mCursor = null
,09-06 16:56:04.891  7706  7706 E wpa_supplicant: Cmd 35605 not handled
,09-06 16:56:04.891  7706  7706 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 16:56:04.891  7706  7706 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
09-06 16:56:04.891  7706  7706 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-06 16:56:04.891  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 16:56:04.891  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 16:56:04.891  7706  7706 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-06 16:56:04.891  7706  7706 I wpa_supplicant: Associated with F4.99.3E
09-06 16:56:04.891  7706  7706 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 16:56:04.891  7706  7706 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-06 16:56:04.891  7706  7706 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-06 16:56:04.891  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 16:56:04.891  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 16:56:04.891  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 16:56:04.891  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 16:56:04.891  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-06 16:56:04.891  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 16:56:04.891  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 16:56:04.901  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 16:56:04.901  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-06 16:56:04.901  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
09-06 16:56:04.901  1015  1128 E Tethering: No numeric data
,09-06 16:56:04.901  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-06 16:56:04.901  1015  1128 D Tethering: clearTetheredNotification()
09-06 16:56:04.901  7706  7706 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 16:56:04.901  7706  7706 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-06 16:56:04.901  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 16:56:04.901  1015  1124 D SecContentProvider2: mCursor = null
09-06 16:56:04.901  7706  7706 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-06 16:56:04.901  7706  7706 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-06 16:56:04.901  7706  7706 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 16:56:04.901  7706  7706 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,09-06 16:56:04.901  7706  7706 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-06 16:56:04.911  7706  7706 I wpa_supplicant: Blacklist: Clear (temp) 
09-06 16:56:04.911  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
09-06 16:56:04.911  7706  7706 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-06 16:56:04.911  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
,09-06 16:56:04.911  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 16:56:04.911  1169  1169 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 16:56:04.911  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
09-06 16:56:04.911  1169  1169 D HotspotTile: updateTetherState():false, false
09-06 16:56:04.911  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:04.911  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 16:56:04.911  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 16:56:04.911  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 16:56:04.911  1015  1124 D SecContentProvider2: mCursor = null
,09-06 16:56:04.921  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:56:04.921  1015  1121 V NetworkStats: performPollLocked() took 9ms
09-06 16:56:04.921  1015  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
09-06 16:56:04.921  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:04.921  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:56:04.921  1015  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,09-06 16:56:04.931  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 16:56:04.931  1015  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-06 16:56:04.931  1015  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-06 16:56:04.931  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 16:56:04.931  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 16:56:04.931  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 16:56:04.931  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:04.931  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:04.931  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 16:56:04.931  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 16:56:04.941  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 16:56:04.941  1015  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 16:56:04.941  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 16:56:04.941  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:04.941  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:04.941  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 16:56:04.941  1619  1619 I Hs20UtilService: Starting #21
,09-06 16:56:04.941  4098  4098 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 16:56:04.941  4098  4098 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 16:56:04.951  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 16:56:04.951  1015  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-06 16:56:04.951  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 16:56:04.951  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false,
09-06 16:56:04.951  4098  4098 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 16:56:04.951  4098  4213 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 16:56:04.961   277  1013 D CommandListener: Setting iface cfg
,09-06 16:56:04.961  1619  1674 I Hs20UtilService: Message received 5007
,09-06 16:56:04.961  1015  1124 E WifiStateMachine: Start Dhcp Watchdog 3
,09-06 16:56:04.971  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 16:56:04.971  1015  1124 D SecContentProvider2: mCursor = null
,09-06 16:56:04.971  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-06 16:56:04.971  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 16:56:04.971  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 16:56:04.971  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:04.971  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:04.971  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-06 16:56:04.981  1015  1124 E WifiNative-wlan0: do suspend false,
,09-06 16:56:04.981  1015  1123 D WifiP2pService: InactiveState{ what=143375 },
09-06 16:56:04.981  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
09-06 16:56:04.991  1015  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 16:56:04.991  1015  1124 D SecContentProvider2: mCursor = null
,09-06 16:56:05.201  7718  7718 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-06 16:56:05.201  7718  7718 I dhcpcd  : version 5.5.6 starting
,09-06 16:56:05.211  7718  7718 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-06 16:56:05.271  7718  7718 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-06 16:56:05.271  7718  7718 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address,
09-06 16:56:05.271  7718  7718 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-06 16:56:05.271  7718  7718 I dhcpcd  : bssid match
,09-06 16:56:05.271  7718  7718 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,09-06 16:56:05.321  7718  7718 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
09-06 16:56:05.321  6847  6901 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1351),
09-06 16:56:05.321  6847  6901 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1351)
09-06 16:56:05.321  6847  6901 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1356)
09-06 16:56:05.321  6847  6901 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-06 16:56:05.321  6847  6901 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1357),
09-06 16:56:05.331  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-06 16:56:05.331  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3836fcd5 added. We now have 2 listener(s),
,09-06 16:56:05.331  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 16:56:05.331  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 16:56:05.331  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 16:56:05.331  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:05.331  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1230bcea added. We now have 9 listener(s)
09-06 16:56:05.331  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:56:05.331  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 16:56:05.341  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:56:05.341  6847  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-06 16:56:05.341  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:05.341  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:05.341  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:05.341  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:05.341  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:05.341  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:05.341  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 16:56:05.341  6847  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:56:05.341  6847  6901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:56:05.341  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:05.341  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b925678 added. We now have 3 listener(s)
,09-06 16:56:05.341  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:05.341  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:05.351  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 16:56:05.351  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 16:56:05.351  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-06 16:56:05.351  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:05.351  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c779151 added. We now have 10 listener(s)
,09-06 16:56:05.351  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:05.351  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:56:05.351  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:56:05.351  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:56:05.351  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:05.351  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:05.351  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:05.351  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
09-06 16:56:05.351  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3836fcd5 removed from the list
09-06 16:56:05.351  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:05.351  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1230bcea removed from the list
09-06 16:56:05.351  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 16:56:05.351  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:05.351  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:05.351  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:05.351  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 16:56:05.351  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 16:56:05.351  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:05.351  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1230bcea not in the list
09-06 16:56:05.351  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:05.351  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:05.351  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:05.351  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:05.351  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 16:56:05.351  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c779151 removed from the list
09-06 16:56:05.351  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:05.351  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:05.351  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:05.351  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-06 16:56:05.351  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b925678 removed from the list
09-06 16:56:05.351  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:05.351  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32d5bdb6 added. We now have 2 listener(s)
,09-06 16:56:05.361  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
09-06 16:56:05.361  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:05.361  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 16:56:05.361  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:05.361  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35936ab7 added. We now have 9 listener(s)
09-06 16:56:05.361  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:05.361  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 16:56:05.361  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-06 16:56:05.361  6847  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-06 16:56:05.361  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:05.361  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:05.361  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:05.361  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:05.361  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:05.361  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:05.361  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:56:05.371  6847  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-06 16:56:05.371  6847  6901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:56:05.371  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 16:56:05.371  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3152f18d added. We now have 3 listener(s)
,09-06 16:56:05.371  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:05.371  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:05.371  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 16:56:05.371  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:05.371  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:05.371  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-06 16:56:05.371  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25f7ff42 added. We now have 10 listener(s)
09-06 16:56:05.371  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:05.371  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:56:05.371  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
09-06 16:56:05.371  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:56:05.371  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:56:05.371  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 16:56:05.371  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 16:56:05.381  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
09-06 16:56:05.381  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,09-06 16:56:05.381  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-06 16:56:05.381  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 16:56:05.381  6847  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 16:56:05.391  7599  7607 D BtGatt.GattService: registerClient() - UUID=50598b8d-8639-4d28-90b8-679aea75931a,
,09-06 16:56:05.441  7718  7718 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
09-06 16:56:05.441  7599  7624 D BtGatt.GattService: onClientRegistered() - UUID=50598b8d-8639-4d28-90b8-679aea75931a, clientIf=6
09-06 16:56:05.441  6847  6855 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-06 16:56:05.441  7599  7665 D BtGatt.GattService: start scan with filters
,09-06 16:56:05.441  7599  7631 D BtGatt.ScanManager: handling starting scan
,09-06 16:56:05.441  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
09-06 16:56:05.441  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 16:56:05.441  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 16:56:05.441  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 16:56:05.441  7599  7631 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13729f93
,09-06 16:56:05.451  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-06 16:56:05.451  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 16:56:05.451  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 16:56:05.451  7599  7624 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 16:56:05.451  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:56:05.451  7599  7631 D BtGatt.ScanManager: allow scan with filters
09-06 16:56:05.451  7599  7631 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 16:56:05.451  7599  7631 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-06 16:56:05.451  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 16:56:05.451  7599  7624 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 16:56:05.451  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:56:05.451  7599  7631 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 16:56:05.451  7599  7631 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 16:56:05.461  7599  7624 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 16:56:05.461  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:56:05.461  7599  7624 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 16:56:05.461  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:56:05.461  6847  6901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 16:56:05.461  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 16:56:05.461  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 16:56:05.461  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:05.461  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 16:56:05.461  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 16:56:05.461  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 16:56:05.461  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 16:56:05.461  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 16:56:05.461  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 16:56:05.461  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 16:56:05.471  7599  7607 D BtGatt.GattService: stopScan() - queue size =1
,09-06 16:56:05.471  7599  7665 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 16:56:05.471  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 16:56:05.471  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-06 16:56:05.481  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 16:56:05.481  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 16:56:05.481  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 16:56:05.481  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:56:05.481  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 16:56:05.481  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 16:56:05.481  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 16:56:05.481  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 16:56:05.481  7599  7631 D BtGatt.ScanManager: filter size is 1,
09-06 16:56:05.481  7599  7631 D BtGatt.ScanManager: delete FilterIndex - 3
,09-06 16:56:05.481  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:56:05.481  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-06 16:56:05.481  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:56:05.481  7599  7624 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 16:56:05.481  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:56:05.481  7599  7631 D BtGatt.ScanManager: stopping BLe Batch
,09-06 16:56:05.491  7599  7624 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 16:56:05.491  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:56:05.491  7599  7631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 16:56:05.491  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-06 16:56:05.491  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 16:56:05.491  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-06 16:56:05.491  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-06 16:56:05.491  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:05.491  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:05.491  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
09-06 16:56:05.491  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32d5bdb6 removed from the list
09-06 16:56:05.491  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:05.491  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35936ab7 removed from the list
09-06 16:56:05.491  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:56:05.491  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:56:05.491  7599  7624 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 16:56:05.491  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:56:05.491  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:05.491  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:56:05.491  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:05.491  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:05.491  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:05.491  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35936ab7 not in the list
09-06 16:56:05.491  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:05.491  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:56:05.491  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-06 16:56:05.491  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:05.491  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-06 16:56:05.491  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25f7ff42 removed from the list
09-06 16:56:05.491  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,09-06 16:56:05.491  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:05.491  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:05.491  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:05.491  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3152f18d removed from the list
09-06 16:56:05.501  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:05.501  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0acd8e added. We now have 2 listener(s)
,09-06 16:56:05.501  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 16:56:05.501  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:05.501  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:05.501  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:05.501  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@380ef9af added. We now have 9 listener(s)
09-06 16:56:05.501  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:56:05.501  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 16:56:05.501  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:56:05.511  6847  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:56:05.511  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:05.511  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:05.511  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:05.511  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:05.511  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:05.511  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:05.511  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:56:05.521  6847  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:56:05.521  6847  6901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:56:05.521  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:05.521  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32f1c545 added. We now have 3 listener(s)
,09-06 16:56:05.521  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-06 16:56:05.521  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 16:56:05.521  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:05.521  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:05.521  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336a349a added. We now have 10 listener(s)
09-06 16:56:05.521  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:56:05.521  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:56:05.521  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:05.521  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 16:56:05.521  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 16:56:05.521  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:56:05.521  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:56:05.521  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 16:56:05.521  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:05.531  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,09-06 16:56:05.541  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 16:56:05.541  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 16:56:05.551  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 16:56:05.551  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 16:56:05.551  6847  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 16:56:05.561  7599  7665 D BtGatt.GattService: registerClient() - UUID=f7a48eec-3bd1-4d5e-b8a7-e3312ea2a162
,09-06 16:56:05.601  7599  7624 D BtGatt.GattService: onClientRegistered() - UUID=f7a48eec-3bd1-4d5e-b8a7-e3312ea2a162, clientIf=6
09-06 16:56:05.601  6847  6855 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-06 16:56:05.601  7599  7609 D BtGatt.GattService: start scan with filters
09-06 16:56:05.601  7599  7631 D BtGatt.ScanManager: handling starting scan
09-06 16:56:05.601  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 16:56:05.601  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 16:56:05.601  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 16:56:05.601  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 16:56:05.601  7599  7624 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-06 16:56:05.601  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:56:05.611  7599  7631 D BtGatt.ScanManager: allow scan with filters
09-06 16:56:05.611  7599  7631 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 16:56:05.611  7599  7631 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
09-06 16:56:05.611  7599  7624 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 16:56:05.611  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:56:05.611  7599  7631 D BtGatt.ScanManager: Starting BLE batch scan
09-06 16:56:05.611  7599  7631 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
09-06 16:56:05.611  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 16:56:05.611  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 16:56:05.611  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 16:56:05.611  7599  7624 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 16:56:05.611  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:56:05.611  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 16:56:05.611  7599  7624 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-06 16:56:05.611  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:56:05.621  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
09-06 16:56:05.621  6847  6901 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-06 16:56:05.621  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:56:05.621  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:56:05.621  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 16:56:05.621  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:05.621  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-06 16:56:05.621  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 16:56:05.621  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:05.621  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0acd8e removed from the list
09-06 16:56:05.621  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:05.621  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@380ef9af removed from the list
,09-06 16:56:05.621  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:56:05.621  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:05.621  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:05.621  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 16:56:05.621  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 16:56:05.621  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:05.621  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:05.621  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:05.621  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:05.621  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@380ef9af not in the list
09-06 16:56:05.621  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-06 16:56:05.621  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 16:56:05.621  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 16:56:05.621  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 16:56:05.621  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 16:56:05.621  7599  7609 D BtGatt.GattService: stopScan() - queue size =1
,09-06 16:56:05.631  7599  7631 D BtGatt.ScanManager: filter size is 1
09-06 16:56:05.631  7599  7631 D BtGatt.ScanManager: delete FilterIndex - 4
09-06 16:56:05.631  7599  7668 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 16:56:05.631  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-06 16:56:05.631  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 16:56:05.631  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-06 16:56:05.631  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 16:56:05.631  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 16:56:05.631  7599  7624 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 16:56:05.631  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:56:05.631  7599  7631 D BtGatt.ScanManager: stopping BLe Batch
09-06 16:56:05.631  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 16:56:05.631  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 16:56:05.631  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 16:56:05.631  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 16:56:05.631  7599  7624 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 16:56:05.631  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:56:05.631  7599  7631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 16:56:05.631  7599  7624 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-06 16:56:05.631  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:56:05.631  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:56:05.641  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:56:05.641  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:56:05.641  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:56:05.641  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:05.641  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:05.641  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:05.641  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336a349a removed from the list
09-06 16:56:05.641  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:05.641  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:05.641  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:05.641  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:05.641  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32f1c545 removed from the list
,09-06 16:56:05.641  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:05.641  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18270066 added. We now have 2 listener(s)
,09-06 16:56:05.641  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 16:56:05.641  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:05.641  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
09-06 16:56:05.641  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:05.641  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f9e6fa7 added. We now have 9 listener(s)
09-06 16:56:05.641  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:05.641  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 16:56:05.651  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:56:05.651  6847  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:56:05.651  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:05.651  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:05.651  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
09-06 16:56:05.651  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:05.651  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:05.651  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:05.651  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:56:05.661  6847  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-06 16:56:05.661  6847  6901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:56:05.661  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:05.661  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10b057fd added. We now have 3 listener(s)
09-06 16:56:05.661  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:05.661  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 16:56:05.661  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:05.661  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:05.661  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:05.661  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2092bcf2 added. We now have 10 listener(s)
09-06 16:56:05.661  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:05.661  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:56:05.661  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 16:56:05.661  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 16:56:05.661  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 16:56:05.661  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 16:56:05.661  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 16:56:05.671  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 16:56:05.671  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 16:56:05.671  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 16:56:05.681  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 16:56:05.681  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 16:56:05.681  6847  6901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 16:56:05.681  7599  7609 D BtGatt.GattService: registerClient() - UUID=ea8e747a-e6b5-432a-81e6-4679d1246003
,09-06 16:56:05.691   292   292 E SMD     : DCD OFF,
,09-06 16:56:05.721  7599  7624 D BtGatt.GattService: onClientRegistered() - UUID=ea8e747a-e6b5-432a-81e6-4679d1246003, clientIf=6,
09-06 16:56:05.721  6847  6857 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 16:56:05.721  7599  7607 D BtGatt.GattService: start scan with filters
,09-06 16:56:05.721  7599  7631 D BtGatt.ScanManager: handling starting scan
,09-06 16:56:05.721  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,09-06 16:56:05.731  7599  7624 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 16:56:05.731  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:56:05.731  7599  7631 D BtGatt.ScanManager: allow scan with filters
,09-06 16:56:05.731  7599  7631 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 16:56:05.731  7599  7631 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-06 16:56:05.731  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 16:56:05.731  7599  7624 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 16:56:05.731  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:56:05.731  7599  7631 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 16:56:05.731  7599  7631 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 16:56:05.741  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
09-06 16:56:05.741  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 16:56:05.741  7599  7624 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 16:56:05.741  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:56:05.741  7599  7624 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 16:56:05.741  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 16:56:05.751  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 16:56:05.751  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 16:56:05.751  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 16:56:05.751  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 16:56:05.761  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 16:56:05.761  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 16:56:05.761  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 16:56:05.761  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 16:56:05.761  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 16:56:05.761  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 16:56:05.761  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
09-06 16:56:05.761  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18270066 removed from the list,
,09-06 16:56:05.761  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:05.761  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f9e6fa7 removed from the list,
09-06 16:56:05.761  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:56:05.761  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 16:56:05.761  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed,
09-06 16:56:05.761  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 16:56:05.761  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-06 16:56:05.761  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 16:56:05.771  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-06 16:56:05.771  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:05.771  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 16:56:05.771  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f9e6fa7 not in the list,
09-06 16:56:05.771  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 16:56:05.771  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 16:56:05.771  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 16:56:05.771  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 16:56:05.771  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 16:56:05.771  7599  7609 D BtGatt.GattService: stopScan() - queue size =1
09-06 16:56:05.771  7599  7631 D BtGatt.ScanManager: filter size is 1,
09-06 16:56:05.771  7599  7607 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 16:56:05.771  7599  7631 D BtGatt.ScanManager: delete FilterIndex - 5
09-06 16:56:05.771  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 16:56:05.771  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 16:56:05.771  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-06 16:56:05.771  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 16:56:05.771  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 16:56:05.771  7599  7624 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 16:56:05.771  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
09-06 16:56:05.771  7599  7631 D BtGatt.ScanManager: stopping BLe Batch
09-06 16:56:05.771  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 16:56:05.771  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 16:56:05.771  6847  6901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 16:56:05.771  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 16:56:05.771  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:56:05.781  7599  7624 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 16:56:05.781  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:56:05.781  7599  7631 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 16:56:05.781  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 16:56:05.781  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:05.781  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:05.781  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2092bcf2 removed from the list
09-06 16:56:05.781  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 16:56:05.781  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:05.781  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:05.781  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:05.781  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10b057fd removed from the list
,09-06 16:56:05.781  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:56:05.781  6847  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 16:56:05.781  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:05.781  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@358bb63e added. We now have 2 listener(s)
09-06 16:56:05.781  7599  7624 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-06 16:56:05.781  7599  7624 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 16:56:05.781  6847  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 16:56:05.781  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 16:56:05.781  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:05.781  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 16:56:05.781  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:05.781  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff7ac9f added. We now have 9 listener(s)
,09-06 16:56:05.781  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 16:56:05.781  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 16:56:05.791  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 16:56:05.791  6847  6901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 16:56:05.791  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 16:56:05.791  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 16:56:05.791  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 16:56:05.791  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 16:56:05.791  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 16:56:05.791  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 16:56:05.791  6847  6901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 16:56:05.791  6847  6901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 16:56:05.791  6847  6901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 16:56:05.791  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 16:56:05.791  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18e789b5 added. We now have 3 listener(s)
,09-06 16:56:05.791  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-06 16:56:05.791  1015  1124 E WifiNative-wlan0: do suspend true
,09-06 16:56:05.801  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-06 16:56:05.801  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 16:56:05.801  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 16:56:05.801  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 16:56:05.801  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d88f84a added. We now have 10 listener(s)
09-06 16:56:05.801  6847  6901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 16:56:05.801  6847  6901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 16:56:05.801  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 16:56:05.801  6847  6901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 16:56:05.801  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:05.801  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:05.801  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 16:56:05.801  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:05.801  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@358bb63e removed from the list
09-06 16:56:05.801  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:05.801  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff7ac9f removed from the list
,09-06 16:56:05.801  6847  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 16:56:05.801  6847  6901 D io.jxcore.node.ConnectivityMonitor: stop
09-06 16:56:05.801  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:56:05.801  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:05.801  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:56:05.801  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:05.801  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:05.801  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:05.801  6847  6901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff7ac9f not in the list
09-06 16:56:05.801  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:05.801  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 16:56:05.801  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 16:56:05.801  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 16:56:05.801  6847  6901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 16:56:05.801  6847  6901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d88f84a removed from the list
09-06 16:56:05.801  6847  6901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 16:56:05.801  6847  6901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 16:56:05.801  6847  6901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 16:56:05.801  6847  6901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 16:56:05.801  6847  6901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18e789b5 removed from the list
,09-06 16:56:05.801  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-06 16:56:05.801  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-06 16:56:05.801  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 16:56:05.801  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 16:56:05.801  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 16:56:05.801  6847  6901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 16:56:05.811  6847  7749 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1364, name: My test thread name)
09-06 16:56:05.811  6847  7749 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1364, thread name: My test thread name)
09-06 16:56:05.811  6847  7749 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1364, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 16:56:05.811  6847  7750 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1366, name: My test thread name)
09-06 16:56:05.811  6847  7750 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1366, thread name: My test thread name)
09-06 16:56:05.811  6847  7750 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1366, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 16:56:05.811  6847  6901 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-06 16:56:05.811  6847  6901 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 16:56:05.811  6847  6901 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-06 16:56:05.811  6847  6901 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 16:56:05.811  6847  6901 D com.test.thalitest.ThaliTestRunner: Total duration: 23289 ms
09-06 16:56:05.821  6847  6901 I jxcore-log: *Native tests were executed*
09-06 16:56:05.821  6847  6901 I jxcore-log: 
09-06 16:56:05.821  6847  6901 I jxcore-log: Total number of executed tests:  80
09-06 16:56:05.821  6847  6901 I jxcore-log: 
09-06 16:56:05.821  6847  6901 I jxcore-log: Number of passed tests:  80
09-06 16:56:05.821  6847  6901 I jxcore-log: 
09-06 16:56:05.821  6847  6901 I jxcore-log: Number of failed tests:  0
09-06 16:56:05.821  6847  6901 I jxcore-log: 
09-06 16:56:05.821  6847  6901 I jxcore-log: Number of ignored tests:  0
09-06 16:56:05.821  6847  6901 I jxcore-log: 
09-06 16:56:05.821  6847  6901 I jxcore-log: Total duration:  23289
09-06 16:56:05.821  6847  6901 I jxcore-log: 
09-06 16:56:05.821  6847  6901 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 16:56:05.821  6847  6901 I jxcore-log: 
09-06 16:56:05.821  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:05.821  6847  6901 I jxcore-log: 
09-06 16:56:05.821  1015  1123 D WifiP2pService: InactiveState{ what=143375 }
09-06 16:56:05.821  1015  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
09-06 16:56:05.831  1015  1124 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-06 16:56:05.831  1015  1124 E WifiStateMachine: VerifyingLinkState enter
09-06 16:56:05.831  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:05.831  6847  6901 I jxcore-log: 
09-06 16:56:05.831  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 16:56:05.831  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 16:56:05.831  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.831  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.831  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.831  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.831  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:05.831  6847  6901 I jxcore-log: 
09-06 16:56:05.831  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:05.831  6847  6901 I jxcore-log: 
09-06 16:56:05.831  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:05.831  6847  6901 I jxcore-log: 
09-06 16:56:05.831  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:05.831  6847  6901 I jxcore-log: 
09-06 16:56:05.831  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 16:56:05.841  1015  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-06 16:56:05.841  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 16:56:05.841  6847  6901 I jxcore-log: 
09-06 16:56:05.841  1015  1126 D ConnectivityService: Adding iface wlan0 to network 504
09-06 16:56:05.841  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:05.841  6847  6901 I jxcore-log: 
09-06 16:56:05.841  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:05.841  6847  6901 I jxcore-log: 
09-06 16:56:05.841  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 16:56:05.841  6847  6901 I jxcore-log: 
09-06 16:56:05.841  6847  6847 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-06 16:56:05.841  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 16:56:05.841  6847  6901 I jxcore-log: 
09-06 16:56:05.841  1015  1141 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-06 16:56:05.851  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 16:56:05.851  6847  6901 I jxcore-log: 
09-06 16:56:05.851  1015  1141 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 16:56:05.851  1015  1141 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 16:56:05.851  1015  1141 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 16:56:05.851  1015  1141 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 16:56:05.851  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:05.851  6847  6901 I jxcore-log: 
09-06 16:56:05.851  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:05.851  6847  6901 I jxcore-log: 
09-06 16:56:05.851  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 16:56:05.851  6847  6901 I jxcore-log: 
09-06 16:56:05.851  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 16:56:05.851  6847  6901 I jxcore-log: 
09-06 16:56:05.851  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:05.851  6847  6901 I jxcore-log: 
09-06 16:56:05.851  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 16:56:05.851  6847  6901 I jxcore-log: 
09-06 16:56:05.851  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 16:56:05.851  6847  6901 I jxcore-log: 
09-06 16:56:05.851  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 16:56:05.851  6847  6901 I jxcore-log: 
09-06 16:56:05.861  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 16:56:05.861  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 16:56:05.861  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.861  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.861  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.861  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.861  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 16:56:05.861  6847  6901 I jxcore-log: 
09-06 16:56:05.861  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 16:56:05.861  6847  6901 I jxcore-log: 
09-06 16:56:05.871  1015  4377 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 16:56:05.861  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 16:56:05.861  6847  6901 I jxcore-log: 
09-06 16:56:05.871  1015  4377 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 16:56:05.861  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 16:56:05.861  6847  6901 I jxcore-log: 
09-06 16:56:05.871  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 16:56:05.871  6847  6901 I jxcore-log: 
09-06 16:56:05.871  1015  1124 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
09-06 16:56:05.871  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 16:56:05.871  6847  6901 I jxcore-log: 
09-06 16:56:05.871  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 16:56:05.871  6847  6901 I jxcore-log: 
09-06 16:56:05.871  1015  4377 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:05.871  1015  4377 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:05.871  1015  4377 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 16:56:05.871  1015  1126 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
09-06 16:56:05.871  4098  4098 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 16:56:05.871  1015  1126 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
09-06 16:56:05.871  1619  1619 I Hs20UtilService: Starting #22
09-06 16:56:05.871  4098  4098 I NearbySettings: MountReceiver.onReceive - Keep current state
09-06 16:56:05.871  1619  1674 I Hs20UtilService: Message received 5007
09-06 16:56:05.881  1015  1126 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
09-06 16:56:05.881  1015  1126 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 16:56:05.881  1015  1126 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-06 16:56:05.881  1015  1126 D ConnectivityService: LTETest block dns file not exists
09-06 16:56:05.881  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 16:56:05.891  1169  1169 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 16:56:05.891  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 16:56:05.891  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.891  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.891  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.891  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.891  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:05.891  1015  1126 V NetworkStats: updateIfacesLocked()
09-06 16:56:05.891  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
09-06 16:56:05.891  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 16:56:05.891  1015  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 16:56:05.891  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 16:56:05.891  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
09-06 16:56:05.891  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
09-06 16:56:05.891  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 16:56:05.891  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 16:56:05.891  1015  1126 V NetworkStats: performPollLocked() took 5ms
09-06 16:56:05.901  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:05.901  1169  1169 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 16:56:05.901  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 16:56:05.901  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.901  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.901  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.901  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.901  1015  1452 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 16:56:05.901  1015  1452 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 16:56:05.911  1015  1452 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:05.911  1015  1452 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:05.911  1015  1452 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 16:56:05.911  1619  1619 I Hs20UtilService: Starting #23
09-06 16:56:05.911  1619  1674 I Hs20UtilService: Message received 5007
09-06 16:56:05.911  1015  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-06 16:56:05.911  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 16:56:05.911  1015  1126 E ConnectivityService: updateNetworkInfo()
09-06 16:56:05.911  1015  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 16:56:05.911  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:05.911  1015  1126 V NetworkStats: updateIfacesLocked()
09-06 16:56:05.911  1015  1126 V NetworkStats: performPollLocked(flags=0x1)
09-06 16:56:05.911  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 16:56:05.921  1015  1126 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 16:56:05.921  1015  1126 V NetworkStats: performPollLocked() took 4ms
09-06 16:56:05.921  1015  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:05.921  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:05.921  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:56:05.931  4098  4098 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 16:56:05.931  1015  1126 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-06 16:56:05.931  1015  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-06 16:56:05.931  1015  7716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler },
09-06 16:56:05.931  1015  7716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-06 16:56:05.931  1015  7716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 16:56:05.931  1015  7716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-06 16:56:05.931  1015  7716 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 16:56:05.931  4098  4098 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 16:56:05.931   277  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 16:56:05.931   277  1009 D Netd    : getNetworkForDns: using netid 504 for uid 1000
09-06 16:56:05.931  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 16:56:05.931  1015  1126 D ConnectivityService:    accepting network in place of null
09-06 16:56:05.931  1015  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 16:56:05.941  1479  1479 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-06 16:56:05.941  1479  1479 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 16:56:05.941  1015  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-06 16:56:05.941  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 16:56:05.941  4098  4098 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 16:56:05.941  4098  4098 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 16:56:05.941  1015  1126 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 16:56:05.941  1015  1126 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-06 16:56:05.941  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 16:56:05.941  4098  4213 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 16:56:05.941  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:05.941  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-06 16:56:05.941  1015  1126 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-06 16:56:05.941  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-06 16:56:05.941  1015  1128 D Tethering: MasterInitialState.processMessage what=3
,09-06 16:56:05.941  1015  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504],
,09-06 16:56:05.941  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-06 16:56:05.941  1015  1121 V NetworkStats: updateIfacesLocked()
,09-06 16:56:05.941  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:05.941  1015  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 16:56:05.941  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 16:56:05.941  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 16:56:05.951  1169  1712 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 16:56:05.951  4873  6909 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 16:56:05.951  1169  1169 D StatusBar.NetworkController: EthernetConnected: false
09-06 16:56:05.951  1169  1169 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-06 16:56:05.951  1169  1169 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 16:56:05.951  1169  1169 D StatusBar.NetworkController: updateDataNetType()
09-06 16:56:05.951  1015  1121 V NetworkStats: performPollLocked() took 8ms
09-06 16:56:05.951  1169  1169 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-06 16:56:05.951  1169  1169 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-06 16:56:05.951  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:56:05.951  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:05.951  1015  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-06 16:56:05.951  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:05.951  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:05.951  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:56:05.961  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:05.961  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:05.961  1169  1169 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-06 16:56:05.961  1169  1169 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-06 16:56:05.961  1169  1169 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-06 16:56:05.961  1169  1169 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 16:56:05.961  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 16:56:05.961  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.961  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.961  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:05.961  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 16:56:05.961  1015  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 16:56:05.961  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 16:56:05.971  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:05.971  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:05.971  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 16:56:05.971  1619  1619 I Hs20UtilService: Starting #24
,09-06 16:56:05.971  1619  1674 I Hs20UtilService: Message received 5007
,09-06 16:56:05.971  4098  4098 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 16:56:05.971  4098  4098 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-06 16:56:05.981  1015  1485 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-06 16:56:05.981  1015  1453 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-06 16:56:05.981  1015  1453 D SecContentProvider2: mCursor = null
,09-06 16:56:05.981  1015  1213 D SecContentProvider2: uri = 15 selection = getToastGravity
09-06 16:56:05.981  1015  1213 D SecContentProvider2: mCursor = null
,09-06 16:56:05.981  1015  1495 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-06 16:56:05.981  1015  1495 D SecContentProvider2: mCursor = null
,09-06 16:56:05.981  6847  6847 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-06 16:56:05.981  1015  1027 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-06 16:56:05.981  1015  1027 D SecContentProvider2: mCursor = null
,09-06 16:56:05.981  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 16:56:05.981  6847  6901 I jxcore-log: 
,09-06 16:56:05.991  1015  4041 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-06 16:56:05.991  1015  4041 D SecContentProvider2: mCursor = null
,09-06 16:56:05.991  1015  1452 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState,
09-06 16:56:05.991  1015  1452 D SecContentProvider2: mCursor = null
,09-06 16:56:06.011   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-06 16:56:06.031  1015  1213 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,09-06 16:56:06.031  1169  1169 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-06 16:56:06.061  1015  7716 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 16:56:06.111  7754  7754 D AndroidRuntime: 
09-06 16:56:06.111  7754  7754 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-06 16:56:06.121  7754  7754 D AndroidRuntime: CheckJNI is OFF
,09-06 16:56:06.121  7754  7754 D AndroidRuntime: readGMSProperty: start
09-06 16:56:06.121  7754  7754 D AndroidRuntime: readGMSProperty: already setted!!
09-06 16:56:06.121  7754  7754 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-06 16:56:06.121  7754  7754 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-06 16:56:06.121  7754  7754 D AndroidRuntime: readGMSProperty: end
09-06 16:56:06.121  7754  7754 D AndroidRuntime: addProductProperty: start
,09-06 16:56:06.121  1015  7716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 14:56:06 GMT], X-Android-Received-Millis=[1473173766130], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473173766099]}
,09-06 16:56:06.121  1015  7716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-06 16:56:06.121  1015  7716 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-06 16:56:06.121  1015  1126 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504],
09-06 16:56:06.121  1015  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-06 16:56:06.121  1015  1126 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-06 16:56:06.121  1015  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-06 16:56:06.121  1169  1712 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-06 16:56:06.121  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-06 16:56:06.121  4873  6909 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290,
,09-06 16:56:06.131  1169  1169 D StatusBar.NetworkController: EthernetConnected: false,
09-06 16:56:06.131  1169  1169 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-06 16:56:06.131  1169  1169 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 16:56:06.131  1169  1169 D StatusBar.NetworkController: updateDataNetType(),
09-06 16:56:06.131  1169  1169 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-06 16:56:06.131  1169  1169 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-06 16:56:06.131  1169  1169 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-06 16:56:06.131  1169  1169 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-06 16:56:06.131  1169  1169 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-06 16:56:06.131  1169  1169 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 16:56:06.131  1169  1169 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 16:56:06.131  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 16:56:06.131  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:06.131  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 16:56:06.131  1169  1169 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 16:56:06.141  6847  6847 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-06 16:56:06.141  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 16:56:06.141  6847  6901 I jxcore-log: 
,09-06 16:56:06.151  1015  1453 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-06 16:56:06.151  1015  1453 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-06 16:56:06.151  1015  1453 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-06 16:56:06.151  1015  1453 D BatteryService: stay LED for fully charged
09-06 16:56:06.151  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 16:56:06.151  1015  1015 I MotionRecognitionService: Plugged,
09-06 16:56:06.151  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 16:56:06.161  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 16:56:06.161  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 16:56:06.161  1169  1169 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 16:56:06.161  1169  1169 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-06 16:56:06.161  1169  1169 D SViewCoverView: level :100 plugged : 2
,09-06 16:56:06.171  1169  1169 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 16:56:06.171  7599  7599 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 16:56:06.171  7599  7632 D HeadsetStateMachine: Disconnected process message: 10
,09-06 16:56:06.181  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
09-06 16:56:06.181  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-06 16:56:06.181  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-06 16:56:06.241  7754  7754 E AffinityControl: AffinityControl: registerfunction enter
,09-06 16:56:06.271  7754  7754 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,09-06 16:56:06.281  6847  6847 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-06 16:56:06.281  6847  6901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 16:56:06.281  6847  6901 I jxcore-log: 
,09-06 16:56:06.281  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-06 16:56:06.281  1015  1028 D PackageManager: START PACKAGE DELETE: observer{178479232}
09-06 16:56:06.281  1015  1028 D PackageManager: pkg{<packageName>}
09-06 16:56:06.281  1015  1028 D PackageManager: user{0}
09-06 16:56:06.281  1015  1028 D PackageManager: caller{2000}
09-06 16:56:06.281  1015  1028 D PackageManager: flags{2}
09-06 16:56:06.281  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
09-06 16:56:06.281  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-06 16:56:06.281  1015  1028 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-06 16:56:06.281  1015  1028 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-06 16:56:06.291  1015  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
09-06 16:56:06.291  1015  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-06 16:56:06.291  1015  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-06 16:56:06.291  1015  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
,09-06 16:56:06.291  1015  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-06 16:56:06.291  1015  1054 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,09-06 16:56:06.321  1015  1040 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,09-06 16:56:06.321  1015  1040 I ActivityManager: Killing 6847:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-06 16:56:06.381  1015  1054 W PackageSettings: Skipping PackageSetting{1a3dc452 com.example.hello/10168} due to missing metadata
,09-06 16:56:06.411  1015  1485 I WindowState: WIN DEATH: Window{2597aaf3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 16:56:06.411   257   449 I SurfaceFlinger: id=13 Removed NainActivit (6/9),
,09-06 16:56:06.411   257  1990 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
09-06 16:56:06.421  1015  1040 I ActivityManager:   Force finishing activity ActivityRecord{23612713 u0 com.test.thalitest/.MainActivity t2}
,09-06 16:56:06.421  1015  1485 D InputDispatcher: Focus left window: 6847,
,09-06 16:56:06.431  1015  4041 W ActivityManager: Spurious death for ProcessRecord{31f746b9 6847:com.test.thalitest/u0a171}, curProc for 6847: null,
,09-06 16:56:06.441  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
09-06 16:56:06.441  1015  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:06.441  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 16:56:06.451  1015  1054 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-06 16:56:06.451  1015  1054 I ActivityManager:   Force finishing activity ActivityRecord{23612713 u0 com.test.thalitest/.MainActivity t2 f}
09-06 16:56:06.451  1015  1054 W ActivityManager: Duplicate finish request for ActivityRecord{23612713 u0 com.test.thalitest/.MainActivity t2 f}
,09-06 16:56:06.471  1015  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-06 16:56:06.511  1015  1040 D InputDispatcher: Focused application released
,09-06 16:56:06.511  1015  1040 D FocusedStackFrame: Set to : 0
,09-06 16:56:06.511  1015  1040 W ActivityManager: mDVFSHelper.acquire()
,09-06 16:56:06.521  1015  1040 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,09-06 16:56:06.531  2645  2645 I art     : Explicit concurrent mark sweep GC freed 19510(1113KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 813us total 58.896ms
,09-06 16:56:06.541  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:56:06.541  4873  4873 I art     : Explicit concurrent mark sweep GC freed 19974(1181KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 12MB/21MB, paused 3.010ms total 88.485ms
,09-06 16:56:06.551  1497  1497 D Launcher: onRestart, Launcher: 585365449
,09-06 16:56:06.581  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 16:56:06.601  1870  1870 E SamsungIME: mOCRHelper is null
,09-06 16:56:06.611  1015  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
,09-06 16:56:06.611  1015  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-06 16:56:06.611  1015  1039 W TextServicesManagerService: no available spell checker services found
,09-06 16:56:06.621  1015  1121 V NetworkStats: removeUidsLocked() for UIDs [10171]
09-06 16:56:06.621  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 16:56:06.621  1015  1121 V NetworkStats: performPollLocked(flags=0x3)
,09-06 16:56:06.621  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 16:56:06.621  1015  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 16:56:06.631  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 16:56:06.631  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 16:56:06.631  1015  1121 V NetworkStats: performPollLocked() took 15ms
,09-06 16:56:06.631  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:56:06.631  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-06 16:56:06.641  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:56:06.641  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:56:06.641  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:56:06.641  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:56:06.651  7769  7769 E Zygote  : MountEmulatedStorage()
09-06 16:56:06.651  7769  7769 E Zygote  : v2
09-06 16:56:06.651  7769  7769 I libpersona: KNOX_SDCARD checking this for 1000
09-06 16:56:06.651  7769  7769 I libpersona: KNOX_SDCARD not a persona
,09-06 16:56:06.651  7769  7769 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 16:56:06.661  1015  1040 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7769 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-06 16:56:06.661  7769  7769 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 16:56:06.661  7769  7769 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 16:56:06.661  1497  1497 D Launcher: onStart, Launcher: 585365449
09-06 16:56:06.661  1497  1497 D Launcher.HomeView: onStart
09-06 16:56:06.661  1497  1497 D Launcher: onResume, Launcher: 585365449
,09-06 16:56:06.671  1015  1496 D SettingsProvider: name = kids_home_mode
09-06 16:56:06.671  1015  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 16:56:06.671  1015  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 16:56:06.671  1015  1496 D SettingsProvider: selectionArgs: false
09-06 16:56:06.671  1015  1496 D SettingsProvider: selectionArgs: 10006
09-06 16:56:06.671  1015  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 16:56:06.671  1015  1496 D SettingsProvider: ret = -1
09-06 16:56:06.671  1497  1497 D Launcher.HomeView: onResume
,09-06 16:56:06.671  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 16:56:06.681  1460  1460 D PersonaManager: isKioskContainerExistOnDevice,
,09-06 16:56:06.681  1460  1460 D RegisteredServicesCache: empty dynamic service,
,09-06 16:56:06.681  1497  1497 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-06 16:56:06.691  1497  1497 D MenuAppsGridFragment: onResume
,09-06 16:56:06.691  1015  1015 I art     : Explicit concurrent mark sweep GC freed 78401(4MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 24MB/37MB, paused 3.175ms total 217.908ms
09-06 16:56:06.691  1015  1054 I art     : WaitForGcToComplete blocked for 213.138ms for cause Explicit
,09-06 16:56:06.691  1497  1497 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-06 16:56:06.691  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
09-06 16:56:06.691  1497  1497 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-06 16:56:06.711  1015  1028 D ActivityManager: handle home activity for 0
09-06 16:56:06.711  1460  1460 D RegisteredComponentCache: Collect Tech packages for Knox
,09-06 16:56:06.711  1015  1028 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,09-06 16:56:06.711  1015  1028 D KnoxTimeoutHandler: post home show event for user 0
09-06 16:56:06.711  1015  1028 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-06 16:56:06.711  1015  1028 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 16:56:06.711  1015  1028 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-06 16:56:06.711  1460  1460 D PersonaManager: isKioskContainerExistOnDevice
,09-06 16:56:06.711  1497  1497 D Launcher.HomeView: onPause
,09-06 16:56:06.711  1497  1497 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-06 16:56:06.721  7769  7769 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:56:06.721  7769  7769 D ActivityThread: Added TimaKeyStore provider
,09-06 16:56:06.731  1015  1485 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-06 16:56:06.731  1015  1485 D SecContentProvider2: mCursor = null
,09-06 16:56:06.741   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,09-06 16:56:06.741  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-06 16:56:06.741  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-06 16:56:06.751  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:56:06.751  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 16:56:06.751  1015  4377 D InputDispatcher: Focus entered window: 1497
,09-06 16:56:06.751  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 16:56:06.751  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 16:56:06.761  1497  1497 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-06 16:56:06.771  1497  1497 D Launcher.HomeView: onStop
09-06 16:56:06.771  1497  1497 V ActivityThread: updateVisibility : ActivityRecord{3bac45c token=android.os.BinderProxy@9905841 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,09-06 16:56:06.791  1015  1452 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-06 16:56:06.791  1015  1452 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6847 uid 10171
,09-06 16:56:06.801  7769  7769 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true,
09-06 16:56:06.801  7769  7769 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-06 16:56:06.801  7769  7769 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
09-06 16:56:06.801  1870  1870 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-06 16:56:06.811  1015  7786 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-06 16:56:06.821  7769  7769 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true,
09-06 16:56:06.821  7769  7769 I PCWCLIENTTRACE_PushUtil: sales region : global
09-06 16:56:06.821  1015  1211 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 6 r.nextReceiver= 1 receivers.size=28
09-06 16:56:06.821  7769  7769 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-06 16:56:06.821  1015  1211 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
09-06 16:56:06.821  7769  7769 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:56:06.831  1015  1211 I ActivityManager: Killing 7121:com.sec.android.soagent/u0a31 (adj 15): empty #21
,09-06 16:56:06.851  1015  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-06 16:56:06.861  1752  1752 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 16:56:06.861  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-06 16:56:06.861  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,09-06 16:56:06.861  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:06.861  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:06.861  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-06 16:56:06.871  1015  4377 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-06 16:56:06.871  1015  4377 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.sec.android.soagent/com.sec.android.soagent.RegisterReceiver}
09-06 16:56:06.871  1015  4377 W BroadcastQueue: android.os.TransactionTooLargeException
09-06 16:56:06.871  1015  4377 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 16:56:06.871  1015  4377 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 16:56:06.871  1015  4377 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-06 16:56:06.871  1015  4377 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-06 16:56:06.871  1015  4377 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-06 16:56:06.871  1015  4377 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-06 16:56:06.871  1015  4377 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-06 16:56:06.871  1015  4377 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-06 16:56:06.871  1015  4377 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 16:56:06.871  7136  7136 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
09-06 16:56:06.871  1015  4377 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-06 16:56:06.871  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 16:56:06.881  1015  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:56:06.881  1015  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:56:06.881  1015  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:56:06.881  1015  4377 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:56:06.881  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 16:56:06.891  7790  7790 E Zygote  : MountEmulatedStorage()
09-06 16:56:06.891  7790  7790 E Zygote  : v2
09-06 16:56:06.891  7790  7790 I libpersona: KNOX_SDCARD checking this for 10031
09-06 16:56:06.891  7790  7790 I libpersona: KNOX_SDCARD not a persona
,09-06 16:56:06.891  7790  7790 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 16:56:06.901  7790  7790 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 16:56:06.901  7790  7790 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 16:56:06.901  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,09-06 16:56:06.901  1015  4377 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7790 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,09-06 16:56:06.901  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0,
09-06 16:56:06.911  1015  4041 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-06 16:56:06.911  1015  4041 D SecContentProvider2: mCursor = null
,09-06 16:56:06.921  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,09-06 16:56:06.921  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-06 16:56:06.921  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,09-06 16:56:06.931  7136  7136 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
09-06 16:56:06.931  1015  1045 W ActivityManager: mDVFSHelper.release()
09-06 16:56:06.931  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{166892b0 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:147196
09-06 16:56:06.931  7790  7790 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 16:56:06.931  7136  7136 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
09-06 16:56:06.931  7790  7790 D ActivityThread: Added TimaKeyStore provider
09-06 16:56:06.941  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
09-06 16:56:06.941  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
09-06 16:56:06.941  1015  1054 I art     : Explicit concurrent mark sweep GC freed 15272(1243KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 11.017ms total 250.732ms
09-06 16:56:06.941  1015  1126 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-06 16:56:06.951  2479  2487 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,09-06 16:56:06.951  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 16:56:06.971  1015  1495 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 16:56:06.971  1752  1752 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-06 16:56:06.971  1951  2158 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 16:56:06.981  1752  1752 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-06 16:56:06.981  1015  1211 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 16:56:06.981  1752  1752 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,09-06 16:56:06.991  1752  1752 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-06 16:56:07.001  7279  7279 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-06 16:56:07.001  1752  1752 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 16:56:07.001  1752  1752 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-06 16:56:07.011  1015  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-06 16:56:07.011  1015  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 16:56:07.011  1015  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 16:56:07.011  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 16:56:07.021  1015  1054 D PackageManager: delete codoeFile: 
,09-06 16:56:07.021  1015  1478 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
,09-06 16:56:07.031  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,09-06 16:56:07.031  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:07.031  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:56:07.031  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,09-06 16:56:07.031  1015  1054 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,09-06 16:56:07.031  1015  1054 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,09-06 16:56:07.031  1015  1054 D PackageManager: result of delete: 1{178479232}
,09-06 16:56:07.051  7754  7754 D AndroidRuntime: Shutting down VM
,09-06 16:56:07.051  1015  1478 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-06 16:56:07.051  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-06 16:56:07.051  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:07.051  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:56:07.051  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 16:56:07.081  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 16:56:07.091  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 16:56:07.091  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-06 16:56:07.091  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-06 16:56:07.091  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-06 16:56:07.091  7014  7810 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-06 16:56:07.091  1015  1015 V EnterpriseBillingPolicy: uID is 10171
09-06 16:56:07.091  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-06 16:56:07.091  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-06 16:56:07.091  7014  7810 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 16:56:07.091  7014  7810 I System.out: (HTTPLog)-Static: isShipBuild true
09-06 16:56:07.091  7014  7810 I System.out: (HTTPLog)-Thread-1256-529383412: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-06 16:56:07.091  7014  7810 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 16:56:07.091  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-06 16:56:07.091  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-06 16:56:07.091  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-06 16:56:07.091  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-06 16:56:07.091  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-06 16:56:07.091  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 16:56:07.091  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
09-06 16:56:07.091   277  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 16:56:07.091   277  1009 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,09-06 16:56:07.091  2785  7812 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
09-06 16:56:07.091  2785  7812 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
09-06 16:56:07.091  7169  7169 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,09-06 16:56:07.091  2785  7812 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-06 16:56:07.101  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 16:56:07.101  7217  7217 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-06 16:56:07.101  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-06 16:56:07.101  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 16:56:07.101  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-06 16:56:07.101  1015  1015 V EnterpriseBillingPolicy: uID is 10171
09-06 16:56:07.101  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-06 16:56:07.101  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-06 16:56:07.101  1015  1158 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
09-06 16:56:07.101  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-06 16:56:07.101  1015  3370 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-06 16:56:07.101  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-06 16:56:07.101  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-06 16:56:07.101  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-06 16:56:07.101  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-06 16:56:07.111  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-06 16:56:07.111  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
09-06 16:56:07.111  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
09-06 16:56:07.111  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
09-06 16:56:07.111  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-06 16:56:07.111  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,09-06 16:56:07.111  7217  7217 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,09-06 16:56:07.111  7217  7217 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-06 16:56:07.121  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,09-06 16:56:07.121  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 16:56:07.121  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 16:56:07.121  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 16:56:07.121  7217  7217 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-06 16:56:07.121  7217  7217 I SA      : [OR] == isSIMCardReady false ==
,09-06 16:56:07.121  7217  7217 I SA      : [SCU] == networkStateCheck == true
,09-06 16:56:07.131  1169  1169 I StatusBar: Icon Only
09-06 16:56:07.131  1169  1169 D PanelView: There is/are notification(s) 
,09-06 16:56:07.131  7217  7217 I SA      : [DM] getCountryCodeFromCSC : PL
09-06 16:56:07.131  7217  7217 I SA      : isChinaCountryCode : false,
09-06 16:56:07.131  7217  7217 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-06 16:56:07.131  7217  7217 I SA      : [OR] == networkStateCheck true ==
,09-06 16:56:07.141  7217  7217 I SA      : [OR] GetMyCountryZoneTask
,09-06 16:56:07.141  7217  7217 I SA      : [OR] onReceive END
,09-06 16:56:07.141  7014  7810 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 16:56:07.151  1224  1224 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-06 16:56:07.151  1015  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-06 16:56:07.151  1015  4041 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
09-06 16:56:07.151  1015  4041 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,09-06 16:56:07.151  1015  4041 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:07.151  2785  7812 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,09-06 16:56:07.151  7217  7815 I SA      : [SRS] prepareGetMyCountryZone
,09-06 16:56:07.151  1015  4041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 16:56:07.151  1015  4041 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
09-06 16:56:07.151  2785  7812 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,09-06 16:56:07.151  2785  7812 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,09-06 16:56:07.161  1015  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
09-06 16:56:07.161  2785  7812 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,09-06 16:56:07.161  2785  7812 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,09-06 16:56:07.161  2785  7812 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,09-06 16:56:07.161  2785  7812 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,09-06 16:56:07.161  2785  7812 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,09-06 16:56:07.171  1015  1039 W libprocessgroup: failed to open /acct/uid_10031/pid_7121/cgroup.procs: No such file or directory
,09-06 16:56:07.171  2785  7812 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,09-06 16:56:07.181  7217  7815 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-06 16:56:07.181  7217  7815 I SA      : [SSP] query invoked
,09-06 16:56:07.181  1015  4377 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,09-06 16:56:07.181  1015  4377 D SecContentProvider2: mCursor = null
,09-06 16:56:07.191  7217  7815 I SA      : [TPMU] GetMccFromDB : null
,09-06 16:56:07.191  7217  7815 I SA      : [SCU] getMccFromPreferece mcc = 260
,09-06 16:56:07.191  7217  7815 I SA      : [LBE] isSupportCheckDomainRegion : false
09-06 16:56:07.191  7217  7815 I SA      : [TPM] isNoProxy(default) : true
,09-06 16:56:07.201  7217  7815 E File    : fail readDirectory() errno=2
,09-06 16:56:07.211  2785  7812 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-06 16:56:07.221  7014  7810 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-06 16:56:07.261  7754  7754 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-06 16:56:07.281  1497  1497 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9905841 time:147544
,09-06 16:56:07.301  1015  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-06 16:56:07.301  1015  1054 D PackageManager: userId{-1}
09-06 16:56:07.301  1015  1054 D PackageManager: andCode{true}
,09-06 16:56:07.301  1015  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-06 16:56:07.301  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:56:07.301  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:56:07.301  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:56:07.301  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:56:07.311  7819  7819 E Zygote  : MountEmulatedStorage(),
,09-06 16:56:07.311  7819  7819 E Zygote  : v2,
09-06 16:56:07.311  7819  7819 I libpersona: KNOX_SDCARD checking this for 10003,
09-06 16:56:07.311  7819  7819 I libpersona: KNOX_SDCARD not a persona
,09-06 16:56:07.321  7819  7819 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-06 16:56:07.321  1015  1054 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7819 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-06 16:56:07.331  7819  7819 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-06 16:56:07.331  7819  7819 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 16:56:07.341   321   321 I art     : Explicit concurrent mark sweep GC freed 8691(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 23.973ms
,09-06 16:56:07.351  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-06 16:56:07.351  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:56:07.351  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:56:07.351  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 16:56:07.351  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 16:56:07.351  7819  7819 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 16:56:07.351  7819  7819 D ActivityThread: Added TimaKeyStore provider
,09-06 16:56:07.361   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 16.694ms
,09-06 16:56:07.381   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 561us total 16.412ms
,09-06 16:56:07.391  7835  7835 E Zygote  : MountEmulatedStorage(),
09-06 16:56:07.391  7835  7835 E Zygote  : v2
09-06 16:56:07.391  7835  7835 I libpersona: KNOX_SDCARD checking this for 10001
09-06 16:56:07.391  7835  7835 I libpersona: KNOX_SDCARD not a persona,
09-06 16:56:07.391  7835  7835 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-06 16:56:07.391  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7835 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-06 16:56:07.401  1015  1485 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
09-06 16:56:07.401  1015  1485 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,09-06 16:56:07.401  7835  7835 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-06 16:56:07.401  1015  1485 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:07.401  1015  1485 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-06 16:56:07.401  1015  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
09-06 16:56:07.401  7835  7835 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 16:56:07.411  1015  4041 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 16:56:07.411  1015  4041 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-06 16:56:07.411  1015  4041 W ActivityManager: userId = 0, bbcId = -10000
09-06 16:56:07.411  1015  4041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:56:07.411  1015  4041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 16:56:07.421  1015  1478 I ActivityManager: Killing 7200:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,09-06 16:56:07.431  7835  7835 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 16:56:07.431  7835  7835 D ActivityThread: Added TimaKeyStore provider
,09-06 16:56:07.431  7279  7279 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,09-06 16:56:07.441   277  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-06 16:56:07.441   277  1009 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,09-06 16:56:07.441  4873  4873 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-06 16:56:07.441  7279  7279 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,09-06 16:56:07.441  7279  7279 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
09-06 16:56:07.441  7279  7279 D InitializeManagerStateMachine: exit::IDLE
09-06 16:56:07.441  7279  7279 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,09-06 16:56:07.451  7279  7279 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
09-06 16:56:07.451  7279  7279 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-06 16:56:07.451  7279  7279 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-06 16:56:07.451  7279  7279 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-06 16:56:07.451  7279  7279 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-06 16:56:07.451  7279  7279 D InitializeManagerStateMachine: entry::SUCCESS
09-06 16:56:07.451  7279  7279 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-06 16:56:07.451  7279  7279 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-06 16:56:07.451  4873  7315 I iu.UploadsManager: num queued entries: 0
09-06 16:56:07.451  7279  7279 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,09-06 16:56:07.461  4873  7315 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-06 16:56:07.461  4873  7315 E SQLiteLog: (3850) statement aborts at 61: [UPDATE media_record SET upload_state=? WHERE upload_account_id != -1 AND upload_state = 200] disk I/O error
,09-06 16:56:07.461  7279  7279 E SharedPreferencesImpl: Couldn't rename file /data/data/com.sec.android.app.samsungapps/shared_prefs/SamsungAppsPreferences.xml to backup file /data/data/com.sec.android.app.samsungapps/shared_prefs/SamsungAppsPreferences.xml.bak
,09-06 16:56:07.461  7279  7279 D InitializeManagerStateMachine: exit::SUCCESS
09-06 16:56:07.461  7279  7279 D InitializeManagerStateMachine: entry::IDLE
,09-06 16:56:07.461  1015  1027 I ActivityManager: Killing 7263:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-06 16:56:07.481  1015  1027 I ActivityManager: Killing 7247:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-06 16:56:07.491  1015  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 16:56:07.491  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.AnalyticsService; callingUser = 0; userId(target) = 0
,09-06 16:56:07.491  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,09-06 16:56:07.491  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 16:56:07.491  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 16:56:07.491  4873  5243 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,09-06 16:56:07.491  4873  5243 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-06 16:56:07.491  4873  5243 E GAv4-SVC: Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,09-06 16:56:07.501  4873  5243 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
09-06 16:56:07.501  4873  5243 E GAv4-SVC: Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
09-06 16:56:07.501  4873  5057 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,09-06 16:56:07.501  4873  5057 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,09-06 16:56:07.501  1015  1496 D PersonaManager: isKioskContainerExistOnDevice

```
