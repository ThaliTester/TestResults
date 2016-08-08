#### Test 79689775d0c6cb6_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
08-08 16:37:38.252   304   304 E SMD     : DCD ON
,08-08 16:37:40.131  7499  7499 D AndroidRuntime: 
08-08 16:37:40.131  7499  7499 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-08 16:37:40.131  7499  7499 D AndroidRuntime: CheckJNI is OFF
08-08 16:37:40.131  7499  7499 D AndroidRuntime: readGMSProperty: start
08-08 16:37:40.131  7499  7499 D AndroidRuntime: readGMSProperty: already setted!!
08-08 16:37:40.131  7499  7499 D AndroidRuntime: readGMSProperty: end
08-08 16:37:40.131  7499  7499 D AndroidRuntime: addProductProperty: start
08-08 16:37:40.321  7499  7499 E AffinityControl: AffinityControl: registerfunction enter
08-08 16:37:40.351  7499  7499 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-08 16:37:40.361   750  1468 E PersonaManagerService: inState():  stateMachine is null !!
08-08 16:37:40.361   750  1468 I PersonaManagerService: PersonaId don't exist
08-08 16:37:40.361   750  1468 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-08 16:37:40.361   750  1468 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-08 16:37:40.361   750  1468 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-08 16:37:40.361   750  1468 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
08-08 16:37:40.371   750  1468 W ActivityManager: mDVFSHelper.acquire()
08-08 16:37:40.371   750  1468 D FocusedStackFrame: Set to : 0
08-08 16:37:40.371   750  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-08 16:37:40.371   750  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-08 16:37:40.371   750  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-08 16:37:40.371   750  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-08 16:37:40.411   750  1468 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7515 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-08 16:37:40.421  7515  7515 E Zygote  : MountEmulatedStorage()
08-08 16:37:40.421  7515  7515 I libpersona: KNOX_SDCARD checking this for 10079
08-08 16:37:40.421  7515  7515 E Zygote  : v2
08-08 16:37:40.421  7515  7515 I libpersona: KNOX_SDCARD not a persona
08-08 16:37:40.431  7515  7515 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-08 16:37:40.431  7515  7515 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-08 16:37:40.431  7515  7515 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-08 16:37:40.431   750  1042 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-08 16:37:40.431   750  1042 D PointerIcon: setMouseCustomIcon IconType is same.101
08-08 16:37:40.431   750  1042 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-08 16:37:40.431   750  1042 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-08 16:37:40.441  7499  7499 D AndroidRuntime: Shutting down VM
08-08 16:37:40.461  7515  7515 D TimaKeyStoreProvider: TimaSignature is unavailable
08-08 16:37:40.461  7515  7515 D ActivityThread: Added TimaKeyStore provider
08-08 16:37:40.471   750  1694 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-08 16:37:40.471   750  1694 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-08 16:37:40.471   750  1694 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-08 16:37:40.471   750  1694 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-08 16:37:40.471   750  1694 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-08 16:37:40.501  1439  1439 D SurfaceWidgetView: destroyHardwareResources():853406383
08-08 16:37:40.501   750  3286 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 16:37:40.511  7515  7515 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
08-08 16:37:40.511   750  3286 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 16:37:40.561   266   319 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
08-08 16:37:40.561   266  1447 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
08-08 16:37:40.571  1439  1439 V ActivityThread: updateVisibility : ActivityRecord{f560dd1 token=android.os.BinderProxy@1533cde8 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-08 16:37:40.571  1439  1439 D Launcher: onTrimMemory. Level: 20
08-08 16:37:40.571  1772  1784 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
08-08 16:37:40.611  7515  7515 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-08 16:37:40.611  7515  7515 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
08-08 16:37:40.621  7515  7515 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8656-8659)
08-08 16:37:40.631  7515  7515 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 16:37:40.651  7515  7515 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {187a6b51}
08-08 16:37:40.651  7515  7515 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 16:37:40.651  7515  7515 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-08 16:37:40.681  7515  7515 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-08 16:37:40.681  7515  7515 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-08 16:37:40.681  7515  7515 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-08 16:37:40.701  7515  7515 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-08 16:37:40.701  7515  7515 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
08-08 16:37:40.701  7515  7515 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,08-08 16:37:40.701  7515  7515 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
08-08 16:37:40.701  7515  7515 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
08-08 16:37:40.701  7515  7515 I Adreno-EGL: Build Date: 11/19/14 Wed
08-08 16:37:40.701  7515  7515 I Adreno-EGL: Local Branch: mybranch5813579
08-08 16:37:40.701  7515  7515 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
08-08 16:37:40.701  7515  7515 I Adreno-EGL: Local Patches: NONE
08-08 16:37:40.701  7515  7515 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,08-08 16:37:40.841  7515  7553 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-08 16:37:40.871  7515  7515 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-08 16:37:40.881  7515  7515 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-08 16:37:40.891  7515  7515 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-08 16:37:40.901  7515  7515 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-08 16:37:40.901  7515  7515 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-08 16:37:40.941  7515  7515 D Activity: performCreate Call secproduct feature valuefalse
,08-08 16:37:40.941   750  1345 E Watchdog: !@Sync 11
,08-08 16:37:40.951  7515  7515 D Activity: performCreate Call debug elastic valuetrue
,08-08 16:37:40.961  7515  7572 D OpenGLRenderer: Render dirty regions requested: true
,08-08 16:37:40.961   750  1674 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-08 16:37:40.961   750  1674 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-08 16:37:40.961   750  1674 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-08 16:37:40.961   750   750 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-08 16:37:40.961   750   750 D PersonaManagerService: getPersonasForUser(): returning null!
,08-08 16:37:40.981   266   266 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,08-08 16:37:40.981   750  1037 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-08 16:37:40.991   750  1037 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-08 16:37:40.991   750  1042 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-08 16:37:40.991   750  1042 D PointerIcon: setMouseCustomIcon IconType is same.101
08-08 16:37:40.991   750  1042 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-08 16:37:40.991   750  1042 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-08 16:37:40.991  7515  7572 I OpenGLRenderer: Initialized EGL, version 1.4
,08-08 16:37:41.001  7515  7572 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0x9e507060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,08-08 16:37:41.001  7515  7572 D OpenGLRenderer: Enabling debug mode 0
,08-08 16:37:41.021  7515  7515 V ActivityThread: updateVisibility : ActivityRecord{242ae943 token=android.os.BinderProxy@2a9951fd {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-08 16:37:41.051   750  1373 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-08 16:37:41.051   750  7576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-08 16:37:41.061  7515  7515 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2a9951fd time:349092
,08-08 16:37:41.061  7515  7515 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-08 16:37:41.061  1744  1744 I SamsungIME: getCurrentCandidateView
,08-08 16:37:41.071   750  1042 W ActivityManager: mDVFSHelper.release()
,08-08 16:37:41.071   750  1042 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{35a4ddc4 u0 com.test.thalitest/.MainActivity t99} time:349102
,08-08 16:37:41.111  7515  7515 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7515
,08-08 16:37:41.121  1744  1744 D SamsungIME: Dismiss ExpandCandiate
,08-08 16:37:41.191  7515  7515 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-08 16:37:41.211  1744  1744 I SamsungIME: getDebugLevel  : 0x4f4c
,08-08 16:37:41.241  1744  1744 I SamsungIME: getDebugLevel  : 0x4f4c
,08-08 16:37:41.241   304   304 E SMD     : DCD ON
,08-08 16:37:41.261  1744  1744 I SamsungIME: KeybaordView init() : load resources
,08-08 16:37:41.281  1744  1744 I SamsungIME: getCurrentKeyboard
08-08 16:37:41.281  1744  1744 I SamsungIME: getTextKeyboard
,08-08 16:37:41.291  1744  1744 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-08 16:37:41.291  7515  7578 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258385280
,08-08 16:37:41.301  7515  7578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-08 16:37:41.301  7515  7578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-08 16:37:41.301  7515  7578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-08 16:37:41.301  7515  7578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-08 16:37:41.301  7515  7578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-08 16:37:41.301  7515  7578 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dc8a933 added. We now have 1 listener(s)
,08-08 16:37:41.311  7515  7578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:1F:C9:5E
,08-08 16:37:41.311  7515  7578 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-08 16:37:41.311  7515  7578 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-08 16:37:41.311  7515  7578 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-08 16:37:41.321  7515  7578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-08 16:37:41.321  7515  7578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-08 16:37:41.321  7515  7578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-08 16:37:41.321  7515  7578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:1F:C9:5E
08-08 16:37:41.321  7515  7578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-08 16:37:41.321  7515  7578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-08 16:37:41.321  7515  7578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-08 16:37:41.321  7515  7578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-08 16:37:41.321  7515  7578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-08 16:37:41.321  7515  7578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-08 16:37:41.321  7515  7578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-08 16:37:41.321  7515  7578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-08 16:37:41.321  7515  7578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-08 16:37:41.321  7515  7578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-08 16:37:41.321  7515  7578 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3cee added. We now have 1 listener(s)
08-08 16:37:41.321  7515  7578 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 16:37:41.331  7515  7578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-08 16:37:41.331  7515  7578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-08 16:37:41.331  7515  7578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-08 16:37:41.331  7515  7578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-08 16:37:41.331  7515  7578 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-08 16:37:41.331  7515  7578 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-08 16:37:41.331  7515  7578 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:1F:C9:5E
,08-08 16:37:41.341   750  1143 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-08 16:37:41.341  7515  7578 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-08 16:37:41.341  7515  7578 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 16:37:41.341  7515  7578 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 16:37:41.341  7515  7578 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-08 16:37:41.341  7515  7578 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 16:37:41.341  7515  7578 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 16:37:41.341  7515  7578 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 16:37:41.341  7515  7578 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 16:37:41.341  7515  7578 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 16:37:41.341  7515  7578 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-08 16:37:41.341  7515  7578 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-08 16:37:41.351  7515  7578 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-08 16:37:41.351   750  1475 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-08 16:37:41.351  7515  7515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 16:37:41.351   750  1694 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-08 16:37:41.351  7515  7515 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 16:37:41.371  7515  7515 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-08 16:37:41.491   750  1115 V AlarmManager: waitForAlarm result :4
,08-08 16:37:41.491   750  1115 D ActivityManager: caller:null, r.packageName :com.google.android.gms
,08-08 16:37:41.521   750  1475 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-08 16:37:41.531   750  1475 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4313, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
08-08 16:37:41.531   750  1475 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
08-08 16:37:41.531   750   750 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-08 16:37:41.531   750  1475 D BatteryService: stay LED for fully charged
,08-08 16:37:41.531   750   750 I MotionRecognitionService: Plugged
08-08 16:37:41.531   750   750 I MotionRecognitionService: setPowerConnected  = true
,08-08 16:37:41.531  1187  1187 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-08 16:37:41.531  1187  1187 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-08 16:37:41.531  1187  1187 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,08-08 16:37:41.531  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-08 16:37:41.531  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-08 16:37:41.531  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-08 16:37:41.531  3212  3212 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-08 16:37:41.531  3212  3283 D HeadsetStateMachine: Disconnected process message: 10
,08-08 16:37:41.601   750  3286 D SSRM:n  : SIOP:: AP = 320, PST = 311, CUR = 450
,08-08 16:37:41.631   750  1467 I art     : Explicit concurrent mark sweep GC freed 51592(3MB) AllocSpace objects, 75(1200KB) LOS objects, 29% free, 37MB/53MB, paused 1.495ms total 119.237ms
,08-08 16:37:41.631   750  1467 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:41.641  4583  7594 I MS_RegisterService: RegisterService intent:Intent { act=com.google.android.gms.matchstick.register_intent_action (has extras) } isPeriodic:false
,08-08 16:37:41.651  1744  7587 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-08 16:37:41.651   750   767 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:41.661  4583  7594 I MS_RegisterService: Phone type: 1
,08-08 16:37:41.661   750  1674 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-08 16:37:41.661  4583  7594 I MS_RegisterService: Doing full registration.
08-08 16:37:41.671   750  1650 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:41.671   750  1430 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:41.681   750  1455 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:41.691   750  1650 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:41.691   750  1475 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:41.701   750  1373 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:41.701   750  1522 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:41.711   750  1455 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:41.711   750  1143 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:41.721   750   767 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:41.721   750  1582 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:41.731   750  1522 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:41.741   750  1373 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:41.751   750  1582 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:41.751   750  1455 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:41.761  4583  7594 I MS_RegisterService: Throttling registration.
,08-08 16:37:41.761  4583  7594 W MS_WakeLockHelper: Call to release wakelock: register_service_start_wakelock, but not held.
08-08 16:37:41.761   750  1555 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-08 16:37:41.761   750  1555 D ActivityManager: caller:android.app.ApplicationThreadProxy@aefaa, r.packageName :com.google.android.gms
,08-08 16:37:42.311  7515  7592 W jxcore-log: Initializing JXcore engine
,08-08 16:37:42.311  7515  7592 W jxcore-log: JXcore engine is ready
,08-08 16:37:42.361  1836  1836 E auditd  : In denial and Property audit_ondenial is set to 1 
,08-08 16:37:42.361  1836  1836 E audit   : type=1400 msg=audit(1470667062.361:203): avc:  denied  { ioctl } for  pid=7592 comm="Thread-1234" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3089 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-08 16:37:42.361  1836  1836 E audit   :  SEPF_SM-N9005_5.0-1_0032
08-08 16:37:42.361  1836  1836 E audit   : 
08-08 16:37:42.361  1836  1836 E audit   : type=1300 msg=audit(1470667062.361:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=1 a3=99ae08d8 items=0 ppid=352 ppcomm=main pid=7592 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1234" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-08 16:37:42.361  1836  1836 E audit   : type=1320 msg=audit(1470667062.361:203): 
08-08 16:37:42.361   750  1029 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
,08-08 16:37:42.371   750  1029 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,08-08 16:37:42.371   750   955 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-08 16:37:42.371   750   955 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-08 16:37:42.371   750  1029 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
08-08 16:37:42.371   750   955 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-08 16:37:42.371   750   955 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-08 16:37:42.371   750   955 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-08 16:37:42.381  7515  7592 W jxcore-log: Starting JXcore engine
,08-08 16:37:42.411  7607  7607 E Zygote  : MountEmulatedStorage()
,08-08 16:37:42.411  7607  7607 E Zygote  : v2
08-08 16:37:42.411  7607  7607 I libpersona: KNOX_SDCARD checking this for 1000
08-08 16:37:42.411   750   955 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7607 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-08 16:37:42.411  7607  7607 I libpersona: KNOX_SDCARD not a persona
,08-08 16:37:42.431   352   352 I art     : Explicit concurrent mark sweep GC freed 8782(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 330us total 25.788ms
,08-08 16:37:42.441   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 275us total 9.567ms
,08-08 16:37:42.441  7607  7607 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-08 16:37:42.451  7607  7607 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-08 16:37:42.451  7607  7607 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-08 16:37:42.471   367   367 I ServiceManager: Waiting for service AtCmdFwd...
,08-08 16:37:42.471  7607  7607 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-08 16:37:42.481  7607  7607 D ActivityThread: Added TimaKeyStore provider
,08-08 16:37:42.481   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 401us total 33.592ms
,08-08 16:37:42.481  7515  7592 W jxcore-log: Platform android
08-08 16:37:42.481  7515  7592 W jxcore-log: 
08-08 16:37:42.481  7515  7592 W jxcore-log: Process ARCH arm
08-08 16:37:42.481  7515  7592 W jxcore-log: 
,08-08 16:37:42.501  7607  7607 D ResourcesManager: creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,08-08 16:37:42.511  7607  7607 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,08-08 16:37:42.511  7607  7607 D SecurityLogAgent:  SeDenialReceiver : File path = null
,08-08 16:37:42.711  7515  7592 I jxcore-log: JXcore Cordova bridge is ready!
08-08 16:37:42.711  7515  7592 I jxcore-log: 
08-08 16:37:42.711  7515  7592 W jxcore-log: JXcore engine is started
,08-08 16:37:42.721  7515  7578 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-08 16:37:42.721  7515  7515 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-08 16:37:43.471   367   367 I ServiceManager: Waiting for service AtCmdFwd...
,08-08 16:37:44.251   304   304 E SMD     : DCD ON
,08-08 16:37:44.471   367   367 I ServiceManager: Waiting for service AtCmdFwd...
,08-08 16:37:45.181   750  1048 I PowerManagerService: [PWL] Off : 275s ago
,08-08 16:37:45.471   367   367 I ServiceManager: Waiting for service AtCmdFwd...
,08-08 16:37:46.471   367   367 I ServiceManager: Waiting for service AtCmdFwd...
,08-08 16:37:47.251   304   304 E SMD     : DCD ON,
,08-08 16:37:47.471   367   367 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-08 16:37:48.041   750  3321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-08 16:37:48.791   750  1650 I ActivityManager: Killing 6482:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 15): emptyCount ##41
,08-08 16:37:49.941  6266  6295 I PlayCommon: [1054] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-08 16:37:49.951   750  1582 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-08 16:37:49.951   750  1430 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-08 16:37:49.961  1850  1850 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-08 16:37:49.961   750  1455 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-08 16:37:49.971  1850  1850 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-08 16:37:49.971  1850  1850 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-08 16:37:50.001  6266  6295 I PlayCommon: [1054] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,08-08 16:37:50.001  6266  6295 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-08 16:37:50.011  6266  6295 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-08 16:37:50.241  6266  6295 I PlayCommon: [1054] com.google.android.play.a.al.a(945): Successfully uploaded logs.
,08-08 16:37:50.251   304   304 E SMD     : DCD ON
,08-08 16:37:50.391   750  1064 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-08 16:37:51.601   750  1455 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-08 16:37:51.601   750  1455 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
08-08 16:37:51.601   750  1455 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
08-08 16:37:51.601   750  1455 D BatteryService: stay LED for fully charged
08-08 16:37:51.601   750   750 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-08 16:37:51.601   750   750 I MotionRecognitionService: Plugged
08-08 16:37:51.601   750   750 I MotionRecognitionService: setPowerConnected  = true
,08-08 16:37:51.601  1187  1187 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-08 16:37:51.601  1187  1187 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-08 16:37:51.611  1187  1187 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,08-08 16:37:51.611  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-08 16:37:51.611  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-08 16:37:51.611  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-08 16:37:51.611  3212  3212 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-08 16:37:51.611  3212  3283 D HeadsetStateMachine: Disconnected process message: 10
,08-08 16:37:51.661   750  3286 D SSRM:n  : SIOP:: AP = 360, PST = 316, CUR = 450
,08-08 16:37:53.251   304   304 E SMD     : DCD ON
,08-08 16:37:56.251   304   304 E SMD     : DCD ON

```
