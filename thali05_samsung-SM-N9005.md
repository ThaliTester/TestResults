#### Test 79689775e33639d_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
08-03 17:25:30.014   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,08-03 17:25:31.015   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
08-03 17:25:31.204  7725  7725 D AndroidRuntime: 
08-03 17:25:31.204  7725  7725 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-03 17:25:31.204  7725  7725 D AndroidRuntime: CheckJNI is OFF
08-03 17:25:31.204  7725  7725 D AndroidRuntime: readGMSProperty: start
08-03 17:25:31.204  7725  7725 D AndroidRuntime: readGMSProperty: already setted!!
08-03 17:25:31.204  7725  7725 D AndroidRuntime: readGMSProperty: end
08-03 17:25:31.204  7725  7725 D AndroidRuntime: addProductProperty: start
08-03 17:25:31.374  7725  7725 E AffinityControl: AffinityControl: registerfunction enter
08-03 17:25:31.404  7725  7725 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-03 17:25:31.404   772  1526 E PersonaManagerService: inState():  stateMachine is null !!
08-03 17:25:31.404   772  1526 I PersonaManagerService: PersonaId don't exist
08-03 17:25:31.404   772  1526 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-03 17:25:31.404   772  1526 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-03 17:25:31.414   772  1526 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-03 17:25:31.414   772  1526 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
08-03 17:25:31.414   772  1526 W ActivityManager: mDVFSHelper.acquire()
08-03 17:25:31.414   772  1526 D FocusedStackFrame: Set to : 0
08-03 17:25:31.414   772  1526 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:31.414   772  1526 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:31.424   772  1526 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:31.424   772  1526 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:31.474   772  1526 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7740 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-03 17:25:31.474   772  1058 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-03 17:25:31.474   772  1058 D PointerIcon: setMouseCustomIcon IconType is same.101
08-03 17:25:31.474   772  1058 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-03 17:25:31.474   772  1058 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-03 17:25:31.484  7740  7740 E Zygote  : MountEmulatedStorage()
08-03 17:25:31.484  7740  7740 E Zygote  : v2
08-03 17:25:31.484  7740  7740 I libpersona: KNOX_SDCARD checking this for 10079
08-03 17:25:31.484  7740  7740 I libpersona: KNOX_SDCARD not a persona
08-03 17:25:31.484  7725  7725 D AndroidRuntime: Shutting down VM
08-03 17:25:31.504  7740  7740 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-03 17:25:31.504  7740  7740 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-03 17:25:31.504  7740  7740 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-03 17:25:31.554  7740  7740 D TimaKeyStoreProvider: TimaSignature is unavailable
08-03 17:25:31.554  7740  7740 D ActivityThread: Added TimaKeyStore provider
08-03 17:25:31.554   772  1375 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-03 17:25:31.554   772  1375 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-03 17:25:31.554   772  1375 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-03 17:25:31.554   772  1375 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-03 17:25:31.554   772  1375 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-03 17:25:31.584  1426  1426 D SurfaceWidgetView: destroyHardwareResources():421828631
08-03 17:25:31.594   772  3303 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 17:25:31.604  7740  7740 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
08-03 17:25:31.634   772  3303 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 17:25:31.654   267  1863 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
08-03 17:25:31.654   267   347 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
08-03 17:25:31.654   306   306 E SMD     : DCD ON
08-03 17:25:31.654  1426  1426 V ActivityThread: updateVisibility : ActivityRecord{37ffbdf9 token=android.os.BinderProxy@65d51d6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-03 17:25:31.654  1929  1972 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
08-03 17:25:31.654  1426  1426 D Launcher: onTrimMemory. Level: 20
08-03 17:25:31.704  7740  7740 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-03 17:25:31.704  7740  7740 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,08-03 17:25:31.724  7740  7740 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6227-6229)
,08-03 17:25:31.724  7740  7740 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-03 17:25:31.734  7740  7740 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cd310be}
,08-03 17:25:31.744  7740  7740 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-03 17:25:31.744  7740  7740 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-03 17:25:31.764  7740  7740 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-03 17:25:31.764  7740  7740 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-03 17:25:31.774  7740  7740 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-03 17:25:31.784  7740  7740 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-03 17:25:31.784  7740  7740 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,08-03 17:25:31.784  7740  7740 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,08-03 17:25:31.794  7740  7740 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
08-03 17:25:31.794  7740  7740 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
08-03 17:25:31.794  7740  7740 I Adreno-EGL: Build Date: 11/19/14 Wed
08-03 17:25:31.794  7740  7740 I Adreno-EGL: Local Branch: mybranch5813579
08-03 17:25:31.794  7740  7740 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
08-03 17:25:31.794  7740  7740 I Adreno-EGL: Local Patches: NONE
08-03 17:25:31.794  7740  7740 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,08-03 17:25:31.884  7740  7772 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-03 17:25:31.914  7740  7740 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-03 17:25:31.924  7740  7740 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-03 17:25:31.934  7740  7740 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-03 17:25:31.944  7740  7740 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-03 17:25:31.944  7740  7740 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-03 17:25:31.984  7740  7740 D Activity: performCreate Call secproduct feature valuefalse
08-03 17:25:31.984  7740  7740 D Activity: performCreate Call debug elastic valuetrue
,08-03 17:25:31.994  7740  7785 D OpenGLRenderer: Render dirty regions requested: true
,08-03 17:25:31.994   772  1220 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-03 17:25:31.994   772  1220 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-03 17:25:31.994   772  1220 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-03 17:25:31.994   772   772 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-03 17:25:31.994   772   772 D PersonaManagerService: getPersonasForUser(): returning null!
,08-03 17:25:32.014   267   267 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,08-03 17:25:32.014   772  1056 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-03 17:25:32.014   772  1056 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-03 17:25:32.024   772  1058 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-03 17:25:32.024   772  1058 D PointerIcon: setMouseCustomIcon IconType is same.101
08-03 17:25:32.024   772  1058 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-03 17:25:32.024   772  1058 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-03 17:25:32.024  7740  7785 I OpenGLRenderer: Initialized EGL, version 1.4
,08-03 17:25:32.034  7740  7785 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3cc5060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,08-03 17:25:32.034  7740  7785 D OpenGLRenderer: Enabling debug mode 0
,08-03 17:25:32.044  7740  7740 V ActivityThread: updateVisibility : ActivityRecord{2eaee688 token=android.os.BinderProxy@c002a7a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-03 17:25:32.074   772   797 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-03 17:25:32.074   772  7790 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-03 17:25:32.084  7740  7740 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-03 17:25:32.094  1739  1739 I SamsungIME: getCurrentCandidateView
,08-03 17:25:32.094   772  1058 W ActivityManager: mDVFSHelper.release()
08-03 17:25:32.094   772  1058 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f4ce8f9 u0 com.test.thalitest/.MainActivity t99} time:166601
,08-03 17:25:32.094  7740  7740 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@c002a7a time:166603
,08-03 17:25:32.124  7740  7740 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7740
,08-03 17:25:32.154  1739  1739 D SamsungIME: Dismiss ExpandCandiate
,08-03 17:25:32.204  7740  7740 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-03 17:25:32.234  1739  1739 I SamsungIME: getDebugLevel  : 0x4f4c
,08-03 17:25:32.264  1739  1739 I SamsungIME: getDebugLevel  : 0x4f4c
,08-03 17:25:32.274  1739  1739 I SamsungIME: KeybaordView init() : load resources
,08-03 17:25:32.294  7740  7792 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1359649152
,08-03 17:25:32.294  1739  1739 I SamsungIME: getCurrentKeyboard
08-03 17:25:32.294  1739  1739 I SamsungIME: getTextKeyboard
,08-03 17:25:32.304  7740  7792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-03 17:25:32.304  7740  7792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-03 17:25:32.304  7740  7792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-03 17:25:32.304  7740  7792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-03 17:25:32.304  7740  7792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-03 17:25:32.304  7740  7792 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e2d01b8 added. We now have 1 listener(s)
,08-03 17:25:32.314  7740  7792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:1F:C9:5E
,08-03 17:25:32.314  7740  7792 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-03 17:25:32.314  7740  7792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 17:25:32.314  7740  7792 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 17:25:32.314  1739  1739 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-03 17:25:32.314  7740  7792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-03 17:25:32.314  7740  7792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-03 17:25:32.314  7740  7792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-03 17:25:32.314  7740  7792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:1F:C9:5E
08-03 17:25:32.314  7740  7792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-03 17:25:32.314  7740  7792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-03 17:25:32.314  7740  7792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-03 17:25:32.314  7740  7792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-03 17:25:32.314  7740  7792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-03 17:25:32.314  7740  7792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-03 17:25:32.314  7740  7792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-03 17:25:32.314  7740  7792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-03 17:25:32.314  7740  7792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-03 17:25:32.314  7740  7792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-03 17:25:32.314  7740  7792 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f17ef7 added. We now have 1 listener(s)
08-03 17:25:32.314  7740  7792 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 17:25:32.324  7740  7792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 17:25:32.324  7740  7792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-03 17:25:32.324  7740  7792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-03 17:25:32.324  7740  7792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-03 17:25:32.324  7740  7792 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-03 17:25:32.334  7740  7792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 17:25:32.334  7740  7792 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:1F:C9:5E
,08-03 17:25:32.334   772  1475 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 17:25:32.334  7740  7792 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-03 17:25:32.334  7740  7792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 17:25:32.334  7740  7792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 17:25:32.334  7740  7792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 17:25:32.334  7740  7792 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 17:25:32.334  7740  7792 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 17:25:32.334  7740  7792 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 17:25:32.334  7740  7792 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 17:25:32.334  7740  7792 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 17:25:32.334  7740  7792 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-03 17:25:32.334  7740  7792 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 17:25:32.334   772  1692 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 17:25:32.334  7740  7792 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-03 17:25:32.334  7740  7740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 17:25:32.344   772  1568 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 17:25:32.344  7740  7740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 17:25:32.364  7740  7740 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-03 17:25:32.654  1739  7796 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-03 17:25:33.244  7740  7800 W jxcore-log: Initializing JXcore engine
,08-03 17:25:33.244  7740  7800 W jxcore-log: JXcore engine is ready
,08-03 17:25:33.294  1772  1772 E auditd  : In denial and Property audit_ondenial is set to 1 
,08-03 17:25:33.294  1772  1772 E audit   : type=1400 msg=audit(1470237933.294:203): avc:  denied  { ioctl } for  pid=7800 comm="Thread-1263" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-03 17:25:33.294  1772  1772 E audit   :  SEPF_SM-N9005_5.0-1_0032
08-03 17:25:33.294  1772  1772 E audit   : 
08-03 17:25:33.294   772  1054 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
08-03 17:25:33.294  1772  1772 E audit   : type=1300 msg=audit(1470237933.294:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=990a08d8 items=0 ppid=355 ppcomm=main pid=7800 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1263" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-03 17:25:33.294  1772  1772 E audit   : type=1320 msg=audit(1470237933.294:203): 
,08-03 17:25:33.294   772  1054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
08-03 17:25:33.294   772  1024 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-03 17:25:33.294   772  1054 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,08-03 17:25:33.294   772  1024 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:33.294   772  1024 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:33.294   772  1024 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:33.294   772  1024 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-03 17:25:33.314  7740  7800 W jxcore-log: Starting JXcore engine
,08-03 17:25:33.334   772  1024 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7804 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-03 17:25:33.334  7804  7804 E Zygote  : MountEmulatedStorage()
,08-03 17:25:33.344  7804  7804 E Zygote  : v2
,08-03 17:25:33.344  7804  7804 I libpersona: KNOX_SDCARD checking this for 1000
08-03 17:25:33.344  7804  7804 I libpersona: KNOX_SDCARD not a persona
,08-03 17:25:33.374  7804  7804 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-03 17:25:33.374  7804  7804 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-03 17:25:33.374  7804  7804 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-03 17:25:33.424  7804  7804 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-03 17:25:33.434  7804  7804 D ActivityThread: Added TimaKeyStore provider
,08-03 17:25:33.444  7740  7800 W jxcore-log: Platform android
08-03 17:25:33.444  7740  7800 W jxcore-log: 
,08-03 17:25:33.444  7740  7800 W jxcore-log: Process ARCH arm
08-03 17:25:33.444  7740  7800 W jxcore-log: 
,08-03 17:25:33.454  7804  7804 D ResourcesManager: creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,08-03 17:25:33.464  7804  7804 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
08-03 17:25:33.464  7804  7804 D SecurityLogAgent:  SeDenialReceiver : File path = null
08-03 17:25:33.464   772  1311 I ActivityManager: Killing 5701:com.android.calendar/u0a172 (adj 15): emptyCount ##41
,08-03 17:25:33.714  7740  7800 I jxcore-log: JXcore Cordova bridge is ready!
08-03 17:25:33.714  7740  7800 I jxcore-log: 
08-03 17:25:33.714  7740  7800 W jxcore-log: JXcore engine is started
,08-03 17:25:33.724  7740  7792 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-03 17:25:33.724  7740  7740 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-03 17:25:33.744  7740  7800 E jxcore  : Error!: syntax error
08-03 17:25:33.744  7740  7800 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-03 17:25:33.754  7740  7740 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "syntax error\nSyntaxError: syntax error\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (57)
,08-03 17:25:33.754  7740  7740 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-03 17:25:33.764   772  1568 I ActivityManager: Killing 6872:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 15): emptyCount ##41
08-03 17:25:33.764   772  3303 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 17:25:33.764  7740  7740 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-03 17:25:33.764  7740  7740 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,08-03 17:25:33.774  7740  7740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 17:25:33.774  7740  7740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 17:25:33.774   772  3303 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 17:25:33.774  7740  7740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 17:25:33.774  7740  7740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 17:25:33.774  7740  7740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e2d01b8 removed from the list
08-03 17:25:33.774  7740  7740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 17:25:33.774  7740  7740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f17ef7 removed from the list
08-03 17:25:33.774  7740  7740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 17:25:33.774  7740  7740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-03 17:25:33.784  7740  7740 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-03 17:25:33.784   267  1367 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
,08-03 17:25:33.794   267   361 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,08-03 17:25:33.794   772  1058 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-03 17:25:33.794   772  1058 D PointerIcon: setMouseCustomIcon IconType is same.101
08-03 17:25:33.794   772  1058 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-03 17:25:33.794   772  1058 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-03 17:25:33.814  7740  7740 E ViewRootImpl: sendUserActionEvent() mView == null
,08-03 17:25:33.994  7826  7826 D AndroidRuntime: 
08-03 17:25:33.994  7826  7826 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-03 17:25:34.004  7826  7826 D AndroidRuntime: CheckJNI is OFF
,08-03 17:25:34.004  7826  7826 D AndroidRuntime: readGMSProperty: start
08-03 17:25:34.004  7826  7826 D AndroidRuntime: readGMSProperty: already setted!!
,08-03 17:25:34.004  7826  7826 D AndroidRuntime: readGMSProperty: end
08-03 17:25:34.004  7826  7826 D AndroidRuntime: addProductProperty: start
,08-03 17:25:34.164  7826  7826 E AffinityControl: AffinityControl: registerfunction enter
,08-03 17:25:34.184  7826  7826 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-03 17:25:34.184   772  1626 D PackageManager: START PACKAGE DELETE: observer{1020497322}
08-03 17:25:34.184   772  1626 D PackageManager: pkg{<packageName>}
08-03 17:25:34.184   772  1626 D PackageManager: user{0}
08-03 17:25:34.184   772  1626 D PackageManager: caller{2000}
08-03 17:25:34.184   772  1626 D PackageManager: flags{2}
,08-03 17:25:34.184   772  1626 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-03 17:25:34.184   772  1626 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,08-03 17:25:34.194   772  1626 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-03 17:25:34.194   772  1626 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-03 17:25:34.194   772  1626 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-03 17:25:34.194   772  1064 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-03 17:25:34.194   772  1064 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-03 17:25:34.194   772  1064 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-03 17:25:34.194   772  1064 D ApplicationPolicy: getApplicationUninstallationEnabled
08-03 17:25:34.194   772  1064 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-03 17:25:34.194   772  1064 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
,08-03 17:25:34.194   772  1024 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
08-03 17:25:34.194   772  1024 I ActivityManager: Killing 7740:com.test.thalitest/u0a79 (adj 9): stop com.test.thalitest cause uninstall pkg
,08-03 17:25:34.194   772  1024 D FocusedStackFrame: Set to : 0
,08-03 17:25:34.284   772  1064 W PackageSettings: Skipping PackageSetting{77ace86 com.example.hello/10078} due to missing metadata
,08-03 17:25:34.304   772  1064 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
,08-03 17:25:34.344  1503  1503 I art     : Explicit concurrent mark sweep GC freed 51837(3MB) AllocSpace objects, 2(646KB) LOS objects, 40% free, 20MB/33MB, paused 553us total 34.931ms
,08-03 17:25:34.344  6627  6627 I art     : Explicit concurrent mark sweep GC freed 647(36KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 302us total 37.637ms
,08-03 17:25:34.364  2537  2537 I art     : Explicit concurrent mark sweep GC freed 5043(299KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 24MB/32MB, paused 681us total 46.189ms
,08-03 17:25:34.384  7421  7421 I art     : Explicit concurrent mark sweep GC freed 9683(552KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 317us total 29.303ms
,08-03 17:25:34.394   772  1058 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,08-03 17:25:34.394   772  1121 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-03 17:25:34.404  1739  1739 E SamsungIME: mOCRHelper is null
,08-03 17:25:34.404  1852  2306 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-03 17:25:34.424  3841  3841 I art     : Explicit concurrent mark sweep GC freed 5624(340KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 15MB/26MB, paused 352us total 40.624ms
,08-03 17:25:34.424  2572  2572 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-03 17:25:34.424  2572  2572 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1470237934436
,08-03 17:25:34.424  2572  2572 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
,08-03 17:25:34.424   772  3113 E libprocessgroup: failed to kill 1 processes for processgroup 7740
08-03 17:25:34.424   772  1346 E Watchdog: !@Sync 5
,08-03 17:25:34.424  2572  2572 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,08-03 17:25:34.434  1411  1411 D RegisteredServicesCache: empty dynamic service
,08-03 17:25:34.444   772  1021 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,08-03 17:25:34.474   772  1021 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,08-03 17:25:34.474   772  1145 V NetworkStats: removeUidsLocked() for UIDs [10079]
08-03 17:25:34.474   772  1145 D NtpTrustedTime: currentTimeMillis() cache hit
08-03 17:25:34.474   772  1145 V NetworkStats: performPollLocked(flags=0x3)
,08-03 17:25:34.484   772  1145 D NetworkStatsFactory: UpdateStatsForKnox
,08-03 17:25:34.484   772  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 17:25:34.494   772  1145 V NetworkStats: performPollLocked() took 22ms
08-03 17:25:34.494   772  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,08-03 17:25:34.514   772  1555 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-03 17:25:34.514   772  1555 D SecContentProvider2: mCursor = null
,08-03 17:25:34.524   772   772 I art     : Explicit concurrent mark sweep GC freed 39911(2MB) AllocSpace objects, 23(368KB) LOS objects, 29% free, 37MB/53MB, paused 2.468ms total 137.488ms
,08-03 17:25:34.524   772  1064 I art     : WaitForGcToComplete blocked for 50.661ms for cause Explicit
,08-03 17:25:34.524   772   772 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,08-03 17:25:34.534   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,08-03 17:25:34.534   772  1021 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,08-03 17:25:34.534   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,08-03 17:25:34.534   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,08-03 17:25:34.534   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,08-03 17:25:34.544   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,08-03 17:25:34.544  2572  2572 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
,08-03 17:25:34.544   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,08-03 17:25:34.544   772  1021 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
,08-03 17:25:34.544   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,08-03 17:25:34.554  2572  2572 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-03 17:25:34.554   772  1555 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-03 17:25:34.554   772  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:34.554   772  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:34.554   772  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:34.554   772  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-03 17:25:34.564   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,08-03 17:25:34.574   772  1021 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-03 17:25:34.574   772  1021 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-03 17:25:34.574   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,08-03 17:25:34.574   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,08-03 17:25:34.574   772  1146 D NtpTrustedTime: currentTimeMillis() cache hit
08-03 17:25:34.574   772  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-03 17:25:34.584   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,08-03 17:25:34.584   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,08-03 17:25:34.594   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
08-03 17:25:34.594   772  1555 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7863 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,08-03 17:25:34.594   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
08-03 17:25:34.594  7863  7863 I libpersona: KNOX_SDCARD checking this for 10116
08-03 17:25:34.594  7863  7863 E Zygote  : MountEmulatedStorage()
08-03 17:25:34.594  7863  7863 I libpersona: KNOX_SDCARD not a persona
08-03 17:25:34.594  7863  7863 E Zygote  : v2
08-03 17:25:34.594   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,08-03 17:25:34.594   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,08-03 17:25:34.604   772  1021 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,08-03 17:25:34.604   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,08-03 17:25:34.604   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,08-03 17:25:34.614   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-03 17:25:34.614   772  1021 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,08-03 17:25:34.614   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,08-03 17:25:34.614   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,08-03 17:25:34.614   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-03 17:25:34.614   772  1021 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
08-03 17:25:34.614   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
08-03 17:25:34.624  7863  7863 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-03 17:25:34.624  7863  7863 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-03 17:25:34.624  7863  7863 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-03 17:25:34.624   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,08-03 17:25:34.624   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,08-03 17:25:34.634   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,08-03 17:25:34.644   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,08-03 17:25:34.644   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-03 17:25:34.644   772  1021 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,08-03 17:25:34.644  7863  7863 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-03 17:25:34.644  7863  7863 D ActivityThread: Added TimaKeyStore provider
,08-03 17:25:34.654   306   306 E SMD     : DCD ON
,08-03 17:25:34.654   772   772 D RCPManagerService: PackageReceiver onReceive()
,08-03 17:25:34.654   772   772 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-03 17:25:34.664   772   772 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-03 17:25:34.664   772   772 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-03 17:25:34.664   772   772 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-03 17:25:34.664   772   772 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-03 17:25:34.664   772   772 V EnterpriseBillingPolicy: uID is 10079
08-03 17:25:34.664   772   772 V EnterpriseBillingPolicy: Removed Packageuid is0
08-03 17:25:34.664   772   772 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-03 17:25:34.664   772   772 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
08-03 17:25:34.664   772   772 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-03 17:25:34.664   772   772 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,08-03 17:25:34.664   772   772 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-03 17:25:34.664   772   772 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-03 17:25:34.664   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-03 17:25:34.664   772  1021 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
08-03 17:25:34.664   772  1177 D TaskPersister: removeObsoleteFile: deleting file=99_task.xml
,08-03 17:25:34.664   772   772 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
,08-03 17:25:34.674  1426  1426 D SurfaceWidgetView: destroyHardwareResources():421828631
08-03 17:25:34.674   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-03 17:25:34.674   772   797 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-03 17:25:34.674   772   797 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-03 17:25:34.674   772   797 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-03 17:25:34.674   772   797 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-03 17:25:34.674   772   797 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-03 17:25:34.674  7863  7863 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
08-03 17:25:34.674   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-03 17:25:34.674   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-03 17:25:34.684  1426  1426 D Launcher: onRestart, Launcher: 626034229
08-03 17:25:34.684  1426  1426 D Launcher: onStart, Launcher: 626034229
08-03 17:25:34.684  1426  1426 D Launcher.HomeView: onStart
08-03 17:25:34.684   772  1021 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
08-03 17:25:34.684  1929  1967 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
08-03 17:25:34.684  1426  1426 V ActivityThread: updateVisibility : ActivityRecord{37ffbdf9 token=android.os.BinderProxy@65d51d6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-03 17:25:34.684  1929  2122 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
08-03 17:25:34.684  1929  2122 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
08-03 17:25:34.684   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-03 17:25:34.684   772  1021 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
08-03 17:25:34.694   267   267 I SurfaceFlinger: id=13 createSurf (1080x1920),1 flag=4, Mauncher
08-03 17:25:34.694  7863  7863 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
08-03 17:25:34.694   772  1056 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-03 17:25:34.694   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-03 17:25:34.704   772  1056 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-03 17:25:34.704   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-03 17:25:34.704   772  1021 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
08-03 17:25:34.704   772  1058 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-03 17:25:34.704   772  1058 D PointerIcon: setMouseCustomIcon IconType is same.101
08-03 17:25:34.704   772  1058 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-03 17:25:34.704   772  1058 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-03 17:25:34.704   772  1021 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-03 17:25:34.704   772  1021 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 17:25:34.704   772  1021 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-03 17:25:34.714   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-03 17:25:34.714  7863  7863 D elm:14491: ELMEngine.ELMEngine( context ).
,08-03 17:25:34.714  7863  7863 D elm:14491: MDMBridge.setEnterpriseBridge()
,08-03 17:25:34.714   772  1220 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-03 17:25:34.714   772  1220 D ActivityManager: caller:android.app.ApplicationThreadProxy@15eb8a6e, r.packageName :com.sec.esdk.elm
,08-03 17:25:34.714   772  1555 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-03 17:25:34.714   772  1555 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 7740 uid 10079
08-03 17:25:34.714  7863  7863 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
08-03 17:25:34.714   772  7881 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-03 17:25:34.724   772  1021 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,08-03 17:25:34.724  3865  3865 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-03 17:25:34.724  3865  3865 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-03 17:25:34.724  3865  3865 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
08-03 17:25:34.724  3865  3865 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-03 17:25:34.724  3865  3865 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
08-03 17:25:34.724  3865  3865 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
,08-03 17:25:34.724  3865  3865 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-03 17:25:34.724  3865  3865 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 17:25:34.724  3865  3865 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-03 17:25:34.724  3865  3865 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
,08-03 17:25:34.724  3865  3865 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 17:25:34.724  3865  3865 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 17:25:34.724  3865  3865 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-03 17:25:34.724  7863  7863 D elm:14491: ElmAgentService : onCreate()
08-03 17:25:34.724  3865  3865 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,08-03 17:25:34.734  6178  6178 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
,08-03 17:25:34.734   772  1021 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
08-03 17:25:34.734  6178  6178 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
08-03 17:25:34.734  6178  6178 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
,08-03 17:25:34.734  7863  7883 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-03 17:25:34.734  7863  7883 D elm:14491: MainReceiver.listeningToPackageRemoved()
08-03 17:25:34.734  7863  7883 D elm:14491: MDMBridge.getInstance()
08-03 17:25:34.744  7863  7883 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,08-03 17:25:34.744   772  3303 I SQLiteConnectionPool: exportDB...
,08-03 17:25:34.744  7863  7883 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,08-03 17:25:34.764  7150  7150 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-03 17:25:34.764  7150  7150 I PCWCLIENTTRACE_PushUtil: sales region : global
08-03 17:25:34.764  7150  7150 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-03 17:25:34.764  7150  7150 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-03 17:25:34.774   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-03 17:25:34.774   772  1021 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
08-03 17:25:34.774  7863  7863 D elm:14491: ElmAgentService : onDestroy().
,08-03 17:25:34.774   772  1375 D ActivityManager: startService callerProcessName:com.sec.android.app.shealth, calleePkgName: com.sec.android.app.shealth
,08-03 17:25:34.784   772  1375 D ActivityManager: caller:android.app.ApplicationThreadProxy@18d54e5d, r.packageName :com.sec.android.app.shealth
,08-03 17:25:34.784   772  1058 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{19d23186 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t97} time:169297
,08-03 17:25:34.794   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-03 17:25:34.794   772  1021 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,08-03 17:25:34.794   772  1064 I art     : Explicit concurrent mark sweep GC freed 21247(1830KB) AllocSpace objects, 5(80KB) LOS objects, 29% free, 37MB/53MB, paused 7.784ms total 273.383ms
,08-03 17:25:34.804   772  3303 I SQLiteConnectionPool: ...exportDB
,08-03 17:25:34.804   772  3303 D SSRM:aY : MSG_TYPE_APP_REMOVED::
,08-03 17:25:34.814   772  1452 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-03 17:25:34.814   772  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:34.814   772  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:34.814   772  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:34.814   772  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-03 17:25:34.824   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-03 17:25:34.824   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-03 17:25:34.824   772  1021 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,08-03 17:25:34.834   772  1064 D PackageManager: delete codoeFile: 
,08-03 17:25:34.844   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-03 17:25:34.844   772  1021 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
08-03 17:25:34.844   772  1064 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
08-03 17:25:34.844   772  1064 I AASA_removePackage: UID=10079 Target=com.test.thalitest
08-03 17:25:34.844   772  1064 D PackageManager: result of delete: 1{1020497322}
08-03 17:25:34.844   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-03 17:25:34.844   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-03 17:25:34.844   772  1021 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
08-03 17:25:34.844  7826  7826 D AndroidRuntime: Shutting down VM
08-03 17:25:34.844   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-03 17:25:34.844   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-03 17:25:34.844   772  1021 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,08-03 17:25:34.854   772  1021 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-03 17:25:34.854  7886  7886 E Zygote  : MountEmulatedStorage()
08-03 17:25:34.854  7886  7886 E Zygote  : v2
08-03 17:25:34.854  7886  7886 I libpersona: KNOX_SDCARD checking this for 10043
08-03 17:25:34.854  7886  7886 I libpersona: KNOX_SDCARD not a persona
08-03 17:25:34.864   772  1452 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7886 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-03 17:25:34.864   772  1021 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-03 17:25:34.864   772  1021 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-03 17:25:34.864  7886  7886 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-03 17:25:34.864  7886  7886 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-03 17:25:34.864  7886  7886 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-03 17:25:34.884  7886  7886 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-03 17:25:34.884  7886  7886 D ActivityThread: Added TimaKeyStore provider
,08-03 17:25:34.904  7886  7886 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,08-03 17:25:34.934  7886  7886 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-03 17:25:34.934  7886  7886 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-03 17:25:34.934  7886  7886 D SPPClientService: PushLog.txt file is not deleted.
,08-03 17:25:34.934  7886  7886 D SPPClientService: PushLog.txt file is not deleted.
08-03 17:25:34.934  7886  7886 D SPPClientService: ============PushLog. stop!
,08-03 17:25:34.944   772  1457 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,08-03 17:25:34.944   772  1457 D ActivityManager: caller:android.app.ApplicationThreadProxy@2db93491, r.packageName :com.samsung.android.app.galaxyfinder
,08-03 17:25:34.964  7216  7216 I SA      : [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,08-03 17:25:34.964  7216  7216 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10079 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,08-03 17:25:34.964   772  1475 I ActivityManager: Killing 6892:com.google.android.gms:car/u0a15 (adj 15): emptyCount ##41
,08-03 17:25:34.964   772  1220 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
08-03 17:25:34.964   772  1220 D ActivityManager: caller:android.app.ApplicationThreadProxy@1f05bff6, r.packageName :com.android.providers.contacts
,08-03 17:25:35.034  7237  7237 D Mms/FreeMessageReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,08-03 17:25:35.034   772  1680 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
,08-03 17:25:35.034   772  1680 D ActivityManager: caller:android.app.ApplicationThreadProxy@285dce64, r.packageName :com.android.mms
,08-03 17:25:35.034   772  1423 I TactileAssist: enable value -1
,08-03 17:25:35.034   772  1423 I TactileAssist: internal enable value -1
08-03 17:25:35.034   772  1423 I TactileAssist: intensity value -1
08-03 17:25:35.034   772  1423 I TactileAssist: saveAppList value true
,08-03 17:25:35.034  7237  7904 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,08-03 17:25:35.044  7237  7904 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
08-03 17:25:35.044   772  1423 I TactileAssist: List of disabled apps :
,08-03 17:25:35.044   772  1220 D SettingsProvider: name = reading_mode_app_list
,08-03 17:25:35.054  7277  7277 D Compatibility: onReceive() it will make start service
08-03 17:25:35.054   772   799 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-03 17:25:35.054   772   799 D ActivityManager: caller:android.app.ApplicationThreadProxy@33c5e582, r.packageName :com.sec.android.app.soundalive
08-03 17:25:35.054   772   797 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-03 17:25:35.054   772   797 D ActivityManager: caller:android.app.ApplicationThreadProxy@1c5b6cd0, r.packageName :com.google.android.googlequicksearchbox
,08-03 17:25:35.064  7277  7905 D Compatibility: onHandleIntent()
,08-03 17:25:35.064  7277  7905 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10079, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-03 17:25:35.064  1503  7906 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-03 17:25:35.064  7277  7905 D Compatibility: found: 2
08-03 17:25:35.064  7277  7905 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-03 17:25:35.064  7277  7905 D Compatibility: skipping ResolveInfo{22bc406c com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
,08-03 17:25:35.064  7277  7905 D Compatibility: considering ResolveInfo{25508635 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-03 17:25:35.064  7277  7905 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-03 17:25:35.064  7277  7905 D Compatibility: enabling receiver ResolveInfo{2e2b7aca com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-03 17:25:35.074  7277  7905 D Compatibility: enabling receiver ResolveInfo{2a29043b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-03 17:25:35.074  7277  7905 D Compatibility: enabling receiver ResolveInfo{3362f758 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-03 17:25:35.084   772  1064 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-03 17:25:35.084   772  1064 D PackageManager: userId{-1}
08-03 17:25:35.084   772  1064 D PackageManager: andCode{true}
,08-03 17:25:35.084   772  1064 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
08-03 17:25:35.084  6627  6627 I art     : Explicit concurrent mark sweep GC freed 122(6KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 298us total 12.236ms
08-03 17:25:35.084  7277  7905 D Compatibility: enabling receiver ResolveInfo{2e9050b1 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-03 17:25:35.084  7277  7905 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-03 17:25:35.114  7297  7297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2989 
08-03 17:25:35.114   772  1692 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,08-03 17:25:35.114   772  1692 D ActivityManager: caller:android.app.ApplicationThreadProxy@3920d6ef, r.packageName :com.samsung.android.app.assistantmenu
,08-03 17:25:35.114  7545  7545 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-03 17:25:35.124   772  1423 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-03 17:25:35.124   772  1423 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-03 17:25:35.124  6627  7908 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-03 17:25:35.144  1426  1426 D Launcher.Model: reloadBadges entered.
,08-03 17:25:35.144  7262  7271 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-03 17:25:35.144  7262  7271 D BadgeProvider: sendNotify, [notify] : null
,08-03 17:25:35.144  7262  7271 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-03 17:25:35.144  7262  7271 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-03 17:25:35.144  7262  7271 D BadgeProvider: update, [UpdateCount] : 1
,08-03 17:25:35.154   772  1375 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-03 17:25:35.154   772  1375 D ActivityManager: caller:android.app.ApplicationThreadProxy@384005e8, r.packageName :com.google.android.gms
,08-03 17:25:35.164  7370  7370 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2989 
,08-03 17:25:35.164   772  1311 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-03 17:25:35.164   772  1311 D ActivityManager: caller:android.app.ApplicationThreadProxy@367c12a6, r.packageName :com.google.android.gms
,08-03 17:25:35.174   772  1692 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
,08-03 17:25:35.174   772  1692 D ActivityManager: caller:android.app.ApplicationThreadProxy@29039894, r.packageName :com.samsung.android.app.filterinstaller
,08-03 17:25:35.184   772  1568 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.provider.filterprovider
,08-03 17:25:35.184   772  1568 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:35.184   772  1568 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:35.184   772  1568 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:35.184   772  1568 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-03 17:25:35.224  7914  7914 E Zygote  : MountEmulatedStorage()
,08-03 17:25:35.224  7914  7914 E Zygote  : v2
08-03 17:25:35.224  7914  7914 I libpersona: KNOX_SDCARD checking this for 10121
08-03 17:25:35.224  7914  7914 I libpersona: KNOX_SDCARD not a persona
,08-03 17:25:35.224   772  1568 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=7914 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,08-03 17:25:35.234  7914  7914 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-03 17:25:35.234  7914  7914 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-03 17:25:35.234  7914  7914 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-03 17:25:35.234   772  1121 I EventHub: Removing device '/dev/input/event6' due to inotify event
,08-03 17:25:35.234   772  1423 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-03 17:25:35.234   772  1423 D ActivityManager: caller:android.app.ApplicationThreadProxy@5c6b332, r.packageName :com.google.android.gms
,08-03 17:25:35.254  1503  7906 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-03 17:25:35.254  1503  7906 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-03 17:25:35.254  1503  7906 E chromium: ### WebView Version 43.0.2357.121 (code 2357121)
,08-03 17:25:35.254  1503  7906 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xa027b0ee in tid 7906 (IntentService[U)
,08-03 17:25:35.254   772  1626 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-03 17:25:35.254   772  1626 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:35.254   772  1626 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:35.254   772  1626 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-03 17:25:35.254   772  1626 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-03 17:25:35.274  7914  7914 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-03 17:25:35.274  7914  7914 D ActivityThread: Added TimaKeyStore provider
,08-03 17:25:35.294   772  1121 I EventHub: Removing device '/dev/input/event7' due to inotify event
,08-03 17:25:35.304   302   302 I DEBUG   : failed to change ownership of /data/tombstones: Read-only file system
08-03 17:25:35.304   302   302 E         : ro.product_ship = true
08-03 17:25:35.304   302   302 E         : ro.debug_level = 0x4f4c
,08-03 17:25:35.304  7930  7930 E Zygote  : MountEmulatedStorage()
08-03 17:25:35.304  7930  7930 E Zygote  : v2
08-03 17:25:35.304  7930  7930 I libpersona: KNOX_SDCARD checking this for 1000
08-03 17:25:35.304  7930  7930 I libpersona: KNOX_SDCARD not a persona
,08-03 17:25:35.314  1772  1772 E audit_log: File locking failed. error= Bad file number
,08-03 17:25:35.314   772  1626 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7930 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-03 17:25:35.344   772  1121 I EventHub: Removing device '/dev/input/event8' due to inotify event
,08-03 17:25:35.364  7930  7930 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-03 17:25:35.364  7930  7930 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-03 17:25:35.364  7930  7930 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-03 17:25:35.374  2537  7913 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-03 17:25:35.374  2537  7913 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-03 17:25:35.384   772  1692 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-03 17:25:35.384   772  1692 D ActivityManager: caller:android.app.ApplicationThreadProxy@28db59df, r.packageName :com.google.android.gms
,08-03 17:25:35.404   772  1626 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-03 17:25:35.404   772  1626 D ActivityManager: caller:android.app.ApplicationThreadProxy@3574b918, r.packageName :com.google.android.gms
,08-03 17:25:35.404  7930  7930 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-03 17:25:35.404  7930  7930 D ActivityThread: Added TimaKeyStore provider
,08-03 17:25:35.414   772  1121 I EventHub: Removing device '/dev/input/event9' due to inotify event
,08-03 17:25:35.424  7914  7914 D ResourcesManager: creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,08-03 17:25:35.424  7914  7914 W ContextImpl: Unable to create files subdir /data/user/0/com.samsung.android.provider.filterprovider/cache
08-03 17:25:35.424  7914  7914 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,08-03 17:25:35.434  7930  7930 D ResourcesManager: creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,08-03 17:25:35.444  7930  7930 W ContextImpl: Unable to create files subdir /data/data/com.android.keychain/cache
08-03 17:25:35.444  7930  7930 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,08-03 17:25:35.444  7914  7914 D AndroidRuntime: Shutting down VM
,08-03 17:25:35.444  2537  3063 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-03 17:25:35.444  2537  3063 E GAv4-SVC: Error creating clientId file: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/gaClientId: open failed: EROFS (Read-only file system)
,08-03 17:25:35.444  2537  3063 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml
,08-03 17:25:35.444  7914  7914 E AndroidRuntime: FATAL EXCEPTION: main
08-03 17:25:35.444  7914  7914 E AndroidRuntime: Process: com.samsung.android.provider.filterprovider, PID: 7914
08-03 17:25:35.444  7914  7914 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.filterprovider.FilterProvider: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.provider.filterprovider.FilterProvider" on path: DexPathList[[zip file "/system/app/FilterProvider/FilterProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5558)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5150)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5090)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: Caused by: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.provider.filterprovider.FilterProvider" on path: DexPathList[[zip file "/system/app/FilterProvider/FilterProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5543)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	... 11 more
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	Suppressed: java.io.IOException: Zip archive '/system/app/FilterProvider/FilterProvider.apk' doesn't contain classes.dex (error msg: Entry not found)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFileNative(Native Method)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:80)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:59)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at dalvik.system.PathC,lassLoader.openArtFile(PathClassLoader.java:76)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Native Method)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Method.java:372)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		... 9 more
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/app/FilterProvider/FilterProvider.apk'
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		... 27 more
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from /system/app/FilterProvider/arm/FilterProvider.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		... 27 more
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	Caused by: java.io.IOException: 
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		... 27 more
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	Suppressed: java.lang.ClassNotFoundException: com.samsung.android.provider.filterprovider.FilterProvider
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at java.lang.Class.classForName(Native Method)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 		... 13 more
08-03 17:25:35.444  7914  7914 E AndroidRuntime: 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
08-03 17:25:35.444  2537  5236 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml
08-03 17:25:35.454   772  1121 I EventHub: Removing device '/dev/input/event10' due to inotify event
08-03 17:25:35.454   772  1143 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.filterprovider
08-03 17:25:35.454  2537  3063 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-03 17:25:35.454  2537  3063 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-03 17:25:35.454   772  7945 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
08-03 17:25:35.454   772  7945 E AndroidRuntime: java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
08-03 17:25:35.454   772  7945 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:46)
08-03 17:25:35.454   772  7945 E AndroidRuntime: 	at android.os.StatFs.restat(StatFs.java:56)
08-03 17:25:35.454   772  7945 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
08-03 17:25:35.454   772  7945 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
08-03 17:25:35.454   772  7945 E AndroidRuntime: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-03 17:25:35.454   772  7945 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
08-03 17:25:35.454   772  7945 E AndroidRuntime: Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
08-03 17:25:35.454   772  7945 E AndroidRuntime: 	at libcore.io.Posix.statvfs(Native Method)
08-03 17:25:35.454   772  7945 E AndroidRuntime: 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
08-03 17:25:35.454   772  7945 E AndroidRuntime: 	at android.system.Os.statvfs(Os.java:473)
08-03 17:25:35.454   772  7945 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:44)
08-03 17:25:35.454   772  7945 E AndroidRuntime: 	... 5 more
08-03 17:25:35.464   772   799 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-03 17:25:35.464   772   799 D ActivityManager: caller:android.app.ApplicationThreadProxy@9447156, r.packageName :com.google.android.apps.plus
08-03 17:25:35.464  7930  7930 D AndroidRuntime: Shutting down VM
08-03 17:25:35.464  7930  7930 E AndroidRuntime: FATAL EXCEPTION: main
08-03 17:25:35.464  7930  7930 E AndroidRuntime: Process: com.android.keychain, PID: 7930
08-03 17:25:35.464  7930  7930 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate receiver com.android.keychain.KeyChainBroadcastReceiver: java.lang.ClassNotFoundException: Didn't find class "com.android.keychain.KeyChainBroadcastReceiver" on path: DexPathList[[zip file "/system/app/KeyChain/KeyChain.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2970)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: Caused by: java.lang.ClassNotFoundException: Didn't find class "com.android.keychain.KeyChainBroadcastReceiver" on path: DexPathList[[zip file "/system/app/KeyChain/KeyChain.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2965)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	... 9 more
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	Suppressed: java.io.IOException: Zip archive '/system/app/KeyChain/KeyChain.apk' doesn't contain classes.dex (error msg: Entry not found)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFileNative(Native Method)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:80)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:59)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Native Method)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Method.java:372)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		... 7 more
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/app/KeyChain/KeyChain.apk'
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		... 27 more
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from /system/app/KeyChain/arm/KeyChain.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		... 27 more
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	Caused by: java.io.IOException: 
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		... 27 more
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	Suppressed: java.lang.ClassNotFoundException: com.android.keychain.KeyChainBroadcastReceiver
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at java.lang.Class.classForName(Native Method)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 		... 11 more
08-03 17:25:35.464  7930  7930 E AndroidRuntime: 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
08-03 17:25:35.474  2537  3063 E GAv4-SVC: Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 17:25:35.474   772  7945 E android.os.Debug: ro.product_ship = true
08-03 17:25:35.474   772  7945 E android.os.Debug: ro.debug_level = 0x4f4c
08-03 17:25:35.474   772  1555 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.keychain
08-03 17:25:35.474  2537  5236 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml
08-03 17:25:35.474   772  7945 E AndroidRuntime: Error reporting crash
08-03 17:25:35.474   772  7945 E AndroidRuntime: java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
08-03 17:25:35.474   772  7945 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:46)
08-03 17:25:35.474   772  7945 E AndroidRuntime: 	at android.os.StatFs.restat(StatFs.java:56)
08-03 17:25:35.474   772  7945 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
08-03 17:25:35.474   772  7945 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
08-03 17:25:35.474   772  7945 E AndroidRuntime: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-03 17:25:35.474   772  7945 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
08-03 17:25:35.474   772  7945 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:15161)
08-03 17:25:35.474   772  7945 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14749)
08-03 17:25:35.474   772  7945 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14733)
08-03 17:25:35.474   772  7945 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
08-03 17:25:35.474   772  7945 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-03 17:25:35.474   772  7945 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-03 17:25:35.474   772  7945 E AndroidRuntime: Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
08-03 17:25:35.474   772  7945 E AndroidRuntime: 	at libcore.io.Posix.statvfs(Native Method)
08-03 17:25:35.474   772  7945 E AndroidRuntime: 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
08-03 17:25:35.474   772  7945 E AndroidRuntime: 	at android.system.Os.statvfs(Os.java:473)
08-03 17:25:35.474   772  7945 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:44)
08-03 17:25:35.474   772  7945 E AndroidRuntime: 	... 11 more
08-03 17:25:35.474   772  7945 I Process : Sending signal. PID: 772 SIG: 9
08-03 17:25:35.474  2537  3063 E GAv4-SVC: Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
08-03 17:25:35.474  7914  7914 I Process : Sending signal. PID: 7914 SIG: 9
08-03 17:25:35.474   355   355 I Zygote  : Process 1503 exited due to signal (7)
08-03 17:25:35.474  2537  5236 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml
,08-03 17:25:35.614  1417  1455 W Sensors : sensorservice died [0xaef7f1c0]
08-03 17:25:35.614  1192  1221 W Sensors : sensorservice died [0xafb0e280]
,08-03 17:25:35.614  1852  1901 W Sensors : sensorservice died [0xb3a523c0]
,08-03 17:25:35.614   267  1367 I SurfaceFlinger: restart the boot-animation @ binderDied
,08-03 17:25:35.614  1417  1766 E WifiManager: Channel connection lost
08-03 17:25:35.614  1192  1583 E WifiManager: Channel connection lost
,08-03 17:25:35.614  1852  2305 E WifiManager: Channel connection lost
,08-03 17:25:35.614   267   267 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6962000
08-03 17:25:35.614   267   267 D qdhwcomposer: hwc_blank: Unblanking display: 0
,08-03 17:25:35.614  2537  5181 E WifiManager: Channel connection lost
,08-03 17:25:35.624  1304  3043 E WifiManager: Channel connection lost
,08-03 17:25:35.624   311   311 W AudioFlinger: power manager service died !!!
08-03 17:25:35.624   311   311 W AudioCache: clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
,08-03 17:25:35.624   267  1747 I SurfaceFlinger: id=2 Removed GocusedStac (5/8)
,08-03 17:25:35.624   267  1747 I SurfaceFlinger: id=3 Removed EimLayer (0/7)
08-03 17:25:35.624   267  1747 I SurfaceFlinger: id=4 Removed EimLayer (0/6)
08-03 17:25:35.624   267  1747 I SurfaceFlinger: id=5 Removed EimLayer (0/5)
08-03 17:25:35.624   267  1747 I SurfaceFlinger: id=6 Removed EimLayer (0/4)
08-03 17:25:35.624   267  1747 I SurfaceFlinger: id=2 Removed GocusedStac (-2/4)
08-03 17:25:35.624   267  1747 I SurfaceFlinger: id=3 Removed EimLayer (-2/4)
08-03 17:25:35.624   267  1747 I SurfaceFlinger: id=4 Removed EimLayer (-2/4)
,08-03 17:25:35.624  1929  1967 W Sensors : sensorservice died [0xaef52340]
,08-03 17:25:35.624  1426  1461 W Sensors : sensorservice died [0xaef59280]
08-03 17:25:35.624  1867  1953 W Sensors : sensorservice died [0xaefb9a40]
,08-03 17:25:35.624  1393  1404 W Sensors : sensorservice died [0xaefbd940]
,08-03 17:25:35.624  5100  5184 E WifiManager: Channel connection lost
,08-03 17:25:35.634  7370  7912 E ActivityThread: Failed to find provider info for com.samsung.android.provider.filterprovider
,08-03 17:25:35.634   265   265 I ServiceManager: service 'location' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'country_detector' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'search' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'dropbox' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'wallpaper' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'audio' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'DockObserver' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'usb' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'serial' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'uimode' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'jobscheduler' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'imms' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'sec_analytics' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'device_policy' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'harmony_eas_service' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'sdp' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'log_manager_service' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'enterprise_policy' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'statusbar' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'clipboard' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'clipboardEx' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'network_management' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'ABTPersistenceService' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'textservices' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'network_score' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'netstats' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'motion_recognition' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'cover' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'mount' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'lock_settings' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'enterprise_license_policy' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'netpolicy' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'wifip2p' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'connectivity' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'sb_service' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'servicediscovery' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'updatelock' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'notification' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'devicestoragemonitor' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'wifi' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'msapwifi' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'wifiscanner' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'rttmanager' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'samsung.smartfaceservice' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'consumer_ir' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'alarm' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'application_policy' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'wifi_policy' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'phone_restriction_policy' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'remoteinjection' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'mum_container_policy' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'enterprise_billing_policy' died
08-03 17:25:35.634   265   265 I Serv,iceManager: service 'knox_timakeystore_policy' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'context_aware' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'scontext' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'barbeam' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'multiwindow_facade' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'window' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'input' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'backup' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'appwidget' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'voiceinteraction' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'SecExternalDisplayService' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'diskstats' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'mDNIe' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'spengestureservice' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'quickconnect' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'samplingprofiler' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'commontime_management' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'dreams' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'print' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'restrictions' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'media_session' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'media_router' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'trust' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'fingerprint' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'launcherapps' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'voip' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'media_projection' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'lpnet' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'bluetooth_manager' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'tactileassist' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'rcp' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'input_method' died
08-03 17:25:35.634  6627  6627 E ActivityThread: Failed to find provider info for com.sec.badge
08-03 17:25:35.634   265   265 I ServiceManager: service 'accessibility' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'hardware' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'persona_policy' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'batterystats' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'appops' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'power' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'display' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'scheduling_policy' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'telephony.registry' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'account' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'content' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'DirEncryptService' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'ReactiveService' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'sedenial' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'vibrator' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'tima' died
,08-03 17:25:35.634   265   265 I ServiceManager: service 'cepproxyks' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'CustomFrequencyManagerService' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'entropy' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'procstats' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'meminfo' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'dbinfo' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'user' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'gfxinfo' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'battery' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'cpuinfo' died
,08-03 17:25:35.634   265   265 I ServiceManager: service 'webviewupdate' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'activity' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'permission' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'usagestats' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'edmnativehelper' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'package' died
08-03 17:25:35.644  2537  3063 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
08-03 17:25:35.634   265   265 I ServiceManager: service 'mdm.remotedesktop' died
,08-03 17:25:35.644  2537  3063 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
08-03 17:25:35.634   265   265 I ServiceManager: service 'sensorservice' died
08-03 17:25:35.634   265   265 I ServiceManager: service 'SEAMService' died
08-03 17:25:35.644  7370  7912 E ActivityThread: Failed to find provider info for com.samsung.android.provider.filterprovider
08-03 17:25:35.634   265   265 I ServiceManager: service 'persona' died
08-03 17:25:35.634  6627  6627 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-03 17:25:35.644   267   347 I SurfaceFlinger: id=5 Removed EimLayer (-2/4)
08-03 17:25:35.644   267   347 I SurfaceFlinger: id=6 Removed EimLayer (-2/4)
08-03 17:25:35.644   267  1747 I SurfaceFlinger: id=13 Removed Mauncher (1/3)
08-03 17:25:35.644   267  1747 I SurfaceFlinger: id=9 Removed TtatusBar (1/2)
08-03 17:25:35.644   267  1747 I SurfaceFlinger: id=7 Removed JmageWallpa (0/1)
08-03 17:25:35.644   267  1747 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/1)
08-03 17:25:35.644   267  1747 I SurfaceFlinger: id=13 Removed Mauncher (-2/1)
08-03 17:25:35.644   267  1747 I SurfaceFlinger: id=9 Removed TtatusBar (-2/1)
08-03 17:25:35.644   267  1747 I SurfaceFlinger: id=11 Removed DolorFade (0/0)
08-03 17:25:35.644   267  1747 I SurfaceFlinger: id=11 Removed DolorFade (-2/0)
,08-03 17:25:35.644  7930  7930 E AndroidRuntime: Error reporting crash
08-03 17:25:35.644  7930  7930 E AndroidRuntime: android.os.DeadObjectException
08-03 17:25:35.644  7930  7930 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 17:25:35.644  7930  7930 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 17:25:35.644  7930  7930 E AndroidRuntime: 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4706)
08-03 17:25:35.644  7930  7930 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
08-03 17:25:35.644  7930  7930 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-03 17:25:35.644  7930  7930 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
,08-03 17:25:35.644  7930  7930 I Process : Sending signal. PID: 7930 SIG: 9
,08-03 17:25:35.644  2537  3063 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-03 17:25:35.644  2537  3063 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-03 17:25:35.644  2537  3063 E GAv4-SVC: Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
08-03 17:25:35.644  7370  7912 E AndroidRuntime: FATAL EXCEPTION: FilterPackageServiceHandler
08-03 17:25:35.644  7370  7912 E AndroidRuntime: Process: com.samsung.android.app.filterinstaller, PID: 7370
08-03 17:25:35.644  7370  7912 E AndroidRuntime: java.lang.IllegalArgumentException: Unknown URL content://com.samsung.android.provider.filterprovider/packages/com.test.thalitest
08-03 17:25:35.644  7370  7912 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
08-03 17:25:35.644  7370  7912 E AndroidRuntime: 	at com.samsung.android.app.filterinstaller.FilterUninstaller.removeFromDB(FilterUninstaller.java:52)
08-03 17:25:35.644  7370  7912 E AndroidRuntime: 	at com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters(FilterUninstaller.java:43)
08-03 17:25:35.644  7370  7912 E AndroidRuntime: 	at com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage(FilterPackageService.java:149)
08-03 17:25:35.644  7370  7912 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 17:25:35.644  7370  7912 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-03 17:25:35.644  7370  7912 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-03 17:25:35.644  6592  7947 E NativeCrashHandler: Native crash signal: 7 code: 2 address: 0xffffffff9f8f15e2
08-03 17:25:35.644  6592  7947 E NativeCrashHandler: joq: Native crash signal: 7 code: 2 address: 0xffffffff9f8f15e2
08-03 17:25:35.644  6592  7947 E NativeCrashHandler: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.reportCrash(PG:137)
08-03 17:25:35.644  6592  7947 E NativeCrashHandler: 	at lpq.a(PG:50)
08-03 17:25:35.644  6592  7947 E NativeCrashHandler: 	at lqt.uncaughtException(PG:43)
08-03 17:25:35.644  6592  7947 E NativeCrashHandler: 	at mus.uncaughtException(PG:100)
08-03 17:25:35.644  6592  7947 E NativeCrashHandler: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-03 17:25:35.644  6592  7947 E NativeCrashHandler: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-03 17:25:35.644  6592  7947 I Timeline: Timeline: Activity_launch_request id:com.google.android.apps.plus time:170159
,08-03 17:25:35.644  2537  5236 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml
08-03 17:25:35.644  6592  7947 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9f8f15e2 in tid 7947 (IntentService[G)
,08-03 17:25:35.654  7370  7912 E AndroidRuntime: Error reporting crash
08-03 17:25:35.654  7370  7912 E AndroidRuntime: android.os.DeadObjectException
08-03 17:25:35.654  7370  7912 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 17:25:35.654  7370  7912 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 17:25:35.654  7370  7912 E AndroidRuntime: 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4706)
08-03 17:25:35.654  7370  7912 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
08-03 17:25:35.654  7370  7912 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-03 17:25:35.654  7370  7912 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-03 17:25:35.654  7370  7912 I Process : Sending signal. PID: 7370 SIG: 9
,08-03 17:25:35.654  2537  7913 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTQQstg5Gl8KHWNvbS5nb29nbGUuYW5kcm9pZC
08-03 17:25:35.654  2537  7913 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjcuMjQgKDMwNTE3NzQtMDM4KRjm-eAR
08-03 17:25:35.654  2537  7913 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQwPngEQ
08-03 17:25:35.654  2537  7913 I GCore-Chimera-Crash: ==
08-03 17:25:35.654  2537  7913 I GCore-Chimera-Crash: GCore-Chimera-Crash
08-03 17:25:35.654  2537  7913 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
08-03 17:25:35.654  2537  7913 I DeviceDoctorDatabaseHelper: Cleaning stale data from database!
,08-03 17:25:35.654  2537  7913 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db" with flag (131138) and mode_t (0) due to error (30)
08-03 17:25:35.654  2537  7913 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db" with flag (131072) and mode_t (0) due to error (2)
08-03 17:25:35.654  2537  7913 E SQLiteLog: (14) cannot open file at line 32509 of [b3bb660af9]
08-03 17:25:35.654  2537  7913 E SQLiteLog: (14) os_unix.c:32509: (2) open(/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db) - 
,08-03 17:25:35.664  2537  7913 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db'.
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1496)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at ivm.g(:com.google.android.gms:204)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at ivm.e(:com.google.android.gms:176)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at ivh.a(:com.google.android.gms:22519)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at iiq.c(:com.google.android.gms:207)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at ifm.uncaughtException(:com.google.android.gms:2111)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at ifs.uncaughtException(:com.google.android.gms:54)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at ifl.uncaughtException(:com.google.android.gms:62)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at cir.uncaughtException(:com.google.android.gms:112)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-03 17:25:35.664  2537  7913 E SQLiteDatabase: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-03 17:25:35.664  2537  7913 E AndroidRuntime: Process: com.google.android.gms, PID: 2537
08-03 17:25:35.664  2537  7913 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransa,ction(SQLiteDatabase.java:421)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at pgd.a(:com.google.android.gms:290)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at pgd.b(:com.google.android.gms:138)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at phk.a(:com.google.android.gms:382)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at com.google.android.gms.icing.proxy.InternalIcingCorporaChimeraProvider.update(:com.google.android.gms:247)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at com.google.android.chimera.container.ContentProviderProxy.update(:com.google.android.gms:462)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:330)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1343)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at pih.call(:com.google.android.gms:1333)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at pii.call(:com.google.android.gms:1266)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at com.google.android.gms.icing.proxy.UpdateIcingCorporaChimeraService.a(:com.google.android.gms:244)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at com.google.android.gms.icing.proxy.UpdateIcingCorporaChimeraService.onHandleIntent(:com.google.android.gms:2177)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at bhe.handleMessage(:com.google.android.gms:65)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: Error reporting crash
08-03 17:25:35.664  2537  7913 E AndroidRuntime: android.os.DeadObjectException
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4706)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at ifm.uncaughtException(:com.google.android.gms:42)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at ifs.uncaughtException(:com.google.android.gms:54)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at ifl.uncaughtException(:com.google.android.gms:62)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at cir.uncaughtException(:com.google.android.gms:112)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-03 17:25:35.664  2537  7913 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-03 17:25:35.664  2537  7913 I Process : Sending signal. PID: 2537 SIG: 9
,08-03 17:25:35.754   302   302 I DEBUG   : failed to change ownership of /data/tombstones: Read-only file system
08-03 17:25:35.754   302   302 E         : ro.product_ship = true
08-03 17:25:35.754   302   302 E         : ro.debug_level = 0x4f4c
,08-03 17:25:35.754   314   314 E installd: eof
08-03 17:25:35.754  1772  1772 E audit_log: File locking failed. error= Bad file number
08-03 17:25:35.754   314   314 E installd: failed to read size
08-03 17:25:35.754   314   314 I installd: closing connection
,08-03 17:25:35.834   355   355 I Zygote  : Process 6592 exited due to signal (7)
,08-03 17:25:35.854   267   523 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-03 17:25:35.854   267   267 E qdexternal: writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
08-03 17:25:35.854   267   267 D qdhwcomposer: hwc_blank: Done unblanking display: 0
08-03 17:25:35.854   267   559 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
,08-03 17:25:35.854   267   559 E SurfaceFlinger: eventControl(0, 1) failed Operation not permitted
,08-03 17:25:36.024   267   523 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
