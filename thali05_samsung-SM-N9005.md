#### Test 6810213040493cb_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
07-28 12:30:39.475   937  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
07-28 12:30:40.605  7414  7414 D AndroidRuntime: 
07-28 12:30:40.605  7414  7414 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-28 12:30:40.605  7414  7414 D AndroidRuntime: CheckJNI is OFF
07-28 12:30:40.605  7414  7414 D AndroidRuntime: readGMSProperty: start
07-28 12:30:40.605  7414  7414 D AndroidRuntime: readGMSProperty: already setted!!
07-28 12:30:40.605  7414  7414 D AndroidRuntime: readGMSProperty: end
07-28 12:30:40.605  7414  7414 D AndroidRuntime: addProductProperty: start
07-28 12:30:40.775  7414  7414 E AffinityControl: AffinityControl: registerfunction enter
07-28 12:30:40.795  7414  7414 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-28 12:30:40.805   937  1434 E PersonaManagerService: inState():  stateMachine is null !!
07-28 12:30:40.805   937  1434 I PersonaManagerService: PersonaId don't exist
07-28 12:30:40.805   937  1434 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-28 12:30:40.805   937  1434 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-28 12:30:40.805   937  1434 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-28 12:30:40.815   937  1434 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-28 12:30:40.815   937  1434 W ActivityManager: mDVFSHelper.acquire()
07-28 12:30:40.815   937  1434 D FocusedStackFrame: Set to : 0
07-28 12:30:40.815   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:40.815   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:40.815   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:40.815   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:40.865   937  1434 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7429 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-28 12:30:40.875  7429  7429 E Zygote  : MountEmulatedStorage()
07-28 12:30:40.875  7429  7429 E Zygote  : v2
07-28 12:30:40.875  7429  7429 I libpersona: KNOX_SDCARD checking this for 10079
07-28 12:30:40.875  7429  7429 I libpersona: KNOX_SDCARD not a persona
07-28 12:30:40.875   937  1062 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-28 12:30:40.885   937  1062 D PointerIcon: setMouseCustomIcon IconType is same.101
07-28 12:30:40.885   937  1062 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-28 12:30:40.885   937  1062 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-28 12:30:40.905  7414  7414 D AndroidRuntime: Shutting down VM
07-28 12:30:40.905  7429  7429 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:40.905  7429  7429 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:30:40.905  7429  7429 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-28 12:30:40.935  7429  7429 D TimaKeyStoreProvider: TimaSignature is unavailable
07-28 12:30:40.935  7429  7429 D ActivityThread: Added TimaKeyStore provider
07-28 12:30:40.945   937  1648 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-28 12:30:40.945   937  1648 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-28 12:30:40.945   937  1648 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-28 12:30:40.945   937  1648 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-28 12:30:40.945   937  1648 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-28 12:30:40.965  1442  1442 D SurfaceWidgetView: destroyHardwareResources():153551175
07-28 12:30:40.965   937  3069 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:40.975  7429  7429 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-28 12:30:40.985   937  3069 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:41.005   303   303 E SMD     : DCD ON
07-28 12:30:41.005   267  1647 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
07-28 12:30:41.015   267   417 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
07-28 12:30:41.015  1442  1442 V ActivityThread: updateVisibility : ActivityRecord{d9971a9 token=android.os.BinderProxy@353cf587 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-28 12:30:41.015  1759  1775 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
07-28 12:30:41.015  1442  1442 D Launcher: onTrimMemory. Level: 20
07-28 12:30:41.075  7429  7429 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-28 12:30:41.075  7429  7429 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
07-28 12:30:41.085  7429  7429 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7267-7269)
07-28 12:30:41.095  7429  7429 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:30:41.105  7429  7429 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {384f92ae}
07-28 12:30:41.105  7429  7429 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:30:41.105  7429  7429 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-28 12:30:41.135  7429  7429 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-28 12:30:41.135  7429  7429 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-28 12:30:41.135  7429  7429 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-28 12:30:41.155  7429  7429 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-28 12:30:41.155  7429  7429 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-28 12:30:41.155  7429  7429 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-28 12:30:41.165  7429  7429 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-28 12:30:41.165  7429  7429 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-28 12:30:41.165  7429  7429 I Adreno-EGL: Build Date: 11/19/14 Wed
07-28 12:30:41.165  7429  7429 I Adreno-EGL: Local Branch: mybranch5813579
07-28 12:30:41.165  7429  7429 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-28 12:30:41.165  7429  7429 I Adreno-EGL: Local Patches: NONE
07-28 12:30:41.165  7429  7429 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-28 12:30:41.255  7429  7461 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-28 12:30:41.285  7429  7429 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-28 12:30:41.295  7429  7429 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-28 12:30:41.305  7429  7429 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-28 12:30:41.315  7429  7429 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:30:41.315  7429  7429 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-28 12:30:41.365  7429  7429 D Activity: performCreate Call secproduct feature valuefalse
07-28 12:30:41.365  7429  7429 D Activity: performCreate Call debug elastic valuetrue
,07-28 12:30:41.375  7429  7474 D OpenGLRenderer: Render dirty regions requested: true
,07-28 12:30:41.375   937  1434 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-28 12:30:41.375   937  1434 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-28 12:30:41.375   937  1434 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-28 12:30:41.375   937   937 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-28 12:30:41.375   937   937 D PersonaManagerService: getPersonasForUser(): returning null!
,07-28 12:30:41.395   267   267 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,07-28 12:30:41.395   937  1060 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-28 12:30:41.405   937  1060 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-28 12:30:41.415   937  1062 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-28 12:30:41.415   937  1062 D PointerIcon: setMouseCustomIcon IconType is same.101
07-28 12:30:41.415   937  1062 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-28 12:30:41.415   937  1062 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-28 12:30:41.415  7429  7474 I OpenGLRenderer: Initialized EGL, version 1.4
,07-28 12:30:41.425  7429  7474 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3da5d58 ,&mEglDisplay = 1 , &mEglConfig = 8 
,07-28 12:30:41.425  7429  7474 D OpenGLRenderer: Enabling debug mode 0
,07-28 12:30:41.435  7429  7429 V ActivityThread: updateVisibility : ActivityRecord{fcb54f8 token=android.os.BinderProxy@a0f76a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-28 12:30:41.465   937  3040 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-28 12:30:41.465   937  7479 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-28 12:30:41.465  1696  1696 I SamsungIME: getCurrentCandidateView
,07-28 12:30:41.475  7429  7429 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-28 12:30:41.475  7429  7429 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a0f76a time:157653
,07-28 12:30:41.475   937  1062 W ActivityManager: mDVFSHelper.release()
07-28 12:30:41.475   937  1062 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{26d3209a u0 com.test.thalitest/.MainActivity t99} time:157659
,07-28 12:30:41.515  7429  7429 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7429
,07-28 12:30:41.535  1696  1696 D SamsungIME: Dismiss ExpandCandiate
,07-28 12:30:41.555   937  3069 D SSRM:n  : SIOP:: AP = 350, PST = 373, CUR = 450
,07-28 12:30:41.625  1696  1696 I SamsungIME: getDebugLevel  : 0x4f4c
,07-28 12:30:41.625  7429  7429 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-28 12:30:41.655  1696  1696 I SamsungIME: getDebugLevel  : 0x4f4c
,07-28 12:30:41.665  1696  1696 I SamsungIME: KeybaordView init() : load resources
,07-28 12:30:41.685  1696  1696 I SamsungIME: getCurrentKeyboard
,07-28 12:30:41.685  1696  1696 I SamsungIME: getTextKeyboard
,07-28 12:30:41.695  7429  7481 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258386560
,07-28 12:30:41.695  1696  1696 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-28 12:30:41.705  7429  7481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-28 12:30:41.705  7429  7481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-28 12:30:41.705  7429  7481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-28 12:30:41.705  7429  7481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-28 12:30:41.705  7429  7481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-28 12:30:41.705  7429  7481 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3139ec28 added. We now have 1 listener(s)
,07-28 12:30:41.715  7429  7481 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:1F:C9:5E
,07-28 12:30:41.715  7429  7481 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:30:41.715  7429  7481 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:30:41.715  7429  7481 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 12:30:41.725  7429  7481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-28 12:30:41.725  7429  7481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-28 12:30:41.725  7429  7481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-28 12:30:41.725  7429  7481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:1F:C9:5E
07-28 12:30:41.725  7429  7481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-28 12:30:41.725  7429  7481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-28 12:30:41.725  7429  7481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-28 12:30:41.725  7429  7481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-28 12:30:41.725  7429  7481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-28 12:30:41.725  7429  7481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-28 12:30:41.725  7429  7481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-28 12:30:41.725  7429  7481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-28 12:30:41.725  7429  7481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-28 12:30:41.725  7429  7481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-28 12:30:41.725  7429  7481 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ded8027 added. We now have 1 listener(s)
,07-28 12:30:41.725  7429  7481 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:30:41.735  7429  7481 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:30:41.735  7429  7481 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
07-28 12:30:41.735  7429  7481 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
07-28 12:30:41.735  7429  7481 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
07-28 12:30:41.735  7429  7481 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,07-28 12:30:41.735  7429  7481 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:30:41.735  7429  7481 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:1F:C9:5E
,07-28 12:30:41.735   937  1556 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:41.745  7429  7481 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,07-28 12:30:41.745  7429  7481 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:30:41.745  7429  7481 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:41.745  7429  7481 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:41.745  7429  7481 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:41.745  7429  7481 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:30:41.745  7429  7481 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:30:41.745  7429  7481 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:30:41.745  7429  7481 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:30:41.745  7429  7481 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-28 12:30:41.745  7429  7481 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:30:41.745   937  1472 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:41.745  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:41.745   937  1434 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:41.745  7429  7481 I io.jxcore.node.LifeCycleMonitor: start: OK
07-28 12:30:41.745  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:41.775  7429  7429 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-28 12:30:42.025  1696  7485 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-28 12:30:42.445  7429  7490 W jxcore-log: Initializing JXcore engine
07-28 12:30:42.445  7429  7490 W jxcore-log: JXcore engine is ready
,07-28 12:30:42.495  1816  1816 E auditd  : In denial and Property audit_ondenial is set to 1 
,07-28 12:30:42.495  1816  1816 E audit   : type=1400 msg=audit(1469701842.485:203): avc:  denied  { ioctl } for  pid=7490 comm="Thread-1234" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-28 12:30:42.495  1816  1816 E audit   :  SEPF_SM-N9005_5.0-1_0032
07-28 12:30:42.495  1816  1816 E audit   : 
07-28 12:30:42.495  1816  1816 E audit   : type=1300 msg=audit(1469701842.485:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=98a008d8 items=0 ppid=337 ppcomm=main pid=7490 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1234" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,07-28 12:30:42.495  1816  1816 E audit   : type=1320 msg=audit(1469701842.485:203): 
07-28 12:30:42.495   937  1049 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
07-28 12:30:42.495   937  1049 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,07-28 12:30:42.495   937  1049 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,07-28 12:30:42.505  6889  6889 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-28 12:30:42.505  7429  7490 W jxcore-log: Starting JXcore engine
07-28 12:30:42.505  6889  6889 D SecurityLogAgent:  SeDenialReceiver : File path = null
,07-28 12:30:42.585  7429  7490 W jxcore-log: Platform android
07-28 12:30:42.585  7429  7490 W jxcore-log: 
07-28 12:30:42.585  7429  7490 W jxcore-log: Process ARCH arm
07-28 12:30:42.585  7429  7490 W jxcore-log: 
,07-28 12:30:42.755  7429  7490 I jxcore-log: JXcore Cordova bridge is ready!
07-28 12:30:42.755  7429  7490 I jxcore-log: 
,07-28 12:30:42.755  7429  7490 W jxcore-log: JXcore engine is started
,07-28 12:30:42.765  7429  7481 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-28 12:30:42.765  7429  7429 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-28 12:30:44.005   303   303 E SMD     : DCD ON
,07-28 12:30:44.305   349   349 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:30:44.405   937  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-28 12:30:44.405   937  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-28 12:30:44.405   937  1479 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-28 12:30:44.405   937   937 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-28 12:30:44.415   937   937 I MotionRecognitionService: Plugged
,07-28 12:30:44.415   937   937 I MotionRecognitionService: setPowerConnected  = true
,07-28 12:30:44.415   937  1479 D BatteryService: stay LED for fully charged
,07-28 12:30:44.415  1194  1194 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-28 12:30:44.415  1194  1194 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-28 12:30:44.425  1194  1194 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-28 12:30:44.425  1194  1194 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:30:44.425  1194  1194 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-28 12:30:44.425  1194  1194 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:30:44.425  2992  2992 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-28 12:30:44.425  2992  3066 D HeadsetStateMachine: Disconnected process message: 10
,07-28 12:30:45.305   349   349 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:30:46.305   349   349 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:30:47.005   303   303 E SMD     : DCD ON
,07-28 12:30:47.305   349   349 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:30:48.305   349   349 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:30:49.305   349   349 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-28 12:30:50.005   303   303 E SMD     : DCD ON
,07-28 12:30:50.865   937  1068 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-28 12:30:51.595   937  3069 D SSRM:n  : SIOP:: AP = 390, PST = 375, CUR = 450
,07-28 12:30:52.255  1823  2936 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-28 12:30:52.555   937  1348 E Watchdog: !@Sync 5
,07-28 12:30:52.895  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-28 12:30:52.895  7429  7490 I jxcore-log: 
,07-28 12:30:52.895  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-28 12:30:52.895  7429  7490 I jxcore-log: 
,07-28 12:30:52.895   937  1242 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:52.905  7429  7490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:30:52.905  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:52.905  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:52.905  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:52.905  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:30:52.905  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:30:52.905  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:30:52.905  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:30:52.905  7429  7490 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:30:52.915  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-28 12:30:52.915  7429  7490 I jxcore-log: 
,07-28 12:30:52.915  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-28 12:30:52.915  7429  7490 I jxcore-log: 
,07-28 12:30:53.005   303   303 E SMD     : DCD ON
,07-28 12:30:53.265  7429  7490 D ExecuteNativeTests: Running unit tests
,07-28 12:30:53.365  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:30:53.365  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 added. We now have 2 listener(s)
,07-28 12:30:53.365  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:30:53.365  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:30:53.365  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:30:53.365  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:30:53.365  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 added. We now have 2 listener(s)
07-28 12:30:53.365  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:30:53.365  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:30:53.365  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:30:53.365   937  1242 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.375  7429  7490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:30:53.375  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:53.375  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:53.375  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:53.375  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:30:53.375  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:30:53.375  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:30:53.375  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:30:53.375  7429  7490 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:30:53.375  7429  7490 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:30:53.375   937  1537 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.375  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:53.375   937  1147 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.375  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:30:53.375  7429  7490 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:30:53.375  7429  7490 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-28 12:30:53.375  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:53.395  7429  7490 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-28 12:30:53.395  7429  7490 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 12:30:53.395  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-28 12:30:53.395  7429  7490 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-28 12:30:53.395  7429  7490 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-28 12:30:53.395  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:30:53.405  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.405  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:30:53.405  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.405  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.405  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:30:53.405  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-28 12:30:53.405  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 removed from the list
07-28 12:30:53.405  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.405  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 removed from the list
07-28 12:30:53.405  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.405  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.405  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.405  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.405  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.405  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.405  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.405  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
,07-28 12:30:53.405  7429  7490 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,07-28 12:30:53.405  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.405  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.405  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:30:53.405  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.405  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.405  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:30:53.405  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.405  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.405  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.405  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.405  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.405  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:30:53.405  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.405  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:30:53.415  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.415  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.415  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.415  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
,07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 12:30:53.415  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:30:53.425  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 12:30:53.425  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:30:53.425  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 12:30:53.425  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 12:30:53.425  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:30:53.425  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 12:30:53.425  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 12:30:53.425  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 12:30:53.425  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 12:30:53.425  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:30:53.425  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:30:53.425  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 12:30:53.425  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 12:30:53.425  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.425  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.425  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.425  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.425  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.425  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.425  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.425  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.425  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.425  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.425  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.425  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.425  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.425  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.425  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.425  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.425  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.425  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.425  7429  7490 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:30:53.425  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:30:53.425   937  1537 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:53.425  7429  7490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:30:53.425  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:53.425  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:53.425  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:53.425  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:30:53.425  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:30:53.425  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:30:53.425  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:30:53.435  7429  7490 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:30:53.435  7429  7490 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:30:53.435   937  1364 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:53.435  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:53.435   937  1479 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:53.435  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:30:53.435  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:30:53.435  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:30:53.435  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:30:53.435  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:30:53.435  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:53.435  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:30:53.435  7429  7490 E BluetoothAdapter: bluetooth le advertising not supported
07-28 12:30:53.435  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:30:53.445  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:30:53.445  7429  7490 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
07-28 12:30:53.445  7429  7490 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
07-28 12:30:53.445  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:30:53.445  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:30:53.445  7429  7490 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:30:53.445  7429  7490 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:30:53.455  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.455  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.455  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.455  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.455  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.455  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:30:53.455  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.455  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.455  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.455  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.455  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.455  7429  7490 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:30:53.455  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:30:53.455   937  1434 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:53.455  7429  7490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:30:53.455  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:53.455  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:53.455  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:53.455  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:30:53.455  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:30:53.455  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:30:53.455  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:30:53.455  7429  7490 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:30:53.455  7429  7490 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:30:53.455  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:30:53.455  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:30:53.455   937  1737 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:53.455  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:30:53.455  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:30:53.455  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:30:53.465  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:53.465   937  1434 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:53.465  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:53.465  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:30:53.465  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:30:53.465  7429  7490 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:30:53.465  7429  7490 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:30:53.465  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.465  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.465  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.465  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.465  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.465  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:30:53.465  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.465  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.465  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.465  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.465  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.465  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.465  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.475  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.475  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.475  7429  7490 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.475  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.475  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.475  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.475  7429  7490 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:30:53.475  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:30:53.475   937  1537 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:53.475  7429  7490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:30:53.475  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:53.475  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:53.475  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:53.475  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:30:53.475  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:30:53.475  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:30:53.475  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:30:53.475  7429  7490 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:30:53.475  7429  7490 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:30:53.475  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:30:53.475   937  1666 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:53.475  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:53.475   937  1648 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:53.475  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:53.475  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:30:53.475  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:30:53.475  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:30:53.475  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:30:53.485  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:30:53.485  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:30:53.485  7429  7490 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:30:53.485  7429  7490 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:30:53.485  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.485  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.485  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.485  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.485  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.485  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.485  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.485  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.485  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:30:53.485  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.485  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.485  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.485  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.485  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.485  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.485  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.485  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.485  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.485  7429  7490 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.485  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.485  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.485  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.485  7429  7490 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-28 12:30:53.485  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.485  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.485  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.495  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.495  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.495  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.495  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.495  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.495  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.495  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.495  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.495  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.495  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.495  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.495  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.495  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.495  7429  7490 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.495  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.495  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.495  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.495  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 12:30:53.495  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.495  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.495  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.495  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.495  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.495  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.495  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.495  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.495  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.495  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.495  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.495  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.495  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.495  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.495  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.495  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.495  7429  7490 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.495  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.495  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.495  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.495  7429  7490 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-28 12:30:53.495  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.495  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.495  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:30:53.495  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.495  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.495  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.495  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.495  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.495  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.495  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.495  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.495  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.495  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.495  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.505  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.505  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.505  7429  7490 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.505  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.505  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.505  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.505  7429  7490 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-28 12:30:53.505  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.505  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.505  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.505  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.505  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.505  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.505  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.505  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.505  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.505  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.505  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.505  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.505  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.505  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.505  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.505  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.505  7429  7490 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.505  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.505  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.505  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.505  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:30:53.505  7429  7490 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:30:53.505  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:30:53.505  7429  7490 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:30:53.505  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:30:53.505  7429  7490 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:30:53.505  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.505  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.505  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.505  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.505  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.505  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.505  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.505  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.505  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.505  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.505  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.505  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.505  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.505  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.515  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.515  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.515  7429  7490 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.515  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.515  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.515  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.515  7429  7490 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:30:53.515  7429  7490 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-28 12:30:53.515  7429  7490 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:30:53.515  7429  7490 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:30:53.515  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 12:30:53.525  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 12:30:53.525  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 12:30:53.525  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 12:30:53.525  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:30:53.525  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:30:53.525  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 12:30:53.525  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 12:30:53.525  7429  7490 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-28 12:30:53.525  7429  7490 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:30:53.525  7429  7490 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-28 12:30:53.525  7429  7490 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:30:53.525  7429  7490 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:30:53.525  7429  7490 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-28 12:30:53.525  7429  7490 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:30:53.525  7429  7490 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:30:53.525  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-28 12:30:53.525  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-28 12:30:53.535  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-28 12:30:53.535  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-28 12:30:53.535  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-28 12:30:53.535  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-28 12:30:53.535  7429  7490 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-28 12:30:53.535  7429  7490 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:30:53.535  7429  7490 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-28 12:30:53.535  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.535  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.535  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.535  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.535  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.535  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.535  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-28 12:30:53.535  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.535  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.535  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.535  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.535  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.535  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.535  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.535  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.535  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.535  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.535  7429  7490 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.535  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.535  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.535  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
,07-28 12:30:53.545  7429  7501 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1298)
07-28 12:30:53.545  7429  7490 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-28 12:30:53.545  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.545  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.545  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.545  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.545  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.545  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.545  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.545  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.545  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.545  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.545  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.545  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.545  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.545  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.545  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.545  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.545  7429  7490 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.545  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.545  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.545  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.545  7429  7490 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-28 12:30:53.545  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.545  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.545  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.545  7429  7501 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
07-28 12:30:53.545  7429  7501 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:30:53.555  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.555  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.555  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.555  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.555  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.555  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.555  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.555  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.555  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.555  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.555  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.555  7429  7502 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1298
07-28 12:30:53.555  7429  7502 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 1298)
07-28 12:30:53.555  7429  7502 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@4ee0a58, channel: -1, state: INIT
07-28 12:30:53.555  7429  7502 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@4ee0a58, channel: -1, mSocketIS: null, mSocketOS: nullmSocket: null
07-28 12:30:53.555  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.555  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.555  7429  7490 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.555  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.555  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.555  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.555  2992  3003 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:30:53.555  7429  7490 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-28 12:30:53.555  7429  7490 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-28 12:30:53.555  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:30:53.555  7429  7490 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-28 12:30:53.555  7429  7502 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 1298)
07-28 12:30:53.555  7429  7490 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:30:53.555  7429  7490 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-28 12:30:53.555  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:30:53.555  7429  7490 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-28 12:30:53.555  7429  7490 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:30:53.555  7429  7490 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 12:30:53.555  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:30:53.555  7429  7490 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-28 12:30:53.555  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.555  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.555  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.555  2992  3123 D bt_vendor: op for 7
07-28 12:30:53.555  7429  7501 D BluetoothSocket: connect(), SocketState: CLOSED, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
07-28 12:30:53.555  7429  7501 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@4ee0a58, channel: -1, state: CLOSED
07-28 12:30:53.555  7429  7501 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1298)
07-28 12:30:53.555  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.555  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.555  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.555  2992  3123 D bt_upio : proc btwrite assertion
07-28 12:30:53.555  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.555  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.555  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.555  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.555  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.555  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.555  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.555  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.565  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.565  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.565  7429  7490 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.565  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.565  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.565  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.565  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.565  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.565  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.565  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.565  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.565  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.565  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.565  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.565  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.565  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.565  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.565  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.565  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.565  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.565  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.565  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.565  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.565  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.565  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.565  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.565  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.565  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.565  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.565  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.565  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.565  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.565  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.565  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.565  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.575  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.575  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.575  7429  7490 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.575  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.575  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.575  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.575  7429  7490 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-28 12:30:53.575  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:30:53.575  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-28 12:30:53.575  7429  7490 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-28 12:30:53.575  7429  7490 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-28 12:30:53.575  7429  7429 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-28 12:30:53.575  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-28 12:30:53.575  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-28 12:30:53.575  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.575  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-28 12:30:53.575  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-28 12:30:53.575  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-28 12:30:53.575  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.575  7429  7490 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,07-28 12:30:53.575  7429  7429 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-28 12:30:53.575  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.575  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.575  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:30:53.575  7429  7490 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 12:30:53.575  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:30:53.585  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 12:30:53.585  7429  7490 D BluetoothLeScanner: could not find callback wrapper
07-28 12:30:53.585  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:30:53.585  7429  7490 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 12:30:53.585  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.585  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.585  7429  7490 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:30:53.585  7429  7429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:30:53.585  7429  7429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:30:53.585  7429  7429 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:30:53.585  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.585  7429  7503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-28 12:30:53.585  7429  7503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-28 12:30:53.585  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.585  7429  7429 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-28 12:30:53.585  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.585  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.585  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.585  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.585  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.585  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.585  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.585  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.585  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.585  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.585  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.585  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.585  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.585  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.585  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.585  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.585  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.585  7429  7490 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-28 12:30:53.585  7429  7490 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 12:30:53.585  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:30:53.585  7429  7490 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-28 12:30:53.585  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.585  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.585  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.585  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.585  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.585  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:30:53.595  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.595  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.595  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.595  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.595  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.595  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.595  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:30:53.595  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.595  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:30:53.595  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.595  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.595  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
,07-28 12:30:53.595  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.595  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.595  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:30:53.595  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:30:53.595  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.595  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.595  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
,07-28 12:30:53.595  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.595  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.595  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.595  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.595  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.595  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.595  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:30:53.595  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.595  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.595  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:30:53.595  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
,07-28 12:30:53.595  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:30:53.595  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:30:53.595  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:30:53.595  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:30:53.595  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.595  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.595  7429  7490 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3eb72a72 not in the list
07-28 12:30:53.595  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.595  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
07-28 12:30:53.605  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:30:53.605  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:30:53.605  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:30:53.605  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:30:53.605  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:30:53.605  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:30:53.605  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:30:53.605  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:30:53.605  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@917fec3 not in the list
,07-28 12:30:53.605  7429  7490 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,07-28 12:30:53.605  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:30:53.605  7429  7490 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-28 12:30:53.605  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:30:53.605  7429  7490 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,07-28 12:30:53.605  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-28 12:30:53.605  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 12:30:53.605  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,07-28 12:30:53.605  7429  7490 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-28 12:30:53.605  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:30:53.605  7429  7490 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-28 12:30:53.605  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:30:53.605  7429  7490 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-28 12:30:53.605  7429  7490 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,07-28 12:30:53.605  7429  7490 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,07-28 12:30:53.605  7429  7490 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-28 12:30:53.605  7429  7490 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,07-28 12:30:53.605  7429  7490 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-28 12:30:53.605  7429  7490 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-28 12:30:53.615  7429  7490 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,07-28 12:30:53.615  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:30:53.615  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@389167b1 added. We now have 2 listener(s)
07-28 12:30:53.615  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:30:53.615  7429  7490 D BluetoothAdapter: enable()
07-28 12:30:53.615  7429  7490 D BluetoothAdapter: enable(): BT is already enabled..!
,07-28 12:30:53.615  7429  7490 I WifiManager: packageName : com.test.thalitest
07-28 12:30:53.615   937  1737 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-28 12:30:53.615   937  1737 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:30:53.615   937  1737 D SecContentProvider2: mCursor = null
,07-28 12:30:53.615   937  1737 D WifiService: setWifiEnabled: true pid=7429, uid=10079
,07-28 12:30:53.615   937  1737 W ActivityManager: Permission Denial: getCurrentUser() from pid=7429, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:30:53.615   937  1737 W WifiService: Failed getting userId using ActivityManagerNative
07-28 12:30:53.615   937  1737 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7429, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:30:53.615   937  1737 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-28 12:30:53.615   937  1737 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-28 12:30:53.615   937  1737 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-28 12:30:53.615   937  1737 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-28 12:30:53.615   937  1737 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-28 12:30:53.615   937  1737 D SettingsProvider: name = wifi_on
,07-28 12:30:53.615  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:30:53.615  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7674496 added. We now have 3 listener(s)
07-28 12:30:53.615  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:30:53.615  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:30:53.615  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3fe21817 added. We now have 4 listener(s)
07-28 12:30:53.615  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:30:53.625  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:30:53.625  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f657404 added. We now have 5 listener(s)
07-28 12:30:53.625  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:30:53.625  7429  7490 I WifiManager: packageName : com.test.thalitest
,07-28 12:30:53.625   937  1253 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-28 12:30:53.625   937  1253 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:30:53.625   937  1253 D SecContentProvider2: mCursor = null
07-28 12:30:53.625   937  1253 D WifiService: setWifiEnabled: false pid=7429, uid=10079
07-28 12:30:53.625   937  1253 D SettingsProvider: name = wifi_on
07-28 12:30:53.625  7429  7490 D BluetoothAdapter: disable()
07-28 12:30:53.625   937  1737 D SettingsProvider: name = bluetooth_on
,07-28 12:30:53.625   937  1152 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-28 12:30:53.625  1285  1285 I wpa_supplicant: reset timer : RESET_TIMER 0
07-28 12:30:53.625  1285  1285 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-28 12:30:53.635  1285  1285 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-28 12:30:53.635  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:30:53.635   937  3040 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:53.635  2992  3057 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
07-28 12:30:53.635  2992  3057 D BluetoothAdapterProperties: Setting state to 13
07-28 12:30:53.635  2992  3057 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-28 12:30:53.635  2992  3057 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:30:53.635  2992  3057 D BluetoothAdapterService: updateAdapterState state is 13
,07-28 12:30:53.635   937  1147 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:30:53.635   937  1147 D ActivityManager: caller:android.app.ApplicationThreadProxy@12ce296f, r.packageName :com.android.bluetooth
,07-28 12:30:53.635  2992  2992 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
07-28 12:30:53.635  2992  3057 D BluetoothAdapterService: Autoconnection is available 
07-28 12:30:53.635  2992  2992 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@14e657b3, channel: 19, state: LISTENING
,07-28 12:30:53.635  2992  3057 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
07-28 12:30:53.635  2992  2992 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@14e657b3, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10d41840, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c3e1170mSocket: android.net.LocalSocket@1c5dbce9 impl:android.net.LocalSocketImpl@28ae9d6e fd:FileDescriptor[72]
07-28 12:30:53.635  2992  2992 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1c5dbce9 impl:android.net.LocalSocketImpl@28ae9d6e fd:FileDescriptor[72]
07-28 12:30:53.635  2992  3057 D BluetoothAdapterService: terminating service from this receiver
,07-28 12:30:53.635   937  1152 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:30:53.645  1285  1285 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-28 12:30:53.645   937   937 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:30:53.645   937   937 I InputMethodManagerService: [BT Setting State] State =13
,07-28 12:30:53.645  2992  3057 D BluetoothAdapterProperties: onBluetoothDisable()
,07-28 12:30:53.645   937  1471 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-28 12:30:53.655  1194  1194 D BluetoothTile:  onBluetoothStateChange:
,07-28 12:30:53.655  2992  2992 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9cad49c, channel: 5, state: LISTENING
07-28 12:30:53.655  2992  2992 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@9cad49c, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28d4af58, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@4cc3ea5mSocket: android.net.LocalSocket@1eab227a impl:android.net.LocalSocketImpl@17bb0a2b fd:FileDescriptor[74]
07-28 12:30:53.655  2992  2992 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1eab227a impl:android.net.LocalSocketImpl@17bb0a2b fd:FileDescriptor[74]
,07-28 12:30:53.655  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:30:53.655   937  1152 E native  : do suspend true
,07-28 12:30:53.655  1696  1696 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-28 12:30:53.655  2992  3057 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,07-28 12:30:53.655  2992  2992 I BtOppRfcommListener: stopping Accept Thread
,07-28 12:30:53.655  2992  3123 D bt_vendor: op for 7
07-28 12:30:53.655  2992  3123 D bt_upio : BT_WAKE is asserted already
07-28 12:30:53.655  2992  2992 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1ffe9e88, channel: 12, state: LISTENING
07-28 12:30:53.655  2992  2992 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1ffe9e88, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38349122, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@18e72021mSocket: android.net.LocalSocket@b8ec46 impl:android.net.LocalSocketImpl@2ade1e07 fd:FileDescriptor[78]
07-28 12:30:53.655  2992  2992 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@b8ec46 impl:android.net.LocalSocketImpl@2ade1e07 fd:FileDescriptor[78]
,07-28 12:30:53.655  2992  3123 D bt_vendor: op for 7
07-28 12:30:53.655  2992  3123 D bt_upio : BT_WAKE is asserted already
07-28 12:30:53.665   937  1151 D WifiP2pService: InactiveState{ what=143375 }
,07-28 12:30:53.665   937  1151 D WifiP2pService: P2pEnabledState{ what=143375 }
07-28 12:30:53.665  2992  5609 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:30:53.665  2992  3060 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:30:53.665  2992  3123 D bt_vendor: op for 7
07-28 12:30:53.665  2992  3123 D bt_upio : BT_WAKE is asserted already
,07-28 12:30:53.665  2992  5609 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-28 12:30:53.665   937  1253 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:30:53.665  2992  3057 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-28 12:30:53.665   937  1253 D ActivityManager: caller:android.app.ApplicationThreadProxy@d41a67c, r.packageName :com.google.android.gms
07-28 12:30:53.665  2992  3057 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,07-28 12:30:53.665  2992  3057 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
07-28 12:30:53.665  2992  3057 E bt-btif : cmd socket is not created
,07-28 12:30:53.665  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:30:53.665  2992  3119 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
07-28 12:30:53.665  2992  3123 D bt_vendor: op for 7
07-28 12:30:53.665  2992  3123 D bt_upio : BT_WAKE is asserted already
07-28 12:30:53.665  2992  3119 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-28 12:30:53.665  2992  3119 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:30:53.665  2992  3119 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:30:53.665  2992  3119 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,07-28 12:30:53.665  2992  3057 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-28 12:30:53.665   937  1737 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-28 12:30:53.665   937  1737 D ActivityManager: caller:android.app.ApplicationThreadProxy@1467f75a, r.packageName :com.android.settings
,07-28 12:30:53.665  2992  3123 D bt_vendor: op for 7
07-28 12:30:53.665  2992  3123 D bt_upio : BT_WAKE is asserted already
,07-28 12:30:53.665   298  1058 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:30:53.665  2992  3123 D bt_vendor: op for 7
07-28 12:30:53.665  2992  3123 D bt_upio : BT_WAKE is asserted already
,07-28 12:30:53.685  2992  3123 D bt_vendor: op for 7
07-28 12:30:53.685  2992  3123 D bt_upio : BT_WAKE is asserted already
,07-28 12:30:53.685  1194  1194 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:30:53.685   937  1472 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:53.685  1194  1194 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-28 12:30:53.695  2992  3123 D bt_vendor: op for 7
,07-28 12:30:53.695  2992  3123 D bt_upio : BT_WAKE is asserted already
,07-28 12:30:53.695  2992  3123 D bt_vendor: op for 7
,07-28 12:30:53.705  2992  3123 D bt_upio : BT_WAKE is asserted already
07-28 12:30:53.705  1823  5055 V NativeCrypto: Read error: ssl=0x9b569e00: I/O error during system call, Connection timed out
,07-28 12:30:53.705  2992  3123 D bt_vendor: op for 7
,07-28 12:30:53.705  2992  3123 D bt_upio : BT_WAKE is asserted already
,07-28 12:30:53.705  1194  1583 D BluetoothTile:  handleUpdatestate:false name:null
,07-28 12:30:53.705  2992  3123 D bt_vendor: op for 7
07-28 12:30:53.705  2992  3123 D bt_upio : BT_WAKE is asserted already
,07-28 12:30:53.705  1194  1583 D BluetoothTile:  handleUpdatestate:false name:null
07-28 12:30:53.705   937  1154 E ConnectivityService: updateNetworkInfo()
07-28 12:30:53.705   937  1154 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:30:53.705   937  1154 E ConnectivityService: updateNetworkInfo()
07-28 12:30:53.705   937  1154 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
,07-28 12:30:53.705   937  1154 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,07-28 12:30:53.705  1823  5055 V NativeCrypto: SSL shutdown failed: ssl=0x9b569e00: I/O error during system call, Broken pipe
,07-28 12:30:53.705   937  1648 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.715   937   937 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-28 12:30:53.715   937   952 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:30:53.715  2992  3123 D bt_vendor: op for 7
07-28 12:30:53.715  2992  3123 D bt_upio : BT_WAKE is asserted already
,07-28 12:30:53.725  2992  3123 D bt_vendor: op for 7
07-28 12:30:53.725  2992  3123 D bt_upio : BT_WAKE is asserted already
,07-28 12:30:53.725   937  1253 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-28 12:30:53.725  1194  1194 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:30:53.725  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-28 12:30:53.725  1823  5055 E GCM     : Wifi connection closed with errorCode 20
,07-28 12:30:53.725  1194  1583 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:30:53.725  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:53.725  7429  7490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:30:53.725  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:53.725  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:53.725  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:53.725  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:30:53.725  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:30:53.725  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:30:53.725  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:30:53.725  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:53.725  7429  7490 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:30:53.725  2992  3123 D bt_vendor: op for 7
07-28 12:30:53.725  2992  3123 D bt_upio : BT_WAKE is asserted already
,07-28 12:30:53.725  7429  7490 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:30:53.725   937  3040 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.725  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:30:53.725  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:30:53.725  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:53.725  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:53.725  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:53.725  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:30:53.725  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:53.725  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:53.725  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:30:53.735  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:30:53.735  7429  7429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:30:53.735   937   952 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.735  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:53.735   937  1737 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.735   937  1152 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:30:53.735  2992  3123 D bt_vendor: op for 7
07-28 12:30:53.735  2992  3123 D bt_upio : BT_WAKE is asserted already
,07-28 12:30:53.735  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:30:53.735  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-28 12:30:53.735  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-28 12:30:53.735  1194  1194 D StatusBar.NetworkController: applyOpen
,07-28 12:30:53.735  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:53.735  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:53.745  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:53.745  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:53.745   937  1648 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.745  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:53.745  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:53.745  1194  1194 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-28 12:30:53.745  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:53.745  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:30:53.745  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:53.745  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:53.745  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:53.745  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:30:53.745  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:53.745  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:53.745  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:30:53.745  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:53.745  7429  7429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:30:53.745   937  1537 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.745   937  1253 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
,07-28 12:30:53.745   937  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:53.745   937  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:53.745   937  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
07-28 12:30:53.745   937  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:53.745   937  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,07-28 12:30:53.745  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:53.745   937   937 D WifiScanningService: SCAN_AVAILABLE : 1
07-28 12:30:53.745   937  1748 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-28 12:30:53.745   937   937 D RttService: SCAN_AVAILABLE : 1
07-28 12:30:53.745   937  1748 I qtaguid : Tagging socket 392 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 937, getuid(): 1000
,07-28 12:30:53.745   937  1170 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:53.745   937  1169 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:30:53.745   937  1151 D WifiP2pService: InactiveState{ what=131204 }
,07-28 12:30:53.745   937  1151 D WifiP2pService: P2pEnabledState{ what=131204 }
07-28 12:30:53.745   937  1748 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-28 12:30:53.745   937  1151 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-28 12:30:53.755   937  1062 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:53.755   937  1062 D WifiDisplayAdapter: onP2pDisconnected
,07-28 12:30:53.755   937  1062 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-28 12:30:53.755   937  1062 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-28 12:30:53.755   937  1151 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-28 12:30:53.755   937  1062 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-28 12:30:53.755   937   937 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-28 12:30:53.755   937  1062 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:30:53.755   937  1062 D WifiDisplayController: disconnect
07-28 12:30:53.755   937  1062 D WifiDisplayController: updateConnection
07-28 12:30:53.755   937  1062 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:30:53.755   937  1062 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-28 12:30:53.755   937  1472 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:53.755   937  1152 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-28 12:30:53.755  1315  1315 D BluetoothPbap: Proxy object disconnected
07-28 12:30:53.755  1315  1315 D PbapServerProfile: Bluetooth service disconnected
07-28 12:30:53.755   937  1364 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.755   937  3040 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.765  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:53.765   937  1666 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.765   937  1147 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.765  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:53.765  1194  1194 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-28 12:30:53.765   937  1364 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-28 12:30:53.765  1194  1194 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-28 12:30:53.765  1315  1315 D DockEventReceiver: finishStartingService: stopping service
07-28 12:30:53.765   937  1151 D WifiP2pService: P2pDisablingState
,07-28 12:30:53.765   937  1151 D WifiP2pService: P2pDisablingState{ what=147458 }
07-28 12:30:53.765   937  1151 D WifiP2pService: p2p socket connection lost
,07-28 12:30:53.765   937  1151 D WifiP2pService: P2pDisabledState
,07-28 12:30:53.775  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:30:53.775   937  1152 E native  : do suspend true
,07-28 12:30:53.785   937  1151 D WifiP2pService: P2pDisabledState{ what=143375 }
,07-28 12:30:53.785   937  1151 D WifiP2pService: DefaultState{ what=143375 }
,07-28 12:30:53.785   937  1062 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.785   937  1062 D WifiDisplayAdapter: onP2pDisconnected
07-28 12:30:53.785   937  1062 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-28 12:30:53.785   937  1062 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-28 12:30:53.785  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:30:53.785   298  1058 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:30:53.785  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:30:53.785   937  1154 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
07-28 12:30:53.785   937  1154 D ConnectivityService: calling update connectivity
07-28 12:30:53.785   937  1154 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:30:53.785   937  1154 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-28 12:30:53.785   937  1061 D EntConnectivity: Not allowed due to - mEnabled false
07-28 12:30:53.785   937  1154 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:30:53.785   937  1154 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:30:53.785   937  1154 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:30:53.785   937  1154 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-28 12:30:53.785   937  1154 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:30:53.785   937  1154 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:30:53.785   937  1147 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.785  1194  1580 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-28 12:30:53.785   937  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
07-28 12:30:53.785   937  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
07-28 12:30:53.785   937  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:53.785   937  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:53.785   937  1748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-28 12:30:53.785  1429  1429 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:30:53.785   937  1154 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
07-28 12:30:53.785   937  1154 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,07-28 12:30:53.795   937  1154 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-28 12:30:53.795  4453  7281 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,07-28 12:30:53.795  1285  1285 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,07-28 12:30:53.795   937  1149 V NetworkStats: updateIfacesLocked()
07-28 12:30:53.795  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:30:53.795  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:30:53.795   937  1149 V NetworkStats: performPollLocked(flags=0x1)
07-28 12:30:53.795   937   937 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-28 12:30:53.795   937  1149 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:30:53.795   937   937 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:30:53.795   937  1155 D Tethering: MasterInitialState.processMessage what=3
,07-28 12:30:53.795   937  1156 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,07-28 12:30:53.795   937  1156 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:30:53.795   937  1156 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:30:53.795   937  1156 D SmartBondingService: getSBEnabled() enabled =false
,07-28 12:30:53.795   937  1149 D NetworkStatsFactory: UpdateStatsForKnox
07-28 12:30:53.795   937  1149 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.795   937  1156 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-28 12:30:53.795   937  1364 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,07-28 12:30:53.805   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:30:53.805   937  1364 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:53.805   937  1364 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:53.805   937  1364 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:53.805   937  1364 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:53.805   937  1149 V NetworkStats: performPollLocked() took 8ms
,07-28 12:30:53.805   937  1149 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:30:53.805   937  1154 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:30:53.805   937  1737 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:53.805   937  1434 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:53.805  1194  1194 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-28 12:30:53.805   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:30:53.805   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:30:53.805   937  1154 E ConnectivityService: updateNetworkInfo()
07-28 12:30:53.805   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:30:53.805   937  1150 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-28 12:30:53.805   937  1154 E ConnectivityService: updateNetworkInfo()
07-28 12:30:53.805   937  1154 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:30:53.805   937  1154 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-28 12:30:53.805   937  1154 E ConnectivityService: EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,07-28 12:30:53.815  1194  1194 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-28 12:30:53.815  1194  1194 D StatusBar.NetworkController: updateDataNetType()
07-28 12:30:53.815  1194  1194 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-28 12:30:53.815  1194  1194 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-28 12:30:53.815  1194  1194 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-28 12:30:53.815  1194  1194 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,07-28 12:30:53.815  1194  1194 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
07-28 12:30:53.815  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:30:53.815  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-28 12:30:53.815  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:53.815  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:53.815  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:53.815  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:53.815  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:53.815  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:53.815  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:53.815  1194  1194 D StatusBar.NetworkController: applyOpen
,07-28 12:30:53.845  7528  7528 E Zygote  : MountEmulatedStorage()
07-28 12:30:53.845  7528  7528 E Zygote  : v2
07-28 12:30:53.845  7528  7528 I libpersona: KNOX_SDCARD checking this for 10140
07-28 12:30:53.845  7528  7528 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:53.845   937  1364 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7528 uid=10140 gids={50140, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,07-28 12:30:53.855  1285  1285 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:30:53.855  7528  7528 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:53.855  7528  7528 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:30:53.855  7528  7528 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
07-28 12:30:53.855   937   937 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:30:53.855  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:30:53.855  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-28 12:30:53.855  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:53.855  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:53.855  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:53.855  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:53.855  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:53.855  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:53.855  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:53.855  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:53.855  1194  1194 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:30:53.855  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:53.855  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:30:53.855  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:53.855  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:53.855  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:30:53.855  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:30:53.855  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:53.855  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:53.855  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:30:53.855  1194  1194 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
07-28 12:30:53.855  1194  1583 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-28 12:30:53.855  1194  1194 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:30:53.855   937  1156 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-28 12:30:53.855  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:53.855  7429  7429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:30:53.865  1194  1194 D HotspotTile: onReceive : 0, 0
,07-28 12:30:53.865  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:30:53.865  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:30:53.865  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:30:53.865  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:53.865  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:53.865  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:30:53.865  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:30:53.865  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:53.865  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:53.865  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:30:53.865  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:53.865  7429  7429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:30:53.865  2992  3123 D bt_vendor: op for 6
07-28 12:30:53.865  2992  3123 D bt_vendor: op for 7
07-28 12:30:53.865  2992  3123 D bt_upio : BT_WAKE is asserted already
07-28 12:30:53.865  2992  3125 D bt_userial: RX termination
07-28 12:30:53.865  2992  3125 W bt_userial: select_read return size <=0:-1, exiting userial_read_thread
07-28 12:30:53.865  2992  3125 D bt_userial: Leaving userial_read_thread()
,07-28 12:30:53.865  2992  3119 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:30:53.865  2992  3119 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:30:53.865  2992  3119 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:30:53.865  2992  3119 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:30:53.865  2992  3119 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:30:53.865  2992  3119 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:30:53.865  2992  3119 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:30:53.865  2992  3119 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:30:53.865  2992  3119 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:30:53.865  2992  3119 W bt-btif : ag scb idx 1 not allocated
07-28 12:30:53.865  2992  3119 W bt-btif : ag scb idx 2 not allocated
07-28 12:30:53.865  2992  3119 E bt-btif : BTA AG is already disabled, ignoring ...
07-28 12:30:53.865  2992  3060 D bt_userial: userial_close_reader Joined userial reader thread: 0
07-28 12:30:53.865  2992  3123 D bt_vendor: op for 9
07-28 12:30:53.865  2992  3123 D bt_hwcfg: hw_epilog_process
07-28 12:30:53.865  2992  3060 D bt_vendor: op for 4
07-28 12:30:53.865  2992  3060 I bt_userial_vendor: device fd = 65 close
,07-28 12:30:53.865   937  1152 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:30:53.865   937  1152 D SecContentProvider2: mCursor = null
,07-28 12:30:53.865  2992  3060 D bt_vendor: op for 0
07-28 12:30:53.865  2992  3060 D bt_upio : upio_set_bluetooth_power(on: 0)
07-28 12:30:53.865  2992  3060 D bt_upio : is_emulator_context : 0
07-28 12:30:53.865  2992  3060 D bt_upio : is_rfkill_disabled ? [0]
,07-28 12:30:53.875  2992  3060 D bt_vendor: cleanup
,07-28 12:30:53.875   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:30:53.875   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:30:53.875  2992  3119 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-28 12:30:53.875  2992  3060 I GKI_LINUX: GKI_exit_task 0 done
07-28 12:30:53.875  2992  3060 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,07-28 12:30:53.875  2992  3057 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-28 12:30:53.875  2992  3057 D BtConfig.SecureMode: isSecureModeOn:false
07-28 12:30:53.875  2992  3057 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
07-28 12:30:53.875  2992  3057 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-28 12:30:53.875  2992  3057 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-28 12:30:53.875  2992  3057 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
07-28 12:30:53.875   937  3040 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:30:53.875   337   337 I art     : Explicit concurrent mark sweep GC freed 8753(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 312us total 22.679ms
,07-28 12:30:53.875   937  3040 D ActivityManager: caller:android.app.ApplicationThreadProxy@159bd767, r.packageName :com.android.bluetooth
,07-28 12:30:53.875  2992  3057 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-28 12:30:53.875  2992  3057 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-28 12:30:53.875  2992  3057 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-28 12:30:53.875   937  1537 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:30:53.875   937  1537 D ActivityManager: caller:android.app.ApplicationThreadProxy@2fa64914, r.packageName :com.android.bluetooth
07-28 12:30:53.875  2992  2992 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:30:53.875  2992  2992 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 12:30:53.875  2992  3057 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-28 12:30:53.875  2992  3057 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-28 12:30:53.875  2992  2992 D BtGatt.GattService: stop()
07-28 12:30:53.875  2992  3057 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-28 12:30:53.875  2992  2992 D BtGatt.AdvertiseManager: advertise clients cleared
07-28 12:30:53.875   937  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:30:53.875   937  1471 D ActivityManager: caller:android.app.ApplicationThreadProxy@d8965bd, r.packageName :com.android.bluetooth
,07-28 12:30:53.875  2992  3057 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-28 12:30:53.875  2992  3057 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-28 12:30:53.875  2992  3057 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-28 12:30:53.875  2992  2992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29
07-28 12:30:53.875   937  1648 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:30:53.875   937  1648 D ActivityManager: caller:android.app.ApplicationThreadProxy@dae17b2, r.packageName :com.android.bluetooth
,07-28 12:30:53.885  2992  3057 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-28 12:30:53.885  2992  3057 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-28 12:30:53.885  2992  3057 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,07-28 12:30:53.885   937  1556 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:30:53.885   937  1556 D ActivityManager: caller:android.app.ApplicationThreadProxy@24048303, r.packageName :com.android.bluetooth
,07-28 12:30:53.885   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 270us total 9.764ms
07-28 12:30:53.885  2992  3057 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-28 12:30:53.885  2992  3057 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-28 12:30:53.885  2992  3057 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-28 12:30:53.885  2992  2992 D HeadsetService: Received stop request...Stopping profile...
07-28 12:30:53.885   937   954 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:30:53.885   937   954 D ActivityManager: caller:android.app.ApplicationThreadProxy@d28e280, r.packageName :com.android.bluetooth
,07-28 12:30:53.885  2992  3057 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-28 12:30:53.885  2992  3057 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:30:53.885  2992  2992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29
,07-28 12:30:53.885  2992  3057 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-28 12:30:53.885   937  1537 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:30:53.885   937  1537 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e6ba0b9, r.packageName :com.android.bluetooth
,07-28 12:30:53.885  1315  1315 D HeadsetProfile: Bluetooth service disconnected
,07-28 12:30:53.895   937   937 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,07-28 12:30:53.895  2992  3057 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-28 12:30:53.895  2992  3057 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-28 12:30:53.895  1285  1285 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-28 12:30:53.895  2992  2992 D A2dpService: Received stop request...Stopping profile...
07-28 12:30:53.895  2992  2992 V Avrcp   : doQuit
07-28 12:30:53.895  2992  3070 D A2dpStateMachine: Exit Disconnected: -1
,07-28 12:30:53.895  2992  2992 D Avrcp   : Unregistering previous receiver
,07-28 12:30:53.895   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 277us total 11.006ms
,07-28 12:30:53.895  1285  1285 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
07-28 12:30:53.895  2992  3057 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-28 12:30:53.895  1285  1285 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
07-28 12:30:53.895   937  1556 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:30:53.895   937  1556 D ActivityManager: caller:android.app.ApplicationThreadProxy@26e1fcfe, r.packageName :com.android.bluetooth
07-28 12:30:53.895  1285  1285 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=0 BSSID=F4.99.3E SSID=4E47373030
07-28 12:30:53.895  1285  1285 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-28 12:30:53.895  2992  3057 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:30:53.895  2992  3057 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:30:53.895  2992  3057 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:30:53.895  2992  3057 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:30:53.895  2992  3057 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:30:53.895  2992  2992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29
,07-28 12:30:53.905  2992  3057 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:30:53.905  2992  3057 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
07-28 12:30:53.905  2992  3057 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,07-28 12:30:53.905  2992  3057 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-28 12:30:53.905  2992  3057 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
07-28 12:30:53.905  2992  3057 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-28 12:30:53.905  2992  3057 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-28 12:30:53.905  2992  3057 D BluetoothAdapterState: Stopping profile services that were post enabled
07-28 12:30:53.905  2992  2992 E BluetoothAdapterService(54542121): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
07-28 12:30:53.905   937   937 D BluetoothA2dp: Proxy object disconnected
07-28 12:30:53.905   937   937 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,07-28 12:30:53.905  2992  2992 D HidService: Received stop request...Stopping profile...
07-28 12:30:53.905  2992  2992 D HidService: Stopping Bluetooth HidService
,07-28 12:30:53.905  2992  2992 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:30:53.905  1315  1315 D BluetoothA2dp: Proxy object disconnected
07-28 12:30:53.905  1315  1315 D A2dpProfile: Bluetooth service disconnected
07-28 12:30:53.905  2992  2992 W bt-btif : cleanup: HH disabling or disabled already, status = 0
07-28 12:30:53.905  2992  2992 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:30:53.905  2992  2992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29
,07-28 12:30:53.905  3158  3158 D BluetoothA2dp: Proxy object disconnected
,07-28 12:30:53.905  2992  2992 D HealthService: Received stop request...Stopping profile...
,07-28 12:30:53.905  2992  2992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29
,07-28 12:30:53.905  1315  1315 D BluetoothInputDevice: Proxy object disconnected
07-28 12:30:53.905  1315  1315 D HidProfile: Bluetooth service disconnected
,07-28 12:30:53.905  2992  2992 D PanService: Received stop request...Stopping profile...
,07-28 12:30:53.905  2992  2992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29
07-28 12:30:53.905   937   937 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-28 12:30:53.905  2992  2992 E BluetoothAdapterService(54542121): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
07-28 12:30:53.905  2992  2992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-28 12:30:53.905  2992  2992 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,07-28 12:30:53.915  1315  1315 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:30:53.915  1315  1315 D PanProfile: Bluetooth service disconnected
,07-28 12:30:53.915  7528  7528 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:53.915  2992  2992 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:30:53.915  2992  2992 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-28 12:30:53.915  7528  7528 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:53.915  2992  2992 D BluetoothMapService: Received stop request...Stopping profile...
07-28 12:30:53.915  2992  2992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29
,07-28 12:30:53.915  2992  2992 D SapService: Received stop request...Stopping profile...
,07-28 12:30:53.915  2992  2992 D SapService: Stopping Bluetooth SapService
07-28 12:30:53.915  2992  2992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29
,07-28 12:30:53.915  2992  2992 E BluetoothAdapterService(54542121): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,07-28 12:30:53.915  2992  2992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:30:53.915  2992  2992 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-28 12:30:53.915  2992  2992 D BluetoothA2dp: Proxy object disconnected
07-28 12:30:53.915  2992  2992 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,07-28 12:30:53.915  2992  3071 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-28 12:30:53.915  2992  2992 I GKI_LINUX: GKI_exit_task 2 done
07-28 12:30:53.915  2992  2992 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,07-28 12:30:53.915  2992  2992 V Avrcp   : cleanup
07-28 12:30:53.915  2992  2992 E BluetoothAdapterService(54542121): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-28 12:30:53.915  2992  2992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:30:53.915  2992  2992 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,07-28 12:30:53.925  2992  2992 E BluetoothAdapterService(54542121): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-28 12:30:53.925  2992  2992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:30:53.925  2992  2992 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,07-28 12:30:53.925  2992  2992 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 12:30:53.925  2992  2992 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:30:53.925  2992  2992 E BluetoothAdapterService(54542121): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
07-28 12:30:53.925  2992  2992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-28 12:30:53.925  2992  2992 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-28 12:30:53.925  2992  2992 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:30:53.925  2992  2992 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-28 12:30:53.925  2992  2992 E BluetoothAdapterService(54542121): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
07-28 12:30:53.925  2992  2992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,07-28 12:30:53.925  2992  2992 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
07-28 12:30:53.925  2992  2992 E BluetoothAdapterService(54542121): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,07-28 12:30:53.925  2992  3057 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
07-28 12:30:53.925  2992  3057 D BluetoothAdapterProperties: Setting state to 10
07-28 12:30:53.925  2992  3057 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-28 12:30:53.925  2992  3057 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:30:53.925  2992  3057 D BluetoothAdapterService: updateAdapterState state is 10
,07-28 12:30:53.925  2992  2992 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
07-28 12:30:53.925  2992  3057 D BluetoothAdapterService: Autoconnection is available 
,07-28 12:30:53.925  2992  3057 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
07-28 12:30:53.925  2992  3057 I BluetoothAdapterState: Entering OffState
07-28 12:30:53.925  1315  7510 D BluetoothPbap: onBluetoothStateChange: up=false
07-28 12:30:53.925  2992  2992 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,07-28 12:30:53.925  1315  1315 D BluetoothMap: Proxy object disconnected
,07-28 12:30:53.925  1315  1315 D MapProfile: Bluetooth service disconnected
07-28 12:30:53.925  1315  1315 D Bluetoothsap: BluetoothSAP Proxy object disconnected
07-28 12:30:53.925  1315  1315 D SapProfile: Bluetooth service disconnected
,07-28 12:30:53.935  1285  1285 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:30:53.935  2992  3006 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:30:53.935  1429  1429 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:30:53.935   937  1061 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:30:53.935  1315  1337 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-28 12:30:53.935  1429  1429 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:30:53.935  3158  3170 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:30:53.945  1315  7510 D Bluetoothsap: onBluetoothStateChange: up=false
,07-28 12:30:53.945  1315  7510 D Bluetoothsap: Unbinding service...
,07-28 12:30:53.945  1315  1337 D BluetoothMap: onBluetoothStateChange: up=false
,07-28 12:30:53.945  1315  1325 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:30:53.945   937  1061 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 12 receivers.
,07-28 12:30:53.945  1429  1429 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:30:53.945   937  1061 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,07-28 12:30:53.945  1429  1429 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:30:53.955  1194  1194 D BluetoothAdapter: 619609957: getState() :  mService = null. Returning STATE_OFF
07-28 12:30:53.955  1194  1194 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-28 12:30:53.955  1194  1194 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:30:53.955  1194  1194 D BluetoothAdapter: 619609957: getState() :  mService = null. Returning STATE_OFF
,07-28 12:30:53.955  1696  1696 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
07-28 12:30:53.955   937   937 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-28 12:30:53.955   937   937 I InputMethodManagerService: [BT Setting State] State =10
07-28 12:30:53.955   937   937 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-28 12:30:53.955  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:53.955  1194  1583 D BluetoothAdapter: 619609957: getState() :  mService = null. Returning STATE_OFF
07-28 12:30:53.955  1194  1583 D BluetoothAdapter: 619609957: getState() :  mService = null. Returning STATE_OFF
07-28 12:30:53.955  1194  1583 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-28 12:30:53.955  1429  1429 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-28 12:30:53.955  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:53.955  1823  2361 D BluetoothAdapter: 369937324: getState() :  mService = null. Returning STATE_OFF
07-28 12:30:53.955  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:30:53.955  1194  1194 D BluetoothAdapter: 619609957: getState() :  mService = null. Returning STATE_OFF
07-28 12:30:53.955  1823  2361 D BluetoothAdapter: 369937324: getState() :  mService = null. Returning STATE_OFF
07-28 12:30:53.955   937   952 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:30:53.955   937  1737 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-28 12:30:53.955  1429  1429 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-28 12:30:53.955  2992  3060 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,07-28 12:30:53.955  1194  1194 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
07-28 12:30:53.955  2992  2992 I GKI_LINUX: GKI_exit_task 1 done
07-28 12:30:53.955  2992  2992 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,07-28 12:30:53.955  2992  2992 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-28 12:30:53.955  1429  1429 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:30:53.955  7528  7528 D ResourcesManager: creating new AssetManager and set to /system/app/Maps/Maps.apk
,07-28 12:30:53.965  2992  2992 I art     : System.exit called, status: 0
07-28 12:30:53.965  2992  2992 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-28 12:30:53.965  1429  1429 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:30:53.965  1429  1429 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:30:53.965  1429  1429 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:30:53.975  1429  1429 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:30:53.985  1429  1429 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:30:53.985   937  1666 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:30:53.985   937  1666 D ActivityManager: caller:android.app.ApplicationThreadProxy@13c24c5f, r.packageName :com.google.android.gms
07-28 12:30:53.985  1429  1429 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:30:53.995  1429  1429 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:30:54.015   937  1556 I ActivityManager: Process com.android.bluetooth (pid 2992)(adj 0) has died(212,1560)
,07-28 12:30:54.085  1285  1285 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-28 12:30:54.085   937  1155 D Tethering: InitialState.processMessage what=4
,07-28 12:30:54.085   937  1155 E Tethering: No numeric data
07-28 12:30:54.085   937  1155 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-28 12:30:54.085  1194  1194 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,07-28 12:30:54.085   937  1149 V NetworkStats: performPollLocked(flags=0x1)
07-28 12:30:54.085   937  1149 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:30:54.085  1194  1194 D HotspotTile: updateTetherState():false, false
,07-28 12:30:54.085   937  1149 D NetworkStatsFactory: UpdateStatsForKnox
,07-28 12:30:54.085   937  1149 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:54.085  7429  7429 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-28 12:30:54.085   937  1149 V NetworkStats: performPollLocked() took 6ms
07-28 12:30:54.085   937  1149 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:30:54.095   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:30:54.095   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:30:54.165   937  1666 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,07-28 12:30:54.165  1823  1823 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-28 12:30:54.165  1823  1823 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-28 12:30:54.185   937  1152 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,07-28 12:30:54.185   937  1152 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-28 12:30:54.185   937   937 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:30:54.195  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:30:54.195  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-28 12:30:54.195  1194  1194 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:30:54.195  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:54.195   937  1156 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-28 12:30:54.195  1194  1194 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
07-28 12:30:54.195  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-28 12:30:54.195  1823  2361 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:30:54.195  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:30:54.195  1194  1194 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:30:54.195  1194  1583 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-28 12:30:54.195  1194  1194 D HotspotTile: onReceive : 1, 0
,07-28 12:30:54.205  7528  7528 D StrictMode: StrictMode policy violation; ~duration=181 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,07-28 12:30:54.205  7528  7528 D StrictMode: StrictMode policy violation; ~duration=171 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:30:54.205  7528  7528 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.io.File.exists(File.java:363)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1319)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-28 12:30:54.205  7528  7528 D StrictMod,e: 	at com.google.b.a.ca.a(PG:125)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:30:54.205  7528  7528 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at androi,d.os.Looper.loop(Looper.java:145)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:30:54.205  7528  7528 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:30:54.205  7528  7528 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.r.e.b(PG:170)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:30:54.205  7528  7528 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.r.k.b(PG:14147)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.r.k.c(PG:583)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.r.e.b(PG:170)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:30:54.205  7528  7528 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.io.File.exists(File.java:363)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1485)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:30:54.205  7528  7528 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:30:54.215   937   954 I ActivityManager: Killing 6681:com.sec.pcw.device/1000 (adj 15): emptyCount ##41
07-28 12:30:54.215  1823  1823 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-28 12:30:54.215  1823  1823 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-28 12:30:54.215   937  1648 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
07-28 12:30:54.215   937  1648 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:54.215   937  1648 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:54.215   937  1648 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:54.215   937  1648 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:54.255  7571  7571 E Zygote  : MountEmulatedStorage()
07-28 12:30:54.255  7571  7571 E Zygote  : v2
07-28 12:30:54.255  7571  7571 I libpersona: KNOX_SDCARD checking this for 10038
07-28 12:30:54.255  7571  7571 I libpersona: KNOX_SDCARD not a persona
07-28 12:30:54.265   937  1648 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7571 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
07-28 12:30:54.265  7528  7568 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
07-28 12:30:54.285  7571  7571 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:54.285  7571  7571 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:30:54.285  7571  7571 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-28 12:30:54.305   937  1154 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:30:54.305   937   937 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:30:54.305   937  1014 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:30:54.305   937  1014 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:54.305   937   937 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:54.305   937   937 I ApplicationPolicy: updateDataUsageMap
,07-28 12:30:54.305   937  1156 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-28 12:30:54.305   937  1156 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:30:54.305   937  1156 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:30:54.305   937  1156 D SmartBondingService: getSBEnabled() enabled =false
,07-28 12:30:54.315  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:54.315  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:54.315   937  1156 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-28 12:30:54.315   937  1737 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:54.315  1587  1587 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-28 12:30:54.315  7571  7571 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:54.325  7571  7571 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:54.325   937  1147 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:54.335  7571  7571 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,07-28 12:30:54.335  7571  7571 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,07-28 12:30:54.355  1823  2266 I art     : Explicit concurrent mark sweep GC freed 107758(5MB) AllocSpace objects, 42(1461KB) LOS objects, 40% free, 23MB/39MB, paused 748us total 55.250ms
,07-28 12:30:54.395   937  1152 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,07-28 12:30:54.465   937  1666 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-28 12:30:54.465   937  1666 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4303, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-28 12:30:54.465   937  1666 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-28 12:30:54.465   937   937 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-28 12:30:54.465   937  1666 D BatteryService: stay LED for fully charged
,07-28 12:30:54.465  1194  1194 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-28 12:30:54.465  1194  1194 D KeyguardUpdateMonitor: handleBatteryUpdate
07-28 12:30:54.465  1194  1194 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-28 12:30:54.465  1194  1194 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:30:54.465   937   937 I MotionRecognitionService: Plugged
07-28 12:30:54.465   937   937 I MotionRecognitionService: setPowerConnected  = true
,07-28 12:30:54.465  1194  1194 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:30:54.465  1194  1194 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:30:54.465  7571  7571 I VlingoApplication: VlingoApplication appVersion ='11.2.2.0.37791', ro.csc.sales_code=XEO
,07-28 12:30:54.535  7571  7571 D BluetoothAdapter: 962513891: getState() :  mService = null. Returning STATE_OFF
,07-28 12:30:54.535  7571  7571 D BluetoothAdapter: 962513891: getState() :  mService = null. Returning STATE_OFF
,07-28 12:30:54.535  7571  7571 D BluetoothAdapter: 962513891: getState() :  mService = null. Returning STATE_OFF
,07-28 12:30:54.535  7571  7571 D BluetoothAdapter: 962513891: getState() :  mService = null. Returning STATE_OFF
07-28 12:30:54.535  7571  7571 D BluetoothAdapter: 962513891: getState() :  mService = null. Returning STATE_OFF
07-28 12:30:54.535  7571  7571 D BluetoothAdapter: 962513891: getState() :  mService = null. Returning STATE_OFF
,07-28 12:30:54.565  7571  7571 E BluetoothHeadset: BTStateChangeCB is registed
,07-28 12:30:54.565   937   952 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:30:54.565  7571  7571 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:30:54.575   937  1472 I ActivityManager: Killing 4793:com.sec.spp.push/u0a43 (adj 15): emptyCount ##41
,07-28 12:30:54.575  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-28 12:30:54.575  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-28 12:30:54.575   937  1253 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:54.575  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:30:54.575   937  1364 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:30:54.575  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:30:54.575  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:30:54.575  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:30:54.575  1315  2678 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:30:54.585   937   954 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:54.585  7038  7038 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:30:54.585   937  1556 D SettingsProvider: name = driving_mode_on
07-28 12:30:54.585   937  1556 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:30:54.585   937  1556 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:30:54.585   937  1556 D SettingsProvider: selectionArgs: false
07-28 12:30:54.585   937  1556 D SettingsProvider: selectionArgs: 10038
07-28 12:30:54.585   937  1556 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:30:54.585   937  1556 D SettingsProvider: ret = -1
,07-28 12:30:54.595  7571  7571 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,07-28 12:30:54.595  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:30:54.595  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-28 12:30:54.605   937  1472 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:54.605  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:30:54.605   937  1537 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-28 12:30:54.605  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:30:54.605  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:30:54.605  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:30:54.605  1315  2678 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:30:54.605  7165  7165 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-28 12:30:54.605   937  1471 D ActivityManager: startProcessLocked calleePkgName: com.samsung.shareshot, hostingType: broadcast
,07-28 12:30:54.605   937  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:54.615   937  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:54.615   937  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:54.615   937  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:54.695  7596  7596 E Zygote  : MountEmulatedStorage()
07-28 12:30:54.695  7596  7596 E Zygote  : v2
07-28 12:30:54.695  7596  7596 I libpersona: KNOX_SDCARD checking this for 10192
07-28 12:30:54.695  7596  7596 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:54.695   937  1471 I ActivityManager: Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=7596 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:30:54.705  7596  7596 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:54.705  7596  7596 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:30:54.705  7596  7596 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:30:54.725  7596  7596 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:54.725  7596  7596 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:54.735  7596  7596 D ResourcesManager: creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,07-28 12:30:54.745  7596  7596 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:30:54.755  7596  7596 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,07-28 12:30:54.755  7596  7596 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-28 12:30:54.755  7596  7596 D WifiDirectBR: stopServiceTest : false
,07-28 12:30:54.755  7596  7596 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-28 12:30:54.755   937  1556 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,07-28 12:30:54.755   937  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:54.755   937  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:54.755   937  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:54.755   937  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:54.795  7611  7611 E Zygote  : MountEmulatedStorage()
,07-28 12:30:54.795  7611  7611 E Zygote  : v2
07-28 12:30:54.795  7611  7611 I libpersona: KNOX_SDCARD checking this for 10131
07-28 12:30:54.795  7611  7611 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:54.805  7611  7611 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:54.805  7611  7611 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:30:54.805  7611  7611 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-28 12:30:54.805   937  1556 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7611 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
07-28 12:30:54.805   937  1556 I ActivityManager: Killing 6741:com.samsung.android.scloud.sync/u0a76 (adj 15): emptyCount ##41
,07-28 12:30:54.825  7611  7611 D TimaKeyStoreProvider: TimaSignature is unavailable
07-28 12:30:54.825  7611  7611 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:54.835  7611  7611 D ResourcesManager: creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,07-28 12:30:54.845  7611  7611 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-28 12:30:55.005  7611  7637 I Babel   : MmsConfig: mnc/mcc: 0/0
07-28 12:30:55.005  7611  7637 I Babel   : MmsConfig.loadMmsSettings
,07-28 12:30:55.005  7611  7637 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
07-28 12:30:55.005  7611  7637 I Babel   : MmsConfig.loadFromDatabase
,07-28 12:30:55.005  7611  7611 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-28 12:30:55.015  7611  7637 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-28 12:30:55.015  7611  7637 I Babel   : MmsConfig.loadFromResources
,07-28 12:30:55.015  7611  7637 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,07-28 12:30:55.015  7611  7637 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,07-28 12:30:55.025   937  3040 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,07-28 12:30:55.025  7611  7611 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:30:55.045  7611  7611 I Babel_StickerModule: App launched.
,07-28 12:30:55.055  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-28 12:30:55.055  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-28 12:30:55.065   937  3040 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:55.065  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-28 12:30:55.065   937  1147 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-28 12:30:55.065  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:30:55.065  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:30:55.065  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-28 12:30:55.065  1315  2678 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:30:55.065   311  4893 W QCamera2Factory: getCameraInfo: E, camera_id = 0
07-28 12:30:55.065   311  4893 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-28 12:30:55.065   311  4893 W QCamera2Factory: getCameraInfo: X
,07-28 12:30:55.065   937   954 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:55.065   311  2744 W QCamera2Factory: getCameraInfo: E, camera_id = 1
07-28 12:30:55.065   311  2744 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-28 12:30:55.065   311  2744 W QCamera2HWI: __dbg: info->orientation : 270 rc = 0
07-28 12:30:55.065   311  2744 W QCamera2Factory: getCameraInfo: X
,07-28 12:30:55.065  7038  7038 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:30:55.085  7611  7611 W AudioCapabilities: Unsupported mime audio/evrc
,07-28 12:30:55.085  7038  7038 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:30:55.085  7611  7611 W AudioCapabilities: Unsupported mime audio/qcelp
,07-28 12:30:55.085  7611  7611 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-28 12:30:55.085   937  3040 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:55.085  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:30:55.085  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:30:55.085  6889  6889 D SecurityLogAgent: StateMachine : Current State = 1
,07-28 12:30:55.095  6889  6889 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:30:55.095  7611  7611 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,07-28 12:30:55.095  7611  7611 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,07-28 12:30:55.095  7611  7611 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-28 12:30:55.095  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-28 12:30:55.095   937  1364 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-28 12:30:55.095   937  1364 D ActivityManager: caller:android.app.ApplicationThreadProxy@e0626d3, r.packageName :com.android.settings
07-28 12:30:55.095  7611  7611 W AudioCapabilities: Unsupported mime audio/x-ima
,07-28 12:30:55.105  7611  7611 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,07-28 12:30:55.105  7611  7611 W AudioCapabilities: Unsupported mime audio/qcelp
,07-28 12:30:55.105  7611  7611 W AudioCapabilities: Unsupported mime audio/evrc
,07-28 12:30:55.105  1315  1315 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:30:55.105  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
07-28 12:30:55.105   937  1253 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,07-28 12:30:55.115   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:55.115   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:55.115   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:55.115   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:55.115  7611  7611 W VideoCapabilities: Unsupported mime video/wvc1
,07-28 12:30:55.115  7611  7611 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-28 12:30:55.125  7611  7611 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,07-28 12:30:55.125  7611  7611 W VideoCapabilities: Unsupported mime video/wvc1
,07-28 12:30:55.125  7611  7611 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-28 12:30:55.125  7611  7611 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,07-28 12:30:55.125  7611  7611 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,07-28 12:30:55.125  7611  7611 W VideoCapabilities: Unsupported mime video/mp43
,07-28 12:30:55.125  7611  7611 W VideoCapabilities: Unsupported mime video/sorenson
,07-28 12:30:55.135  7611  7611 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-28 12:30:55.145  7611  7611 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-28 12:30:55.145   937  1253 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7642 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
07-28 12:30:55.155  7642  7642 E Zygote  : MountEmulatedStorage()
07-28 12:30:55.155  7642  7642 E Zygote  : v2
07-28 12:30:55.155  7642  7642 I libpersona: KNOX_SDCARD checking this for 1002
07-28 12:30:55.155  7642  7642 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:55.185  7642  7642 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:55.185  7642  7642 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:30:55.185  7642  7642 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:30:55.205  7642  7642 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:55.205  7642  7642 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:55.215  7642  7642 D ResourcesManager: creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,07-28 12:30:55.225  7642  7642 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-28 12:30:55.225  7642  7642 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-28 12:30:55.225   937  1666 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,07-28 12:30:55.235   937   952 I ActivityManager: Killing 6758:com.sec.android.provider.badge/u0a92 (adj 15): emptyCount ##41
,07-28 12:30:55.245  7642  7642 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-28 12:30:55.275  7642  7642 D BtSettings.ProfileConfig: Adding GattService
,07-28 12:30:55.275  7642  7642 D BtSettings.ProfileConfig: Adding HeadsetService
07-28 12:30:55.275  7642  7642 D BtSettings.ProfileConfig: Adding A2dpService
,07-28 12:30:55.275  7642  7642 D BtSettings.ProfileConfig: Adding HidService
07-28 12:30:55.275  7642  7642 D BtSettings.ProfileConfig: Adding HealthService
,07-28 12:30:55.275  7642  7642 D BtSettings.ProfileConfig: Adding PanService
07-28 12:30:55.275  7642  7642 D BtSettings.ProfileConfig: Adding BluetoothMapService
07-28 12:30:55.275  7642  7642 D BtSettings.ProfileConfig: Adding SapService
,07-28 12:30:55.275  7642  7642 D BtSettings.ProfileConfig: Adding HeadsetClientService
07-28 12:30:55.275  7642  7642 D BtSettings.ProfileConfig: Adding A2dpSinkService
07-28 12:30:55.275  7642  7642 D BtSettings.ProfileConfig: Adding SapClientService
,07-28 12:30:55.275  7642  7642 D BtSettings.ProfileConfig: Adding HidDevService
07-28 12:30:55.275  7642  7642 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-28 12:30:55.275   937  1434 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,07-28 12:30:55.275   937  1434 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:30:55.285   937  1434 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:30:55.285   937  1434 D SettingsProvider: selectionArgs: false
07-28 12:30:55.285   937  1434 D SettingsProvider: selectionArgs: 1002
07-28 12:30:55.285   937  1434 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:30:55.285   937  1434 D SettingsProvider: ret = -1
,07-28 12:30:55.285   937  1471 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-28 12:30:55.285   937  1471 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:30:55.285   937  1471 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,07-28 12:30:55.285   937  1471 D SettingsProvider: selectionArgs: false
07-28 12:30:55.285   937  1471 D SettingsProvider: selectionArgs: 1002
07-28 12:30:55.285   937  1471 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:30:55.285   937  1471 D SettingsProvider: ret = -1
,07-28 12:30:55.285   937   954 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
07-28 12:30:55.285   937   954 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:30:55.285   937   954 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:30:55.285   937   954 D SettingsProvider: selectionArgs: false
07-28 12:30:55.285   937   954 D SettingsProvider: selectionArgs: 1002
07-28 12:30:55.285   937   954 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-28 12:30:55.285   937   954 D SettingsProvider: ret = -1
07-28 12:30:55.285   937  1472 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
07-28 12:30:55.285   937  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:30:55.285   937  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:30:55.285   937  1472 D SettingsProvider: selectionArgs: false
07-28 12:30:55.285   937  1472 D SettingsProvider: selectionArgs: 1002
07-28 12:30:55.285   937  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:30:55.285   937  1472 D SettingsProvider: ret = -1
,07-28 12:30:55.285   937  1666 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
07-28 12:30:55.285   937  1666 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:30:55.285   937  1666 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:30:55.285   937  1666 D SettingsProvider: selectionArgs: false
07-28 12:30:55.285   937  1666 D SettingsProvider: selectionArgs: 1002
07-28 12:30:55.285   937  1666 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:30:55.285   937  1666 D SettingsProvider: ret = -1
,07-28 12:30:55.295   937  1253 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
07-28 12:30:55.295   937  1253 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:30:55.295   937  1253 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:30:55.295   937  1253 D SettingsProvider: selectionArgs: false
07-28 12:30:55.295   937  1253 D SettingsProvider: selectionArgs: 1002
07-28 12:30:55.295   937  1253 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:30:55.295   937  1253 D SettingsProvider: ret = -1
07-28 12:30:55.295   937  1537 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
07-28 12:30:55.295   937  1537 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:30:55.295   937  1537 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:30:55.295   937  1537 D SettingsProvider: selectionArgs: false
07-28 12:30:55.295   937  1537 D SettingsProvider: selectionArgs: 1002
07-28 12:30:55.295   937  1537 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:30:55.295   937  1537 D SettingsProvider: ret = -1
,07-28 12:30:55.295   937  1648 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
07-28 12:30:55.295   937  1648 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:30:55.295   937  1648 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:30:55.295   937  1648 D SettingsProvider: selectionArgs: false
07-28 12:30:55.295   937  1648 D SettingsProvider: selectionArgs: 1002
07-28 12:30:55.295   937  1648 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:30:55.295   937  1648 D SettingsProvider: ret = -1
07-28 12:30:55.295   937  3040 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:30:55.295   937  3040 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:30:55.295   937  3040 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:30:55.295   937  3040 D SettingsProvider: selectionArgs: false
07-28 12:30:55.295   937  3040 D SettingsProvider: selectionArgs: 1002
07-28 12:30:55.295   937  3040 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:30:55.295   937  3040 D SettingsProvider: ret = -1
,07-28 12:30:55.295   937   952 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:30:55.295   937   952 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:30:55.295   937   952 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:30:55.295   937   952 D SettingsProvider: selectionArgs: false
07-28 12:30:55.295   937   952 D SettingsProvider: selectionArgs: 1002
07-28 12:30:55.295   937   952 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:30:55.295   937   952 D SettingsProvider: ret = -1
07-28 12:30:55.295   937  1147 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
07-28 12:30:55.295   937  1147 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:30:55.295   937  1147 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:30:55.295   937  1147 D SettingsProvider: selectionArgs: false
07-28 12:30:55.295   937  1147 D SettingsProvider: selectionArgs: 1002
07-28 12:30:55.295   937  1147 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:30:55.295   937  1147 D SettingsProvider: ret = -1
,07-28 12:30:55.295   937  1556 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
07-28 12:30:55.295   937  1556 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:30:55.295   937  1556 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:30:55.295   937  1556 D SettingsProvider: selectionArgs: false
07-28 12:30:55.295   937  1556 D SettingsProvider: selectionArgs: 1002
07-28 12:30:55.295   937  1556 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:30:55.295   937  1556 D SettingsProvider: ret = -1
07-28 12:30:55.305   937  1242 I ActivityManager: Killing 6778:com.sec.android.app.clockpackage/u0a106 (adj 15): emptyCount ##41
07-28 12:30:55.305  1823  1823 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-28 12:30:55.305   937  1471 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:30:55.305   937  1471 D ActivityManager: caller:android.app.ApplicationThreadProxy@25025d2f, r.packageName :com.google.android.gms
07-28 12:30:55.315  1823  7663 D EasyUnlockInitService: Handling intent for initializer IntentService.
07-28 12:30:55.315  1823  1823 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:30:55.325  7038  7038 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
07-28 12:30:55.335   937  1479 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:55.335  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:30:55.335  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:30:55.335  6889  6889 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:30:55.335  6889  6889 D SecurityLogAgent: StateMachine : Changed Current State = 1
07-28 12:30:55.345   937  1472 D ActivityManager: caller:android.app.ApplicationThreadProxy@8ff0328, r.packageName :com.google.android.gms
07-28 12:30:55.345   937  1253 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
07-28 12:30:55.345   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:55.345   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:55.345   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:55.345   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:55.345  1823  7663 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-28 12:30:55.425  7665  7665 E Zygote  : MountEmulatedStorage()
07-28 12:30:55.425  7665  7665 E Zygote  : v2
07-28 12:30:55.425  7665  7665 I libpersona: KNOX_SDCARD checking this for 1000
07-28 12:30:55.425  7665  7665 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:55.435   937  1253 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7665 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-28 12:30:55.445  7665  7665 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:55.445  7665  7665 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:30:55.445  7665  7665 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:30:55.465  7665  7665 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:55.465  7665  7665 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:55.475  7665  7665 D ResourcesManager: creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,07-28 12:30:55.485  7665  7665 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
07-28 12:30:55.485  7665  7665 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
07-28 12:30:55.485  7665  7665 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,07-28 12:30:55.495  7665  7665 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,07-28 12:30:55.495  7665  7665 I PCWCLIENTTRACE_PushUtil: sales region : global
07-28 12:30:55.495  7665  7665 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-28 12:30:55.495  7665  7665 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:30:55.495  7665  7665 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,07-28 12:30:55.505   937  1253 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,07-28 12:30:55.505   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:55.505   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:55.505   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:55.505   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:55.545  7681  7681 E Zygote  : MountEmulatedStorage()
,07-28 12:30:55.545  7681  7681 E Zygote  : v2
07-28 12:30:55.545  7681  7681 I libpersona: KNOX_SDCARD checking this for 10144
07-28 12:30:55.545  7681  7681 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:55.555  7681  7681 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:55.555  7681  7681 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:30:55.555  7681  7681 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-28 12:30:55.555   937  1253 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7681 uid=10144 gids={50144, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:30:55.565  7681  7681 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:55.575  7681  7681 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:55.585  7681  7681 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-28 12:30:55.675  7681  7681 I MusicStore: Database version: 108
,07-28 12:30:55.685   937  1253 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:30:55.735  7681  7681 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,07-28 12:30:55.735  7681  7681 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-28 12:30:55.735  7681  7681 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-28 12:30:55.765  7681  7681 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-28 12:30:55.805  7681  7681 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-28 12:30:55.805  7681  7681 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@28011eed: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-28 12:30:55.805  7681  7681 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-28 12:30:55.805  7681  7681 D AndroidMusic: GMSCore installation verified
,07-28 12:30:55.815   937  1479 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:30:55.825  7681  7681 I ConfigStore: Config Database version: 1
,07-28 12:30:55.865   266   556 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-28 12:30:55.865  7681  7681 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
07-28 12:30:55.865   266   556 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:30:55.865   266   556 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-28 12:30:55.865   266   556 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:30:55.875  7681  7681 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-28 12:30:55.875   266   556 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-28 12:30:55.875   266   556 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:30:55.875  7681  7681 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-28 12:30:55.875   937  1666 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-28 12:30:55.885   937  1666 D ActivityManager: caller:android.app.ApplicationThreadProxy@23386f3b, r.packageName :com.google.android.music
,07-28 12:30:55.895   937   952 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:30:55.915   937  1253 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-28 12:30:55.915   937  1479 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-28 12:30:55.925   937  1472 I AudioService: getStreamVolume 3 index 0
,07-28 12:30:55.925  7681  7681 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-28 12:30:55.935  7681  7681 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-28 12:30:55.955   937  1479 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:30:55.955   937  1147 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:30:55.955   937  1472 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:30:55.965   937   954 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-28 12:30:55.965   937  1666 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,07-28 12:30:55.965   937  1666 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:55.965   937  1666 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:55.965   937  1666 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:55.965   937  1666 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:56.005   303   303 E SMD     : DCD ON
07-28 12:30:56.005   937  1666 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7714 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:30:56.015  7714  7714 E Zygote  : MountEmulatedStorage()
,07-28 12:30:56.015  7714  7714 E Zygote  : v2
07-28 12:30:56.015  7714  7714 I libpersona: KNOX_SDCARD checking this for 10004
07-28 12:30:56.015  7714  7714 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:56.035  7714  7714 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:56.035  7714  7714 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:30:56.035  7714  7714 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:30:56.055   937  1737 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,07-28 12:30:56.055  7681  7681 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,07-28 12:30:56.055   937  1472 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:30:56.065  7714  7714 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:56.065  7714  7714 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:56.075  7714  7714 D ResourcesManager: creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,07-28 12:30:56.095   937  1147 I ActivityManager: Killing 6716:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): emptyCount ##41
,07-28 12:30:56.115   937   954 I ActivityManager: Killing 6795:com.wsomacp/u0a29 (adj 15): emptyCount ##41
,07-28 12:30:56.115   937  1253 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,07-28 12:30:56.115   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:56.115   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:56.115   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:56.115   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:56.155  7737  7737 E Zygote  : MountEmulatedStorage()
,07-28 12:30:56.155  7737  7737 E Zygote  : v2
07-28 12:30:56.155  7737  7737 I libpersona: KNOX_SDCARD checking this for 1000
07-28 12:30:56.155  7737  7737 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:56.165   937  1253 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7737 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-28 12:30:56.175  7737  7737 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:56.175  7737  7737 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:30:56.175  7737  7737 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:30:56.195  7737  7737 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:56.195  7737  7737 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:56.205  7737  7737 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,07-28 12:30:56.235  7737  7737 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,07-28 12:30:56.245  7737  7737 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,07-28 12:30:56.355  7737  7737 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,07-28 12:30:56.355  7737  7737 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,07-28 12:30:56.365  7737  7737 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:30:56.365  7737  7737 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-28 12:30:56.415   937  1434 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,07-28 12:30:56.415   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:56.415   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:56.415   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:56.425   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:56.465  7757  7757 E Zygote  : MountEmulatedStorage()
,07-28 12:30:56.465  7757  7757 E Zygote  : v2
07-28 12:30:56.465  7757  7757 I libpersona: KNOX_SDCARD checking this for 10014
07-28 12:30:56.465  7757  7757 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:56.465   937  1434 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7757 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:30:56.475  7757  7757 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:56.475  7757  7757 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:30:56.475  7757  7757 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-28 12:30:56.495  7757  7757 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:56.495  7757  7757 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:56.505  7757  7757 D ResourcesManager: creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,07-28 12:30:56.555   937  1666 I ActivityManager: Killing 6662:com.osp.app.signin/u0a50 (adj 15): emptyCount ##41
,07-28 12:30:56.555  7757  7757 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-28 12:30:56.555  7757  7757 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-28 12:30:56.575  7757  7757 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-28 12:30:56.585   937  1434 I ActivityManager: Killing 6700:com.android.mms/u0a55 (adj 15): emptyCount ##41
,07-28 12:30:56.585  3927  3927 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-28 12:30:56.585  3927  3927 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1469701856595
,07-28 12:30:56.585  3927  3927 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,07-28 12:30:56.585   937   954 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:56.585   937  1737 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:56.585  3927  3927 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,07-28 12:30:56.595  3927  3927 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
07-28 12:30:56.595   937  1147 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.pinboard, hostingType: broadcast
,07-28 12:30:56.595   937  1147 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:56.595   937  1147 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:56.595   937  1147 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:56.595   937  1147 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:56.655   937  1471 D CountryDetector: No listener is left
,07-28 12:30:56.685  7774  7774 E Zygote  : MountEmulatedStorage()
,07-28 12:30:56.685  7774  7774 E Zygote  : v2
07-28 12:30:56.685  7774  7774 I libpersona: KNOX_SDCARD checking this for 10036
07-28 12:30:56.685  7774  7774 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:56.685   937  1147 I ActivityManager: Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7774 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-28 12:30:56.705  7774  7774 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:56.705  7774  7774 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:30:56.705  7774  7774 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:30:56.725  7774  7774 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:56.725  7429  7490 I WifiManager: packageName : com.test.thalitest
,07-28 12:30:56.725   937  1253 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-28 12:30:56.725   937  1253 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:30:56.725   937  1253 D SecContentProvider2: mCursor = null
,07-28 12:30:56.725   937  1253 D WifiService: setWifiEnabled: true pid=7429, uid=10079
07-28 12:30:56.725   937  1253 W ActivityManager: Permission Denial: getCurrentUser() from pid=7429, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:30:56.735   937  1253 W WifiService: Failed getting userId using ActivityManagerNative
07-28 12:30:56.735   937  1253 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7429, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:30:56.735   937  1253 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-28 12:30:56.735   937  1253 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-28 12:30:56.735   937  1253 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-28 12:30:56.735   937  1253 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-28 12:30:56.735   937  1253 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-28 12:30:56.735   937  1253 D SettingsProvider: name = wifi_on
,07-28 12:30:56.735  7774  7774 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:56.735   937  1152 E WifiHW  : ##################### set firmware type 0 #####################
,07-28 12:30:56.735   298  1058 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
07-28 12:30:56.735   298  1058 I WifiHW  : module is semco
07-28 12:30:56.735   298  1058 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-28 12:30:56.735   298  1058 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-28 12:30:56.735   298  1058 E WifiHW  : TEMP_FAILURE_RETRY complete
07-28 12:30:56.735   298  1058 D SoftapController: Softap fwReload - Ok
,07-28 12:30:56.745   298  1058 D CommandListener: Setting iface cfg
07-28 12:30:56.745   298  1058 D CommandListener: Trying to bring down wlan0
,07-28 12:30:56.745   298  1058 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:30:56.745   937  1152 E WifiHW  : supplicant_name : p2p_supplicant
,07-28 12:30:56.745   937   937 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:30:56.755  7774  7774 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-28 12:30:56.755  7774  7774 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-28 12:30:56.755  7774  7774 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-28 12:30:56.765  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:30:56.765  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-28 12:30:56.765  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:30:56.775  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:56.775  1194  1194 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:30:56.775   937  1152 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-28 12:30:56.775  1194  1194 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
07-28 12:30:56.775  1194  1194 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:30:56.775  1194  1583 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-28 12:30:56.775  1194  1194 D HotspotTile: onReceive : 2, 0
,07-28 12:30:56.775   937  1156 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-28 12:30:56.775  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:30:56.785  7790  7790 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-28 12:30:56.785  7790  7790 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-28 12:30:56.785  7790  7790 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:30:56.785  7790  7790 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-28 12:30:56.785   361   361 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7790
07-28 12:30:56.785   361   361 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-28 12:30:56.785  7790  7790 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:30:56.785  7790  7790 I wpa_supplicant: ssSupport state is = 1
,07-28 12:30:56.785  7790  7790 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,07-28 12:30:56.785  7790  7790 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-28 12:30:56.785   361   361 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7790
07-28 12:30:56.785   361   361 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,07-28 12:30:56.795  7774  7774 E Minikin : addFont failed to create font /system/fonts/SamsungSans-light.ttf
,07-28 12:30:56.805   937   952 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:56.805   937  1242 I ActivityManager: Killing 6817:com.sec.android.app.soundalive/u0a64 (adj 15): emptyCount ##41
,07-28 12:30:56.815   937  1479 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,07-28 12:30:56.815   937  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:56.815   937  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:56.815   937  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:56.815   937  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:56.855  7800  7800 E Zygote  : MountEmulatedStorage()
07-28 12:30:56.855  7800  7800 E Zygote  : v2
07-28 12:30:56.855  7800  7800 I libpersona: KNOX_SDCARD checking this for 10042
07-28 12:30:56.855  7800  7800 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:56.865   937  1479 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7800 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,07-28 12:30:56.885   337   337 I art     : Explicit concurrent mark sweep GC freed 8754(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 306us total 13.125ms
,07-28 12:30:56.885  7800  7800 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:56.885  7800  7800 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:30:56.885  7800  7800 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:30:56.895   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 282us total 9.903ms
,07-28 12:30:56.905  7800  7800 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:56.905  7800  7800 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:56.905   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 384us total 9.949ms
,07-28 12:30:56.915  7800  7800 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,07-28 12:30:56.935  7800  7800 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,07-28 12:30:56.935   937  1471 I ActivityManager: Killing 6830:com.sec.esdk.elm/u0a116 (adj 15): emptyCount ##41
,07-28 12:30:56.945   937  1666 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,07-28 12:30:56.945   937  1666 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:56.945   937  1666 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:56.945   937  1666 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:56.945   937  1666 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:56.945   937  3040 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:56.945  3518  7815 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,07-28 12:30:56.945   937  1472 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:56.945  3518  7815 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,07-28 12:30:56.945  3518  7815 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
07-28 12:30:56.945  3518  7815 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,07-28 12:30:56.945  3518  7815 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,07-28 12:30:56.985  7816  7816 E Zygote  : MountEmulatedStorage()
07-28 12:30:56.985  7816  7816 E Zygote  : v2
07-28 12:30:56.985  7816  7816 I libpersona: KNOX_SDCARD checking this for 10043
07-28 12:30:56.985  7816  7816 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:56.995   937  1666 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7816 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:30:57.035  7816  7816 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:57.035  7816  7816 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:30:57.035  7816  7816 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,07-28 12:30:57.055  7816  7816 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:57.055  7816  7816 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:57.065  7816  7816 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,07-28 12:30:57.075   361   361 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,07-28 12:30:57.095  7816  7816 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,07-28 12:30:57.095  7816  7816 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,07-28 12:30:57.095  7816  7816 D SPPClientService: PushLog.txt file is not deleted.
,07-28 12:30:57.095  7816  7816 D SPPClientService: PushLog.txt file is not deleted.
07-28 12:30:57.095  7816  7816 D SPPClientService: ============PushLog. stop!
,07-28 12:30:57.105  7816  7816 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,07-28 12:30:57.105   937  1537 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,07-28 12:30:57.105   937  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:57.105   937  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:57.105   937  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:57.105   937  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:57.145  7832  7832 E Zygote  : MountEmulatedStorage()
07-28 12:30:57.145  7832  7832 E Zygote  : v2
07-28 12:30:57.145  7832  7832 I libpersona: KNOX_SDCARD checking this for 10050
07-28 12:30:57.145  7832  7832 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:57.155  7832  7832 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:57.155  7832  7832 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:30:57.155  7832  7832 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-28 12:30:57.155   937  1537 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7832 uid=10050 gids={50050, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:30:57.155   937  1537 I ActivityManager: Killing 6856:com.samsung.android.app.assistantmenu/1000 (adj 15): emptyCount ##41
,07-28 12:30:57.155   937  1556 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,07-28 12:30:57.155   937  1556 D ActivityManager: caller:android.app.ApplicationThreadProxy@11e6271b, r.packageName :com.sec.spp.push
,07-28 12:30:57.175  7832  7832 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:57.175  7832  7832 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:57.175  7816  7839 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,07-28 12:30:57.195  7832  7832 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,07-28 12:30:57.225  7832  7832 I SA      : [SSP] onCreated
,07-28 12:30:57.235  7832  7832 I SA      : [TPM] There is no property file
,07-28 12:30:57.245  7832  7832 I SA      : [SCU] isHaveSA() - false
,07-28 12:30:57.245  7832  7832 I SA      : [TPM] getModelProperty : null
,07-28 12:30:57.245  7832  7832 I SA      : [TPM] getCSCProperty : null
,07-28 12:30:57.245  7832  7832 I SA      : [DM] init START
,07-28 12:30:57.245  7832  7832 I SA      : [DM] This device is not a Vodafone
,07-28 12:30:57.255  7832  7832 I SA      : checkReactivationActive for LOLLIPOP
,07-28 12:30:57.255  7832  7832 I SA      : checkReactivationActive for reactiveActive
07-28 12:30:57.255  7832  7832 I SA      : setSupportRL : true
,07-28 12:30:57.255  7832  7832 I SA      : [SCU] isHaveSA() - false
,07-28 12:30:57.255  7832  7832 I SA      : support phone number id : false
,07-28 12:30:57.255  7832  7832 I SA      : [DM] init END
,07-28 12:30:57.255  7832  7832 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,07-28 12:30:57.265  7832  7832 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,07-28 12:30:57.265  7832  7832 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-28 12:30:57.265  7832  7832 I SA      : [SLFUCHKMGR] constructor called
,07-28 12:30:57.275  7832  7832 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,07-28 12:30:57.275  7832  7832 I SA      : [OR] == isSIMCardReady false ==
,07-28 12:30:57.275  7832  7832 I SA      : [SCU] == networkStateCheck == false
07-28 12:30:57.275  7832  7832 I SA      : [OR] onReceive END
,07-28 12:30:57.275   937  1737 I ActivityManager: Killing 6923:com.qualcomm.timeservice/1000 (adj 15): emptyCount ##41
,07-28 12:30:57.285   937  1666 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,07-28 12:30:57.285   937  1666 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:57.285   937  1666 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:57.285   937  1666 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:57.285   937  1666 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:57.325  7853  7853 E Zygote  : MountEmulatedStorage()
07-28 12:30:57.325  7853  7853 E Zygote  : v2
07-28 12:30:57.325  7853  7853 I libpersona: KNOX_SDCARD checking this for 10074
07-28 12:30:57.325  7853  7853 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:57.325  7790  7790 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-28 12:30:57.335   937  1666 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7853 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,07-28 12:30:57.345  7853  7853 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:57.345  7853  7853 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:30:57.345  7853  7853 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:30:57.365  7853  7853 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:57.365  7853  7853 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:57.375  7790  7790 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-28 12:30:57.375  7790  7790 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-28 12:30:57.375   361   361 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7790
07-28 12:30:57.375   361   361 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,07-28 12:30:57.375  7790  7790 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:30:57.375  7790  7790 I wpa_supplicant: ssSupport state is = 1
07-28 12:30:57.375  7790  7790 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,07-28 12:30:57.375  7790  7790 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:30:57.375  7790  7790 E wpa_supplicant: SIM READ ERROR
07-28 12:30:57.375  7790  7790 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:30:57.375  7790  7790 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:30:57.375  7790  7790 E wpa_supplicant: SIM READ ERROR
07-28 12:30:57.375  7790  7790 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:30:57.375  7790  7790 I wpa_supplicant: wpa_default_ap_write_once
07-28 12:30:57.375  7790  7790 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,07-28 12:30:57.375  7790  7790 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:30:57.375  7790  7790 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
07-28 12:30:57.375  7790  7790 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:30:57.375  7790  7790 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-28 12:30:57.385  7790  7790 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-28 12:30:57.385  7853  7853 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,07-28 12:30:57.425  7853  7853 I sCloudBackupApp: sCloudBackupApp Version Info : 3.13.7.KK_APP
,07-28 12:30:57.425  7853  7853 I SCloudBackupReceiver: Other Intent
,07-28 12:30:57.435  7180  7180 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,07-28 12:30:57.435  7180  7180 I KnoxUsageLogPro: premStatus:2
,07-28 12:30:57.445  7180  7180 I KnoxUsageLogPro: isEulaShown : false
,07-28 12:30:57.445  7180  7180 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-28 12:30:57.445   937  1648 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,07-28 12:30:57.445   937  1648 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:57.445   937  1648 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:57.445   937  1648 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:57.445   937  1648 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:57.485  7872  7872 E Zygote  : MountEmulatedStorage()
07-28 12:30:57.485  7872  7872 E Zygote  : v2
07-28 12:30:57.485  7872  7872 I libpersona: KNOX_SDCARD checking this for 10104
07-28 12:30:57.485  7872  7872 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:57.495  7872  7872 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:57.495  7872  7872 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:30:57.495  7872  7872 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,07-28 12:30:57.495   937  1648 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7872 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:30:57.495   937  1648 I ActivityManager: Killing 6908:com.google.android.apps.docs/u0a112 (adj 15): emptyCount ##41
,07-28 12:30:57.515  7872  7872 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:57.515  7872  7872 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:57.525  7872  7872 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-28 12:30:57.605   937  1471 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,07-28 12:30:57.605   937  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:57.605   937  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:57.605   937  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:57.605   937  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:57.645  7888  7888 E Zygote  : MountEmulatedStorage()
07-28 12:30:57.645  7888  7888 E Zygote  : v2
07-28 12:30:57.645  7888  7888 I libpersona: KNOX_SDCARD checking this for 10146
07-28 12:30:57.645  7888  7888 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:57.645   937  1471 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7888 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:30:57.655  7888  7888 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:57.655   937  1471 I ActivityManager: Killing 6962:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##41
07-28 12:30:57.655  7888  7888 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:30:57.655  7888  7888 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-28 12:30:57.675  7888  7888 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:57.675  7888  7888 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:57.685  7888  7888 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-28 12:30:57.875   266   556 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-28 12:30:57.875   266   556 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:30:57.875  7888  7906 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-28 12:30:57.895   266   556 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-28 12:30:57.895   266   556 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:30:57.895  7888  7906 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-28 12:30:57.925   266   556 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-28 12:30:57.925   266   556 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:30:57.925  7888  7909 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-28 12:30:57.925   266   556 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-28 12:30:57.925   266   556 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:30:57.925  7888  7909 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-28 12:30:58.035  7888  7888 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,07-28 12:30:58.035  7888  7888 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,07-28 12:30:58.055  7888  7888 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4232-4234)
,07-28 12:30:58.055  7888  7888 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-28 12:30:58.065  7888  7888 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1eab227a}
,07-28 12:30:58.065  7888  7888 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-28 12:30:58.065  7888  7888 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-28 12:30:58.085  7888  7888 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-28 12:30:58.085  7888  7888 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-28 12:30:58.085  7888  7888 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-28 12:30:58.195   937  1155 E Tethering: No numeric data
,07-28 12:30:58.195   937  1155 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-28 12:30:58.195   937  1149 V NetworkStats: performPollLocked(flags=0x1)
07-28 12:30:58.195   937  1149 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:30:58.195   937  1149 D NetworkStatsFactory: UpdateStatsForKnox
,07-28 12:30:58.195   937  1149 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:58.195  1194  1194 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-28 12:30:58.195  1194  1194 D HotspotTile: updateTetherState():false, false
,07-28 12:30:58.205   937  1149 V NetworkStats: performPollLocked() took 4ms
,07-28 12:30:58.205   937  1149 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:30:58.205   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:30:58.205   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:30:58.205  7888  7888 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-28 12:30:58.205  7888  7888 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
07-28 12:30:58.205  7888  7888 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,07-28 12:30:58.215  7790  7790 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,07-28 12:30:58.215  7888  7888 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-28 12:30:58.215  7888  7888 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-28 12:30:58.215  7888  7888 I Adreno-EGL: Build Date: 11/19/14 Wed
07-28 12:30:58.215  7888  7888 I Adreno-EGL: Local Branch: mybranch5813579
07-28 12:30:58.215  7888  7888 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-28 12:30:58.215  7888  7888 I Adreno-EGL: Local Patches: NONE
07-28 12:30:58.215  7888  7888 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-28 12:30:58.245  7790  7790 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-28 12:30:58.245  7790  7790 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:30:58.245  7790  7790 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-28 12:30:58.245   361   361 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7790
07-28 12:30:58.245   361   361 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,07-28 12:30:58.245  7790  7790 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:30:58.245  7790  7790 I wpa_supplicant: ssSupport state is = 1
07-28 12:30:58.245  7790  7790 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:30:58.245  7790  7790 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-28 12:30:58.245   361   361 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7790
07-28 12:30:58.245   361   361 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-28 12:30:58.245  7790  7790 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:30:58.245  7790  7790 I wpa_supplicant: ssSupport state is = 1
07-28 12:30:58.245  7790  7790 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:30:58.245  7790  7790 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:30:58.245  7790  7790 E wpa_supplicant: SIM READ ERROR
07-28 12:30:58.245  7790  7790 I wpa_supplicant: wpa_default_ap_write_once
07-28 12:30:58.245  7790  7790 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-28 12:30:58.245  7790  7790 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 12:30:58.265  7790  7790 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
07-28 12:30:58.265  7790  7790 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-28 12:30:58.275  7790  7790 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
07-28 12:30:58.275  7790  7790 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,07-28 12:30:58.275   937  1152 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-28 12:30:58.275   937  1152 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-28 12:30:58.275  7790  7790 I wpa_supplicant: HOTSPOT20_ENABLE called
07-28 12:30:58.275  7790  7790 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:30:58.275  7790  7790 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:30:58.275  7790  7790 E wpa_supplicant: SIM READ ERROR
07-28 12:30:58.275  7790  7790 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:30:58.285  7888  7888 I NSApplication: Starting up...
,07-28 12:30:58.295  7888  7936 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-28 12:30:58.295   937   954 I ActivityManager: Killing 6985:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): emptyCount ##41
,07-28 12:30:58.315  7790  7790 I wpa_supplicant: Skip scan - bUseNetwork false
,07-28 12:30:58.315  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:30:58.325   937  1152 D WifiNative-HAL: callSECApiInt - ID [210]
07-28 12:30:58.325   937   937 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:30:58.325  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:30:58.325  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-28 12:30:58.325  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:58.325  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:58.325  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:58.325  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:58.325  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:58.325  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:58.325  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:58.325  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:58.325  1194  1194 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:30:58.325  1194  1194 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
07-28 12:30:58.325  1194  1194 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:30:58.325  1194  1194 D HotspotTile: onReceive : 3, 0
07-28 12:30:58.325   937  1152 D WifiConfigStore: Loading config and enabling all networks 
07-28 12:30:58.325  1194  1583 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-28 12:30:58.325  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:58.325  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:30:58.325  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:58.325  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:58.325  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:58.325  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:30:58.325  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:58.325  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:58.325  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:30:58.325  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:58.325  7429  7429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:30:58.325   937  1156 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-28 12:30:58.325  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:58.325  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:30:58.325  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:58.325  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:58.325  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:30:58.325  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:30:58.325  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:58.325  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:58.325  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:30:58.325  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:58.325  7429  7429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:30:58.335   937  1152 E WifiConfigStore: Not a HS20
07-28 12:30:58.345   937  1152 E WifiConfigStore: Not a HS20
07-28 12:30:58.345   937  1152 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-28 12:30:58.355   937  1152 D WifiNative-HAL: callSECApiInt - ID [65]
,07-28 12:30:58.365   937  1152 D WifiNative-HAL: callSECApiBoolean - ID [13]
07-28 12:30:58.365  7790  7790 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-28 12:30:58.365  7790  7790 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-28 12:30:58.365  7790  7790 I wpa_supplicant: reset timer : RESET_TIMER 0
07-28 12:30:58.365  7790  7790 I wpa_supplicant: P2P: Current p2p state = IDLE
07-28 12:30:58.365  7790  7790 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-28 12:30:58.365  7790  7790 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-28 12:30:58.365  7790  7790 I wpa_supplicant: First Scan Start
07-28 12:30:58.365  7611  7611 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:30:58.365  7790  7790 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-28 12:30:58.365   937  1152 D WifiNative-HAL: Setting external_sim to 1
07-28 12:30:58.365   937  1152 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:30:58.365   937  1152 I WifiNative-HAL: startHal
07-28 12:30:58.365   937  1152 E wifi    : getStaticLongField sWifiHalHandle 0x931dd86c
07-28 12:30:58.365   937  1152 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x50217e
07-28 12:30:58.365   937  1152 I WifiNative-HAL: Could not start hal
07-28 12:30:58.385   937  1152 E native  : do suspend true
07-28 12:30:58.385   937  1151 D WifiP2pService: P2pDisabledState{ what=131203 }
07-28 12:30:58.385   937   937 D WifiScanningService: SCAN_AVAILABLE : 3
07-28 12:30:58.385   937   937 D RttService: SCAN_AVAILABLE : 3
07-28 12:30:58.385   937  1170 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:58.385   937  1169 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:58.385   937  1169 I WifiNative-HAL: startHal
07-28 12:30:58.385   937  1169 E wifi    : getStaticLongField sWifiHalHandle 0x9c5d399c
07-28 12:30:58.385   937  1169 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x501e8e
07-28 12:30:58.385   937  1169 I WifiNative-HAL: Could not start hal
07-28 12:30:58.385   937  1169 E WifiScanningService: could not start HAL
07-28 12:30:58.385   937  1152 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
07-28 12:30:58.385   298  1058 D CommandListener: Setting iface cfg
07-28 12:30:58.385   298  1058 D CommandListener: Trying to bring up p2p0
07-28 12:30:58.385   937  1151 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-28 12:30:58.385   937  1151 D WifiP2pService: P2pEnablingState
07-28 12:30:58.385   937  1151 D WifiP2pService: P2pEnablingState{ what=147457 }
07-28 12:30:58.385   937  1151 D WifiP2pService: P2p socket connection successful
07-28 12:30:58.385   937  1152 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
07-28 12:30:58.385   937  1152 D WifiNative-HAL: callSECStringApiVoid - ID [215]
07-28 12:30:58.385   937  1152 E WifiNative-HAL: invaild command id : 215
07-28 12:30:58.395   937  1151 D WifiP2pService: P2pEnabledState
07-28 12:30:58.395   937  1151 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-28 12:30:58.395   937  1062 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-28 12:30:58.395   937   937 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-28 12:30:58.395   937  1154 E ConnectivityService: updateNetworkInfo()
07-28 12:30:58.395   937  1062 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:30:58.395   937  1154 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-28 12:30:58.395   937  1062 D WifiDisplayController: disconnect
07-28 12:30:58.395   937  1062 D WifiDisplayController: updateConnection
07-28 12:30:58.395   937  1062 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:30:58.395   937  1062 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:58.395   937  1062 D WifiDisplayAdapter: onP2pDisconnected
07-28 12:30:58.395   937  1062 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-28 12:30:58.395   937  1062 D IpRemoteDisplayController: WfdBridgeServer is already null
07-28 12:30:58.395   937  1062 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-28 12:30:58.395  1194  1194 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-28 12:30:58.395   937  1147 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-28 12:30:58.395  1194  1194 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
07-28 12:30:58.395   937  1151 D WifiNative-HAL: p2pGetDeviceAddress
07-28 12:30:58.395   937  1151 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:de:28:a3
07-28 12:30:58.395   937  1151 D WifiP2pService: DeviceAddress: ea:28:a3
07-28 12:30:58.395   937  1062 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
07-28 12:30:58.395   937  1062 D WifiDisplayController:  deviceAddress: ea:50:8b:de:28:a3
07-28 12:30:58.395   937  1062 D WifiDisplayController:  primary type: 10-0050F204-5
07-28 12:30:58.395   937  1062 D WifiDisplayController:  secondary type: null
07-28 12:30:58.395   937  1062 D WifiDisplayController:  wps: 0
07-28 12:30:58.395   937  1062 D WifiDisplayController:  grpcapab: 0
07-28 12:30:58.395   937  1062 D WifiDisplayController:  devcapab: 0
07-28 12:30:58.395   937  1062 D WifiDisplayController:  status: 3
07-28 12:30:58.395   937  1062 D WifiDisplayController:  wfdInfo: null
07-28 12:30:58.395   937  1062 D WifiDisplayController:  groupownerAddress: null
07-28 12:30:58.395   937  1062 D WifiDisplayController:  GOdeviceName: null
07-28 12:30:58.395   937  1062 D WifiDisplayController:  interfaceAddress: 
07-28 12:30:58.395   937  1062 D WifiDisplayController:  SConnectInfo : null
,07-28 12:30:58.415   937  1151 D WifiP2pService: sending p2p persistent groups changed broadcast
07-28 12:30:58.415   937  1151 D WifiP2pService: InactiveState
07-28 12:30:58.415   937  1151 D WifiP2pService: InactiveState{ what=143376 }
07-28 12:30:58.415   937  1151 D WifiP2pService: P2pEnabledState{ what=143376 }
07-28 12:30:58.415   937  1253 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
07-28 12:30:58.415   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:58.415   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:58.415   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:58.415   937  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:58.445  7790  7790 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-28 12:30:58.445  7790  7790 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-28 12:30:58.445   937  1151 D WifiP2pService: InactiveState{ what=143376 }
,07-28 12:30:58.445   937  1151 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-28 12:30:58.465  7790  7790 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-28 12:30:58.465   937  1152 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:30:58.465   937  1152 D SecContentProvider2: mCursor = null
,07-28 12:30:58.475  7946  7946 E Zygote  : MountEmulatedStorage()
,07-28 12:30:58.475  7946  7946 E Zygote  : v2
07-28 12:30:58.475  7946  7946 I libpersona: KNOX_SDCARD checking this for 10158
07-28 12:30:58.475  7946  7946 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:58.485   937  1253 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7946 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,07-28 12:30:58.485   937  1152 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:30:58.485   937  1152 D SecContentProvider2: mCursor = null
,07-28 12:30:58.495  7946  7946 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:58.495  7946  7946 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:30:58.495  7946  7946 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:30:58.515  7946  7946 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:58.515  7946  7946 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:58.525  7946  7946 D ResourcesManager: creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,07-28 12:30:58.525  7946  7946 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 12:30:58.525  7946  7946 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-28 12:30:58.525  7946  7946 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-28 12:30:58.535  7946  7946 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:30:58.535  7946  7946 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,07-28 12:30:58.545  7946  7946 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-28 12:30:58.545   937  1434 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,07-28 12:30:58.545   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:58.545   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:58.545   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:58.545   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:58.585   937  1434 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7961 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,07-28 12:30:58.585   937  1434 I ActivityManager: Killing 7000:com.samsung.helphub/1000 (adj 15): emptyCount ##41
,07-28 12:30:58.595  7961  7961 E Zygote  : MountEmulatedStorage()
,07-28 12:30:58.595  7961  7961 E Zygote  : v2
07-28 12:30:58.595  7961  7961 I libpersona: KNOX_SDCARD checking this for 10186
07-28 12:30:58.595  7961  7961 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:58.625  7961  7961 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:58.625  7961  7961 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:30:58.625  7961  7961 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:30:58.645  7961  7961 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:58.645  7961  7961 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:58.655  7961  7961 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-28 12:30:58.665  7961  7961 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,07-28 12:30:58.665  7961  7961 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:30:58.665  7961  7961 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
07-28 12:30:58.665  7961  7961 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-28 12:30:58.665  7961  7961 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-28 12:30:58.745   937  1556 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:30:58.775   937  1364 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:30:58.775   937  3040 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:30:58.815   937  1479 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,07-28 12:30:58.815   937  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:58.815   937  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:58.815   937  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:58.815   937  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:58.825   937   952 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:30:58.845   937  1471 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:30:58.855  7984  7984 E Zygote  : MountEmulatedStorage()
07-28 12:30:58.855  7984  7984 E Zygote  : v2
07-28 12:30:58.855  7984  7984 I libpersona: KNOX_SDCARD checking this for 10092
07-28 12:30:58.855  7984  7984 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:58.855   937  1479 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7984 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,07-28 12:30:58.895  7984  7984 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:58.895  7984  7984 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:30:58.895   937  1242 D RCPManagerService: exchangeData() failure , invalid userId
07-28 12:30:58.895  7984  7984 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-28 12:30:58.895   937   954 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:58.895  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:30:58.895  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:30:58.895  6889  6889 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:30:58.895  6889  6889 D SecurityLogAgent: StateMachine : Changed Current State = 1
07-28 12:30:58.895   937  1556 I ActivityManager: Killing 7056:com.samsung.android.snote:provider/u0a168 (adj 15): emptyCount ##41
,07-28 12:30:58.905   937  1364 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:58.905   937  3040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,07-28 12:30:58.905   937  3040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:58.905   937  3040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:58.905   937  3040 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:30:58.905   937  3040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:30:58.905   937  1471 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:58.925  7984  7984 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:58.925  7984  7984 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:58.945  7999  7999 E Zygote  : MountEmulatedStorage()
07-28 12:30:58.945  7999  7999 I libpersona: KNOX_SDCARD checking this for 10200
07-28 12:30:58.945  7999  7999 E Zygote  : v2
07-28 12:30:58.945  7999  7999 I libpersona: KNOX_SDCARD not a persona
,07-28 12:30:58.945   937  3040 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7999 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:30:58.975  7999  7999 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:30:58.975  7999  7999 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:30:58.975  7999  7999 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-28 12:30:58.975   937  1648 I ActivityManager: Killing 7075:com.sec.kidsplat.installer/u0a189 (adj 15): emptyCount ##41
,07-28 12:30:59.005  7999  7999 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:30:59.005  7999  7999 D ActivityThread: Added TimaKeyStore provider
,07-28 12:30:59.005   303   303 E SMD     : DCD ON
,07-28 12:30:59.085   937  1242 I art     : Explicit concurrent mark sweep GC freed 78672(4MB) AllocSpace objects, 22(400KB) LOS objects, 29% free, 37MB/53MB, paused 1.328ms total 101.126ms
,07-28 12:30:59.085  7984  7984 D ResourcesManager: creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,07-28 12:30:59.095  7999  7999 D ResourcesManager: creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,07-28 12:30:59.095  7984  7984 D BadgeProvider: onCreate
,07-28 12:30:59.095  7984  7984 D BadgeProvider: DatabaseHelper
,07-28 12:30:59.105  7984  7992 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,07-28 12:30:59.115   937  1434 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,07-28 12:30:59.115   937  1666 I ActivityManager: Killing 7098:com.sec.android.app.samsungapps/u0a45 (adj 15): emptyCount ##41
,07-28 12:30:59.125   937   952 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:30:59.125   937   952 D ActivityManager: caller:android.app.ApplicationThreadProxy@11c66530, r.packageName :com.google.android.gms
,07-28 12:30:59.125  7984  7992 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
07-28 12:30:59.125  7984  7992 D BadgeProvider: sendNotify, [notify] : null
,07-28 12:30:59.125  7984  7992 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
07-28 12:30:59.125  7984  7992 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-28 12:30:59.125  7984  7992 D BadgeProvider: update, [UpdateCount] : 1
07-28 12:30:59.125  1442  1442 D Launcher.Model: reloadBadges entered.
,07-28 12:30:59.125  4453  4453 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-28 12:30:59.135  4453  5336 I iu.UploadsManager: num queued entries: 0
07-28 12:30:59.135  4453  5336 I iu.UploadsManager: num updated entries: 0
,07-28 12:30:59.135  4453  5336 I iu.SyncManager: NEXT; no task
,07-28 12:30:59.145  7790  7790 I wpa_supplicant: nl80211: Received scan results (22 BSSes)
07-28 12:30:59.145  7790  7790 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-28 12:30:59.145  7790  7790 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
07-28 12:30:59.145  7790  7790 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
07-28 12:30:59.145  7790  7790 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=5 BSSID=00.00.00 SSID=4E47373030
,07-28 12:30:59.155   937  1152 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:30:59.155   937  1152 D SecContentProvider2: mCursor = null
,07-28 12:30:59.165  7038  7038 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:30:59.175   937  1556 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:59.175  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:30:59.175  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:30:59.175  6889  6889 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:30:59.175  6889  6889 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:30:59.185  7038  7038 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:30:59.185   937  1737 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:59.185  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,07-28 12:30:59.185  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:30:59.185  6889  6889 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:30:59.185  6889  6889 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:30:59.195  7596  7596 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-28 12:30:59.195  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:30:59.195  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:30:59.195  7790  7790 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
07-28 12:30:59.205  7790  7790 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=6 BSSID=00.00.00 SSID=4E47373030
,07-28 12:30:59.205  7790  7790 I wpa_supplicant: Associated with F4.99.3E
07-28 12:30:59.205  7790  7790 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
07-28 12:30:59.205  7790  7790 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=7 BSSID=F4.99.3E SSID=4E47373030
,07-28 12:30:59.205   937  1434 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:59.205  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:30:59.205   937  1556 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:59.205  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:30:59.205  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:30:59.205  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:30:59.205  1315  2678 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:30:59.205   937  1152 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:30:59.205   937  1152 D SecContentProvider2: mCursor = null
,07-28 12:30:59.205   937  1152 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:30:59.205   937  1152 D SecContentProvider2: mCursor = null
,07-28 12:30:59.205  7165  7165 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-28 12:30:59.215  7596  7596 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:30:59.215  7596  7596 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
07-28 12:30:59.215  7596  7596 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-28 12:30:59.215  7596  7596 D WifiDirectBR: stopServiceTest : false
,07-28 12:30:59.225  7790  7790 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,07-28 12:30:59.225  7790  7790 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
07-28 12:30:59.225  7790  7790 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=8 BSSID=F4.99.3E SSID=4E47373030
,07-28 12:30:59.225  7790  7790 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:30:59.225  7790  7790 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
07-28 12:30:59.225  7790  7790 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=1 id_str=]
,07-28 12:30:59.225  7790  7790 I wpa_supplicant: Blacklist: Clear (temp) 
07-28 12:30:59.225  7790  7790 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=9 BSSID=F4.99.3E SSID=4E47373030
,07-28 12:30:59.225   937  1152 D WifiNative-HAL: callSECApiVoid - ID [50]
,07-28 12:30:59.235  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:30:59.235  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:30:59.235   937  1152 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
07-28 12:30:59.235   937  1152 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:30:59.235   937  1154 D ConnectivityService: Got NetworkAgent Messenger
07-28 12:30:59.235   937  1154 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
07-28 12:30:59.235   937  1154 E ConnectivityService: updateNetworkInfo()
,07-28 12:30:59.235  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-28 12:30:59.235   937  1154 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:30:59.235   937  1154 D ConnectivityService: NetworkAgent connected
07-28 12:30:59.235  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:30:59.235   937  1472 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:59.235  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-28 12:30:59.235   937  1537 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:59.235  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:30:59.235  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:30:59.235  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:30:59.235  1315  2678 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:30:59.245   937  1556 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:59.245   937  1152 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:30:59.245  7038  7038 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:30:59.255   298  1058 D CommandListener: Setting iface cfg
,07-28 12:30:59.255   937  1152 E WifiStateMachine: Start Dhcp Watchdog 2
,07-28 12:30:59.255   937  1152 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:30:59.255   937  1152 D SecContentProvider2: mCursor = null
,07-28 12:30:59.255  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:30:59.255  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:30:59.265   937  1154 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-28 12:30:59.345   937  1152 E native  : do suspend false
,07-28 12:30:59.345   937  1152 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:30:59.345   937  1151 D WifiP2pService: InactiveState{ what=143375 }
07-28 12:30:59.345   937  1152 D SecContentProvider2: mCursor = null
07-28 12:30:59.345   937  1151 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-28 12:30:59.485   937  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-28 12:30:59.585  8035  8035 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-28 12:30:59.585  8035  8035 I dhcpcd  : version 5.5.6 starting
,07-28 12:30:59.595  8035  8035 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-28 12:30:59.655  8035  8035 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-28 12:30:59.655  8035  8035 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
07-28 12:30:59.655  8035  8035 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
07-28 12:30:59.655  8035  8035 I dhcpcd  : bssid match
07-28 12:30:59.665  8035  8035 I dhcpcd  : wlan0: rebinding lease of 192.168.1.122
,07-28 12:30:59.675  8035  8035 I dhcpcd  : wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,07-28 12:30:59.675  8035  8035 I dhcpcd  : wlan0: leased 192.168.1.122 for 172800 seconds
,07-28 12:30:59.675   937  1154 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-28 12:30:59.735  7429  7490 I WifiManager: packageName : com.test.thalitest
07-28 12:30:59.735   937  1471 D WifiService: setWifiEnabled: false pid=7429, uid=10079
07-28 12:30:59.735   937  1471 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-28 12:30:59.735   937  1471 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:30:59.735   937  1471 D SecContentProvider2: mCursor = null
07-28 12:30:59.735   937  1471 D SettingsProvider: name = wifi_on
,07-28 12:30:59.745   937  1152 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:30:59.765   937  1152 E native  : do suspend true
,07-28 12:30:59.775   937  1151 D WifiP2pService: InactiveState{ what=143375 }
,07-28 12:30:59.775   937  1151 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-28 12:30:59.775   298  1058 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:30:59.775  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:30:59.775  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:30:59.815   937  1152 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:30:59.815   937   937 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-28 12:30:59.815   937  1154 E ConnectivityService: updateNetworkInfo()
,07-28 12:30:59.815   937  1154 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-28 12:30:59.815   937  1154 E ConnectivityService: updateNetworkInfo()
07-28 12:30:59.815   937  1154 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
,07-28 12:30:59.815   937  1154 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
07-28 12:30:59.815   298  1058 E Netd    : no such netId 503
,07-28 12:30:59.815   937  1154 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '77 network destroy 503' failed with '400 77 destroyNetwork() failed (Machine is not on the network)'
,07-28 12:30:59.815   937  1154 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
07-28 12:30:59.815   937  1154 D ConnectivityService: calling update connectivity
07-28 12:30:59.815   937  1154 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
,07-28 12:30:59.815   937  1154 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
07-28 12:30:59.815  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:30:59.815  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:30:59.825   937  8022 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-9ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:30:59.825   937  8022 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,07-28 12:30:59.825   937  1151 D WifiP2pService: InactiveState{ what=131204 }
07-28 12:30:59.825   937  1151 D WifiP2pService: P2pEnabledState{ what=131204 }
,07-28 12:30:59.825   937  1151 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-28 12:30:59.825   937  1152 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-28 12:30:59.835   937  1151 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-28 12:30:59.835   937  1154 E ConnectivityService: updateNetworkInfo()
07-28 12:30:59.835   937  1154 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-28 12:30:59.835   937   937 D WifiScanningService: SCAN_AVAILABLE : 1
07-28 12:30:59.835   937   937 D RttService: SCAN_AVAILABLE : 1
07-28 12:30:59.835   937  1169 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:30:59.835   937  1170 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:30:59.835   937  1154 E ConnectivityService: updateNetworkInfo()
07-28 12:30:59.835   937  1154 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-28 12:30:59.835   937  1062 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-28 12:30:59.835   937  1062 D WifiDisplayAdapter: onP2pDisconnected
07-28 12:30:59.835   937  1062 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-28 12:30:59.835   937  1062 D IpRemoteDisplayController: WfdBridgeServer is already null
07-28 12:30:59.835   937   937 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-28 12:30:59.835   937  1151 D WifiP2pService: P2pDisablingState
,07-28 12:30:59.835   937  1062 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,07-28 12:30:59.835   937  1151 D WifiP2pService: P2pDisablingState{ what=147458 }
07-28 12:30:59.835   937  1151 D WifiP2pService: p2p socket connection lost
,07-28 12:30:59.835   937  1151 D WifiP2pService: P2pDisabledState
,07-28 12:30:59.845   937  1062 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:30:59.845   937  1062 D WifiDisplayController: disconnect
07-28 12:30:59.845   937  1062 D WifiDisplayController: updateConnection
07-28 12:30:59.845   937  1062 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:30:59.845   937  1062 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-28 12:30:59.845  1194  1194 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-28 12:30:59.845   937  1666 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-28 12:30:59.845  1194  1194 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-28 12:30:59.845  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-28 12:30:59.855  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-28 12:30:59.855   937  1434 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:59.855  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:30:59.855   937   954 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-28 12:30:59.855  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:30:59.855  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:30:59.855  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-28 12:30:59.855   937  1152 E native  : do suspend true
,07-28 12:30:59.855  1315  2678 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:30:59.865   937  1151 D WifiP2pService: P2pDisabledState{ what=143375 }
,07-28 12:30:59.865   937  1737 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:59.865   937  1151 D WifiP2pService: DefaultState{ what=143375 }
,07-28 12:30:59.865  7038  7038 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:30:59.865  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:30:59.865  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:30:59.865   298  1058 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:30:59.875  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:30:59.875  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:30:59.875  7790  7790 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
07-28 12:30:59.875   937   937 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-28 12:30:59.875  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:30:59.875  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:30:59.875   937   937 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
07-28 12:30:59.875   937  1472 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:59.875  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:30:59.875   937  1434 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-28 12:30:59.875   937  1156 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-28 12:30:59.875  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:59.875  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:30:59.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:59.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:59.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:30:59.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:30:59.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:59.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:59.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:30:59.875  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:30:59.875  7429  7429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:30:59.875   937  1152 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:30:59.875  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:30:59.875  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-28 12:30:59.875  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:59.875  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:59.875  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:59.875  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:59.875  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:59.875  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:59.875  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:30:59.875  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:30:59.875  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:30:59.875  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:30:59.875  1194  1194 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:30:59.875  1194  1194 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:30:59.875  1194  1194 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
07-28 12:30:59.875  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:30:59.875  1315  2678 V NearbySettings: MountReceiver.mPrefHandler - 7002
07-28 12:30:59.875  1194  1583 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-28 12:30:59.875  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:59.875   937  1152 D SecContentProvider2: mCursor = null
,07-28 12:30:59.875  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:30:59.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:30:59.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:30:59.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:30:59.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:30:59.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:30:59.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:30:59.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:30:59.875  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:30:59.875  7429  7429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:30:59.885  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:30:59.885  7165  7165 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-28 12:30:59.885  1194  1194 D HotspotTile: onReceive : 0, 0
,07-28 12:30:59.885  7596  7596 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-28 12:30:59.885  7596  7596 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,07-28 12:30:59.895  7596  7596 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-28 12:30:59.895  7596  7596 D WifiDirectBR: stopServiceTest : false
,07-28 12:30:59.895  7596  7596 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-28 12:30:59.905  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-28 12:30:59.905  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:30:59.905   937  1434 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:59.905  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:30:59.905   937  3040 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-28 12:30:59.905  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:30:59.905  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:30:59.905  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:30:59.905  1315  2678 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:30:59.915   937  1147 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:30:59.915  7038  7038 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:30:59.925  7038  7038 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:30:59.925   937  1472 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:30:59.925  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,07-28 12:30:59.925  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:30:59.925  6889  6889 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:30:59.925  6889  6889 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:30:59.935  7790  7790 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:30:59.965  7790  7790 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-28 12:30:59.965  7790  7790 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,07-28 12:30:59.965  7790  7790 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
07-28 12:30:59.965  7790  7790 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=0 BSSID=F4.99.3E SSID=4E47373030
07-28 12:30:59.965  7790  7790 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-28 12:30:59.995   937  1116 V AlarmManager: waitForAlarm result :8
,07-28 12:31:00.005  7790  7790 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:31:00.145   937  1155 D Tethering: InitialState.processMessage what=4
,07-28 12:31:00.145   937  1155 E Tethering: No numeric data
07-28 12:31:00.145   937  1155 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-28 12:31:00.145  7790  7790 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-28 12:31:00.145   937  1149 V NetworkStats: performPollLocked(flags=0x1)
07-28 12:31:00.145   937  1149 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:31:00.145  1194  1194 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-28 12:31:00.145  1194  1194 D HotspotTile: updateTetherState():false, false
,07-28 12:31:00.145   937  1149 D NetworkStatsFactory: UpdateStatsForKnox
,07-28 12:31:00.145   937  1149 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:00.145   937  1149 V NetworkStats: performPollLocked() took 3ms
,07-28 12:31:00.145   937  1149 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:31:00.145   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:31:00.145   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:31:00.245   937  1152 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
07-28 12:31:00.245   937  1152 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-28 12:31:00.245  7611  7611 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:00.245   937   937 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:31:00.245   937  1156 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-28 12:31:00.255  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:31:00.255  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:00.255  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-28 12:31:00.255  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:00.255  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-28 12:31:00.255  1194  1194 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:31:00.255  1194  1194 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
07-28 12:31:00.255  1194  1194 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:31:00.255  1194  1583 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-28 12:31:00.255  1194  1194 D HotspotTile: onReceive : 1, 0
07-28 12:31:00.255  1823  2361 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:31:00.255  7038  7038 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:31:00.265   937   952 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:00.265  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:31:00.265  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:31:00.265  6889  6889 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:31:00.265  6889  6889 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:31:00.355   937  1471 I ActivityManager: Killing 7115:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 15): emptyCount ##41
,07-28 12:31:00.455   937  1152 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,07-28 12:31:00.925   937   952 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-28 12:31:00.925   937   952 D ActivityManager: caller:android.app.ApplicationThreadProxy@bdc3578, r.packageName :com.google.android.music
,07-28 12:31:00.945   937  1537 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:31:00.945   937  1434 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:31:00.945   937  3040 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:31:00.955   937  1666 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-28 12:31:00.955   937  1666 D ActivityManager: caller:android.app.ApplicationThreadProxy@3675248e, r.packageName :com.google.android.music
,07-28 12:31:00.975  1823  1823 D WearableService: callingUid 10015, callindPid: 1823
,07-28 12:31:00.985   937  1737 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:31:01.025  7681  7681 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-28 12:31:01.035  7681  8106 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-28 12:31:01.055  7681  8101 I MusicLeanback: Conditions not met for autocaching.
07-28 12:31:01.055  7681  8101 I MusicLeanback: Stop autocaching.
,07-28 12:31:01.655   937  3069 D SSRM:n  : SIOP:: AP = 400, PST = 378, CUR = 450
,07-28 12:31:02.015   303   303 E SMD     : DCD ON
,07-28 12:31:02.756  7429  7490 D BluetoothAdapter: enable()
,07-28 12:31:02.756   937  1471 W ActivityManager: Permission Denial: getCurrentUser() from pid=7429, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-28 12:31:02.766   937  1471 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-28 12:31:02.766   937  1471 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7429, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:31:02.766   937  1471 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-28 12:31:02.766   937  1471 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-28 12:31:02.766   937  1471 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-28 12:31:02.766   937  1471 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-28 12:31:02.766   937  1471 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-28 12:31:02.766   937  1471 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:31:02.766   937  1471 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:31:02.776   937  1471 D SettingsProvider: name = bluetooth_on
,07-28 12:31:02.785   937  1061 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:31:02.785   937  1061 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:31:02.785   937  1061 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,07-28 12:31:02.815  7642  7642 D BluetoothAdapterState: make
,07-28 12:31:02.815  7642  7642 I bluedroid: init
,07-28 12:31:02.815  7642  8116 I BluetoothAdapterState: Entering OffState
,07-28 12:31:02.815  7642  7642 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-28 12:31:02.815  7642  7642 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 12:31:02.815  7642  7642 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-28 12:31:02.815  7642  7642 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-28 12:31:02.815  7642  7642 E bt-btif : btif_fetch_local_ble_random_bdaddr
07-28 12:31:02.815  7642  7642 I bluedroid: get_profile_interface socket
07-28 12:31:02.815  7642  7642 I bluedroid: get_profile_interface map_client
,07-28 12:31:02.825  7642  7642 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,07-28 12:31:02.825  7642  8119 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,07-28 12:31:02.825   937  1364 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:31:02.835  7642  7654 I bluedroid: config_hci_snoop_log
,07-28 12:31:02.835   937  1061 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 14 receivers.
,07-28 12:31:02.835   937  1061 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:31:02.835   937  1061 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:31:02.835   937  1061 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-28 12:31:02.845  7642  8119 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,07-28 12:31:02.845  7642  8116 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
07-28 12:31:02.845  7642  8119 E BluetoothServiceJni: populateRssiValuesNative
07-28 12:31:02.845  7642  8119 I bluedroid: getModelRssiValues
,07-28 12:31:02.845  7642  8119 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-28 12:31:02.845  7642  8119 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-28 12:31:02.845   937   937 D SettingsProvider: name = bluetooth_name
,07-28 12:31:02.845  7642  8119 D BluetoothAdapterProperties: Name is: Note3-1
,07-28 12:31:02.845  7642  8116 D BluetoothAdapterProperties: Setting state to 11
07-28 12:31:02.845  7642  8116 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-28 12:31:02.845  7642  8116 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,07-28 12:31:02.845  7642  8116 D BluetoothAdapterService: updateAdapterState state is 11
,07-28 12:31:02.845   937   937 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:02.855  1696  1696 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-28 12:31:02.855   937   937 I InputMethodManagerService: [BT Setting State] State =11
,07-28 12:31:02.855  1194  1194 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-28 12:31:02.855  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:02.855  1194  1194 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:02.855  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:02.855   937  1471 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:31:02.865  1194  1583 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:31:02.865   937  1537 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-28 12:31:02.865  1194  1194 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-28 12:31:02.865  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:02.865   937   954 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:31:02.865   937   954 D ActivityManager: caller:android.app.ApplicationThreadProxy@26604616, r.packageName :com.google.android.gms
,07-28 12:31:02.865  7571  7571 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:02.865  7642  8116 D BluetoothAdapterService: Autoconnection is available 
07-28 12:31:02.875  7642  8116 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,07-28 12:31:02.875  7642  8116 D BluetoothSecureManager: getInstant: null
,07-28 12:31:02.875  7642  8116 D BluetoothSecureManager: calling getMethod for getService
,07-28 12:31:02.875  7642  8116 D BluetoothSecureManager: calling getService
,07-28 12:31:02.885  7642  8116 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3853da74
,07-28 12:31:02.885   937   952 D BluetoothSecureManagerService: isSecureModeEnabled
07-28 12:31:02.885   937   952 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,07-28 12:31:02.885  7642  8116 D BtConfig.SecureMode: isSecureModeOn:false
07-28 12:31:02.885  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-28 12:31:02.885  7642  8116 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,07-28 12:31:02.885  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-28 12:31:02.885  7642  8116 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,07-28 12:31:02.885  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-28 12:31:02.885  7642  8116 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,07-28 12:31:02.885  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:31:02.885  7642  8116 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,07-28 12:31:02.885  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-28 12:31:02.895  7642  8116 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,07-28 12:31:02.895  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-28 12:31:02.895  7642  8116 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,07-28 12:31:02.895  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-28 12:31:02.895  7642  8116 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-28 12:31:02.895  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,07-28 12:31:02.895  7642  8116 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
07-28 12:31:02.895  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:31:02.895  7642  8116 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:31:02.895  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-28 12:31:02.895  7642  8116 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:31:02.895  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-28 12:31:02.895  7642  8116 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,07-28 12:31:02.895  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-28 12:31:02.895  7642  8116 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,07-28 12:31:02.895  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:31:02.905  7642  8116 D BluetoothBondStateMachine: make
,07-28 12:31:02.915   937   952 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,07-28 12:31:02.925  7888  7907 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,07-28 12:31:02.925  7642  8121 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-28 12:31:02.925  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,07-28 12:31:02.935  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-28 12:31:02.935  7642  8116 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,07-28 12:31:02.935   937  1556 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:31:02.935   937  1556 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e12ada2, r.packageName :com.android.bluetooth
,07-28 12:31:02.935  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,07-28 12:31:02.935  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-28 12:31:02.935  7642  8116 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
07-28 12:31:02.935   937  1364 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:31:02.935  7642  7642 I BtGatt.JNI: classInitNative(L890): classInitNative: Success!
07-28 12:31:02.935   937  1364 D ActivityManager: caller:android.app.ApplicationThreadProxy@2a7cc1f0, r.packageName :com.android.bluetooth
,07-28 12:31:02.935  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-28 12:31:02.935  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-28 12:31:02.935  7642  8116 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-28 12:31:02.935   937  1737 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:31:02.935   937  1737 D ActivityManager: caller:android.app.ApplicationThreadProxy@279201ee, r.packageName :com.android.bluetooth
,07-28 12:31:02.935  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-28 12:31:02.935  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:31:02.935  7642  8116 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,07-28 12:31:02.935   937  1242 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:31:02.935   937  1242 D ActivityManager: caller:android.app.ApplicationThreadProxy@38840d1c, r.packageName :com.android.bluetooth
,07-28 12:31:02.945  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-28 12:31:02.945  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-28 12:31:02.945  7642  8116 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-28 12:31:02.945  7642  7642 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:31:02.945   937  1472 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:31:02.945  7642  7642 D BtGatt.GattService: Received start request. Starting profile...
07-28 12:31:02.945  7642  7642 D BtGatt.GattService: start()
07-28 12:31:02.945  7642  7642 I bluedroid: get_profile_interface gatt
07-28 12:31:02.945   937  1472 D ActivityManager: caller:android.app.ApplicationThreadProxy@35a04efa, r.packageName :com.android.bluetooth
,07-28 12:31:02.945  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
07-28 12:31:02.945  7642  7642 D BtGatt.AdvertiseManager: advertise manager created
,07-28 12:31:02.945  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-28 12:31:02.945  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-28 12:31:02.945  7642  8116 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-28 12:31:02.945   937  1537 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:31:02.945   937  1537 D ActivityManager: caller:android.app.ApplicationThreadProxy@3052df08, r.packageName :com.android.bluetooth
,07-28 12:31:02.945  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,07-28 12:31:02.945  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:31:02.945  7642  8116 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-28 12:31:02.955   937  1253 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:31:02.955   937  1253 D ActivityManager: caller:android.app.ApplicationThreadProxy@331460c6, r.packageName :com.android.bluetooth
,07-28 12:31:02.955  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-28 12:31:02.955  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-28 12:31:02.955  7642  8116 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,07-28 12:31:02.955   937  1434 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:31:02.955   937  1434 D ActivityManager: caller:android.app.ApplicationThreadProxy@13435623, r.packageName :com.android.bluetooth
,07-28 12:31:02.955  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:31:02.955  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:31:02.955  7642  8116 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:31:02.955  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:31:02.955  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-28 12:31:02.955  7642  8116 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:31:02.955  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
07-28 12:31:02.955  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-28 12:31:02.955  7642  8116 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-28 12:31:02.955  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
07-28 12:31:02.955  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-28 12:31:02.955  7642  8116 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-28 12:31:02.955  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
,07-28 12:31:02.955  1823  1823 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:31:02.955  7642  8116 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-28 12:31:02.965  7642  7642 D HeadsetService: Received start request. Starting profile...
,07-28 12:31:02.965  7642  7642 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-28 12:31:02.965  7642  7642 D HeadsetStateMachine: make
,07-28 12:31:02.965  1823  1823 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:31:02.975  7642  7642 E HeadsetStateMachine: # of Max HF connection is 2
,07-28 12:31:02.975   937  3040 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,07-28 12:31:02.975   937  1147 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,07-28 12:31:02.975  7642  7642 I bluedroid: get_profile_interface handsfree
,07-28 12:31:02.985  7642  7642 I DualScoManager: Instantiating Dual Sco Manager
,07-28 12:31:02.985  7642  7642 I DualScoManager: Set HeadsetServiceHelper
,07-28 12:31:02.985  7642  7642 D BluetoothAtMessage: createCMTIContentObservers
,07-28 12:31:02.985   937  1364 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
07-28 12:31:02.985   937  1364 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:31:02.985   937  1364 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:31:02.985   937  1364 D SettingsProvider: selectionArgs: false
07-28 12:31:02.985   937  1364 D SettingsProvider: selectionArgs: 1002
07-28 12:31:02.985   937  1364 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:31:02.985   937  1364 D SettingsProvider: ret = -1
,07-28 12:31:02.995  7642  8143 D HeadsetStateMachine: Enter Disconnected: -2
,07-28 12:31:02.995  7642  8143 E HeadsetStateMachine: set to mRemoteBrsf = 0
07-28 12:31:02.995  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
,07-28 12:31:02.995  7642  7642 D A2dpService: Received start request. Starting profile...
,07-28 12:31:02.995  7642  7642 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-28 12:31:02.995  7642  7642 V Avrcp   : make
07-28 12:31:02.995  7642  7642 V Avrcp   : Avrcp
,07-28 12:31:02.995  7642  7642 I bluedroid: get_profile_interface avrcp
,07-28 12:31:02.995  7642  7642 V Avrcp   : start
,07-28 12:31:03.005  7642  8143 D HeadsetStateMachine: map size, before remove : 0
07-28 12:31:03.005  7642  8143 D HeadsetStateMachine: map size, after remove: 0
,07-28 12:31:03.005  7642  8143 D HeadsetStateMachine: mNextConnectingDevice : null
,07-28 12:31:03.005  7642  7642 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-28 12:31:03.005  7642  7642 V Avrcp   : ++registerMediaPlayers++
,07-28 12:31:03.005  7642  7642 I Avrcp   : No of Audio players :: 2
,07-28 12:31:03.005  7642  7642 I Avrcp   : App Package name is com.google.android.music
,07-28 12:31:03.005  7642  7642 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-28 12:31:03.015  7642  7642 I Avrcp   : App pkg name is Google Play Music
,07-28 12:31:03.015  7642  7642 I Avrcp   : Name::Google Play Music
07-28 12:31:03.015  7642  7642 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-28 12:31:03.015  7642  7642 I Avrcp   : App Package name is com.sec.android.app.music
,07-28 12:31:03.015  7642  7642 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-28 12:31:03.015  7642  7642 I Avrcp   : App pkg name is Music
,07-28 12:31:03.015  7642  7642 I Avrcp   : Name::Music
07-28 12:31:03.015  7642  7642 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-28 12:31:03.015  7642  7642 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,07-28 12:31:03.015  7642  7642 I Avrcp   : No of Video players :: 1
07-28 12:31:03.015  7642  7642 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,07-28 12:31:03.015  7642  7642 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,07-28 12:31:03.015  7642  7642 I Avrcp   : Video App pkg name is Video Player
,07-28 12:31:03.015  7642  7642 I Avrcp   : Name::Video Player
07-28 12:31:03.015  7642  7642 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-28 12:31:03.015  7642  7642 I Avrcp   : Add tempPlayer
07-28 12:31:03.015  7642  7642 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-28 12:31:03.015  7642  7642 I Avrcp   : Total no of players: 4
07-28 12:31:03.015  7642  7642 V Avrcp   : swapping the samsung player with 1st player
07-28 12:31:03.015  7642  7642 I Avrcp   :  Updating now playing list upon AVRCP Start
,07-28 12:31:03.015  7642  8144 V Avrcp   : handleMessage, msg=207
07-28 12:31:03.015  7642  8144 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,07-28 12:31:03.025  7642  7642 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:31:03.025  7642  7642 D A2dpStateMachine: make
,07-28 12:31:03.025  7642  7642 I bluedroid: get_profile_interface a2dp
07-28 12:31:03.025  7642  8146 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,07-28 12:31:03.025  7642  7642 E bt-btif : warning : media task started media_task_refcnt 1 
,07-28 12:31:03.025  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
07-28 12:31:03.025  7642  8145 D A2dpStateMachine: Enter Disconnected: -2
07-28 12:31:03.025  7642  8144 D BluetoothMediaBrowser: no now playing list
,07-28 12:31:03.025  7642  8144 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
07-28 12:31:03.025  7642  8144 D Avrcp   :  checkNowPlayingList start
,07-28 12:31:03.025  7642  7642 I BluetoothHidServiceJni: classInitNative: succeeds
,07-28 12:31:03.025  7642  7642 D HidService: Received start request. Starting profile...
,07-28 12:31:03.025  7642  7642 I bluedroid: get_profile_interface hidhost
07-28 12:31:03.025  7642  7642 D HidService: setHidService(): set to: null
07-28 12:31:03.025  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
,07-28 12:31:03.025  7642  7642 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-28 12:31:03.035  7642  7642 D HealthService: Received start request. Starting profile...
,07-28 12:31:03.035  7642  7642 I bluedroid: get_profile_interface health
,07-28 12:31:03.035  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
,07-28 12:31:03.035  7642  7642 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-28 12:31:03.035  7642  7642 D PanService: Received start request. Starting profile...
,07-28 12:31:03.035  7642  7642 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:31:03.035  7642  7642 I bluedroid: get_profile_interface pan
,07-28 12:31:03.035  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
,07-28 12:31:03.035  7642  7642 D BluetoothMapService: Received start request. Starting profile...
,07-28 12:31:03.065  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
,07-28 12:31:03.065  7642  7642 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,07-28 12:31:03.065  7642  7642 D SapService: Received start request. Starting profile...
,07-28 12:31:03.065  7642  7642 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-28 12:31:03.065  7642  7642 I bluedroid: get_profile_interface sap
07-28 12:31:03.065  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
,07-28 12:31:03.065  7642  7642 E BluetoothAdapterService(421963855): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
07-28 12:31:03.065  7642  7642 D HeadsetStateMachine: Try to query the phonestate on bind
,07-28 12:31:03.065  1409  3065 I Telecom : BluetoothPhoneService: queryPhoneState
,07-28 12:31:03.065  1409  1409 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-28 12:31:03.065  7642  7642 D HeadsetStateMachine: Proxy object connected
,07-28 12:31:03.065  7642  7642 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
07-28 12:31:03.075  7642  7642 D HeadsetPhoneState: sendDeviceDataStateChanged
,07-28 12:31:03.075  7642  7642 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-28 12:31:03.075  7642  7642 E BluetoothAdapterService(421963855): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
07-28 12:31:03.075  7642  7642 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-28 12:31:03.075  7642  7642 D BluetoothA2dp: Proxy object connected
07-28 12:31:03.075  7642  7642 D BluetoothAdapterService: Bluetooth A2dp source service connected
07-28 12:31:03.075  7642  8143 D HeadsetStateMachine: Disconnected process message: 11
,07-28 12:31:03.075  7642  8143 D HeadsetStateMachine: Disconnected process message: 18
07-28 12:31:03.075  7642  8143 D HeadsetStateMachine: Disconnected process message: 10
07-28 12:31:03.075  7642  8143 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-28 12:31:03.075  7642  8143 D HeadsetStateMachine: Disconnected process message: 11
,07-28 12:31:03.075  7642  7642 E BluetoothAdapterService(421963855): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,07-28 12:31:03.075  7642  7642 E BluetoothAdapterService(421963855): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-28 12:31:03.075  7642  7642 E BluetoothAdapterService(421963855): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
07-28 12:31:03.075  7642  7642 E BluetoothAdapterService(421963855): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,07-28 12:31:03.075  7642  7642 E BluetoothAdapterService(421963855): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,07-28 12:31:03.075  7642  7642 E BluetoothAdapterService(421963855): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
07-28 12:31:03.075  7642  8116 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
07-28 12:31:03.075  7642  8116 I bluedroid: enable
,07-28 12:31:03.075  7642  8151 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-28 12:31:03.075  7642  8116 I bt_hci_bdroid: init
,07-28 12:31:03.085  7642  8116 I bt_vendor: init
07-28 12:31:03.085  7642  8116 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-28 12:31:03.085  7642  8116 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-28 12:31:03.085  7642  8116 D bt_userial: userial_init
07-28 12:31:03.085  7642  8116 D bt_vendor: op for 5
07-28 12:31:03.085  7642  8116 D bt_vendor: op for 0
,07-28 12:31:03.085  7642  8116 D bt_upio : upio_set_bluetooth_power(on: 0)
07-28 12:31:03.085  7642  8116 D bt_upio : is_emulator_context : 0
07-28 12:31:03.085  7642  8116 D bt_upio : is_rfkill_disabled ? [0]
07-28 12:31:03.085  7642  8116 D bt_upio : is_rfkill_disabled ? [0]
,07-28 12:31:03.085  7642  8116 D bt_vendor: op for 0
07-28 12:31:03.085  7642  8116 D bt_upio : upio_set_bluetooth_power(on: 1)
07-28 12:31:03.085  7642  8116 D bt_upio : is_emulator_context : 0
07-28 12:31:03.085  7642  8116 D bt_upio : is_rfkill_disabled ? [0]
,07-28 12:31:03.085  7642  8153 D bt_vendor: op for 3
07-28 12:31:03.085  7642  8153 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-28 12:31:03.085  7642  8153 I bt_userial_vendor: userial_vendor_open():UART is setup
07-28 12:31:03.085  7642  8153 I bt_userial_vendor: device fd = 66 open
,07-28 12:31:03.085  7642  8153 D bt_vendor: op for 1
07-28 12:31:03.085  7642  8153 E bt_hwcfg: Start CFG HW, HCI reset
07-28 12:31:03.085  7642  8154 D bt_userial: Entering userial_read_thread()
,07-28 12:31:03.165  7642  8153 E bt_hwcfg: Read Local Name after HCI reset
,07-28 12:31:03.195  7642  8153 D bt_hwcfg: Chipset BCM4335C0
,07-28 12:31:03.195  7642  8153 D bt_hwcfg: Target name = [BCM4335C0]
,07-28 12:31:03.195  7642  8153 I bt_hwcfg: module_type[semco].
07-28 12:31:03.195  7642  8153 I bt_hwcfg: not ZERO...
07-28 12:31:03.195  7642  8153 I bt_hwcfg: module_type[semco] is invalid.
,07-28 12:31:03.195  7642  8153 E bt_hwcfg: patchram path ORG . BCM4335C0
07-28 12:31:03.195  7642  8153 E bt_hwcfg: patchram path ORG .. BCM4335C0
07-28 12:31:03.195  7642  8153 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
07-28 12:31:03.195  7642  8153 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
07-28 12:31:03.195  7642  8153 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
07-28 12:31:03.195  7642  8153 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
07-28 12:31:03.195  7642  8153 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335C0
07-28 12:31:03.195  7642  8153 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559_wisol.hcd BCM4335C0
07-28 12:31:03.195  7642  8153 E bt_hwcfg: fw ver (org)0.0
07-28 12:31:03.195  7642  8153 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
07-28 12:31:03.195  7642  8153 E bt_hwcfg: Remove module rev, try again BCM4335
07-28 12:31:03.195  7642  8153 D bt_hwcfg: Target name = [BCM4335]
,07-28 12:31:03.195  7642  8153 I bt_hwcfg: module_type[semco].
07-28 12:31:03.195  7642  8153 I bt_hwcfg: not ZERO...
07-28 12:31:03.195  7642  8153 I bt_hwcfg: module_type[semco] is invalid.
07-28 12:31:03.195  7642  8153 E bt_hwcfg: patchram path ORG . BCM4335
07-28 12:31:03.195  7642  8153 E bt_hwcfg: patchram path ORG .. BCM4335
07-28 12:31:03.195  7642  8153 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335
07-28 12:31:03.195  7642  8153 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
07-28 12:31:03.195  7642  8153 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335
,07-28 12:31:03.195  7642  8153 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
07-28 12:31:03.195  7642  8153 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335
07-28 12:31:03.195  7642  8153 I bt_hwcfg: patch(org) : bcm4335_V0111.0559.hcd
07-28 12:31:03.195  7642  8153 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4335_V0111.0559.hcd
07-28 12:31:03.195  7642  8153 E bt_hwcfg: ORG patchram base 0111
07-28 12:31:03.195  7642  8153 E bt_hwcfg: ORG patchram minor 0559
07-28 12:31:03.195  7642  8153 E bt_hwcfg: fw ver (org)111.559
07-28 12:31:03.195  7642  8153 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4335_V0111.0559.hcd
,07-28 12:31:03.215  7642  8153 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-28 12:31:03.215  7642  8153 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:31:03.725  7642  8153 I bt_hwcfg: bt vendor lib: set UART baud 115200,
,07-28 12:31:03.725  7642  8153 I bt_hwcfg: FW Download delta = 563273
,07-28 12:31:03.725  7642  8153 D bt_hwcfg: Settlement delay -- 100 ms
07-28 12:31:03.725  7642  8153 I bt_hwcfg: Setting fw settlement delay to 100 ,
,07-28 12:31:03.835  7642  8153 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:31:03.865  7642  8153 I bt_hwcfg: vendor lib fwcfg completed
,07-28 12:31:03.885  7642  8151 I         : BTE_InitTraceLevels -- TRC_HCI
,07-28 12:31:03.885  7642  8151 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-28 12:31:03.885  7642  8151 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 12:31:03.885  7642  8151 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 12:31:03.885  7642  8151 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-28 12:31:03.885  7642  8151 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 12:31:03.885  7642  8151 I         : BTE_InitTraceLevels -- TRC_BNEP
07-28 12:31:03.885  7642  8151 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 12:31:03.885  7642  8151 I         : BTE_InitTraceLevels -- TRC_GAP
,07-28 12:31:03.885  7642  8151 I         : BTE_InitTraceLevels -- TRC_PAN
07-28 12:31:03.885  7642  8151 I         : BTE_InitTraceLevels -- TRC_SAP
07-28 12:31:03.885  7642  8151 I         : BTE_InitTraceLevels -- TRC_SDP
07-28 12:31:03.885  7642  8151 I         : BTE_InitTraceLevels -- TRC_GATT
,07-28 12:31:03.885  7642  8151 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 12:31:03.885  7642  8151 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 12:31:03.885  7642  8151 I         : BTE_InitTraceLevels -- TRC_BTIF
07-28 12:31:03.885  7642  8151 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,07-28 12:31:04.115  7642  8151 W bt-l2cap: l2c_link_processs_ble_num_bufs 15
,07-28 12:31:04.115  7642  8151 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa1addb5d 
,07-28 12:31:04.115  7642  8151 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa1addb5d 
,07-28 12:31:04.335  7642  8119 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 1 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,07-28 12:31:04.335  7642  8119 E bt-btif : Calling BTA_HhEnable
,07-28 12:31:04.335  7642  8119 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,07-28 12:31:04.335  7642  8119 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,07-28 12:31:04.335  7642  8119 E BluetoothServiceJni: populateRssiValuesNative
,07-28 12:31:04.345  7642  8119 I bluedroid: getModelRssiValues
,07-28 12:31:04.345  7642  8119 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,07-28 12:31:04.345  7642  8119 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-28 12:31:04.345   937   937 D SettingsProvider: name = bluetooth_name
,07-28 12:31:04.345  7642  8119 D BluetoothAdapterProperties: Name is: Note3-1
,07-28 12:31:04.355  7642  8119 D BluetoothAdapterProperties: Scan Mode:20
,07-28 12:31:04.355  7642  8119 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 12:31:04.355  7642  8119 D BluetoothAdapterProperties: LE Address is:E0:B7:20:3E:93:BC
,07-28 12:31:04.355  7642  8153 D bt_vendor: op for 2
,07-28 12:31:04.355  7642  8153 D bt_vendor: op for 6
,07-28 12:31:04.355  7642  8153 D bt_vendor: op for 7
,07-28 12:31:04.355  7642  8153 D bt_upio : proc btwrite assertion
,07-28 12:31:04.365  7642  8119 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,07-28 12:31:04.365  7642  8119 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,07-28 12:31:04.365  7642  8153 D bt_vendor: op for 7
,07-28 12:31:04.365  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.365  7642  8119 E bt-btif : btif_sock_init: !radio_req && !rfc_init
07-28 12:31:04.365  7642  8153 D bt_vendor: op for 7
,07-28 12:31:04.365  7642  8153 D bt_upio : BT_WAKE is asserted already
07-28 12:31:04.365  7642  8119 E bt-btif : btif_sock_init: !vhci_init
,07-28 12:31:04.365  7642  8119 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,07-28 12:31:04.365  7642  8119 D IOP_DB_BT: db_open: db_open : handle 3026739216l, read 14063 bytes onto local cache
07-28 12:31:04.365  7642  8119 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,07-28 12:31:04.365  7642  8119 D IOP_DB_BT: db_query: result 1
07-28 12:31:04.365  7642  8119 I         : iop_db_open: iop_db_open status 0
,07-28 12:31:04.365  7642  8119 D bte_conf: Device ID record 1 : primary
,07-28 12:31:04.365  7642  8119 D bte_conf:   vendorId            = 0075
07-28 12:31:04.365  7642  8119 D bte_conf:   vendorIdSource      = 0001
07-28 12:31:04.365  7642  8119 D bte_conf:   product             = 0100
07-28 12:31:04.365  7642  8119 D bte_conf:   version             = 0200
,07-28 12:31:04.365  7642  8119 D bte_conf:   clientExecutableURL = 
07-28 12:31:04.365  7642  8119 D bte_conf:   serviceDescription  = 
07-28 12:31:04.365  7642  8119 D bte_conf:   documentationURL    = 
07-28 12:31:04.365  7642  8119 D bte_conf: bte_load_did_conf no section named DID2.
,07-28 12:31:04.375  7642  8116 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,07-28 12:31:04.375  7642  8116 D BluetoothAdapterProperties: ScanMode =  20
07-28 12:31:04.375  7642  8116 D BluetoothAdapterProperties: State =  11
,07-28 12:31:04.375   937  1242 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-28 12:31:04.375  7642  8116 D BluetoothAdapterProperties: Setting state to 12
,07-28 12:31:04.375  7642  8116 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-28 12:31:04.375  7642  8119 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-28 12:31:04.375  7642  8153 E bt_h4   : vendor lib postload completed
,07-28 12:31:04.375  7642  8153 D bt_vendor: op for 7
07-28 12:31:04.375  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.375   937  1242 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,07-28 12:31:04.375   937  1242 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-28 12:31:04.385  7642  8153 D bt_vendor: op for 7
07-28 12:31:04.385  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.385   937  1242 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:31:04.385   937  1242 D SettingsProvider: selectionArgs: false
,07-28 12:31:04.385  7642  8153 D bt_vendor: op for 7
07-28 12:31:04.385  7642  8153 D bt_upio : BT_WAKE is asserted already
07-28 12:31:04.385   937  1242 D SettingsProvider: selectionArgs: 1002
,07-28 12:31:04.385   937  1242 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-28 12:31:04.385   937  1242 D SettingsProvider: ret = -1
,07-28 12:31:04.385  7642  8153 D bt_vendor: op for 7
07-28 12:31:04.385  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.385  7642  8116 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:31:04.385  7642  8116 D BluetoothAdapterService: updateAdapterState state is 12
,07-28 12:31:04.385  7642  8153 D bt_vendor: op for 7
,07-28 12:31:04.385  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.385  7642  8153 D bt_vendor: op for 7
,07-28 12:31:04.385  7642  8153 D bt_upio : BT_WAKE is asserted already
07-28 12:31:04.385  7642  8119 D BluetoothAdapterProperties: Scan Mode:21
07-28 12:31:04.385  7642  8119 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 12:31:04.385  7642  8153 D bt_vendor: op for 7
,07-28 12:31:04.385  7642  8153 D bt_upio : BT_WAKE is asserted already
07-28 12:31:04.395   937  1242 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:31:04.395  7642  8153 D bt_vendor: op for 7
,07-28 12:31:04.395  7642  8153 D bt_upio : BT_WAKE is asserted already
07-28 12:31:04.395   937  1242 D ActivityManager: caller:android.app.ApplicationThreadProxy@3fc60e13, r.packageName :com.android.bluetooth
,07-28 12:31:04.395  7642  8153 D bt_vendor: op for 7
07-28 12:31:04.395  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.395  7642  8153 D bt_vendor: op for 7
,07-28 12:31:04.395  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.395  7642  8153 D bt_vendor: op for 7
,07-28 12:31:04.395  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.405  7642  8153 D bt_vendor: op for 7
,07-28 12:31:04.405  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.405  7642  8153 D bt_vendor: op for 7
07-28 12:31:04.405  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.405  7642  8153 D bt_vendor: op for 7
07-28 12:31:04.405  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.415  7642  8153 D bt_vendor: op for 7
,07-28 12:31:04.415  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.415  7642  7642 I BluetoothPbapService: Handler(): got msg=1
,07-28 12:31:04.415  7642  8153 D bt_vendor: op for 7
,07-28 12:31:04.415  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.415   937  1556 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-28 12:31:04.415  7642  8153 D bt_vendor: op for 7
,07-28 12:31:04.415  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.415  7642  8153 D bt_vendor: op for 7
,07-28 12:31:04.415  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.415  7642  8153 D bt_vendor: op for 7
,07-28 12:31:04.415  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.425  7642  7642 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-28 12:31:04.425  7642  8153 D bt_vendor: op for 7
07-28 12:31:04.425  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.425  1315  7510 D BluetoothPbap: onBluetoothStateChange: up=true
,07-28 12:31:04.425  7642  8153 D bt_vendor: op for 7
07-28 12:31:04.425  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.425   937  1061 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
07-28 12:31:04.425  7642  8116 D BluetoothAdapterService: Autoconnection is available 
07-28 12:31:04.425  7642  8116 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-28 12:31:04.425  7642  8116 D BluetoothAdapterService: starting service from this receiver
,07-28 12:31:04.425  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:04.425  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:04.425  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:04.425  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:31:04.425  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:04.425  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:04.425  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:04.425  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:31:04.425  7642  8153 D bt_vendor: op for 7
07-28 12:31:04.425  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.425   937  1648 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:31:04.425   937  1648 D ActivityManager: caller:android.app.ApplicationThreadProxy@11f9786f, r.packageName :com.android.bluetooth
,07-28 12:31:04.425  7642  8153 D bt_vendor: op for 7
07-28 12:31:04.425  7642  8153 D bt_upio : BT_WAKE is asserted already
07-28 12:31:04.425  7429  7429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:31:04.435  7642  8116 I BluetoothAdapterState: Entering On State from state = 11
,07-28 12:31:04.435  7642  8167 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-28 12:31:04.435  1315  1315 D BluetoothPbap: Proxy object connected
07-28 12:31:04.435  1315  1315 D PbapServerProfile: Bluetooth service connected
,07-28 12:31:04.435  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:04.435  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:04.435  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:04.435  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:31:04.435  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:04.435  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:04.435  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:04.435  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:31:04.435  7429  7429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:31:04.445  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:04.445  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:04.445  7642  8167 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:31:04.445   937  1061 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:31:04.445  1409  1420 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:31:04.445  7642  8153 D bt_vendor: op for 7
07-28 12:31:04.445  7642  8153 D bt_upio : BT_WAKE is asserted already
07-28 12:31:04.445  7642  8167 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[73]}
,07-28 12:31:04.445   937  1061 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-28 12:31:04.445  7642  8167 D BluetoothSocket: bindListen(), new LocalSocket 
07-28 12:31:04.445  7642  8167 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:31:04.445  7642  8167 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28d4af58
07-28 12:31:04.445  7642  8167 D BluetoothSocket: channel: 19
07-28 12:31:04.445  7642  8167 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-28 12:31:04.445  1409  3064 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:31:04.445   937  1061 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:31:04.445  3158  3170 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:31:04.445   937  1061 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:31:04.445   937  1061 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:31:04.445  1315  1325 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-28 12:31:04.445   937   937 D BluetoothA2dp: Proxy object connected
,07-28 12:31:04.455   937  1061 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,07-28 12:31:04.455  1315  1315 D BluetoothInputDevice: Proxy object connected
07-28 12:31:04.455  1315  1315 D HidProfile: Bluetooth service connected
,07-28 12:31:04.455  1315  7510 D BluetoothPan: Binding service...
,07-28 12:31:04.455   937  1061 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-28 12:31:04.455  3158  3167 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:31:04.455  1315  1315 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:31:04.455  1315  1315 D PanProfile: Bluetooth service connected
07-28 12:31:04.455   937  1061 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:31:04.455  3158  3158 D BluetoothA2dp: Proxy object connected
,07-28 12:31:04.455   937  1061 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:31:04.455   937  1061 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:31:04.455   937  1061 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:31:04.465  1409  1438 E BluetoothHeadset: BluetoothHeadset service is binded
07-28 12:31:04.465   937  1061 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-28 12:31:04.465  1429  3551 E BluetoothHeadset: BluetoothHeadset service is binded
07-28 12:31:04.465  1315  1337 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
07-28 12:31:04.465  1315  1337 D Bluetoothsap: onBluetoothStateChange: up=true
07-28 12:31:04.465   937  1061 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
07-28 12:31:04.465  1315  1337 D Bluetoothsap: Binding service...
07-28 12:31:04.465  1315  1337 D Bluetoothsap: bindService called to Bluetooth SAP Service
07-28 12:31:04.465  7642  8019 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:31:04.465  1315  1315 D Bluetoothsap: BluetoothSAP Proxy object connected
,07-28 12:31:04.465  1315  1315 D SapProfile: Bluetooth service connected
07-28 12:31:04.465  1315  1315 D Bluetoothsap: getConnectedDevices()
07-28 12:31:04.465  1315  1325 D BluetoothMap: onBluetoothStateChange: up=true
,07-28 12:31:04.465   937  1061 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,07-28 12:31:04.465  1315  1337 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:31:04.465  1315  1315 D BluetoothMap: Proxy object connected
07-28 12:31:04.465  1315  1315 D MapProfile: Bluetooth service connected
07-28 12:31:04.475   937  1061 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:31:04.475  1315  1315 D BluetoothA2dp: Proxy object connected
07-28 12:31:04.475  1315  1315 D A2dpProfile: Bluetooth service connected
,07-28 12:31:04.475   937  1061 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-28 12:31:04.475  1315  1325 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:31:04.475   937  1061 D BluetoothPan: Binding service...
07-28 12:31:04.475   937  1061 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
07-28 12:31:04.475  1315  1315 D HeadsetProfile: Bluetooth service connected
,07-28 12:31:04.475   937   937 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:31:04.475   937  1061 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,07-28 12:31:04.475  1194  1194 D BluetoothTile:  onBluetoothStateChange:
,07-28 12:31:04.475   937   937 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:04.475   937   937 I InputMethodManagerService: [BT Setting State] State =12
07-28 12:31:04.475   937   937 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-28 12:31:04.475  1409  1409 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@397a79c5, true
,07-28 12:31:04.475  1409  1409 D BluetoothHeadset: registerMessageListener
,07-28 12:31:04.475  1194  1194 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-28 12:31:04.475  1194  1194 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:04.475  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:04.475  7571  7571 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:04.485  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:04.485  1696  1696 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
07-28 12:31:04.485   937  1434 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:31:04.485   937  1434 D ActivityManager: caller:android.app.ApplicationThreadProxy@269e53e0, r.packageName :com.google.android.gms
,07-28 12:31:04.485  7642  7656 D HeadsetService: registerMessageListener
,07-28 12:31:04.485  7642  7656 D HeadsetService: registerMessageListener
07-28 12:31:04.485  7642  8143 D HeadsetStateMachine: Disconnected process message: 70
07-28 12:31:04.485  7642  8143 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@260ba8b1
,07-28 12:31:04.485  1409  1409 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-28 12:31:04.485  1409  1409 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,07-28 12:31:04.485   937  1061 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,07-28 12:31:04.485  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:04.485  1315  1315 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,07-28 12:31:04.485  7642  8143 D HeadsetStateMachine: Disconnected process message: 9
,07-28 12:31:04.485  1194  1583 D BluetoothTile:  handleUpdatestate:false name:null
07-28 12:31:04.485  7642  8143 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
07-28 12:31:04.485  1194  1583 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:31:04.485  1315  1315 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,07-28 12:31:04.485   937  1537 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:31:04.485   937  1147 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,07-28 12:31:04.495   311   311 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
07-28 12:31:04.495   311   311 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-28 12:31:04.495   311   311 V voice   : voice_set_parameters: exit with code(-2)
07-28 12:31:04.495   311   311 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-28 12:31:04.495   311   311 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-28 12:31:04.495   311   311 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-28 12:31:04.495  1194  1194 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-28 12:31:04.495   311   311 V audio_hw_primary: adev_set_parameters: exit
07-28 12:31:04.495  7642  8143 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,07-28 12:31:04.495  7642  8187 D BluetoothMapMasInstance: set MAP SDP message type : 1
,07-28 12:31:04.495  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:31:04.495   937  1253 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-28 12:31:04.495   937  1253 D ActivityManager: caller:android.app.ApplicationThreadProxy@2eedf53f, r.packageName :com.android.settings
,07-28 12:31:04.505  7642  8187 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:31:04.505   937  1537 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-28 12:31:04.505   937  1537 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-28 12:31:04.505   937  1537 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-28 12:31:04.505   937   937 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-28 12:31:04.505   937  1537 D BatteryService: stay LED for fully charged
,07-28 12:31:04.505  7642  8187 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
07-28 12:31:04.505  7642  8153 D bt_vendor: op for 7
07-28 12:31:04.505  7642  8153 D bt_upio : BT_WAKE is asserted already
07-28 12:31:04.505  7642  8187 D BluetoothSocket: bindListen(), new LocalSocket 
,07-28 12:31:04.505  1315  1315 D DockEventReceiver: finishStartingService: stopping service
07-28 12:31:04.505  7642  8187 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:31:04.505   937   937 I MotionRecognitionService: Plugged
07-28 12:31:04.505   937   937 I MotionRecognitionService: setPowerConnected  = true
07-28 12:31:04.505  7642  8187 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a42f196
07-28 12:31:04.505  7642  8187 D BluetoothSocket: channel: 5
,07-28 12:31:04.505  7642  7642 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-28 12:31:04.505  7642  8143 D HeadsetStateMachine: Disconnected process message: 10
,07-28 12:31:04.505  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:31:04.515  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
07-28 12:31:04.515  7642  7642 D BtConfig.SecureMode: isSecureModeOn:false
,07-28 12:31:04.515  1194  1194 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-28 12:31:04.515  1194  1194 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-28 12:31:04.515  1194  1194 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:31:04.515  1194  1194 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-28 12:31:04.515  1194  1194 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:31:04.515   937  1253 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:31:04.515  1194  1194 D KeyguardUpdateMonitor: handleBatteryUpdate
07-28 12:31:04.515   937  1253 D ActivityManager: caller:android.app.ApplicationThreadProxy@28db9355, r.packageName :com.android.bluetooth
,07-28 12:31:04.535   937  1242 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-28 12:31:04.545  7642  8193 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:31:04.555  7642  8153 D bt_vendor: op for 7
07-28 12:31:04.555  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:04.555  7642  8193 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
07-28 12:31:04.555  7642  8193 D BluetoothSocket: bindListen(), new LocalSocket 
07-28 12:31:04.555  7642  8193 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:31:04.555  7642  8193 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38349122
,07-28 12:31:04.555  7642  8193 D BluetoothSocket: channel: 12
07-28 12:31:04.555  7642  8193 I BtOppRfcommListener: Accept thread started.
,07-28 12:31:04.575  1823  1823 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:31:04.575   937  1737 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:31:04.575   937  1737 D ActivityManager: caller:android.app.ApplicationThreadProxy@3ae19a36, r.packageName :com.google.android.gms
,07-28 12:31:04.585  1823  8197 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-28 12:31:04.585  1823  1823 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:31:04.595   937  1737 D ActivityManager: caller:android.app.ApplicationThreadProxy@16c185d3, r.packageName :com.google.android.gms
,07-28 12:31:04.605  1823  8197 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-28 12:31:05.015   303   303 E SMD     : DCD ON
,07-28 12:31:05.795  7429  7490 D BluetoothAdapter: disable()
,07-28 12:31:05.795   937  1556 D SettingsProvider: name = bluetooth_on
,07-28 12:31:05.815  7642  8116 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,07-28 12:31:05.815  7642  8116 D BluetoothAdapterProperties: Setting state to 13
,07-28 12:31:05.815  7642  8116 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-28 12:31:05.825  7642  8116 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,07-28 12:31:05.825  7642  8116 D BluetoothAdapterService: updateAdapterState state is 13
,07-28 12:31:05.825   937  1253 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:31:05.825   937  1253 D ActivityManager: caller:android.app.ApplicationThreadProxy@2942e809, r.packageName :com.android.bluetooth
,07-28 12:31:05.825  7642  8116 D BluetoothAdapterService: Autoconnection is available 
,07-28 12:31:05.825  7642  8116 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
07-28 12:31:05.825  7642  8116 D BluetoothAdapterService: terminating service from this receiver
,07-28 12:31:05.825  7642  8116 D BluetoothAdapterProperties: onBluetoothDisable()
,07-28 12:31:05.825   937  3040 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-28 12:31:05.825  7642  8153 D bt_vendor: op for 7
,07-28 12:31:05.835  7642  8153 D bt_upio : BT_WAKE is asserted already
07-28 12:31:05.835  7642  8116 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,07-28 12:31:05.835  7642  8153 D bt_vendor: op for 7
,07-28 12:31:05.835  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:05.835  7642  8153 D bt_vendor: op for 7
,07-28 12:31:05.835  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:05.835  7642  8119 D BluetoothAdapterProperties: Scan Mode:20
,07-28 12:31:05.835  7642  8116 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-28 12:31:05.835  7642  8116 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,07-28 12:31:05.835  7642  8116 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,07-28 12:31:05.835  7642  8116 E bt-btif : cmd socket is not created
,07-28 12:31:05.835  7642  8193 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-28 12:31:05.835  7642  8116 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-28 12:31:05.845  7642  8153 D bt_vendor: op for 7
07-28 12:31:05.845  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:05.845  7642  8151 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
07-28 12:31:05.845  7642  8151 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-28 12:31:05.845  7642  8151 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-28 12:31:05.845  7642  8151 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:31:05.845  7642  8151 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,07-28 12:31:05.845  7642  8153 D bt_vendor: op for 7
07-28 12:31:05.845  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:05.845  7642  8153 D bt_vendor: op for 7
,07-28 12:31:05.845  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:05.845  7642  8153 D bt_vendor: op for 7
,07-28 12:31:05.845  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:05.845  7642  8153 D bt_vendor: op for 7
,07-28 12:31:05.845  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:05.855  7642  7642 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,07-28 12:31:05.855  7642  7642 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@14e657b3, channel: 19, state: LISTENING
,07-28 12:31:05.855  7642  7642 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@14e657b3, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28d4af58, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c3e1170mSocket: android.net.LocalSocket@1c5dbce9 impl:android.net.LocalSocketImpl@28ae9d6e fd:FileDescriptor[73]
07-28 12:31:05.855  7642  7642 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1c5dbce9 impl:android.net.LocalSocketImpl@28ae9d6e fd:FileDescriptor[73]
,07-28 12:31:05.855  7642  8153 D bt_vendor: op for 7
,07-28 12:31:05.855  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:05.855  7642  8153 D bt_vendor: op for 7
,07-28 12:31:05.855  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:05.855  7642  8153 D bt_vendor: op for 7
,07-28 12:31:05.855  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:05.855  7642  8153 D bt_vendor: op for 7
,07-28 12:31:05.855  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:05.865  7642  8153 D bt_vendor: op for 7
07-28 12:31:05.865  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:05.865  7642  8153 D bt_vendor: op for 7
,07-28 12:31:05.865  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:05.865  7642  8153 D bt_vendor: op for 7
07-28 12:31:05.865  7642  8153 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:05.865  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:31:05.865  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:05.865  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:05.865  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:05.865  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:31:05.865  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:31:05.865  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:05.865  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:05.865  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:31:05.875  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:31:05.875  7429  7429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:31:05.875  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:31:05.875  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:05.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:05.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:05.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:31:05.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:31:05.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:05.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:05.875  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:31:05.875  7429  7429 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:31:05.875  7429  7429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:31:05.875   937   937 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:05.875  1194  1194 D BluetoothTile:  onBluetoothStateChange:
,07-28 12:31:05.875   937   937 I InputMethodManagerService: [BT Setting State] State =13
,07-28 12:31:05.885  7642  7642 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9cad49c, channel: 5, state: LISTENING
,07-28 12:31:05.885  7642  7642 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@9cad49c, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a42f196, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@4cc3ea5mSocket: android.net.LocalSocket@1eab227a impl:android.net.LocalSocketImpl@17bb0a2b fd:FileDescriptor[75]
07-28 12:31:05.885  7642  7642 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1eab227a impl:android.net.LocalSocketImpl@17bb0a2b fd:FileDescriptor[75]
,07-28 12:31:05.885  7642  7642 I BtOppRfcommListener: stopping Accept Thread
,07-28 12:31:05.885  7642  7642 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1ffe9e88, channel: 12, state: LISTENING
07-28 12:31:05.885  7642  7642 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1ffe9e88, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38349122, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@18e72021mSocket: android.net.LocalSocket@b8ec46 impl:android.net.LocalSocketImpl@2ade1e07 fd:FileDescriptor[78]
07-28 12:31:05.885  7642  7642 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@b8ec46 impl:android.net.LocalSocketImpl@2ade1e07 fd:FileDescriptor[78]
,07-28 12:31:05.885  7642  8193 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-28 12:31:05.885  1194  1194 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-28 12:31:05.885  1194  1194 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:05.885  1194  1583 D BluetoothTile:  handleUpdatestate:false name:null
,07-28 12:31:05.885  1194  1583 D BluetoothTile:  handleUpdatestate:false name:null
,07-28 12:31:05.885  1194  1583 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:31:05.895   937  1253 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:31:05.895   937  1666 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-28 12:31:05.895  1194  1194 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-28 12:31:05.895  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:05.895  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:05.905   937   952 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:31:05.905   937   952 D ActivityManager: caller:android.app.ApplicationThreadProxy@3425ba0e, r.packageName :com.google.android.gms
,07-28 12:31:05.915  1696  1696 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-28 12:31:05.915  7571  7571 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:05.915  1315  1315 D BluetoothPbap: Proxy object disconnected
07-28 12:31:05.915  1315  1315 D PbapServerProfile: Bluetooth service disconnected
07-28 12:31:05.915  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:05.915  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:31:05.915   937  1147 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-28 12:31:05.915   937  1147 D ActivityManager: caller:android.app.ApplicationThreadProxy@21dd23c, r.packageName :com.android.settings
,07-28 12:31:05.935  1315  1315 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:31:05.935  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:31:05.945  7642  8153 D bt_vendor: op for 6
07-28 12:31:05.945  7642  8151 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:31:05.945  7642  8151 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:31:05.945  7642  8151 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:31:05.945  7642  8151 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:31:05.945  7642  8151 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:31:05.945  7642  8151 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:31:05.945  7642  8151 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:31:05.945  7642  8151 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:31:05.945  7642  8151 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:31:05.945  7642  8151 W bt-btif : ag scb idx 1 not allocated
07-28 12:31:05.945  7642  8151 W bt-btif : ag scb idx 2 not allocated
07-28 12:31:05.945  7642  8151 E bt-btif : BTA AG is already disabled, ignoring ...
07-28 12:31:05.945  7642  8154 D bt_userial: RX termination
07-28 12:31:05.945  7642  8154 W bt_userial: select_read return size <=0:-1, exiting userial_read_thread
07-28 12:31:05.945  7642  8154 D bt_userial: Leaving userial_read_thread()
07-28 12:31:05.945  7642  8119 D bt_userial: userial_close_reader Joined userial reader thread: 0
07-28 12:31:05.945  7642  8153 D bt_vendor: op for 9
07-28 12:31:05.945  7642  8153 D bt_hwcfg: hw_epilog_process
07-28 12:31:05.945  7642  8153 D bt_vendor: op for 7
07-28 12:31:05.945  7642  8153 D bt_upio : BT_WAKE is asserted already
07-28 12:31:05.945  7642  8119 D bt_vendor: op for 4
07-28 12:31:05.945  7642  8119 I bt_userial_vendor: device fd = 66 close
,07-28 12:31:05.945  7642  8119 D bt_vendor: op for 0
07-28 12:31:05.945  7642  8119 D bt_upio : upio_set_bluetooth_power(on: 0)
07-28 12:31:05.945  7642  8119 D bt_upio : is_emulator_context : 0
,07-28 12:31:05.945  7642  8119 D bt_upio : is_rfkill_disabled ? [0]
07-28 12:31:05.945  7642  8119 D bt_vendor: cleanup
,07-28 12:31:05.945  7642  8151 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-28 12:31:05.945  7642  8119 I GKI_LINUX: GKI_exit_task 0 done
07-28 12:31:05.945  7642  8119 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,07-28 12:31:05.945  7642  8116 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-28 12:31:05.945  7642  8116 D BtConfig.SecureMode: isSecureModeOn:false
07-28 12:31:05.945  7642  8116 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
07-28 12:31:05.945  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-28 12:31:05.945  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-28 12:31:05.945  7642  8116 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,07-28 12:31:05.955   937  1147 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:31:05.955   937  1147 D ActivityManager: caller:android.app.ApplicationThreadProxy@2487691a, r.packageName :com.android.bluetooth
,07-28 12:31:05.955  7642  7642 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:31:05.955  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-28 12:31:05.955  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-28 12:31:05.955  7642  8116 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
07-28 12:31:05.955  7642  7642 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 12:31:05.955  7642  7642 D BtGatt.GattService: stop()
07-28 12:31:05.955   937  1364 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:31:05.955  7642  7642 D BtGatt.AdvertiseManager: advertise clients cleared
,07-28 12:31:05.955   937  1364 D ActivityManager: caller:android.app.ApplicationThreadProxy@33c9dc4b, r.packageName :com.android.bluetooth
,07-28 12:31:05.955  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
07-28 12:31:05.955  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-28 12:31:05.955  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-28 12:31:05.955  7642  8116 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-28 12:31:05.955   937  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:31:05.955   937  1471 D ActivityManager: caller:android.app.ApplicationThreadProxy@3b13d628, r.packageName :com.android.bluetooth
,07-28 12:31:05.955  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-28 12:31:05.955  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:31:05.955  7642  8116 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-28 12:31:05.955   937   952 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:31:05.955   937   952 D ActivityManager: caller:android.app.ApplicationThreadProxy@3da28f41, r.packageName :com.android.bluetooth
,07-28 12:31:05.955  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-28 12:31:05.955  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-28 12:31:05.955  7642  8116 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-28 12:31:05.955   937  1556 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:31:05.955  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-28 12:31:05.955   937  1556 D ActivityManager: caller:android.app.ApplicationThreadProxy@1322fce6, r.packageName :com.android.bluetooth
07-28 12:31:05.955  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-28 12:31:05.955   937  1666 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:31:05.955  7642  8116 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-28 12:31:05.955   937  1666 D ActivityManager: caller:android.app.ApplicationThreadProxy@ed7f227, r.packageName :com.android.bluetooth
07-28 12:31:05.955  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,07-28 12:31:05.965   937  1737 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:31:05.955  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:31:05.965   937  1737 D ActivityManager: caller:android.app.ApplicationThreadProxy@ee42cd4, r.packageName :com.android.bluetooth
07-28 12:31:05.955  7642  8116 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-28 12:31:05.965  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,07-28 12:31:05.965  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-28 12:31:05.965  7642  8116 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-28 12:31:05.965   937  3040 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:31:05.965   937  3040 D ActivityManager: caller:android.app.ApplicationThreadProxy@1cc7de7d, r.packageName :com.android.bluetooth
,07-28 12:31:05.965  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:31:05.965  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:31:05.965  7642  8116 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:31:05.965  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:31:05.965  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-28 12:31:05.965  7642  8116 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:31:05.965  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
07-28 12:31:05.965  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-28 12:31:05.965  7642  8116 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-28 12:31:05.965  7642  8116 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,07-28 12:31:05.965  7642  8116 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-28 12:31:05.965  7642  8116 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-28 12:31:05.965  7642  7642 E BluetoothAdapterService(421963855): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
07-28 12:31:05.965  7642  8116 D BluetoothAdapterState: Stopping profile services that were post enabled
07-28 12:31:05.965  7642  7642 D HeadsetService: Received stop request...Stopping profile...
,07-28 12:31:05.965  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
,07-28 12:31:05.965   937   937 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,07-28 12:31:05.965  7571  7571 W BluetoothHeadset: Proxy not attached to service
,07-28 12:31:05.965  7642  7642 D A2dpService: Received stop request...Stopping profile...
07-28 12:31:05.965  7642  7642 V Avrcp   : doQuit
07-28 12:31:05.965  7642  8145 D A2dpStateMachine: Exit Disconnected: -1
,07-28 12:31:05.965  7642  7642 D Avrcp   : Unregistering previous receiver
,07-28 12:31:05.975  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
,07-28 12:31:05.975  1315  1315 D HeadsetProfile: Bluetooth service disconnected
07-28 12:31:05.975   937   937 D BluetoothA2dp: Proxy object disconnected
07-28 12:31:05.975   937   937 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,07-28 12:31:05.975  7642  7642 D HidService: Received stop request...Stopping profile...
07-28 12:31:05.975  7642  7642 D HidService: Stopping Bluetooth HidService
07-28 12:31:05.975  7642  7642 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:31:05.975  7642  7642 W bt-btif : cleanup: HH disabling or disabled already, status = 0
07-28 12:31:05.975  7642  7642 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:31:05.975  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
,07-28 12:31:05.975  3158  3158 D BluetoothA2dp: Proxy object disconnected
,07-28 12:31:05.975  7642  7642 D HealthService: Received stop request...Stopping profile...
07-28 12:31:05.975  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
,07-28 12:31:05.975  7642  7642 D PanService: Received stop request...Stopping profile...
07-28 12:31:05.975  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
,07-28 12:31:05.975   937   937 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-28 12:31:05.975  7642  7642 D BluetoothMapService: Received stop request...Stopping profile...
,07-28 12:31:05.975  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
,07-28 12:31:05.975  1315  1315 D BluetoothA2dp: Proxy object disconnected
07-28 12:31:05.975  7642  7642 D SapService: Received stop request...Stopping profile...
07-28 12:31:05.975  7642  7642 D SapService: Stopping Bluetooth SapService
07-28 12:31:05.975  7642  7642 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1926a84f
07-28 12:31:05.975  1315  1315 D A2dpProfile: Bluetooth service disconnected
,07-28 12:31:05.975  1315  1315 D BluetoothInputDevice: Proxy object disconnected
07-28 12:31:05.975  1315  1315 D HidProfile: Bluetooth service disconnected
07-28 12:31:05.975  7642  7642 E BluetoothAdapterService(421963855): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
07-28 12:31:05.975  7642  7642 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:31:05.975  7642  7642 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,07-28 12:31:05.975  1315  1315 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:31:05.975  7642  7642 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:31:05.975  7642  7642 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:31:05.985  7642  7642 E BluetoothAdapterService(421963855): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,07-28 12:31:05.985  7642  7642 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:31:05.985  7642  7642 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-28 12:31:05.985  7642  7642 D BluetoothA2dp: Proxy object disconnected
07-28 12:31:05.985  7642  7642 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
07-28 12:31:05.985  1315  1315 D PanProfile: Bluetooth service disconnected
07-28 12:31:05.985  1315  1315 D BluetoothMap: Proxy object disconnected
07-28 12:31:05.985  1315  1315 D MapProfile: Bluetooth service disconnected
07-28 12:31:05.985  7642  8146 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-28 12:31:05.985  1315  1315 D Bluetoothsap: BluetoothSAP Proxy object disconnected
07-28 12:31:05.985  1315  1315 D SapProfile: Bluetooth service disconnected
07-28 12:31:05.985  7642  7642 I GKI_LINUX: GKI_exit_task 2 done
07-28 12:31:05.985  7642  7642 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-28 12:31:05.985  7642  7642 V Avrcp   : cleanup
07-28 12:31:05.985  7642  7642 E BluetoothAdapterService(421963855): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-28 12:31:05.985  7642  7642 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:31:05.985  7642  7642 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-28 12:31:05.985  7642  7642 E BluetoothAdapterService(421963855): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-28 12:31:05.985  7642  7642 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:31:05.985  7642  7642 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-28 12:31:05.985  7642  7642 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,07-28 12:31:05.985  7642  7642 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:31:05.985  7642  7642 E BluetoothAdapterService(421963855): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
07-28 12:31:05.985  7642  7642 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:31:05.985  7642  7642 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-28 12:31:05.985  7642  7642 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:31:05.985  7642  7642 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-28 12:31:05.985  7642  7642 E BluetoothAdapterService(421963855): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
07-28 12:31:05.985  7642  7642 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-28 12:31:05.985  7642  7642 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
07-28 12:31:05.985  7642  7642 E BluetoothAdapterService(421963855): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,07-28 12:31:05.985  7642  8116 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
07-28 12:31:05.985  7642  8116 D BluetoothAdapterProperties: Setting state to 10
07-28 12:31:05.985  7642  8116 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-28 12:31:05.985  7642  8116 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:31:05.985  7642  8116 D BluetoothAdapterService: updateAdapterState state is 10
07-28 12:31:05.985  7642  7642 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,07-28 12:31:05.985  7642  7642 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
07-28 12:31:05.985  7642  8116 D BluetoothAdapterService: Autoconnection is available 
07-28 12:31:05.985  7642  8116 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
07-28 12:31:05.985  7642  8116 I BluetoothAdapterState: Entering OffState
07-28 12:31:05.985  1315  1325 D BluetoothPbap: onBluetoothStateChange: up=false
,07-28 12:31:05.985   937  1061 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:31:05.985  1315  1337 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-28 12:31:05.985  3158  3167 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:31:05.985  1315  1325 D Bluetoothsap: onBluetoothStateChange: up=false
07-28 12:31:05.985  1315  1325 D Bluetoothsap: Unbinding service...
,07-28 12:31:05.985  7642  7656 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:31:05.995  1315  1337 D BluetoothMap: onBluetoothStateChange: up=false
,07-28 12:31:05.995  1315  7510 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:31:05.995   937  1061 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 14 receivers.
,07-28 12:31:05.995   937  1061 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,07-28 12:31:05.995   937   937 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:05.995   937   937 I InputMethodManagerService: [BT Setting State] State =10
07-28 12:31:05.995   937   937 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-28 12:31:05.995  1194  1194 D BluetoothAdapter: 619609957: getState() :  mService = null. Returning STATE_OFF
07-28 12:31:06.005  1194  1194 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-28 12:31:06.005  1194  1583 D BluetoothAdapter: 619609957: getState() :  mService = null. Returning STATE_OFF
,07-28 12:31:06.005  7642  8119 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-28 12:31:06.005  7642  7642 I GKI_LINUX: GKI_exit_task 1 done
07-28 12:31:06.005  7642  7642 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-28 12:31:06.005  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:06.005  1194  1194 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:06.005  1194  1194 D BluetoothAdapter: 619609957: getState() :  mService = null. Returning STATE_OFF
07-28 12:31:06.005  1823  2361 D BluetoothAdapter: 369937324: getState() :  mService = null. Returning STATE_OFF
,07-28 12:31:06.005  1194  1583 D BluetoothAdapter: 619609957: getState() :  mService = null. Returning STATE_OFF
07-28 12:31:06.005  7571  7571 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:06.005  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:06.005  1194  1583 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:31:06.005  1194  1194 D BluetoothAdapter: 619609957: getState() :  mService = null. Returning STATE_OFF
07-28 12:31:06.005  1823  2361 D BluetoothAdapter: 369937324: getState() :  mService = null. Returning STATE_OFF
07-28 12:31:06.005   937  1253 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:31:06.005  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:06.005   937  1537 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
07-28 12:31:06.005  7642  7642 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-28 12:31:06.005  1194  1194 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
07-28 12:31:06.005  1696  1696 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-28 12:31:06.005  7642  7642 I art     : System.exit called, status: 0
07-28 12:31:06.015  7642  7642 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-28 12:31:06.015  1823  1823 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:31:06.015   937  1471 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:31:06.015   937  1471 D ActivityManager: caller:android.app.ApplicationThreadProxy@38920172, r.packageName :com.google.android.gms
,07-28 12:31:06.025  1823  1823 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:31:06.025  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:31:06.025   937  1147 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-28 12:31:06.025   937  1147 D ActivityManager: caller:android.app.ApplicationThreadProxy@22c789c3, r.packageName :com.android.settings
,07-28 12:31:06.035  1315  1315 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:31:06.035  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:31:06.055   937   954 I ActivityManager: Process com.android.bluetooth (pid 7642)(adj 0) has died(203,1560)
,07-28 12:31:06.065  1823  1823 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:31:06.065   937  1147 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:31:06.065   937  1147 D ActivityManager: caller:android.app.ApplicationThreadProxy@278eff1f, r.packageName :com.google.android.gms
,07-28 12:31:06.065  1823  8235 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-28 12:31:06.075  1823  1823 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:31:06.075   937  3040 D ActivityManager: caller:android.app.ApplicationThreadProxy@2996035, r.packageName :com.google.android.gms
,07-28 12:31:06.085  1823  8235 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-28 12:31:06.145   937  1064 I PowerManagerService: [PWL] Off : 105s ago
,07-28 12:31:06.145   937  1064 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,07-28 12:31:06.145   937  1064 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
07-28 12:31:06.145   937  1064 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=937, ws=null) (elapsedTime=12342)
,07-28 12:31:06.145   937  1064 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=1656)
,07-28 12:31:08.015   303   303 E SMD     : DCD ON
,07-28 12:31:08.915  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:31:08.915  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:31:09.306   349   349 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:31:10.315   349   349 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:31:11.015   303   303 E SMD     : DCD ON
,07-28 12:31:11.315   349   349 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:31:11.725   937  3069 D SSRM:n  : SIOP:: AP = 360, PST = 377, CUR = 450
,07-28 12:31:11.915  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:11.915  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ecb1422 added. We now have 6 listener(s)
07-28 12:31:11.915  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:31:11.915  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:31:11.915  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30e61eb3 added. We now have 7 listener(s)
07-28 12:31:11.915  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:31:11.915  7429  7490 I System.out: IsBluetoothEnabled
,07-28 12:31:11.915  7429  7490 D BluetoothAdapter: disable()
,07-28 12:31:11.925   937   954 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,07-28 12:31:11.925  7429  7490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:11.925  7429  7490 D BluetoothAdapter: enable()
,07-28 12:31:11.925   937   952 W ActivityManager: Permission Denial: getCurrentUser() from pid=7429, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-28 12:31:11.925   937   952 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-28 12:31:11.925   937   952 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7429, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:31:11.925   937   952 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-28 12:31:11.925   937   952 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-28 12:31:11.925   937   952 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-28 12:31:11.925   937   952 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-28 12:31:11.925   937   952 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
07-28 12:31:11.925   937   952 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:31:11.925   937   952 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:31:11.925   937   952 D SettingsProvider: name = bluetooth_on
,07-28 12:31:11.925   937  1061 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:31:11.935   937  1061 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:31:11.935   937  1061 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,07-28 12:31:11.935   937  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:31:11.935   937  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:11.935   937  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:11.935   937  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:31:11.975   937  1061 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=8248 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,07-28 12:31:11.985  8248  8248 E Zygote  : MountEmulatedStorage()
,07-28 12:31:11.985  8248  8248 E Zygote  : v2
07-28 12:31:11.985  8248  8248 I libpersona: KNOX_SDCARD checking this for 1002
07-28 12:31:11.985  8248  8248 I libpersona: KNOX_SDCARD not a persona
,07-28 12:31:11.995  8248  8248 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-28 12:31:11.995  8248  8248 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:31:11.995  8248  8248 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:31:12.035  8248  8248 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:31:12.035  8248  8248 D ActivityThread: Added TimaKeyStore provider
,07-28 12:31:12.045  8248  8248 D ResourcesManager: creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,07-28 12:31:12.055  8248  8248 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
07-28 12:31:12.055  8248  8248 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-28 12:31:12.075  8248  8248 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-28 12:31:12.105  8248  8248 D BtSettings.ProfileConfig: Adding GattService
,07-28 12:31:12.105  8248  8248 D BtSettings.ProfileConfig: Adding HeadsetService
07-28 12:31:12.105  8248  8248 D BtSettings.ProfileConfig: Adding A2dpService
07-28 12:31:12.105  8248  8248 D BtSettings.ProfileConfig: Adding HidService,
07-28 12:31:12.105  8248  8248 D BtSettings.ProfileConfig: Adding HealthService
07-28 12:31:12.105  8248  8248 D BtSettings.ProfileConfig: Adding PanService
,07-28 12:31:12.105  8248  8248 D BtSettings.ProfileConfig: Adding BluetoothMapService
07-28 12:31:12.105  8248  8248 D BtSettings.ProfileConfig: Adding SapService
07-28 12:31:12.105  8248  8248 D BtSettings.ProfileConfig: Adding HeadsetClientService
,07-28 12:31:12.105  8248  8248 D BtSettings.ProfileConfig: Adding A2dpSinkService
07-28 12:31:12.105  8248  8248 D BtSettings.ProfileConfig: Adding SapClientService
07-28 12:31:12.105  8248  8248 D BtSettings.ProfileConfig: Adding HidDevService
,07-28 12:31:12.105  8248  8248 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
07-28 12:31:12.105   937  1556 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
07-28 12:31:12.105   937  1556 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
07-28 12:31:12.105   937  1556 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:31:12.115   937  1556 D SettingsProvider: selectionArgs: false
,07-28 12:31:12.115   937  1556 D SettingsProvider: selectionArgs: 1002
07-28 12:31:12.115   937  1556 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:31:12.115   937  1556 D SettingsProvider: ret = -1
,07-28 12:31:12.115   937  1147 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-28 12:31:12.115   937  1147 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:31:12.115   937  1147 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
07-28 12:31:12.115   937  1147 D SettingsProvider: selectionArgs: false
07-28 12:31:12.115   937  1147 D SettingsProvider: selectionArgs: 1002
,07-28 12:31:12.115   937  1147 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:31:12.115   937  1147 D SettingsProvider: ret = -1
07-28 12:31:12.115   937  1364 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,07-28 12:31:12.115   937  1364 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:31:12.115   937  1364 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:31:12.115   937  1364 D SettingsProvider: selectionArgs: false,
07-28 12:31:12.115   937  1364 D SettingsProvider: selectionArgs: 1002
07-28 12:31:12.115   937  1364 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-28 12:31:12.115   937  1364 D SettingsProvider: ret = -1
07-28 12:31:12.115   937  1648 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
07-28 12:31:12.115   937  1648 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-28 12:31:12.115   937  1648 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:31:12.115   937  1648 D SettingsProvider: selectionArgs: false
07-28 12:31:12.115   937  1648 D SettingsProvider: selectionArgs: 1002
,07-28 12:31:12.115   937  1648 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:31:12.115   937  1648 D SettingsProvider: ret = -1
07-28 12:31:12.115   937  1472 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,07-28 12:31:12.115   937  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:31:12.115   937  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:31:12.115   937  1472 D SettingsProvider: selectionArgs: false
,07-28 12:31:12.115   937  1472 D SettingsProvider: selectionArgs: 1002
07-28 12:31:12.115   937  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:31:12.115   937  1472 D SettingsProvider: ret = -1,
07-28 12:31:12.115   937  1537 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
07-28 12:31:12.115   937  1537 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:31:12.115   937  1537 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,07-28 12:31:12.115   937  1537 D SettingsProvider: selectionArgs: false
07-28 12:31:12.115   937  1537 D SettingsProvider: selectionArgs: 1002
07-28 12:31:12.115   937  1537 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-28 12:31:12.115   937  1537 D SettingsProvider: ret = -1
07-28 12:31:12.115   937  1737 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
07-28 12:31:12.115   937  1737 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-28 12:31:12.115   937  1737 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:31:12.115   937  1737 D SettingsProvider: selectionArgs: false
07-28 12:31:12.115   937  1737 D SettingsProvider: selectionArgs: 1002,
07-28 12:31:12.115   937  1737 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:31:12.115   937  1737 D SettingsProvider: ret = -1
,07-28 12:31:12.115   937  1479 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
07-28 12:31:12.115   937  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:31:12.115   937  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:31:12.115   937  1479 D SettingsProvider: selectionArgs: false
07-28 12:31:12.115   937  1479 D SettingsProvider: selectionArgs: 1002
07-28 12:31:12.115   937  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-28 12:31:12.115   937  1479 D SettingsProvider: ret = -1
07-28 12:31:12.115   937  1253 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:31:12.115   937  1253 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:31:12.115   937  1253 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:31:12.115   937  1253 D SettingsProvider: selectionArgs: false
07-28 12:31:12.115   937  1253 D SettingsProvider: selectionArgs: 1002
07-28 12:31:12.115   937  1253 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:31:12.115   937  1253 D SettingsProvider: ret = -1
07-28 12:31:12.115   937  3040 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,07-28 12:31:12.115   937  3040 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:31:12.115   937  3040 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:31:12.115   937  3040 D SettingsProvider: selectionArgs: false
07-28 12:31:12.115   937  3040 D SettingsProvider: selectionArgs: 1002
07-28 12:31:12.115   937  3040 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:31:12.115   937  3040 D SettingsProvider: ret = -1
07-28 12:31:12.115   937  1242 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
07-28 12:31:12.115   937  1242 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:31:12.115   937  1242 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:31:12.115   937  1242 D SettingsProvider: selectionArgs: false
,07-28 12:31:12.115   937  1242 D SettingsProvider: selectionArgs: 1002
07-28 12:31:12.115   937  1242 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:31:12.115   937  1242 D SettingsProvider: ret = -1
07-28 12:31:12.115   937  1471 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
07-28 12:31:12.115   937  1471 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:31:12.115   937  1471 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:31:12.115   937  1471 D SettingsProvider: selectionArgs: false
07-28 12:31:12.115   937  1471 D SettingsProvider: selectionArgs: 1002
07-28 12:31:12.115   937  1471 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:31:12.115   937  1471 D SettingsProvider: ret = -1
,07-28 12:31:12.135  8248  8248 D BluetoothAdapterState: make,
,07-28 12:31:12.145  8248  8248 I bluedroid: init,
,07-28 12:31:12.145  8248  8269 I BluetoothAdapterState: Entering OffState,
07-28 12:31:12.145  8248  8248 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-28 12:31:12.145  8248  8248 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 12:31:12.145  8248  8248 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-28 12:31:12.145  8248  8248 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-28 12:31:12.145  8248  8248 E bt-btif : btif_fetch_local_ble_random_bdaddr
07-28 12:31:12.145  8248  8248 I bluedroid: get_profile_interface socket
07-28 12:31:12.145  8248  8248 I bluedroid: get_profile_interface map_client
,07-28 12:31:12.145  8248  8272 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,07-28 12:31:12.145  8248  8248 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,07-28 12:31:12.145  8248  8272 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,07-28 12:31:12.145  8248  8272 E BluetoothServiceJni: populateRssiValuesNative
07-28 12:31:12.145  8248  8272 I bluedroid: getModelRssiValues
07-28 12:31:12.145  8248  8272 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,07-28 12:31:12.155  8248  8272 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
07-28 12:31:12.155   937  1472 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:31:12.155   937   937 D SettingsProvider: name = bluetooth_name
,07-28 12:31:12.155  8248  8272 D BluetoothAdapterProperties: Name is: Note3-1
,07-28 12:31:12.155  8248  8256 I bluedroid: config_hci_snoop_log
,07-28 12:31:12.155   937  1061 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 14 receivers.
,07-28 12:31:12.155   937  1061 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-28 12:31:12.155   937  1061 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:31:12.165   937  1061 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-28 12:31:12.165  8248  8269 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,07-28 12:31:12.165  8248  8269 D BluetoothAdapterProperties: Setting state to 11
07-28 12:31:12.165  8248  8269 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-28 12:31:12.165  8248  8269 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,07-28 12:31:12.165  8248  8269 D BluetoothAdapterService: updateAdapterState state is 11
,07-28 12:31:12.165  8248  8269 D BluetoothAdapterService: Autoconnection is available 
,07-28 12:31:12.165  8248  8269 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,07-28 12:31:12.165  1696  1696 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-28 12:31:12.165   937   937 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:12.165   937   937 I InputMethodManagerService: [BT Setting State] State =11
,07-28 12:31:12.175  1194  1194 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-28 12:31:12.175   937  1242 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:31:12.175  1194  1194 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:12.175   937  1242 D ActivityManager: caller:android.app.ApplicationThreadProxy@29158888, r.packageName :com.google.android.gms
,07-28 12:31:12.175  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:12.175  1194  1583 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:31:12.175   937  1471 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:31:12.175   937   954 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-28 12:31:12.175  1194  1194 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:31:12.175  7571  7571 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:12.185  8248  8269 D BluetoothSecureManager: getInstant: null
,07-28 12:31:12.185  8248  8269 D BluetoothSecureManager: calling getMethod for getService
07-28 12:31:12.185  8248  8269 D BluetoothSecureManager: calling getService
07-28 12:31:12.185  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:12.185  8248  8269 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@325b4986
,07-28 12:31:12.185   937   952 D BluetoothSecureManagerService: isSecureModeEnabled
07-28 12:31:12.185   937   952 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
07-28 12:31:12.185  8248  8269 D BtConfig.SecureMode: isSecureModeOn:false
,07-28 12:31:12.185  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-28 12:31:12.185  8248  8269 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,07-28 12:31:12.185  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-28 12:31:12.185  8248  8269 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-28 12:31:12.185  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-28 12:31:12.185  8248  8269 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-28 12:31:12.185  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:31:12.185  8248  8269 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
07-28 12:31:12.185  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-28 12:31:12.185  8248  8269 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
07-28 12:31:12.185  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-28 12:31:12.185  8248  8269 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-28 12:31:12.185  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-28 12:31:12.185  8248  8269 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-28 12:31:12.185  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,07-28 12:31:12.195  8248  8269 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
07-28 12:31:12.195  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:31:12.195  8248  8269 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:31:12.195  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-28 12:31:12.195  8248  8269 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:31:12.195  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-28 12:31:12.195  8248  8269 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
07-28 12:31:12.195  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-28 12:31:12.195  8248  8269 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,07-28 12:31:12.195  8248  8269 D BluetoothBondStateMachine: make
,07-28 12:31:12.195  1194  1194 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-28 12:31:12.195  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:31:12.195  8248  8269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-28 12:31:12.195  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-28 12:31:12.205  8248  8269 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,07-28 12:31:12.205  8248  8274 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-28 12:31:12.205   937  1242 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:31:12.205   937  1242 D ActivityManager: caller:android.app.ApplicationThreadProxy@17e2e646, r.packageName :com.android.bluetooth
,07-28 12:31:12.205  8248  8248 I BtGatt.JNI: classInitNative(L890): classInitNative: Success!
,07-28 12:31:12.215  8248  8269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,07-28 12:31:12.215  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-28 12:31:12.215  8248  8269 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
07-28 12:31:12.215   937  1666 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:31:12.215   937  1666 D ActivityManager: caller:android.app.ApplicationThreadProxy@22bea534, r.packageName :com.android.bluetooth
07-28 12:31:12.215  8248  8248 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:31:12.215  8248  8248 D BtGatt.GattService: Received start request. Starting profile...
07-28 12:31:12.215  8248  8248 D BtGatt.GattService: start()
07-28 12:31:12.215  8248  8248 I bluedroid: get_profile_interface gatt
07-28 12:31:12.215  8248  8248 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29
07-28 12:31:12.215  8248  8248 D BtGatt.AdvertiseManager: advertise manager created
,07-28 12:31:12.215  8248  8269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-28 12:31:12.215  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-28 12:31:12.215  8248  8269 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-28 12:31:12.225   937  1648 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:31:12.225   937  1648 D ActivityManager: caller:android.app.ApplicationThreadProxy@365720d2, r.packageName :com.android.bluetooth
,07-28 12:31:12.225  8248  8269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,07-28 12:31:12.225  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:31:12.225  8248  8269 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-28 12:31:12.225   937  1537 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:31:12.225   937  1537 D ActivityManager: caller:android.app.ApplicationThreadProxy@303ae0a0, r.packageName :com.android.bluetooth
,07-28 12:31:12.225  8248  8269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,07-28 12:31:12.225  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-28 12:31:12.225  8248  8269 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,07-28 12:31:12.235   937  1737 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:31:12.235   937  1737 D ActivityManager: caller:android.app.ApplicationThreadProxy@3f7f1d15, r.packageName :com.android.bluetooth
,07-28 12:31:12.235  8248  8269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,07-28 12:31:12.235  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-28 12:31:12.235  8248  8269 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-28 12:31:12.235   937  3040 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:31:12.235   937  3040 D ActivityManager: caller:android.app.ApplicationThreadProxy@27c7a61b, r.packageName :com.android.bluetooth
,07-28 12:31:12.235  8248  8269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-28 12:31:12.235  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:31:12.235  8248  8269 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-28 12:31:12.235   937  1556 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:31:12.235   937  1556 D ActivityManager: caller:android.app.ApplicationThreadProxy@11c17591, r.packageName :com.android.bluetooth
,07-28 12:31:12.235  8248  8248 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29
,07-28 12:31:12.245  8248  8269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,07-28 12:31:12.245  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-28 12:31:12.245  8248  8248 D HeadsetService: Received start request. Starting profile...
07-28 12:31:12.245  8248  8269 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-28 12:31:12.245   937  1253 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:31:12.245   937  1253 D ActivityManager: caller:android.app.ApplicationThreadProxy@4b088f7, r.packageName :com.android.bluetooth
,07-28 12:31:12.245  8248  8248 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:31:12.245  8248  8248 D HeadsetStateMachine: make
,07-28 12:31:12.245  8248  8269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:31:12.245  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:31:12.245  8248  8269 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:31:12.245  8248  8269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,07-28 12:31:12.245  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-28 12:31:12.245  8248  8269 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:31:12.255  8248  8248 E HeadsetStateMachine: # of Max HF connection is 2
07-28 12:31:12.255  8248  8269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,07-28 12:31:12.255  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-28 12:31:12.255  8248  8269 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,07-28 12:31:12.255  8248  8269 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
07-28 12:31:12.255  8248  8269 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-28 12:31:12.255  8248  8269 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,07-28 12:31:12.255  8248  8269 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-28 12:31:12.255   937   954 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,07-28 12:31:12.255   937  1479 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
07-28 12:31:12.255  8248  8248 I bluedroid: get_profile_interface handsfree
,07-28 12:31:12.265  8248  8248 I DualScoManager: Instantiating Dual Sco Manager
07-28 12:31:12.265  8248  8248 I DualScoManager: Set HeadsetServiceHelper
,07-28 12:31:12.265  8248  8248 D BluetoothAtMessage: createCMTIContentObservers
,07-28 12:31:12.265   937  3040 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
07-28 12:31:12.265   937  3040 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:31:12.265   937  3040 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:31:12.265   937  3040 D SettingsProvider: selectionArgs: false
07-28 12:31:12.265   937  3040 D SettingsProvider: selectionArgs: 1002
07-28 12:31:12.275   937  3040 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:31:12.275   937  3040 D SettingsProvider: ret = -1
07-28 12:31:12.275  8248  8285 D HeadsetStateMachine: Enter Disconnected: -2
,07-28 12:31:12.275  8248  8248 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29
,07-28 12:31:12.275  8248  8248 D A2dpService: Received start request. Starting profile...
07-28 12:31:12.275  8248  8285 E HeadsetStateMachine: set to mRemoteBrsf = 0
,07-28 12:31:12.275  8248  8285 D HeadsetStateMachine: map size, before remove : 0
07-28 12:31:12.275  8248  8285 D HeadsetStateMachine: map size, after remove: 0
07-28 12:31:12.275  8248  8248 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-28 12:31:12.275  8248  8285 D HeadsetStateMachine: mNextConnectingDevice : null
07-28 12:31:12.275  8248  8248 V Avrcp   : make
07-28 12:31:12.275  8248  8248 V Avrcp   : Avrcp
,07-28 12:31:12.275  8248  8248 I bluedroid: get_profile_interface avrcp
,07-28 12:31:12.275  8248  8248 V Avrcp   : start
,07-28 12:31:12.285  1823  1823 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:31:12.285  8248  8248 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-28 12:31:12.285  8248  8248 V Avrcp   : ++registerMediaPlayers++
,07-28 12:31:12.285  8248  8248 I Avrcp   : No of Audio players :: 2
07-28 12:31:12.285  8248  8248 I Avrcp   : App Package name is com.google.android.music
07-28 12:31:12.285  1823  1823 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:31:12.295  8248  8248 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-28 12:31:12.295  8248  8248 I Avrcp   : App pkg name is Google Play Music
,07-28 12:31:12.295  8248  8248 I Avrcp   : Name::Google Play Music
07-28 12:31:12.295  8248  8248 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-28 12:31:12.295  8248  8248 I Avrcp   : App Package name is com.sec.android.app.music
,07-28 12:31:12.295  8248  8248 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-28 12:31:12.295  8248  8248 I Avrcp   : App pkg name is Music
07-28 12:31:12.295  8248  8248 I Avrcp   : Name::Music
07-28 12:31:12.295  8248  8248 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-28 12:31:12.295  8248  8248 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,07-28 12:31:12.305  8248  8248 I Avrcp   : No of Video players :: 1
,07-28 12:31:12.305  8248  8248 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
07-28 12:31:12.305  8248  8248 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk,
,07-28 12:31:12.305  8248  8248 I Avrcp   : Video App pkg name is Video Player
,07-28 12:31:12.305  8248  8248 I Avrcp   : Name::Video Player
07-28 12:31:12.305  8248  8248 V Avrcp   : MediaPlayerInfo: mPlayerId=3
,07-28 12:31:12.305  8248  8248 I Avrcp   : Add tempPlayer
07-28 12:31:12.305  8248  8248 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-28 12:31:12.305  8248  8248 I Avrcp   : Total no of players: 4
,07-28 12:31:12.305  8248  8248 V Avrcp   : swapping the samsung player with 1st player
07-28 12:31:12.305  8248  8248 I Avrcp   :  Updating now playing list upon AVRCP Start
07-28 12:31:12.305  8248  8288 V Avrcp   : handleMessage, msg=207,
07-28 12:31:12.305  8248  8288 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
07-28 12:31:12.305  8248  8248 I BluetoothA2dpServiceJni: classInitNative: succeeds
,07-28 12:31:12.305  8248  8248 D A2dpStateMachine: make
,07-28 12:31:12.305  8248  8248 I bluedroid: get_profile_interface a2dp
,07-28 12:31:12.305  8248  8292 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-28 12:31:12.305  8248  8248 E bt-btif : warning : media task started media_task_refcnt 1 
,07-28 12:31:12.315  8248  8248 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29,
07-28 12:31:12.315  8248  8291 D A2dpStateMachine: Enter Disconnected: -2
07-28 12:31:12.315  8248  8288 D BluetoothMediaBrowser: no now playing list,
07-28 12:31:12.315  8248  8288 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
07-28 12:31:12.315  8248  8288 D Avrcp   :  checkNowPlayingList start
,07-28 12:31:12.315  8248  8248 I BluetoothHidServiceJni: classInitNative: succeeds
07-28 12:31:12.315  8248  8248 D HidService: Received start request. Starting profile...
07-28 12:31:12.315  8248  8248 I bluedroid: get_profile_interface hidhost,
07-28 12:31:12.315   349   349 I ServiceManager: Waiting for service AtCmdFwd...
07-28 12:31:12.315  8248  8248 D HidService: setHidService(): set to: null
,07-28 12:31:12.315  8248  8248 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29
07-28 12:31:12.315  8248  8248 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-28 12:31:12.315  8248  8248 D HealthService: Received start request. Starting profile...
,07-28 12:31:12.315  8248  8248 I bluedroid: get_profile_interface health
07-28 12:31:12.315  8248  8248 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29
,07-28 12:31:12.315  8248  8248 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-28 12:31:12.315  8248  8248 D PanService: Received start request. Starting profile...
07-28 12:31:12.315  8248  8248 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:31:12.315  8248  8248 I bluedroid: get_profile_interface pan
,07-28 12:31:12.325  8248  8248 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29
,07-28 12:31:12.325  8248  8248 E BluetoothAdapterService(54542121): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
07-28 12:31:12.325  8248  8248 D BluetoothMapService: Received start request. Starting profile...
,07-28 12:31:12.345  8248  8248 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29
,07-28 12:31:12.345  8248  8248 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,07-28 12:31:12.355  8248  8248 D SapService: Received start request. Starting profile...
07-28 12:31:12.355  8248  8248 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-28 12:31:12.355  8248  8248 I bluedroid: get_profile_interface sap
07-28 12:31:12.355  8248  8248 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29
07-28 12:31:12.355  8248  8248 D HeadsetStateMachine: Try to query the phonestate on bind
07-28 12:31:12.355  1409  3065 I Telecom : BluetoothPhoneService: queryPhoneState
07-28 12:31:12.355  1409  1409 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-28 12:31:12.355  8248  8248 D HeadsetStateMachine: Proxy object connected
,07-28 12:31:12.355  8248  8248 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
07-28 12:31:12.355  8248  8248 D HeadsetPhoneState: sendDeviceDataStateChanged
07-28 12:31:12.355  8248  8285 D HeadsetStateMachine: Disconnected process message: 11
,07-28 12:31:12.355  8248  8285 D HeadsetStateMachine: Disconnected process message: 18
07-28 12:31:12.355  8248  8248 D HeadsetPhoneState: Signal level : previous=0 curr=0
,07-28 12:31:12.355  8248  8248 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-28 12:31:12.355  8248  8285 D HeadsetStateMachine: Disconnected process message: 10
07-28 12:31:12.355  8248  8248 E BluetoothAdapterService(54542121): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,07-28 12:31:12.355  8248  8248 D BluetoothA2dp: Proxy object connected
07-28 12:31:12.355  8248  8285 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-28 12:31:12.355  8248  8285 D HeadsetStateMachine: Disconnected process message: 11
07-28 12:31:12.355  8248  8248 D BluetoothAdapterService: Bluetooth A2dp source service connected
,07-28 12:31:12.355  8248  8248 E BluetoothAdapterService(54542121): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
07-28 12:31:12.355  8248  8248 E BluetoothAdapterService(54542121): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-28 12:31:12.355  8248  8248 E BluetoothAdapterService(54542121): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,07-28 12:31:12.355  8248  8248 E BluetoothAdapterService(54542121): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,07-28 12:31:12.365  8248  8248 E BluetoothAdapterService(54542121): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,07-28 12:31:12.365  8248  8248 E BluetoothAdapterService(54542121): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
07-28 12:31:12.365  8248  8269 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,07-28 12:31:12.365  8248  8269 I bluedroid: enable
07-28 12:31:12.365  8248  8296 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,07-28 12:31:12.365  8248  8269 I bt_hci_bdroid: init
07-28 12:31:12.365  8248  8269 I bt_vendor: init
07-28 12:31:12.365  8248  8269 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,07-28 12:31:12.365  8248  8269 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-28 12:31:12.365  8248  8269 D bt_userial: userial_init
,07-28 12:31:12.365  8248  8269 D bt_vendor: op for 5
07-28 12:31:12.365  8248  8269 D bt_vendor: op for 0
,07-28 12:31:12.365  8248  8269 D bt_upio : upio_set_bluetooth_power(on: 0)
07-28 12:31:12.365  8248  8269 D bt_upio : is_emulator_context : 0
07-28 12:31:12.365  8248  8269 D bt_upio : is_rfkill_disabled ? [0]
,07-28 12:31:12.365  8248  8269 D bt_upio : is_rfkill_disabled ? [0]
07-28 12:31:12.365  8248  8269 D bt_vendor: op for 0
,07-28 12:31:12.365  8248  8269 D bt_upio : upio_set_bluetooth_power(on: 1)
07-28 12:31:12.365  8248  8269 D bt_upio : is_emulator_context : 0
,07-28 12:31:12.365  8248  8269 D bt_upio : is_rfkill_disabled ? [0]
07-28 12:31:12.365  8248  8298 D bt_vendor: op for 3
,07-28 12:31:12.365  8248  8298 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
07-28 12:31:12.365  8248  8298 I bt_userial_vendor: userial_vendor_open():UART is setup
07-28 12:31:12.365  8248  8298 I bt_userial_vendor: device fd = 65 open
07-28 12:31:12.365  8248  8298 D bt_vendor: op for 1,
07-28 12:31:12.365  8248  8298 E bt_hwcfg: Start CFG HW, HCI reset
07-28 12:31:12.365  8248  8299 D bt_userial: Entering userial_read_thread()
,07-28 12:31:12.445  8248  8298 E bt_hwcfg: Read Local Name after HCI reset
,07-28 12:31:12.465  8248  8298 D bt_hwcfg: Chipset BCM4335C0,
07-28 12:31:12.465  8248  8298 D bt_hwcfg: Target name = [BCM4335C0]
,07-28 12:31:12.465  8248  8298 I bt_hwcfg: module_type[semco].
07-28 12:31:12.465  8248  8298 I bt_hwcfg: not ZERO...
,07-28 12:31:12.465  8248  8298 I bt_hwcfg: module_type[semco] is invalid.
07-28 12:31:12.465  8248  8298 E bt_hwcfg: patchram path ORG . BCM4335C0,
07-28 12:31:12.465  8248  8298 E bt_hwcfg: patchram path ORG .. BCM4335C0
07-28 12:31:12.465  8248  8298 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
,07-28 12:31:12.465  8248  8298 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
07-28 12:31:12.465  8248  8298 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
,07-28 12:31:12.465  8248  8298 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
07-28 12:31:12.465  8248  8298 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335C0,
07-28 12:31:12.465  8248  8298 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559_wisol.hcd BCM4335C0
,07-28 12:31:12.465  8248  8298 E bt_hwcfg: fw ver (org)0.0
07-28 12:31:12.465  8248  8298 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
,07-28 12:31:12.465  8248  8298 E bt_hwcfg: Remove module rev, try again BCM4335
07-28 12:31:12.465  8248  8298 D bt_hwcfg: Target name = [BCM4335]
,07-28 12:31:12.465  8248  8298 I bt_hwcfg: module_type[semco].
07-28 12:31:12.465  8248  8298 I bt_hwcfg: not ZERO...,
07-28 12:31:12.465  8248  8298 I bt_hwcfg: module_type[semco] is invalid.
,07-28 12:31:12.465  8248  8298 E bt_hwcfg: patchram path ORG . BCM4335
07-28 12:31:12.465  8248  8298 E bt_hwcfg: patchram path ORG .. BCM4335
,07-28 12:31:12.465  8248  8298 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335
07-28 12:31:12.465  8248  8298 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335,
07-28 12:31:12.465  8248  8298 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335
,07-28 12:31:12.465  8248  8298 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
07-28 12:31:12.465  8248  8298 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335
,07-28 12:31:12.465  8248  8298 I bt_hwcfg: patch(org) : bcm4335_V0111.0559.hcd
07-28 12:31:12.465  8248  8298 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4335_V0111.0559.hcd
,07-28 12:31:12.465  8248  8298 E bt_hwcfg: ORG patchram base 0111
,07-28 12:31:12.465  8248  8298 E bt_hwcfg: ORG patchram minor 0559
07-28 12:31:12.465  8248  8298 E bt_hwcfg: fw ver (org)111.559
,07-28 12:31:12.465  8248  8298 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4335_V0111.0559.hcd
07-28 12:31:12.485  8248  8298 I bt_hwcfg: Axi patch failure or not include AXI patching,
,07-28 12:31:12.485  8248  8298 I bt_hwcfg: bt vendor lib: set UART baud 3000000,
,07-28 12:31:12.975  8248  8298 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-28 12:31:12.975  8248  8298 I bt_hwcfg: FW Download delta = 536235
,07-28 12:31:12.985  8248  8298 D bt_hwcfg: Settlement delay -- 100 ms
07-28 12:31:12.985  8248  8298 I bt_hwcfg: Setting fw settlement delay to 100 
,07-28 12:31:13.085  8248  8298 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:31:13.125  8248  8298 I bt_hwcfg: vendor lib fwcfg completed
,07-28 12:31:13.145  8248  8296 I         : BTE_InitTraceLevels -- TRC_HCI
,07-28 12:31:13.145  8248  8296 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-28 12:31:13.145  8248  8296 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 12:31:13.145  8248  8296 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-28 12:31:13.145  8248  8296 I         : BTE_InitTraceLevels -- TRC_AVRC
07-28 12:31:13.145  8248  8296 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 12:31:13.145  8248  8296 I         : BTE_InitTraceLevels -- TRC_BNEP
07-28 12:31:13.145  8248  8296 I         : BTE_InitTraceLevels -- TRC_BTM
,07-28 12:31:13.145  8248  8296 I         : BTE_InitTraceLevels -- TRC_GAP
07-28 12:31:13.145  8248  8296 I         : BTE_InitTraceLevels -- TRC_PAN
07-28 12:31:13.145  8248  8296 I         : BTE_InitTraceLevels -- TRC_SAP
07-28 12:31:13.145  8248  8296 I         : BTE_InitTraceLevels -- TRC_SDP
,07-28 12:31:13.145  8248  8296 I         : BTE_InitTraceLevels -- TRC_GATT
07-28 12:31:13.145  8248  8296 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 12:31:13.145  8248  8296 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 12:31:13.145  8248  8296 I         : BTE_InitTraceLevels -- TRC_BTIF
07-28 12:31:13.145  8248  8296 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,07-28 12:31:13.315   349   349 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:31:13.375  8248  8296 W bt-l2cap: l2c_link_processs_ble_num_bufs 15
,07-28 12:31:13.385  8248  8296 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xaf918b5d 
,07-28 12:31:13.385  8248  8296 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xaf918b5d 
,07-28 12:31:13.605  8248  8272 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 1 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,07-28 12:31:13.605  8248  8272 E bt-btif : Calling BTA_HhEnable
,07-28 12:31:13.605  8248  8272 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,07-28 12:31:13.605  8248  8272 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
07-28 12:31:13.605  8248  8272 E BluetoothServiceJni: populateRssiValuesNative
07-28 12:31:13.605  8248  8272 I bluedroid: getModelRssiValues
,07-28 12:31:13.605  8248  8272 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-28 12:31:13.605  8248  8272 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-28 12:31:13.615  8248  8272 D BluetoothAdapterProperties: Name is: Note3-1
,07-28 12:31:13.615  8248  8272 D BluetoothAdapterProperties: Scan Mode:20
,07-28 12:31:13.615  8248  8272 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 12:31:13.615  8248  8272 D BluetoothAdapterProperties: LE Address is:E0:B7:20:3E:93:BC
,07-28 12:31:13.615  8248  8272 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
07-28 12:31:13.615  8248  8298 D bt_vendor: op for 2
07-28 12:31:13.615  8248  8298 D bt_vendor: op for 6
,07-28 12:31:13.615  8248  8298 D bt_vendor: op for 7
,07-28 12:31:13.615  8248  8298 D bt_upio : proc btwrite assertion
,07-28 12:31:13.615  8248  8272 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,07-28 12:31:13.615  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.615  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.615  8248  8272 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,07-28 12:31:13.615  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.615  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.615  8248  8272 E bt-btif : btif_sock_init: !vhci_init
07-28 12:31:13.615  8248  8272 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,07-28 12:31:13.615  8248  8272 D IOP_DB_BT: db_open: db_open : handle 3014184976l, read 14063 bytes onto local cache
07-28 12:31:13.615  8248  8272 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,07-28 12:31:13.615  8248  8272 D IOP_DB_BT: db_query: result 1
07-28 12:31:13.615  8248  8272 I         : iop_db_open: iop_db_open status 0
,07-28 12:31:13.625  8248  8272 D bte_conf: Device ID record 1 : primary
,07-28 12:31:13.625  8248  8272 D bte_conf:   vendorId            = 0075
07-28 12:31:13.625  8248  8272 D bte_conf:   vendorIdSource      = 0001
07-28 12:31:13.625  8248  8272 D bte_conf:   product             = 0100
07-28 12:31:13.625  8248  8272 D bte_conf:   version             = 0200
,07-28 12:31:13.625  8248  8272 D bte_conf:   clientExecutableURL = 
07-28 12:31:13.625  8248  8272 D bte_conf:   serviceDescription  = 
07-28 12:31:13.625  8248  8272 D bte_conf:   documentationURL    = 
,07-28 12:31:13.625  8248  8272 D bte_conf: bte_load_did_conf no section named DID2.
,07-28 12:31:13.625  8248  8269 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,07-28 12:31:13.625  8248  8269 D BluetoothAdapterProperties: ScanMode =  20
07-28 12:31:13.625  8248  8269 D BluetoothAdapterProperties: State =  11
,07-28 12:31:13.625   937  1556 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-28 12:31:13.625  8248  8269 D BluetoothAdapterProperties: Setting state to 12
07-28 12:31:13.625  8248  8269 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-28 12:31:13.625   937   937 D SettingsProvider: name = bluetooth_name
,07-28 12:31:13.625  8248  8272 D BluetoothAdapterProperties: Scan Mode:21
,07-28 12:31:13.625  8248  8272 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 12:31:13.635   937  1479 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,07-28 12:31:13.635   937  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:31:13.635   937  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:31:13.635   937  1479 D SettingsProvider: selectionArgs: false
07-28 12:31:13.635   937  1479 D SettingsProvider: selectionArgs: 1002
,07-28 12:31:13.635   937  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:31:13.635   937  1479 D SettingsProvider: ret = -1
,07-28 12:31:13.635  8248  8269 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:31:13.635  8248  8269 D BluetoothAdapterService: updateAdapterState state is 12
,07-28 12:31:13.635   937  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:31:13.635  8248  8298 E bt_h4   : vendor lib postload completed
,07-28 12:31:13.635   937  1479 D ActivityManager: caller:android.app.ApplicationThreadProxy@345f9de7, r.packageName :com.android.bluetooth
,07-28 12:31:13.645  8248  8269 D BluetoothAdapterService: Autoconnection is available 
,07-28 12:31:13.645  8248  8269 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-28 12:31:13.645  8248  8269 D BluetoothAdapterService: starting service from this receiver
,07-28 12:31:13.645   937  3040 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:31:13.645   937  3040 D ActivityManager: caller:android.app.ApplicationThreadProxy@e3ed03d, r.packageName :com.android.bluetooth
,07-28 12:31:13.645  8248  8269 I BluetoothAdapterState: Entering On State from state = 11
,07-28 12:31:13.645  1315  7510 D BluetoothPbap: onBluetoothStateChange: up=true
,07-28 12:31:13.655  8248  8248 I BluetoothPbapService: Handler(): got msg=1
,07-28 12:31:13.655   937  1648 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-28 12:31:13.665  8248  8248 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-28 12:31:13.665  8248  8298 D bt_vendor: op for 7
,07-28 12:31:13.675  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.675  8248  8272 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-28 12:31:13.675  8248  8298 D bt_vendor: op for 7
,07-28 12:31:13.675  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.675  8248  8298 D bt_vendor: op for 7
,07-28 12:31:13.675  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.675  8248  8313 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-28 12:31:13.675  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.675  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.675  8248  8298 D bt_vendor: op for 7
,07-28 12:31:13.675  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.685  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.685  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.685  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:13.685  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:13.685  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:13.685  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:31:13.685  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:13.685  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:13.685  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:13.685  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:31:13.685  8248  8298 D bt_vendor: op for 7
,07-28 12:31:13.685  8248  8298 D bt_upio : BT_WAKE is asserted already
07-28 12:31:13.685  7429  7429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:31:13.685  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:13.685  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.685  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.685  8248  8298 D bt_vendor: op for 7
,07-28 12:31:13.685  8248  8298 D bt_upio : BT_WAKE is asserted already
07-28 12:31:13.685  8248  8313 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:31:13.695  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.695  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.695  8248  8313 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
,07-28 12:31:13.695  8248  8313 D BluetoothSocket: bindListen(), new LocalSocket 
07-28 12:31:13.695  8248  8313 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:31:13.695  8248  8313 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29f088be
,07-28 12:31:13.695  8248  8298 D bt_vendor: op for 7
,07-28 12:31:13.695  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.695  8248  8313 D BluetoothSocket: channel: 19
,07-28 12:31:13.695  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.695  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.695  8248  8313 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
07-28 12:31:13.695  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.695  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.705  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.705  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.705  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.705  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.715  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.715  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.715  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.715  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.715  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.715  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.725  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.725  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.725  8248  8298 D bt_vendor: op for 7
,07-28 12:31:13.725  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.725  8248  8298 D bt_vendor: op for 7
,07-28 12:31:13.725  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.725  8248  8298 D bt_vendor: op for 7
,07-28 12:31:13.725  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.725  8248  8298 D bt_vendor: op for 7
,07-28 12:31:13.725  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.735  8248  8298 D bt_vendor: op for 7
,07-28 12:31:13.735  8248  8298 D bt_upio : BT_WAKE is asserted already
07-28 12:31:13.735  8248  8298 D bt_vendor: op for 7,
07-28 12:31:13.735  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.735  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.735  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.735  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.735  8248  8298 D bt_upio : BT_WAKE is asserted already
,07-28 12:31:13.795   937  1061 I art     : Explicit concurrent mark sweep GC freed 54548(3MB) AllocSpace objects, 5(80KB) LOS objects, 30% free, 37MB/53MB, paused 1.284ms total 131.200ms
07-28 12:31:13.795   937  1061 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,07-28 12:31:13.795   937  1061 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:31:13.795  7571  7580 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:31:13.795  1315  1315 D BluetoothPbap: Proxy object connected
07-28 12:31:13.795  1315  1315 D PbapServerProfile: Bluetooth service connected
,07-28 12:31:13.805   937  1061 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:31:13.805  1409  1438 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:31:13.805   937  1061 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:31:13.805  1409  1438 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:31:13.805   937  1061 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:31:13.805  3158  3170 E BluetoothHeadset: BluetoothHeadset service is binded
07-28 12:31:13.805   937  1061 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:31:13.815   937  1061 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
07-28 12:31:13.815   937   937 D BluetoothA2dp: Proxy object connected
07-28 12:31:13.815  1315  1325 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-28 12:31:13.815   937  1061 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,07-28 12:31:13.815  1315  7510 D BluetoothPan: Binding service...
,07-28 12:31:13.815  1315  1315 D BluetoothInputDevice: Proxy object connected
07-28 12:31:13.815  1315  1315 D HidProfile: Bluetooth service connected
,07-28 12:31:13.815   937  1061 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-28 12:31:13.815  3158  3167 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:31:13.815   937  1061 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:31:13.815  3158  3158 D BluetoothA2dp: Proxy object connected
,07-28 12:31:13.815   937  1061 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:31:13.815   937  1061 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:31:13.815  1315  1315 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:31:13.815  1315  1315 D PanProfile: Bluetooth service connected
,07-28 12:31:13.825   937  1061 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:31:13.825  1409  1420 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:31:13.825  8248  8312 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:31:13.825   937  1061 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:31:13.825  1429  1631 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:31:13.825  1315  1337 D Bluetoothsap: onBluetoothStateChange: up=true
07-28 12:31:13.825  1315  1337 D Bluetoothsap: Binding service...
,07-28 12:31:13.825  1315  1337 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,07-28 12:31:13.825   937  1061 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
07-28 12:31:13.825  1315  1337 D Bluetoothsap: bindService called to Bluetooth SAP Service
,07-28 12:31:13.825  1315  1315 D Bluetoothsap: BluetoothSAP Proxy object connected
07-28 12:31:13.825  1315  1325 D BluetoothMap: onBluetoothStateChange: up=true
,07-28 12:31:13.825  1315  1315 D SapProfile: Bluetooth service connected
07-28 12:31:13.825  1315  1315 D Bluetoothsap: getConnectedDevices()
07-28 12:31:13.825   937  1061 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,07-28 12:31:13.825  1315  1315 D BluetoothMap: Proxy object connected
07-28 12:31:13.825  1315  1325 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:31:13.825  1315  1315 D MapProfile: Bluetooth service connected
,07-28 12:31:13.825   937  1061 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
07-28 12:31:13.825  1315  1315 D BluetoothA2dp: Proxy object connected
07-28 12:31:13.825  1315  1315 D A2dpProfile: Bluetooth service connected
,07-28 12:31:13.835   937  1061 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:31:13.835  1315  1337 E BluetoothHeadset: BluetoothHeadset service is binded
07-28 12:31:13.835   937  1061 D BluetoothPan: Binding service...
07-28 12:31:13.835   937  1061 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-28 12:31:13.835  1315  1315 D HeadsetProfile: Bluetooth service connected
07-28 12:31:13.835   937   937 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:31:13.835   937  1061 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,07-28 12:31:13.835   937   937 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-28 12:31:13.835   937   937 I InputMethodManagerService: [BT Setting State] State =12
07-28 12:31:13.835   937   937 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-28 12:31:13.835  1194  1194 D BluetoothTile:  onBluetoothStateChange:
,07-28 12:31:13.835  1409  1409 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3d9e0f1a, true
,07-28 12:31:13.835  7571  7571 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:13.835  1409  1409 D BluetoothHeadset: registerMessageListener
,07-28 12:31:13.835  1194  1194 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-28 12:31:13.835  1194  1194 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:13.835  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:13.845  1696  1696 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-28 12:31:13.845  1194  1583 D BluetoothTile:  handleUpdatestate:false name:null
07-28 12:31:13.845  1194  1583 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:31:13.845   937  1061 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
07-28 12:31:13.845   937  1434 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:31:13.845   937  1434 D ActivityManager: caller:android.app.ApplicationThreadProxy@37a26142, r.packageName :com.google.android.gms
,07-28 12:31:13.845  1315  1315 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:31:13.845   937  1737 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:31:13.845   937  1537 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,07-28 12:31:13.845  8248  8312 D HeadsetService: registerMessageListener
,07-28 12:31:13.845  8248  8312 D HeadsetService: registerMessageListener
07-28 12:31:13.845  8248  8285 D HeadsetStateMachine: Disconnected process message: 70
07-28 12:31:13.845  8248  8285 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1bee9c3b
07-28 12:31:13.845  1194  1194 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:31:13.845  1409  1409 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-28 12:31:13.845  1409  1409 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,07-28 12:31:13.855  8248  8285 D HeadsetStateMachine: Disconnected process message: 9
07-28 12:31:13.855  1315  1315 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
07-28 12:31:13.855  1315  1315 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,07-28 12:31:13.855  8248  8285 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,07-28 12:31:13.855  8248  8327 D BluetoothMapMasInstance: set MAP SDP message type : 1
07-28 12:31:13.855   311  1521 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
07-28 12:31:13.855   311  1521 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-28 12:31:13.855   311  1521 V voice   : voice_set_parameters: exit with code(-2)
07-28 12:31:13.855   311  1521 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-28 12:31:13.855   311  1521 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-28 12:31:13.855   311  1521 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-28 12:31:13.855   311  1521 V audio_hw_primary: adev_set_parameters: exit
07-28 12:31:13.855  8248  8285 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,07-28 12:31:13.855  8248  8327 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:31:13.865  1315  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:31:13.865  8248  8327 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
07-28 12:31:13.865  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.865   937  1479 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-28 12:31:13.865  8248  8298 D bt_upio : BT_WAKE is asserted already
07-28 12:31:13.865   937  1479 D ActivityManager: caller:android.app.ApplicationThreadProxy@39796389, r.packageName :com.android.settings
07-28 12:31:13.865  8248  8327 D BluetoothSocket: bindListen(), new LocalSocket 
,07-28 12:31:13.865  8248  8327 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:31:13.865  8248  8327 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28d4af58
07-28 12:31:13.865  8248  8327 D BluetoothSocket: channel: 5
,07-28 12:31:13.865  1315  1315 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:31:13.865  1315  1315 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:31:13.875  8248  8248 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3403f29
07-28 12:31:13.875  8248  8248 D BtConfig.SecureMode: isSecureModeOn:false
,07-28 12:31:13.875   937  1147 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:31:13.875   937  1147 D ActivityManager: caller:android.app.ApplicationThreadProxy@3b3853af, r.packageName :com.android.bluetooth
,07-28 12:31:13.905   937  1253 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-28 12:31:13.915  8248  8333 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:31:13.915  8248  8333 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
07-28 12:31:13.915  8248  8333 D BluetoothSocket: bindListen(), new LocalSocket 
07-28 12:31:13.915  8248  8333 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:31:13.915  8248  8333 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38349122
07-28 12:31:13.915  8248  8298 D bt_vendor: op for 7
07-28 12:31:13.915  8248  8298 D bt_upio : BT_WAKE is asserted already
07-28 12:31:13.915  8248  8333 D BluetoothSocket: channel: 12
07-28 12:31:13.915  8248  8333 I BtOppRfcommListener: Accept thread started.
,07-28 12:31:13.935  1823  1823 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:31:13.935   937  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:31:13.935   937  1479 D ActivityManager: caller:android.app.ApplicationThreadProxy@7aebfa8, r.packageName :com.google.android.gms
,07-28 12:31:13.945  1823  8337 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-28 12:31:13.945  1823  1823 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:31:13.955  7429  7490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:13.955  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:13.955  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:13.955  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:31:13.955  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:13.955  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:13.955  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:13.955  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:31:13.955  7429  7490 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:31:13.955  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:31:13.955  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20c7cc70 added. We now have 8 listener(s)
07-28 12:31:13.955  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:31:13.965   937  1556 D ActivityManager: caller:android.app.ApplicationThreadProxy@8dd81fd, r.packageName :com.google.android.gms
,07-28 12:31:13.965  7429  7490 I WifiManager: packageName : com.test.thalitest
,07-28 12:31:13.965   937   952 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-28 12:31:13.965   937   952 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:31:13.965   937   952 D SecContentProvider2: mCursor = null
,07-28 12:31:13.965   937   952 D WifiService: setWifiEnabled: false pid=7429, uid=10079
,07-28 12:31:13.965   937   952 D SettingsProvider: name = wifi_on
,07-28 12:31:13.965  7429  7490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:13.965  7429  7490 I WifiManager: packageName : com.test.thalitest
07-28 12:31:13.965   937  3040 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-28 12:31:13.965   937  3040 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:31:13.965   937  3040 D SecContentProvider2: mCursor = null
,07-28 12:31:13.965   937  3040 D WifiService: setWifiEnabled: true pid=7429, uid=10079
07-28 12:31:13.965   937  3040 W ActivityManager: Permission Denial: getCurrentUser() from pid=7429, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:31:13.965   937  3040 W WifiService: Failed getting userId using ActivityManagerNative
07-28 12:31:13.965   937  3040 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7429, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:31:13.965   937  3040 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-28 12:31:13.965   937  3040 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-28 12:31:13.965   937  3040 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-28 12:31:13.965   937  3040 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-28 12:31:13.965   937  3040 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-28 12:31:13.965   937  3040 D SettingsProvider: name = wifi_on
,07-28 12:31:13.965  1823  8337 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-28 12:31:13.975   937  1152 E WifiHW  : ##################### set firmware type 0 #####################
,07-28 12:31:13.975   298  1058 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,07-28 12:31:13.975   298  1058 I WifiHW  : module is semco
07-28 12:31:13.975   298  1058 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-28 12:31:13.975   298  1058 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-28 12:31:13.975   298  1058 E WifiHW  : TEMP_FAILURE_RETRY complete
07-28 12:31:13.975   298  1058 D SoftapController: Softap fwReload - Ok
,07-28 12:31:13.975   298  1058 D CommandListener: Setting iface cfg
07-28 12:31:13.975   298  1058 D CommandListener: Trying to bring down wlan0
,07-28 12:31:13.975   298  1058 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:31:13.975   937  1152 E WifiHW  : supplicant_name : p2p_supplicant
,07-28 12:31:14.005  8341  8341 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,07-28 12:31:14.005  8341  8341 I wpa_supplicant: Successfully initialized wpa_supplicant
07-28 12:31:14.015  8341  8341 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-28 12:31:14.015  8341  8341 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-28 12:31:14.015   361   361 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8341
07-28 12:31:14.015   361   361 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-28 12:31:14.015  8341  8341 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:31:14.015  8341  8341 I wpa_supplicant: ssSupport state is = 1
07-28 12:31:14.015  8341  8341 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,07-28 12:31:14.015  8341  8341 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
07-28 12:31:14.015   303   303 E SMD     : DCD ON
,07-28 12:31:14.015   361   361 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8341
07-28 12:31:14.015   361   361 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,07-28 12:31:14.085   937   937 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:31:14.085  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:31:14.085  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-28 12:31:14.085  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:14.085  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-28 12:31:14.085  1194  1194 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:31:14.085  1194  1194 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
07-28 12:31:14.085  1194  1194 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:31:14.085   937  1156 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-28 12:31:14.085  1194  1583 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-28 12:31:14.085   937  1152 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-28 12:31:14.085  1194  1194 D HotspotTile: onReceive : 2, 0
,07-28 12:31:14.085  7038  7038 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:31:14.095   937  1737 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:14.095  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:31:14.095  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:31:14.095  6889  6889 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:31:14.095  6889  6889 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:31:14.275   361   361 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,07-28 12:31:14.315   349   349 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-28 12:31:14.535  8341  8341 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-28 12:31:14.565   937  1147 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-28 12:31:14.565   937  1147 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-28 12:31:14.565   937  1147 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-28 12:31:14.565   937  1147 D BatteryService: stay LED for fully charged
07-28 12:31:14.565   937   937 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-28 12:31:14.565   937   937 I MotionRecognitionService: Plugged
,07-28 12:31:14.575   937   937 I MotionRecognitionService: setPowerConnected  = true
,07-28 12:31:14.575  1194  1194 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-28 12:31:14.575  1194  1194 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-28 12:31:14.575  1194  1194 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:31:14.585  1194  1194 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:31:14.585  1194  1194 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:31:14.585  1194  1194 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-28 12:31:14.585  8248  8248 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-28 12:31:14.585  8248  8285 D HeadsetStateMachine: Disconnected process message: 10
,07-28 12:31:14.615  8341  8341 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-28 12:31:14.615  8341  8341 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-28 12:31:14.625   361   361 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8341
07-28 12:31:14.625   361   361 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,07-28 12:31:14.625  8341  8341 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:31:14.625  8341  8341 I wpa_supplicant: ssSupport state is = 1
07-28 12:31:14.625  8341  8341 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,07-28 12:31:14.625  8341  8341 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:31:14.625  8341  8341 E wpa_supplicant: SIM READ ERROR
07-28 12:31:14.625  8341  8341 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:31:14.625  8341  8341 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:31:14.625  8341  8341 E wpa_supplicant: SIM READ ERROR
,07-28 12:31:14.625  8341  8341 I wpa_supplicant: Blacklist: Clear (all) 
07-28 12:31:14.625  8341  8341 I wpa_supplicant: wpa_default_ap_write_once
,07-28 12:31:14.625  8341  8341 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-28 12:31:14.625  8341  8341 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:31:14.625  8341  8341 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
07-28 12:31:14.625  8341  8341 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:31:14.625  8341  8341 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-28 12:31:14.625  8341  8341 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 12:31:15.275   937  1155 E Tethering: No numeric data
,07-28 12:31:15.275   937  1155 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-28 12:31:15.275   937  1149 V NetworkStats: performPollLocked(flags=0x1)
07-28 12:31:15.275   937  1149 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:31:15.275  1194  1194 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-28 12:31:15.275  1194  1194 D HotspotTile: updateTetherState():false, false
,07-28 12:31:15.275   937  1149 D NetworkStatsFactory: UpdateStatsForKnox
07-28 12:31:15.275   937  1149 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:15.275   937  1149 V NetworkStats: performPollLocked() took 4ms
07-28 12:31:15.275   937  1149 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:31:15.275   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:31:15.275   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:31:15.285  8341  8341 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,07-28 12:31:15.295  8341  8341 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-28 12:31:15.295  8341  8341 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:31:15.295  8341  8341 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-28 12:31:15.295   361   361 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8341
07-28 12:31:15.295   361   361 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
07-28 12:31:15.295  8341  8341 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:31:15.295  8341  8341 I wpa_supplicant: ssSupport state is = 1
,07-28 12:31:15.295  8341  8341 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:31:15.295  8341  8341 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-28 12:31:15.295   361   361 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8341
07-28 12:31:15.295   361   361 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
07-28 12:31:15.295  8341  8341 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,07-28 12:31:15.295  8341  8341 I wpa_supplicant: ssSupport state is = 1
07-28 12:31:15.295  8341  8341 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:31:15.295  8341  8341 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:31:15.295  8341  8341 E wpa_supplicant: SIM READ ERROR
07-28 12:31:15.295  8341  8341 I wpa_supplicant: wpa_default_ap_write_once
07-28 12:31:15.295  8341  8341 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,07-28 12:31:15.295  8341  8341 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 12:31:15.315  8341  8341 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
07-28 12:31:15.315  8341  8341 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-28 12:31:15.325  8341  8341 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
07-28 12:31:15.325  8341  8341 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,07-28 12:31:15.325   937  1152 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-28 12:31:15.325   937  1152 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-28 12:31:15.325  8341  8341 I wpa_supplicant: HOTSPOT20_ENABLE called
07-28 12:31:15.325  8341  8341 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:31:15.325  8341  8341 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:31:15.325  8341  8341 E wpa_supplicant: SIM READ ERROR
07-28 12:31:15.325  8341  8341 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:31:15.345  8341  8341 I wpa_supplicant: Skip scan - bUseNetwork false
,07-28 12:31:15.355  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:31:15.355  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-28 12:31:15.355  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:31:15.355  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:31:15.355  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:31:15.355  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:31:15.355  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:31:15.355  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:31:15.355  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:31:15.355  1194  1194 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:31:15.355  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:31:15.355  1194  1194 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:31:15.355  1194  1194 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,07-28 12:31:15.355  1194  1583 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-28 12:31:15.355   937   937 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:31:15.355   937  1152 D WifiNative-HAL: callSECApiInt - ID [210]
,07-28 12:31:15.355   937  1156 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-28 12:31:15.355   937  1152 D WifiConfigStore: Loading config and enabling all networks 
,07-28 12:31:15.355  1194  1194 D HotspotTile: onReceive : 3, 0
,07-28 12:31:15.355  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:15.355  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:15.355  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:15.355  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:31:15.355  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:15.355  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:15.355  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:15.355  7429  7429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:31:15.365  7429  7429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:31:15.365  1315  1315 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:31:15.365   937  1152 E WifiConfigStore: Not a HS20
,07-28 12:31:15.365  7038  7038 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:31:15.375   937  1147 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:15.375  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:31:15.375  6889  6889 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:31:15.375  6889  6889 D SecurityLogAgent: StateMachine : Current State = 1
,07-28 12:31:15.375  6889  6889 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:31:15.375   937  1152 E WifiConfigStore: Not a HS20
,07-28 12:31:15.385   937  1152 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-28 12:31:15.385   937  1152 D WifiNative-HAL: callSECApiInt - ID [65]
,07-28 12:31:15.395   937  1152 D WifiNative-HAL: callSECApiBoolean - ID [13]
,07-28 12:31:15.395  8341  8341 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-28 12:31:15.395  8341  8341 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-28 12:31:15.395  8341  8341 I wpa_supplicant: reset timer : RESET_TIMER 0
07-28 12:31:15.395  8341  8341 I wpa_supplicant: P2P: Current p2p state = IDLE
07-28 12:31:15.395  8341  8341 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-28 12:31:15.395  8341  8341 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-28 12:31:15.395  8341  8341 I wpa_supplicant: First Scan Start
,07-28 12:31:15.395  8341  8341 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-28 12:31:15.395   937  1152 D WifiNative-HAL: Setting external_sim to 1
07-28 12:31:15.395  7611  7611 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:31:15.395   937  1152 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:31:15.395   937  1152 I WifiNative-HAL: startHal
07-28 12:31:15.395   937  1152 E wifi    : getStaticLongField sWifiHalHandle 0x931dd86c
07-28 12:31:15.395   937  1152 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x901d02
07-28 12:31:15.395   937  1152 I WifiNative-HAL: Could not start hal
,07-28 12:31:15.415   937  1152 E native  : do suspend true
,07-28 12:31:15.415  8248  8298 D bt_vendor: op for 7
,07-28 12:31:15.415   937  1151 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-28 12:31:15.415   298  1058 D CommandListener: Setting iface cfg
07-28 12:31:15.415   937   937 D WifiScanningService: SCAN_AVAILABLE : 3
07-28 12:31:15.415   298  1058 D CommandListener: Trying to bring up p2p0
07-28 12:31:15.415   937   937 D RttService: SCAN_AVAILABLE : 3
07-28 12:31:15.415   937  1169 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.415   937  1169 I WifiNative-HAL: startHal
07-28 12:31:15.415   937  1169 E wifi    : getStaticLongField sWifiHalHandle 0x9c5d399c
07-28 12:31:15.415   937  1169 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x801ce2
07-28 12:31:15.415   937  1169 I WifiNative-HAL: Could not start hal
07-28 12:31:15.415   937  1169 E WifiScanningService: could not start HAL
07-28 12:31:15.415   937  1170 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:15.415   937  1152 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,07-28 12:31:15.415   937  1151 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-28 12:31:15.415   937  1151 D WifiP2pService: P2pEnablingState
,07-28 12:31:15.415   937  1151 D WifiP2pService: P2pEnablingState{ what=147457 }
,07-28 12:31:15.415   937  1152 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
07-28 12:31:15.415   937  1152 D WifiNative-HAL: callSECStringApiVoid - ID [215]
07-28 12:31:15.425   937  1151 D WifiP2pService: P2p socket connection successful
07-28 12:31:15.425   937  1151 D WifiP2pService: P2pEnabledState
,07-28 12:31:15.425   937  1152 E WifiNative-HAL: invaild command id : 215
,07-28 12:31:15.425   937   937 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-28 12:31:15.425   937  1062 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-28 12:31:15.425   937  1062 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:31:15.425   937  1062 D WifiDisplayController: disconnect
07-28 12:31:15.425  7596  7596 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-28 12:31:15.425   937  1062 D WifiDisplayController: updateConnection
07-28 12:31:15.425   937  1062 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:31:15.425   937  1062 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-28 12:31:15.425   937  1151 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-28 12:31:15.435   937  1154 E ConnectivityService: updateNetworkInfo()
07-28 12:31:15.435   937  1154 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-28 12:31:15.435   937  1062 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:15.435   937  1062 D WifiDisplayAdapter: onP2pDisconnected
07-28 12:31:15.435   937  1062 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-28 12:31:15.435   937  1062 D IpRemoteDisplayController: WfdBridgeServer is already null
07-28 12:31:15.435  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:31:15.435  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:31:15.435   937  1737 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:15.435  1194  1194 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-28 12:31:15.435   937  1537 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-28 12:31:15.435  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:31:15.435  1194  1194 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
07-28 12:31:15.435   937  1242 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:15.435  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:31:15.435  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:31:15.435  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:31:15.435  1315  2678 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:31:15.445  7165  7165 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-28 12:31:15.445  7596  7596 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:31:15.445  7596  7596 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
07-28 12:31:15.445  7596  7596 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-28 12:31:15.445  7596  7596 D WifiDirectBR: stopServiceTest : false
,07-28 12:31:15.465  8341  8341 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-28 12:31:15.485  8341  8341 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-28 12:31:15.485   937  1152 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:31:15.485   937  1152 D SecContentProvider2: mCursor = null
,07-28 12:31:15.485   937  1151 D WifiNative-HAL: p2pGetDeviceAddress
07-28 12:31:15.485   937  1151 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:de:28:a3
,07-28 12:31:15.485   937  1062 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
07-28 12:31:15.485   937  1062 D WifiDisplayController:  deviceAddress: ea:50:8b:de:28:a3
07-28 12:31:15.485   937  1062 D WifiDisplayController:  primary type: 10-0050F204-5
07-28 12:31:15.485   937  1062 D WifiDisplayController:  secondary type: null
07-28 12:31:15.485   937  1062 D WifiDisplayController:  wps: 0
07-28 12:31:15.485   937  1062 D WifiDisplayController:  grpcapab: 0
07-28 12:31:15.485   937  1062 D WifiDisplayController:  devcapab: 0
07-28 12:31:15.485   937  1062 D WifiDisplayController:  status: 3
07-28 12:31:15.485   937  1062 D WifiDisplayController:  wfdInfo: null
07-28 12:31:15.485   937  1062 D WifiDisplayController:  groupownerAddress: null
07-28 12:31:15.485   937  1062 D WifiDisplayController:  GOdeviceName: null
07-28 12:31:15.485   937  1062 D WifiDisplayController:  interfaceAddress: 
07-28 12:31:15.485   937  1062 D WifiDisplayController:  SConnectInfo : null
,07-28 12:31:15.485   937  1151 D WifiP2pService: DeviceAddress: ea:28:a3
,07-28 12:31:15.485   937  1152 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:31:15.485   937  1152 D SecContentProvider2: mCursor = null
,07-28 12:31:15.505   937  1151 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-28 12:31:15.505   937  1151 D WifiP2pService: InactiveState
07-28 12:31:15.505   937  1151 D WifiP2pService: InactiveState{ what=143376 }
,07-28 12:31:15.505   937  1151 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-28 12:31:15.505  8341  8341 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-28 12:31:15.505   937  1151 D WifiP2pService: InactiveState{ what=143376 }
,07-28 12:31:15.505   937  1151 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-28 12:31:15.615  8248  8309 D bt_upio : ..proc_btwrite_timeout..
,07-28 12:31:15.985  7429  7490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:31:15.985  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:15.985  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:15.985  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:31:15.985  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:15.985  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:15.985  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:15.985  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:31:15.995  7429  7490 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:31:16.005  7429  7490 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-28 12:31:16.005  7429  7490 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-28 12:31:16.005  7429  7490 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2e0a4499 Bundle[{}]
,07-28 12:31:16.015  7429  7490 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-28 12:31:16.015  7429  7490 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-28 12:31:16.015  7429  7490 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-28 12:31:16.015  7429  7490 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-28 12:31:16.015  7429  7490 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-28 12:31:16.015  7429  7490 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-28 12:31:16.015  7429  7490 I System.out: Running OutgoingSocketThread
,07-28 12:31:16.025  7429  8367 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1328)
,07-28 12:31:16.025  7429  8367 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46266
,07-28 12:31:16.025  7429  8367 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-28 12:31:16.215  8341  8341 I wpa_supplicant: nl80211: Received scan results (18 BSSes)
07-28 12:31:16.215  8341  8341 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-28 12:31:16.215  8341  8341 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
07-28 12:31:16.215  8341  8341 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
07-28 12:31:16.215  8341  8341 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=5 BSSID=00.00.00 SSID=4E47373030
,07-28 12:31:16.225   937  1152 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-28 12:31:16.235   937  1152 D SecContentProvider2: mCursor = null
,07-28 12:31:16.285  8341  8341 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
07-28 12:31:16.285  8341  8341 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=6 BSSID=00.00.00 SSID=4E47373030
,07-28 12:31:16.285  8341  8341 I wpa_supplicant: Associated with F4.99.3E
07-28 12:31:16.285  8341  8341 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
07-28 12:31:16.285  8341  8341 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=7 BSSID=F4.99.3E SSID=4E47373030
,07-28 12:31:16.285   937  1152 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-28 12:31:16.285   937  1152 D SecContentProvider2: mCursor = null
,07-28 12:31:16.285   937  1152 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-28 12:31:16.295   937  1152 D SecContentProvider2: mCursor = null
,07-28 12:31:16.295  8341  8341 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,07-28 12:31:16.295  8341  8341 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
07-28 12:31:16.295  8341  8341 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=8 BSSID=F4.99.3E SSID=4E47373030
,07-28 12:31:16.305  8341  8341 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:31:16.305  8341  8341 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
07-28 12:31:16.305  8341  8341 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=1 id_str=]
07-28 12:31:16.305  8341  8341 I wpa_supplicant: Blacklist: Clear (temp) 
07-28 12:31:16.305  8341  8341 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=9 BSSID=F4.99.3E SSID=4E47373030
07-28 12:31:16.305   937  1152 D WifiNative-HAL: callSECApiVoid - ID [50]
07-28 12:31:16.305  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:31:16.305  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-28 12:31:16.315   937  1152 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
07-28 12:31:16.315   937  1152 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:31:16.315   937  1154 D ConnectivityService: Got NetworkAgent Messenger
07-28 12:31:16.315   937  1154 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
07-28 12:31:16.315   937  1154 E ConnectivityService: updateNetworkInfo()
07-28 12:31:16.315   937  1154 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:31:16.315   937  1154 D ConnectivityService: NetworkAgent connected
07-28 12:31:16.325  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-28 12:31:16.325  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:31:16.325   937  1147 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:16.325  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-28 12:31:16.325   937  1479 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:16.325  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:31:16.325  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:31:16.325  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:31:16.325   937  1152 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:31:16.335  1315  2678 V NearbySettings: MountReceiver.mPrefHandler - 7002
07-28 12:31:16.335   298  1058 D CommandListener: Setting iface cfg
07-28 12:31:16.345   937  1152 E WifiStateMachine: Start Dhcp Watchdog 3
07-28 12:31:16.345   937  1152 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:31:16.345   937  1152 D SecContentProvider2: mCursor = null
07-28 12:31:16.355   937   954 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:16.355  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:31:16.355  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-28 12:31:16.355   937  1154 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
07-28 12:31:16.355   937  1152 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:31:16.355   937  1152 D SecContentProvider2: mCursor = null
07-28 12:31:16.365  7038  7038 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:31:16.435   937  1152 E native  : do suspend false
,07-28 12:31:16.445   937  1151 D WifiP2pService: InactiveState{ what=143375 }
,07-28 12:31:16.445   937  1151 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-28 12:31:16.655  8372  8372 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-28 12:31:16.655  8372  8372 I dhcpcd  : version 5.5.6 starting
,07-28 12:31:16.655  8372  8372 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-28 12:31:16.715  8372  8372 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-28 12:31:16.725  8372  8372 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
07-28 12:31:16.725  8372  8372 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
07-28 12:31:16.725  8372  8372 I dhcpcd  : bssid match
07-28 12:31:16.725  8372  8372 I dhcpcd  : wlan0: rebinding lease of 192.168.1.122
,07-28 12:31:16.735  8372  8372 I dhcpcd  : wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,07-28 12:31:16.735  8372  8372 I dhcpcd  : wlan0: leased 192.168.1.122 for 172800 seconds
,07-28 12:31:16.735   937  1154 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-28 12:31:17.015   303   303 E SMD     : DCD ON
,07-28 12:31:17.025  7429  7490 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1329)
07-28 12:31:17.025  7429  7490 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1329)
07-28 12:31:17.025  7429  7490 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1334)
07-28 12:31:17.025  7429  7490 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
07-28 12:31:17.025  7429  7490 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1335)
07-28 12:31:17.025  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:31:17.025  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc5be9 added. We now have 2 listener(s)
,07-28 12:31:17.025  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:31:17.025  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:31:17.025  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:17.025  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:31:17.025  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35aa506e added. We now have 9 listener(s)
07-28 12:31:17.025  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:31:17.035  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:31:17.035  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:31:17.035  7429  7490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:31:17.035  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:17.035  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:17.035  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:31:17.035  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:17.035  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:17.035  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:17.035  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:31:17.035  7429  7490 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:31:17.035  7429  7490 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:31:17.035  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:31:17.035  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb53f9c added. We now have 3 listener(s)
,07-28 12:31:17.035  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:17.035  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:17.035  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:31:17.035  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:31:17.035  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:17.035  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:17.035  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3135cda5 added. We now have 10 listener(s)
07-28 12:31:17.035  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:17.035  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:31:17.035  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:31:17.035  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:31:17.035  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:17.035  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:31:17.035  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:31:17.035  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:31:17.035  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23fc5be9 removed from the list
07-28 12:31:17.035  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:17.035  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35aa506e removed from the list
07-28 12:31:17.035  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:31:17.035  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:31:17.035  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:17.035  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:31:17.045  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:17.045  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:31:17.045  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:17.045  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35aa506e not in the list
07-28 12:31:17.045  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:17.045  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:31:17.045  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:17.045  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:17.045  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:17.045  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3135cda5 removed from the list
,07-28 12:31:17.045  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:17.045  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:17.045  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:17.045  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:31:17.045  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb53f9c removed from the list
,07-28 12:31:17.045  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:31:17.045  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2f057a added. We now have 2 listener(s)
,07-28 12:31:17.045  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:31:17.045  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:31:17.045  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:17.045  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:17.045  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0cb12b added. We now have 9 listener(s)
07-28 12:31:17.045  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:31:17.045  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:31:17.045   937  1152 E native  : do suspend true
07-28 12:31:17.045  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:31:17.055  7429  7490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:31:17.055  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:17.055  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:17.055  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:31:17.055  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:17.055  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:17.055  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:17.055  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:31:17.055  7429  7490 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:31:17.055  7429  7490 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:31:17.055  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:31:17.055  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 12:31:17.055  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3da9f21 added. We now have 3 listener(s)
,07-28 12:31:17.055  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:17.055  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:31:17.055  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:31:17.055  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:17.055  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:17.055  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3517ff46 added. We now have 10 listener(s)
07-28 12:31:17.055  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:17.055  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:31:17.055  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:31:17.055  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:31:17.055  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:31:17.055  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 12:31:17.055  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 12:31:17.055   937  1151 D WifiP2pService: InactiveState{ what=143375 }
07-28 12:31:17.055   937  1151 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-28 12:31:17.065  7429  7490 E BluetoothAdapter: bluetooth le advertising not supported
07-28 12:31:17.065  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:31:17.065  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:31:17.065  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-28 12:31:17.065  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:31:17.065   937  1154 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-28 12:31:17.065  7429  7490 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-28 12:31:17.065  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:31:17.065  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:31:17.065  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:31:17.065  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:31:17.065  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:31:17.065  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:31:17.065  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:31:17.065   937  1152 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-28 12:31:17.065   937  1152 E WifiStateMachine: VerifyingLinkState enter
07-28 12:31:17.065  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:31:17.065  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:17.065  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:31:17.065  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:31:17.065  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2f057a removed from the list
07-28 12:31:17.065  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:17.065  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0cb12b removed from the list
,07-28 12:31:17.065  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:31:17.065  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:17.065   937  1152 D WifiNative-HAL: callSECApiInt - ID [210]
07-28 12:31:17.075  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:31:17.075  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:31:17.075  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:17.075  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:17.075   937  1154 E ConnectivityService: updateNetworkInfo()
07-28 12:31:17.075  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:17.075  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0cb12b not in the list
07-28 12:31:17.075  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:31:17.075  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:17.075   937  1154 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-28 12:31:17.075   937  1154 D ConnectivityService: Adding iface wlan0 to network 504
07-28 12:31:17.075  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:17.075  7429  7490 D BluetoothLeScanner: could not find callback wrapper
07-28 12:31:17.075  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:31:17.075  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:17.075  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:17.075  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3517ff46 removed from the list
07-28 12:31:17.075  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:17.075  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:17.075  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:17.075  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:31:17.075  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3da9f21 removed from the list
07-28 12:31:17.075  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:31:17.075  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35a10c5d added. We now have 2 listener(s)
,07-28 12:31:17.075  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:31:17.075   937  1164 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-28 12:31:17.075   937  1164 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-28 12:31:17.075  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:31:17.075  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:17.075  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:17.075  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1444c9d2 added. We now have 9 listener(s)
07-28 12:31:17.075  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:17.075  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:31:17.085  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:31:17.085   937  1164 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-28 12:31:17.085   937  1164 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-28 12:31:17.085  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:31:17.085   937  1164 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-28 12:31:17.095  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:31:17.095  7429  7490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:31:17.095  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:17.095  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:17.095  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:31:17.095  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:17.095  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:17.095  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:17.095  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:31:17.095  7429  7490 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:31:17.105  7429  7490 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:31:17.105  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 12:31:17.105  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:17.105  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:17.105  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@205f31a0 added. We now have 3 listener(s)
,07-28 12:31:17.105   937  1152 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,07-28 12:31:17.105  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:31:17.115  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-28 12:31:17.115  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:17.115  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:17.115  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b671159 added. We now have 10 listener(s)
07-28 12:31:17.115  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:17.115  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 12:31:17.115   937   937 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-28 12:31:17.115  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:31:17.115  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:31:17.115  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:31:17.115  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:31:17.115  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 12:31:17.115  1194  1194 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:31:17.115  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:31:17.115   937   937 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-28 12:31:17.115   937   937 I WifiTrafficPoller: mBoosterFLAG : 0
07-28 12:31:17.115   937   937 I WifiTrafficPoller: current booster mode : FullMode
07-28 12:31:17.115   937   937 D WifiNative-HAL: callSECApiVoid - ID [212]
,07-28 12:31:17.125  1194  1194 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:31:17.125  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-28 12:31:17.125  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-28 12:31:17.125  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:31:17.125  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-28 12:31:17.125  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:31:17.125  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:31:17.125  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:31:17.125  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-28 12:31:17.125  1194  1194 D StatusBar.NetworkController: applyOpen
,07-28 12:31:17.125   937  1152 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-28 12:31:17.135  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 12:31:17.135   937  1154 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,07-28 12:31:17.135   937  1154 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,07-28 12:31:17.135   937  1154 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 504
,07-28 12:31:17.135   937  1154 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-28 12:31:17.135   937  1154 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-28 12:31:17.135   937  1154 D ConnectivityService: updateSourceRoutes : add src route for:192.168.1.122
,07-28 12:31:17.135   298  1058 V         : QcRouteController
,07-28 12:31:17.135  7429  7490 E BluetoothAdapter: bluetooth le advertising not supported
,07-28 12:31:17.135  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 12:31:17.135  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:31:17.145  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-28 12:31:17.145  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:31:17.145  7429  7490 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-28 12:31:17.145  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-28 12:31:17.145  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:31:17.145  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:31:17.145  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:31:17.145  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:17.145  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:17.145  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:31:17.145  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-28 12:31:17.145  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35a10c5d removed from the list
07-28 12:31:17.145  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:31:17.155  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1444c9d2 removed from the list
,07-28 12:31:17.155  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:31:17.155  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:31:17.155  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:17.155   298  1058 V         : QcRouteController
,07-28 12:31:17.155  1315  1315 I NearbySettings: MountReceiver.onReceive - Keep current state
07-28 12:31:17.155  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:31:17.155  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:17.155  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:17.155  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:31:17.155  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1444c9d2 not in the list
,07-28 12:31:17.165  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:31:17.165  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:31:17.165  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:17.165  7429  7490 D BluetoothLeScanner: could not find callback wrapper
07-28 12:31:17.165  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:31:17.165  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:17.165  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:17.165   937  1471 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:17.165  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b671159 removed from the list
07-28 12:31:17.165  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:17.165  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:17.165  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:17.165  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-28 12:31:17.165  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@205f31a0 removed from the list
,07-28 12:31:17.175  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 12:31:17.175  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2015c7cc added. We now have 2 listener(s)
,07-28 12:31:17.175   298  1058 V         : QcRouteController
,07-28 12:31:17.175  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:31:17.175  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:31:17.175  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:17.175  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:17.175  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fee6a15 added. We now have 9 listener(s)
07-28 12:31:17.175  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:17.175  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:31:17.175  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:31:17.185  7038  7038 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:31:17.185  7429  7490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:31:17.185  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:17.185  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:17.185  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:31:17.185  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:17.185  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:17.185  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:17.185  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:31:17.185  7429  7490 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:31:17.185  7429  7490 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:31:17.185  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:31:17.185  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23c03b1b added. We now have 3 listener(s)
,07-28 12:31:17.185  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:31:17.185  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:31:17.185  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:17.185  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:17.185  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cbd94b8 added. We now have 10 listener(s)
07-28 12:31:17.185  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:31:17.185  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:31:17.185  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:31:17.185  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:31:17.185  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:31:17.185  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 12:31:17.185  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:17.195  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:17.195  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-28 12:31:17.195  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 12:31:17.195   298  1058 V         : QcRouteController
,07-28 12:31:17.195  1315  1315 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-28 12:31:17.195  7429  7490 E BluetoothAdapter: bluetooth le advertising not supported
,07-28 12:31:17.195  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:31:17.195  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:31:17.195   937  1648 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.195  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-28 12:31:17.205  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:31:17.205  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:31:17.205  7429  7490 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-28 12:31:17.205  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:31:17.205   937  1472 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:17.205  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:31:17.205  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:31:17.205  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:17.205  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:17.205  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:31:17.205  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-28 12:31:17.205  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2015c7cc removed from the list
07-28 12:31:17.205  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:17.205  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fee6a15 removed from the list
,07-28 12:31:17.205  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:31:17.205  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:31:17.205  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:17.205  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:31:17.205  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,07-28 12:31:17.205  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:17.205  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:17.205  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:17.205  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fee6a15 not in the list
,07-28 12:31:17.205  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:17.205  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:17.205  1315  1315 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,07-28 12:31:17.215  1315  1315 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:31:17.215  1315  2678 V NearbySettings: MountReceiver.mPrefHandler - 7002
07-28 12:31:17.215  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:17.215  7429  7490 D BluetoothLeScanner: could not find callback wrapper
07-28 12:31:17.215  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:31:17.215  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:17.215  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:17.215  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cbd94b8 removed from the list
07-28 12:31:17.215  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:17.215  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:17.215  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:17.215  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:31:17.215  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23c03b1b removed from the list
,07-28 12:31:17.215  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:31:17.215  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@101d6df7 added. We now have 2 listener(s)
,07-28 12:31:17.215  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:31:17.215  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:31:17.215  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:17.215  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:17.215  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18134464 added. We now have 9 listener(s)
07-28 12:31:17.215  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:31:17.215  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:31:17.215   937  1017 W ProcessCpuTracker: Skipping unknown process pid 8419
,07-28 12:31:17.215   298  1058 V         : QcRouteController
,07-28 12:31:17.215  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:31:17.215  7429  7490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:31:17.215  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:31:17.215  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:31:17.215  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:31:17.215  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:31:17.215  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:31:17.215  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:31:17.215  7429  7490 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:31:17.225   937  1017 W ProcessCpuTracker: Skipping unknown process pid 8422
,07-28 12:31:17.225  7429  7490 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:31:17.225  7429  7490 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:31:17.225  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:31:17.225  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a2f4b82 added. We now have 3 listener(s)
,07-28 12:31:17.225  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:17.225  7429  7429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:31:17.225  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:31:17.225  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:31:17.225  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:31:17.225  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:31:17.225  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37b0f293 added. We now have 10 listener(s)
07-28 12:31:17.225  7429  7490 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:31:17.225   937  1737 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.225  7038  7038 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:31:17.235  7429  7490 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:31:17.235  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:31:17.235  7429  7490 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:31:17.235  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:17.235  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:17.235  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:31:17.235  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:31:17.235  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@101d6df7 removed from the list
07-28 12:31:17.235  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:17.235  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18134464 removed from the list
07-28 12:31:17.235  7429  7490 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:31:17.235  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:31:17.235   298  1058 V         : QcRouteController
,07-28 12:31:17.235  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:17.235  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:31:17.235  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:17.235  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:17.235  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:17.235  7429  7490 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18134464 not in the list
07-28 12:31:17.235  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:17.235  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:31:17.235  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:31:17.235  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:31:17.235  7429  7490 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:31:17.235  7429  7490 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37b0f293 removed from the list
07-28 12:31:17.235  7429  7490 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:31:17.235  7429  7490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:31:17.235  7429  7490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:31:17.235  7429  7490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:31:17.235  7429  7490 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a2f4b82 removed from the list
,07-28 12:31:17.235  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-28 12:31:17.235  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-28 12:31:17.235  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-28 12:31:17.235   298  1058 V         : QcRouteController
07-28 12:31:17.235  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:31:17.235  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-28 12:31:17.235  7429  7490 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:31:17.235  1315  1315 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-28 12:31:17.245  1315  1315 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-28 12:31:17.245   937  1537 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,07-28 12:31:17.245  7429  8435 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1342, name: My test thread name)
,07-28 12:31:17.245  7429  8435 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1342, thread name: My test thread name)
07-28 12:31:17.245  7429  8435 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1342, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,07-28 12:31:17.255   937  1434 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.255  7429  8436 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1344, name: My test thread name)
,07-28 12:31:17.255  7429  8436 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1344, thread name: My test thread name)
07-28 12:31:17.255  7429  8436 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1344, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,07-28 12:31:17.255  7429  7490 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,07-28 12:31:17.255  7429  7490 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
07-28 12:31:17.255  7429  7490 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-28 12:31:17.255  7429  7490 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,07-28 12:31:17.255  7429  7490 D com.test.thalitest.ThaliTestRunner: Total duration: 23897 ms
,07-28 12:31:17.255  7038  7038 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
07-28 12:31:17.255  7429  7490 I jxcore-log: Total number of executed tests:  80
07-28 12:31:17.255  7429  7490 I jxcore-log: 
,07-28 12:31:17.255  7429  7490 I jxcore-log: Number of passed tests:  80
07-28 12:31:17.255  7429  7490 I jxcore-log: 
07-28 12:31:17.255  7429  7490 I jxcore-log: Number of failed tests:  0
07-28 12:31:17.255  7429  7490 I jxcore-log: 
07-28 12:31:17.255  7429  7490 I jxcore-log: Number of ignored tests:  0
07-28 12:31:17.255  7429  7490 I jxcore-log: 
07-28 12:31:17.255  7429  7490 I jxcore-log: Total duration:  23897
07-28 12:31:17.255  7429  7490 I jxcore-log: 
,07-28 12:31:17.255  7429  7490 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
07-28 12:31:17.255  7429  7490 I jxcore-log: 
,07-28 12:31:17.265  7429  7490 I jxcore-log: Unit Test app is loaded
07-28 12:31:17.265  7429  7490 I jxcore-log: 
07-28 12:31:17.265   298  1058 V         : QcRouteController
07-28 12:31:17.265  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:31:17.265  7429  7490 I jxcore-log: 
07-28 12:31:17.265  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:31:17.265  7429  7490 I jxcore-log: 
07-28 12:31:17.275  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:31:17.275  7429  7490 I jxcore-log: 
07-28 12:31:17.275   267   267 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
07-28 12:31:17.275  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:31:17.275  7429  7490 I jxcore-log: 
07-28 12:31:17.275  7429  7429 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-28 12:31:17.275  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:31:17.275  7429  7490 I jxcore-log: 
07-28 12:31:17.275  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:31:17.275  7429  7490 I jxcore-log: 
07-28 12:31:17.275  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:31:17.275  7429  7490 I jxcore-log: 
,07-28 12:31:17.275  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:31:17.275  7429  7490 I jxcore-log: 
,07-28 12:31:17.285  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:31:17.285  7429  7490 I jxcore-log: 
07-28 12:31:17.285   937  1154 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
07-28 12:31:17.285   937  1154 D ConnectivityService: LTETest block dns file not exists
07-28 12:31:17.285  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:31:17.285  7429  7490 I jxcore-log: 
,07-28 12:31:17.285   937  1154 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-28 12:31:17.285   937  1154 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
07-28 12:31:17.285   937  1154 D ConnectivityService: calling update connectivity
07-28 12:31:17.285   937  1154 E ConnectivityService: updateNetworkInfo()
07-28 12:31:17.285   937  1154 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-28 12:31:17.285   937  1154 E ConnectivityService: updateNetworkInfo()
07-28 12:31:17.285   937  1154 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-28 12:31:17.285   937  1154 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:31:17.285   937  8368 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:17.285   937  1154 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
07-28 12:31:17.285   937  8368 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
07-28 12:31:17.285   937  1154 D ConnectivityService: calling update connectivity
07-28 12:31:17.285   937  8368 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:31:17.285   937  1154 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
07-28 12:31:17.285   937  8368 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-28 12:31:17.285   937  1154 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:31:17.285   937  1061 D EntConnectivity: Not allowed due to - mEnabled false
07-28 12:31:17.285   937  1154 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:31:17.285   937  1154 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:17.285   937  1154 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:31:17.285   937  8368 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-28 12:31:17.285   937   954 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=937
,07-28 12:31:17.285   937  1154 D ConnectivityService: currentScore = 0, newScore = 60
07-28 12:31:17.285   937  1154 D ConnectivityService:    accepting network in place of null
07-28 12:31:17.285   937  1154 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:31:17.285  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 12:31:17.285  7429  7490 I jxcore-log: 
,07-28 12:31:17.295   937  1154 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-28 12:31:17.295   937  1154 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
07-28 12:31:17.295   937  1154 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-28 12:31:17.295  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:31:17.295  7429  7490 I jxcore-log: 
,07-28 12:31:17.295  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:31:17.295  7429  7490 I jxcore-log: 
,07-28 12:31:17.295  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:31:17.295  7429  7490 I jxcore-log: 
,07-28 12:31:17.295  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:31:17.295  7429  7490 I jxcore-log: 
,07-28 12:31:17.295  1429  1429 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:31:17.295   937  1155 D Tethering: MasterInitialState.processMessage what=3
07-28 12:31:17.295   937  1154 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:17.295   937  1154 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
07-28 12:31:17.295   937   937 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:31:17.295   937  1156 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-28 12:31:17.295   937  1156 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:31:17.295   937  1156 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:31:17.295   937  1156 D SmartBondingService: getSBEnabled() enabled =false
,07-28 12:31:17.295   937  1156 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-28 12:31:17.295   937  1149 V NetworkStats: updateIfacesLocked()
07-28 12:31:17.295   937  1149 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:31:17.295   937  1149 V NetworkStats: performPollLocked(flags=0x1)
07-28 12:31:17.295   937  1149 D NetworkStatsFactory: UpdateStatsForKnox
07-28 12:31:17.295   937  1149 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.295  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:31:17.295  7429  7490 I jxcore-log: 
07-28 12:31:17.295  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:31:17.295  7429  7490 I jxcore-log: 
,07-28 12:31:17.295   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:31:17.295  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:31:17.295  7429  7490 I jxcore-log: 
07-28 12:31:17.295  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:31:17.295  7429  7490 I jxcore-log: 
07-28 12:31:17.295   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:31:17.295   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:31:17.295  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:31:17.295  7429  7490 I jxcore-log: 
07-28 12:31:17.295   937  1150 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-28 12:31:17.305   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:31:17.305   937  3040 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.305  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:31:17.305  7429  7490 I jxcore-log: 
07-28 12:31:17.305   937  1149 V NetworkStats: performPollLocked() took 8ms
07-28 12:31:17.305   937  1149 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:31:17.305  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:31:17.305  7429  7490 I jxcore-log: 
07-28 12:31:17.305   937  1364 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.305  1194  1194 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-28 12:31:17.305  1194  1194 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-28 12:31:17.305  1194  1194 D StatusBar.NetworkController: updateDataNetType()
07-28 12:31:17.305  1194  1194 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-28 12:31:17.305  1194  1194 E StatusBar.NetworkController: updateLTEICONDataNetType:0
07-28 12:31:17.305  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:31:17.305  7429  7490 I jxcore-log: 
,07-28 12:31:17.305   937  1061 D EntConnectivity: Not allowed due to - mEnabled false
07-28 12:31:17.305   937  1154 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
07-28 12:31:17.305   937  1154 D ConnectivityService: calling update connectivity
07-28 12:31:17.305  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:31:17.305  7429  7490 I jxcore-log: 
07-28 12:31:17.305   937  1154 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:17.305   937  1154 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-28 12:31:17.305   937  1154 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:31:17.305  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:31:17.305  7429  7490 I jxcore-log: 
07-28 12:31:17.305   937  1154 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:31:17.305  1194  1580 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:31:17.305   937  1154 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:17.305  1194  1194 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-28 12:31:17.305  1194  1194 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
07-28 12:31:17.305  1194  1194 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-28 12:31:17.305  1194  1194 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:31:17.305  4453  7281 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:31:17.305  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-28 12:31:17.305  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:31:17.305  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:31:17.305  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:31:17.305  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:31:17.305  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:31:17.305  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:31:17.305  1194  1194 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:31:17.305  1194  1194 D StatusBar.NetworkController: applyOpen
07-28 12:31:17.305   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:31:17.305   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:31:17.315  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:31:17.315  7429  7490 I jxcore-log: 
,07-28 12:31:17.315  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:31:17.315  7429  7490 I jxcore-log: 
07-28 12:31:17.315  7429  7490 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:31:17.315  7429  7490 I jxcore-log: 
,07-28 12:31:17.315  7429  7490 I jxcore-log: My device name is: samsung-SM-N9005
07-28 12:31:17.315  7429  7490 I jxcore-log: 
,07-28 12:31:17.315  7429  7490 I jxcore-log: WARN testUtils: myNameCallback not set!
07-28 12:31:17.315  7429  7490 I jxcore-log: 
,07-28 12:31:17.385   937  8368 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,07-28 12:31:17.465   937  8368 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jul 2016 10:31:17 GMT], X-Android-Received-Millis=[1469701877473], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469701877433]}
07-28 12:31:17.465   937  8368 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-28 12:31:17.465   937  8368 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,07-28 12:31:17.465   937  1154 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
07-28 12:31:17.465   937  1154 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
07-28 12:31:17.465   937  1154 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:31:17.465   937  1154 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:31:17.465   937  1154 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:17.465   937  1154 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
07-28 12:31:17.465   937  1154 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
07-28 12:31:17.465   937  1154 D ConnectivityService: calling update connectivity
07-28 12:31:17.465   937  1154 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:17.465   937  1154 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:31:17.465   937  1154 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-28 12:31:17.465   937  1154 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:17.465  1194  1580 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:31:17.465   937  1154 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:31:17.465   937  1154 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-28 12:31:17.465  4453  7281 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-28 12:31:17.465   937  1737 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.465  1194  1194 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-28 12:31:17.465  1194  1194 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-28 12:31:17.465  1194  1194 D StatusBar.NetworkController: updateDataNetType()
07-28 12:31:17.465  1194  1194 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-28 12:31:17.465  1194  1194 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-28 12:31:17.475  1194  1194 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,07-28 12:31:17.475  1194  1194 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
07-28 12:31:17.475  1194  1194 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-28 12:31:17.475  1194  1194 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:31:17.475  1194  1194 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-28 12:31:17.505  8444  8444 D AndroidRuntime: 
07-28 12:31:17.505  8444  8444 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-28 12:31:17.515  8444  8444 D AndroidRuntime: CheckJNI is OFF
,07-28 12:31:17.515  8444  8444 D AndroidRuntime: readGMSProperty: start
07-28 12:31:17.515  8444  8444 D AndroidRuntime: readGMSProperty: already setted!!
,07-28 12:31:17.515  8444  8444 D AndroidRuntime: readGMSProperty: end
07-28 12:31:17.515  8444  8444 D AndroidRuntime: addProductProperty: start
,07-28 12:31:17.645  8444  8444 E AffinityControl: AffinityControl: registerfunction enter
,07-28 12:31:17.665  8444  8444 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-28 12:31:17.675   937  3040 D PackageManager: START PACKAGE DELETE: observer{452570458}
07-28 12:31:17.675   937  3040 D PackageManager: pkg{<packageName>}
07-28 12:31:17.675   937  3040 D PackageManager: user{0}
07-28 12:31:17.675   937  3040 D PackageManager: caller{2000}
07-28 12:31:17.675   937  3040 D PackageManager: flags{2}
,07-28 12:31:17.675   937  3040 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-28 12:31:17.675   937  3040 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,07-28 12:31:17.675   937  3040 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-28 12:31:17.675   937  3040 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-28 12:31:17.675   937  3040 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,07-28 12:31:17.675   937  1068 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,07-28 12:31:17.675   937  1068 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,07-28 12:31:17.675   937  1068 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-28 12:31:17.675   937  1068 D ApplicationPolicy: getApplicationUninstallationEnabled
07-28 12:31:17.675   937  1068 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,07-28 12:31:17.675   937  1068 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
,07-28 12:31:17.675   937  1017 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
,07-28 12:31:17.685   937  1017 I ActivityManager: Killing 7429:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
,07-28 12:31:17.685   937  1017 I ActivityManager:   Force finishing activity ActivityRecord{26d3209a u0 com.test.thalitest/.MainActivity t99}
,07-28 12:31:17.685   937  1017 D FocusedStackFrame: Set to : 0
,07-28 12:31:17.695   937  1062 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-28 12:31:17.695   937  1062 D PointerIcon: setMouseCustomIcon IconType is same.101
07-28 12:31:17.695   937  1062 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-28 12:31:17.695   937  1062 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-28 12:31:17.695   267  1647 I SurfaceFlinger: id=12 Removed NainActivit (6/9)
,07-28 12:31:17.695   267   417 I SurfaceFlinger: id=12 Removed NainActivit (-2/9)
,07-28 12:31:17.765   937  1068 W PackageSettings: Skipping PackageSetting{30db587f com.example.hello/10078} due to missing metadata
,07-28 12:31:17.785   937  3069 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.795   937  1154 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:31:17.795   937  1068 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
,07-28 12:31:17.815   937  3069 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.825  1587  1587 I art     : Explicit concurrent mark sweep GC freed 689(39KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 19MB/32MB, paused 426us total 24.652ms
,07-28 12:31:17.845  4453  4453 I art     : Explicit concurrent mark sweep GC freed 27091(1601KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 24MB/40MB, paused 780us total 41.791ms
,07-28 12:31:17.855   937   937 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,07-28 12:31:17.855   937  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
07-28 12:31:17.855   937  1062 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,07-28 12:31:17.855   937   937 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,07-28 12:31:17.865  3693  3693 I art     : Explicit concurrent mark sweep GC freed 5482(303KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 15MB/26MB, paused 923us total 29.016ms
,07-28 12:31:17.865   937  1242 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.865  1696  1696 E SamsungIME: mOCRHelper is null
07-28 12:31:17.865   937  1666 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:17.865   937  1737 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.865   937  3040 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.865   937  1434 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.875  1442  1442 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,07-28 12:31:17.875  1442  1442 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-28 12:31:17.875  1442  1442 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-28 12:31:17.875   937   952 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.875  1823  2324 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-28 12:31:17.875  1442  1442 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,07-28 12:31:17.875   937  1666 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:17.875   937  1242 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.875  1442  1442 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:31:17.875  1442  1442 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-28 12:31:17.875  1442  1442 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-28 12:31:17.875   937  1364 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:17.875   937  3040 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.875  7681  7681 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-28 12:31:17.885   937  1253 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:17.885   937  1125 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-28 12:31:17.885   937  1537 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.885   937  1472 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.885  1442  1442 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,07-28 12:31:17.885  1442  1442 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-28 12:31:17.885  1442  1442 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-28 12:31:17.895   937   937 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,07-28 12:31:17.895  5385  5385 I art     : Explicit concurrent mark sweep GC freed 638(36KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 397us total 56.109ms
,07-28 12:31:17.895   937  1014 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,07-28 12:31:17.905   937   937 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,07-28 12:31:17.905  3927  3927 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-28 12:31:17.905   937   937 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,07-28 12:31:17.905  1587  1587 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-28 12:31:17.905  3927  3927 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1469701877914
,07-28 12:31:17.905   937  1149 V NetworkStats: removeUidsLocked() for UIDs [10079]
07-28 12:31:17.905   937  1149 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:31:17.905   937  1149 V NetworkStats: performPollLocked(flags=0x3)
,07-28 12:31:17.915   937  1149 D NetworkStatsFactory: UpdateStatsForKnox
,07-28 12:31:17.915   937  1149 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:17.915  1422  1422 D RegisteredServicesCache: empty dynamic service
,07-28 12:31:17.915  3927  3927 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
,07-28 12:31:17.915  3927  3927 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,07-28 12:31:17.915   937  2991 E libprocessgroup: failed to kill 1 processes for processgroup 7429
,07-28 12:31:17.925   937  1149 V NetworkStats: performPollLocked() took 16ms
07-28 12:31:17.925   937  1149 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:31:17.925   937   937 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,07-28 12:31:17.925   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:31:17.925   937  1150 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:31:17.945   937   937 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,07-28 12:31:17.945   937   937 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-28 12:31:17.955   937   937 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,07-28 12:31:17.965   937  1556 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-28 12:31:17.965   937  1556 D SecContentProvider2: mCursor = null
,07-28 12:31:17.975   937  1014 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
,07-28 12:31:17.985   937   937 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,07-28 12:31:17.995   937   937 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-28 12:31:17.995   937   937 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,07-28 12:31:17.995   937  1014 D EnterpriseDeviceManagerService: Package has changed for user 0
07-28 12:31:17.995   937  1014 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,07-28 12:31:18.015   937   937 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,07-28 12:31:18.015   937  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-28 12:31:18.015   937   937 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,07-28 12:31:18.025  3927  3927 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
,07-28 12:31:18.035  3927  3927 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
07-28 12:31:18.035   937   937 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
07-28 12:31:18.035   937  1472 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
07-28 12:31:18.035   937   937 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
07-28 12:31:18.035   937  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.035   937  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.035   937  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.035   937  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.035   937   937 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
07-28 12:31:18.035   937   937 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
07-28 12:31:18.045   937   937 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,07-28 12:31:18.055   937   937 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,07-28 12:31:18.065   937   937 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,07-28 12:31:18.065   937   937 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-28 12:31:18.075   937   937 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-28 12:31:18.075   937   937 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,07-28 12:31:18.075  8462  8462 E Zygote  : MountEmulatedStorage()
07-28 12:31:18.075   937  1472 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8462 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
07-28 12:31:18.075  8462  8462 E Zygote  : v2
07-28 12:31:18.075  8462  8462 I libpersona: KNOX_SDCARD checking this for 10116
07-28 12:31:18.075  8462  8462 I libpersona: KNOX_SDCARD not a persona
,07-28 12:31:18.085   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:31:18.085   937   937 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,07-28 12:31:18.095   937   937 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
07-28 12:31:18.095  8462  8462 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:31:18.095  8462  8462 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:31:18.095  8462  8462 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-28 12:31:18.095   937   937 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
07-28 12:31:18.095   337   337 I art     : Explicit concurrent mark sweep GC freed 8719(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 2.995ms total 19.327ms
,07-28 12:31:18.105   937   937 D RCPManagerService: PackageReceiver onReceive()
,07-28 12:31:18.105   937   937 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-28 12:31:18.105   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 618us total 10.237ms
,07-28 12:31:18.105   937   937 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,07-28 12:31:18.105   937   937 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-28 12:31:18.105   937   937 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-28 12:31:18.105   937   937 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-28 12:31:18.105   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:31:18.105   937   937 V EnterpriseBillingPolicy: uID is 10079
07-28 12:31:18.105   937  1014 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,07-28 12:31:18.105   937   937 V EnterpriseBillingPolicy: Removed Packageuid is0
07-28 12:31:18.105   937   937 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-28 12:31:18.115   937   937 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
,07-28 12:31:18.115   937   937 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-28 12:31:18.115   937   937 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-28 12:31:18.115   937   937 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-28 12:31:18.115   937   937 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-28 12:31:18.115   937   937 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:18.115   937  1181 D TaskPersister: removeObsoleteFile: deleting file=99_task.xml
,07-28 12:31:18.115   937   937 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:18.115   937   937 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:31:18.115   937  1364 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:18.115   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 383us total 11.365ms
07-28 12:31:18.115   937   937 D SmartBondingService: SmartBondingReceiver: wifi is connected
07-28 12:31:18.115   937   937 D SmartBondingService: SmartBondingReceiver: wifi ap is not changed
07-28 12:31:18.115   937   937 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:18.115   937   937 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:18.115   937   937 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:18.115   937   937 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:18.115   937   937 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:31:18.115   937   937 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
,07-28 12:31:18.125   937  1156 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-28 12:31:18.125   937  1156 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:31:18.125   937  1156 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:31:18.125   937  1156 D SmartBondingService: getSBEnabled() enabled =false
,07-28 12:31:18.125   937  1156 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-28 12:31:18.125   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:31:18.125   937  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,07-28 12:31:18.135   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:31:18.135   937  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,07-28 12:31:18.135  8462  8462 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:31:18.135  8462  8462 D ActivityThread: Added TimaKeyStore provider
,07-28 12:31:18.145   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:31:18.145   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:31:18.145   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:31:18.155   937  1014 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,07-28 12:31:18.165   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:31:18.165  8462  8462 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,07-28 12:31:18.165   937  1014 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,07-28 12:31:18.165  1442  1442 D SurfaceWidgetView: destroyHardwareResources():153551175
,07-28 12:31:18.165   937   952 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-28 12:31:18.165   937   952 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-28 12:31:18.165   937   952 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-28 12:31:18.165   937   952 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-28 12:31:18.165   937   952 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,07-28 12:31:18.165   937  1253 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-28 12:31:18.165   937  1253 D SecContentProvider2: mCursor = null
,07-28 12:31:18.175  1442  1442 D Launcher: onRestart, Launcher: 99919077
,07-28 12:31:18.175  1442  1442 D Launcher: onStart, Launcher: 99919077
07-28 12:31:18.175  1442  1442 D Launcher.HomeView: onStart
,07-28 12:31:18.175  1442  1442 V ActivityThread: updateVisibility : ActivityRecord{d9971a9 token=android.os.BinderProxy@353cf587 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,07-28 12:31:18.175  1759  1775 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
,07-28 12:31:18.175  1759  2137 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
07-28 12:31:18.175  1759  2137 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,07-28 12:31:18.175   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:31:18.175   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:31:18.175   937  1014 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,07-28 12:31:18.185   937  1014 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-28 12:31:18.185   937  1014 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:31:18.185   937  1014 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-28 12:31:18.185   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:31:18.185   937  1014 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,07-28 12:31:18.195   267   267 I SurfaceFlinger: id=14 createSurf (1080x1920),1 flag=4, Mauncher
,07-28 12:31:18.195   937  1060 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-28 12:31:18.195   937  1060 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-28 12:31:18.195   937  1062 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-28 12:31:18.195   937  1062 D PointerIcon: setMouseCustomIcon IconType is same.101
07-28 12:31:18.195   937  1062 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-28 12:31:18.195   937  1062 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-28 12:31:18.215   937  1537 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-28 12:31:18.215  8462  8462 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-28 12:31:18.215  8462  8462 D elm:14491: ELMEngine.ELMEngine( context ).
,07-28 12:31:18.215   937  1537 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 7429 uid 10079
07-28 12:31:18.215   937  8480 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-28 12:31:18.215   937  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,07-28 12:31:18.225   937  3069 I SQLiteConnectionPool: exportDB...
,07-28 12:31:18.225  8462  8462 D elm:14491: MDMBridge.setEnterpriseBridge()
,07-28 12:31:18.225   937  1147 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,07-28 12:31:18.225   937  1147 D ActivityManager: caller:android.app.ApplicationThreadProxy@c1637f6, r.packageName :com.sec.esdk.elm
,07-28 12:31:18.235  8462  8462 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,07-28 12:31:18.235   937  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-28 12:31:18.235  3619  3619 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-28 12:31:18.235  3619  3619 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-28 12:31:18.235  3619  3619 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
07-28 12:31:18.235  3619  3619 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-28 12:31:18.235  3619  3619 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-28 12:31:18.235  3619  3619 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-28 12:31:18.235  3619  3619 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-28 12:31:18.235  3619  3619 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:31:18.235  3619  3619 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:31:18.235  3619  3619 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:31:18.235  3619  3619 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:31:18.235  3619  3619 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:31:18.235  3619  3619 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:31:18.235  3619  3619 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:31:18.235   937  1434 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.service.health, hostingType: broadcast
,07-28 12:31:18.235   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.235   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.235   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.235   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:31:18.245   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:31:18.245   937  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,07-28 12:31:18.255  8462  8462 D elm:14491: ElmAgentService : onCreate()
,07-28 12:31:18.255  8462  8482 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,07-28 12:31:18.255  8462  8482 D elm:14491: MainReceiver.listeningToPackageRemoved()
07-28 12:31:18.255  8462  8482 D elm:14491: MDMBridge.getInstance()
,07-28 12:31:18.255  8462  8482 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,07-28 12:31:18.255   937  1068 I art     : Explicit concurrent mark sweep GC freed 82396(5MB) AllocSpace objects, 15(240KB) LOS objects, 29% free, 37MB/53MB, paused 5.106ms total 340.028ms
,07-28 12:31:18.255  8462  8482 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,07-28 12:31:18.275  8483  8483 E Zygote  : MountEmulatedStorage()
07-28 12:31:18.275  8483  8483 E Zygote  : v2
07-28 12:31:18.275  8483  8483 I libpersona: KNOX_SDCARD checking this for 10021
07-28 12:31:18.275  8483  8483 I libpersona: KNOX_SDCARD not a persona
,07-28 12:31:18.285   937  1434 I ActivityManager: Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8483 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,07-28 12:31:18.285   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:31:18.285   937  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,07-28 12:31:18.295  8483  8483 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:31:18.295  8483  8483 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:31:18.295  8483  8483 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:31:18.295  8462  8462 D elm:14491: ElmAgentService : onDestroy().
,07-28 12:31:18.305   937  3069 I SQLiteConnectionPool: ...exportDB
,07-28 12:31:18.305   937  1062 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{6ed6d76 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t97} time:194484
,07-28 12:31:18.305   937  3069 D SSRM:aY : MSG_TYPE_APP_REMOVED::
,07-28 12:31:18.305   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:31:18.305   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-28 12:31:18.305   937  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,07-28 12:31:18.305   937  1154 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,07-28 12:31:18.315   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:31:18.315   937  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,07-28 12:31:18.315   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:31:18.315   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-28 12:31:18.315   937  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,07-28 12:31:18.325  8483  8483 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:31:18.325  8483  8483 D ActivityThread: Added TimaKeyStore provider
,07-28 12:31:18.325   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:31:18.325   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-28 12:31:18.325   937  1014 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,07-28 12:31:18.335   937  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:31:18.335   937  1014 D UsbSettingsManager: clearDefaults: com.test.thalitest
,07-28 12:31:18.335   937  1014 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-28 12:31:18.335   937  1014 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 12:31:18.335   937  1014 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:18.335   937  1014 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:31:18.335  8483  8483 D ResourcesManager: creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,07-28 12:31:18.345  8483  8483 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
,07-28 12:31:18.345  8483  8483 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
07-28 12:31:18.345  8483  8483 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
,07-28 12:31:18.355  7665  7665 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-28 12:31:18.355  7665  7665 I PCWCLIENTTRACE_PushUtil: sales region : global
07-28 12:31:18.355  7665  7665 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-28 12:31:18.355  7665  7665 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,07-28 12:31:18.365   937  1068 D PackageManager: delete codoeFile: 
,07-28 12:31:18.365   937  3040 D ActivityManager: startService callerProcessName:com.sec.android.app.shealth, calleePkgName: com.sec.android.app.shealth
,07-28 12:31:18.365   937  3040 D ActivityManager: caller:android.app.ApplicationThreadProxy@24758b0b, r.packageName :com.sec.android.app.shealth
,07-28 12:31:18.375   937  1068 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
,07-28 12:31:18.375   937  1068 I AASA_removePackage: UID=10079 Target=com.test.thalitest
,07-28 12:31:18.375   937  1068 D PackageManager: result of delete: 1{452570458}
,07-28 12:31:18.375  8444  8444 D AndroidRuntime: Shutting down VM
,07-28 12:31:18.375   937  1068 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-28 12:31:18.375   937  1068 D PackageManager: userId{-1}
07-28 12:31:18.375   937  1068 D PackageManager: andCode{true}
07-28 12:31:18.385   937  1434 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,07-28 12:31:18.385   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.385   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.385   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.385   937  1434 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:31:18.425  8502  8502 E Zygote  : MountEmulatedStorage()
07-28 12:31:18.425  8502  8502 E Zygote  : v2
07-28 12:31:18.425  8502  8502 I libpersona: KNOX_SDCARD checking this for 10043
07-28 12:31:18.425  8502  8502 I libpersona: KNOX_SDCARD not a persona
,07-28 12:31:18.425   937  1434 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8502 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:31:18.435   937  1068 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
,07-28 12:31:18.435   937  1068 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.435   937  1068 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.435   937  1068 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.435   937  1068 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:31:18.445  8502  8502 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:31:18.445  8502  8502 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:31:18.445  8502  8502 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,07-28 12:31:18.465  8502  8502 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:31:18.465  8502  8502 D ActivityThread: Added TimaKeyStore provider
,07-28 12:31:18.475  8517  8517 E Zygote  : MountEmulatedStorage()
07-28 12:31:18.475  8517  8517 E Zygote  : v2
07-28 12:31:18.475  8517  8517 I libpersona: KNOX_SDCARD checking this for 10007
07-28 12:31:18.475  8517  8517 I libpersona: KNOX_SDCARD not a persona
,07-28 12:31:18.485   937  1068 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8517 uid=10007 gids={50007, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,07-28 12:31:18.485  8517  8517 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:31:18.485  8517  8517 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:31:18.485   937  1666 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,07-28 12:31:18.485   937  1666 D ActivityManager: caller:android.app.ApplicationThreadProxy@10acbc01, r.packageName :com.samsung.android.app.galaxyfinder
07-28 12:31:18.485  8517  8517 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:31:18.495  8502  8502 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,07-28 12:31:18.505  8517  8517 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:31:18.505  8517  8517 D ActivityThread: Added TimaKeyStore provider
,07-28 12:31:18.515  8517  8517 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DefaultContainerService/DefaultContainerService.apk
,07-28 12:31:18.525  8502  8502 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,07-28 12:31:18.525  8502  8502 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,07-28 12:31:18.535  8502  8502 D SPPClientService: PushLog.txt file is not deleted.
07-28 12:31:18.535  8502  8502 D SPPClientService: PushLog.txt file is not deleted.
,07-28 12:31:18.535  8502  8502 D SPPClientService: ============PushLog. stop!
,07-28 12:31:18.535   937  1479 I ActivityManager: Killing 5693:com.android.calendar/u0a172 (adj 15): emptyCount ##41
,07-28 12:31:18.545   937  1242 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,07-28 12:31:18.555   937  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.555   937  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.555   937  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.555   937  1242 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:31:18.635  8536  8536 E Zygote  : MountEmulatedStorage()
07-28 12:31:18.635  8536  8536 E Zygote  : v2
07-28 12:31:18.635  8536  8536 I libpersona: KNOX_SDCARD checking this for 10048
07-28 12:31:18.635  8536  8536 I libpersona: KNOX_SDCARD not a persona
,07-28 12:31:18.645  8536  8536 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:31:18.645  8536  8536 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:31:18.645  8536  8536 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,07-28 12:31:18.645   937  1242 I ActivityManager: Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8536 uid=10048 gids={50048, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,07-28 12:31:18.645   937  1242 I ActivityManager: Killing 6871:com.android.providers.calendar/u0a51 (adj 15): emptyCount ##41
,07-28 12:31:18.665  8536  8536 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:31:18.665  8536  8536 D ActivityThread: Added TimaKeyStore provider
,07-28 12:31:18.675  8536  8536 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,07-28 12:31:18.685  8536  8536 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-28 12:31:18.685  8536  8536 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,07-28 12:31:18.775  8536  8536 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db" with flag (131138) and mode_t (0) due to error (30)
,07-28 12:31:18.775  8536  8536 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:465)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1716)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1685)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5555)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5150)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5090)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:31:18.775  8536  8536 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:31:18.775  8536  8536 D AndroidRuntime: Shutting down VM
,07-28 12:31:18.785  8536  8536 E AndroidRuntime: FATAL EXCEPTION: main
07-28 12:31:18.785  8536  8536 E AndroidRuntime: Process: com.samsung.android.sdk.samsunglink, PID: 8536
07-28 12:31:18.785  8536  8536 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5558)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5150)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5090)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:465)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1716)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1685)
07-,28 12:31:18.785  8536  8536 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5555)
07-28 12:31:18.785  8536  8536 E AndroidRuntime: 	... 11 more
,07-28 12:31:18.785   937  1666 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sdk.samsunglink
,07-28 12:31:18.785  8536  8536 I Process : Sending signal. PID: 8536 SIG: 9
,07-28 12:31:18.785  7832  7832 I SA      : [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,07-28 12:31:18.785   937  8552 E DropBoxManagerService: Can't write: system_app_crash
07-28 12:31:18.785   937  8552 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop206.tmp: open failed: EROFS (Read-only file system)
07-28 12:31:18.785   937  8552 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-28 12:31:18.785   937  8552 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:31:18.785   937  8552 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:31:18.785   937  8552 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 12:31:18.785   937  8552 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-28 12:31:18.785   937  8552 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
07-28 12:31:18.785   937  8552 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 12:31:18.785   937  8552 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 12:31:18.785   937  8552 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:31:18.785   937  8552 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-28 12:31:18.785   937  8552 E DropBoxManagerService: 	... 5 more
,07-28 12:31:18.785  7832  7832 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10079 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,07-28 12:31:18.795   937  1434 I ActivityManager: Killing 5544:com.sec.android.gallery3d/u0a53 (adj 15): emptyCount ##41
,07-28 12:31:18.795   937  1253 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,07-28 12:31:18.795   937  1253 D ActivityManager: caller:android.app.ApplicationThreadProxy@3928173d, r.packageName :com.android.providers.contacts
,07-28 12:31:18.805   264   264 E lowmemorykiller: Error writing /proc/8536/oom_score_adj; errno=22
,07-28 12:31:18.815   937  1125 I EventHub: Removing device '/dev/input/event6' due to inotify event
,07-28 12:31:18.825   937  1556 I ActivityManager: Process com.samsung.android.sdk.samsunglink (pid 8536)(adj 11) has died(359,1495)
,07-28 12:31:18.835   937  1017 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,07-28 12:31:18.835   937  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.835   937  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.835   937  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:18.835   937  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:31:18.855   937  1125 I EventHub: Removing device '/dev/input/event7' due to inotify event
,07-28 12:31:18.875   937  1017 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=8554 uid=10055 gids={50055, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,07-28 12:31:18.875  8554  8554 E Zygote  : MountEmulatedStorage()
07-28 12:31:18.875  8554  8554 E Zygote  : v2
07-28 12:31:18.875  8554  8554 I libpersona: KNOX_SDCARD checking this for 10055
07-28 12:31:18.875  8554  8554 I libpersona: KNOX_SDCARD not a persona
,07-28 12:31:18.905   937  1125 I EventHub: Removing device '/dev/input/event8' due to inotify event
,07-28 12:31:18.925  8554  8554 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:31:18.925  8554  8554 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-28 12:31:18.945  8554  8554 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:31:18.945  8554  8554 D ActivityThread: Added TimaKeyStore provider
,07-28 12:31:18.965   937  1125 I EventHub: Removing device '/dev/input/event9' due to inotify event
,07-28 12:31:18.965  8554  8554 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-28 12:31:18.975  8554  8554 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,07-28 12:31:18.975  8554  8554 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 12:31:18.975  8554  8554 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
07-28 12:31:18.975  8554  8554 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-28 12:31:18.975  8554  8554 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-28 12:31:18.975  8554  8554 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,07-28 12:31:18.975  8554  8554 W ContextImpl: Unable to create files subdir /data/data/com.android.mms/cache
,07-28 12:31:18.975  8554  8554 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,07-28 12:31:19.005  8554  8554 W         : Zip: inflate read failed (30320 vs 32768)
,07-28 12:31:19.005  8554  8554 D AndroidRuntime: Shutting down VM
,07-28 12:31:19.005  8554  8554 E AndroidRuntime: FATAL EXCEPTION: main
07-28 12:31:19.005  8554  8554 E AndroidRuntime: Process: com.android.mms, PID: 8554
07-28 12:31:19.005  8554  8554 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application com.android.mms.MmsApp: java.lang.ClassNotFoundException: Didn't find class "com.android.mms.MmsApp" on path: DexPathList[[zip file "/system/framework/imsmanager.jar", zip file "/system/framework/secvision.jar", zip file "/system/framework/twframework.jar", zip file "/system/framework/multiwindow.jar", zip file "/system/framework/com.google.android.maps.jar", zip file "/system/framework/minimode.jar", zip file "/system/priv-app/SecMms_Candy/SecMms_Candy.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:625)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: Caused by: java.lang.ClassNotFoundException: Didn't find class "com.android.mms.MmsApp" on path: DexPathList[[zip file "/system/framework/imsmanager.jar", zip file "/system/framework/secvision.jar", zip file "/system/framework/twframework.jar", zip file "/system/framework/multiwindow.jar", zip file "/system/framework/com.google.android.maps.jar", zip file "/system/framework/minimode.jar", zip file "/system/priv-app/SecMms_Candy/SecMms_Candy.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	at android.app.Instrumentation.newApplication(Instrumentation.java:988)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:620)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	... 10 more
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	Suppressed: java.io.IOException: Failed to extract 'classes.dex' from '/system/priv-app/SecMms_Candy/SecMms_Candy.apk': I/O Error
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFileNative(Native Method)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:80)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:59)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
07-28 12:31:19.005  8554  8554 E, AndroidRuntime: 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Native Method)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		... 10 more
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open file '/data/dalvik-cache/arm/system@priv-app@SecMms_Candy@SecMms_Candy.apk@classes.dex': Read-only file system
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		... 27 more
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/SecMms_Candy/SecMms_Candy.apk'
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		... 27 more
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/SecMms_Candy/arm/SecMms_Candy.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		... 27 more
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	Caused by: java.io.IOException: 
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 		... 27 more
07-28 12:31:19.005  8554  8554 E AndroidRuntime: 	Suppressed: java.lang.ClassNo
,07-28 12:31:19.015   937  1242 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.mms
,07-28 12:31:19.015   937  1017 I ActivityManager: Killing 6025:com.sec.android.app.controlpanel/u0a134 (adj 15): emptyCount ##41
,07-28 12:31:19.015   937  8569 E DropBoxManagerService: Can't write: system_app_crash
07-28 12:31:19.015   937  8569 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop207.tmp: open failed: EROFS (Read-only file system)
07-28 12:31:19.015   937  8569 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-28 12:31:19.015   937  8569 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:31:19.015   937  8569 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:31:19.015   937  8569 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 12:31:19.015   937  8569 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-28 12:31:19.015   937  8569 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
07-28 12:31:19.015   937  8569 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 12:31:19.015   937  8569 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 12:31:19.015   937  8569 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:31:19.015   937  8569 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-28 12:31:19.015   937  8569 E DropBoxManagerService: 	... 5 more
,07-28 12:31:19.015  8554  8554 I Process : Sending signal. PID: 8554 SIG: 9
,07-28 12:31:19.025   937   952 I TactileAssist: enable value -1
,07-28 12:31:19.025   937   952 I TactileAssist: internal enable value -1
07-28 12:31:19.025   937   952 I TactileAssist: intensity value -1
07-28 12:31:19.025   937   952 I TactileAssist: saveAppList value true
,07-28 12:31:19.025   937   952 I TactileAssist: List of disabled apps :
,07-28 12:31:19.025   937   952 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.android.settings/shared_prefs/com.android.settings_tactileassist.xml
,07-28 12:31:19.035   937  1147 D SettingsProvider: name = reading_mode_app_list
07-28 12:31:19.035   937  1666 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
07-28 12:31:19.035   937  1666 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:19.035   937  1666 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:19.035   937  1666 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:19.035   937  1666 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:31:19.045   937  1125 I EventHub: Removing device '/dev/input/event10' due to inotify event
,07-28 12:31:19.075  8570  8570 E Zygote  : MountEmulatedStorage()
07-28 12:31:19.075  8570  8570 I libpersona: KNOX_SDCARD checking this for 10064
07-28 12:31:19.075  8570  8570 E Zygote  : v2
07-28 12:31:19.075  8570  8570 I libpersona: KNOX_SDCARD not a persona
,07-28 12:31:19.085   937  1666 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=8570 uid=10064 gids={50064, 9997, 3003, 3002} abi=armeabi-v7a
,07-28 12:31:19.095   937  1125 I EventHub: Removing device '/dev/input/event11' due to inotify event
,07-28 12:31:19.105  8570  8570 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:31:19.105  8570  8570 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-28 12:31:19.105   937  1472 I ActivityManager: Process com.android.mms (pid 8554)(adj 9) has died(363,1496)
,07-28 12:31:19.125  8570  8570 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:31:19.125  8570  8570 D ActivityThread: Added TimaKeyStore provider
,07-28 12:31:19.135  8570  8570 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,07-28 12:31:19.145  8570  8570 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,07-28 12:31:19.145  8570  8570 W ContextImpl: Unable to create files subdir /data/data/com.sec.android.app.soundalive/cache
07-28 12:31:19.145  8570  8570 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,07-28 12:31:19.155   937  1125 I EventHub: Removing device '/dev/input/event12' due to inotify event
,07-28 12:31:19.155  8570  8570 W         : Zip: inflate read failed (14358 vs 32768)
,07-28 12:31:19.155  8570  8570 D AndroidRuntime: Shutting down VM
,07-28 12:31:19.155  8570  8570 E AndroidRuntime: FATAL EXCEPTION: main
07-28 12:31:19.155  8570  8570 E AndroidRuntime: Process: com.sec.android.app.soundalive, PID: 8570
07-28 12:31:19.155  8570  8570 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate receiver com.sec.android.app.soundalive.compatibility.Compatibility$Receiver: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.app.soundalive.compatibility.Compatibility$Receiver" on path: DexPathList[[zip file "/system/framework/multiwindow.jar", zip file "/system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2970)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.app.soundalive.compatibility.Compatibility$Receiver" on path: DexPathList[[zip file "/system/framework/multiwindow.jar", zip file "/system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2965)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	... 9 more
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	Suppressed: java.io.IOException: Failed to extract 'classes.dex' from '/system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk': I/O Error
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFileNative(Native Method)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:80)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:59)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Native Method),
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		... 7 more
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open file '/data/dalvik-cache/arm/system@priv-app@SoundAlive_20_L@SoundAlive_20_L.apk@classes.dex': Read-only file system
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		... 27 more
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk'
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		... 27 more
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/SoundAlive_20_L/arm/SoundAlive_20_L.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		... 27 more
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	Caused by: java.io.IOException: 
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		... 27 more
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 	Suppressed: java.lang.ClassNotFoundException: com.sec.android.app.soundalive.compatibility.Compatibility$Receiver
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at java.lang.Class.classForName(Native Method)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
07-28 12:31:19.155  8570  8570 E AndroidRuntime: 		a
07-28 12:31:19.155   937  1253 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
07-28 12:31:19.155   937  1253 D ActivityManager: caller:android.app.ApplicationThreadProxy@703ea39, r.packageName :com.google.android.googlequicksearchbox
,07-28 12:31:19.165   937  1666 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.soundalive
,07-28 12:31:19.165  8570  8570 I Process : Sending signal. PID: 8570 SIG: 9
,07-28 12:31:19.165   937  8586 E DropBoxManagerService: Can't write: system_app_crash
07-28 12:31:19.165   937  8586 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop208.tmp: open failed: EROFS (Read-only file system)
07-28 12:31:19.165   937  8586 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-28 12:31:19.165   937  8586 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:31:19.165   937  8586 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:31:19.165   937  8586 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 12:31:19.165   937  8586 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-28 12:31:19.165   937  8586 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
07-28 12:31:19.165   937  8586 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 12:31:19.165   937  8586 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 12:31:19.165   937  8586 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:31:19.165   937  8586 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-28 12:31:19.165   937  8586 E DropBoxManagerService: 	... 5 more
,07-28 12:31:19.165  1587  8585 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-28 12:31:19.175  5385  5385 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
07-28 12:31:19.175  5385  5385 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131072) and mode_t (0) due to error (2)
07-28 12:31:19.175  5385  5385 E SQLiteLog: (14) cannot open file at line 32509 of [b3bb660af9]
07-28 12:31:19.175  5385  5385 E SQLiteLog: (14) os_unix.c:32509: (2) open(/data/data/com.samsung.android.sm/databases/history.db) - 
,07-28 12:31:19.185  5385  5385 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/history.db'.
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:31:19.185  5385  5385 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,07-28 12:31:19.185  5385  5385 D AndroidRuntime: Shutting down VM
,07-28 12:31:19.185  5385  5385 E AndroidRuntime: FATAL EXCEPTION: main
07-28 12:31:19.185  5385  5385 E AndroidRuntime: Process: com.samsung.android.sm, PID: 5385
07-28 12:31:19.185  5385  5385 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2996)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
07-28 12:31:19.185  5385  5385 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-28 12:31,:19.185  5385  5385 E AndroidRuntime: 	... 9 more
07-28 12:31:19.185   937  1147 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
,07-28 12:31:19.185  5385  5385 I Process : Sending signal. PID: 5385 SIG: 9
,07-28 12:31:19.195   937  8587 E DropBoxManagerService: Can't write: system_app_crash
07-28 12:31:19.195   937  8587 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop209.tmp: open failed: EROFS (Read-only file system)
07-28 12:31:19.195   937  8587 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-28 12:31:19.195   937  8587 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:31:19.195   937  8587 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:31:19.195   937  8587 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 12:31:19.195   937  8587 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-28 12:31:19.195   937  8587 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
07-28 12:31:19.195   937  8587 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 12:31:19.195   937  8587 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 12:31:19.195   937  8587 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:31:19.195   937  8587 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-28 12:31:19.195   937  8587 E DropBoxManagerService: 	... 5 more
,07-28 12:31:19.215   937  1125 I EventHub: Removing device '/dev/input/event13' due to inotify event
,07-28 12:31:19.225   937  1648 I ActivityManager: Process com.sec.android.app.soundalive (pid 8570)(adj 9) has died(365,1496)
,07-28 12:31:19.235   937  1472 I ActivityManager: Process com.samsung.android.sm (pid 5385)(adj 0) has died(368,1496)
,07-28 12:31:19.235   937  1017 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,07-28 12:31:19.235   937  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:19.235   937  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:19.235   937  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:19.235   937  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:31:19.235  1587  8585 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-28 12:31:19.235  1587  8585 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,07-28 12:31:19.245  1587  8585 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xa0302e20 in tid 8585 (IntentService[U)
,07-28 12:31:19.255   937  1125 I EventHub: Removing device '/dev/input/event14' due to inotify event
,07-28 12:31:19.275   937  1017 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=8588 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-28 12:31:19.275  8588  8588 E Zygote  : MountEmulatedStorage()
07-28 12:31:19.275  8588  8588 E Zygote  : v2
07-28 12:31:19.275  8588  8588 I libpersona: KNOX_SDCARD checking this for 1000
07-28 12:31:19.275  8588  8588 I libpersona: KNOX_SDCARD not a persona
,07-28 12:31:19.295   299   299 I DEBUG   : failed to create /data/tombstones: Read-only file system
07-28 12:31:19.295   299   299 I DEBUG   : failed to open /data/tombstones: No such file or directory
07-28 12:31:19.295   299   299 E         : ro.product_ship = true
07-28 12:31:19.295   299   299 E         : ro.debug_level = 0x4f4c
,07-28 12:31:19.295  1816  1816 E audit_log: File locking failed. error= Bad file number
,07-28 12:31:19.325  8588  8588 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:31:19.325  8588  8588 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:31:19.355  8588  8588 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:31:19.355  8588  8588 D ActivityThread: Added TimaKeyStore provider
,07-28 12:31:19.355   937   954 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 1587)(adj 1) has died(379,1496)
,07-28 12:31:19.355   937   954 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService in 1000ms
07-28 12:31:19.355   937   954 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 11000ms
,07-28 12:31:19.365  8588  8588 D ResourcesManager: creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
,07-28 12:31:19.375  8588  8588 W ContextImpl: Unable to create files subdir /data/data/com.samsung.android.app.assistantmenu/cache
07-28 12:31:19.375  8588  8588 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,07-28 12:31:19.375  8588  8588 W         : Zip: inflate read failed (14029 vs 32768)
,07-28 12:31:19.375  8588  8588 D AndroidRuntime: Shutting down VM
,07-28 12:31:19.385  7180  7180 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,07-28 12:31:19.385   937  1471 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
07-28 12:31:19.385   937  1471 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,07-28 12:31:19.385  8588  8588 E AndroidRuntime: FATAL EXCEPTION: main
07-28 12:31:19.385  8588  8588 E AndroidRuntime: Process: com.samsung.android.app.assistantmenu, PID: 8588
07-28 12:31:19.385  8588  8588 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate receiver com.samsung.android.app.assistantmenu.AssistantMenuReceiver: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.app.assistantmenu.AssistantMenuReceiver" on path: DexPathList[[zip file "/system/app/AssistantMenu2/AssistantMenu2.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2970)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: Caused by: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.app.assistantmenu.AssistantMenuReceiver" on path: DexPathList[[zip file "/system/app/AssistantMenu2/AssistantMenu2.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2965)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	... 9 more
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	Suppressed: java.io.IOException: Failed to extract 'classes.dex' from '/system/app/AssistantMenu2/AssistantMenu2.apk': I/O Error
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFileNative(Native Method)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:80)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:59)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Native Method)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:31:19.385  8588,  8588 E AndroidRuntime: 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		... 7 more
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open file '/data/dalvik-cache/arm/system@app@AssistantMenu2@AssistantMenu2.apk@classes.dex': Read-only file system
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		... 27 more
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/app/AssistantMenu2/AssistantMenu2.apk'
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		... 27 more
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from /system/app/AssistantMenu2/arm/AssistantMenu2.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		... 27 more
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	Caused by: java.io.IOException: 
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		... 27 more
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	Suppressed: java.lang.ClassNotFoundException: com.samsung.android.app.assistantmenu.AssistantMenuReceiver
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at java.lang.Class.classForName(Native Method)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 		... 11 more
07-28 12:31:19.385  8588  8588 E AndroidRuntime: 	Caused by: java.lang.NoCl
,07-28 12:31:19.385   937  1556 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.assistantmenu
,07-28 12:31:19.395   937  8603 E DropBoxManagerService: Can't write: system_app_crash
07-28 12:31:19.395   937  8603 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop210.tmp: open failed: EROFS (Read-only file system)
07-28 12:31:19.395   937  8603 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-28 12:31:19.395   937  8603 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:31:19.395   937  8603 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:31:19.395   937  8603 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 12:31:19.395   937  8603 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-28 12:31:19.395   937  8603 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
07-28 12:31:19.395   937  8603 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 12:31:19.395   937  8603 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 12:31:19.395   937  8603 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:31:19.395   937  8603 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-28 12:31:19.395   937  8603 E DropBoxManagerService: 	... 5 more
,07-28 12:31:19.395  8588  8588 I Process : Sending signal. PID: 8588 SIG: 9
,07-28 12:31:19.395   937  1147 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,07-28 12:31:19.395   937  1147 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:19.395   937  1147 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:19.395   937  1147 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:31:19.395   937  1147 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:31:19.435  8604  8604 E Zygote  : MountEmulatedStorage()
07-28 12:31:19.435  8604  8604 E Zygote  : v2
07-28 12:31:19.435  8604  8604 I libpersona: KNOX_SDCARD checking this for 10112
07-28 12:31:19.435  8604  8604 I libpersona: KNOX_SDCARD not a persona
,07-28 12:31:19.435   937  1147 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8604 uid=10112 gids={50112, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:31:19.445   264   264 E lowmemorykiller: Error writing /proc/8588/oom_score_adj; errno=22
,07-28 12:31:19.465  8604  8604 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:31:19.465   937  1737 I ActivityManager: Process com.samsung.android.app.assistantmenu (pid 8588)(adj 11) has died(380,1496)
,07-28 12:31:19.465  8604  8604 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-28 12:31:19.485  8604  8604 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:31:19.485  8604  8604 D ActivityThread: Added TimaKeyStore provider
,07-28 12:31:19.485   937  3105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-28 12:31:19.495   267   531 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-28 12:31:19.505  8604  8604 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,07-28 12:31:19.515  8604  8604 W ContextImpl: Unable to create files subdir /data/data/com.google.android.apps.docs/cache
07-28 12:31:19.515  8604  8604 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,07-28 12:31:19.515  8604  8604 W         : Zip: inflate read failed (31654 vs 32768)
,07-28 12:31:19.515  8604  8604 D AndroidRuntime: Shutting down VM
,07-28 12:31:19.525  8604  8604 E AndroidRuntime: FATAL EXCEPTION: main
07-28 12:31:19.525  8604  8604 E AndroidRuntime: Process: com.google.android.apps.docs, PID: 8604
07-28 12:31:19.525  8604  8604 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application com.google.android.apps.docs.drive.DriveApplication: java.lang.ClassNotFoundException: Didn't find class "com.google.android.apps.docs.drive.DriveApplication" on path: DexPathList[[zip file "/system/app/Drive/Drive.apk"],nativeLibraryDirectories=[/system/app/Drive/lib/arm, /vendor/lib, /system/lib]]
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:625)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: Caused by: java.lang.ClassNotFoundException: Didn't find class "com.google.android.apps.docs.drive.DriveApplication" on path: DexPathList[[zip file "/system/app/Drive/Drive.apk"],nativeLibraryDirectories=[/system/app/Drive/lib/arm, /vendor/lib, /system/lib]]
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	at android.app.Instrumentation.newApplication(Instrumentation.java:988)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:620)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	... 10 more
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 	Suppressed: java.io.IOException: Failed to extract 'classes.dex' from '/system/app/Drive/Drive.apk': I/O Error
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFileNative(Native Method)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:80)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:59)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
07-28 12:31:19.525  8604  8604 E AndroidRuntime: 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
07-28 12:31:19.525  8604  8
```
